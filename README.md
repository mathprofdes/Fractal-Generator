# Fractal Generator

The Fractal Generator is designed to display images produced from complex and real parametric dynamical systems. Its main purpose is to allow the user to experiment with their own formulas in the dynamical system. To this end, equations are not hard coded into this program, all equations are input by the user, parsed by the program, and evaluated through general expression evaluation methods. Thus, the generation of images is much slower then if the formulas had been hard coded. On the other hand, the user is not limited to viewing only specific fractal families, as they would be with programs that hard code formulas.  The program does use multi-threading in the calculations to speed up the evaluation and the user can set the number of calculation threads from the program menu.  

If you simply wish to explore the Mandelbrot set, there are far faster programs to do that out there, even freeware and open-source packages. You can explore the Mandelbrot set with this program, but other programs will be faster, many close to real-time generation. This program was written for those who wish to explore general complex and real plane iterative systems, so if you want to explore z = cosh(z^3)+ z^(1/3) + c or a Newton's Method fractal for the complex sine function (z = z - tan(z)), and are willing to give up a little speed, download and enjoy.  This is a Java application, so if the Java JRE is not installed on your computer download and install the current version of the Java JRE (Version 8 or later).

The software is being distributed as an executable jar file. In most cases you can simply download the FractalGenerator.jar file (raw file), from the version directory and double-click it from your system's file browser. You can also run it from the command-line with

`java -jar FractalGenerator.jar`

The software was created using the older Java Swing API, so the appearance is a little retro. This software has been tested on Windows 10 and 11, Linux Mint 21, and MacOS Mojave.

**Program Features**

- General formula dynamical systems.
- Complex plane systems and real plane parametric systems.
- Escape and convergence mode bailouts.
- Inverse complex plane graphing.
- All options are user editable.
- History window.
- Image resizing option to various set sizes as well as custom sizes.
- Multi-Threading options for more efficient use of the CPU.
- Fractal information saving and loading.
- Mouse options for zooming and recentering.
- Image saving and copying.
- Display image auto-resizing.
- Animation Image Sequence Creator.
- Color scheme options for both inside color schemes and outside color schemes.
- Color data storage options.
- Independent editable color palettes.

---

**Third Party Software Used**

- Oracle Help for Java: (Oracle): The help system.
