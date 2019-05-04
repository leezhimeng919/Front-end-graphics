#Web 图形学
- Canvas
- CSS

#Web 3D
- Canvas 3D
    + 点
        * 3D标签云就是做一个球面，然后再球面上取均匀分布的点，把点坐标赋给标签，再根据抽象出来的Z轴大小来改变标签的字体大小，透明度，做出立体感觉，然后球体就做好了
        ```javascript
        function innit(){
            for(var i=0;i<tagEle.length;i++){
                var a , b;
                var k = -1+(2*(i+1)-1)/tagEle.length;
                var a = Math.acos(k);
                var b = a*Math.sqrt(tagEle.length*Math.PI);
                // var a = Math.random()*2*Math.PI;
                // var b = Math.random()*2*Math.PI;
                var x = RADIUS * Math.sin(a) * Math.cos(b);
                var y = RADIUS * Math.sin(a) * Math.sin(b); 
                var z = RADIUS * Math.cos(a);
                var t = new tag(tagEle[i] , x , y , z);
                tagEle[i].style.color = "rgb("+parseInt(Math.random()*255)+","+parseInt(Math.random()*255)+","+parseInt(Math.random()*255)+")";
                tags.push(t);
                t.move();
            }
        }
        ```
    + 线
        * 如果知道怎么做点之后，线也就容易了，只要把点连起来就行了。这个没做DEMO，不过也确实不难。就循环moveTo，然后lineTo，线就出来了
    + 面
        * 点对象，面对象，以及立方体本身一个对象：下面这个是点对象，x,y,z是点的三维坐标，_get2d方法是把三维坐标转换到二维层面来。fallLength是焦距。
        * 
        ``` javascript
        var Vector = function(x,y,z){
            this.x = x;
            this.y = y;
            this.z = z;
            this._get2d = function(){
                var scale = fallLength/(fallLength+this.z);
                var x = centerX + this.x*scale;
                var y = centerY + this.y*scale;
                return {x:x , y:y};
            }
        }
        ```
        ```javascript
        var Face = function(vector1,vector2,vector3,vector4,color){
            this.v1 = vector1;
            this.v2 = vector2;
            this.v3 = vector3;
            this.v4 = vector4;
            this.color = color;
            this.zIndex = (this.v1.z + this.v2.z + this.v3.z + this.v4.z)/4;
            this.draw = function(){
                ctx.save();
                ctx.beginPath();
                ctx.moveTo(this.v1._get2d().x , this.v1._get2d().y);
                ctx.lineTo(this.v2._get2d().x , this.v2._get2d().y);
                ctx.lineTo(this.v3._get2d().x , this.v3._get2d().y);
                ctx.lineTo(this.v4._get2d().x , this.v4._get2d().y);
                ctx.closePath();
                // ctx.fillStyle = "rgba("+parseInt(Math.random()*255)+","+parseInt(Math.random()*255)+","+parseInt(Math.random()*255)+",0.2)";
                ctx.fillStyle = this.color;
                ctx.fill();
            }
        }
        ```
- CSS 3D
    + 在没有CSS3之前，我们只能在网页上实现2D平面动画，但是随着CSS3技术的普及，我们可以很方便的在网页上实现一个3D立方体。今天给大家带来的便是一个基于jQuery和CSS3的3D立方体盒子，我们可以通过鼠标拖拽浏览盒子的每一个面，另外，3D盒子的面都可以自定义封面图片，你可以为每一个面选择不同的图片，并还可以自定义盒子的尺寸大小。

#WebGL简介
