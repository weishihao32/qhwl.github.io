Drmo使用手册


一、平台介绍
1.1 平台简介
- VR创作编辑平台是我公司推出的专业的虚拟现实创作编辑平台即Drmo（追梦）；其简洁明快UI设计，操作简单门槛低 ，支持图片文字、音频、视频、模型等多媒体数据加载，支持PC端、手机端、AR/VR端、TV端、触控屏端、H5端等多端互动展示，丰富的资源库。
- 依托虚拟现实技术为教育、企业等领域快速认识、掌握技能建立桥梁，推动技术攻关、标准制定、人才对接、应用推广、投资促进、品牌宣传、凝聚社会力量支持虚拟现实产业创新发展。
1.2 安装环境


二、界面介绍
2.1 登陆界面
账号登录：需要注册账号才能进行登录；



2.2 项目管理界面
Drmo支持课件目录的管理功能;
(1)如果需要创建一个属于自己的作品，可以点击界面左上方“新建项目”按钮，如图所示
(2)或者点击页面右侧的历史文件，如图所示：
2.3 预览界面
在预览界面,可以进行作品的录制,录制完成后,点击浏览按钮,快速跳转到视频存储的位置


2.4 编辑界面
2.4.1菜单栏


(1)文件
1) 新场景:点击会创建一个空白的场景;
ps:在当前版本中若点击新场景会出现提示，提示信息如图所示


2）保存：保存当前作品的事件配置，如是第一次保存，将会弹出窗口选择保存位置,如图所示：

3）另存为：出现一个另存为确认框，可以为作品重新命名并且另外选择位置储存，可以起到备份的作用，如图所示：

4）项目:  弹出项目管理界面;
5)  导入资源: 
6)  从文件导入资源: 
7)  关闭: 关闭编辑操作界面,进入预览界面 ;
(2)文件
1)撤销: 还原上一次所做的操作,最多50步;
2)重置: 重做已还原的操作;
3)复制: 将物品拷贝一份完全一样的;
4)粘贴: 将复制的物品粘贴到指定位置;
5)删除: 删除当前所选中的物品;
6)播放: 播放当前所做的动画逻辑;
7)停止: 停止播放;
8)设置: 对于编辑器内的相关功能界面进行的设置；

(3)游戏物体
1)创建空物体: 可以用来修改物品和物品之间的父子关系、调整结构、做锚点的作用;
2)创建空子物体: 在现有的物品上创建一个空的子物体;
3)3D物品: 里面包含方形体、圆形体、胶囊体、圆柱体、平面、四方体、地形,可以自由变形添加材质等;
4)灯光: 创建平行光、点光源、聚光灯,可以调整光的角度位置;
   ps:平行光,这种类型的灯光可以被放置在无穷远处，可以影响场景中的一切游戏对象;
   点光源,从一个位置向四面八方发出光线，影响其范围内的所有对象，类似灯泡的照明效果;
平行光,这种灯光从一点发出，在一个方向按照—个锥形的范围照射，该锥形是由聚光灯角度;
5)相机: 相机是一个能够为玩家捕获并显示游戏世界的设备。通过操纵相机，我们可以使得我们的游戏场景以更加真实和独特的方式显示出来;
(4)窗口
1)布局: 编辑界面可以快速的切换到默认的布局;
2)一般: 里面包含场景、游戏、属性栏、层级窗口、项目文件、控制台、动画,可对界面中的面板进行显示和隐藏;
(5)帮助
1)关于我们: 
2.4.2工具栏

(1)播放: 播放当前所做的动画逻辑;
(2)撤销: 还原上一次所做的操作,最多50步;
(3)重置: 重做已还原的操作;
(4)保存: 保存当前作品的事件配置;
(5)抓手: 拖动界面是以XY轴进行平移,在移动工具和选择工具中,按住鼠标中键就是抓手的功能;
(6)移动: 可以对物体进行移动,会有三个箭头,红绿蓝对应着XYZ轴;
(7)旋转: 可以对物体进行旋转,红绿蓝对于XYZ轴;
(8)缩放: 可以对物体的长宽高进行增大或缩小;
(9)变形: 能够在移动、缩放、旋转、倾斜、扭曲和透视扭曲等模式之间进行切换
(10)手柄工具处于活动对象的旋转状态: 默认状态是以世界整体的方向进行操作,选中之后是以自身的左右进行操作,如图所示(第一张是默认状态下,第二张是选中状态下)

(11)手柄工具被放置在选择的中心:
2.4.3资源栏
可以通过该面板快速将需要的本地资源找到并放置到场景中,左侧为物品的分类,右侧为具体的物品,可以将物品拖动到场景中进行使用;

2.4.4属性栏
属性: 物体的显示和隐藏,重命名,以及层级配合着相机使用;

变量: 用数值进行物品的位置,旋转的角度,以及缩放大小的调整;

网格过滤器:  从资源中获取网格并将其传递给网格渲染器以便在屏幕上渲染;

方形碰撞器: 

网格渲染器: 渲染一个网格。它与同一个对象上的网格过滤器组件一起使用；网格渲染器渲染 网状过滤器引用的网格;

材料:使用材质可描述表面的外观。材质和着色器紧密相连；总是通过着色器使用材质;

AudioListener: 监听器在 3D 空间中的表示。该类实现了类似麦克风的设备。它录制周围的声音并通过玩家的扬声器进行播放。 一个场景中只能有一个监听器。

