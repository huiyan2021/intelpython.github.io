# System Requirements

The Intel® Distribution for Python* supports the Intel® 64 architecture. For a complete explanation of
this architecture name please read the following article:

[Intel® Architecture Platform Terminology for Development Tools](https://www.intel.com/content/www/us/en/developer/tools/overview.html)

The lists below pertain only to the system requirements necessary to support application
development with Intel® Distribution for Python*. If you are using Cython*, please review the
documentation for your compiler (GCC*, Microsoft Visual Studio*, or Intel® Compiler) to determine the
minimum hardware and software requirements

## 2023.2

### Minimum System Requirements

- A system based on an Intel® 64 architecture processor supporting the Intel® Streaming SIMD
Extensions 4.2 (Intel® SSE4.2) instructions (or compatible non-Intel® processor).
NOTE:
  - Incompatible or proprietary instructions in non-Intel® processors may cause the analysis
capabilities of this product to function incorrectly. Any attempt to analyze code not
supported by Intel® processors may lead to failures in this product.
  - For the best experience, a multi-core or multiprocessor system is recommended.
- About 4GB free disk space for all product features and all architectures
 
**Note:** Intel® Distribution for Python* is expected to work on many more Linux distributions as well.
Let us know if you have trouble with the distribution you use.

### Hardware Requirements
- GPU:
  - 6th Gen Intel® Core™ processor or higher
  - Intel® Iris® Plus Graphics
  - Intel® Iris® Xe Graphics
  - Intel® Iris® Xe Max Graphics
  - Intel® Iris® Graphics
  - Intel® Iris® Pro Graphics
- CPU:
  - Intel Atom® Processors
  - Intel® Core™ Processor Family
  - Intel® Xeon® Processor Family
  - Intel® Xeon® Scalable Performance Processor Family 

Apple M1* hardware is currently not supported.

#### Windows Intel® Graphics Driver

To install the driver follow the directions in the article appropriate for your device:
- [Intel® Iris® Xe MAX (DG1) and 10th-13th Gen Intel® Core™ Processor Graphics](https://www.intel.com/content/www/us/en/download/19344/intel-graphics-windows-dchdrivers.html)
- [Intel® Arc™ A-Series Graphics (DG2)](https://www.intel.com/content/www/us/en/download/726609/intel-arc-graphics-windowsdch-driver.html)
- [Intel® Data Center GPU Flex Series (ATS-M)](https://registrationcenter.intel.com/en/products/subscription/956/)
  
Contact your OEM representative for access to the Intel Registration Center.

#### Linux General Purpose Intel GPUs (GPGPU) Driver

For all Intel GPUs, see [this article](https://dgpu-docs.intel.com/), and follow the directions for your device

### Software Requirements

These OS distributions are tested by Intel or known to work; other distributions may or may not work
and are not recommended. If you have questions, access the [Intel Community Forums](https://community.intel.com/t5/Developer-Software-Forums/ct-p/developer-software-forums) when you need
assistance. If you have Commercial Support, create a support ticket.

Operating Systems:

- 64-bit Linux*: Ubuntu* 20.04, 22.04 (CPU & GPU)
-  64-bit Windows* Pro & Enterprise 10 (CPU & GPU), 11 (GPU only)
  - Using Microsoft’s Windows Subsystem for Linux 2 (WSL2) in Windows 10, you can
install the native Linux distribution of Intel oneAPI toolkits and libraries on Windows
for CPU and GPU workflows. Details here
- Windows* Server 2019, 2022 (CPU & GPU)
- Red Hat Enterprise Linux 8, 9 (CPU & GPU)
- Fedora 36, 37 (CPU only)
- SUSE Linux Enterprise 15 SP3, 15 SP4 (CPU & GPU)
- MacOS Monterey 12.x, Ventura 13.x (CPU only)

### External Dependencies 
- For **Windows\***: None
- For **Linux\***: None
