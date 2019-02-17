VEC4
========

Official repository for [https://www.facebook.com/groups/vec4glsl/](https://www.facebook.com/groups/vec4glsl/)

This is a curated list about WebGL / GLSL.

## What is WebGL

WebGL (Web Graphics Library) is a JavaScript API for rendering interactive 3D computer graphics and 2D graphics within
any compatible web browser without the use of plug-ins. WebGL is integrated completely into all the web standards
of the browser allowing GPU accelerated usage of physics and image processing and effects as part of the web page canvas.

WebGL elements can be mixed with other HTML elements and composited with other parts of the page or page background.
WebGL programs consist of control code written in JavaScript and shader code that is executed on a computer's Graphics
Processing Unit (GPU).

## Contents
* [Frameworks](#frameworks)
* [Tools](#tools)
* [Learning](#webgl)
* [WebGL 2](#webgl-2)
* [GLSL editors](#glsl-editors)
* [Raymarching](#raymarching)
* [Text && Fonts](#text-fonts)
* [Selected Case Studies](#case-studies)
* [Text && Fonts](#books)

## Frameworks

> Relevant frameworks dealing with WebGL

- complete
  * https://threejs.org/ - THE WebGl Framework
    - https://veda.gl/vedajs/ - useful for Shader Art
    - https://whs.io/ - Framework for developing 3D web apps with physics.
  * https://www.babylonjs.com/
- http://regl.party/ - declarative and stateless webgl
- low-level
  * http://twgljs.org/ - using the WebGL API less verbose
  * https://github.com/search?l=JavaScript&q=nanogl&type=Repositories - NanoGL
  * https://github.com/vaneenige/phenomenon - low-level WebGL library, particles-addicted

### Engines

* https://playcanvas.com/ - Game engine with online editor (free for public projects)


### Tools

> Specific libraries

  * [CurtainsJS](https://www.martin-laxenaire.fr/libs/curtainsjs/) - WebGL transitions focused lib
  * [glMatrix](http://glmatrix.net/) - Javascript matrix and vector library for high performance WebGL apps.
  * [Sylvester](http://sylvester.jcoglan.com/) - Sylvester is a vector, matrix and geometry library for JavaScript.


## Tools

> Tools for development and debugging WebGL

* https://webglstats.com/ - The statistics on this site help WebGL developers make decisions about hardware capabilities.
* http://webglreport.com/ - Check your WebGL client support
* [GLSL Shader Editor Extension](https://github.com/spite/ShaderEditorExtension) - Chrome DevTools extension to help you edit shaders live in the browser.
* [Spector.js Extension](https://chrome.google.com/webstore/detail/spectorjs/denbgaamihkadbghdceggmchnflmhpmk) - Explore and Troubleshoot your WebGL and WebGL2 scenes easily.
* [Webgl Insight](https://github.com/3Dparallax/insight) - Chrome extension WebGL debugging toolkit providing a variety of capabilities.


## Learning

- Basics
  * https://thebookofshaders.com/
  * https://gamedevelopment.tutsplus.com/tutorials/a-beginners-guide-to-coding-graphics-shaders--cms-23313
  * https://www.scratchapixel.com/
  * https://aerotwist.com/tutorials/an-introduction-to-shaders-part-1/
  * https://webglfundamentals.org/
  * http://www.webglacademy.com/
  * https://www.tutorialspoint.com/webgl/index.htm
  * https://www.shadertoy.com/view/Md23DV - nice interactive tutorial for GLSL
  * https://webglfundamentals.org/webgl/lessons/webgl-anti-patterns.html
  * http://immersivemath.com/ila/index.html
- Videos
  * https://www.youtube.com/watch?v=wHdK1Mtuhm8&list=PLMlvA2UVVK3n26u5O7KFs1RbSV6dAHB0g - Introduction to some Three.js concepts ITA
- Advanced (maths, tips, optimizations)
  * https://webglfundamentals.org/ - must-have from Greggman/TwglJS
  * https://developer.mozilla.org/en-US/docs/Games/Techniques/3D_on_the_web/GLSL_Shaders
  * https://medium.com/@Zadvorsky/into-vertex-shaders-594e6d8cd804
  * http://www.iquilezles.org/www/index.htm - Rendering techniques, useful maths, coding hacks…
  * https://aerotwist.com/tutorials/an-introduction-to-shaders-part-1/
  * https://blog.demofox.org/
  * https://medium.com/@luruke/simple-postprocessing-in-three-js-91936ecadfb7
  * https://www.khronos.org/opengl/wiki/GLSL_Optimizations
  * from ShaderToy Master [FabriceN](https://www.shadertoy.com/user/FabriceNeyret2) lots of valuable tips:
    - https://shadertoyunofficial.wordpress.com/
    - https://shadertoyunofficial.wordpress.com/2018/04/16/readings-shaders-maths-3d/
    - https://shadertoyunofficial.wordpress.com/2019/01/26/classical-corner-cases/
    - https://shadertoyunofficial.wordpress.com/2019/01/15/case-study-making-dot-pattern-loopless/
  * https://developer.apple.com/library/archive/documentation/3DDrawing/Conceptual/OpenGLES_ProgrammingGuide/BestPracticesforShaders/BestPracticesforShaders.html#//apple_ref/doc/uid/TP40008793-CH7-SW3
  * https://www.khronos.org/registry/OpenGL-Refpages/
  * https://www.ronja-tutorials.com/ - Unity Related
  * https://alastaira.wordpress.com/2015/08/07/unity-shadertoys-a-k-a-converting-glsl-shaders-to-cghlsl/  - Unity Related
  * https://medium.com/@Zadvorsky/webgl-masking-composition-75b82dd4cdfd

## GLSL editors

A list including resources / tools/ editors for GLSL prototyping:

* http://www.shadertoy.com From IQ ( Inigo Quilez ) THE place for Shader ( Inigo Quilez )
* http://glslsandbox.com/  just like ShaderToy, live shader editor
* From [Greggman](https://github.com/greggman)
  - https://www.vertexshaderart.com/ - like ShaderToy, but dedicated to vertex shader computing.
* http://www.interactiveshaderformat.com/ Originally created by VDMX VJ software, it is a interactive version of GLSL.
* http://www.cdglabs.org/Shadershop/  From Toby Schachman - interesting approach of visualizing math and glsl functions.
* From [Patricio Gonzalez Vivo](https://github.com/patriciogonzalezvivo)
  - [glslEditor](https://github.com/patriciogonzalezvivo/glslEditor) another GLSL shader editor.
  - http://editor.thebookofshaders.com/
* http://shdr.bkcore.com/ From Thibaut Despoulain - simple live shader editor.
* https://godotengine.org/article/visual-shader-editor-back
* http://syntopia.github.io/Fragmentarium/
* https://www.gsn-lib.org/docs/nodes/ShaderPluginNode.php
* https://hexler.net/software/kodelifes
* https://shadergif.com/
* https://cables.gl/home

## WebGL2

* https://webgl2fundamentals.org/webgl/lessons/webgl1-to-webgl2.html
* https://github.com/shrekshao/webgl2examples

## Raymarching

* http://www.michaelwalczyk.com/blog/2017/5/25/ray-marching
* http://mercury.sexy/hg_sdf/

## Text && Fonts

* https://webglfundamentals.org/webgl/lessons/webgl-text-html.html
* https://webglfundamentals.org/webgl/lessons/webgl-text-canvas2d.html
* https://webglfundamentals.org/webgl/lessons/webgl-text-texture.html
* https://medium.com/@calebfaith/implementing-msdf-font-in-opengl-ea09a9ab7e00
* https://delphic.me.uk/tutorials/webgl-text
* https://github.com/Jam3/three-bmfont-text/blob/master/docs/sdf.md
* https://stackoverflow.com/questions/25956272/better-quality-text-in-webgl
* https://blog.mapbox.com/drawing-text-with-signed-distance-fields-in-mapbox-gl-b0933af6f817
* http://pixelscommander.com/polygon/pixi-sdf-text/demo/
* https://github.com/donmccurdy/msdf-bmfont-web
* https://github.com/Chlumsky/msdfgen

## Case Studies

* Curated [case-study collection](https://github.com/luruke/awesome-casestudy) by [@luruke](https://github.com/luruke)

## Books

* [WebGL reference card ](https://github.com/spleennooname/vec4-glsl-webgl-group/blob/master/books/webgl-reference-card-1_0.pdf)
