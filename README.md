WebGL 2 Examples
================

Rendering algorithms of varying complexity implemented in raw WebGL 2.

Currently include:
- [Just a Triangle](https://tsherif.github.io/webgl2examples/triangle.html) (vertex arrays)
- [Phong-shaded Cube](https://tsherif.github.io/webgl2examples/cube.html) (vertex arrays, uniform buffers)
- [Particles](https://tsherif.github.io/webgl2examples/particles.html) (vertex arrays, uniform buffers, transform feedback)
- [Deferred Rendering](https://tsherif.github.io/webgl2examples/deferred.html) (vertex arrays, uniform buffers, multiple render targets, float textures, texelFetch, EXT_color_buffer_float)

All examples are implemented in a single HTML file with minimal use of functions, modules, classes or other abstractions. The goal is to allow the reader to easily see, in sequential order, all GL calls that are made.

These examples can be thought of as companion to Shrek Shao and Trung Le's excellent [WebGL 2 Samples Pack](http://webglsamples.org/WebGL2Samples/). While their samples demonstrate individual features of WebGL 2, this project demonstrates how those feature can be used to implement commonly-used algorithms.
