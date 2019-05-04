#第1章-开始启程————你的第一行Android代码
- 了解全貌————Android王国介绍
    + Android系统架构
    + Android已发布的版本
    + Android应用开发特色
- 手把手带你搭建开发环境
    + 准备所需要的工具
    + 搭建开发环境
- 创建你的第一个Android项目
    + 创建HelloWorld项目
    + 启动模拟器
    + 运行helloworld
    + 分析你的第一个Android程序
    + 详解项目中的资源
    + 详解build.gradle文件
- 前行必备————掌握日志工具的使用
    + 使用Android的日志工具Log
    + 为什么使用Log而不是用System.out
- 小结与点评

#第2章-先从看得到的入手————探索活动
- 活动是什么
- 活动的基本用法
    + 手动创建活动
    + 创建和加载布局
    + 在AndroidManifest文件中注册
    + 在活动中使用Toast
    + 在活动中使用Menu
    + 销毁一个活动
- 使用Intent在活动之间穿梭
    + 使用显示Intent
    + 使用隐式Intent
    + 更多隐式Intent的用法
    + 向下一个活动传递数据
    + 返回数据给上一个活动
- 活动的生命周期
    + 返回栈
    + 活动状态
    + 活动的生存期
    + 体验活动的生存周期
    + 活动被回收了怎么办
- 活动的启动模式
    + standard
    + singleTop
    + singlTask
    + singleInstance
- 活动的最佳实践
    + 知晓当前是在哪一个活动
    + 随时随地退出程序
    + 启动活动的最佳写法
- 小结与点评

#第3章-软件也要拼脸蛋————UI开发的点点滴滴
- 如何编写程序界面
- 常用控件的使用方法
    + TextView
    + Button
    + EditText
    + ImageView
    + ProgressBar
    + AlertDialog
    + ProgressDialog
- 详解4种基本布局
    + 线性布局
    + 相对布局
    + 帧布局
    + 百分比布局
- 系统控件不够用？创建自定义控件
    + 引入布局
    + 创建自定义控件
- 最常用和最难用的控件————ListView
    + listView的简单用法
    + 定制ListView的界面
    + 提升ListView的运行效率
    + ListView的点击事件
- 更强大的滚动控件————RecyclerView
    + RecyclerView的基本用法
    + 实现横向滚动和瀑布流布局
    + RecyclerView的点击事件
- 编写界面的最佳实践
- 小结与点评

#第4章-手机平板要兼顾————探索碎片
- 碎片是什么
- 碎片的使用方式
    + 碎片的简单用法
    + 动态添加碎片
    + 在碎片中模拟返回栈
    + 碎片和活动之间进行通信
- 碎片的生命周期
    + 碎片的状态和回调
    + 体验碎片的生命周期
- 动态加载布局的技巧
    + 使用限定符
    + 使用最小宽度限定符
- 碎片的最佳实践————一个简易版的新闻应用
- 小结与点评

#第5章-全局大喇叭————详解广播机制
- 广播机制简介
- 接收系统广播
    + 动态注册监听网络变化
    + 静态注册实现开机启动
- 发送自定义广播
    + 发送标准广播
    + 发送有序广播
- 使用本地广播
- 广播的最佳实践————实现强制下线功能
- Git时间————初始版本控制工具
    + 安装Git
    + 创建代码仓库
    + 提交本地代码
- 小结与点评

#第6章-数据存储全方案————详解持久化技术
- 持久化技术简介
- 文件存储
    + 将数据存储到文件中
    + 从文件中读取数据
- SharePreferences存储
    + 将数据存储到sharedPreferences中
    + 从shardPreferences中读取数据
    + 实现记住密码功能
- SQLite数据库存储
- 使用LitePal操作数据库
    + LitePal简介
    + 配置LitePal
    + 创建和升级数据库
    + 使用LitePal添加数据
    + 使用LitePal更新数据
    + 使用LitePal删除数据
    + 使用LitePal查询数据
- 小结与点评

#第7章-跨程序共享数据————探究内容提供器
- 内容提供器简介
- 运行时权限
    + Android权限机制详解
    + 在程序运行时申请权限
- 访问其他程序中的数据
    + ContentResolver的基本用法
    + 读取系统联系人
- 创建自己的内容提供器
    + 创建内容提供器的步骤
    + 实现跨程序的数据共享
- Git时间————版本控制工具进阶
    + 忽略文件
    + 查看修改内容
    + 撤销未提交的修改
    + 查看提交记录
- 小结与点评

#第8章-丰富你的程序————运用手机多媒体
- 将程序运行到手机上
- 使用通知
    + 通知的基本用法
    + 通知的进阶技巧
    + 通知的高级功能
- 调用摄像头和相册
    + 调用摄像头拍照
    + 从相册中选择照片
- 播放多媒体文件
    + 播放音频
    + 播放视频
- 小结与点评

#第9章-看看精彩的世界————使用网络技术
- WebView的用法
- 使用HTTP协议访问网络
    + 使用HttpURLConnection
    + 使用OkHttp
- 解析XML格式数据
    + Pull解析方法
    + SAX解析方法
- 解析JSON格式数据
    + 使用JSONObject
    + 使用GSON
- 网格编程的最佳实践
- 小结与点评

#第10章-后台默默的劳动者————探索服务
- 服务是什么
- Android多线程编程
- 服务的基本用法
- 服务的生命周期
- 服务的更多技巧
- 服务的最佳实践————完整版的下载示例
- 小结与点评

#第11章-Android特色开发————基于位置的服务
- 基于位置的服务简介
- 申请API Key
- 使用百度定位
    + 准备LBS SDK
    + 确定自己位置的经纬度
    + 选择定位模式
    + 看得懂的位置信息
- 使用百度地图
    + 让地图显示出来
    + 移动到我的位置
    + 让"我"显示在地图上
- Git实践————版本控制工具的高级
    + 分支的用法
    + 与远程版本库协作
- 小结与点评

#第12章-最佳的UI体验————MaterialDesign实战
- 什么是Material Design
- Toolbar
- 滑动菜单
    + DrawerLayout
    + NavigationView
- 悬浮按钮和可交互提示
    + FloatingActionButton
    + Snackbar
    + CoordinatorLayout
- 卡片式布局
    + CardView
    + AppBarLayout
- 下拉刷新
- 可折叠式标题栏
    + CollapsingToolbarLayout
    + 充分利用系统状态栏空间
- 小结与点评

#第13章-继续进阶————你还应该掌握的高级技巧
- 全局获取Context的技巧
- 使用Intent传递对象
    + Serializable方式
    + Parcelable方式
- 定制自己的日志工具
- 调试Android程序
- 创建定时任务
    + Alarm机制
    + Doze模式
- 多窗口模式编程
    + 进入多窗口模式
    + 多窗口模式下的生命周期
    + 禁用多窗口模式
- Lambda表达式
- 总结

#第14章-进入实战————开发酷欧天气
- 功能需求及技术可行性分析
- Git时间————将代码托管到GitHub上
- 创建数据库和表
- 遍历全国省市县数据
- 显示天气信息
    + 定义GSON实体类
    + 编写天气界面
    + 将天气显示到界面上
    + 获取必应每日一图
- 手动更新天气和切换城市
    + 手动更新天气
    + 切换城市
- 后台自动更新天气
- 修改图标和名称
- 你还可以做的事情

#第15章-最后一步————将应用发布到360应用商店
- 生成正式签名的APK文件
    + 使用Android Studio生成
    + 使用Gradle生成
    + 生成多渠道APK文件
- 申请360开发者账号
- 发布应用程序
- 嵌入广告进行盈利
    + 注册腾讯广告联盟账号
    + 新建媒体和广告位
    + 接入广告SDK
    + 重新发布应用程序
- 结束语

##阅读笔记
#第1章 开始启程，你的第一行Android代码
#第2章 先从看得到的入手，探究活动
1.隐藏标题栏
　　在onCreate()方法中添加：
　　requestWindowFeature(Window.FEATURE_NO_TITLE);//不在活动中显示标题栏。
　　需要在setContentView()之前执行。
2.Intent是Android程序中各组件之间进行交互的一种重要方式，它不仅可以指明当前组件想要执行的动作，还可以在不同组件之间传递数据。Intent一般可被用于启动活动、启动服务、以及发送广播等场景。
3.<data>标签中主要可以配置以下内容：
　　（1）android:scheme
　　　　用于指定数据的协议部分，如http。
　　（2）android:host
　　　　用于指定数据的主机名部分，如www.baidu.com。
　　（3）android:port
　　　　用于指定数据的端口部分，一般紧随在主机名之后。
　　（4）android:path
　　　　用于指定主机名和端口之后的部分，如一段网址中跟在域名之后的内容。
　　（5）android:mimiType
　　　　用于指定可以处理的数据类型，允许使用通配符的方式进行指定。
4.onStop()和onPause()方法的主要区别在于：如果启动的新活动是一个对话框式的活动，那么onPause()方法就会得到执行，而onStop()方法并不会执行。

