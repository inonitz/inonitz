<!-- ========================================================================
     profile README  ->  repo: github.com/inonitz/inonitz
     Base: orhun (dense/table-driven) + Othneildrew header
     Badges: Ileriayo/markdown-badges (reference-style links at bottom)
     Stats cards removed: public github-readme-stats instance is rate-limited (503).
     ======================================================================== -->

# inonitz

### low-level C++ &middot; autonomous &amp; ML systems &middot; OS &amp; GPU compute

![C++][cpp-badge]
![C][c-badge]
![Python][py-badge]
![Assembly][asm-badge]
![GLSL][glsl-badge]
![OpenGL][gl-badge]
![Vulkan][vk-badge]
![CMake][cmake-badge]

Systems programmer. I build autonomous &amp; ML-driven systems, speech-recognition
pipelines, operating systems & GPGPU compute systems - Mostly From Scratch, also do integration work.

**Currently** &middot; [groundstation](https://github.com/inonitz/groundstation)
(autonomous drone flight management) and
[sttserv](https://github.com/inonitz/sttserv) (multi-model speech recognition).

---

### Featured

![stars](https://img.shields.io/github/stars/inonitz/groundstation?style=flat-square&label=%E2%98%85&color=e3b341&labelColor=30363d) &nbsp;**[groundstation](https://github.com/inonitz/groundstation)** &nbsp;`C++` &middot; ML-driven autonomous drone flight management via a natural-voice command interface.

![stars](https://img.shields.io/github/stars/inonitz/sttserv?style=flat-square&label=%E2%98%85&color=e3b341&labelColor=30363d) &nbsp;**[sttserv](https://github.com/inonitz/sttserv)** &nbsp;`C++ / Python` &middot; speech-recognition (ASR) abstraction over Sherpa-ONNX and whisper.cpp; English-first, Hebrew-capable.

---

### Selected work

| project | | stack |
|---|---|---|
| ![stars](https://img.shields.io/github/stars/inonitz/PrimOS?style=flat-square&label=%E2%98%85&color=e3b341&labelColor=30363d) &nbsp;[**PrimOS**](https://github.com/inonitz/PrimOS) | UEFI bootloader + kernel (see also [x86-smp-boot](https://github.com/inonitz/x86-smp-boot)) | `C` |
| ![stars](https://img.shields.io/github/stars/inonitz/tailslayer_win32?style=flat-square&label=%E2%98%85&color=e3b341&labelColor=30363d) &nbsp;[**tailslayer_win32**](https://github.com/inonitz/tailslayer_win32) | Windows DRAM tail-latency via channel-replicated, hedged memory reads | `C++` |
| ![stars](https://img.shields.io/github/stars/inonitz/compute-shader-fluid-2d?style=flat-square&label=%E2%98%85&color=e3b341&labelColor=30363d) &nbsp;[**compute-shader-fluid-2d**](https://github.com/inonitz/compute-shader-fluid-2d) | real-time 2D fluid (GPU Gems ch. 38, OpenGL compute shaders) | `C++` |
| ![stars](https://img.shields.io/github/stars/inonitz/glsl-compute-raytracer?style=flat-square&label=%E2%98%85&color=e3b341&labelColor=30363d) &nbsp;[**glsl-compute-raytracer**](https://github.com/inonitz/glsl-compute-raytracer) | GPU compute-shader raytracer, cross-platform (Windows/Linux) tech demo | `C++` |
| ![stars](https://img.shields.io/github/stars/inonitz/util2?style=flat-square&label=%E2%98%85&color=e3b341&labelColor=30363d) &nbsp;[**util2**](https://github.com/inonitz/util2) | cross-platform C/C++ utility library: allocators, hashing, RNG, ABI-stable C API | `C++` |

<details>
<summary><b>Full stack</b></summary>

<br>

**Languages:** C++, C, Python, x86-64 Assembly, GLSL, C#

**GPU / Graphics:** OpenGL compute, GLSL, Vulkan, SPIR-V, glbinding, GLFW, Dear ImGui, SDL3, shaderc, GLM

**Systems / OS:** UEFI (GNU-EFI), x86-64 boot, QEMU/OVMF, Win32, MemProcFS, miniaudio

**ML / AI:** llama.cpp, whisper.cpp, Sherpa-ONNX, faster-whisper, CTranslate2, Transformers/PyTorch, ONNX Runtime, NumPy

**Robotics:** PX4, Gazebo, OpenVINS, StellaVSLAM, GStreamer, OpenCV, Eigen

**Build / Test:** CMake, premake5, Ninja, Docker, GoogleTest, Google Benchmark, GitHub Actions

</details>

---

### Stats

<img height="150" src="https://github-stats-extended.vercel.app/api?username=inonitz&show_icons=true&hide_border=true&theme=github_dark" alt="inonitz GitHub stats" />
<img height="150" src="https://github-stats-extended.vercel.app/api/top-langs/?username=inonitz&layout=compact&hide_border=true&hide=objective-c,lua,makefile&theme=github_dark" alt="Most used languages" />

<!-- OPTIONAL: WakaTime (profile stays PRIVATE; aggregate language %s only, no repo names).
     Enable athul/waka-readme, add WAKATIME_API_KEY secret, then uncomment: -->
<!--START_WAKA-->
<!--END_WAKA-->

<div align="right"><sub><a href="https://github.com/inonitz">github.com/inonitz</a></sub></div>

<!-- ===================== reference-style badge links ====================== -->
[cpp-badge]:   https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white
[c-badge]:     https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black
[py-badge]:    https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[asm-badge]:   https://img.shields.io/badge/x86--64%20Assembly-6E4C13?style=for-the-badge
[glsl-badge]:  https://img.shields.io/badge/GLSL-1E5A8A?style=for-the-badge
[gl-badge]:    https://img.shields.io/badge/OpenGL-5586A4?style=for-the-badge&logo=opengl&logoColor=white
[vk-badge]:    https://img.shields.io/badge/Vulkan-AC162C?style=for-the-badge&logo=vulkan&logoColor=white
[cmake-badge]: https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white
