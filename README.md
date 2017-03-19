WebGL 2 Examples
================

Rendering algorithms of varying complexity implemented in raw WebGL 2.

Currently include:
- [Simple Triangle](https://tsherif.github.io/webgl2examples/triangle.html) (vertex arrays)
- [Phong-shaded Cube](https://tsherif.github.io/webgl2examples/cube.html) (vertex arrays, uniform buffers)
- [Deferred Rendering](https://tsherif.github.io/webgl2examples/deferred.html) (vertex arrays, uniform buffers, multiple render targets, float textures, EXT_color_buffer_float)
- [Particles](https://tsherif.github.io/webgl2examples/particles.html) (vertex arrays, uniform buffers, transform feedback)

All examples are implemented in a single HTML file (aside from a few geometry/xform array utilities) with minimal branching. The goal is to allow the reader to easily see, in sequential order, all GL calls that are made.

These examples can be thought of as companion to Shrek Shao and Trung Le's excellent [WebGL 2 Samples Pack](http://webglsamples.org/WebGL2Samples/). While their samples demonstrate individual features of WebGL 2, this project aims to show how those feature are used to implement commonly-used algorithms.
