# PagePeek – C++ PDF Viewer and Editor

PagePeek is a native PDF viewer and annotation tool developed in modern C++. It offers multi-page navigation, accurate text rendering, and is designed for future expansion with features like highlights and in-document annotations.

## Features
- Page navigation (next/previous)
- Text layer rendering
- Basic annotation interface (WIP)
- Keyboard and mouse interaction
- Lightweight UI using SDL2

## Technologies Used
- C++17
- Poppler (PDF rendering backend)
- SDL2 (window/input system)
- OpenGL (for custom drawing)
- FreeType (text rendering)
- CMake

## Build Instructions

> **Note:** Poppler and SDL2 must be installed on your system.

```bash
git clone https://github.com/youruser/cpp-pdf-editor.git
cd cpp-pdf-editor
mkdir build && cd build
cmake ..
make
./PagePeek
```

License
This project is licensed under the MIT License.
