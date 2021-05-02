### WebGL & WebGL2

WebGL是基于嵌入式系统开放图形库（OpenGL ES 2.0）的图形JS API，这允许支持它的浏览器在 `canvas` 元素中呈现三维元素

> WebGL 1 可以看成是OpenGL ES 2 的JS 实现。 类似的，WebGL 2 可以看做是OpenGL ES 3 的JS 实现。所以大部分的特性可以去对应到OpenGL ES 3中的特性，当然有些细节上会有出入

> WebGL is a cross-platform, royalty-free web standard for a low-level 3D graphics API based on OpenGL ES, exposed to ECMAScript via the HTML5 Canvas element. Developers familiar with OpenGL ES 2.0 will recognize WebGL as a Shader-based API using GLSL, with constructs that are semantically similar to those of the underlying OpenGL ES API. It stays very close to the OpenGL ES specification, with some concessions made for what developers expect out of memory-managed languages such as JavaScript. WebGL 1.0 exposes the OpenGL ES 2.0 feature set; WebGL 2.0 exposes the OpenGL ES 3.0 API —— [OpenGL ES for the Web](https://www.khronos.org/webgl/)

- [WebGL 工作原理](https://webglfundamentals.org/webgl/lessons/zh_cn/webgl-how-it-works.html)