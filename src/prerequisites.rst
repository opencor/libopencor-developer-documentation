.. _prerequisites:

===============
 Prerequisites
===============

The following tools are required to develop, build , test and package libOpenCOR:

- `Git <https://git-scm.com/>`__: a distributed version control system;
- `CMake <https://cmake.org/>`__ 3.15 or later: a cross-platform build system;
- C++ toolchain: a set of C++ tools.
  The toolchain is different depending on the platform you are using:

  - **Windows:** `Visual Studio Community 2022 <https://apps.microsoft.com/detail/visual-studio-community-2022/XPDCFJDKLZJLP8>`__ ( ``Desktop development with C++`` with ``MSVC v143 - VS 2022 C++ x64/x86 build tools``, ``MSVC v143 - VS 2022 C++ ARM64/ARM64EC build tools``, and ``Windows 11 SDK``);
  - **Linux:** G++ (``g++`` package) on Ubuntu 22.04 LTS; and
  - **macOS:** `Xcode <https://developer.apple.com/xcode/>`__ 16 (including its `Command Line Tools <https://developer.apple.com/downloads/?q=Command%20Line%20Tools>`__).

Additionally, you may also want to rely on the following optional tools:

- `Ninja <https://ninja-build.org/>`__ 1.8.2 or later: a small build system with a focus on speed;
- `buildcache <https://gitlab.com/bits-n-bites/buildcache>`__: a compiler cache;
- `clcache <https://github.com/frerich/clcache>`__ (Windows only): a compiler cache;
- `ccache <https://ccache.dev/>`__ (Linux/macOS only): a compiler cache;
- `ClangFormat <https://clang.llvm.org/docs/ClangFormat.html>`__: a tool to format C/C++ code;
- `Clang-Tidy <https://clang.llvm.org/extra/clang-tidy/>`__: a `Clang <https://clang.llvm.org/>`__-based C++ linter tool;
- `Black <https://black.readthedocs.io/en/stable/>`__: a tool to format Python code;
- `gcov <https://gcc.gnu.org/onlinedocs/gcc/Gcov.html>`__ and `gcovr <https://gcovr.com/en/stable/>`__: some tools to test and report on code coverage;
- `llvm-cov <https://llvm.org/docs/CommandGuide/llvm-cov.html>`__ and `llvm-profdata <https://llvm.org/docs/CommandGuide/llvm-profdata.html>`__: some tools to test and report on code coverage;
- `Valgrind <https://valgrind.org/>`__: an instrumentation framework for building dynamic analysis tools;
- `Python <https://python.org/>`__ 3.9 or later: a programming language;
- `pytest <https://pytest.org/>`__: a Python testing framework;
- `Sphinx <https://www.sphinx-doc.org/>`__: a tool to generate documentation; and
- `Doxygen <https://www.doxygen.nl/>`__: a tool to generate documentation from source code.
