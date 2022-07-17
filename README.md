# 你好

近期主要关注 Rust 和 RISCV。也许这些开源项目能够帮得上忙：

- 下列库不需要 std 和 alloc，零开销抽象，因此可用于几乎任何软件

  - [**crates.io/dtb-walker**](https://crates.io/crates/dtb-walker): 遍历设备树二进制对象（dtb）。
  - [**crates.io/page-table**](https://crates.io/crates/page-table): 页表。目前提供 RISCV sv32/sv39/sv48/sv57 页表的定义和操作。
  
- 其他项目

  [![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=YdrMaster&repo=rustsbi-qemu&theme=dark)](https://github.com/YdrMaster/rustsbi-qemu)

  这个项目实现适用于 qemu virt 虚拟设备的特权运行环境（SEE）。SEE 向特权软件（Supervisor）提供由 [RISCV 标准](https://github.com/riscv-non-isa/riscv-sbi-doc/releases/tag/v1.0.0)定义的特权态二进制接口（SBI：Supervisor Binary Interface）。

---

![Github Stats](https://github-readme-stats.vercel.app/api?username=YdrMaster&show_icons=true&theme=dark)
![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YdrMaster&theme=dark&layout=compact)
