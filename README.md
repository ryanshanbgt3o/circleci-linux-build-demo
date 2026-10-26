# circleci-linux-build-demo

在 CircleCI 免费版上编译 Linux 内核（x86_64 defconfig）的示例项目。

- 配置文件：`.circleci/config.yml`
- 机器：Docker `large`（4 vCPU / 8 GB），每分钟 20 积分
- 免费版每个任务最长 1 小时；产物（bzImage、.config、build.log）在 Artifacts 里下载
- 改内核版本：修改 `kernel_version` 参数
