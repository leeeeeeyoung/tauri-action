# Tauri Tutorial

## APP

- [WA+](https://github.com/lencx/WA) - Making a web page more like a desktop application is just the beginning, the possibilities are unlimited, up to your imagination!

## Pre-installed

- [rust](https://www.rust-lang.org/learn/get-started)
- [nodejs](https://nodejs.org)
- [wasm-pack](https://github.com/rustwasm/wasm-pack)
- [rsw](https://github.com/rwasm/rsw-rs)

### Install wasm-pack

```bash
cargo install wasm-pack

# With Windows
cargo install wasm-pack --version 0.9.1
```

### Install rsw

```bash
cargo install rsw
```

**Note: If your operating system is `Windows`, it is recommended to install `wasm-pack v0.9.1`**

## Quick start

Note: Open two terminal windows, execute `yarn rsw watch` in the first and `yarn tauri dev` in the second. The order of execution is important, do not close the first window!

```bash
# 1. Do not exit the process after the command has started.
yarn rsw watch

# 2. Front-end: start dev server
yarn tauri dev
```

## 开发教程

> 关注 《浮之静》公众号，回复 `tauri` 进技术交流群

虽然 `Tauri` 已经发布 `v1.0` 版本，但是国内资料少的可怜，我想基于 `Tauri` 开发一款工具集（各种小功能）。并通过写文章的形式来记录开发过程中遇到的各种问题。如果这些文章对你有所帮助，可以 `star` 此项目或者将文章转发给更多有需要的人。大家的支持会给我更大的写作动力，感恩 🙏。如果你有开源的项目参考了此教程，可以 PR 到此 README.md 下的 APP，让更多的人看到。

- [GitHub Discussions - Tauri 系列](https://github.com/lencx/OhMyBox/discussions?discussions_q=label%3A%22Tauri+%E7%B3%BB%E5%88%97%22)
- [知乎专栏 - Tauri 系列](https://www.zhihu.com/column/c_1519079232848785408)
- [公众号 - Tauri 系列（免费篇 + 付费篇）](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzIzNjE2NTI3NQ==&action=getalbum&album_id=2593843659863752704&from_itemidx=1&from_msgid=2247485485#wechat_redirect) - `探索 Tauri 更多的能力`。免费篇和知乎专栏，GitHub Discussions 是同步更新的。付费内容针对性解决一些问题（涉及 Tauri 源码，解决思路等），不定期更新。原创不易，有能力的朋友可以支持一下，感恩。

## 赞助

[☕️ 请我喝杯咖啡](https://github.com/lencx/sponsor)

## 微信交流群

> 如群二维码过期，可关注公众号《浮之静》，发送“进群”，和小伙伴一起学习交流。

<img alt="Tauri 交流群" width="240" src="https://user-images.githubusercontent.com/16164244/179861652-4a59808a-c0ed-4025-9b0e-e1459e251d8a.png" /> <img alt="浮之静" width="250" src="https://user-images.githubusercontent.com/16164244/179861932-29036f22-45d9-4345-be14-d804faf2865f.png" />

## License

GPL-3.0 license © 2022 lencx
