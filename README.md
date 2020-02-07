# FlyWithPython
Slides from the 7th PyData Salamanca MeetUp

## Fly With Python Slides

### Using Jupyter: From simple personal notebooks to large deployments with thousands of users

The project Jupyter (https://jupyter.org/) has revolutionized the world of research and data science in the last years. It
comprises a lot of different subprojects, including the Jupyter Notebook web app, the kernels, the Docker images including
modern data science software, JupyterHub, etc.

A lot of people, researchers, and developers use software from this project each day, but, do we know how to take advantage 
of its full potential?

In this talk, we will give a practical overview of the different features of Jupyter-related applications and environments, 
ranging the contents from the regular personal use to explain how to enable cooperative Jupyter environments for thousands 
of users.

[Juan Cruz-Benito](https://github.com/cbjuan) - Senior Software Engineer @ IBM Researc

You can also find this talk in "<https://github.com/cbjuan/pydata-salamanca-talk-2020>"

### Is it a bird? Is it a plane? Accelerating Python with numba

We are lucky there are very diverse solutions to make Python faster that have been in use for a while: from wrapping compiled languages
(NumPy), to altering the Python syntax to make it more suitable to compilers (Cython), to using a subset of it which can in turn be
accelerated (numba), and many many more. However, each of these options has a tradeoff, and there is no silver bullet.

Some years ago I chose numba for poliastro, my personal project, because of its simplicity, effectiveness, and not having to learn a
hybrid dialect of Python. numba compiles numerical Python code on the fly using the LLVM machinery, producing extremely performant code...
when it works!

On the other hand, even though it is quite mature as a library and most of the Python syntax and NumPy functions are supported, there are
still some limitations that affect its usage. In particular, I strive to offer a high-level API with support for physical units (extensions
of NumPy) and reusable functions which can be passed as arguments, which sometimes require using complex objects or introspective Python
behavior which is not available.

In this talk we will introduce numba, describe its basic usage, and then discuss the strategies and workarounds we have developed to
overcome its limitations, as well as some advanced numba features we can leverage. We will focus mostly on CPUs, and mention very briefly
its GPU capabilities.

[Juan Luis Cano Rodríguez](https://github.com/Juanlu001) - Mission Planning & Execution Engineer @ Satellogic

You can also find this talk in "<https://github.com/Juanlu001/talk-numba>"