音频源: 在场景中播放音频剪辑。剪辑的音源可通过音频监听器或者混音器播放。音频源可播放任何类型的音频剪辑，可设置以 2D、3D 或混合模式播放;

相机: 是为玩家捕捉和展示世界的设备。通过自定义和操纵摄像机，您可以让自己的游戏呈现出真正的独特性。在场景中可拥有无限数量的摄像机。这些摄像机可设置为以任何顺序在屏幕上任何位置或仅在屏幕的某些部分进行渲染;

胶囊体碰撞器: 由两个半球与一个圆柱体连接在一起组成,胶囊碰撞体与胶囊原始碰撞体的形状相同;

DefultScripts: 可在这里输入创建好的逻辑的名称;

刚体 固定连接: 关节组件将刚体连接到另一个刚体或空间中的固定点。关节施加使刚体移动的力，而关节限制功能可以限制该移动;

矩形变量 GridLayoutGroup:

铰链接合: 将两个刚体组合在一起，对刚体进行约束，让它们就像通过铰链连接一样移动。铰链关节非常适合用于门，但也可用于模拟链条、钟摆等对象;

HorizontalLayoutGroup:

LayoutElement: 如果要覆盖布局元素的最小大小、偏好大小或灵活大小，可通过向游戏对象添加布局元素组件来实现;

灯光: 是 Unity 光照功能的主要控制点。使用 Lighting 窗口调整与场景中的光照有关的设置，并根据质量、烘焙时间和存储空间来优化预计算的光照数据;

网格碰撞器: 

网格过滤器: 

 NavMeshAgent: 为关卡烘焙导航网格后，即可创建能够在场景中导航的角色了。我们将使用圆柱体构建原型代理，并将代理设置为运动状态

NavMeshDebugController:

NavMeshLink:

NavMeshModlfier:

NavMeshModifierVolunme: 

NavMeshObstacle:

NavMeshSurface:

矩形变量：

刚体：

运行时动画控制机：允许您为角色或对象安排和维护一组动画剪辑以及关联的动画过渡。在大多数情况下，拥有多个动画并在满足某些游戏条件时在这些动画之间切换是很常见的；

人物蒙皮网格渲染器：渲染一个可变形的网格。可变形网格包括蒙皮网格（具有骨骼和绑定姿势的网格）、具有混合形状的网格和运行布料模拟的网格。

Skybox：组件会覆盖由同一游戏对象上的摄像机绘制的天空盒。此组件使您可以控制摄像机渲染的天空盒；当场景中有多个摄像机并希望根据摄像机绘制不同的天空盒时，此组件很有用；

圆形碰撞器：

弹簧链接：将两个刚体连接在一起，但允许两者之间的距离改变，就好像它们通过弹簧连接一样；

地形：

Transform：（显示不出来）
VerticalLayoutGroup：




2.4.5对象列表

(1)隐藏对象列表按钮: 对象列表默认是打开状态。点击隐藏对象列表按钮即可隐藏，可在菜单栏窗口里面调出;
(2)对象列表搜索栏: 可以在搜索栏内搜索对象列表中的对象;
(3)对象名称: 记录对象列表里面对象的名称以及对象的物体ID;
(4)对象父子关系: 如果要将一个物件作为另一个物件的子级，只要在对象列表上面将子级的物件移拖拽到相应父级物件上面松开鼠标即可;
在某一对象上鼠标右键,可以调出针对该对象的一个快捷栏,详细如下图:

2.4.6项目文件
（1）可将非官方资源添加到项目文件里，方便操作，如脚本，模型，材质，图片，音频，动画等
（2）可以右击新建创建材质，动画，脚本，BE脚本
（3）BE脚本在逻辑值进行编辑行为，选择物体后在属性栏进行连接BE脚本
2.4.7逻辑轴

2.4.8动画

三、常见操作介绍
3.1 基本操作
 3.1.1. 前后左右移动
在场景中可以长按鼠标右键再使用键盘W/A/S/D键来进行前后左右的移动,E键上升,Q键下降;
3.1.2. 物体移动
使用鼠标左键选中物体,选择移动工具,点击并拖拽红色箭头,物体以X轴左右移动,点击并拖拽绿色箭头,物体以Y轴上下移动,点击并拖拽蓝色按钮,物体以Z轴前后移动,也可以点击两个箭头的交界处并拖拽进行两个轴的移动;
3.1.3.物体旋转
使用鼠标左键选中物体,选择旋转工具, 点击并拖拽红色线条,物体以X轴缩放,点击并拖拽绿色线条,物体以Y轴缩放,点击并拖拽蓝色线条,物体以Z轴缩放,也可以点击并拖拽线条的交界处进行全局旋转;
3.1.4.物体缩放
使用鼠标左键选中物体,选择缩放工具, 点击并拖拽红色线条,物体以X轴旋转,点击并拖拽绿色线条,物体以Y轴旋转,点击并拖拽蓝色线条,物体以Z轴旋转,也可以点击并拖拽灰色方块进行全局缩放;
3.1.4.物体的父子级
   在对象列表中将对象1拖动到对象2上,对象1就成为对象2的子集,在对象2(父级)上进行操作,例如移动旋转,身为子集的对象2也会跟着移动旋转;
3.2 录像操作