#第3章 软件也要拼脸蛋，UI开发的点点滴滴
1.ProgressDialog使用setCancelable()中传入了false,表示ProgressDialog是不能通过Back键取消掉的，
2.TableLayout布局可以使用android:stretchColumns属性允许将TableLayout中的某一列进行拉伸，以达到自动适应屏幕宽度的作用。
3.ArrayAdapter可以通过泛型来指定要适配的数据类型，然后在构造函数中把要适配的数据传入即可。
4.android.R.layout.simple_list_item_1是Android内置的布局文件，里面只有一个TextView，可用于简单地显示一段文本。
5.dp是密度无关像素的意思，在不同密度的屏幕中显示比例将保持一致。sp是可伸缩像素的意思，解决文字大小的适配问题。
6.Android中的密度就是屏幕每英寸所包含的像素数，通常以dpi为单位。
7.Nine-Patch图片是一种被特殊处理过的png图片，能够指定哪些区域可以被拉伸而哪些区域不可以。

#第4章 手机平板要兼顾，探究碎片
1.碎片（Frgament）是一种可以嵌入在活动当中的UI片段，它能让程序更加合理和充分地利用大屏幕的空间，因而在平板上应用的非常广泛。
2.FragmentTransaction中提供了一个addToBackStack()方法，可以用于将一个事务添加到返回栈中。
3.为了方便碎片和活动之间进行通信，FragmentManager提供了一个类似于findViewById()的方法，专门用于从布局文件中获取碎片的实例。
　　RightFragment rightFragment = (RightFragment) getFragmentManager().findFragmentById(R.id.right_fragment);
4.Android中一些常见的限定符：
　　大小： small       　---提供给小屏幕设备的资源
　　　　    normal 　　---提供给中等屏幕设备的资源
　　　　　large 　　　---提供给大屏幕设备的资源
　　　　   xlarge 　　  ---提供给超大屏幕设备的资源
　　分辨率： ldpi          ---提供给低分辨率设备的资源（120dpi以下）
　　　　　　mdpi         ---提供给中等分辨率设备的资源（120dpi到160dpi）
　　　　　　hdpi 　　  ---提供给高分辨率设备的资源（160dpi到240dpi）
　　　　　　xhdpi 　    ---提供给超高分辨率设备的资源（240dpi到320dpi）
　　方向： land        ---提供给横屏设备的资源
　　　　　 port        ---提供给竖屏设备的资源
5.最小宽度限定符允许我们对屏幕的宽度指定一个最小指（以dp为单位），然后以这个最小值为临界值，屏幕宽度大于这个值的设备就加载一个布局，屏幕宽度小于这个值的设备就加载另一个布局。
　　如layout-sw600dp文件夹中的布局，当屏幕运行在屏幕宽度大于600dp的设备上时，会加载layout-sw600dp中的布局，当程序运行在屏幕宽度小于600dp的设备上时，则仍然加载默认的layout中的布局。
　　最小宽度限定符是在Android3.2版本引入的。
6.TextView的属性
　　android:singleLine设置为true表示让这个TextView只能单行显示。
　　android:ellipsize用于设定文本内容超出控件宽度时，文本的缩略方式，设置为"end"表示在尾部进行缩略。
7.ImageView的属性
　　android:scaleType属性设置为fitXY，表示让这张图片填充满整个控件的大小。

