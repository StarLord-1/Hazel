# Hazel

![Hazel](/Resources/Branding/Hazel_Logo_Text_Light_Square.png?raw=true "Hazel")

Hazel is primarily an early-stage interactive application and rendering engine for Windows. Currently not much is implemented, however (almost) everything inside this repository is available here as open source and ready for collaboration.

## Getting Started
Visual Studio 2019 is recommended, Hazel is officially untested on other development environments whilst I focus on a Windows build.

You can clone the repository to a local destination using git:

`git clone --recursive https://github.com/Starlord-1/Hazel`

Make sure that you do a `--recursive` clone to fetch all of the submodules!

## The Plan
The plan for Hazel is two-fold: to create a powerful 3D engine, but also to serve as an education tool for teaching game engine design and architecture. Because of this the development inside this repository is rather slow, since everything has to be taught and implemented as an assistive teaching tool. There is a much more advanced version of the engine in a private repository called `Hazel-dev`, to be released when completed. The plan for this project is to mostly take already implemented code from the `Hazel-dev` repository and integrate it into this one, done within guides/videos/images. Check my portfolio site https://portfolio-site-a770f.web.app for more projects.

### Main features to come:
- Fast 2D rendering (UI, particles, sprites, etc.)
- High-fidelity Physically-Based 3D rendering (this will be expanded later, 2D to come first)
- Support for Mac, Linux, Android and iOS
    - Native rendering API support (DirectX, Vulkan, Metal)
- Fully featured viewer and editor applications
- Fully scripted interaction and behavior
- Integrated 3rd party 2D and 3D physics engine
- Procedural terrain and world generation
- Artificial Intelligence
- Audio system
