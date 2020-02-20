# GP-GLSL
这是一个学习GLSL并且准备做GP的小项目, 预计代码量在2000
## prepare
includes 和 libs文件中的内容来自网站下载后编译  
下载内容已经放进了prepare文件夹, 编译文件未提供, 请自行cmake编译  
其中glfw需要cmake编译, glad和glm可直接copy使用  

prepare文件说明:  
[glad.zip(version3.3, Core))](https://glad.dav1d.de/)  
[glfw-3.3.2.zip(Source package)](https://www.glfw.org/download.html)  
[glm-stable.zip](https://glm.g-truc.net/0.9.9/index.html)  

GP-GLSL文件说明:  
[stb_image.h](https://raw.githubusercontent.com/nothings/stb/25a2596b2fee5041f8a55fd7317d0ffe90abc198/stb_image.h)
GP-GLSL是用Visual Studio2019创建的工程  
shaderfile文件夹内是各个章节用到的着色器文件  
其中.vs是顶点着色器文件, .fs是片元着色器文件  
## 使用
直接下载内容, 打开GP-GLSL/GP-GLSL.vcxproj  
在解决方案资源管理器中右击项目, 选择属性->VC++目录:  
包含目录配置为includes文件夹, 库目录配置为libs文件夹  
链接器的输入应该包含: glfw3.lib和opengl32.lib  

如果配置无效, 可下载release中v0.1版本, 拷贝VS项目中.vs文件到最新项目中
再配置相关属性即可