#第5章 全部大喇叭，详解广播机制
1.Android中的广播主要可以分为两种类型，标准广播和有序广播。
　　标准广播(Normal broadcasts)是一种完全异步执行的广播，在广播发出之后，所有的广播接收器几乎都会在同一时刻接收到这条广播消息，因此它们之间没有任何先后顺序可言。这种广播的效率会比较高，单同事也意味着它是无法被截断的。
　　有序广播(Ordered broadcasts)则是一种同步执行的广播，在广播发出之后，同一时刻只会有一个广播接收器能够收到这条广播消息，当这个广播接收器中的逻辑执行完毕后，广播才会继续传递。所以此时的广播接收器是有先后顺序的，优先级高的广播接收器就可以先收到广播消息，并且前面的广播接收器还可以截断正在传递的广播，这样后面的广播接收器就饿无法收到广播消息了。
2.注册广播的方式一般有两种，在代码中注册和在AndroidManifest.xml中注册，其中前者也被称为动态注册，厚泽也被称为静态注册。
3.当网络状态发生变化时，系统发出的正是一条值为android.net,.conn.CONNECTIVITY_CHANGE的广播，监听需要权限<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE"/>。
4.访问http://developer.android.com/reference/android/Manifext.permission.html可以查看Android系统所有可声明的权限。
5.Android系统启动完成后会发出一条值为android.intent.action.BOOT_COMPLETED的广播，监听需要权限<uses-permission android:name="android.permission.RECEIVE_BOOT_COMPLETED"/>。
6.不要在onReceive()方法中添加过多的逻辑或者进行任何的耗时操作，因为在广播接收器中是不允许开启线程的，当onReceive()方法运行了较长时间而没有结束时，程序就会出错。
7.广播是一种可以跨进程的通信方式。
8.发送有序广播：
　　sendOrderedBroadcast(intent,null);
　　接受广播AndroidManifest.xml:<intent-filter android:priority="100">
　　　　onReceive(){... abortBroadcast();//截断这条广播}
9.本地广播机制，使用这个机制发出的广播只能够在应用程序的内部进行传递，并且广播接收器只能接收来自本应用程序发出的广播。
　　本地广播主要就是使用了一个LocalBroadcastManager来对广播继续宁管理，并提供了发送广播和注册广播接收器的方法。
　　private LocalBroadcastManager localBroadcastManager;
　　localBroadcastManager = LocalBroadcastManager.getInstance(this);//获取实例
　　localBroadcastManager.sendBroadcast(intent);//发送本地广播
　　localBroadcastManager.registerReceiver(localReceiver, intentFilter);//注册本地广播监听器
　　本地广播是无法通过静态注册的方式来接受的。其实这也是完全可以理解，因为静态注册主要就是为了让程序在未启动的情况下也能收到广播，而发送本地广播时，我们的程序是已经启动了，因此也完全不需要使用静态注册的功能。
　　本地广播的几点优势：
　　（1）可以明确地知道正在发送的广播不会离开我们的程序，因此不需要担心机密数据泄露的问题。
　　（2）其他的程序无法将广播发送到我们程序的内部，因此不需要贪心会有安全漏洞的隐患。
　　（3）发送本地广播比起发送系统全局广播将会更高效。
10.在广播接收器里启动活动，因此一定要给Intent加入FLAG_ACTIVITY_NEW_TASK这个标志。需要把对话框的类型设为TYPE_SYSTEM_ALERT,这样对话框在广播接收器里可以弹出。
11.弹出系统级别的对话框，必须要声明android.permission.SYSTEM_ALERT_WINDOW权限。

#第6章 数据存储全方案，详解持久化技术
1.瞬时数据指那些存储在内存当中，有可能会因为程序关闭或其他原因导致内存被回收而丢失的数据，比如登录界面的账号和密码。
2.数据持久化就是指将那些内存中的瞬时数据保存到存储设备中，保证即使在手机或电话关闭的情况下，这些数据仍然不会丢失。保存在内存中的数据是处于瞬时状态的，而保存在存储设备中的数据是处于持久状态的，持久化技术则是提供一种机制可以让数据在瞬时状态和持久状态之间进行转换。
　　Android系统中主要提供了三种方式用于简单地实现数据持久化功能，即文件存储、SharedPreference存储以及数据库存储。除了这三种方式之外，还可以将数据保存在手机的SD卡中，不过使用文件、SharedPreference或数据库来保存数据会相对更简单一些，而且比起将数据保存在SD卡中会更加的安全。
3.文件存储是Android中最基本的一种数据存储方式，它不对存储的内容进行任何的格式化处理，所有数据都是原封不动地保存到文件当中的，因而它比较适合用于存储一些简单的文本数据或二进制数据。如果你想使用文件存储的方式来保存一些较为复杂的文本数据，就需要定义一套自己的格式规范，这样方便于之后将数据从文件中重新解析出来。
　　Context类中提供了一个openFileOutput()方法，可以用于将数据存储到指定的文件中。这个方法接收两个参数，第一个参数是文件名，在文件创建的时候使用的就是这个名称，注意这里指定的文件名不可以包含路径，因为所有的文件都默认存储到/data/data/<packagename>/files/目录下的。第二个参数是文件的操作模式，主要有两种模式可选，MODE_PRIVATE和MODE_APPEND。其中MODE_PRIVATE是默认的操作模式，表示当指定同样文件名的手，所写的内容将会覆盖原文件中的内容，而MODE_APPEND则表示如果该文件已存在就往文件里面追加内容，不存在就创建新文件。其实文件的操作模式本来还有另外两种，MODE_WORLD_READABLE和MODE_WORLD_WRITEABLE，这两种模式表示允许其他的应用程序对我们程序中的文件进行读写操作，不过由于这两种模式过于危险，很容易引起应用的安全性漏洞，现已在Android 4.2版本中被废弃。
　　openFileOutput()方法返回的是一个FileOutputStream对象，得到了这个对象之后就可以使用Java六的方式将数据写入到文件中了。
　　类似于将数据存储到文件中，Context类中还提供了一个openFileInput()方法，用于从文件中读取数据。这个方法要比openFileOutput()简单一些，它只接收一个参数，即要读取的文件名，然后系统会自动到/data/data/<package name>/files/目录下去加载这个文件，并返回一个FileInputStream对象，得到了这个对象之后再通过java流的方式就可以将数据读取出来了。
　　对字符串进行非空判断的实收使用了TextUtils.isEmpty()方法，这是一个非常好用的方法，它可以一次性进行两种空值的判断。当传入的字符串等于null或者等于空字符串的时候，这个方法都会返回true，从而使得我们不需要单独去判断这两种空值，再使用逻辑运算符连接起来。
4.SharedPreferences是使用键值对的方式来存储数据的。也就是说当保存一条数据的时候，需要给这条数据提供一个对应的键，这样在读取数据的时候就可以通过这个键把相应的值取出来。而且SharedPreferences还支持多种不同的数据类型存储。
　　Android中主要提供了三种方式用于得到SharedPreferences对象。
　　　　（1）Context类中的getSharedPreferences()方法
　　　　　　此方法接收两个参数，第一个参数用于指定SharedPreferences文件的名称，如果指定的文件不存在则会创建一个，SharedPreferences文件都是存放在/data/data/<package name>/shared_prefs/目录下的。第二个参数用于指定操作模式，主要有两种模式可以选择。MODE_PRIVATE和MODE_MULIT_PROCESS。MODE_PRIVATE仍然是默认的操作模式。和直接传入0的效果是相同的，表示只有当前的应用程序才可以对这个SharedPreferences文件进行读写。MODE_MULIT_PROCESS则一般是用于会有多个进程中。
　　　　（2）Activity类中的getPreferences()方法
　　　　　　这个方法和Context中的getSharedPreferences()方法很相似，不过它只接收一个操作模式参数，因为使用这个方法时会自动将当前活动的类名作为SharedPreferences的文件名。
　　　　（3）PreferenceManager类中的getDefaultSharedPreferences()方法
　　　　　　这是一个静态方法，它接收一个Context参数，并自动使用当前应用程序的包名作为前缀来命名SharedPreferences文件。
　　得到了SharedPreferences对象之后，就可以开始向SharedPreferences文件中存储数据了，主要可以分为三步实现：
　　　　（1）调用SharedPreferences随想的edit()方法来获取一个SharedPreferences.Editor对象。
　　　　（2）向SharedPreferences.Editor对象中添加数据，比如添加布尔型数据就是用putBoolean方法，
　　　　（3）调用commit()方法将添加的数据提交，从而完成数据存储操作。
　　SharedPreferences对象中提供了一系列的get方法用于对存储的数据进行读取，每种get方法都对应了SharedPreferences.Editor中的一种put方法，比如读取一个布尔型数据就是用getBoolean()方法。这些get方法都接收两个参数，第一个参数是键，传入存储数据时是用的键就可以得到相应的值了，第二个参数是默认值，即表示传入的键找不到对应的值时，会以什么样的默认值进行返回。
5.SQLite是一款轻量级的关系型数据库，它的运算速度非常快，占用资源很少，通常只需要几百K的内存就足够了，因而特别适合在移动设备上使用。
　　SQLite不仅支持标准的SQL语法，还遵循了数据库的ACID事务。
　　SQLite比一般的数据库要简单得多，它甚至不用设置用户名和密码就可以使用。
　　Android为了让我们能够更加方便地管理数据库，专门提供了一个SQLiteOpenHelper帮助类，借助这个类就可以非常简单地对数据库进行创建和升级。
　　SQLiteOpenHelper是一个抽象类，这意味着如果我们想要使用它的话，就需要创建一个自己的帮助类去继承它。
　　SQLiteOpenHelper中有两个抽象方法，分别是onCreate()和onUpgrade()，必须在自己的帮助类里面重写这两个方法，然后分别在这两个方法中去实现创建、升级数据库的逻辑。
　　SQLiteOpenHelper中海油两个非常重要的实例方法，getReadableDatabase()和getWritableDatabase()。这两个方法都可以创建或打开一个现有的数据库（如果数据库已存在则直接打开，否则创建一个新的数据库），并返回一个可对数据库进行读写操作的对象。不同的是，当数据库不可写入的时候（如磁盘空间已满）getReadableDatabase()方法返回的对象将以只读的方式去打开数据库，而getWriteableDatabase()方法则将出现异常。
　　SQLiteOpenHelper中有两个构造方法可供重写，一般使用参数少一点的那个构造方法即可。这个构造方法中接受四个参数，第一个参数是Context，必须要有它才能对数据库进行操作。第二个参数是数据库名，创建数据库时使用的就是这里指定的名称。第三个参数允许我么在查询数据的时候返回一个自定义的Cursor，一般都是传入null。第三个参数表示当前数据库的版本号，可用于对数据库进行升级操作。构建出SQLiteOpenHelper的实例之后，再调用它的getReadableDatabase()或getWritableDatabase()方法就能够创建数据库了，数据库文件会存放在/data/data/<package name>/databases/目录下。此时，重写的onCreate()方法也会得到执行，所以通常会在这里处理一些创建表的逻辑。
　　SQLiteDatabase中提供了一个insert()方法，这个方法就是专门用于添加数据的。它接收三个参数，第一个参数是表名，我们希望向哪张表里添加数据，这里就传入该表的名字。第二个参数用于在未指定添加数据的情况下给某些可为空的列自动赋值NULL，一般我们用不到这个功能，直接传入null即可。第三个参数是一个ContentValues对象，它提供了一系列的put()方法重载，用于向ContentValues中添加数据，只需要将表中的每个列名以及相应的待添加数据传入即可。
　　SQLiteDatabase中也是提供了一个非常好用的uodate()方法用于对数据进行更新，这个方法接收四个参数，第一个参数和insert()方法一样，也是表名，在这里指定去更新哪张表里的数据。第二个参数是ContentValues对象，要把更新数据在这里组装进去。第三第四个参数用于约束更新某一行或某几行中的数据，不指定的话默认就是更新所有行。
　　SQLiteDatabase中提供了一个delete()方法专门用于删除数据，这个方法接收三个参数，第一个参数仍然是表名，第二、三个参数又是用于去约束删除某一行或某几行的数据，不指定的话默认就是删除所有行。
　　SQLiteDatabase中提供了一个query()方法用于对数据进行查新。这个方法的参数非常复杂，最短的一个方法重载也需要传入七个参数。第一个参数是表名，表示我们希望从哪张表中查询数据。第二个参数用于指定去哪查询哪几列，如果不指定则默认查询所有列。第三、第四个参数用于约束查询某一行或某几行的数据，不指定则默认是查询所有行的数据。第五个参数用于指定需要去group by的列，不指定则表示不会查询结果进行group bu操作。第六个参数用于对group by之后的数据进行进一步的过滤，不指定则表示不进行过滤。第七个参数用于指定查询结果的排序方法，不指定则表示使用默认的排序方式。
　　query()方法参数 对应SQL部分 描述
　　table from table_name 指定查询的表名
　　columns select column1,column2 指定查询的列明
　　selection where column = value 指定where的约束条件
　　selectionArgs - 为where中的占位符提供具体的值
　　groupBy group by column 指定需要group by的列
　　having having column = value 为group by 后的结果进一步约束
　　orderBy order by column1,column2 指定查询结果的排序方式
　　调用query()方法后会返回一个Cursor对象，查询到的所有数据都将从这个对象中取出。
　　除了查询数据的时候调用的是SQLiteDatabase的rawQuery()方法，其他的操作都是调用的execSQL()方法。
　　SQLite数据库是支持事务的，事务的特性可以保证让某一系列的操作要么全部完成，要么一个都不会完成。
　　Android中事务的标准用法，首先调用SQLiteDatabase的beginTransaction()方法来开启一个事务，然后在一个异常捕获的代码块中去执行具体的数据库操作，当所有的操作都完成之后，调用setTransactionSuccessful()表示事务已经执行成功了，最后在finally代码块中调用endTransaction()来结束事务。

#第7章 跨程序共享数据，探究内容提供器
1.使用臼齿化技术所保存的数据都只能在当前程序中访问。
2.内容提供器（Content Provider）主要用于在不同的应用程序之间实现数据共享的功能，它提供了一套完整的机制，允许一个程序访问另一个程序中的数据，同时还能保证被访数据的安全性。目前，使用内容提供器是Android实现跨程序共享数据的标准方式。
　　不同于文件存储和SharedPreferences存储中的两种全局可读写操作模式，内容提供器可以选择只对哪一部分数据进行共享，从而保证我们程序中的隐私数据不会有泄漏的风险。
　　内容提供器的用法一般有两种，一种是使用现有的内容提供器来读取和操作相应程序中的数据，另一种是创建自己的内容提供器给我们程序的数据提供外部访问接口。
3.当一个应用程序通过内容提供器对其数据提供了外部访问接口，任何其他的应用程序就都可以对这部分数据进行访问。Android系统中自带的电话簿、短信、媒体库等程序都提供了类似的访问接口，这就使得第三方应用程序可以充分地利用这部分数据来实现更好的功能。
　　对于每一个应用程序来说，如果想要访问内容提供器中共享的数据，就一定要借助ContentResolve类，可以通过Context中的getContentResolver()方法获取到该类的实例。ContentResolver中提供了一系列的方法用于对数据进行CRUD操作，其中insert()方法用于添加数据，update()方法用于更新数据，delete()方法用于删除数据，query()方法用于查询数据。
　　不同于SQLiteDatabase，ContentResolver中的增删改查方法都是不接收表名参数的，而是使用一个Uri参数代替，这个参数被称为内容URI。内容URI给内容提供器中的数据建立了唯一标识符，它主要由两部分组成，权限（authority）和路径（path）。权限是用于对不同的应用程序做区分的，一般为了避免冲突，都会采用程序包名的方式来进行命名。路径则是用于对同一应用程序中不同的表做区分的，通常都会添加到权限的后面。
　　调用Uri.parse()方法，就可以将内容URL字符串解析成Uri对象了。
　　可以使用Uri对象来查询table表中的数据，代码如下所示：
　　　　Cursor cursor = getContentResolver().query(
　　　　　　　　uri,
　　　　　　　　projection,
　　　　　　　　selection,
　　　　　　　　selectionArgs,
　　　　　　　　sortOrder
　　　　)
　　query()方法参数  　　对应SQL部分 　　　　 　　 描述
　　uri                       　　from table_name 　　  　　 指定查询某个应用程序下的某一张表
　　projection　　　　    select column1,column2 　  指定查询的列名
　　selection 　　　　　 where column = value 　　  指定where的约束条件
　　selectionArgs            - 　　　　　　　　　　　    为where中的占位符提供具体的值
　　orderBy 　　　　　  order by column1,column2   指定查询结果的排序方式
　　查询完成后返回的仍然是一个Cursor对象，这时我们就可以将数据从Cursor对象中逐个读取出来了。读物的思路仍然是通过移动游标的位置来遍历Cursor的所有行，然后再取出每一行中相应列的数据。
4.创建自己的内容提供器需要继承ContentProvider，ContentProvider类中有六个抽象方法。
　　（1）onCreate()
　　　　初始化内容提供器的时候调用。通常会在这里完成对数据库的创建和升级等操作，返回true表示内容提供器初始化成功，返回false则表示失败。注意，只有当存在ContentResolver尝试访问我们程序中的数据时，内容提供器才会被初始化。
　　（2）query()
　　　　从内容提供器中查询数据。使用uri参数来确定查询哪张表，projection参数用于确定查询哪些列，selection和selectionArgs参数用于约束查询哪些行，sortOrder参数用于对结果进行排序，查询的结果存放在Cursor对象中返回。
　　（3）insert()
　　　　更新内容提供器中添加一条数据。使用uri参数来确定要添加到的表，待添加的数据保存在values参数中，selection和selectionArgs参数用于约束更新哪些行，瘦影响的行数将作为返回值返回。
　　（4）update()
　　　　更新内容提供器中已有的数据。使用uri参数来确定更新哪一张表中的数据，新数据保存在values参数中，selection和selectionArgs参数用于约束更新哪些行，受影响的行数将作为返回值返回。
　　（5）delete()
　　　　从内容提供器中删除数据。使用uri参数来确定删除哪一张表中的数据，selection和selectionArgs参数用于约束删除哪些行，被删除的行数将作为返回值返回。
　　（6）getType()
　　　　根据传入的内容URI来返回相应的MIME类型。
5.一个标准的内容URI写法是这样的：
　　content://com.example.app.provider/table1
　　这就表示调用方期望访问的是com.example.app这个应用的table1表中的数据。除此之外，我们还可以在这跟人URI的后面加上一个id，如下所示：
　　content://com.example.app.provider/table1/1
　　内容URI的格式主要就只有以上两种，以路径结尾就表示期望访问该表中所有的数据，以id结尾就表示期望访问该表中拥有相应id的数据。我们可以使用通配符的方式来分别匹配这两种格式的内容URI，规则如下：
　　（1）*：表示匹配任意长度的任意字符
　　（2）#：表示匹配任意长度的数据
　　所以：一个能够匹配任意表的内容URI格式就可以写成：content://com.example.app.provider/*
　　而一个能够匹配table1表中任意一行数据的内容URI格式就可以写成：content://com.example.app.provider/table1/#
　　我们再借助UriMatcher这个类就可以轻松地实现匹配内容URI的功能。UriMatcher中提供了一个addURI()方法，这个方法接收三个参数，可以分别把权限、路径和一个自定义代码传进去。这样，当调用UriMatcher的match()方法时，就可以将一个Uri对象传入，返回值是某个能够匹配这个Uri随想所对应的自定义代码，利用这个代码，我们 就可以判断出调用方期望访问的是哪张表中的数据了。
6.一个内容URI所对应的MIME字符串主要由三部分组成，Android对这三个部分做了如下格式规格：
　　（1）必须以vnd开头。
　　（2）如果内容URI以路径结尾，则后接android.cursor:dir/，如果内容URI以id结尾，则后接android.cursor.item/。
　　（3）最后接上vnd.<authority>.<path>。
　　所以，对于content://com.example.app.provider/table1这个内容URL，它所对应的MIME类型就可以写成：vnd.android.cursor.dir/vnd.com.example.app.provider.table1
　　对于content://com.example.app.provider/table1/1这个内容URI，它所对应的MIME类型就可以写成：vnd.android.cursor.item/vnd.com.example.app.provider.table1
7.Git提供了一种可配性很强的机制来允许用户将指定的文件或目录排除在版本控制之外，它会检查代码仓库的根目录下是否存在一个名为.gitignore的文件，如果存在的话就去一行行读取这个文件中的内容，并把每一行指定的文件或目录排除在版本控制之外。注意.gitignore中指定的文件或目录是可以使用“*”通配符的。
　　查看文件修改情况使用status命令。
　　git diff 可以查看到所有文件的更改内容。
　　想要撤销修改可以使用checkout命令。这种撤销方式只适用于那些还没有执行过add命令的文件。执行过add命令的文件取消添加使用的是reset命令（get reaset HEAD <fileName>）。
　　使用git log命令查看历史提交信息。
　　使用git log commit-id 查看其中一条记录，加-1参数表示我们只想看到一行记录，加-p参数，查看这条提交记录具体修改了什么内容。

#第8章 丰富你的程序，运行手机多媒体
1.通知（Notification）是Android系统中比较有特色的一个功能，当某个应用程序希望向用户发出一些提示信息，而该应用程序又不在前台运行时，就可以借助通知来实现。发出一条通知后，手机最上方的状态栏中会显示一个通知的图标，下拉状态栏后可以看到通知的详细内容。
2.创建通知的详细步骤：首先需要一个NotificationManager来对通知进行管理，可以调用Context的getSystemService()方法获取到。getSystemService()方法接收一个字符串参数用于确定获取系统的哪个服务，这里我们传入Context.NOTIFICATION_SERVICE即可。因此，获取NotificationManager的实例就可以写成：
　　NotificationManager manager = (NotificationManager)getSystemService(Context.NOTIFICATION_SERVICE);
　　接下来需要创建一个Notification对象，这个对象用于存储通知所需的各种信息，我们可以使用它的有参构造函数来进行创建。Notification的有参构造函数接收三个参数，第一个参数用于指定通知的图标，第二个参数用于指定通知的ticker内容，当通知刚被创建的时候，它会在系统的状态栏一闪而过，属于一种瞬时的提示信息。第三个参数用于指定通知被创建的时间，以毫秒为单位，当下拉系统状态栏时，这里指定的时间会显示在相应的通知上。因此，创建一个Notification对象就可以写成：
　　　　Notification notification = new Notification(R.drawable.icon,"This is ticker text",System.currentTimeMillis());（已经不推荐使用，可以使用Builder）
　　创建好了Notification对象后，我们还需要对通知的布局进行设定，这里只需要调用Notification的setLatestEvenInfo()方法就可以给通知设置一个标准的布局。这个方法接收四个参数，第一个参数是Context，第二个参数用于指定通知的标题内容，下拉系统状态栏就可以看到这部分内容。第三个参数用于指定通知的正文内容，同样下拉系统状态栏就可以看到这部分内容。第四个参数暂时用不到，可以先传入null。因此，对通知的布局进行设定就可以写成：
　　　　notification.setLatestEventInfo(context, "This is content title", "This is content text", null);（已经不推荐使用，可以使用Builder）
　　以上工作完成之后，只需要调用NotificationManager的notify()方法就可以让通知显示出来了。notify()方法接收两个参数，第一个参数是id，要保证为每个通知所指定的id都是不同的。第二个参数则是Notification对象，这里直接将我们刚刚创建好的Notification对象传入即可。因此，显示一个通知就可以写成：
　　　　manager.notify(1, notification);
3.PendingIntent从名字上看起来就和Intent有些类似，它们之间也确实存在着不少共同点。比如它们都可以去指明某一个“意图”，都可以用于启动活动、启动服务以及发送广播等。不同的是，Intent更加倾向于去立即执行某个动作，而PendgingIntent更加倾向于在某个合适的时机去执行某个动作。所以，也可以吧PendingIntent简单地理解为延迟执行的Intent。
　　PendingIntent的用法很简单，它主要提供了几个静态方法用于获取PendingIntent的实例，可以根据需求来选择是使用getActivity()方法、getBroadcast()方法、还是getService()方法。这几个方法所接收的参数都是相同的。第一个参数是Context，第二个参数一般用不到，同创都是传入0即可。第三个参数是一个Intent独享，可以通过这个对象构建出PendingIntent的“意图”。第四个参数用于确定PendingIntent的行为，有FLAG_ONE_SHOT、FLAG_NO_CREATE、FLAG_CANCEL_CURRENT和FLAG_UPDATE_CURRENT这四种值可选。
4.接收短信的权限：android.permission.RECEIVE_SMS
　　接收短信的广播的action：android.provider.Telephony.SMS_RECEIVED
　　发送短信的权限：android.permission.SEND_SMS
5.启动相机的intent：Intent intent = new Intent("android.media.action.IMAGE_CAPTURE");
　　裁剪程序的intent：Intent intent = new Intent("com.android.camera.action.CROP");
　　向SD卡中写数据需要声明的权限：android.permission.WRITE_EXTERNAL_STORAGE
　　打开相册获取图片的intent：Intent intent = new Intent("android.intent.action.GET_CONTENT");
　　　　intent.setType("image/*");
　　　　intent.putExtra("crop",true);//是否允许裁剪
　　　　intent.putExtra("scale",true);//是否允许缩放
　　　　intent.putExtra(MediaStore.EXTRA_OUTPUT,image);//图片的输出位置
6.在Android中播放音频文件一般都是使用MediaPlayer来来实现的，它对多种格式的音频文件提供了非常全面的控制方法，从而使得播放音乐的工作变得非常简单。
　　MediaPlayer类中一些较为常用的控制方法：
　　方法名                                功能描述
　　setDataSource() 　　　　 设置要播放的音频文件的位置。
　　prepare()  　　　　　　　 在开始播放之前调用这个方法完成准备工作。
　　start()            　　　　　　开始或继续播放音频。
　　pause()                              暂停播放音频。
　　reset() 　　　　　　　　   将MediaPlayer对象重置到刚刚创建的状态。
　　seekTo() 　　　　　　　   从指定的位置开始播放音频。
　　stop() 　　　　　　　　   停止播放音频。调用这个方法后的MediaPlayer对象无法再播放音频。
　　release()                           释放掉与MediaPlayer对象相关的资源。 
　　isPlaying()　　　　　　   判断当前MediaPlayer是否正在播放音频。
　　getDuration() 　　　　　 获取载入的音频文件的时长。
　　MediaPlayer的工作流程：首先需要创建出一个MediaPlayer对象，然后调用setDataSource()方法来设置音频文件的路径，再调用prepare()方法使MediaPlayer进入到准备状态，接下来调用start()方法就可以开始播放音频，调用pause()方法就会暂停播放，调用reset()方法就会停止播放。
7.播放视频文件主要是使用VideoView类来实现的。这个类将视频的显示和控制集于一身，使得我们仅仅借助它就可以完成一个简易的视频播放器。
　　VideoView的常用方法：
　　方法名 　　　　　　 功能描述
　　setVideoPath() 　　 设置要播放的视频文件的位置 。
　　start()　　　　　　  开始或继续播放视频。
　　pause()　　　　　   暂停播放视频。
　　resume() 　　　　   将视频重头开始播放。
　　seekTo() 　　　　   从指定的位置开始播放视频。
　　isPlaying() 　　　   判断当前时候正在播放视频。
　　getDuration() 　　 获取载入的视频文件的时长。
　　VideoView并不是一个万能的视频播放工具类。它在视频格式的支持以及播放效率方面都存在着较大的不足。所以，如果想要仅仅使用VideoView就编写一个功能非常强大的视频播放器是不太现实的。但是如果只是用于播放一些游戏的片头订花，或者某个应用的视频宣传，使用VideoView还是绰绰有余的。

#第9章 后台默默的劳动者，探究服务
1.服务(Service)是Android中实现程序后台运行的解决方案，它非常适合用于去执行那些不需要和用户交互而且还要求长期运行的任务。服务的运行以依赖于任何用户界面，即使当程序被切换到后台，或者用户打开了另外一个应用程序，服务仍然能够保持正常运行。
不过需要注意的是，服务并不是运行在一个独立的进程当中的，而是依赖于创建服务时所在的应用程序进程。当某个应用程序进程被杀掉时，所有依赖于该进程的服务也会停止运行。
　　另外，也不要被服务的后台概念所迷惑，实际上服务并不会自动开启线程，所有的代码都是默认运行在主线程当中的。也就是说，我们需要在服务的内部手动创建子线程，并在这里执行具体的任务，否则就有可能出现主线程被组塞住的情况。
2.Android中的异步消息处理主要由四个部分组成，Message、Handler、MessageQueue和Looper。
　　（1）Message
　　　　Message是在线程之间传递的消息，它可以在内部携带少量的信息，用于在不同线程之间交换数据。
　　（2）Handler
　　　　Hnadler顾名思义也就是处理者的意思，它主要是用于发送和处理消息的。发送消息一般都是使用Handler的sendMessage()方法，而发出的消息经过一系列地辗转处理后，最终会传递到Handler的handleMessage()方法中。
　　（3）MessageQueue
　　　　MessageQueue是消息队列的意思，呀主要用于存放所有通过Handler发送的消息。这部分消息会一直存在于消息队列中，等待被处理。每个线程中只会有一个MessageQueue对象。
　　（4）Looper
　　　　Looper是每个线程中的MessageQueue的管家，调用Looper的loop()方法后，就会进入到一个无限循环当中，然后每当发现MessageQueue中存在一条消息，就会将它取出，并传递到Handler的handleMessage()方法中。每个线程中也只会有一个Looper对象。
3.异步消息处理的整个流程：首先需要在主线程当中创建一个Handler对象，并重写handleMessage()方法。然后当子线程中需要进行UI操作时，就创建一个Message对象，并通过Handler将这条消息发送出去。之后这条消息会被添加到MessageQueue的队列中等待被处理，而Looper则会一直尝试从MessageQueue中取出待处理消息，最后分发回Handler的handleMessage()方法中。由于Handler是在主线程中创建的。所以此时handleMessage()方法中的代码也会在主线程中运行，于是我们在这里就可以安心地进行UI操作了。
4.AsyncTask背后的实现原理也是基于异步消息处理机制的。
　　AsyncTask是一个抽象类，如果想要使用它没救必须创建一个子类去继承它。在继承时我们可以为AsyncTask类指定三个泛型参数，这三个参数的用途如下：
　　　　（1）Params
　　　　　　在执行AsyncTask时需要传入的参数，可用于在后台任务中使用。
　　　　（2）Progress
　　　　　　后台任务执行时，如果需要在界面上显示当前的速度，则使用这里指定的泛型作为进度单位。
　　　　（3）Result
　　　　　　当任务执行完毕后，如果需要对结果进行返回，则使用这里指定的泛型作为返回值类型。
　　AsyncTask需要经常重写的方法：
　　　　（1）onPreExecute()
　　　　　　这个方法会在后台任务开始执行之前调用，用于进行一些界面上的初始化操作，必须显示一个进度条对话框等。
　　　　（2）doInBackfround(Params...)
　　　　　　这个方法中的所有代码都会在子线程中运行，我们应该在这里去处理所有的耗时任务。任务一旦完成就可以通过return语句来将任务的执行结果返回，如果AsyncTask的第三个泛型参数指定的是Void，就可以不返回任务执行结果。注意，在这个方法中是不可以进行UI操作的，如果需要更新UI元素，如果需要更新UI元素，比如说反馈当前任务的执行进度，可以调用publishProgress(Progress...)
　　　　（3）onProgressUpdate(Progress...)
　　　　　　当在后台任务中调用了publishProgress(Progress...)方法后，这个方法就会很快被调用，方法中携带的参数就是在后台任务中传递过来的。在这个方法中可以对UI进行操作，利用参数中的数值就可以对界面元素进行相应地更新。
　　　　（4）onPostExecute(Result)
　　　　　　当后台任务执行完毕并通过return语句进行返回时，这个方法就很快会被调用。返回的数据会作为参数传递到此方法中，可以利用返回的数据进行一些UI操作。
　　使用AsyncTask的诀窍是，在doInBackground()方法中去执行具体的耗时任务，在onProgressUpdate()方法中进行UI操作，在onPostExecute()方法中执行一些任务的收尾工作。

5.服务的常用到的单个方法，其中onCreate()方法会在服务创建的时候调用，onStartCommand()方法会在每次服务启动的时候调用，onDestory()方法会在服务销毁的时候调用。 
6.一旦在项目的任何位置调用了Context的startService()方法，相应的服务就会启动起来，并回调onStartCommand()方法。如果这个服务之前还没有创建过，onCreate()方法会先于onStartCommand()方法执行。服务启动了之后会一直保持运行状态，直到stopService()或stopService()方法被调用。注意虽然每调用一次startService()方法，onStartCommand()就会执行一次，实际上每个服务都只会存在一个实例。所以不管你调用多少次startService()方法，只需调用一次stopService()或stopSelf()方法，服务就会停止下来了。
　　还可以调用Context的bindService()来获取一次服务的持久连接，这时就会回调服务中的onBind()方法。类似地，如果这个服务之前还没有创建过，onCreate()方法会先于onBind()方法执行。之后，调用方可以获取到onBind()方法里返回的IBinder对象的实例，这样就能自由地和服务进行通信了。只要调用方和服务之间的连接没有断开，服务就会一直保持运行状态。
　　当调用startService()方法后，又去调用stopService()方法，这时服务中的onDestroy()方法就会执行，表示服务以及销毁了。类似地，当调用了bindService()方法后，又去调用unbindService()方法，onDestroy()方法也会执行。但是需要注意，我们是完全有可能对一个服务即调用了startService()方法，又调用了bindService()方法的，根据Android系统的机制，一个服务只要被启动或者被绑定了之后，就会一直处于运行状态，必须要让以上两种条件同时不满足，服务才能被销毁。所以，要同时调用stopService()和unbindService()方法，onDestroy()方法才会执行。
7.服务几乎都是在后台运行的，一直以来它都是默默地做着辛苦的工作。但是服务的系统优先级还是比较低的，当系统出现内存不足的情况下，就可能会回收掉正在后台运行的服务。如果你希望服务可以一直保持运行状态，而不会由于系统内存不足的原因导致被回收，就可以考虑使用前台服务。前台服务和普通服务最大的区别就在于，它会一直有一个正在运行的图标在系统的状态栏显示，下拉状态栏后可以看到更加详细的信息，非常类似于通知的效果。当然有时候你也可能不仅仅是为了防止服务被回收掉才是用前台服务的，有些项目由于特殊的需求必须使用前台服务。
8.IntentService类，可以在onHandleIntent()抽象方法中处理一些具体逻辑，而且不用担心ARN的问题，因为这个方法已经是在子线程中运行了，任务完成服务会自动停止。
9.Android中的定时任务一般有两种实现方式，一种是使用Java API里提供的Timer类，一种是使用Android的Alarm机制。这两种方式在多数情况下都能实现类似的效果，但Timer有一个明显的短板，它并不太适合于那些需要长期在后台运行的定时任务。我们知道，为了能让电池更加耐用，每种手机都会有自己的休眠策略，Android手机就会在长时间不操作的情况下自动让CPU进入到睡眠状态，这就有可能导致Timer中的定时任务无法正常运行。而Alarm机制则不存在这种情况，它具有唤醒CPU的功能，既可以保证每次需要执行定时任务的时候CPU都能正常工作。需要注意，这里唤醒CPU和唤醒屏幕完全不是同一个概念。
10.AlarmManager主要就是借助了AlarmManager类来实现的，通过调用Context的getSystemService()方法来获取实例的，需要传入参数是Context.ALARM_SERVICE。获取实例就可以写成：
　　AlarmManager manager = (AlarmManager) getSystemService(Context.ALARM_SERVICE);
　　接下来调用AlarmManager的set()方法就可以设置一个定时任务了，比如设置一个任务在10分钟后执行：
　　　　long triggerAtTime = SystemClock.elapsedRealtime() + 10 * 1000;
　　　　manager.set(AlarmManager.ELAPSED_REALTIME_WAKEUP, triggAtTime, pendingIntent);
　　set()方法的三个参数，第一个参数是一个整型参数，用于指定AlarmManager的工作类型，有四种值可选，分别是ELAPSED_REALTIME、ELAPSED_REALTIME_WAKEUP、RTC和RTC_WAKEUP。其中ELAPSED_REALTIME表示让定时器表示让定时任务的出发时间从系统开机开始算起，但不会唤醒CPU。ELAPSED_REALTIME_WAKEUP同样表示让定时任务的出发时间从系统开始开始算起，但会唤醒CPU。RTC表示定时任务的触发时间从1970年1月1日0时开始算起，但不会唤醒CPU。RTC_WAKEUP同样表示让定时任务的触发时间从1970年1月1日0时开始算起，但会唤醒CPU。
　　使用SystemClock.elapsedRealtiome()方法可以获取到系统开机至今所经历时间的毫秒数，使用System.curretnTimeMillis()方法可以获取到1970年1月1日0点至今所经历时间的毫秒数。
　　第二个参数就是定时任务触发的时间，以毫秒为单位。如果第一个参数使用的是ELAPSED_REALTIME或ELAPSED_REALTIME_WAKEUP，则这里传入开机至今在加上延迟执行的时间。如果第一个参数使用的是RTC或RTC_WAKEUP，则这里传入1970年1月1日0点至今的时间再加上延迟执行的时间。
　　第三个参数是一个PendingIntent，这里我们一般会调用getBroadcast()方法来获取一个能够执行广播的PendingIntent。这样当定时任务呗出发的时候，广播接收器的onReceiver()方法就可以得到执行。
11.从Android 4.4版本开始，Alarm任务的触发时间将会变得不准确，有可能会延迟一段时间后任务才能得到执行。这不是个bug，而是系统在好点性方面进行的优化。系统会自动检测目前有多敲Alarm任务存在，然后将触发时间将近的几个任务放在一起执行，这就可以大幅度地减少CPU被唤醒的次数，从而有效延长电池的使用时间。
　　如果你要求Alarm任务的执行时间必须准确无误，Android仍然提供了解决方案。使用AlarmManager的setExact()方法来代替set()方法，就可以抱枕任务准时执行了。

#第10章 看看精彩的世界，使用网络技术
1.HTTP协议的工作原理就是客户端向服务器发出一条HTTP请求，，服务器收到请求之后会返回一些数据给客户端，然后客户端再对这些数据进行解析和处理就可以了。
2.在Android上发送HTTP请求的方式一般有两种，HttpURLConnection和HttpClient。
3.HttpURLConnection的用法：
　　首先需要获取到HttpURLConnection的实例，一般只需new出一个URL对象，并传入目标的网络地址，然后调用一下openConnection()方法即可，如下所示：
　　　　URL url = new URL("http://www.baidu.com");
　　　　HttpURLConnection connection = (HttpURLConnection) url.openConnection();
　　得到了HttpURLConnection的实例之后，我们可以设置一下HTTP请求所使用的方法。常用的方法主要有两个，GET和POST。GET表示希望从服务器那里获取数据，而POST则表示希望提交数据给服务器。写法如下：
　　　　connection.setRequestMethod("GET");
　　接下来就可以进行一些自由地定制了，比如设置连接超时，读取超时的毫秒数，以及服务器希望得到的一些消息头等。这部分内容根据自己的实际情况进行编写，示例写法如下：
　　　　connection.setConnectionTimeout(8000);
　　　　connection.setReadTimeout(8000);
　　之后再调用getInputStream()方法就可以获取到服务器返回的输入流了，剩下的任务就是对输入流进行读取，如下所示：
　　　　InoutStream in = connection.getInputStream();
　　最后可以调用disconnect()方法将这个HTTP连接关闭掉，如下所示：
　　　　connection.disconnection();
　　提交数据费服务器，只需要将HTTP请求的方法改成POST，并在获取输入流之前把要提交的数据写出即可。注意每条数据都要以键值对的形式存在，数据与数据之间用&符号隔开，比如说我们想要向服务器提交用户名和密码，就可以这样写：
　　　　connection.setRequestMethod("POST");
　　　　DataOutputStream out = new DataOutputStream(connection.getOutputStream());
　　　　out.writeBytes("username=admin&password=123456");
4.HttpClient是Apache提供的HTTP网络访问接口，从一开始的时候就被引入到了Android API中。它可以完成和HttpURLcONNECTION几乎一模一样的效果，但两者之间的用法却又较大的差别。
5.HttpClient的用法：
　　首先你需要知道，HttpClient是一个接口，因此无法创建它的实例，通常情况下都会创建一个DefaultHttpClient的实例，如下所示：
　　　　HttpClient httpClient = new DefaultHttpClient();
　　接下来如果想要发起一条GET请求，就可以创建一个HttpGet对象，并传入目标的网络地址，然后调用HttpClient的execute()方法即可。
　　　　HttpGet httpGet = new HttpGet("http://www.baidu.com");
　　　　httpClient.execute(httpGet);
　　如果是发起一条POSY请求会比GET稍微复杂一点，我们需要创建一个HttpPost对象，并传入目标的网络地址，如下所示：
　　　　HttpPost httpPost = new HttpPost("http://www.baidu.com");
　　然后通过一个NameValuePair集合来存放待提交的参数，并将这个参数集合传入到一个UrlEncodedFormEntity中，然后调用HttpPost的setEntity()方法将构建好的UrlEncodeFormEntity传入，如下所示：
　　　　List<NameValuePair> params = new ArrayList<NameValuePair>();
　　　　params.add(new BasicNameValuePair("username","admin"));
　　　　params.add(new BasicNameValuePair("password","123456"));
　　　　UrlEncodedFromEntity entity = new UrlEncodedFormEntity(params, "utf-8");
　　　　httpPost.setEntity(entity);
　　接下来的操作就和HttpGet一样了，调用HttpClient的execute()方法，并将HttpPost对象传入即可：
　　　　httpClient.execute(httpPost);
　　执行execute()方法之后会返回一个HttpResponse对象，服务器所返回的所有信息就会包含在这里面。通常情况下我们都会先取出服务器返回的状态码，如果等于200就说明请求和响应都成功了，如下所示：
　　　　if (httpResponse.getStatusLine().getStatusCode == 200) {
　　　　　　//请求和响应都成功了
　　　　}
　　接下来在这个if判断的内部取出服务返回的具体内容，可以调用getEntity()方法获取到一个HttpEntity实例，然后再用EntityUtils.toString()这个静态方法将HttpEntity转换成字符串即可，如下所示：
　　　　HttpEntity entity = httpResponse.getEntity();
　　　　String response = EntityUtils.toString(entity);
　　注意如果服务器返回的数据是带有中文的，直接调用EntityUtils.toString()方法进行转换会有乱码的情况出现，这个时候只需要在转换的时候讲字符集指定成utf-8就可以了，如下所示：
　　　　String response = EntityUtil.toString(entity, "utf-8");
6.比起XML，JSON的主要优势在于它的体积更小，在网络上传输的时候可以更省流量。单缺点在于，它的与异性较差，看起来不如XML直观。


#第11章 Android特色开发，基于位置的服务

1.基于位置的服务简称LBS，主要的工作原理就是利用无线电通讯网络或GPS等定位方式来确定出移动设备所在的位置。
2.基于位置的服务在Android中主要借助LocationManager这个类实现。
3.要想使用LocationManager就必须要先获取到它的实例，我们可以调用Context的getSystemService()方法获取到。getSysytemService()方法接收一个字符串参数用于确定获取系统的哪个服务，这里传入Context.LOCATION_SERVICE即可。因此，获取　　　　　　LocationManager饿实例就可以写成：
　　LocationManager locationManager = (LocationManager) getSystemService(Context.LOCATION_SERVICE);
　　接着我们需要选择一个位置提供器来确定设备当前的位置。Android中一般有三种位置提供器可供选择，GPS_PROVIDER、NETWORK_PROVIDER和PASSIVE_PROVIDER。其中前两种使用的比较多，分贝表示勇士GPS定位和使用网络定位。这两种定位方式各有特点，GPS定位的精确度比较高，但是非常耗电，而网络定位的精准度较差，但耗电量比较少、我们应该根据自己的实际情况来选择使用哪一种位置提供器，当位置精度要求非常高的时候，最好使用GPS_PROVIDER，二一班情况下，使用NETWORK_PROVIDER会更加得划算。
　　需要注意的是，定位功能必要要由用户主动去启动才行，不然任何应用程序都无法获取到手机当前的位置信息。
　　将选择好的位置提供器传入到getLastKnownLocation()方法中，就可以得到一个Location对象，如下所示：
　　　　String provider = LocationManager.NETWORK_PROVIDER;
　　　　Location location = locationManager.getLastKnownLocation(provider);
　　这个Location对象中包含了经度、纬度、海拔等一系列的位置信息，然后从中取出我们所关系的那部分数据即可。
　　判断有哪些位置提供器可用，如下所示：
　　　　List<String> providerList = locationManager.getProviders(true);
　　getProviders()方法接收一个布尔值参数，传入truw就表示只有启用的位置提供器才会被返回。之后再从providerList中判断是否包含GPS定位的功能就行了。
　　调用getLastKnownLocation()方法虽然可以获取到设备当前的位置信息，但是用户是完全有可能带有移动设备随时移动的，那么怎样才能在设备位置发生改变的时候获取到最新的位置信息呢？LocationManager还提供了一个requestLocationUpdates()方法，只要传入一个LocationListener的实例，并简单配置几个参数就可以实现上述功能了，写法如下：
　　locationManager.requestLocationUpdates(LocationManager.GPS_PRIVIDER, 5000, 10, new LocationListener() {
　　　　@Override
　　　　public void onStatusChanged(String provider, int status, Bundle extras){}

　　　　@Override
　　　　public void onProviderEnabled(String provider) {}

　　　　@Override
　　　　public void onProviderDisabled(String provider) {}

　　　　@Override
　　　　public void onLocationChanged(Location location) {}
　　}); 
　　这里requestLocationUpdates()方法接收四个参数，第一个采纳数是位置提供器的类型，第二个参数是监听位置变化的时间间隔，以毫秒为单位，第三个参数是监听位置变化的距离间隔，以米为单位，第四个参数则是LocationListener监听器。
4.其实Android本身就提供了地理编码的API，主要是使用GeoCoder这个类来实现的。他可以非常简单地完成正向和反向的地理编码功能，从而轻松地将一个经纬值转换成看得懂的位置信息。
　　GeoCoder长期存在着一些较为严重的bug，在反向地理编码的时候会有一定的概率不能解析出位置的信息，这样就无法保证位置解析的稳定性。
　　谷歌又提供了一套Geocoding API，使用它的话也可以完成反向地理编码的工作，只不过它的用法稍微复杂了一些，但稳定性要比GeoCoder强得多。
　　Geocoding API的工作原理并不神秘，其实就是利用HTTP协议。在手机端我们可以向谷歌的服务器发起一条HTTP请求，并将经纬度的值作为参数异同传递过去，然后服务端会帮我们将这个经纬值转换成看得懂的位置信息，再将这些信息返回给手机端，最后手机端去解析服务器返回的信息，并进行处理就可以了。
　　Geocoding API中规定了很多借口，其中反向地理编码的接口如下：
　　　　http://maps.googleapis.com/maps/api/geocode/json?latlng=40.714224,-73.96145&sensor=true_or_false
　　其中http://maps.googleapis.com/maps/api/geocode/是固定的，表示接口的连接地址。json表示希望服务器能够返回JSON格式的数据，这里也可以指定成xml。latlng=40.714224,-73.96145表示传递给服务器去解码的经纬值是北纬40.714224度，西经73.96145度，sensor=true_or_false表示这条请求是否来自于某个设备的位置传感器，通常指定成false即可。
5.分支是版本控制工具中比较高级且比较重要的一个概念，它主要的作用就是在现有代码的基础上开辟一个分叉口，使得代码可以在主干线和分支线上同时进行开发，且相互之间不会影响。
　　查看当前的版本库当中有哪些分支，可以使用git branch -a 命令.
　　创建分支命令：       git branch 分支名
　　切换分支命令：       git checkout 分支名
　　合并分支代码命令：git checkout 分支名（先切换分支） git merge 分支名(合并哪个分支的代码)
　　删除分支命令：       git branch -D 分支名
　　将本地修改的内容同步到远程版本库上：git push origin master，其中origin部分指定的是远程版本库的Git地址，master部分指定的是同步哪一个分支上。上述命令就完成了将本地代码同步到版本库的master分支上的功能。
　　将远程版本库上的修改同步到本地。Git提供了两种命令来完成此功能，分别是fetch和pull，fetch的语法规则和push是差不多的，如下所示：
　　　　git fetch origin master
　　执行命令后，就会将远程版本库上的代码同步到本地，不过同步下来的代码并不会合并到任何分支上，而是会存放在一个origin/master分支上，这是我们可以通过diff命令来查看远程版本库上待敌修改了哪些东西：
　　　　git diff origin/master
　　之后再调用merge命令将origin/master分支上的修改合并到主分支上即可，如下所示：
　　　　git merge origin/master
　　而pull命令则是相当于将fetch和merge这两个命令放在一起在执行了，它可以从远程版本库上获取最新的代码并且合并到本地，用法如下：
　　　　git pull origin master

#第12章 Android特色开发，使用传感器 
1.手机内置的传感器是一种微型的物理设备，它呢能够探测、感受到外界的信号，并按一定规律转换成我们所需要的信息。Android手机通常都会支持多种类型的传感器，如光照传感器、加速度传感器、地磁传感器、压力传感器、温蒂传感器等。
2.光照传感器在Android中的应用还是比较常见的，比如系统就有个自动调整屏幕亮度的功能。它会检测手机周围环境的光照强度，然后对手机屏幕的亮度进行相应地调整，一次保证不管在强光还是弱光下，手机屏幕都能够看得清。
3.Android中每个传感器的用法其实都比较类似。首先第一步要获取到SensorManager的实例，方法如下：
　　SensorManager sensorManager = (SensorManager)getSystemService(Context.SENSOR_SERVICE);
　　SensorManager是系统所有传感器的管理器，有了它的实例之后就可以调用getDefaultSensor()方法来得到任意的传感器类型了，如下所示：
　　Sensor sensor = sensorManager.getDefaultSensor(Sensor.TYPE_LIGHT);
　　这里使用Sensor.TYPE_LIGHT常量来指定传感器类型，此时的Sensor实例就代表着一个光照传感器。
　　接下来需要对传感器输出的信号进行监听，这就要借助SensorEventListener来实现了。SensorEventListener是一个接口，其中定义了onSensorChanged()和onAccuracyChanged()这两个方法。当传感器的精度发生变化时就会调用onAccuracyChanged()方法，当传感器监测到的数值发生变化时就会调用onSensorChanged()方法。onSensorChanged()方法中传入了一个SensorEvent参数，这个参数里又包含了一个values数组，所有传感器输出的信息都是存放在这里的。
　　下来还需要调用SensorManager的registerListener()方法来注册SensorEventListener才能使其生效，registerListener()方法来注册SensorEventListener才能使其生效，registerListener()方法接收三个参数，第一个参数就是SensorEventListener的实例，第二个参数是Sensor的实例。第三个参数是用于表示传感器输出信息的更新速率，共有SENSOR_DELAY_UI、SENSOR_DELAY_NORMAL、SENSOR_DELAY_GAME和SENSOR_DELAY_FASTEST这四个值可选，它们的更新速率是一次递增的。
　　始终要记得，当程序退出或传感器使用完毕时，一定要调用unregisterListener()方法将使用的资源释放掉。
4.获取Sensor实例的时候要指定一个加速度传感器的常量，如下所示：
　　Sensor sensor = sensorManager.getDefaultSensor(Sensor.TYPE_ACCELEROMETER);
　　加速度传感器输出的信息同样也是存放在SensorEvent的values数组中的，只不过此时的values数组中会有三个值，分别代表手机在X轴、Y轴、Z轴方向上的加速度。
5.获取到一个用于表示方向传感器的Sensor实例，如下所示：
　　Sensor sensor = sensorManager.getDefaultSensor(Sensor.TYPE_ORIENTATION);
　　之后再onSensorChanged()方法中通过SensorEvent的values数组，就可以得到传唤器输出的所有值了。方向传感器会记录手机在所有方向上的旋转角度。其中,values[0]记录着手机围绕Z轴的旋转角度，values[1]记录着手机围绕X轴的旋转角度，values[2]记录着手机围绕Y轴的旋转角度。
　　但遗憾的是，Android早就废弃了Sensor.TYPE_ORIENTATION这种传感器类型，虽然代码还是有效的，但已经不再推荐这么写了。事实上，Android获取手机旋转的方向和角度是通过加速度传感器和地磁传感器共同计算得出的，这也是Android目前推荐使用的方式。
　　首先我们需要分别获取到加速度传感器和地磁传感器的实例，并给它们注册监听器，如下所示：
　　　　Sensor accelerometerSensor = sensorManager.getDefaultSensor(Sensor.TYPE_ACCELEROMETER);
　　　　Sensor magneticSensor = sensorManager.getDefaultSensor(Sensor.TYPE_MAGNETIC_FIELD);
　　　　sensorManager.registerListener(listener, accelerometerSensor,SensorManager.SENSOR_DELAY_GAME);
　　　　sensorManager.registerListener(listener, magneticSensor,SensorManager.SENSOR_DELAY_GAME);
　　由于方向传感器的精确度要求通常都比较高，这里我们把传感器输出此案次的更新速率提高了一些，使用的是SENSOR_DELAY_GAME。
　　接下来在onSensorChanged()方法中可以获取到SensorEvent的values数组，分别记录着加速度传感器和地磁传感器输出的值。然后将这两个值传入到SensorManager的getRotationMatrix()方法中就可以得到一个包含旋转矩阵的R数组，如下所示：
　　　　SensorManager.getRotationMatrix(R, null, acceler0meterValues, magneticValues);
　　其中第一个参数R是一个长度为9的float数组，getRotationMatrix()方法计算出的旋转数组就会赋值到这个数组中。第二个参数是一个用于将地磁向量转换成重力坐标的旋转矩阵，通常指定为null即可。第三和第四个参数则分别就是加速度传感器和地磁传感器输出的values值。
　　得到了R数组之后，接着就可以调用SensorManager的getOrientation()方法来计算手机的旋转数据了，如下所示：
　　　　SensorManager.getOrientation(R, values);
　　values是一个长度为3的float数组，手机在各个方向上的旋转数据都会被存放到这个数组当中。其中values[0]记录着手机围绕Z轴的旋转弧度，values[1]记录着手机围绕X轴的旋转弧度，values[2]记录着手机围绕Y轴的旋转弧度。
　　注意这里计算出的数据都是以弧度为单位的，因此如果你想将它们转换成角度还需要调用如下方法：
　　　　Math.toDegrees(values[0]);

#第13章 继续进阶，你还应该掌握的高级技巧
1.使用Intent来传递对象通常有两种实现方式，Sericalizable和Paracelable。
　　Serizable是序列化的意思，表示将一个对象转换成可存储或可传输的状态。序列化后的对象可以在网络上进行传输，也可以存储到本地。至于序列化的方法也很简单，只需要让一个类趋势线Serializable这个接口就可以了。
　　除了Serializable之外，使用Parcelable也可以实现相同的效果，不过不同于将对象进行序列化，Parcelable方式的实现原理是将一个完整的对象进行分解，而分解后的每一部分都是Intent所支持的数据类型，这样也就实现传递对象的功能了。
　　Serializable的方式较为简单，但由于会把整个对象进行序列化，因此效率方面会比Parcelable方式低一些，所以在通常情况下还是更加推荐使用Parcelable的方式实现Intent传递对象的功能。

#第14章 进入实战，开发酷欧天气

#第15章 最后一步，将应用发布到Google Play
