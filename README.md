# GP-GLSL
这是一个学习GLSL并且准备做GP的小项目, 预计代码量在2000
## prepare
includes 和 libs文件中的内容来自网站下载后编译  
下载好的内容已经放进了prepare文件夹  
其中glfw需要cmake编译, glad可直接copy使用  
GP-GLSL是用Visual Studio2019创建的工程  

prepare文件说明:  
[glad.zip(version3.3, Core))](https://glad.dav1d.de/)  
[glfw-3.3.2.zip(Source package)](https://www.glfw.org/download.html)  
[glm-stable.zip](https://glm.g-truc.net/0.9.9/index.html)  
## 使用
直接下载内容, 打开GP-GLSL/GP-GLSL.vcxproj  
在解决方案资源管理器中右击项目, 选择属性->VC++目录:  
包含目录配置为includes文件夹, 库目录配置为libs文件夹
链接器的输入应该包含: "glfw3.lib, opengl32.lib;"(下载下来默认已包含)
即可使用  

