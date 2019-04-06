V E C 4 - CREATIVE CODING / WEBGL / GLSL
========

Official repository for [https://www.facebook.com/groups/vec4glsl/](https://www.facebook.com/groups/vec4glsl/)

This is a curated list about WebGL / GLSL.

## Contents
* [Maths](#maths)
* [Frameworks](#frameworks)
* [Libraries](#libraries)
* [Tools](#tools)
* [WebGL](#webgl)
* [WebGL2](#webgl2)
* [GLSL editors](#glsl-editors)
* [Raymarching](#raymarching)
* [Text And Fonts](#text-and-fonts)
* [Books](#books)
* [References](#references)
* [Bug Reporting](#bug-reporting)
* [Selected Case Studies](#case-studies)

## Maths

  * http://immersivemath.com/ila/index.html - immersive linear algebra course

## Frameworks

> Relevant frameworks dealing with WebGL

### Complete

  * [ThreeJS](https://threejs.org/) - THE WebGl Framework. A cross-browser JavaScript library and Application Programming Interface (API) used to create and display animated 3D computer graphics in a web
    - [VedaJS](https://veda.gl/vedajs/) - Framework ThreeJS-based, shader-art oriented
    - [Whitestorm](https://whs.io/) - Framework ThreeJS-based
  * [Babylon](https://www.babylonjs.com/) - Complete JavaScript framework for building 3D games and experiences with HTML5, WebGL, WebVR, WebXR and Web Audio
  * [Playcanvas](https://playcanvas.com/) - Game engine with online editor (free for public projects)
- [RegGL](http://regl.party/) - declarative and stateless webgl

### Low-level, more vanilla approach

  * [TwglJS](http://twgljs.org/) - using the WebGL API less verbose
  * [nanoGL](https://github.com/search?l=JavaScript&q=nanogl&type=Repositories) - low-level WebGL library
  * [Phenomenon](https://github.com/vaneenige/phenomenon)- low-level WebGL library, particles-addicted

Here some comparisons:
* [ThreeJS vs BabylonJS](https://www.slant.co/versus/11077/11348/~babylon-js_vs_three-js)
* [ThreeJS vs WhiteStorm](https://www.slant.co/versus/11349/11348/~whitestorm-js_vs_three-js)

### Libraries

> Specific libraries

  * [CurtainsJS](https://www.martin-laxenaire.fr/libs/curtainsjs/) - WebGL transitions-focused library.
  * [glMatrix](http://glmatrix.net/) - Javascript matrix and vector library for high performance WebGL apps.
  * [Sylvester](http://sylvester.jcoglan.com/) - Sylvester is a vector, matrix and geometry library for JavaScript.

## Tools

> Tools for development and debugging WebGL

* [Shaping Signals Functions](http://www.iquilezles.org/www/articles/functions/functions.htm) - When writing shader or during any procedural creation process (texturing, modeling, shading, lighting, animating...) you often find yourself modifying signals in different ways so they behave the way you want.
* [Graph Toy](http://www.iquilezles.org/apps/graphtoy/) - Useful toy for shaping functions
* [Detect GPU](https://github.com/TimvanScherpenzeel/detect-gpu) - Classify GPU's based on their benchmark score in order to provide an adaptive experience.
* [GLSL Shader Editor Extension](https://github.com/spite/ShaderEditorExtension) - Chrome DevTools extension to help you edit shaders live in the browser.
* [Spector.js Extension](https://chrome.google.com/webstore/detail/spectorjs/denbgaamihkadbghdceggmchnflmhpmk) - Explore and Troubleshoot your WebGL and WebGL2 scenes easily.
* [Webgl Insight](https://github.com/3Dparallax/insight) - Chrome extension WebGL debugging toolkit providing a variety of capabilities.
* [Khronos Dev Tools](https://github.com/KhronosGroup/WebGLDeveloperTools) - Useful WebGL developer tools, intended to be used as an ES6 module.
* [Spector.js](https://spector.babylonjs.com/) - Agnostic JavaScript framework for exploring and troubleshooting your WebGL scenes.
* [WebGL Inspector](http://benvanik.github.io/WebGL-Inspector/) - Tool inspired by gDEBugger and PIX with the goal of making the development of advanced WebGL applications easier.
* [WebGl Playground](http://jessevdk.github.io/webgl-play/) - The editor lets you work on the JavaScript code and the GLSL vertex/fragment shaders (if you have any) at the same time in a convenient way. Everything is organized, formatted and highlighted properly, just as you would like.
* [WebGL Report](http://webglreport.com/?v=1) - Way to view the details of what your browser supports for WebGL.
* [WebGL Support Stats](http://webglstats.com/) - Interactive dashboard showing the support for WebGL features in different browsers and devices.
* [WebGL Texture Tester](http://toji.github.io/texture-tester/) - Attempts to load one of every texture format supported by WebGL, intended to quickly show which formats your browser/device supports.
* [Web Tracing Framework](http://google.github.io/tracing-framework/index.html) - Set of libraries, tools, and visualizers for the tracing and investigation of complex web applications.

### Chrome Specific Tools/Debugger

* [GLSL Shader Editor Extension](https://github.com/spite/ShaderEditorExtension) - Chrome DevTools extension to help you edit shaders live in the browser.
* [Spector.js Extension](https://chrome.google.com/webstore/detail/spectorjs/denbgaamihkadbghdceggmchnflmhpmk) - Explore and Troubleshoot your WebGL and WebGL2 scenes easily.
* [Webgl Insight](https://github.com/3Dparallax/insight) - Chrome extension WebGL debugging toolkit providing a variety of capabilities.

### Firefox Specific Tools/Debugger

* [Canvas Debugger](https://hacks.mozilla.org/2014/03/introducing-the-canvas-debugger-in-firefox-developer-tools/) - Quick tutorial how to use Firefox's developer tools to debug WebGL Shaders.
* [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools) - The official list of all of Firefox's debugger tools.

## WebGL

> Resources for learning WebGL / GLSL and relateds

### Learning

  * [The Book of Shaders](https://thebookofshaders.com/) - Mandatory entry-point for GLSL, by [Patricio Gonzalez Vivo](https://github.com/patriciogonzalezvivo)
  * [WebGL Fundamentals](https://webglfundamentals.org/) - Must-have WebGL journey, by [Greggman](https://github.com/greggman)
  * [A Beginners Guide](https://gamedevelopment.tutsplus.com/tutorials/a-beginners-guide-to-coding-graphics-shaders--cms-23313) - Beginner guide for coding shaders.
  * https://www.scratchapixel.com/ - Learn Computer Graphics From Scratch!
  * https://aerotwist.com/tutorials/an-introduction-to-shaders-part-1/ - Introduction to shaders.
  * http://www.webglacademy.com/ - Learn WebGL and 3D algorithmic for free.
  * https://www.tutorialspoint.com/webgl/index.htm - For all those readers who want to learn the basics of WebGL programming.
  * [Into Vertex Shaders](https://medium.com/@Zadvorsky/into-vertex-shaders-594e6d8cd804) - High-level overview of some key aspects of the 3D graphics pipeline, [@zadvorsky](https://twitter.com/zadvorsky)
  * [GLSL Shader Tutorial](https://www.shadertoy.com/view/Md23DV) - interactive fragment-shader tutorial
  * [Webgl Antipatterns tips](https://webglfundamentals.org/webgl/lessons/webgl-anti-patterns.html) - WebGL Antipatterns, by [Greggman](https://github.com/greggman)
  * [Context Loss & Preloading](https://medium.com/@mattdesl/non-intrusive-webgl-cebd176c281d#.gyc6h9mr5) - How to manage WebGL when you run into the dreaded context lost, by [Matt DesLauriers](https://github.com/mattdesl)
  *[Handling Context Loss & Restore](https://www.khronos.org/webgl/wiki/HandlingContextLost) - Another resource about context lost&&restore.
  * https://www.youtube.com/watch?v=wHdK1Mtuhm8&list=PLMlvA2UVVK3n26u5O7KFs1RbSV6dAHB0g - Video introduction to some Three.js concepts (ITA)

### Advanced (tips and optimizations)

  * https://developer.mozilla.org/en-US/docs/Games/Techniques/3D_on_the_web/GLSL_Shaders
  * http://www.iquilezles.org/www/index.htm - Rendering techniques, useful maths, coding hacks.
  * https://aerotwist.com/tutorials/an-introduction-to-shaders-part-1/
  * https://blog.demofox.org/
  * [GLSL Lighting Walktrough](https://github.com/stackgl/glsl-lighting-walkthrough) - provides an overview of the various steps involved in lighting a mesh with a custom GLSL shader.
  * [WebGL & Mask composition](https://medium.com/@Zadvorsky/webgl-masking-composition-75b82dd4cdfd) by [@zadvorsky](https://twitter.com/zadvorsky)
  * [Simple Post Processing in ThreeJS](https://medium.com/@luruke/simple-postprocessing-in-three-js-91936ecadfb7) - ThreeJS post-processing sample, by [@luruke](https://github.com/luruke)
  * [GLSL Optimizations](https://www.khronos.org/opengl/wiki/GLSL_Optimizations) - GLSL tips from Khronos
  * [ShaderToy Unofficial](https://shadertoyunofficial.wordpress.com/) - lots of valuable tips, by [FabriceN](https://www.shadertoy.com/user/FabriceNeyret2)
    - https://shadertoyunofficial.wordpress.com/2018/04/16/readings-shaders-maths-3d/
    - https://shadertoyunofficial.wordpress.com/2019/01/26/classical-corner-cases/
    - https://shadertoyunofficial.wordpress.com/2019/01/15/case-study-making-dot-pattern-loopless/
  * [Best Practices from Apple's guide](https://developer.apple.com/library/archive/documentation/3DDrawing/Conceptual/OpenGLES_ProgrammingGuide/BestPracticesforShaders/BestPracticesforShaders.html#//apple_ref/doc/uid/TP40008793-CH7-SW3)
  * https://www.khronos.org/registry/OpenGL-Refpages/
  * https://www.ronja-tutorials.com/ - Unity Related articles
  * https://alastaira.wordpress.com/2015/08/07/unity-shadertoys-a-k-a-converting-glsl-shaders-to-cghlsl/  - Unity Related articles

## GLSL editors

> resources / tools/ editors for GLSL prototyping
>
> NOTE: [WebGL must conform to The OpenGL ES Shading Language, Version 1.00](https://www.khronos.org/registry/webgl/specs/1.0.3/#4.3)
>
> [Official Specs for GLSL Version 1.00](https://www.khronos.org/registry/OpenGL/specs/es/2.0/GLSL_ES_Specification_1.00.pdf)
> [Official Specs for Open ES Version 2.0.25](https://www.khronos.org/registry/OpenGL/specs/es/2.0/es_full_spec_2.0.pdf)

* http://www.shadertoy.com From IQ ( Inigo Quilez ) THE place for Shader
* http://glslsandbox.com/  just like ShaderToy, live shader editor
* https://www.vertexshaderart.com/ - like ShaderToy, but dedicated to vertex shader computations, by [Greggman](https://github.com/greggman)
* http://www.interactiveshaderformat.com/ - Originally created by VDMX VJ software, it is a interactive version of GLSL.
* http://www.cdglabs.org/Shadershop/ - From Toby Schachman, interesting approach of visualizing math and glsl functions.
* [glslEditor](https://github.com/patriciogonzalezvivo/glslEditor) - another GLSL shader editor, by [Patricio Gonzalez Vivo](https://github.com/patriciogonzalezvivo)
* http://shdr.bkcore.com/ From Thibaut Despoulain - simple live shader editor.
* https://godotengine.org/article/visual-shader-editor-back
* http://syntopia.github.io/Fragmentarium/
* https://www.gsn-lib.org/docs/nodes/ShaderPluginNode.php
* https://hexler.net/software/kodelifes
* https://shadergif.com/
* https://cables.gl/home

## WebGL2

> resources about WebGL2

* [WebGL1 to WebGL2](https://webgl2fundamentals.org/webgl/lessons/webgl1-to-webgl2.html) - WebGL1 to WebGL2 migration.
* [WebGL Examples](https://github.com/shrekshao/webgl2examples) - WebGL2 examples.
* [PicoGL.js](https://tsherif.github.io/picogl.js/) - Minimal WebGL 2-only rendering library, by [Tarek Sherif](https://github.com/tsherif)

## Ray Marching

> about raymarching

* http://www.michaelwalczyk.com/blog/2017/5/25/ray-marching - Quick tutorial on setting up a basic ray marching shader.
* http://mercury.sexy/hg_sdf/ - A GLSL library for building signed distance functions (SDF), from Mercury demoscene group.

## Text And Fonts

> how-to/infos about text and fonts rendering in WebGL

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

## References

> WebGL references

* [Google Project ANGLE](https://github.com/google/angle) - Default WebGL backend for both Google Chrome and Mozilla Firefox on Windows platforms.
* [Khronos Official Wiki](https://www.khronos.org/webgl/wiki/) - The official wiki for WebGL.

## Bug Reporting

> Reporting bugs helps everyone in long run

* [Chrome Bug Report](https://bugs.chromium.org/p/chromium/issues/list) - Chrome related bugs
* [Khronos Github Issue Page](https://github.com/KhronosGroup/WebGL/issues) - Spec or Conformance related bugs
* [Mozilla BugZilla](https://bugzilla.mozilla.org) - Firefox related bugs
* [WebKit Bugzilla](https://bugs.webkit.org/enter_bug.cgi?assigned_to=cmarrin%40apple.com&attachurl=&blocked=&bug_file_loc=http%3A%2F%2F&bug_severity=Normal&bug_status=NEW&comment=&component=WebGL&contenttypeentry=&contenttypemethod=autodetect&contenttypeselection=text%2Fplain&data=&dependson=&description=&flag_type-1=X&flag_type-3=X&form_name=enter_bug&keywords=&maketemplate=Remember%20values%20as%20bookmarkable%20template&op_sys=Mac%20OS%20X%2010.5&priority=P2&product=WebKit&rep_platform=PC&short_desc=&version=528%2B%20%28Nightly%20build%29) - Safari related bugs

## Books

> Popular books about WebGL

* [Interactive Computer Graphics: A Top-Down Approach with WebGL](https://www.amazon.com/Interactive-Computer-Graphics-Top-Down-Approach/dp/0133574849) by **Edward Angel** and **Dave Shreiner** - Suitable for undergraduate students in computer science and engineering, for students in other disciplines who have good programming skills, and for professionals interested in computer animation and graphics using the latest version of WebGL.
* [Professional WebGL Programming](https://www.amazon.com/Professional-WebGL-Programming-Developing-Graphics/dp/1119968860) by **Andreas Anyuru** - Everything you need to know about developing hardware-accelerated 3D graphics with WebGL.
* [Programming 3D Applications with HTML5 and WebGL](https://www.amazon.com/Programming-Applications-HTML5-WebGL-Visualization/dp/1449362966) by **Tony Parisi** - Create high-performance, visually stunning 3D applications for the Web, using HTML5 and related technologies such as CSS3 and WebGL—the emerging web graphics standard.
* [WebGL Beginner's guide](https://www.amazon.com/WebGL-Beginners-Guide-Diego-Cantor/dp/184969172X) by **Diego Cantor** and **Brandon Jones** - For JavaScript developer who wants to take the plunge into 3D web development via WebGL.
* [WebGL Hotshot](https://www.amazon.com/WebGL-Hotshot-Mitch-Williams-ebook/dp/B00KLAJ65Y) by **Mitch Williams** - For web designer looking to expand your knowledge of 3D graphics concepts and broaden your existing skill set.
* [WebGL Insights](https://github.com/WebGLInsights/WebGLInsights.github.io/releases/download/v1.0/WebGL.Insights.-.Patrick.Cozzi.pdf) by **Patrick Cozzi** - Presents real-world techniques for intermediate and advanced WebGL developers by assembling contributions from experienced WebGL engine and application developers, GPU vendors, browser developers, researchers, and educators.
  * [Book's Personal Site](http://www.webglinsights.com/)
* [WebGL Programming Guide: Interactive 3D Graphics Programming with WebGL](https://www.amazon.com/WebGL-Programming-Guide-Interactive-Graphics/dp/0321902920) by **Kouichi Matsuda** and **Rodger Lea** - WebGL Programming Guide will help you get started quickly with interactive WebGL 3D programming, even if you have no prior knowledge of HTML5, JavaScript, 3D graphics, mathematics, or OpenGL.

## Case Studies

* Curated [case-study collection](https://github.com/luruke/awesome-casestudy) by [@luruke](https://github.com/luruke)
