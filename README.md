# XR-knowledge
a series knowledge, including unity, AR, VR et.

## 1 unity 
### 1.1 basic software
#### 1.1.1 界面
transform 改变物体大小；
#### 1.1.2 快捷键
Q W E R 切换左上角不同的工具
#### 1.1.3 mesh renderer
材质；
shader选择光照形式（标准的为standard，Unlit Shader不会参与光照计算，也可以自己写一个光照形式-create-shader-standard surface shader）
#### 1.1.4 添加其他组件
RigidBody / 刚体，让游戏对象参与物理引擎的计算；

Animator控制管理角色的动画；

AudioSource给游戏对象添加声音；

Canvas绘制二维用户界面；

ParticleSystem 产生粒子效果；
#### 1.1.5 摄像机（camera）
除了基本的操作，还可以配合场景中的Post-process Volume来给镜头添加后期处理的特效（环境光遮罩-ambient occlusion，景深-depth of field，光晕-Vignette）
#### 1.1.6 编程脚本（scripting）
使用C#脚本（MonoScript）来进行编程

选择对象，通过添加组件，输入名字快速创建一个脚本（如PlayerMovement），也可以在工程窗口中创建C#脚本，然后将脚本拖拽到对象上，双击脚本的名字可以在IDE中打开并编辑它
