```dmesg | grep -i gpu```
-> [    4.632173] mali fb000000.gpu: GPU identified as 0x7 arch 10.8.6 r0p0 status 0

### Basic
| Key                  | Value                                     |
| -------------------- | ----------------------------------------- |
| **Board**            | LubanCat-4 V1                             |
| **SoC**              | **Rockchip RK3588S**                      |
| **GPU**              | **ARM Mali-G610 MP4**                     |
| **GPU Architecture** | Valhall Gen3 (G610)                       |
| **GPU Core Count**   | **4 cores** (`MP4` = 4 Execution Engines) |
| **Max Frequency**    | 800 MHz (from earlier logs)               |
| **RAM**              | Shared system RAM (no dedicated VRAM)     |

### GPU Capabilities of Mali-G610 MP4
| Feature	     | Value                                     |
| ------------ | ----------------------------------------- |
| Shader       | Cores	4                                  |
| OpenGL       | ES	3.2                                    |
| Vulkan	     | 1.2                                       |
| OpenCL	     | 2.0                                       |
| Architecture | Valhall Gen3                              |
| Performance	 | Up to ~1 TFLOPS FP32 (depending on clock) |
