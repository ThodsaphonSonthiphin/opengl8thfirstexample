opengl8thfirstexample
=====================

OpenGL Redbook 8th Edition First Example

I've had a couple people state that this program no longer produces a triangle. I checked that it still builds on my Mac Mini, but it doesn't have a real card. My machine with a GeForce GT 610 couldn't run it after trying for a few hours with a fresh Ubuntu after the insane loading of the related libraries and tweaking to conform to the current libraries. Sadly, I'm the proud owner of a black box again when executing the program. I was going to delete this repo, but since it worked at one time there might be a configuration that works for somebody. Setting this up has not been a good experience on Linux.

Find a better example unless you want to be aggravated. You've been warned.

Compile with
============
g++ -g -o tri triangles.cpp LoadShader.cpp -lglut -lGLEW -lGLU -lGL -lX11 -lm

john@zerofluid:~/Downloads/openglfirst/another/opengl8thfirstexample$ glxinfo | grep OpenGL
OpenGL vendor string: NVIDIA Corporation
OpenGL renderer string: GeForce GT 610/PCIe/SSE2
OpenGL version string: 4.3.0 NVIDIA 313.30
OpenGL shading language version string: 4.30 NVIDIA via Cg compiler
OpenGL extensions:

john@zerofluid:~/Downloads/openglfirst/another/opengl8thfirstexample$ uname -a
Linux zerofluid 3.8.0-26-generic #38-Ubuntu SMP Mon Jun 17 21:43:33 UTC 2013 x86_64 x86_64 x86_64 GNU/Linux

Someone on StackOverflow sent me triso.cpp as a one file version of the introductory program. Whoever you are: thank you very much again. I really appreciate it.
