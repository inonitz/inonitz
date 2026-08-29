<!-- ========================================================================
     DRAFT profile README  ->  repo: github.com/inonitz/inonitz
     Base: orhun (dense/table-driven) + Othneildrew header + DenverCoder1 top-half
     Curated badges: Ileriayo/markdown-badges  |  Stats: github-readme-stats
     {{confirm}} = description I guessed; verify or replace.
     ======================================================================== -->

# inonitz

### low-level C++ &middot; graphics &amp; GPU compute &middot; ML systems

![C++][cpp-badge]
![C][c-badge]
![Python][py-badge]
![CUDA][cuda-badge]
![OpenGL][gl-badge]
![Vulkan][vk-badge]
![OpenCL][cl-badge]
![CMake][cmake-badge]

Systems programmer. I build graphics engines, GPU compute kernels
(Vulkan / OpenCL / GLSL), and ML inference systems &mdash; from scratch, in C++.

**Currently** &mdash; porting **Moondream 3.1** (9B-A2B vision MoE) to `llama.cpp`
with hand-written SPIR-V / Vulkan compute kernels.

---

### Selected work

**Now**

| project | | stack |
|---|---|---|
| [**groundstation**](https://github.com/inonitz/groundstation) | LLM-driven ground-control station `{{confirm}}` | `C++` |
| [**cmake_cuda_physics**](https://github.com/inonitz/cmake_cuda_physics) | GPU physics simulation on CUDA `{{confirm}}` | `C++` · `CUDA` |

**Graphics &amp; GPU**

| project | | stack |
|---|---|---|
| [**compute-shader-fluid-2d**](https://github.com/inonitz/compute-shader-fluid-2d) &nbsp;★3 | real-time 2D fluid &mdash; GPU Gems ch. 38, OpenGL compute shaders | `C++` |
| [**pygame-software-renderer**](https://github.com/inonitz/pygame-software-renderer) | from-scratch software 3D renderer | `Python` |
| [**cpp-graphics-archive**](https://github.com/inonitz/cpp-graphics-archive) | ray marcher + SIMD physics experiments | `C++` |

**Systems**

| project | | stack |
|---|---|---|
| [**PrimOS**](https://github.com/inonitz/PrimOS) &nbsp;★4 | OS bootloader + kernel | `C` |
| [**x86-smp-boot**](https://github.com/inonitz/x86-smp-boot) | x86_64 SMP bring-up: real &rarr; protected &rarr; long mode | `Asm` |

**Foundations**

| project | | stack |
|---|---|---|
| [**neural-nets-from-scratch**](https://github.com/inonitz/neural-nets-from-scratch) | backprop &amp; MLPs in raw numpy | `Python` |

---

### Stats

<a href="https://github.com/inonitz">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=inonitz&show_icons=true&hide_border=true&count_private=true&theme=tokyonight" alt="inonitz GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=inonitz&layout=compact&hide_border=true&langs_count=8&theme=tokyonight" alt="Top languages" />
</a>

<!-- OPTIONAL: WakaTime (profile stays PRIVATE; aggregate language %s only, no repo names).
     Enable athul/waka-readme, add WAKATIME_API_KEY secret, then uncomment: -->
<!--START_WAKA-->
<!--END_WAKA-->

<div align="right"><sub><a href="https://github.com/inonitz">github.com/inonitz</a></sub></div>

<!-- ===================== reference-style badge links ====================== -->
[cpp-badge]:   https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white
[c-badge]:     https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black
[py-badge]:    https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[cuda-badge]:  https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white
[gl-badge]:    https://img.shields.io/badge/OpenGL-5586A4?style=for-the-badge&logo=opengl&logoColor=white
[vk-badge]:    https://img.shields.io/badge/Vulkan-AC162C?style=for-the-badge&logo=vulkan&logoColor=white
[cl-badge]:    https://img.shields.io/badge/OpenCL-ED1C24?style=for-the-badge&logo=opencl&logoColor=white
[cmake-badge]: https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white
