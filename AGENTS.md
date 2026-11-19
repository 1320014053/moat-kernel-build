# 项目构建

这个项目的所有编译都在 GitHub Actions 上执行，包括内核、模块、探针、Falco 用户态程序和 SGX enclave。本机 Windows、WSL 和 QEMU 用于编辑、检查和运行测试。QEMU 验证从对应的 Actions 运行下载产物，测试后清理临时二进制和构建目录，保留源码、补丁、工作流和验证记录。
