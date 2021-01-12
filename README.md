# coreutils-patches
在较新的glibc环境中编译旧版本的coreutils所需的patch.

Patches for old gnu coreutils versions to build on newer glibc environments.

在[Ref](https://lists.gnu.org/archive/html/coreutils/2019-08/msg00011.html)基础上添加了对5.93版本的支持。

# 测试环境
Linux 5.4.0-59-generic

Ubuntu 18.04.5 LTS

gcc version 7.5.0 (Ubuntu 7.5.0-3ubuntu1~18.04)

GNU C Library (Ubuntu GLIBC 2.27-3ubuntu1.2) stable release version 2.27

# 对应关系(glibc 2.28)

| Coreutils Versions      |       Patch file |
|  ----                   |       ----       |
|5.0                      |     patch-5.0    |
|5.93                     |     patch-5.93    |
|5.97 to 6.9              |     patch-5.97-6.9    |
|6.10                     |     patch-6.10    |
|6.11                     |     patch-6.11    |
|6.12                     |     patch-6.12    |
|7.2  to 8.3              |     patch-7.2-8.3    |
|8.4  to 8.12             |     patch-8.4-8.12    |
|8.13 to 8.16             |     patch-8.13-8.16    |
|8.17                     |     patch-8.17    |
|8.18 to 8.23             |     patch-8.18-8.23    |
|8.24 to 8.29             |     patch-8.24-8.29    |
|8.30 and newer           |     builds without patching    |

实际上，glibc2.27的话，8.1及之后应该就不用patch了。
