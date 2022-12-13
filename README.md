# rust 中文资源库

转载自：[https://github.com/rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust)

> 大部分转载自awesome-rust 由于本人英文太差所以用api翻译成了中文 有些翻译不对 请见谅

### 不定时更新同步 [更新时间:2022-12-13 10:37:14]

一个精心策划的Rust代码和资源列表.。

---

## 目录

<!-- toc -->

- [应用程序 Applications](#应用程序-applications)
  * [音频和音乐 Audio and Music](#音频和音乐-audio-and-music)
  * [Cryptocurrencies Cryptocurrencies](#Cryptocurrencies-cryptocurrencies)
  * [数据库 Database](#数据库-database)
  * [模拟器 Emulators](#模拟器-emulators)
  * [游戏 Games](#游戏-games)
  * [图形 Graphics](#图形-graphics)
  * [图像处理 Image processing](#图像处理-image-processing)
  * [工业自动化 Industrial automation](#工业自动化-industrial-automation)
  * [可观察性 Observability](#可观察性-observability)
  * [操作系统 Operating systems](#操作系统-operating-systems)
  * [生产力 Productivity](#生产力-productivity)
  * [安全工具 Security tools](#安全工具-security-tools)
  * [模拟 Simulation](#模拟-simulation)
  * [社交网络 Social networks](#社交网络-social-networks)
  * [系统工具 System tools](#系统工具-system-tools)
  * [任务调度 Task scheduling](#任务调度-task-scheduling)
  * [文本编辑器 Text editors](#文本编辑器-text-editors)
  * [文本处理 Text processing](#文本处理-text-processing)
  * [公用事业公司 Utilities](#公用事业公司-utilities)
  * [视频 Video](#视频-video)
  * [虚拟化 Virtualization](#虚拟化-virtualization)
  * [网络 Web](#网络-web)
  * [Web服务器 Web Servers](#Web服务器-web-servers)
- [开发工具 Development tools](#开发工具-development-tools)
  * [构建系统 Build system](#构建系统-build-system)
  * [调试 Debugging](#调试-debugging)
  * [部署 Deployment](#部署-deployment)
  * [嵌入式 Embedded](#嵌入式-embedded)
  * [FFI FFI](#FFI-ffi)
  * [格式器 Formatters](#格式器-formatters)
  * [编译器 IDEs](#编译器-ides)
  * [分析 Profiling](#分析-profiling)
  * [服务 Services](#服务-services)
  * [静态分析 Static analysis](#静态分析-static-analysis)
  * [测试 Testing](#测试-testing)
  * [转化 Transpiling](#转化-transpiling)
- [库 Libraries](#库-libraries)
  * [人工智能 Artificial Intelligence](#人工智能-artificial-intelligence)
    + [遗传算法 Genetic algorithms](#遗传算法-genetic-algorithms)
    + [机器学习 Machine learning](#机器学习-machine-learning)
  * [天文学 Astronomy](#天文学-astronomy)
  * [异步 Asynchronous](#异步-asynchronous)
  * [音频和音乐 Audio and Music](#音频和音乐-audio-and-music-1)
  * [身份验证 Authentication](#身份验证-authentication)
  * [汽车 Automotive](#汽车-automotive)
  * [生物信息学 Bioinformatics](#生物信息学-bioinformatics)
  * [缓存 Caching](#缓存-caching)
  * [云 Cloud](#云-cloud)
  * [命令行 Command-line](#命令行-command-line)
  * [压缩 Compression](#压缩-compression)
  * [计算 Computation](#计算-computation)
  * [并发性 Concurrency](#并发性-concurrency)
  * [配置 Configuration](#配置-configuration)
  * [密码学 Cryptography](#密码学-cryptography)
  * [数据处理 Data processing](#数据处理-data-processing)
  * [数据流 Data streaming](#数据流-data-streaming)
  * [数据结构 Data structures](#数据结构-data-structures)
  * [数据可视化 Data visualization](#数据可视化-data-visualization)
  * [数据库 Database](#数据库-database-1)
  * [日期和时间 Date and time](#日期和时间-date-and-time)
  * [分布式系统 Distributed systems](#分布式系统-distributed-systems)
  * [领域驱动设计 Domain driven design](#领域驱动设计-domain-driven-design)
  * [电子邮件 Email](#电子邮件-email)
  * [编码 Encoding](#编码-encoding)
  * [文件系统 Filesystem](#文件系统-filesystem)
  * [函数式编程 Functional Programming](#函数式编程-functional-programming)
  * [游戏开发 Game development](#游戏开发-game-development)
  * [地理空间 Geospatial](#地理空间-geospatial)
  * [图算法 Graph algorithms](#图算法-graph-algorithms)
  * [图形 Graphics](#图形-graphics-1)
  * [GUI GUI](#GUI-gui)
  * [图像处理 Image processing](#图像处理-image-processing-1)
  * [语言规范 Language specification](#语言规范-language-specification)
  * [日志记录 Logging](#日志记录-logging)
  * [Macro Macro](#Macro-macro)
  * [标记语言 Markup language](#标记语言-markup-language)
  * [移动 Mobile](#移动-mobile)
  * [网络编程 Network programming](#网络编程-network-programming)
  * [解析 Parsing](#解析-parsing)
  * [外围设备 Peripherals](#外围设备-peripherals)
  * [特定于平台的 Platform specific](#特定于平台的-platform-specific)
  * [脚本 Scripting](#脚本-scripting)
  * [模拟 Simulation](#模拟-simulation-1)
  * [任务调度 Task scheduling](#任务调度-task-scheduling-1)
  * [模板引擎 Template engine](#模板引擎-template-engine)
  * [文本处理 Text processing](#文本处理-text-processing-1)
  * [文本搜索 Text search](#文本搜索-text-search)
  * [不安全的 Unsafe](#不安全的-unsafe)
  * [虚拟化 Virtualization](#虚拟化-virtualization-1)
  * [网络编程 Web programming](#网络编程-web-programming)
- [注册表 Registries](#注册表-registries)
- [资源 Resources](#资源-resources)
- [许可证 License](#许可证-license)


<!-- tocstop -->

## 应用程序 Applications
> 应用程序和工具

另见[Rust - Production](https://www.rust-lang.org/production)组织在生产中运行Rust.

* [alacritty](https://github.com/alacritty/alacritty) — 一个跨平台的GPU增强型终端仿真器.
* [asm-cli-rust](https://github.com/cch123/asm-cli-rust) — 用rust编写的交互式汇编外壳.
* [cloudflare/boringtun](https://github.com/cloudflare/boringtun) — 一个用户空间WireGuard VPN的实施. [![build badge](https://img.shields.io/badge/crates.io-v0.2.0-orange.svg)](https://crates.io/crates/boringtun)
* [datafusion](https://github.com/apache/arrow-datafusion) — Apache Arrow DataFusion和Ballista查询引擎.
* [denoland/deno](https://github.com/denoland/deno) — 用V8、Rust和Tokio构建的安全JavaScript/TypeScript运行时 [![Build Status](https://github.com/denoland/deno/workflows/ci/badge.svg?branch=master&event=push)](https://github.com/denoland/deno/actions)
* [Factotum](https://github.com/snowplow/factotum) — [一个以编程方式运行数据管道的系统](https://snowplow.io/blog/introducing-factotum-data-pipeline-runner/) [![build badge](https://api.travis-ci.org/snowplow/factotum.svg?branch=master)](https://travis-ci.org/snowplow/factotum)
* [fcsonline/drill](https://github.com/fcsonline/drill) — 一个HTTP负载测试应用程序受Ansible语法[![build badge](https://api.travis-ci.org/fcsonline/drill.svg?branch=master)](https://travis-ci.org/fcsonline/drill)
* [fend](https://github.com/printfn/fend) - 任意精度的单位感知型计算器 [![build](https://github.com/printfn/fend/workflows/build/badge.svg)](https://github.com/printfn/fend)
* [Fractalide](https://github.com/fractalide/fractalide) — 简单的Rust微服务
* [habitat](https://github.com/habitat-sh/habitat) — 由厨师的工具来构建、部署和管理应用程序。
* [Herd](https://github.com/imjacobclark/Herd) — 一个实验性的HTTP负载测试应用程序
* [jedisct1/flowgger](https://github.com/awslabs/flowgger) — 一种快速、简单、轻量级数据收集器
* [kalker](https://github.com/PaddiM8/kalker) - 一个科学计算器，支持类似数学的语法，有用户定义的变量、函数、推导、积分和复数。跨平台+支持WASM [![Build Status](https://github.com/PaddiM8/kalker/workflows/Release/badge.svg)](https://github.com/PaddiM8/kalker/actions)
* [kytan](https://github.com/changlan/kytan) — 高性能对等VPN
* [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) — 超轻型Kubernetes服务网格。
* [MaidSafe](https://github.com/maidsafe) — 一个分散的平台。
* [mdBook](https://crates.io/crates/mdbook) — 一个命令行实用程序来创建图书从减价文件[![Build Status](https://github.com/rust-lang/mdBook/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/mdBook/actions)
* [nicohman/eidolon](https://github.com/nicohman/eidolon) — 蒸汽和drm免费游戏注册表并为linux和macosx发射器[![build badge](https://api.travis-ci.org/nicohman/eidolon.svg?branch=master)](https://travis-ci.org/nicohman/eidolon)
* [notty](https://github.com/withoutboats/notty) — 一种新的终端
* [Pijul](https://pijul.org) — patch-based分布式版本控制系统
* [rx](https://github.com/cloudhead/rx) — Vi启发现代像素美术编辑
* [Servo](https://github.com/servo/servo) — 一个原型web浏览器引擎
* [shuttle](https://github.com/shuttle-hq/shuttle) — serverless平台建造的生锈
* [SWC](https://github.com/swc-project/swc) — 超高速打印稿/ JavaScript编译器
* [tiny](https://github.com/osa1/tiny) — 一个终端IRC客户端
* [trust-dns](https://crates.io/crates/trust-dns) — 一个dns服务器 [![Build Status](https://github.com/bluejekyll/trust-dns/workflows/test/badge.svg?branch=main)](https://github.com/bluejekyll/trust-dns/actions?query=workflow%3Atest)
* [wasmer](https://github.com/wasmerio/wasmer) — 安全、快速WebAssembly运行时支持WASI和Emscripten[![Build Status](https://github.com/wasmerio/wasmer/workflows/build/badge.svg?style=flat-square)](https://github.com/wasmerio/wasmer/actions)
* [Weld](https://github.com/serayuzgur/weld) — 全假的REST API生成器[![build badge](https://api.travis-ci.org/serayuzgur/weld.svg?branch=master)](https://travis-ci.org/serayuzgur/weld)
* [wezterm](https://github.com/wez/wezterm) — GPU-accelerated跨平台终端仿真器和多路复用器.
* [zellij](https://github.com/zellij-org/zellij) — 一个终端多路复用器(工作区),包括电池程序执行完成.

### 音频和音乐 Audio and Music
> 用于操作音频的库

* [enginesound](https://github.com/DasEtwas/enginesound) — 使用一个GUI和命令行应用程序程序生成真实感的引擎的声音。深入的配置、可变采样率和频率分析窗口。
* [Glicol](https://github.com/chaosprint/glicol) — 面向图编程语言写住在生锈的协作各种浏览器。
* [ncspot](https://github.com/hrkfdn/ncspot) - 跨平台的ncurses Spotify客户端，灵感来自ncmpc和同类产品. [![build badge](https://github.com/hrkfdn/ncspot/workflows/Build/badge.svg)](https://github.com/hrkfdn/ncspot/actions?query=workflow%3ABuild)
* [Polaris](https://github.com/agersant/polaris) — 一个音乐流媒体的应用程序。[![build badge](https://api.travis-ci.org/agersant/polaris.svg?branch=master)](https://travis-ci.org/agersant/polaris)
* [Spotify TUI](https://github.com/Rigellute/spotify-tui) — Spotify客户终端用生锈. ![Continuous Integration](https://github.com/Rigellute/spotify-tui/workflows/Continuous%20Integration/badge.svg?branch=master)
* [Spotifyd](https://github.com/Spotifyd/spotifyd) —一个开源的Spotify客户机作为UNIX守护进程运行. ![Continuous Integration](https://github.com/Spotifyd/spotifyd/workflows/Continuous%20Integration/badge.svg?branch=master)
* [WhatBPM](https://github.com/sergree/whatbpm) — 每天生成静态信息资源电子舞蹈音乐制作人。提供每日分析每个EDM流派:最常用的值的节奏,钥匙,根指出,等等,使用公开数据,如Beatport和Spotify。!(持续集成)(https://github.com/sergree/whatbpm/actions/workflows/website_build_deploy.yml/badge.svg?branch=main)

### 加密货币 Cryptocurrencies
> 应用程序支付和构建在线电子商务的库

* [Akula](https://github.com/akula-bft/akula) - Rust Ethereum执行层（EL）客户端（WIP.
* [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv) [[sv](https://crates.io/crates/sv)] — 比特币SV锈库工作。
* [cairo](https://github.com/starkware-libs/cairo) - Cairo是第一个用于创建一般计算的可证明程序的图灵完备语言。这也是 [StarkNet](https://starknet.io), 一个使用STARK证明的ZK-Rollup ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/starkware-libs/cairo/CI?style=flat-square&logo=github)
* [cairo-rs](https://github.com/lambdaclass/cairo-rs) — 锈开罗VM的实现[![rust](https://github.com/lambdaclass/cairo-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/lambdaclass/cairo-rs/actions/workflows/rust.yml)
* [ChainX](https://github.com/chainx-org/ChainX) — 充分分散的跨链加密资产管理上的圆点花纹。
* [CITA](https://github.com/citahub/cita) — 企业用户的高性能区块链内核。
* [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs) — Coinbase pro客户生锈,支持同步/异步/ websocket[![build badge](https://api.travis-ci.org/inv2004/coinbase-pro-rs.svg?branch=master)](https://travis-ci.org/inv2004/coinbase-pro-rs)
* [Diem](https://github.com/diem/diem) — 吴廷琰的使命是使一个简单的全球货币和金融基础设施,使数以亿计的人。
* [electrumrs](https://github.com/romanz/electrs) — 一个有效的重新实现银金矿服务器生锈。
* [ethabi](https://github.com/rust-ethereum/ethabi) - 对智能合约的调用进行编码和解码.
* [ethaddrgen](https://github.com/Limeth/ethaddrgen) — 定制Ethereum虚荣地址发生器在生锈[![build badge](https://api.travis-ci.org/Limeth/ethaddrgen.svg?branch=master)](https://travis-ci.org/Limeth/ethaddrgen)
* [ethers-rs](https://github.com/gakonst/ethers-rs) - 在Rust中完成Ethereum & Celo库和钱包的实现. ![Build Status](https://github.com/gakonst/ethers-rs/workflows/Tests/badge.svg)
* [etk](https://github.com/quilt/etk) - etk是一个用于编写、阅读和分析EVM字节码的工具集合.
* [Forest](https://github.com/ChainSafe/forest) - Rust Filecoin的实现 [![Build Status](https://img.shields.io/circleci/build/gh/ChainSafe/forest/main?branch=master)](https://app.circleci.com/pipelines/github/ChainSafe/forest?branch=main)
* [Foundry](https://github.com/foundry-rs/foundry) - Foundry是一个用Rust编写的用于Ethereum应用开发的快速、可移植和模块化的工具箱。. ![Build Status](https://img.shields.io/github/workflow/status/foundry-rs/foundry/test?style=flat-square)
* [Grin](https://github.com/mimblewimble/grin/) — 进化MimbleWimble协议
* [hdwallet](https://github.com/jjyr/hdwallet) [[hdwallet](https://crates.io/crates/hdwallet)] — BIP-32高清钱包推导工具相关的关键。
* [Holochain](https://github.com/holochain/holochain) — 可伸缩的P2P替代区块链对于那些你一直想建立分布式应用程序。[![detect critical check failures](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml/badge.svg)](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml)
* [ibc-rs](https://github.com/informalsystems/hermes) - Rust implementation of the [Interblockchain Communication](https://ibc.cosmos.network/) protocol
* [infincia/bip39-rs](https://github.com/infincia/bip39-rs) [[bip39](https://crates.io/crates/bip39)] — 锈BIP39的实现。
* [interBTC](https://github.com/interlay/interbtc) — 不可靠的和完全分散的比特币桥圆点花纹和草间弥生。
* [Joystream](https://github.com/Joystream/joystream) — 用户管理视频平台[![Build Status](https://api.travis-ci.org/Joystream/joystream.svg?branch=master)](https://travis-ci.org/Joystream/joystream)
* [Lighthouse](https://github.com/sigp/lighthouse) — 锈Ethereum共识层(CL)客户机[![Build Status](https://github.com/sigp/lighthouse/workflows/test-suite/badge.svg?branch=master)](https://github.com/sigp/lighthouse/actions)
* [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs) - Ethereum MEV Inspector in Rust
* [near/nearcore](https://github.com/near/nearcore) — 分散smart-contract低端移动设备平台。
* [Nervos CKB](https://github.com/nervosnetwork/ckb) — 紧张CKB是一个公共无许可区块链,紧张的共同知识层网络。
* [Nimiq](https://github.com/nimiq/core-rs) — 锈Nimiq节点的实现
* [opensea-rs](https://github.com/gakonst/opensea-rs) - Opensea API和合约的Rust绑定和CLI.
* [Parity-Bitcoin](https://github.com/paritytech/parity-bitcoin) — 奇偶校验比特币客户端[![build badge](https://api.travis-ci.org/paritytech/parity-bitcoin.svg?branch=master)](https://app.travis-ci.com/github/paritytech/parity-bitcoin)
* [Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain) — 机密智能合同区块链基于英特尔新交所和衬底
* [Polkadot](https://github.com/paritytech/polkadot) — 异构多-链与池安全技术
* [revm](https://github.com/bluealloy/revm) - 革命性的机器（revm）是一个用rust编写的快速以太坊虚拟机.
* [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) — 图书馆支持德/序列化,解析和执行相关数据结构和网络信息比特币。
* [rust-lightning](https://github.com/lightningdevkit/rust-lightning) [![Crate](https://img.shields.io/crates/v/lightning.svg?logo=rust)](https://crates.io/crates/lightning) — 比特币闪电库编写的生锈。主箱,‘闪电’,不处理网络、持久性、或任何其他I / O。因此,runtime-agnostic,但是用户必须实现基本的网络逻辑链的相互作用和磁盘存储。阿宝在连接箱。
* [sigma-rust](https://github.com/ergoplatform/sigma-rust) — 锈ErgoTree解释器和wallet-related功能的实现。
* [Solana](https://github.com/solana-labs/solana) — 令人难以置信的快,使用Proof-of-History高度可伸缩的区块链。
* [Substrate](https://github.com/paritytech/substrate) — 通用模块化区块链模板写在生锈
* [svm-rs](https://github.com/roynalnaruto/svm-rs) - Solidity-编译器版本管理器.
* [tendermint-rs](https://github.com/informalsystems/tendermint-rs) - Tendermint区块链数据结构和客户端的Rust实现.
* [wagyu](https://github.com/AleoHQ/wagyu)[[wagyu](https://crates.io/crates/wagyu)] — 锈库生成cryptocurrency钱包[![build badge](https://api.travis-ci.com/AleoHQ/wagyu.svg?branch=master)](https://api.travis-ci.com/AleoHQ/wagyu.svg?branch=master)
* [zcash](https://github.com/zcash/zcash) — Zcash“Zerocash”协议的实现。

### 数据库 Database
> 与数据库进行交互使用对象关系映射(ORM)或datamapping的库

* [Databend](https://github.com/datafuselabs/databend) - 具有云原生架构的现代实时数据处理和分析DBMS [![Release](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml/badge.svg)](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml)
* [indradb](https://crates.io/crates/indradb) — 生锈的基础图形数据库[![build badge](https://api.travis-ci.org/indradb/indradb.svg?branch=master)](https://travis-ci.org/indradb/indradb)
* [Lucid](https://github.com/lucid-kv/lucid) — 高性能和分布式KV商店通过HTTP API来访问。[![Build Status](https://github.com/lucid-kv/lucid/workflows/Lucid/badge.svg?branch=master)](https://github.com/lucid-kv/lucid/actions?workflow=Lucid)
* [Materialize](https://github.com/MaterializeInc/materialize) - 由Timely Dataflow提供的流式SQL数据库 :heavy_dollar_sign: [![Build status](https://badge.buildkite.com/97d6604e015bf633d1c2a12d166bb46f3b43a927d3952c999a.svg?branch=main)](https://buildkite.com/materialize/tests)
* [noria](https://github.com/mit-pdos/noria) [[noria](https://crates.io/crates/noria)] — 动态改变,局部稳定的对web应用程序的后端数据流[![build badge](https://api.travis-ci.org/mit-pdos/noria.svg?branch=master)](https://travis-ci.org/mit-pdos/noria)
* [ParityDB](https://github.com/paritytech/parity-db) — 快速和可靠的数据库,为读操作优化
* [PumpkinDB](https://github.com/PumpkinDB/PumpkinDB) — 一个事件采购数据库引擎
* [Qdrant](https://github.com/qdrant/qdrant) - 一个具有扩展过滤支持的开源矢量相似性搜索引擎 [![Tests](https://github.com/qdrant/qdrant/workflows/Tests/badge.svg)](https://github.com/qdrant/qdrant/actions)
* [RisingWaveLabs/RisingWave](https://github.com/RisingWaveLabs/risingwave) - 下一代云端流媒体数据库 [![CI](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg)](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg?branch=main)
* [seppo0010/rsedis](https://github.com/seppo0010/rsedis) — 的复述,重新生锈[![build badge](https://api.travis-ci.org/seppo0010/rsedis.svg?branch=master)](https://travis-ci.org/seppo0010/rsedis)
* [Skytable](https://github.com/skytable/skytable) — 多模型NoSQL数据库![GitHub Workflow Status](https://img.shields.io/github/workflow/status/skytable/skytable/Tests?style=flat-square)
* [sled](https://crates.io/crates/sled) — 现代嵌入式数据库(β)[![Build Status](https://github.com/spacejam/sled/workflows/Rust/badge.svg?branch=master)](https://github.com/spacejam/sled/actions?workflow=Rust)
* [SurrealDB](https://github.com/surrealdb/surrealdb) — 一个可伸缩的、分布式、document-graph数据库[![Build Status](https://img.shields.io/github/workflow/status/surrealdb/surrealdb/Continuous%20integration/main)](https://github.com/surrealdb/surrealdb/actions)
* [TerminusDB](https://github.com/terminusdb/terminusdb-store) - 开源图形数据库和文件存储 [![Build Status](https://github.com/terminusdb/terminusdb-store/workflows/Build/badge.svg?branch=master)](https://github.com/terminusdb/terminusdb-store/actions)
* [tikv](https://github.com/tikv/tikv) — 一个分布式KV数据库中生锈[![Build Status](https://ci.pingcap.net/job/tikv_ghpr_test/badge/icon)](https://ci.pingcap.net/job/tikv_ghpr_test/)
* [vorot93/libmdbx-rs](https://github.com/vorot93/libmdbx-rs) [[mdbx-sys](https://crates.io/crates/mdbx-sys)] — 生锈的绑定MDBX,“快速、简洁、有力,嵌入式,事务性数据库键-值,宽松的许可”。这是mozilla的叉子/ lmdb-rs补丁与libmdbx使其工作。
* [WooriDB](https://github.com/naomijub/wooridb) - 受Crux和Datomic启发的通用型时间序列数据库.

### 模拟器 Emulators
> 一些模拟的库

另见 [crates matching keyword 'emulator'](https://crates.io/keywords/emulator).

* CHIP-8
  * [ColinEberhardt/wasm-rust-chip8](https://github.com/ColinEberhardt/wasm-rust-chip8) — 用Rust编写的WebAssembly CHIP-8仿真器
  * [starrhorne/chip8-rust](https://github.com/starrhorne/chip8-rust) — 然而，另一个生锈的chip8模拟器
* Commodore 64
  * [kondrak/rust64](https://github.com/kondrak/rust64) — [![build badge](https://api.travis-ci.org/kondrak/rust64.svg?branch=master)](https://travis-ci.org/kondrak/rust64)
* Flash播放器
  * [Ruffle](https://github.com/ruffle-rs/ruffle) — Ruffle是一个用Rust编程语言编写的Adobe Flash Player仿真器。Ruffle使用WebAssembly同时针对桌面和网络。. [![Build Status Rust](https://img.shields.io/github/workflow/status/ruffle-rs/ruffle/Test%20Rust?label=Rust%20Build&logo=github)](https://github.com/ruffle-rs/ruffle/actions?workflow=Test%20Rust)[![Build Status Web](https://img.shields.io/github/workflow/status/ruffle-rs/ruffle/Test%20Web?label=Web%20Build&logo=github)](https://github.com/ruffle-rs/ruffle/actions?workflow=Test%20Web)
* 游戏机
  * [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb) — [![build badge](https://api.travis-ci.org/Gekkio/mooneye-gb.svg?branch=master)](https://travis-ci.org/Gekkio/mooneye-gb)
  * [mohanson/gameboy](https://github.com/mohanson/gameboy) — 全功能跨平台的GameBoy模拟器。永远的男孩!.
  * [mvdnes/rboy](https://github.com/mvdnes/rboy) — [![build badge](https://api.travis-ci.org/mvdnes/rboy.svg?branch=master)](https://travis-ci.org/mvdnes/rboy)
* 游戏机推进器
  * [michelhe/rustboyadvance-ng](https://github.com/michelhe/rustboyadvance-ng) - RustboyAdvance-ng是一个Gameboy Advance模拟器，具有桌面、安卓和移动设备功能 [WebAssembly](https://michelhe.github.io/rustboyadvance-ng/) support. [![build badge](https://github.com/michelhe/rustboyadvance-ng/workflows/Deploy/badge.svg?branch=master)](https://github.com/michelhe/rustboyadvance-ng/actions?query=workflow%3ADeploy)
* 游戏制作者
  * [OpenGMK](https://github.com/OpenGMK/OpenGMK) — OpenGMK是对专有的GameMaker Classic引擎的现代重写，提供了运行器的完整源代码，一个反编译器，一个TASing框架，以及用于处理游戏数据的库。.
* 英特尔8080 CPU
  * [mohanson/i8080](https://github.com/mohanson/i8080) — Rust的英特尔8080 cpu仿真器.
* NES
  * [koute/pinky](https://github.com/koute/pinky) — [![build badge](https://api.travis-ci.org/koute/pinky.svg?branch=master)](https://travis-ci.org/koute/pinky)
  * [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes)
* ZX Spectrum
  * [rustzx/rustzx](https://github.com/rustzx/rustzx) — [![RustZX CI](https://github.com/rustzx/rustzx/actions/workflows/ci.yml/badge.svg)](https://github.com/rustzx/rustzx/actions/workflows/ci.yml)

### 游戏 Games
> 很棒的游戏开发库

另见 [Games Made With Piston](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston).

* [citybound](https://github.com/citybound/citybound) — sim是你应得的
* [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom) — 厄运的渲染器,可能进步作为一个可玩游戏[![build badge](https://api.travis-ci.org/cristicbz/rust-doom.svg?branch=master)](https://travis-ci.org/cristicbz/rust-doom)
* [doukutsu-rs](https://github.com/doukutsu-rs/doukutsu-rs) — 锈洞穴故事的重新引擎和一些增强。
* [garkimasera/rusted-ruins](https://github.com/garkimasera/rusted-ruins) — 可扩展的开放世界流氓喜欢和像素艺术比赛[![build badge](https://api.travis-ci.org/garkimasera/rusted-ruins.svg?branch=master)](https://travis-ci.org/garkimasera/rusted-ruins)
* [gorilla-devs/ferium](https://github.com/gorilla-devs/ferium) — Ferium是一个快速和功能丰富的CLI程序下载和更新Minecraft插件从Modrinth CurseForge, GitHub版本,并从Modrinth modpacks CurseForge ![ferium build](https://github.com/gorilla-devs/ferium/actions/workflows/build.yml/badge.svg?branch=main)
* [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust) — 简约音乐视频游戏支持BMS的格式[![build badge](https://api.travis-ci.org/lifthrasiir/angolmois-rust.svg?branch=master)](https://travis-ci.org/lifthrasiir/angolmois-rust)
* [mara214/rsnake](https://github.com/mara214/rsnake) — 蛇用生锈。
* [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth) — 一个小二维六角形的回合制战略游戏[![build badge](https://api.travis-ci.org/ozkriff/zemeroth.svg?branch=master)](https://travis-ci.org/ozkriff/zemeroth)
* [rhex](https://github.com/dpc/rhex) — 六角ascii roguelike
* [rsaarelm/magog](https://github.com/rsaarelm/magog) — roguelike游戏中生锈
* [SoftbearStudios/mk48](https://github.com/SoftbearStudios/mk48) — Mk48。io是一个在线多人海战游戏
* [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs) — 一个独角兽的实施
* [thetawavegame/thetawave-legacy](https://github.com/thetawavegame/thetawave-legacy) - 一款太空射击游戏，力争成为新的游戏开发者做出首次贡献的切入点. ![build badge](https://github.com/thetawavegame/thetawave-legacy/actions/workflows/ci.yml/badge.svg?branch=master)
* [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake) — 地震地图渲染器在生锈
* [ttyperacer/terminal-typeracer](https://gitlab.com/ttyperacer/terminal-typeracer) - 为终端编写的单人打字测试游戏
* [Veloren](https://gitlab.com/veloren/veloren) — 一个开放的世界,开源多人体素RPG游戏目前在α发展[![build badge](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/-/pipelines)
* [Zone of Control](https://github.com/ozkriff/zoc) — 六角形的回合制策略游戏[![build badge](https://api.travis-ci.org/ozkriff/zoc.svg?branch=master)](https://travis-ci.org/ozkriff/zoc)

### 图形 Graphics
> 用于构建GUI应用程序的库。

* [ivanceras/svgbob](https://github.com/ivanceras/svgbob) — 将ASCII图转换为SVG图形[![build badge](https://api.travis-ci.org/ivanceras/svgbob.svg?branch=master)](https://travis-ci.org/ivanceras/svgbob)
* [Limeth/euclider](https://github.com/Limeth/euclider) — 一个实时四维CPU射线示踪剂[![build badge](https://api.travis-ci.org/Limeth/euclider.svg?branch=master)](https://travis-ci.org/Limeth/euclider)
* [RazrFalcon/resvg](https://github.com/RazrFalcon/resvg) — SVG呈现图书馆。[![build badge](https://api.travis-ci.org/RazrFalcon/resvg.svg?branch=master)](https://travis-ci.org/RazrFalcon/resvg)
* [turnage/valora](https://crates.io/crates/valora) — 一个库生成艺术![Rust](https://github.com/turnage/valora/workflows/Rust/badge.svg?branch=master)
* [Twinklebear/tray_rust](https://github.com/Twinklebear/tray_rust) — 一线示踪剂[![build badge](https://api.travis-ci.org/Twinklebear/tray_rust.svg?branch=master)](https://travis-ci.org/Twinklebear/tray_rust)

### 图像处理 Image processing
> 图像处理的库

* [Imager](https://github.com/imager-io/imager) — 自动图像优化。
* [shssoichiro/oxipng](https://github.com/shssoichiro/oxipng) [[oxipng](https://crates.io/crates/oxipng)] — 多线程PNG优化器写在生锈。[![Build Status](https://github.com/shssoichiro/oxipng/workflows/oxipng/badge.svg)](https://github.com/shssoichiro/oxipng/actions?query=branch%3Amaster) [![Version](https://img.shields.io/crates/v/oxipng.svg)](https://crates.io/crates/oxipng)

### 工业自动化 Industrial automation
> 工业自动化

* [locka99/opcua](https://github.com/locka99/opcua) — 纯粹的铁锈 [OPC UA](https://opcfoundation.org/about/opc-technologies/opc-ua/) 库.
* [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus) — 一个 [tokio](https://tokio.rs)-基于 [modbus](https://modbus.org) 库. [![Build Status](https://api.travis-ci.org/slowtec/tokio-modbus.svg?branch=master)](https://travis-ci.org/slowtec/tokio-modbus)

### 可观察性 Observability
> 可观察性

* [avito-tech/bioyino](https://github.com/avito-tech/bioyino) — 高性能可伸缩StatsD兼容的服务器。
* [OpenTelemetry](https://crates.io/crates/opentelemetry) — OpenTelemetry提供了一组api、图书馆服务代理和收集器捕获分布式痕迹和指标从您的应用程序。你可以分析他们使用普罗米修斯,贼鸥和其他可观察性工具。[![GitHub Actions CI](https://github.com/open-telemetry/opentelemetry-rust/workflows/CI/badge.svg?branch=master)](https://github.com/open-telemetry/opentelemetry-rust/actions?query=workflow%3ACI+branch%3Amaster)
* [Quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit) - 用于日志管理的云原生和高成本效益的搜索引擎. [![CI](https://github.com/quickwit-oss/quickwit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/quickwit-oss/quickwit/actions?query=workflow%3ACI)
* [Scaphandre](https://github.com/hubblo-org/scaphandre) - 一个功耗监测代理，跟踪主机和每个服务的功耗，使系统和应用程序的设计更具有可持续性。设计成适合任何监测工具链（已经支持Prometheus、warp10、riemann...）.
* [vectordotdev/vector](https://github.com/vectordotdev/vector) — 高性能、日志、指标,

### 操作系统 Operating systems
> 操作系统

另见 [A comparison of operating systems written in Rust](https://github.com/flosse/rust-os-comparison).
* [0x59616e/SteinsOS](https://github.com/0x59616e/SteinsOS)  — armv8-a架构的一个操作系统。
* [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox) — [![build badge](https://api.travis-ci.org/redox-os/redox.svg?branch=master)](https://travis-ci.org/redox-os/redox)
* [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) — [![build badge](https://api.travis-ci.org/thepowersgang/rust_os.svg?branch=master)](https://travis-ci.org/thepowersgang/rust_os)
* [theseus-os/Theseus](https://github.com/theseus-os/Theseus) — safe-language,单地址空间和单一的特权级别操作系统写在纯粹的铁锈——从头开始[![build badge](https://img.shields.io/github/workflow/status/theseus-os/Theseus/Documentation?label=docs%20build)](https://www.theseus-os.com/Theseus/book/index.html)
* [tock/tock](https://github.com/tock/tock) — 安全嵌入式操作系统基于Cortex-M微控制器

### 生产力 Productivity
> 生产力

* [Bartib](https://github.com/nikolassv/bartib) [[Bartib](https://crates.io/crates/bartib)] - 一个用于命令行的简单时间记录器 [![Tests](https://github.com/nikolassv/bartib/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/nikolassv/bartib/actions/workflows/test.yml)
* [espanso](https://github.com/espanso/espanso) — 一个跨平台的文本编写的扩展器生锈[![CI](https://github.com/espanso/espanso/actions/workflows/ci.yml/badge.svg?branch=dev&event=push)](https://github.com/espanso/espanso/actions/workflows/ci.yml)
* [eureka](https://crates.io/crates/eureka) — CLI工具输入和存储你的想法没有离开码头
* [pier-cli/pier](https://github.com/pier-cli/pier) — 一个中央存储库来管理(添加、搜索元数据等等)你所有的俏皮话,脚本,工具和综合领先指标

### 安全工具 Security tools
> 安全工具

* [AFLplusplus/LibAFL](https://github.com/AFLplusplus/LibAFL) - 高级模糊库 - 在Rust中把你的模糊器放在一起! 跨核心和机器的规模。适用于Windows、Android、MacOS、Linux、no_std等。[！[构建和测试](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml)
* [arvancloud/libinjection-rs](https://github.com/arvancloud/libinjection-rs) - [libinjection](https://github.com/client9/libinjection)的Rust绑定 [! [build badge](https://api.travis-ci.org/arvancloud/libinjection-rs.svg?branch=master)](https://travis-ci.org/arvancloud/libinjection-rs)
* [Cherrybomb](https://github.com/blst-security/cherrybomb) - 用一个CLI工具停止半成品的API规范，该工具通过验证你的API规范来帮助你避免未定义的用户行为。
* [epi052/feroxbuster](https://github.com/epi052/feroxbuster) - 一个用Rust编写的简单、快速、递归的内容发现工具(
* [Inspektor](https://github.com/inspektor-dev/inspektor) - 一个数据库协议感知代理，用于执行访问策略👮。
* [kpcyrd/authoscope](https://github.com/kpcyrd/authoscope) - 一个可编写脚本的网络认证破解器[![构建徽章](https://api.travis-ci.org/kpcyrd/authoscope.svg?branch=master)](https://travis-ci.org/kpcyrd/authoscope)
* [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack) - 一个TCP连接劫持者，shijack的重写[![build badge](https://api.travis-ci.org/kpcyrd/rshijack.svg?branch=master)](https://travis-ci.org/kpcyrd/rshijack)
* [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) - 一个半自动的OSINT框架和软件包管理器[![build badge](https://api.travis-ci.org/kpcyrd/sn0int.svg?branch=master)](https://travis-ci.org/kpcyrd/sn0int)
* [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) - 一个安全的多线程数据包嗅探器[![build badge](https://api.travis-ci.org/kpcyrd/sniffglue.svg?branch=master)](https://travis-ci.org/kpcyrd/sniffglue)
* [ObserverWard](https://github.com/0x727/ObserverWard) - 基于社区的网络技术分析工具。
* [phra/rustbuster](https://github.com/phra/rustbuster) - 一个全面的网络模糊器和内容发现工具。
* [ripasso](https://github.com/cortex/ripasso/) - 一个密码管理器，文件系统兼容pass
* [rustscan/rustscan](https://github.com/RustScan/RustScan) - 用这个端口扫描工具使Nmap更快 [![build badge](https://github.com/RustScan/RustScan/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/RustScan/RustScan/actions?query=workflow%3A%22Continuous+integration%22)


### 模拟 Simulation
> 模拟

* [hEngine](https://github.com/hashintel/hash/tree/main/packages/engine) - 一个由Rust实现的计算仿真引擎，支持大规模基于代理的建模，仿真逻辑由JavaScript和Python编写。.

### 社交网络 Social networks
> 社交网络

* Mastodon
  * [Rustodon](https://github.com/rustodon/rustodon) - 一个与Mastodon兼容、使用ActivityPub语言的Rust服务器

### 系统工具 System tools
> 系统工具

* [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide/) — 一个快速替代“cd”,学习你的习惯[![release](https://github.com/ajeetdsouza/zoxide/workflows/.github/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)
* [Alonely0/Voila](https://github.com/Alonely0/Voila) — 瞧是一个特定于域的语言通过CLI启动工具的操作与文件和目录在大量快[![Linux build](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml) [![macOS build](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml) [![Windows build](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml)
* [bandwhich](https://github.com/imsnif/bandwhich) — 终端带宽利用的工具[![build badge](https://api.travis-ci.com/imsnif/bandwhich.svg?branch=master)](https://app.travis-ci.com/github/imsnif/bandwhich)
* [bottom](https://github.com/ClementTsang/bottom) - 然而，另一个跨平台的图形化进程/系统监视器. [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ClementTsang/bottom/ci/master)](https://github.com/ClementTsang/bottom/actions?query=branch%3Amaster)
* [brocode/fblog](https://github.com/brocode/fblog) — 小命令行JSON日志查看器[![build badge](https://api.travis-ci.org/brocode/fblog.svg?branch=master)](https://travis-ci.org/brocode/fblog)
* [bustd](https://github.com/vrmiguel/bustd) - 轻量级的进程杀手守护程序，处理Linux上的内存不足情况. [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/vrmiguel/bustd/build-and-test)](https://github.com/vrmiguel/bustd/actions?query=branch%3Amaster)
* [buster/rrun](https://github.com/buster/rrun) — Linux的命令启动程序,类似于gmrun[![build badge](https://api.travis-ci.org/buster/rrun.svg?branch=master)](https://travis-ci.org/buster/rrun)
* [cantino/mcfly](https://github.com/cantino/mcfly) - 飞过你的炮弹历史。伟大的斯科特! [![build badge](https://api.travis-ci.org/cantino/mcfly.svg?branch=master)](https://travis-ci.org/cantino/mcfly)
* [crabz](https://github.com/sstadick/crabz) - 多线程压缩和解压的CLI工具 [![Build Status](https://github.com/sstadick/crabz/workflows/Check/badge.svg)](https://github.com/sstadick/crabz/actions?query=workflow%3ACheck)
* [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy) — 一个可配置的文件系统中受到启发[entr](http://eradman.com/entrproject/) [![build badge](https://api.travis-ci.org/cristianoliveira/funzzy.svg?branch=master)](https://travis-ci.org/cristianoliveira/funzzy)
* [dalance/procs](https://github.com/dalance/procs) — 现代替代“ps”写的生锈[![Regression](https://github.com/dalance/procs/actions/workflows/regression.yml/badge.svg)](https://github.com/dalance/procs/actions/workflows/regression.yml)
* [ddh](https://github.com/darakian/ddh) — 快速复制文件查找器[![build badge](https://api.travis-ci.org/darakian/ddh.svg?branch=master)](https://travis-ci.org/darakian/ddh)
* [diskonaut](https://github.com/imsnif/diskonaut) — 终端视觉磁盘空间导航器[![build badge](https://api.travis-ci.com/imsnif/diskonaut.svg?branch=main)](https://app.travis-ci.com/github/imsnif/diskonaut)
* [dust](https://github.com/bootandy/dust) — 杜的更直观的版本
* [fselect](https://crates.io/crates/fselect) — 找到文件类似sql的查询[![build badge](https://api.travis-ci.org/jhspetersson/fselect.svg?branch=master)](https://travis-ci.org/jhspetersson/fselect)
* [gitui](https://github.com/extrawurst/gitui) - 用Rust编写的极快的git终端客户端. [![build](https://github.com/extrawurst/gitui/workflows/CI/badge.svg?branch=master)](https://github.com/extrawurst/gitui/actions)
* [Kondo](https://github.com/tbillington/kondo) - 用于删除软件项目工件和回收磁盘空间的CLI和GUI工具
* [lotabout/rargs](https://github.com/lotabout/rargs) [[rargs](https://crates.io/crates/rargs)] — xargs awk与模式匹配的支持[![build badge](https://api.travis-ci.org/lotabout/rargs.svg?branch=master)](https://travis-ci.org/lotabout/rargs)
* [lotabout/skim](https://github.com/lotabout/skim) — 模糊查找器在纯生锈[![build badge](https://api.travis-ci.org/lotabout/skim.svg?branch=master)](https://travis-ci.org/lotabout/skim)
* [Luminarys/synapse](https://github.com/Luminarys/synapse) — 灵活和快速bt守护进程。[![Build Status](https://api.travis-ci.org/Luminarys/synapse.svg?branch=master)](https://travis-ci.org/Luminarys/synapse)
* [m4b/bingrep](https://github.com/m4b/bingrep) — grep通过不同OSs的二进制文件和体系结构,和颜色。[![build badge](https://api.travis-ci.org/m4b/bingrep.svg?branch=master)](https://travis-ci.org/m4b/bingrep)
* [mitnk/cicada](https://github.com/mitnk/cicada) — 一个类似bash的Unix shell[![build badge](https://api.travis-ci.org/mitnk/cicada.svg?branch=master)](https://travis-ci.org/mitnk/cicada)
* [mmstick/concurr](https://github.com/mmstick/concurr) — 替代GNU平行w /客户机-服务器体系结构
* [mmstick/fontfinder](https://github.com/mmstick/fontfinder) — GTK3预览申请和安装谷歌的字体
* [mmstick/tv-renamer](https://github.com/mmstick/tv-renamer) — 电视剧重命名的应用程序和一个可选的GTK3前端。[![build badge](https://api.travis-ci.org/mmstick/tv-renamer.svg?branch=master)](https://travis-ci.org/mmstick/tv-renamer)
* [mxseev/logram](https://github.com/mxseev/logram) — 把日志文件的更新电报
* [nickgerace/gfold](https://github.com/nickgerace/gfold)[[gfold](https://crates.io/crates/gfold)] - 帮助跟踪多个Git存储库的CLI工具 [![build](https://img.shields.io/github/workflow/status/nickgerace/gfold/merge/main)](https://github.com/nickgerace/gfold/actions?query=workflow%3Amerge+branch%3Amain)
* [nivekuil/rip](https://github.com/nivekuil/rip) - 一个安全和符合人体工程学的替代品 对`rm`而言 [![build badge](https://api.travis-ci.org/nivekuil/rip.svg?branch=master)](https://travis-ci.org/nivekuil/rip)
* [ogham/exa](https://github.com/ogham/exa) — 代替“ls”[![build badge](https://api.travis-ci.org/ogham/exa.svg?branch=master)](https://travis-ci.org/ogham/exa)
* [orhun/kmon](https://github.com/orhun/kmon) — Linux内核经理和活动监视器![https://github.com/orhun/kmon/actions](https://img.shields.io/github/workflow/status/orhun/kmon/Continuous%20Integration/master?label=build)
* [orhun/systeroid](https://github.com/orhun/systeroid) — 一个更强大的替代sysctl(8)与终端用户界面![https://github.com/orhun/systeroid/actions](https://img.shields.io/github/workflow/status/orhun/systeroid/Continuous%20Integration/main?label=build)
* [ouch](https://github.com/ouch-org/ouch) - 在命令行上进行无痛压缩和解压 [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ouch-org/ouch/build-and-test)](https://github.com/ouch-org/ouch/actions?query=branch%3Amaster)
* [Peltoche/lsd](https://github.com/Peltoche/lsd) — 一个ls有很多漂亮的颜色和令人敬畏的图标[![build](https://github.com/Peltoche/lsd/workflows/CICD/badge.svg?branch=master)](https://github.com/Peltoche/lsd/actions)
* [pop-os/popsicle](https://github.com/pop-os/popsicle) — GTK3
* [pop-os/system76-power](https://github.com/pop-os/system76-power/) — Linux电源管理守护进程(DBus-interface)与CLI的工具。
* [pueue](https://github.com/nukesor/pueue) — 管理你的长时间运行shell命令。[![GitHub Actions Workflow](https://github.com/nukesor/pueue/workflows/Test%20build/badge.svg?branch=master)](https://github.com/nukesor/pueue/actions)
* [qarmin/cakawka](https://github.com/qarmin/czkawka) - 多功能的应用程序，可以找到重复的，空的文件夹，类似的图像等。. [![GitHub Actions Workflow](https://github.com/qarmin/czkawka/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master)](https://github.com/qarmin/czkawka/actions)
* [redox-os/ion](https://github.com/redox-os/ion) — 下一代系统外壳[![build badge](https://api.travis-ci.org/redox-os/ion.svg?branch=master)](https://travis-ci.org/redox-os/ion)
* [sharkdp/bat](https://github.com/sharkdp/bat) — 长着翅膀的猫(1)克隆。[![CICD](https://github.com/sharkdp/bat/actions/workflows/CICD.yml/badge.svg?branch=master)](https://github.com/sharkdp/bat/actions/workflows/CICD.yml)
* [sharkdp/fd](https://github.com/sharkdp/fd) — 一个简单、快速、友好的替代。[![CICD](https://github.com/sharkdp/fd/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/fd/actions/workflows/CICD.yml)
* [sitkevij/hex](https://github.com/sitkevij/hex) — 一个彩色的hexdump终端效用。[![build badge](https://api.travis-ci.org/sitkevij/hex.svg?branch=master)](https://travis-ci.org/sitkevij/hex)
* [trippy](https://github.com/fujiapple852/trippy) - 一个网络诊断工具 [![build badge](https://github.com/fujiapple852/trippy/workflows/CI/badge.svg)](https://github.com/fujiapple852/trippy/actions/workflows/ci.yml)
* [uutils/coreutils](https://github.com/uutils/coreutils) — 跨平台锈GNU coreutils的重写[[![CICD](https://github.com/uutils/coreutils/actions/workflows/CICD.yml/badge.svg)](https://github.com/uutils/coreutils/actions/workflows/CICD.yml)
* [watchexec](https://github.com/watchexec/watchexec) — 执行命令响应文件的修改[![build badge](https://api.travis-ci.org/watchexec/watchexec.svg?branch=master)](https://travis-ci.org/watchexec/watchexec)
* [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei) — 计算行代码[![build badge](https://api.travis-ci.org/XAMPPRocky/tokei.svg?branch=master)](https://travis-ci.org/XAMPPRocky/tokei)

### 任务调度 Task scheduling
> 任务调度

* [delicate](https://github.com/BinChengZhao/delicate) — 一个用Rust编写的轻量级分布式任务调度平台. [![Build Status](https://github.com/BinChengZhao/delicate/workflows/CI/badge.svg)](https://github.com/BinChengZhao/delicate/actions)

### 文本编辑器 Text editors
> 文本编辑器

* [amp](https://amp.rs) - 受Vi/Vim的启发。[![build badge](https://api.travis-ci.org/jmacdonald/amp.svg?branch=master)](https://travis-ci.org/jmacdonald/amp)
* [gchp/iota](https://github.com/gchp/iota) - 一个简单的文本编辑器 [! [build badge](https://api.travis-ci.org/gchp/iota.svg?branch=master)](https://travis-ci.org/gchp/iota)
* [helix](https://github.com/helix-editor/helix) - 一个后现代模式的文本编辑器，灵感来自Neovim/Kakoune。[![build badge](https://github.com/helix-editor/helix/actions/workflows/build.yml/badge.svg)](https://github.com/helix-editor/helix/actions)
* [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi) - 一个微小的（≤1024 LOC）文本编辑器，具有语法高亮、增量搜索等功能。[![build badge](https://github.com/ilai-deutel/kibi/workflows/CI/badge.svg?branch=master)](https://github.com/ilai-deutel/kibi/actions?query=branch%3Amaster)
* [lapce](https://github.com/lapce/lapce) - 用Rust编写的闪电般快速和强大的代码编辑器。[![build badge](https://github.com/lapce/lapce/actions/workflows/release.yml/badge.svg)](https://github.com/lapce/lapce/actions/workflows/release.yml)
* [mathall/rim](https://github.com/mathall/rim) - 用Rust编写的类似Vim的文本编辑器
* [ox](https://github.com/curlpipe/ox) - 一个独立的Rust文本编辑器，可以在你的终端中运行!
* [Remacs](https://github.com/remacs/remacs) - 一个由社区驱动的Emacs到Rust的移植。[![build badge](https://api.travis-ci.org/remacs/remacs.svg?branch=master)](https://travis-ci.org/remacs/remacs)
* [vamolessa/pepper](https://github.com/vamolessa/pepper) [[pepper](https://crates.io/crates/pepper)] - 一个有意见的模式编辑器，以简化终端的代码编辑 [![build badge](https://github.com/vamolessa/pepper/workflows/rust/badge.svg?branch=master)](https://github.com/vamolessa/pepper)
* [xi-editor](https://github.com/xi-editor/xi-editor) - 一个用Rust编写的后端现代编辑器。

### 文本处理 Text processing
> 文本处理

* [dominikwilkowski/cfonts](https://github.com/dominikwilkowski/cfonts) [[cfonts](https://crates.io/crates/cfonts)] — 性感的ANSI控制台的字体![build badge](https://github.com/dominikwilkowski/cfonts/actions/workflows/testing.yml/badge.svg)
* [grex](https://github.com/pemistahl/grex) — 一个命令行工具和库从用户提供的测试用例生成正则表达式[![build badge](https://api.travis-ci.org/pemistahl/grex.svg?branch=master)](https://travis-ci.org/pemistahl/grex)
* [Lisprez/so_stupid_search](https://github.com/Lisprez/so_stupid_search) — 一个简单和快速字符串搜索工具为人类
* [Melody](https://github.com/yoav-lavi/melody) - 一种可以编译成正则表达式的语言，旨在更容易阅读和维护 [![build badge](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml/badge.svg)](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml) [![crates.io](https://img.shields.io/crates/v/melody_compiler?label=compiler)](https://crates.io/crates/melody_compiler)
* [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all) — ripgrep,还搜索pdf,电子书,办公文档,邮政、焦油。广州等。[![Build Status](https://api.travis-ci.org/phiresky/ripgrep-all.svg?branch=master)](https://travis-ci.org/phiresky/ripgrep-all)
* [replicadse/complate](https://github.com/replicadse/complate) — 一个晚期的文本模板工具设计标准化信息(如GIT提交)。[![crates.io](https://img.shields.io/crates/v/complate.svg)](https://crates.io/crates/complate) [![crates.io](https://img.shields.io/crates/d/complate?label=crates.io%20downloads)](https://crates.io/crates/complate) [![build badge](https://github.com/replicadse/complate/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/complate/actions)
* [ripgrep](https://crates.io/crates/ripgrep) — 结合了银搜索器的可用性和grep的原始速度[![build badge](https://api.travis-ci.org/BurntSushi/ripgrep.svg?branch=master)](https://travis-ci.org/BurntSushi/ripgrep)
* [ruplacer](https://github.com/your-tools/ruplacer) — 在源文件查找和替换文本[![Run tests](https://github.com/your-tools/ruplacer/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/your-tools/ruplacer/actions/workflows/test.yml)
* [sd](https://crates.io/crates/sd) — 直观的发现
* [sstadick/hck](https://github.com/sstadick/hck) - 更快、更有特色地取代了`cut`。  [![build badge](https://github.com/sstadick/hck/workflows/Check/badge.svg?branch=master)](https://github.com/sstadick/hck)
* [vishaltelangre/ff](https://github.com/vishaltelangre/ff) — 找到文件(ff)的名字![![build badge](https://api.travis-ci.org/vishaltelangre/ff.svg?branch=master)](https://travis-ci.org/vishaltelangre/ff)
* [whitfin/bytelines](https://github.com/whitfin/bytelines) [[bytelines](https://crates.io/crates/bytelines)] — 读取输入线作为字节片效率高。
* [whitfin/runiq](https://github.com/whitfin/runiq) — 一种有效的方式来过滤从无序输入重复的行。
* [xsv](https://crates.io/crates/xsv) — 快速CSV命令行工具(切片、索引、选择搜索、抽样等)[![build badge](https://api.travis-ci.org/BurntSushi/xsv.svg?branch=master)](https://travis-ci.org/BurntSushi/xsv)

### 公用事业公司 Utilities
> 公用事业公司

* [1History](https://github.com/1History/1History) - 命令行界面，将Firefox/Chrome/Safari的历史备份到一个SQLite文件[![Build Status](https://github.com/1History/1History/actions/workflows/CI.yml/badge.svg)](https://github.com/1History/1History/actions/workflows/CI.yml)
* [brycx/checkpwn](https://github.com/brycx/checkpwn) - 一个HIBP（Have I Been Pwned）命令行工具，可以让你轻松地检查被入侵的账户和密码。
* [evansmurithi/cloak](https://github.com/evansmurithi/cloak) - 一个命令行OTP（一次性密码）验证器应用程序。
  ![CI](https://github.com/evansmurithi/cloak/workflows/CI/badge.svg) [![build badge](https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true)](https://ci.appveyor.com/project/evansmurithi/cloak)
* [fcsonline/tmux-thumbs](https://github.com/fcsonline/tmux-thumbs) - 一个用Rust编写的闪电般的tmux-fingers版本，像vimium/vimperator一样复制/粘贴tmux。
* [guoxbin/dtool](https://github.com/guoxbin/dtool) - 一个有用的命令行工具集，以协助开发，包括转换、编解码、散列、加密等。[![Build Status](https://api.travis-ci.org/guoxbin/dtool.svg?branch=master)](https://travis-ci.org/guoxbin/dtool)
* [mprocs](https://github.com/pvolok/mprocs) - 用于运行多个进程的TUI
* [nomino](https://github.com/yaa110/nomino) - 开发人员的批量重命名工具 [![Build Status](https://api.travis-ci.org/yaa110/nomino.svg?branch=master)](https://travis-ci.org/yaa110/nomino)
* [raftario/licensor](https://github.com/raftario/licensor) - 将许可证写入stdout [![GitHub Actions](https://github.com/raftario/licensor/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/raftario/licensor/actions/workflows/build.yml)
* [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) - 一个远程桌面软件，是TeamViewer和AnyDesk的最佳替代品。
* [tversteeg/emplace](https://github.com/tversteeg/emplace) - 在多台机器上同步安装软件包
* [vamolessa/verco](https://github.com/vamolessa/verco) [[verco](https://crates.io/crates/verco)] - 一个专注于键盘快捷键的简单Git/Hg tui客户端
* [vaultwarden](https://github.com/dani-garcia/vaultwarden#readme) [![Build](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml/badge.svg)](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml) - 用Rust编写的Bitwarden服务器API的替代实现
* [yaa110/cb](https://github.com/yaa110/cb) - 管理剪贴板的命令行界面 [![Build Status](https://api.travis-ci.org/yaa110/cb.svg?branch=master)](https://travis-ci.org/yaa110/cb)

### 视频 Video
> 视频

* [dertuxmalwieder/yaydl](https://github.com/dertuxmalwieder/yaydl) [[yaydl](https://crates.io/crates/yaydl)] - 一个简单的视频下载器
* [harlanc/xiu](https://github.com/harlanc/xiu) - 一个由pure rust（rtmp/httpflv/hls/relay）构成的强大而安全的实时服务器。[![Build Status](https://api.travis-ci.com/harlanc/xiu.svg?branch=master)](https://app.travis-ci.com/github/harlanc/xiu) [！[crates.io](https://img.shields.io/crates/v/xiu.svg)](https://crates.io/crates/xiu)
* [xiph/rav1e](https://github.com/xiph/rav1e) -最快和最安全的AV1编码器。[![build badge](https://api.travis-ci.org/xiph/rav1e.svg?branch=master)](https://travis-ci.org/xiph/rav1e)

### 虚拟化 Virtualization
> 虚拟化

* [containers/youki](https://github.com/containers/youki) - Rust中的一个容器运行时间[![build badge](https://github.com/containers/youki/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/containers/youki/actions)
* [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) - 一个用于容器工作负载的轻量级虚拟机[Firecracker Microvm](https://firecracker-microvm.github.io/)
* [tailhook/vagga](https://github.com/tailhook/vagga) - 一个没有守护程序的容器化工具[![build badge](https://api.travis-ci.org/tailhook/vagga.svg?branch=master)](https://travis-ci.org/tailhook/vagga)

### 网络 Web
> 网络

* [cfal/tobaru](https://github.com/cfal/tobaru) - 具有允许列表、IP和TLS SNI/ALPN规则路由、iptables支持、轮流转发（负载平衡）和热重载的端口转发器.
* [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy) — 一个链接聚合器/ reddit fediverse克隆[![Build Status](https://cloud.drone.io/api/badges/LemmyNet/lemmy/status.svg)](https://cloud.drone.io/LemmyNet/lemmy)
* [libreddit](https://github.com/libreddit/libreddit) - Reddit的另一个私人前端
* [MASQ-Project/Node](https://github.com/MASQ-Project/Node) — MASQ节点软件提供了一个分散的网状网络的节点为全球互联网用户访问正常内容——下一个进化的科技超越Tor[![build badge](https://github.com/MASQ-Project/Node/actions/workflows/ci-matrix.yml/badge.svg)](https://github.com/MASQ-Project/Node/actions)
* [Plume-org/Plume](https://github.com/Plume-org/Plume) — ActivityPub联合博客应用程序[![build badge](https://api.travis-ci.org/Plume-org/Plume.svg?branch=master)](https://travis-ci.org/Plume-org/Plume)
* [Revolt/backend](https://github.com/revoltchat/backend) - 用现代网络技术建立的用户至上的聊天平台.

### Web服务器 Web Servers
> Web服务器

* [mufeedvh/binserve](https://github.com/mufeedvh/binserve) - 一个快得惊人的静态网络服务器，在一个单一的二进制文件中具有路由、模板和安全功能，你可以用零代码进行设置[![build badge](https://github.com/mufeedvh/binserve/workflows/CICD/badge.svg?branch=master)](https://github.com/mufeedvh/binserve/actions)
* [orhun/rustypaste](https://github.com/orhun/rustypaste) - 一个最小的文件上传/粘贴服务！[https://github.com/orhun/rustypaste/actions](https://img.shields.io/github/workflow/status/orhun/rustypaste/Continuous%20Integration/master?label=build)
* [ronanyeah/rust-hasura](https://github.com/ronanyeah/rust-hasura) - 演示如何用[Hasura](https://hasura.io/)将Rust GraphQL服务器作为远程模式！[Rust](https://github.com/ronanyeah/rust-hasura/workflows/Rust/badge.svg?branch=master)
* [static-web-server](https://github.com/static-web-server/static-web-server) - 一个用于静态文件服务的极快的异步网络服务器。⚡ [![CI](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml/badge.svg)](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml?query=branch%3Amaster)
* [svenstaro/miniserve](https://github.com/svenstaro/miniserve) - 一个小型、独立的跨平台CLI工具，允许你通过HTTP抓取二进制文件并提供一些文件[![build badge](https://github.com/svenstaro/miniserve/workflows/CI/badge.svg?branch=master)](https://github.com/svenstaro/miniserve/actions)
* [thecoshman/http](https://github.com/thecoshman/http) - 请主持这些事情 - 一个基本的http服务器，用于快速而简单地托管一个文件夹 [![build badge](https://api.travis-ci.org/thecoshman/http.svg?branch=master)](https://travis-ci.org/thecoshman/http)
* [TheWaWaR/Simple-http-server](https://github.com/TheWaWaR/simple-http-server) - 简单的静态http服务器
* [wyhaya/see](https://github.com/wyhaya/see) - 静态HTTP文件服务器[![构建状态](https://api.travis-ci.org/wyhaya/see.svg?branch=master)](https://travis-ci.org/wyhaya/see)

## 开发工具 Development tools
> 开发工具

* [bacon](https://github.com/Canop/bacon) — 背景锈代码检查器,类似于cargo-watch
* [clippy](https://crates.io/crates/clippy) — 生锈的绑带[![build badge](https://api.travis-ci.com/rust-lang/rust-clippy.svg?branch=master)](https://travis-ci.org/rust-lang/rust-clippy)
* [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli) — 生成一个更新日志从git元数据([conventional changelog](https://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html)) [![build badge](https://api.travis-ci.org/clog-tool/clog-cli.svg?branch=master)](https://travis-ci.org/clog-tool/clog-cli)
* [comtrya](https://github.com/comtrya/comtrya) — 为localhost / .配置管理工具[![build badge](https://github.com/comtrya/comtrya/actions/workflows/main.yaml/badge.svg)](https://github.com/comtrya/comtrya/actions)
* [create-rust-app](https://github.com/Wulf/create-rust-app) — 建立一个现代锈蚀反应web应用程序通过运行一个命令。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/create-rust-app)
* [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags) — 创建ctags / etag货物项目和它的所有依赖项[![build badge](https://api.travis-ci.org/dan-t/rusty-tags.svg?branch=master)](https://travis-ci.org/dan-t/rusty-tags)
* [datanymizer/datanymizer](https://github.com/datanymizer/datanymizer) - 具有灵活规则的强大的数据库匿名器 [![build badge](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg?branch=main)](https://github.com/datanymizer/datanymizer/actions?query=workflow%3ACI+branch%3Amain)
* [delta](https://crates.io/crates/git-delta) — git的语法高亮显示和diff输出[![build badge](https://github.com/dandavison/delta/workflows/Continuous%20Integration/badge.svg)](https://github.com/dandavison/delta//actions)
* [dotenv-linter](https://github.com/dotenv-linter/dotenv-linter) — 用于".env "文件的链接器 [![build badge](https://github.com/dotenv-linter/dotenv-linter/workflows/CI/badge.svg?branch=master)](https://github.com/dotenv-linter/dotenv-linter/actions?query=workflow%3ACI+branch%3Amaster)
* [fw](https://github.com/brocode/fw) — 工作区生产率助推器[![Rust](https://github.com/brocode/fw/actions/workflows/rust.yml/badge.svg)](https://github.com/brocode/fw/actions/workflows/rust.yml)
* [geiger](https://github.com/rust-secure-code/cargo-geiger) — 程序列表统计相关的使用不安全的铁锈代码锈箱及其所有依赖项[![Build Status](https://dev.azure.com/cargo-geiger/cargo-geiger/_apis/build/status/rust-secure-code.cargo-geiger?branchName=master)](https://dev.azure.com/cargo-geiger/cargo-geiger/_build/latest?definitionId=1&branchName=master)
* [git-cliff](https://github.com/orhun/git-cliff) — 一个高度可定制的Changelog生成器,遵循传统的提交规范![https://github.com/orhun/git-cliff/actions](https://img.shields.io/github/workflow/status/orhun/git-cliff/Continuous%20Integration/main?label=build)
* [git-journal](https://github.com/saschagrunert/git-journal/) — Git提交消息和更新日志生成框架[![build badge](https://api.travis-ci.org/saschagrunert/git-journal.svg?branch=master)](https://travis-ci.org/saschagrunert/git-journal)
* [hot-lib-reloader](https://github.com/rksm/hot-lib-reloader-rs) — 热重载生锈的代码[![build badge](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml)
* [just](https://github.com/casey/just) — 一个方便的命令运动员为具体项目任务[![build badge](https://api.travis-ci.org/casey/just.svg?branch=master)](https://travis-ci.org/casey/just)
* [mask](https://github.com/jacobdeichert/mask) — 跑一个CLI的任务由一个简单的减价文件定义的[![build badge](https://github.com/jacobdeichert/mask/workflows/CI/badge.svg?branch=master)](https://github.com/jacobdeichert/mask/actions?query=workflow%3ACI)
* [Module Linker](https://github.com/fiatjaf/module-linker) — 扩展补充道“< >”链接引用“国防部”,“使用”和“走读生箱”在GitHub语句。
* [ptags](https://github.com/dalance/ptags) — 一个平行universal-ctags包装git存储库[![Build Status](https://api.travis-ci.org/dalance/ptags.svg?branch=master)](https://travis-ci.org/dalance/ptags)
* [Racer](https://github.com/racer-rust/racer) — 代码完成的生锈[![build badge](https://api.travis-ci.org/racer-rust/racer.svg?branch=master)](https://travis-ci.org/racer-rust/racer)
* [Rust Search Extension](https://github.com/huhu/rust-search-extension) — 一个方便的浏览器扩展在地址栏搜索箱和文档(omnibox)。[![Build Status](https://github.com/huhu/rust-search-extension/workflows/build/badge.svg?branch=master)](https://github.com/huhu/rust-search-extension/actions)
* [rust-lang/rustfix](https://github.com/rust-lang/rustfix)  — 由rustc自动应用建议
* [Rustup](https://github.com/rust-lang/rustup) — 生锈的工具链安装程序[![build badge](https://github.com/rust-lang/rustup/workflows/Linux%20(master)/badge.svg?branch=master)](https://github.com/rust-lang/rustup/actions)
* [scriptisto](https://github.com/igor-petruk/scriptisto) 一个与语言无关的 "shebang解释器"，使你能够用编译的语言编写一个文件的脚本. [![Build Status](https://cloud.drone.io/api/badges/igor-petruk/scriptisto/status.svg)](https://cloud.drone.io/igor-petruk/scriptisto)

### 构建系统 Build system
> 构建系统

* [Cargo](https://crates.io/) — Rust软件包管理器
  * [cargo-all-features](https://github.com/frewsxcv/cargo-all-features) - 一个可配置的子命令，以简化所有功能组合的测试、构建和更多工作 [![CI](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml/badge.svg)](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml)
  * [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp) — 一个实用程序比较锈微型基准测试中[![build badge](https://api.travis-ci.org/BurntSushi/cargo-benchcmp.svg?branch=master)](https://travis-ci.org/BurntSushi/cargo-benchcmp)
  * [cargo-bitbake](https://crates.io/crates/cargo-bitbake) — 货物扩展,可以生成BitBake食谱从meta-rust利用类[![build badge](https://api.travis-ci.org/cardoe/cargo-bitbake.svg?branch=master)](https://travis-ci.org/cardoe/cargo-bitbake)
  * [cargo-cache](https://crates.io/crates/cargo-cache) — 检查/管理/清洁你的货物缓存(~ / .cargo /的/ $ {CARGO_HOME}),打印尺寸等[![Build Status](https://github.com/matthiaskrgr/cargo-cache/workflows/ci/badge.svg?branch=master)](https://github.com/matthiaskrgr/cargo-cache/actions)
  * [cargo-check](https://crates.io/crates/cargo-check) — 包装的货物rustc——-Zno-trans”可以帮助更快的编译,如果你只需要运行正确性检查[![build badge](https://api.travis-ci.org/rsolomo/cargo-check.svg?branch=master)](https://travis-ci.org/rsolomo/cargo-check)
  * [cargo-count](https://crates.io/crates/cargo-count) — 列出源代码数量和货物的详细信息项目,包括安全统计数据[![build badge](https://api.travis-ci.org/kbknapp/cargo-count.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-count)
  * [cargo-deb](https://crates.io/crates/cargo-deb) — 生成二进制Debian软件包[![build badge](https://api.travis-ci.org/mmstick/cargo-deb.svg?branch=master)](https://travis-ci.org/mmstick/cargo-deb)
  * [cargo-deps](https://crates.io/crates/cargo-deps) — 锈项目的构建依赖图[![build badge](https://api.travis-ci.com/m-cat/cargo-deps.svg?branch=master)](https://travis-ci.org/m-cat/cargo-deps)
  * [cargo-do](https://crates.io/crates/cargo-do) — 货物运行多个命令行[![build badge](https://api.travis-ci.org/pwoolcoc/cargo-do.svg?branch=master)](https://travis-ci.org/pwoolcoc/cargo-do)
  * [cargo-ebuild](https://crates.io/crates/cargo-ebuild) — 货物扩展,可以使用在树生成ebuild eclass[![build badge](https://api.travis-ci.org/cardoe/cargo-ebuild.svg?branch=master)](https://travis-ci.org/cardoe/cargo-ebuild)
  * [cargo-edit](https://crates.io/crates/cargo-edit) — 允许您添加依赖项列表,读/写你的货物。toml文件从命令行[![build badge](https://api.travis-ci.org/killercup/cargo-edit.svg?branch=master)](https://travis-ci.org/killercup/cargo-edit)
  * [cargo-generate](https://github.com/cargo-generate/cargo-generate) - 通过利用预先存在的git仓库作为模板，生成一个锈蚀项目.
  * [cargo-graph](https://crates.io/crates/cargo-graph) — 更新叉cargo-dot的附加功能。未维护,请参见“cargo-deps”[![build badge](https://api.travis-ci.org/kbknapp/cargo-graph.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-graph)
  * [cargo-info](https://crates.io/crates/cargo-info) — 查询箱。从命令行io箱细节[![build badge](https://api.travis-ci.org/imp/cargo-info.svg?branch=master)](https://travis-ci.org/imp/cargo-info)
  * [cargo-license](https://crates.io/crates/cargo-license) — 货物子命令快速查看所有依赖项的许可证。[![build badge](https://api.travis-ci.org/onur/cargo-license.svg?branch=master)](https://travis-ci.org/onur/cargo-license)
  * [cargo-make](https://crates.io/crates/cargo-make) — 锈任务流道和构建工具。[![build badge](https://github.com/sagiegurari/cargo-make/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cargo-make/actions)
  * [cargo-modules](https://crates.io/crates/cargo-modules) — 货物插件显示树状箱模块的概述。[![build badge](https://api.travis-ci.org/regexident/cargo-modules.svg?branch=master)](https://travis-ci.org/regexident/cargo-modules)
  * [cargo-multi](https://crates.io/crates/cargo-multi) — 在多个板条箱货物运行指定的命令[![build badge](https://api.travis-ci.org/imp/cargo-multi.svg?branch=master)](https://travis-ci.org/imp/cargo-multi)
  * [cargo-outdated](https://crates.io/crates/cargo-outdated) — 显示当锈依赖性的较新版本可用,或过时了[![build badge](https://api.travis-ci.org/kbknapp/cargo-outdated.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-outdated)
  * [cargo-release](https://crates.io/crates/cargo-release) — 释放的工具git管理货物项目,构建、标签、发布、文档和推动[![Rust](https://github.com/crate-ci/cargo-release/actions/workflows/ci.yml/badge.svg)](https://github.com/crate-ci/cargo-release/actions/workflows/rust.yml)
  * [cargo-script](https://crates.io/crates/cargo-script) — 让人们快速、轻松地运行锈“脚本”,可以利用货物的包的生态系统[![build badge](https://api.travis-ci.org/DanielKeep/cargo-script.svg?branch=master)](https://travis-ci.org/DanielKeep/cargo-script)
  * [cargo-update](https://crates.io/crates/cargo-update) — 货物子命令检查和应用更新安装可执行文件[![build badge](https://api.travis-ci.org/nabijaczleweli/cargo-update.svg?branch=master)](https://travis-ci.org/nabijaczleweli/cargo-update)
  * [cargo-watch](https://crates.io/crates/cargo-watch) — 当来源改变效用货物编译项目[![build badge](https://api.travis-ci.org/passcod/cargo-watch.svg?branch=master)](https://travis-ci.org/passcod/cargo-watch)
  * [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) — 扩大在源代码的宏
* CMake
  * [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust) - 对于将Rust库集成到CMake项目中很有用
  * [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake) - 一个展示使用Rust的CMake的例子项目 [！[build badge](https://api.travis-ci.org/SiegeLord/RustCMake.svg?branch=master)](https://travis-ci.org/SiegeLord/RustCMake)
* [Fleet](https://github.com/dimensionhq/fleet) [[fleet-rs](https://crates.io/crates/fleet-rs)] - 用于Rust的快速构建工具。
* Github actions
  * [icepuma/rust-action](https://github.com/icepuma/rust-action) - rust github action
  * [peaceiris/actions-mdbook](https://github.com/peaceiris/actions-mdbook) - mdBook的GitHub动作

### 调试 Debugging
> 调试

* GDB
  * [gdbgui](https://github.com/cs01/gdbgui) — 基于浏览器的gdb前台，用于调试C、C++、Rust和go。 [![build badge](https://api.travis-ci.org/cs01/gdbgui.svg?branch=master)](https://travis-ci.org/cs01/gdbgui)
* LLDB
  * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — 一个LLDB扩展，用于 [Visual Studio Code](https://code.visualstudio.com/).

### 部署 Deployment
> 部署

* Docker
  * [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder) - 使用musl-libc和musl-gcc编译静态Rust二进制文件的Docker镜像，以及有用C库的静态版本
  * [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust) - 一个非常小的Rust docker镜像的例子项目[![build badge](https://api.travis-ci.org/kpcyrd/mini-docker-rust.svg?branch=master)](https://travis-ci.org/kpcyrd/mini-docker-rust)
  * [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup) - 一个多版本（含musl工具）Rust Docker镜像
  * [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef) - 一个工具和预建镜像，用于在Docker构建之间缓存编译远程依赖项。
  * [messense/rust-musl-cross](https://github.com/messense/rust-musl-cross) - 用于使用musl-cross编译静态Rust二进制文件的Docker镜像[![build badge](https://api.travis-ci.org/messense/rust-musl-cross.svg?branch=master)](https://travis-ci.org/messense/rust-musl-cross)
  * [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust) - 官方的Rust Docker图像c
* Github Pages
  * [wasm-template-rust](https://github.com/sn99/wasm-template-rust) — 一个用于Rust的wasm模板，无需npm-deploy即可发布到gh-pages上。
* Heroku
  * [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust) — 用于Heroku上Rust应用程序的构建包

### 嵌入式 Embedded
> 嵌入式

[Rust Embedded](https://rust-embedded.org/) 着重于改善在资源有限的环境和非传统平台中使用Rust的端到端体验。见 [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) 以获得更多的嵌入式Rust资源清单。.

* Arduino
  * [avr-rust/ruduino](https://github.com/avr-rust/ruduino) 用于Arduino Uno的可重复使用的组件.
* 交叉编译
  * [japaric/rust-cross](https://github.com/japaric/rust-cross) — 所有你需要知道的关于交叉编译锈程序[![build badge](https://api.travis-ci.org/japaric/rust-cross.svg?branch=master)](https://travis-ci.org/japaric/rust-cross)
  * [japaric/xargo](https://github.com/japaric/xargo) — 容易生锈的交叉编译程序自定义像手臂Cortex-M裸机目标[![build badge](https://api.travis-ci.org/japaric/xargo.svg?branch=master)](https://travis-ci.org/japaric/xargo)
* Espressif
  * [esp-rs](https://github.com/esp-rs) 在Espressif系统公司生产的各种SoC和模块上使用Rust编程语言的一些社区项目的所在地.
* nRF
  * [nrf-rs/nrf-hal](https://github.com/nrf-rs/nrf-hal) — nRF的家庭设备的生锈哈尔
    [![build badge](https://api.travis-ci.org/nrf-rs/nrf-hal.svg?branch=master)](https://travis-ci.org/nrf-rs/nrf-hal)

### FFI FFI
> FFI

另见 [Foreign Function Interface](https://doc.rust-lang.org/book/first-edition/ffi.html),  [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/) (一组使用其他语言的Rust编写的代码的例子) 和 [FFI examples written in Rust](https://github.com/alexcrichton/rust-ffi-examples).

* C
  * [rlhunt/cbindgen](https://github.com/eqrion/cbindgen) — 源文件生成C头文件从生锈。用于WebRender壁虎[![build badge](https://api.travis-ci.org/eqrion/cbindgen.svg?branch=master)](https://travis-ci.org/eqrion/cbindgen)
  * [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar) — 源文件生成C头文件从生锈[![build badge](https://api.travis-ci.org/Sean1708/rusty-cheddar.svg?branch=master)](https://travis-ci.org/Sean1708/rusty-cheddar)
* C++
  * [dtolnay/cxx](https://github.com/dtolnay/cxx) — 安全的铁锈和C之间的互操作[![build badge](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-the-badge&labelColor=555555&logo=github)](https://github.com/dtolnay/cxx)
  * [rust-cpp](https://crates.io/crates/cpp) - 在Rust中直接嵌入C++代码. [![Build Status](https://api.travis-ci.org/mystor/rust-cpp.svg?branch=master)](https://travis-ci.org/mystor/rust-cpp) [![Build status](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master?svg=true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
  * [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) — 锈绑定生成器
* Erlang
  * [rusterlium/rustler](https://github.com/rusterlium/rustler) — 安全锈桥为创建Erlang NIF功能[![build badge](https://api.travis-ci.org/rusterlium/rustler.svg?branch=master)](https://travis-ci.org/rusterlium/rustler)
* Java
  * [bennettanderson/rjni](https://github.com/benanders/rjni) — 使用Java从生锈
  * [drrb/java-rust-example](https://github.com/drrb/java-rust-example) — 在Java中使用生锈[![build badge](https://api.travis-ci.org/drrb/java-rust-example.svg?branch=master)](https://travis-ci.org/drrb/java-rust-example)
  * [j4rs](https://crates.io/crates/j4rs) — 使用Java从生锈[![build badge](https://api.travis-ci.org/astonbitecode/j4rs.svg?branch=master)](https://travis-ci.org/astonbitecode/j4rs)
  * [jni](https://crates.io/crates/jni) — 在Java中使用生锈[![build badge](https://api.travis-ci.org/jni-rs/jni-rs.svg?branch=master)](https://travis-ci.org/jni-rs/jni-rs)
  * [jni-sys](https://crates.io/crates/jni-sys) — 对应jni.h锈定义[![build badge](https://api.travis-ci.org/sfackler/rust-jni-sys.svg?branch=master)](https://travis-ci.org/sfackler/rust-jni-sys)
  * [rucaja](https://crates.io/crates/rucaja) — 使用Java从生锈[![build badge](https://api.travis-ci.org/kud1ing/rucaja.svg?branch=master)](https://travis-ci.org/kud1ing/rucaja)
* Lua
  * [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53) — Lua 5.3绑定生锈[![build badge](https://api.travis-ci.org/jcmoyer/rust-lua53.svg?branch=master)](https://travis-ci.org/jcmoyer/rust-lua53)
  * [lilyball/rust-lua](https://github.com/lilyball/rust-lua) — 安全锈绑定Lua 5.1[![build badge](https://api.travis-ci.org/lilyball/rust-lua.svg?branch=master)](https://travis-ci.org/lilyball/rust-lua)
  * [tickbh/td_rlua](https://github.com/tickbh/td_rlua) [[td_rlua](https://crates.io/crates/td_rlua)] — 零成本高层lua 5.3包装生锈[![build badge](https://api.travis-ci.org/tickbh/td_rlua.svg?branch=master)](https://travis-ci.org/tickbh/td_rlua)
  * [tomaka/hlua](https://github.com/tomaka/hlua) — 铁锈与Lua库接口[![build badge](https://api.travis-ci.org/tomaka/hlua.svg?branch=master)](https://travis-ci.org/tomaka/hlua)
* mruby
  * [anima-engine/mrusty](https://github.com/anima-engine/mrusty) — mruby安全绑定生锈[![build badge](https://api.travis-ci.org/anima-engine/mrusty.svg?branch=master)](https://travis-ci.org/anima-engine/mrusty)
* Node.js
  * [infinyon/node-bindgen](https://github.com/infinyon/node-bindgen) - 使用Rust生成nodejs模块的简单方法
  * [neon-bindings/neon](https://github.com/neon-bindings/neon) — 锈绑定编写安全、快速本地节点。js模块[![build badge](https://api.travis-ci.org/neon-bindings/neon.svg?branch=master)](https://travis-ci.org/neon-bindings/neon)
* Objective-C
  * [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) — objective - c运行时绑定和包装生锈
* Python
  * [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) — Python绑定[![build badge](https://api.travis-ci.org/dgrunwald/rust-cpython.svg?branch=master)](https://travis-ci.org/dgrunwald/rust-cpython)
  * [getsentry/milksnake](https://github.com/getsentry/milksnake) — 扩展python setuptools,允许您分配动态链接库在python中车轮在最便携的方式。
  * [PyO3/PyO3](https://github.com/PyO3/PyO3) — Python解释器锈绑定[![build badge](https://api.travis-ci.org/PyO3/pyo3.svg?branch=master)](https://travis-ci.org/PyO3/pyo3)
  * [RustPython](https://github.com/RustPython/RustPython) — 编写的Python解释器中生锈[![Build Status](https://github.com/RustPython/RustPython/workflows/CI/badge.svg)](https://github.com/RustPython/RustPython/actions?query=workflow%3ACI)
* Ruby
  * [d-unseductable/ruru](https://github.com/d-unseductable/ruru) — 本地Ruby编写的扩展生锈[![build badge](https://api.travis-ci.org/d-unseductable/ruru.svg?branch=master)](https://travis-ci.org/d-unseductable/ruru)
  * [danielpclark/rutie](https://github.com/danielpclark/rutie) — 本地Ruby编写的扩展生锈,反之亦然[![Build Status](https://api.travis-ci.org/danielpclark/rutie.svg?branch=master)](https://travis-ci.org/danielpclark/rutie)
  * [tildeio/helix](https://github.com/tildeio/helix) — 编写Ruby类在生锈[![build badge](https://api.travis-ci.org/tildeio/helix.svg?branch=master)](https://travis-ci.org/tildeio/helix)
* Web Assembly
  * [rhysd/wain](https://github.com/rhysd/wain) - wain: 在安全的Rust中从头开始的WebAssembly INterpreter，零依赖性 [![build badge](https://github.com/rhysd/wain/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/rhysd/wain/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush)
  * [rustwasm/wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) — 一个项目促进高层wasm模块之间的交互和JS。[![build badge](https://api.travis-ci.com/rustwasm/wasm-bindgen.svg?branch=master)](https://travis-ci.org/rustwasm/wasm-bindgen)
  * [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack) — :包::闪光:打包wasm和发布npm ![![build badge](https://api.travis-ci.com/rustwasm/wasm-pack.svg?branch=master)](https://travis-ci.org/rustwasm/wasm-pack)

### 格式器 Formatters
> 格式器

* [dprint](https://github.com/dprint/dprint) - 一个可插拔和可配置的代码格式化平台[![build badge](https://github.com/dprint/dprint/workflows/CI/badge.svg)](https://github.com/dprint/dprint/actions?query=workflow%3ACI)
* [Prettier Rust](https://github.com/jinxdash/prettier-plugin-rust) - 一个有主见的Rust代码格式化器，可以自动修正不良语法（[Prettier](https://prettier.io/)社区插件）
* [rustfmt](https://github.com/rust-lang/rustfmt) - 由Rust团队维护的Rust代码格式化器，包含在货物中 [![build badge](https://api.travis-ci.com/rust-lang/rustfmt.svg?branch=master)](https://app.travis-ci.com/github/rust-lang/rustfmt)

### 编译器 IDEs
> 编译器

另见 [Are we (I)DE yet?](https://areweideyet.com/) 和 [Rust Tools](https://www.rust-lang.org/tools).

* [Atom](https://atom.io/)
  * [rust-lang/atom-ide-rust](https://github.com/rust-lang/atom-ide-rust) — 生锈的IDE支持原子,由铁锈语言服务器(RLS)[![Build Status](https://api.travis-ci.com/rust-lang/atom-ide-rust.svg?branch=master)](https://app.travis-ci.com/grust-lang/atom-ide-rust)
  * [Eclipse](https://www.eclipse.org/)
    * [Eclipse Corrosion](https://github.com/eclipse/corrosion)
  * [Emacs](https://www.gnu.org/software/emacs/)
    * [emacs-racer](https://github.com/racer-rust/emacs-racer) — 自动完成(见也[company](https://company-mode.github.io) and [auto-complete](https://github.com/auto-complete/auto-complete))
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust) — 生锈的支持[Flycheck](https://github.com/flycheck/flycheck)
    * [rust-mode](https://github.com/rust-lang/rust-mode) — 生锈的主要模式
    * [rustic](https://github.com/brotzeit/rustic) - Emacs的Rust开发环境 [![build badge](https://github.com/brotzeit/rustic/workflows/CI/badge.svg)](https://github.com/brotzeit/rustic/actions?query=workflow%3ACI)
  * [gitpod.io](https://gitpod.io) — 在线与完整的铁锈支持基于锈语言IDE服务器
  * [gnome-builder](https://wiki.gnome.org/Apps/Builder) 自3.22.2版起，对rust和cargo的本地支持
  * [IntelliJ](https://www.jetbrains.com/idea/)
    * [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust) — [![build badge](https://api.travis-ci.org/intellij-rust/intellij-rust.svg?branch=master)](https://travis-ci.org/intellij-rust/intellij-rust)
  * [Kakoune](http://kakoune.org/)
    * [kak-lsp/kak-lsp](https://github.com/kak-lsp/kak-lsp/) — [LSP](https://microsoft.github.io/language-server-protocol/) 客户端。用Rust实现，支持开箱即用的rls.
  * [Ride](https://github.com/madeso/ride) — [![build badge](https://api.travis-ci.org/madeso/ride.svg?branch=master)](https://travis-ci.org/madeso/ride)
  * [Sublime Text](https://www.sublimetext.com/)
    * [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced) — 官方锈包
  * [Vim](https://vim.sourceforge.io/) — 无处不在的文本编辑器
    * [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim) — [LSP](https://microsoft.github.io/language-server-protocol/) 客户端。用Rust实现，支持开箱即用的rls.
    * [crates.nvim](https://github.com/Saecki/crates.nvim) - 帮助管理crates.io依赖性的插件.
    * [rust.vim](https://github.com/rust-lang/rust.vim) — 提供文件检测,语法高亮显示、格式化、Syntastic集成等等。
    * [vim-racer](https://github.com/racer-rust/vim-racer) — 允许vim使用[Racer](https://github.com/racer-rust/racer)  完成 Rust 代码并导航。
  * Visual Studio
    * [dgriffen/rls-vs2017](https://github.com/ZoeyR/rls-vs2017) — 锈支持Visual Studio 2017预览[![build badge](https://ci.appveyor.com/api/projects/status/d2lxlincwninhsng?svg=true)](https://ci.appveyor.com/project/dgriffen/rls-vs2017)
    * [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust) — 生锈的Visual Studio扩展[![Build status](https://ci.appveyor.com/api/projects/status/5nw5no10jj0y4p3f?svg=true)](https://ci.appveyor.com/project/vosen/visualrust)
  * [Visual Studio Code](https://code.visualstudio.com/)
    * [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml) - 在vscode中支持TOML
    * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — LLDB扩展
    * [crates](https://github.com/serayuzgur/crates) — 箱是板条箱的一个扩展。io依赖性。[![build badge](https://img.shields.io/vscode-marketplace/v/serayuzgur.crates.svg)](https://github.com/serayuzgur/crates) [![build badge](https://api.travis-ci.org/serayuzgur/crates.svg?branch=master)](https://travis-ci.org/serayuzgur/crates)
    * [Prettier - Code formatter (Rust)](https://marketplace.visualstudio.com/items?itemName=jinxdash.prettier-rust) — 固执己见的铁锈代码格式化程序autofixes糟糕的语法([Prettier](https://prettier.io/) community plugin)
    * [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) — 另一个生锈的语言RLS服务器
    * [rust-lang/rls-vscode](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust) — 锈支持Visual Studio代码(同时支持RLS和rust-analyzer)

### 分析 Profiling
> 分析

* [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs) — Statistics-driven基准库生锈[![Build Status](https://api.travis-ci.org/bheisler/criterion.rs.svg?branch=master)](https://travis-ci.org/bheisler/criterion.rs)
* [Bytehound](https://github.com/koute/bytehound) — Linux内存分析器
* [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch) — 秒表图书馆[![build badge](https://api.travis-ci.org/ellisonch/rust-stopwatch.svg?branch=master)](https://travis-ci.org/ellisonch/rust-stopwatch)
* FlameGraphs
  * [llogiq/flame](https://github.com/llogiq/flame) — [![build badge](https://api.travis-ci.org/llogiq/flame.svg?branch=master)](https://travis-ci.org/llogiq/flame)
  * [mrhooray/torch](https://github.com/mrhooray/torch) — 生成基于矮FlameGraphs调试信息
* [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) — 一个命令行基准测试工具[![Version info](https://img.shields.io/crates/v/hyperfine.svg)](https://crates.io/crates/hyperfine) [![Build Status](https://api.travis-ci.org/sharkdp/hyperfine.svg?branch=master)](https://travis-ci.org/sharkdp/hyperfine)

### 服务 Services
> 服务

* [deps.rs](https://github.com/deps-rs/deps.rs) - 检测过期或不安全的依赖关系
* [docs.rs](https://docs.rs) - 自动生成箱体的文档

### 静态分析 Static analysis
> 静态分析

[[assert](https://crates.io/keywords/assert), [static](https://crates.io/keywords/static)]

* [facebookexperimental/MIRAI](https://github.com/facebookexperimental/mirai) — 抽象解释器操作在生锈的中层中间表示(MIR)[![Continuous Integration](https://github.com/facebookexperimental/MIRAI/actions/workflows/rust.yml/badge.svg)](https://github.com/facebookexperimental/MIRAI/actions/workflows/rust.yml)
* [static_assertions](https://crates.io/crates/static_assertions) — 编译时断言,以确保不变量[![Build Status](https://api.travis-ci.org/nvzqz/static-assertions-rs.svg?branch=master)](https://travis-ci.org/nvzqz/static-assertions-rs/)

### 测试 Testing
> 测试

[[test](https://crates.io/keywords/test), [testing](https://crates.io/keywords/testing)]

* 代码覆盖率
  * [tarpaulin](https://crates.io/crates/cargo-tarpaulin) — 一个代码覆盖率工具用于生锈[![build badge](https://api.travis-ci.org/repositories/xd009642/tarpaulin.svg?branch=master)](https://travis-ci.org/xd009642/tarpaulin)
* 持续集成
  * [trust](https://github.com/japaric/trust) — 特拉维斯CI和AppVeyor模板来测试您的铁锈箱架构和5日发布二进制版本的Linux, macOS和窗户
* 框架和运行器
  * [AlKass/polish](https://github.com/AlKass/polish) — 迷你测试/测试驱动的框架[![Build Status](https://api.travis-ci.org/AlKass/polish.svg?branch=master)](https://travis-ci.org/AlKass/polish) [![Crates Package Status](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
  * [cargo-dinghy](https://crates.io/crates/cargo-dinghy/) - 用于简化在智能手机和其他小型处理器设备上运行库测试和工作台的货物扩展.
  * [cucumber](https://crates.io/crates/cucumber) [![Latest Version](https://img.shields.io/crates/v/cucumber.svg)](https://crates.io/crates/cucumber) — 一个实现黄瓜测试框架的生锈。完全本地,没有外部测试或依赖性。[![Build Status](https://github.com/cucumber-rs/cucumber/workflows/CI/badge.svg?branch=master)](https://github.com/cucumber-rs/cucumber)
  * [demonstrate](https://crates.io/crates/demonstrate) — 声明性测试框架[![Build Status](https://github.com/aubaugh/demonstrate/workflows/Continuous%20Integration/badge.svg?branch=master)](https://github.com/aubaugh/demonstrate)
  * [rstest](https://crates.io/crates/rstest) — Fixture-based生锈的测试框架[![Build Status](https://github.com/la10736/rstest/workflows/Test/badge.svg?branch=master)](https://github.com/la10736/rstest/actions)
  * [speculate](https://crates.io/crates/speculate) — 生锈的RSpec启发最少的测试框架
* 模拟和测试数据
  * [asomers/mockall](https://github.com/asomers/mockall) [[mockall](https://crates.io/crates/mockall)] — 一个强大的模拟对象库生锈。[![Cirrus Build Status](https://api.cirrus-ci.com/github/asomers/mockall.svg)](https://cirrus-ci.com/github/asomers/mockall)
  * [fake-rs](https://github.com/cksac/fake-rs) —  库生成假数据[![build badge](https://api.travis-ci.org/repositories/cksac/fake-rs.svg?branch=master)](https://travis-ci.org/cksac/fake-rs)
  * [goldenfile](https://github.com/calder/rust-goldenfile) [[goldenfile](https://crates.io/crates/goldenfile)] - 一个为Goldenfile测试提供简单API的库. [![build badge](https://api.travis-ci.org/calder/rust-goldenfile.svg?branch=master)](https://travis-ci.org/calder/rust-goldenfile)
  * [httpmock](https://github.com/alexliesenfeld/httpmock) — HTTP嘲笑[![build badge](https://dev.azure.com/alexliesenfeld/httpmock/_apis/build/status/alexliesenfeld.httpmock?branchName=master)](https://dev.azure.com/alexliesenfeld/httpmock/_build/latest?definitionId=2&branchName=master)
  * [mockiato](https://crates.io/crates/mockiato) — 严格,但友好嘲笑图书馆2018生锈[![build badge](https://api.travis-ci.com/mockiato/mockiato.svg?branch=master)](https://app.travis-ci.com/github/mockiato/mockiato)
  * [mockito](https://crates.io/crates/mockito) — HTTP嘲笑[![build badge](https://api.travis-ci.org/lipanski/mockito.svg?branch=master)](https://travis-ci.org/lipanski/mockito)
  * [nrxus/faux](https://github.com/nrxus/faux/) [![Latest Version](https://img.shields.io/crates/v/faux.svg)](https://crates.io/crates/faux) — 库来创建模拟结构。！[build](https://github.com/nrxus/faux/workflows/test/badge.svg?branch=master)
* 基因突变检测
  * [cargo-mutants](https://github.com/sourcefrog/cargo-mutants) [[cargo-mutants](https://crates.io/crates/cargo-mutants)] - 通过注入突变来发现测试不充分的代码，不需要修改源代码. [![build badge](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml/badge.svg?branch=main&event=push)](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml?query=branch%3Amain)
  * [mutagen](https://github.com/llogiq/mutagen) [[mutagen](https://crates.io/crates/mutagen)] — 源代码级变异测试框架(夜间)[![build badge](https://api.travis-ci.org/llogiq/mutagen.svg?branch=master)](https://travis-ci.org/llogiq/mutagen)
* 性能测试和模糊
  * [proptest](https://crates.io/crates/proptest) — 财产受的启发而创建的测试框架[Hypothesis](https://hypothesis.works/) Python的框架 [![build badge](https://api.travis-ci.org/altsysrq/proptest.svg?branch=master)](https://travis-ci.org/altsysrq/proptest)
  * [quickcheck](https://crates.io/crates/quickcheck) — 一个生锈的实现[QuickCheck](https://wiki.haskell.org/Introduction_to_QuickCheck1) [![build badge](https://api.travis-ci.org/BurntSushi/quickcheck.svg?branch=master)](https://travis-ci.org/BurntSushi/quickcheck)
  * [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs) — fuzzer生锈,使用[AFL](https://lcamtuf.coredump.cx/afl/) [![build badge](https://api.travis-ci.org/rust-fuzz/afl.rs.svg?branch=master)](https://travis-ci.org/rust-fuzz/afl.rs)

### 转化 Transpiling
> 转化

* [BayesWitnesses/m2cgen](https://github.com/BayesWitnesses/m2cgen) - 一个CLI工具，可以将训练好的经典机器学习模型转译成零依赖的本地Rust代码。[![GitHub Actions Status](https://github.com/BayesWitnesses/m2cgen/workflows/GitHub%20Actions/badge.svg?branch=master)](https://github.com/BayesWitnesses/m2cgen/actions)
* [immunant/c2rust](https://github.com/immunant/c2rust) - 在Clang/LLVM之上构建的C到Rust翻译器和交叉检查器。[![Build Status](https://api.travis-ci.org/immunant/c2rust.svg?branch=master)](https://travis-ci.org/immunant/c2rust)
* [jameysharp/corrode](https://github.com/jameysharp/corrode) - 一个用Haskell编写的C到Rust翻译器。

## 库 Libraries
> 库

* [perf-monitor-rs](https://github.com/larksuite/perf-monitor-rs) — 一个工具包，旨在成为应用程序监测其性能的基础. [![crates.io](https://img.shields.io/crates/v/perf_monitor.svg)](https://crates.io/crates/perf_monitor)
* [Phate6660/nixinfo](https://github.com/Phate6660/nixinfo) [[crate](https://crates.io/crates/nixinfo)] — 一个收集系统信息的lib crate，如cpu、发行版、环境、内核等.

### 人工智能 Artificial Intelligence
> 人工智能

#### Genetic algorithms

* [innoave/genevo](https://github.com/innoave/genevo) — 执行遗传算法(GA)模拟可定制和可扩展的方式。
* [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic) — 遗传算法图书馆生锈。在维护模式。
* [Martin1887/oxigen](https://github.com/Martin1887/oxigen) — 快速、并行、可扩展的和自适应的遗传算法的库。一个例子使用这个库解决N = 255 N皇后问题的只有几秒钟,使用小于1 MB的RAM。
* [pkalivas/radiate](https://github.com/pkalivas/radiate) — 一个可定制的并行遗传编程引擎能够发展的解决方案,监督、非监督,强化学习问题。有完整的整洁Evtree和可定制的实现。[![Build Status](https://api.travis-ci.com/pkalivas/radiate.svg?branch=master)](https://app.travis-ci.com/github/pkalivas/radiate)![Crates.io](https://img.shields.io/crates/v/radiate)
* [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs) — 进化算法与生锈[![Build Status](https://api.travis-ci.org/willi-kappler/darwin-rs.svg?branch=master)](https://travis-ci.org/willi-kappler/darwin-rs)

#### 机器学习 Machine learning
> 机器学习
>
见 [[Machine learning](https://crates.io/keywords/machine-learning)]

另见 [About Rust’s Machine Learning Community](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f) 和 [Are we learning yet?](https://www.arewelearningyet.com).

* [autumnai/leaf](https://github.com/autumnai/leaf) — 打开机器智能的框架。[![Build Status](https://api.travis-ci.org/autumnai/leaf.svg?branch=master)](https://travis-ci.org/autumnai/leaf). 被放弃的项目。最新的分叉是 [spearow/juice]( https://github.com/spearow/juice).
* [huggingface/tokenizers](https://github.com/huggingface/tokenizers) - hug Face为现代NLP管道编写的标记器，使用Rust(原始实现)与Python绑定. [![Build Status](https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg?branch=master)](https://github.com/huggingface/tokenizers/actions)
* [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) — 锈PyTorch语言绑定。[![Build Status](https://api.travis-ci.org/LaurentMazare/tch-rs.svg?branch=master)](https://travis-ci.org/LaurentMazare/tch-rs)
* [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) — 机器学习的板条箱生锈。[![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://app.circleci.com/pipelines/github/maciejkula/rustlearn)
* [rust-ml/linfa](https://github.com/rust-ml/linfa) — 机器学习框架。
* [smartcorelib/smartcore](https://github.com/smartcorelib/smartcore) — 机器学习图书馆生锈[![Build Status](https://img.shields.io/circleci/build/github/smartcorelib/smartcore)](https://smartcorelib.org/)
* [tensorflow/rust](https://github.com/tensorflow/rust) — 锈TensorFlow语言绑定。[![Build Status](https://api.travis-ci.org/tensorflow/rust.svg?branch=master)](https://travis-ci.org/tensorflow/rust)

### 天文学 Astronomy
> 天文学

[[天文学](https://crates.io/keywords/astronomy)]

* [fitsio](https://crates.io/crates/fitsio) - 包裹cfitsio的fit接口库 [![build badge](https://api.travis-ci.org/mindriot101/rust-fitsio.svg?branch=master)](https://travis-ci.org/mindriot101/rust-fitsio)
* [flosse/rust-sun](https://github.com/flosse/rust-sun) [[sun](https://crates.io/crates/sun)] - JS库suncalc的锈蚀移植 [![build badge](https://api.travis-ci.org/flosse/rust-sun.svg?branch=master)](https://travis-ci.org/flosse/rust-sun)
* [saurvs/astro-rust](https://github.com/saurvs/astro-rust) - Rust的天文学 [![build badge](https://api.travis-ci.org/saurvs/astro-rust.svg?branch=master)](https://travis-ci.org/saurvs/astro-rust)

### 异步 Asynchronous
> 异步

* [async-std](https://async.rs/) [[async-std]](https://crates.io/crates/async-std) - Rust标准库的异步版本 [![CI](https://github.com/async-rs/async-std/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/async-rs/async-std/actions/workflows/ci.yml)
* [dpc/mioco](https://github.com/dpc/mioco) — 可伸缩、coroutine-based异步IO处理库[![build badge](https://api.travis-ci.org/dpc/mioco.svg?branch=master)](https://travis-ci.org/dpc/mioco)
* [mio](https://github.com/tokio-rs/mio) — 绪是一个轻量级的IO库生锈的关注增加操作系统抽象尽可能少的开销[![build badge](https://api.travis-ci.org/tokio-rs/mio.svg?branch=master)](https://travis-ci.org/tokio-rs/mio)
* [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs) — 零成本期货生锈[![build badge](https://api.travis-ci.com/rust-lang/futures-rs.svg?branch=master)](https://travis-ci.org/rust-lang/futures-rs)
* [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust) — 单轴/ MonadIO,处理程序,协同程序/ doNotation,函数式编程特性生锈[![build badge](https://api.travis-ci.org/TeaEntityLab/fpRust.svg?branch=master)](https://travis-ci.org/TeaEntityLab/fpRust)
* [Xudong-Huang/may](https://github.com/Xudong-Huang/may) — 锈stackful协同程序库[![build badge](https://api.travis-ci.org/Xudong-Huang/may.svg?branch=master)](https://travis-ci.org/Xudong-Huang/may)
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) — 一个协同程序I / O库working-stealing调度器[![build badge](https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master)](https://travis-ci.org/zonyitoo/coio-rs)

### 音频和音乐 Audio and Music
> 音频和音乐

[[audio](https://crates.io/keywords/audio)]

* [hound](https://crates.io/crates/hound) — 一个WAV编码和解码库[![build badge](https://api.travis-ci.org/ruuda/hound.svg?branch=master)](https://travis-ci.org/ruuda/hound)
* [insomnimus/nodi](https://github.com/insomnimus/nodi) [[nodi](https://crates.io/crates/nodi)] — 一个图书馆MIDI文件的播放和抽象。[![build badge](https://github.com/insomnimus/nodi/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/nodi/actions)
* [jhasse/ears](https://github.com/jhasse/ears) — 一个简单的库来播放声音和音乐,在OpenAL libsndfile[![build badge](https://api.travis-ci.org/jhasse/ears.svg?branch=master)](https://travis-ci.org/jhasse/ears)
* [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs) — [PortMidi](https://portmedia.sourceforge.net/portmidi/) 绑定 [![build badge](https://api.travis-ci.org/musitdev/portmidi-rs.svg?branch=master)](https://travis-ci.org/musitdev/portmidi-rs)
* [ozankasikci/rust-music-theory](https://github.com/ozankasikci/rust-music-theory) — 一个生锈的音乐理论库[![Build Status](https://api.travis-ci.com/ozankasikci/rust-music-theory.svg?branch=master)](https://travis-ci.org/ozankasikci/rust-music-theory)
* [pdeljanov/Symphonia](https://github.com/pdeljanov/Symphonia) — 纯锈支持AAC音频解码和媒体多路分配器库,FLAC, MP3, MP4, OGG Vorbis, WAV。
* [RustAudio](https://github.com/RustAudio)
  * [RustAudio/cpal](https://github.com/RustAudio/cpal) - 纯Rust的低级别跨平台音频I/O库. [![Actions Status](https://github.com/RustAudio/cpal/workflows/cpal/badge.svg?branch=master)](https://github.com/RustAudio/cpal/actions)
  * [RustAudio/rodio](https://github.com/RustAudio/rodio) — 一个生锈音频播放库[![Build Status](https://api.travis-ci.org/RustAudio/rodio.svg?branch=master)](https://travis-ci.org/RustAudio/rodio)
  * [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) — PortAudio绑定[![build badge](https://api.travis-ci.org/RustAudio/rust-portaudio.svg?branch=master)](https://travis-ci.org/RustAudio/rust-portaudio)
* [Serial-ATA/lofty-rs](https://github.com/Serial-ATA/lofty-rs) [[lofty](https://crates.io/crates/lofty)] — 一个图书馆阅读和编辑各种音频格式的元数据[![build badge](https://github.com/Serial-ATA/lofty-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Serial-ATA/lofty-rs/actions)

### 身份验证 Authentication
> 身份验证

* [constantoine/totp-rs](https://github.com/constantoine/totp-rs) [[totp-rs](https://crates.io/crates/totp-rs)] — 2 fa库来生成和验证TOTP-based令牌![Build Status](https://github.com/constantoine/totp-rs/workflows/Rust/badge.svg)
* [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) — [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) lib in rust  [![Build Status](https://api.travis-ci.org/Keats/jsonwebtoken.svg?branch=master)](https://travis-ci.org/Keats/jsonwebtoken)
* [oauth2](https://github.com/ramosbugs/oauth2-rs) — 可扩展的,强类型的铁锈OAuth2客户端库[![Build Status](https://api.travis-ci.org/ramosbugs/oauth2-rs.svg?branch=main)](https://travis-ci.org/ramosbugs/oauth2-rs)
* [oxide-auth](https://github.com/HeroicKatora/oxide-auth) — OAuth2服务器库,用于结合actix或其他前端,具有一组可配置的和可扩展的后端[![Build Status](https://api.cirrus-ci.com/github/HeroicKatora/oxide-auth.svg?branch=master)](https://cirrus-ci.com/github/HeroicKatora/oxide-auth)
* [sgrust01/jwtvault](https://github.com/sgrust01/jwtvault) — 异步图书馆管理和协调JWT工作流[![Build Status](https://api.travis-ci.org/sgrust01/jwtvault.svg?branch=master)](https://travis-ci.org/sgrust01/jwtvault)
* [yup-oauth2](https://github.com/dermesser/yup-oauth2) — oauth2客户端实现提供设备,安装和服务帐户流动[![Build Status](https://api.travis-ci.org/dermesser/yup-oauth2.svg?branch=master)](https://travis-ci.org/dermesser/yup-oauth2)

### 汽车 Automotive
> 汽车

* [marcelbuesing/can-dbc](https://github.com/marcelbuesing/can-dbc) [[can-dbc](https://crates.io/crates/can-dbc)] — DBC格式的解析器[![build badge](https://api.travis-ci.org/marcelbuesing/can-dbc.svg?branch=dev)](https://travis-ci.org/marcelbuesing/can-dbc)
* [marcelbuesing/tokio-socketcan-bcm](https://github.com/marcelbuesing/tokio-socketcan-bcm) [[tokio-socketcan-bcm](https://crates.io/crates/tokio-socketcan-bcm)] — Linux SocketCAN BCM支持东京[![build badge](https://api.travis-ci.org/marcelbuesing/tokio-socketcan-bcm.svg?branch=master)](https://travis-ci.org/marcelbuesing/tokio-socketcan-bcm)
* [mbr/socketcan](https://github.com/socketcan-rs/socketcan-rs) [[socketcan](https://crates.io/crates/socketcan)] — Linux SocketCAN图书馆
* [oefd/tokio-socketcan](https://github.com/oefd/tokio-socketcan) [[tokio-socketcan]](https://crates.io/crates/tokio-socketcan)] — Linux SocketCAN支持东京基于SocketCAN箱
* [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs) [[lin-bus](https://crates.io/crates/lin-bus)] — 林司机特征和协议的实现[![build badge](https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg)](https://app.circleci.com/pipelines/github/Sensirion/lin-bus-rs)

### 生物信息学 Bioinformatics
> 生物信息学

* [Rust-Bio](https://github.com/rust-bio) — 生物信息学图书馆生锈。

### 缓存 Caching
> 缓存

* [aisk/rust-memcache](https://github.com/aisk/rust-memcache) — Memcached客户端库[![build badge](https://api.travis-ci.org/aisk/rust-memcache.svg?branch=master)](https://travis-ci.org/aisk/rust-memcache)
* [al8n/stretto](https://github.com/al8n/stretto) - 一个高性能的线程安全的内存绑定的Rust缓存 [![build badge](https://github.com/al8n/stretto/actions/workflows/ci.yml/badge.svg)](https://github.com/al8n/stretto/actions/workflows/ci.yml)
* [jaemk/cached](https://github.com/jaemk/cached) — 简单的函数缓存/记忆
* [mozilla/sccache](https://github.com/mozilla/sccache/) - 共享的编译缓存，非常适合Rust编译 [![build badge](https://api.travis-ci.org/mozilla/sccache.svg?branch=master)](https://travis-ci.org/mozilla/sccache)

### 云 Cloud
> 云

* AWS（亚马逊） [[aws](https://crates.io/keywords/aws)]
  * [awslabs/aws-lambda-rust-runtime](https://github.com/awslabs/aws-lambda-rust-runtime) [[lambda_runtime](https://crates.io/crates/lambda_runtime)] — AWSλ的铁锈运行时[![build badge](https://github.com/awslabs/aws-lambda-rust-runtime/workflows/Rust/badge.svg)](https://github.com/awslabs/aws-lambda-rust-runtime/actions)
  * [awslabs/aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust) - 用于Rust的新AWS SDK
  * [rusoto/rusoto](https://github.com/rusoto/rusoto) — [![build badge](https://api.travis-ci.org/rusoto/rusoto.svg?branch=master)](https://travis-ci.org/rusoto/rusoto)
* 负载平衡器
  * [Convey](https://github.com/bparli/convey) - 具有动态配置加载的第4层负载平衡器.
* 多重云
  * [Qovery/engine](https://github.com/Qovery/engine) - 抽象层库，只需几分钟就能在云供应商上轻松部署应用程序

### 命令行 Command-line
> 命令行

* 论据解析
  * [clap-rs](https://github.com/clap-rs/clap) [[clap](https://crates.io/crates/clap)] — 一个简单的使用,全功能的命令行参数解析器[![build badge](https://api.travis-ci.org/clap-rs/clap.svg?branch=master)](https://travis-ci.org/clap-rs/clap)
  * [cliparser](https://crates.io/crates/cliparser) — 简单的命令行解析器. [![build badge](https://github.com/sagiegurari/cliparser/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cliparser/actions)
  * [docopt/docopt.rs](https://github.com/docopt/docopt.rs) [[docopt](https://crates.io/crates/docopt)] — 一个生锈的实现[DocOpt](http://docopt.org) [![build badge](https://api.travis-ci.org/docopt/docopt.rs.svg?branch=master)](https://travis-ci.org/docopt/docopt.rs)
  * [google/argh](https://github.com/google/argh) [[argh](https://crates.io/crates/argh)] — 一个固执己见的Derive-based参数解析器优化代码大小[![build badge](https://github.com/google/argh/workflows/Argh/badge.svg?branch=master)](https://github.com/google/argh/actions)
  * [killercup/quicli](https://github.com/killercup/quicli) [[quicli](https://crates.io/crates/quicli)] — 快速构建酷CLI应用程序在生锈[![build badge](https://api.travis-ci.org/killercup/quicli.svg?branch=master)](https://travis-ci.org/killercup/quicli)
  * [ksk001100/seahorse](https://github.com/ksk001100/seahorse) [[seahorse](https://crates.io/crates/seahorse)] — 最小的CLI框架编写的生锈[![Build status](https://github.com/ksk001100/seahorse/workflows/CI/badge.svg?branch=master)](https://github.com/ksk001100/seahorse/actions)
  * [TeXitoi/structopt](https://github.com/TeXitoi/structopt) [[structopt](https://crates.io/crates/structopt)] — 解析命令行参数通过定义一个结构体[![build badge](https://api.travis-ci.org/TeXitoi/structopt.svg?branch=master)](https://travis-ci.org/TeXitoi/structopt)
* 数据可视化
  * [nukesor/comfy-table](https://github.com/nukesor/comfy-table) [[comfy-table](https://crates.io/crates/comfy-table)] — 美丽的动态表为您的cli工具。[![Build status](https://github.com/Nukesor/comfy-table/workflows/Tests/badge.svg?branch=master)](https://github.com/nukesor/comfy-table/actions)
  * [zhiburt/tabled](https://github.com/zhiburt/tabled) [[tabled](https://crates.io/crates/tabled)] — 一个易于使用的库非常打印生锈的表结构和枚举。[![Build Status](https://github.com/zhiburt/tabled/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/tabled/actions)
* 以人为本的设计
  * [rust-cli/human-panic](https://github.com/rust-cli/human-panic) [[human-panic](https://crates.io/crates/human-panic)] — 对人类恐慌的消息[![build badge](https://api.travis-ci.org/rust-cli/human-panic.svg?branch=master)](https://travis-ci.org/rust-cli/human-panic)
* 线条编辑器
  * [kkawakam/rustyline](https://github.com/kkawakam/rustyline) [[rustyline](https://crates.io/crates/rustyline)] — readline实现生锈[![build badge](https://api.travis-ci.org/kkawakam/rustyline.svg?branch=master)](https://travis-ci.org/kkawakam/rustyline)
  * [MovingtoMars/liner](https://github.com/MovingtoMars/liner) [[liner](https://crates.io/crates/liner)] — 图书馆提供readline-like功能[![build badge](https://api.travis-ci.org/MovingtoMars/liner.svg?branch=master)](https://travis-ci.org/MovingtoMars/liner)
  * [murarth/linefeed](https://github.com/murarth/linefeed) [[linefeed](https://crates.io/crates/linefeed)] — 可配置、可扩展的、交互式读者[![build badge](https://api.travis-ci.org/murarth/linefeed.svg?branch=master)](https://travis-ci.org/murarth/linefeed)
  * [srijs/rust-copperline](https://github.com/srijs/rust-copperline) [[copperline](https://crates.io/crates/copperline)] — pure-Rust命令行编辑库
* 其他
  * [mgrachev/update-informer](https://github.com/mgrachev/update-informer) [[update-informer](https://crates.io/crates/update-informer)] — CLI应用程序更新告密者。它在箱子检查新版本。io和GitHub[![build badge](https://github.com/mgrachev/update-informer/workflows/CI/badge.svg)](https://github.com/mgrachev/update-informer/actions)
* 管道
  * [hniksic/rust-subprocess](https://github.com/hniksic/rust-subprocess) [[subprocess](https://crates.io/crates/subprocess)] — 设施与外部管道[![build badge](https://api.travis-ci.org/hniksic/rust-subprocess.svg?branch=master)](https://travis-ci.org/hniksic/rust-subprocess)
  * [imp/pager-rs](https://gitlab.com/imp/pager-rs) [[pager](https://crates.io/crates/pager)] — 管您的输出通过一个外部寻呼机
  * [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs) [[duct](https://crates.io/crates/duct)] — 子流程的构建器管道和输入输出重定向[![build badge](https://api.travis-ci.org/oconnor663/duct.rs.svg?branch=master)](https://travis-ci.org/oconnor663/duct.rs)
  * [rust-cli/rexpect](https://github.com/rust-cli/rexpect) [[rexpect](https://crates.io/crates/rexpect)] — 自动化的交互式应用程序(如ssh、ftp密码等[![CI](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml/badge.svg)](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml)
  * [zhiburt/expectrl](https://github.com/zhiburt/expectrl) [[expectrl](https://crates.io/crates/expectrl)] — 一个图书馆的伪终端控制互动节目[![build badge](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml)
* 进度条
  * [a8m/pb](https://github.com/a8m/pb) [[pbr](https://crates.io/crates/pbr)] — 控制台进度条锈病
  * [console-rs/indicatif](https://github.com/console-rs/indicatif) [[indicatif](https://crates.io/crates/indicatif)] — 向用户显示进展
  * [etienne-napoleone/spinach](https://github.com/etienne-napoleone/spinach) [[spinach](https://crates.io/crates/spinach)] — 实际转子生锈。[![CI](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml/badge.svg)](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml)
  * [FGRibreau/spinners](https://github.com/FGRibreau/spinners) [[spinners](https://crates.io/crates/spinners)] — 60优雅终端纺纱
* 提示
  * [hashmismatch/terminal_cli.rs](https://github.com/hashmismatch/terminal_cli.rs) [[terminal_cli](https://crates.io/crates/terminal_cli)]  — 建立一个交互式命令提示符[![build badge](https://api.travis-ci.org/hashmismatch/terminal_cli.rs.svg?branch=master)](https://travis-ci.org/hashmismatch/terminal_cli.rs)
  * [starship/starship](https://starship.rs/) [[starship](https://crates.io/crates/starship)]  — 最小,速度极快,极可定制任何shell提示[![Build status](https://github.com/starship/starship/workflows/Main%20workflow/badge.svg?branch=master)](https://github.com/starship/starship/actions)
  * [ynqa/promkit](https://github.com/ynqa/promkit) [[promkit](https://crates.io/crates/promkit)]  — 一个工具箱构建交互式命令行工具[![Build status](https://github.com/ynqa/promkit/workflows/promkit/badge.svg?branch=master)](https://github.com/ynqa/promkit/actions)
* 风格
  * [LukasKalbertodt/bunt](https://github.com/LukasKalbertodt/bunt) [[bunt](https://crates.io/crates/bunt)] — 跨平台终端与宏的颜色和样式[![Build status](https://github.com/LukasKalbertodt/bunt/actions/workflows/ci.yml/badge.svg)](https://github.com/LukasKalbertodt/bunt/actions?query=workflow%3ACI+branch%3Amaster)
  * [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter) [[term-painter](https://crates.io/crates/term-painter)] — 跨平台终端输出样式[![build badge](https://api.travis-ci.org/LukasKalbertodt/term-painter.svg?branch=master)](https://travis-ci.org/LukasKalbertodt/term-painter)
  * [mackwic/colored](https://github.com/mackwic/colored) [[colored](https://crates.io/crates/colored)] — 着色终端那么简单,你已经知道如何去做!
  * [ogham/rust-ansi-term](https://github.com/ogham/rust-ansi-term) [[ansi_term](https://crates.io/crates/ansi_term)] — 在ANSI终端控制颜色和格式[![build badge](https://api.travis-ci.org/ogham/rust-ansi-term.svg?branch=master)](https://travis-ci.org/ogham/rust-ansi-term)
  * [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi) [[yansi](https://crates.io/crates/yansi)] — 死简单ANSI终端颜色绘画图书馆
* TUI
  * BearLibTerminal
    * [cfyzium/bearlibterminal](https://github.com/nabijaczleweli/BearLibTerminal.rs) [[bear-lib-terminal](https://crates.io/crates/bear-lib-terminal)] — [BearLibTerminal](https://github.com/tommyettinger/BearLibTerminal) 捆绑 [![build badge](https://api.travis-ci.org/nabijaczleweli/BearLibTerminal.rs.svg?branch=master)](https://travis-ci.org/nabijaczleweli/BearLibTerminal.rs)
  * [fdehau/tui-rs](https://github.com/fdehau/tui-rs) [[tui](https://crates.io/crates/tui)] — 途易库启发[blessed-contrib](https://github.com/yaronn/blessed-contrib) and [termui](https://github.com/gizak/termui) [![build badge](https://api.travis-ci.org/fdehau/tui-rs.svg?branch=master)](https://travis-ci.org/fdehau/tui-rs)
  * [gyscos/Cursive](https://github.com/gyscos/Cursive) [[cursive](https://crates.io/crates/cursive)] — 构建富途易应用程序[![build badge](https://api.travis-ci.org/gyscos/Cursive.svg?branch=master)](https://travis-ci.org/gyscos/Cursive)
  * [ivanceras/titik](https://github.com/ivanceras/titik) - 一个跨平台的TUI小部件库，目标是提供互动小部件 [![Build Status](https://api.travis-ci.com/ivanceras/titik.svg?branch=master)](https://app.travis-ci.com/github/ivanceras/titik)
  * ncurses
    * [ihalila/pancurses](https://github.com/ihalila/pancurses) [[pancurses](https://crates.io/crates/pancurses)] — 诅咒库,支持linux和windows[![build badge](https://api.travis-ci.org/ihalila/pancurses.svg?branch=master)](https://travis-ci.org/ihalila/pancurses)
    * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) [[ncurses](https://crates.io/crates/ncurses)] — [ncurses](https://www.gnu.org/software/ncurses/) 捆绑 [![build badge](https://api.travis-ci.org/jeaye/ncurses-rs.svg?branch=master)](https://travis-ci.org/jeaye/ncurses-rs)
  * [ogham/rust-term-grid](https://github.com/ogham/rust-term-grid) [[term_grid](https://crates.io/crates/term_grid)] — 在网格中生锈库放东西[![build badge](https://api.travis-ci.org/ogham/rust-term-grid.svg?branch=master)](https://travis-ci.org/ogham/rust-term-grid)
  * [redox-os/termion](https://github.com/redox-os/termion) [[termion](https://crates.io/crates/termion)] — bindless图书馆/遥控控制终端[![build badge](https://api.travis-ci.org/redox-os/termion.svg?branch=master)](https://travis-ci.org/redox-os/termion)
  * Termbox
    * [gchp/rustbox](https://github.com/gchp/rustbox) [[rustbox](https://crates.io/crates/rustbox)] — 绑定[Termbox](https://github.com/nsf/termbox) [![build badge](https://api.travis-ci.org/gchp/rustbox.svg?branch=master)](https://travis-ci.org/gchp/rustbox)
  * [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm) [[crossterm](https://crates.io/crates/crossterm)] — crossplatform终端库

### 压缩 Compression
> 压缩

* [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  * [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) — 在生锈,可以避免stdlib Brotli减压器
  * [ende76/brotli-rs](https://github.com/ende76/brotli-rs) — 实现Brotli压缩
* bzip2
  * [alexcrichton/bzip2-rs](https://github.com/alexcrichton/bzip2-rs) — [libbz2](https://www.sourceware.org/bzip2/) 捆绑 [![build badge](https://api.travis-ci.com/alexcrichton/bzip2-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/bzip2-rs)
* gzip
  * [zopfli](https://github.com/zopfli-rs/zopfli) [[zopfli](https://crates.io/crates/zopfli)] — Zopfli压缩算法的实现更高质量的缩小或zlib压缩
* gzp
  * [sstadick/gzp](https://github.com/sstadick/gzp/) - 多线程编码和解码deflate格式和snappy
* miniz
  * [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs) — [miniz](https://code.google.com/archive/p/miniz) 捆绑 [![build badge](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)
* snappy
  * [JeffBelgum/rust-snappy](https://github.com/JeffBelgum/rust-snappy) — [snappy](https://github.com/google/snappy) 捆绑 [![build badge](https://api.travis-ci.org/JeffBelgum/rust-snappy.svg?branch=master)](https://travis-ci.org/JeffBelgum/rust-snappy)
* tar
  * [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) — tar存档读/写在生锈[![build badge](https://api.travis-ci.com/alexcrichton/tar-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/tar-rs)
* zip
  * [zip-rs/zip](https://github.com/zip-rs/zip) — 读和写ZIP档案[![Build Status](https://api.travis-ci.org/mvdnes/zip-rs.svg?branch=master)](https://travis-ci.org/mvdnes/zip-rs)

### 计算 Computation
> 计算

* [argmin-rs/argmin](https://github.com/argmin-rs/argmin) [[argmin](https://crates.io/crates/argmin)] — 纯锈优化图书馆[![build badge](https://api.travis-ci.org/argmin-rs/argmin.svg?branch=master)](https://travis-ci.org/argmin-rs/argmin)
* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) [[blas](https://crates.io/keywords/blas)]
  * [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas) — 布拉斯特区绑定
* [calebwin/emu](https://github.com/calebwin/emu) — 一种语言对GPGPU从生锈的宏观数值计算
* [dimforge/nalgebra](https://github.com/dimforge/nalgebra) — 低维线性代数库[![build badge](https://api.travis-ci.org/dimforge/nalgebra.svg?branch=dev)](https://travis-ci.org/dimforge/nalgebra)
* [GSL](http://www.gnu.org/software/gsl/)
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez/rust-GSL) — GSL绑定[![build badge](https://api.travis-ci.org/GuillaumeGomez/rust-GSL.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-GSL)
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
  * [stainless-steel/lapack](https://github.com/blas-lapack-rs/lapack) — LAPACK绑定[![build badge](https://api.travis-ci.org/blas-lapack-rs/lapack.svg?branch=master)](https://travis-ci.org/blas-lapack-rs/lapack)
* Parallel
  * [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) — [Arrayfire](https://github.com/arrayfire) 捆绑
  * [autumnai/collenchyma](https://github.com/autumnai/collenchyma) — 一个可扩展的、可插入backend-agnostic框架平行,高性能计算在CUDA OpenCL,常见的主机CPU。[![build badge](https://api.travis-ci.org/autumnai/collenchyma.svg?branch=master)](https://travis-ci.org/autumnai/collenchyma)
  * [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl) — [OpenCL](https://www.khronos.org/opencl/) 绑定
* Scirust
  * [indigits/scirust](https://github.com/indigits/scirust) — 科学计算库在生锈[![Build Status](https://api.travis-ci.org/indigits/scirust.svg?branch=master)](https://travis-ci.org/indigits/scirust)
* Statrs
  * [statrs-dev/statrs](https://github.com/statrs-dev/statrs) — 健壮的统计计算图书馆生锈[![Build Status](https://api.travis-ci.org/boxtown/statrs.svg?branch=master)](https://travis-ci.org/boxtown/statrs)

### 并发性 Concurrency
> 并发性

* [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) – Rust支持并行性和低级并发性 [![build badge](https://api.travis-ci.org/crossbeam-rs/crossbeam.svg?branch=master)](https://travis-ci.org/crossbeam-rs/crossbeam)
* [orium/archery](https://github.com/orium/archery) [[archery](https://crates.io/crates/archery)] — 图书馆抽象从“钢筋混凝土”/“弧”指针类型。[![build badge](https://api.travis-ci.org/orium/archery.svg?branch=master)](https://travis-ci.org/orium/archery)
* [Rayon](https://github.com/rayon-rs/rayon) – Rust的数据并行化库 [![build badge](https://api.travis-ci.org/rayon-rs/rayon.svg?branch=master)](https://travis-ci.org/rayon-rs/rayon)
* [rustcc/coroutine-rs](https://github.com/rustcc/coroutine-rs) – Rust中的Coroutine库 [![build badge](https://api.travis-ci.org/rustcc/coroutine-rs.svg?branch=master)](https://travis-ci.org/rustcc/coroutine-rs)
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) – 用于Rust的Coroutine I/O [![build badge](https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master)](https://travis-ci.org/zonyitoo/coio-rs)

### 配置 Configuration
> 配置

* [andoriyu/uclicious](https://github.com/andoriyu/uclicious) [[uclicious](https://crates.io/crates/uclicious)] — [libUCL](https://github.com/vstakhov/libucl) 基于功能丰富的配置库. [![CircleCI](https://circleci.com/gh/vstakhov/libucl.svg?style=svg)](https://app.circleci.com/pipelines/github/vstakhov/libucl)
* [Kixunil/configure_me](https://github.com/Kixunil/configure_me) [[configure_me](https://crates.io/crates/configure_me)] — 图书馆很容易处理应用程序配置
* [mehcode/config-rs](https://github.com/mehcode/config-rs) [[config](https://crates.io/crates/config)] — 分层配置系统生锈应用(与大力支持12-factor应用程序)。[![build badge](https://api.travis-ci.org/mehcode/config-rs.svg?branch=master)](https://travis-ci.org/mehcode/config-rs)

### 密码学 Cryptography
> 密码学

[[crypto](https://crates.io/keywords/crypto), [cryptography](https://crates.io/keywords/cryptography)]

* [briansmith/ring](https://github.com/briansmith/ring) — 安全、快速、小加密使用防锈、BoringSSL的密码学原语。[![build badge](https://api.travis-ci.org/briansmith/ring.svg?branch=master)](https://travis-ci.org/briansmith/ring)
* [briansmith/webpki](https://github.com/briansmith/webpki) — Web PKI TLS证书验证生锈。[![build badge](https://api.travis-ci.org/briansmith/webpki.svg?branch=master)](https://travis-ci.org/briansmith/webpki)
* [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster) [[rooster](https://crates.io/crates/rooster)] — 简单的密码管理器在您的终端使用
* [cossacklabs/themis](https://github.com/cossacklabs/themis) [[themis](https://crates.io/crates/themis)] — 高级加密库解决典型数据安全任务,适合多平台的应用程序。[![build badge](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) — 加密算法在生锈[![build badge](https://api.travis-ci.org/DaGenix/rust-crypto.svg?branch=master)](https://travis-ci.org/DaGenix/rust-crypto)
* [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) — 纯锈Curve25519操作的实现
* [dalek-cryptography/ed25519-dalek](https://github.com/dalek-cryptography/ed25519-dalek) — 纯锈Ed25519数字签名的实现
* [dalek-cryptography/x25519-dalek](https://github.com/dalek-cryptography/x25519-dalek) — 纯锈X25519密钥交换的实现
* [debris/tiny-keccak](https://github.com/debris/tiny-keccak) — 纯锈Keccak家族的实现(SHA3)
* [exonum/exonum](https://github.com/exonum/exonum) [[exonum](https://crates.io/crates/exonum)] — 为区块链项目可扩展的框架[![build badge](https://api.travis-ci.com/exonum/exonum.svg?branch=master)](https://travis-ci.org/exonum/exonum)
* [gakonst/ark-circom](https://github.com/gakonst/ark-circom) - Arkworks与Circom的R1CS的绑定，用于Rust中的Groth16证明和见证生成.
* [klutzy/suruga](https://github.com/klutzy/suruga) — 一个生锈的实现[TLS 1.2](https://datatracker.ietf.org/doc/html/rfc5246)
* [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) — 绑定的安全框架(OSX本地)
* [libOctavo/octavo](https://github.com/libOctavo/octavo) — 模块化的哈希和加密库在生锈[![build badge](https://api.travis-ci.org/libOctavo/octavo.svg?branch=master)](https://travis-ci.org/libOctavo/octavo)
* [novifinancial/opaque-ke](https://github.com/novifinancial/opaque-ke) — 纯rust最实现的[OPAQUE](https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/) 密码认证的密钥交换. [![build badge](https://github.com/novifinancial/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/novifinancial/opaque-ke)
* [orion-rs/orion](https://github.com/orion-rs/orion) — 这个库旨在提供简单和可用的加密。“可用性”意义暴露高层API易于使用和滥用。[![Tests](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)
* [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers) [[djangohashers](https://crates.io/crates/djangohashers)] — 锈端口密码原语中使用Django项目。它不需要Django,只有散列和验证密码根据其风格。[![build badge](https://api.travis-ci.org/Racum/rust-djangohashers.svg?branch=master)](https://travis-ci.org/Racum/rust-djangohashers)
* [RustCrypto/hashes](https://github.com/RustCrypto/hashes) — 加密哈希函数的集合用纯生锈[![build badge](https://api.travis-ci.org/RustCrypto/hashes.svg?branch=master)](https://travis-ci.org/RustCrypto/hashes)
* [rustls/rustls](https://github.com/rustls/rustls) — 一个生锈TLS的实现
* [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls) — 绑定本地TLS的库
* [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) — [OpenSSL](https://www.openssl.org/) 绑定 [![build badge](https://api.travis-ci.org/sfackler/rust-openssl.svg?branch=master)](https://travis-ci.org/sfackler/rust-openssl)
* [sodiumoxide/sodiumoxide](https://github.com/sodiumoxide/sodiumoxide) — [libsodium](https://github.com/jedisct1/libsodium) 绑定 [![build badge](https://api.travis-ci.org/sodiumoxide/sodiumoxide.svg?branch=master)](https://travis-ci.org/sodiumoxide/sodiumoxide)
* [vityafx/randomorg](https://github.com/vityafx/randomorg) - 一个Random.org客户端库. [![Crates badge](https://img.shields.io/crates/v/randomorg.svg)](https://crates.io/crates/randomorg)
* [w3f/schnorrkel](https://github.com/w3f/schnorrkel) - 施诺尔VRFs和瑞斯特瑞特集团的签名

### 数据处理 Data processing
> 数据处理

* [amv-dev/yata](https://github.com/amv-dev/yata) — 优质技术分析图书馆[![Build Status](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)
* [bluss/ndarray](https://github.com/rust-ndarray/ndarray) — n维数组和数组视图、多维切片和高效的操作
* [kernelmachine/utah](https://github.com/kernelmachine/utah) — 在铁锈Dataframe结构和业务
* [pola-rs/polars](https://github.com/pola-rs/polars) - 快速功能完整的DataFrame库 ![Build and test](https://github.com/pola-rs/polars/workflows/Build%20and%20test/badge.svg?branch=master)
* [weld-project/weld](https://github.com/weld-project/weld) — 高性能数据分析应用程序的运行时

### 数据流 Data streaming
> 数据流

* [infinyon/fluvio](https://github.com/infinyon/fluvio) - 可编程数据流平台 [![CI](https://github.com/infinyon/fluvio/workflows/CI/badge.svg?branch=stable)](https://github.com/infinyon/fluvio/actions)

### 数据结构 Data structures
> 数据结构

* [becheran/grid](https://github.com/becheran/grid) [[grid](https://crates.io/crates/grid)] —  提供一个二维数据结构易于使用和快速的生锈。[![build status](https://github.com/becheran/grid/actions/workflows/rust.yml/badge.svg)](https://github.com/becheran/grid/actions)
* [billyevans/tst](https://github.com/billyevans/tst) [[tst](https://crates.io/crates/tst)] — 三元搜索树的集合[![build badge](https://api.travis-ci.org/billyevans/tst.svg?branch=master)](https://travis-ci.org/billyevans/tst)
* [contain-rs](https://github.com/contain-rs) — 延长生锈的std::集合
* [danielpclark/array_tool](https://github.com/danielpclark/array_tool) — 数组的助手生锈。您将使用一些最常见的方法在阵列可用向量。多态的实现来处理你的用例。[![build badge](https://api.travis-ci.org/danielpclark/array_tool.svg?branch=master)](https://travis-ci.org/danielpclark/array_tool)
* [fizyk20/generic-array](https://github.com/fizyk20/generic-array) – 一个黑客，允许用类型化的数组大小. [![build badge](https://api.travis-ci.org/fizyk20/generic-array.svg?branch=master)](https://travis-ci.org/fizyk20/generic-array)
* [garro95/priority-queue](https://github.com/garro95/priority-queue)[[priority-queue](https://crates.io/crates/priority-queue)] — 一个优先队列实现优先级的变化。[![build badge](https://api.travis-ci.org/garro95/priority-queue.svg?branch=master)](https://travis-ci.org/garro95/priority-queue)
* [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs) — k维树锈快速地理空间索引和最近的邻居查找
* [orium/rpds](https://github.com/orium/rpds) [[rpds](https://crates.io/crates/rpds)] — 持久数据结构中生锈。[![build badge](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions?query=workflow%3ACI)
* [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs) – 在Rust中咆哮的位图
* [rust-itertools/itertools](https://github.com/rust-itertools/itertools) — [![build badge](https://api.travis-ci.org/rust-itertools/itertools.svg?branch=master)](https://travis-ci.org/rust-itertools/itertools)
* [tnballo/scapegoat](https://github.com/tnballo/scapegoat) [[scapegoat](https://crates.io/crates/scapegoat)] — 安全,可靠,stack-only替代“BTreeSet”和“BTreeMap”。[![GitHub Actions](https://github.com/tnballo/scapegoat/workflows/test/badge.svg?branch=master)](https://github.com/tnballo/scapegoat/actions)
* [xfix/enum-map](https://github.com/xfix/enum-map) [[enum-map](https://crates.io/crates/enum-map)] — 一个优化的映射实现使用一个数组来存储枚举值。[![build badge](https://api.travis-ci.org/xfix/enum-map.svg?branch=master)](https://travis-ci.org/xfix/enum-map)
* [yamafaktory/hypergraph](https://github.com/yamafaktory/hypergraph) [[hypergraph](https://crates.io/crates/hypergraph)] — 超图是一个数据结构库来生成有向超图。[![ci](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml)

### 数据可视化 Data visualization
> 数据可视化

* [djduque/pgfplots](https://github.com/djduque/pgfplots) [[pgfplots](https://crates.io/crates/pgfplots)] — 锈库来生成可发布数据。[![build](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml/badge.svg)](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml)
* [igiagkiozis/plotly](https://github.com/igiagkiozis/plotly) — 情节的生锈。
* [milliams/plotlib](https://github.com/milliams/plotlib) — [![build badge](https://api.travis-ci.org/milliams/plotlib.svg?branch=master)](https://travis-ci.org/milliams/plotlib)
* [plotters](https://github.com/plotters-rs/plotters) — [![build badge](https://github.com/plotters-rs/plotters/workflows/CI/badge.svg)](https://github.com/plotters-rs/plotters/actions)
* [saresend/gust](https://github.com/saresend/Gust) — [![build badge](https://api.travis-ci.org/saresend/Gust.svg?branch=master)](https://travis-ci.org/saresend/Gust)

### 数据库 Database
> 数据库

[[database](https://crates.io/keywords/database)]

* NoSQL [[nosql](https://crates.io/keywords/nosql)]

  * [ArangoDB](https://www.arangodb.com)
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[aragog](https://crates.io/crates/aragog)] - 一个轻量级的ArangoDB对象文档、关系和图形映射器 [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
    * [Arangors](https://github.com/fMeow/arangors) [[arangors](https://crates.io/crates/arangors)] - 用于Rust的ArangoDB驱动
  * [Cassandra](https://cassandra.apache.org/_/index.html) [[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
    * [AlexPikalov/cdrs](https://github.com/AlexPikalov/cdrs) [[cdrs](https://crates.io/crates/cdrs)] — 原生客户端写在生锈[![build badge](https://api.travis-ci.org/AlexPikalov/cdrs.svg?branch=master)](https://travis-ci.org/AlexPikalov/cdrs)
    * [krojew/cdrs-tokio](https://github.com/krojew/cdrs-tokio) [[cdrs-tokio](https://crates.io/crates/cdrs-tokio)] - 用纯Rust编写的生产就绪的异步Apache Cassandra驱动程序 [![build badge](https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)
    * [Metaswitch/cassandra-rs](https://github.com/Metaswitch/cassandra-rs) —  绑定到DataStax C / C端[![build badge](https://api.travis-ci.org/Metaswitch/cassandra-rs.svg?branch=master)](https://travis-ci.org/Metaswitch/cassandra-rs)
  * CouchDB [[couchdb](https://crates.io/keywords/couchdb)]
    * [chill-rs/chill](https://github.com/chill-rs/chill) [[couchdb](https://crates.io/crates/chill)] — CouchDB的铁锈端REST API[![build badge](https://api.travis-ci.org/chill-rs/chill.svg?branch=master)](https://travis-ci.org/chill-rs/chill)
  * [DynamoDB](https://aws.amazon.com/dynamodb/) [[dynamodb](https://crates.io/keywords/dynamodb)]
    * [softprops/dynomite](https://github.com/softprops/dynomite) - 一个用于与`rusoto_dynamodb`进行强类型和便捷互动的库 [![build badge](https://github.com/softprops/dynomite/workflows/Main/badge.svg?branch=master)](https://github.com/softprops/dynomite/actions)
  * Elasticsearch [[elasticsearch](https://crates.io/keywords/elasticsearch)]
    * [benashford/rs-es](https://github.com/benashford/rs-es) [[rs-es](https://crates.io/crates/rs-es)] — 一个生锈的客户[Elastic](https://www.elastic.co/) REST API [![build badge](https://api.travis-ci.org/benashford/rs-es.svg?branch=master)](https://travis-ci.org/benashford/rs-es)
    * [elastic-rs/elastic](https://github.com/elastic-rs/elastic) [[elastic](https://crates.io/crates/elastic)] — 弹性是一种有效的、模块化的API客户机Elasticsearch写在生锈[![build badge](https://ci.appveyor.com/api/projects/status/csa78tcumdpnbur2?svg=true)](https://ci.appveyor.com/project/KodrAus/elastic)
  * etcd
    * [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd) [[etcd](https://crates.io/crates/etcd)] — 客户端库CoreOS etcd。[![build badge](https://api.travis-ci.org/jimmycuadra/rust-etcd.svg?branch=master)](https://travis-ci.org/jimmycuadra/rust-etcd)
    * [lodrem/etcd-rs](https://github.com/lodrem/etcd-rs) — 异步etcd客户生锈[![CI](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml)
  * ForestDB
    * [vhbit/sherwood](https://github.com/vhbit/sherwood) — [ForestDB](https://github.com/couchbase/forestdb) 捆绑 [![build badge](https://api.travis-ci.org/vhbit/sherwood.svg?branch=master)](https://travis-ci.org/vhbit/sherwood)
  * [InfluxDB](https://www.influxdata.com/)
    * [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs) — 同步接口[![build badge](https://api.travis-ci.org/driftluo/InfluxDBClient-rs.svg?branch=master)](https://travis-ci.org/driftluo/InfluxDBClient-rs)
  * LevelDB
    * [skade/leveldb](https://github.com/skade/leveldb) — [LevelDB](https://github.com/google/leveldb) 捆绑 [![build badge](https://api.travis-ci.org/skade/leveldb.svg?branch=master)](https://travis-ci.org/skade/leveldb)
  * LMDB [[lmdb](https://crates.io/keywords/lmdb)]
    * [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs) [[lmdb-rs](https://crates.io/crates/lmdb-rs)] — [LMDB](https://www.symas.com/symas-embedded-database-lmdb) 捆绑 [![build badge](https://api.travis-ci.org/vhbit/lmdb-rs.svg?branch=master)](https://travis-ci.org/vhbit/lmdb-rs)
  * MongoDB [[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver) [[mongodb](https://crates.io/crates/mongodb)] — [MongoDB](https://www.mongodb.com/) 捆绑
  * [PickleDB](https://pythonhosted.org/pickleDB/)
    * [seladb/pickledb-rs](https://github.com/seladb/pickledb-rs) — 一个轻量级的和简单的键值存储,灵感来自于Python的PickleDB。[![build badge](https://api.travis-ci.org/seladb/pickledb-rs.svg?branch=master)](https://travis-ci.org/seladb/pickledb-rs)
  * Redis [[redis](https://crates.io/keywords/redis)]
    * [aembke/fred](https://github.com/aembke/fred.rs) [[fred](https://crates.io/crates/fred)] - 一个高水平的异步 [Redis](https://redis.io/) 与Tokio公司合作的Rust客户. [![CircleCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg?style=svg)]([https://circleci.com/gh/aembke/fred.rs/tree/main](https://app.circleci.com/pipelines/github/aembke/fred.rs?branch=main))
    * [redis-rs](https://github.com/redis-rs/redis-rs) — [Redis](https://redis.io/) 图书馆在 Rust [![Rust](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)
  * [RocksDB](https://rocksdb.org/)
    * [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) — RocksDB绑定[![RocksDB CI](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml)
  * [SurrealDB](https://surrealdb.com/)
    * [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb) — SurrealDB嵌入式document-graph数据库
  * [UnQLite](https://unqlite.org/)
    * [zitsen/unqlite.rs](https://github.com/zitsen/unqlite.rs) — UnQLite绑定[![build badge](https://api.travis-ci.org/zitsen/unqlite.rs.svg?branch=master)](https://travis-ci.org/zitsen/unqlite.rs)
  * [ZooKeeper](https://zookeeper.apache.org/)
    * [bonifaido/rust-zookeeper](https://github.com/bonifaido/rust-zookeeper) [[zookeeper](https://crates.io/crates/zookeeper)] — Apache管理员客户端库。[![build badge](https://api.travis-ci.org/bonifaido/rust-zookeeper.svg?branch=master)](https://travis-ci.org/bonifaido/rust-zookeeper)
    * [krojew/rust-zookeeper](https://github.com/krojew/rust-zookeeper) [[zookeeper-async](https://crates.io/crates/zookeeper-async)] - 100%用Rust编写的异步Zookeeper客户端，基于tokio。.  ![build status](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)
* OGM [[ogm](https://crates.io/keywords/ogm)]
  * [Aragog](https://gitlab.com/qonfucius/aragog) [[aragog](https://crates.io/crates/aragog)] - 一个轻量级的ArangoDB对象文档、关系和图形映射器 [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
* ORM [[orm](https://crates.io/keywords/orm)]
  * [Brendonovich/prisma-client-rust](https://github.com/Brendonovich/prisma-client-rust) — 一个自动生成query builder,它提供了简单、完全使用棱镜生态系统类型安全的数据库访问。[![Test Status](https://img.shields.io/github/workflow/status/Brendonovich/prisma-client-rust/CI?label=tests&style=flat-square)](https://github.com/Brendonovich/prisma-client-rust/actions)
  * [diesel-rs/diesel](https://github.com/diesel-rs/diesel) — 一个ORM和Query builder生锈[![Build Status](https://api.travis-ci.org/diesel-rs/diesel.svg?branch=master)](https://travis-ci.org/diesel-rs/diesel)
  * [ivanceras/rustorm](https://github.com/ivanceras/rustorm) — 一个ORM生锈[![Build Status](https://api.travis-ci.org/ivanceras/rustorm.svg?branch=master)](https://travis-ci.org/ivanceras/rustorm)
  * [rbatis/rbatis](https://github.com/rbatis/rbatis) — 基于锈ORM框架高性能(JSON)[![Build Status](https://api.travis-ci.org/zhuxiujia/rbatis.svg?branch=master)](https://travis-ci.org/zhuxiujia/rbatis)
  * [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm) — Guo Wu An async[![Build Status](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)
* [sfackler/r2d2](https://github.com/sfackler/r2d2) — 通用的连接池[![build badge](https://api.travis-ci.org/sfackler/r2d2.svg?branch=master)](https://travis-ci.org/sfackler/r2d2)
* SQL [[sql](https://crates.io/keywords/sql)]
  * Generic
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx) - 支持强类型的异步PostgreSQL/MySQL/SQLite连接池 [![build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)
    * [SeaQL/sea-query](https://github.com/SeaQL/sea-query) - 🔱 用于MySQL、Postgres和SQLite的动态SQL查询生成器 [![build status](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml)
    * [SeaQL/sea-schema](https://github.com/SeaQL/sea-schema) - 🌿 SQL模式管理套件 [![build status](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml)
  * Microsoft SQL
    * [prisma/tiberius](https://github.com/prisma/tiberius) — [![Cargo tests](https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)
  * MySql [[mysql](https://crates.io/keywords/mysql)]
    * [AgilData/mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs) — 一个MySQL代理[![CircleCI](https://circleci.com/gh/AgilData/mysql-proxy-rs/tree/master.svg?style=svg)](https://app.circleci.com/pipelines/github/AgilData/mysql-proxy-rs?branch=master)
    * [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async) [[mysql_async](https://crates.io/crates/mysql_async)] — 根据东京asyncronous锈Mysql驱动程序。[![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)] — 一个本地MySql客户端[![build badge](https://api.travis-ci.org/blackbeam/rust-mysql-simple.svg?branch=master)](https://travis-ci.org/blackbeam/rust-mysql-simple)
  * PostgreSql [[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) [[postgres](https://crates.io/crates/postgres)] — 一个本地[PostgreSQL](https://www.postgresql.org/) 客户端 [![build badge](https://api.travis-ci.org/sfackler/rust-postgres.svg?branch=master)](https://travis-ci.org/sfackler/rust-postgres)
  * Sqlite [[sqlite](https://crates.io/keywords/sqlite)]
    * [rusqlite](https://github.com/rusqlite/rusqlite) — [Sqlite3](https://www.sqlite.org/index.html) 捆绑 [![build badge](https://api.travis-ci.org/rusqlite/rusqlite.svg?branch=master)](https://travis-ci.org/rusqlite/rusqlite)

### 日期和时间 Date and time
> 日期和时间

[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

* [chronotope/chrono](https://github.com/chronotope/chrono) — [![build badge](https://api.travis-ci.org/chronotope/chrono.svg?branch=master)](https://travis-ci.org/chronotope/chrono)
* [Mnwa/ms](https://github.com/Mnwa/ms) [[ms-converter](https://crates.io/crates/ms-converter)] — 它是一个将类似人类的时间转换为毫秒的库 [![build badge](https://github.com/Mnwa/ms/workflows/build/badge.svg?branch=master)](https://github.com/Mnwa/ms/actions?query=workflow%3Abuild)
* [time-rs/time](https://github.com/time-rs/time) — [![build badge](https://github.com/time-rs/time/workflows/Build/badge.svg)](https://github.com/time-rs/time/actions)

### 分布式系统 Distributed systems
> 分布式系统

* Antimony
  * [antimonyproject/antimony](https://github.com/antimonyproject/antimony) [[antimony](https://crates.io/crates/antimony)] — 流处理/分布式计算平台 [![build badge](https://api.travis-ci.org/antimonyproject/antimony.svg?branch=master)](https://travis-ci.org/antimonyproject/antimony)
* Apache Kafka
  * [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) [[rdkafka](https://crates.io/crates/rdkafka)] — [librdkafka](https://github.com/edenhill/librdkafka) 绑定 [![build badge](https://api.travis-ci.org/fede1024/rust-rdkafka.svg?branch=master)](https://travis-ci.org/fede1024/rust-rdkafka)
  * [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter) [[schema_registry_converter](https://crates.io/crates/schema_registry_converter)] — 以与 [confluent schema registry](https://www.confluent.io/product/confluent-platform/data-compatibility/) [![build badge](https://api.travis-ci.org/gklijs/schema_registry_converter.svg?branch=master)](https://travis-ci.org/gklijs/schema_registry_converter)
  * [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust) — [![build badge](https://api.travis-ci.org/kafka-rust/kafka-rust.svg?branch=master)](https://travis-ci.org/kafka-rust/kafka-rust)
* Beanstalkd
  * [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd) — [Beanstalkd](https://github.com/beanstalkd/beanstalkd) 绑定 [![build badge](https://api.travis-ci.org/schickling/rust-beanstalkd.svg?branch=master)](https://travis-ci.org/schickling/rust-beanstalkd)
* HDFS
  * [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs) [[hdfs](https://crates.io/crates/hdfs)] — libhdfs 绑定

### 领域驱动设计 Domain driven design
> 领域驱动设计

  * [serverlesstechnology/cqrs](https://github.com/serverlesstechnology/cqrs) [[cqrs-es](https://crates.io/crates/cqrs-es)] — 一个关于CQRS和事件来源的框架，包括 [user guide](https://doc.rust-cqrs.org/)

### 电子邮件 Email
> 电子邮件

[[email](https://crates.io/keywords/email), [imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

* [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) - 非官方的铁锈库SendGrid API[![build badge](https://api.travis-ci.org/gsquire/sendgrid-rs.svg?branch=master)](https://travis-ci.org/gsquire/sendgrid-rs)
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte) [![build badge](https://api.travis-ci.com/jdrouet/catapulte.svg?branch=main)](https://travis-ci.org/jdrouet/catapulte) - 一个使用[MRML](https://github.com/jdrouet/mrml)模板发送电子邮件的微服务。
* [jdrouet/jolimail](https://github.com/jdrouet/jolimail) [![pipeline status](https://gitlab.com/jeremie.drouet/jolimail/badges/main/pipeline.svg)](https://gitlab.com/jeremie.drouet/jolimail/-/commits/main) - 一个构建[MRML](https://github.com/jdrouet/mrml)模板的Web应用程序。
* [jdrouet/mrml](https://github.com/jdrouet/mrml) [![build badge](https://api.travis-ci.com/jdrouet/mrml.svg?branch=master)](https://travis-ci.org/jdrouet/mrml) - 一个生成漂亮的电子邮件模板的库，可以在任何邮件客户端工作。
* [lettre/lettre](https://github.com/lettre/lettre) - 一个SMTP-library生锈[![CI](https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)
* [staktrace/mailparse](https://github.com/staktrace/mailparse) [[mailparse](https://crates.io/crates/mailparse)] - 库解析真实电子邮件文件[![build badge](https://api.travis-ci.org/staktrace/mailparse.svg?branch=master)](https://travis-ci.org/staktrace/mailparse)
* [stalwartlabs/mail-parser](https://github.com/stalwartlabs/mail-parser) [[mail-parser](https://crates.io/crates/mail-parser)] - 一个快速而强大的电子邮件解析库，完全支持MIME[![build badge](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml)
* [stalwartlabs/mail-send](https://github.com/stalwartlabs/mail-send) [[mail-send](https://crates.io/crates/mail-send)] - 支持DKIM的电子邮件生成器和SMTP客户端库[![build badge](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml)


### 编码 Encoding
> 编码

[[编码](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1) — 一个生锈的asn . 1 (DER)序列化器[![build badge](https://api.travis-ci.org/alex/rust-asn1.svg?branch=master)](https://travis-ci.org/alex/rust-asn1)
* Binary
  * [bincode-org/bincode](https://github.com/bincode-org/bincode) — 一个二进制编码器/解码器生锈[![CI](https://github.com/bincode-org/bincode/actions/workflows/rust.yml/badge.svg?branch=trunk)](https://github.com/bincode-org/bincode/actions/workflows/rust.yml)
  * [m4b/goblin](https://github.com/m4b/goblin) [[goblin](https://crates.io/crates/goblin)] —  跨平台、零拷贝和endian-aware二进制解析[![build badge](https://api.travis-ci.org/m4b/goblin.svg?branch=master)](https://travis-ci.org/m4b/goblin)
* BSON
  * [mongodb/bson-rust](https://github.com/mongodb/bson-rust) — 编码和解码支持BSON生锈
* Byte swapping
  * [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) — 支持大端法、低位优先和本机字节顺序[![build badge](https://api.travis-ci.org/BurntSushi/byteorder.svg?branch=master)](https://travis-ci.org/BurntSushi/byteorder)
* Cap'n Proto
  * [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) — [![build badge](https://api.travis-ci.org/capnproto/capnproto-rust.svg?branch=master)](https://travis-ci.org/capnproto/capnproto-rust)
* CBOR
  * [serde_cbor](https://crates.io/crates/serde_cbor) — CBOR支持serde[![build badge](https://api.travis-ci.org/pyfisch/cbor.svg?branch=master)](https://travis-ci.org/pyfisch/cbor)
* Character Encoding
  * [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs) [[encoding_rs](https://crates.io/crates/encoding_rs)] — Gecko-oriented实现编码标准的生锈[![build badge](https://api.travis-ci.org/hsivonen/encoding_rs.svg?branch=master)](https://travis-ci.org/hsivonen/encoding_rs)
  * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding) — [![build badge](https://api.travis-ci.org/lifthrasiir/rust-encoding.svg?branch=master)](https://travis-ci.org/lifthrasiir/rust-encoding)
* CRC
  * [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) — [![build badge](https://api.travis-ci.org/mrhooray/crc-rs.svg?branch=master)](https://travis-ci.org/mrhooray/crc-rs)
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) — 一个快速和灵活的CSV读者和作家,对Serde的支持[![build badge](https://api.travis-ci.org/BurntSushi/rust-csv.svg?branch=master)](https://travis-ci.org/BurntSushi/rust-csv)
* EDN
  * [naomijub/edn-rs](https://github.com/naomijub/edn-rs) [[edn-rs](https://crates.io/crates/edn-rs)] — 箱和排放版格式解析成铁锈类型。[![Build Status]( https://api.travis-ci.org/naomijub/edn-rs.svg?branch=master)](https://travis-ci.org/naomijub/edn-rs)
* [FlatBuffers](https://google.github.io/flatbuffers/)
  * [frol/flatc-rust](https://github.com/frol/flatc-rust) — FlatBuffers货物构建脚本编译器(flatc)集成[![build badge](https://api.travis-ci.org/frol/flatc-rust.svg?branch=master)](https://travis-ci.org/frol/flatc-rust)
* HAR
  * [mandrean/har-rs](https://github.com/mandrean/har-rs) [[har](https://crates.io/crates/har)] — HTTP档案格式(HAR)序列化[![Build Status](https://api.travis-ci.org/mandrean/har-rs.svg?branch=master)](https://travis-ci.org/mandrean/har-rs)
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever) — 高性能browser-grade HTML5解析器[![build badge](https://api.travis-ci.com/servo/html5ever.svg?branch=master)](https://travis-ci.org/servo/html5ever)
* JSON
  * [importcjj/rust-ajson](https://github.com/importcjj/rust-ajson) [[ajson]](https://crates.io/crates/ajson) —  迅速得到JSON值[![build badge](https://api.travis-ci.com/importcjj/rust-ajson.svg?branch=master)](https://app.travis-ci.com/github/importcjj/rust-ajson)
  * [maciejhirsz/json-rust](https://github.com/maciejhirsz/json-rust) [[json](https://crates.io/crates/json)] — JSON实现生锈[![build badge](https://api.travis-ci.org/maciejhirsz/json-rust.svg?branch=master)](https://travis-ci.org/maciejhirsz/json-rust)
  * [pikkr/pikkr](https://github.com/pikkr/pikkr) [[pikkr](https://crates.io/crates/pikkr)] — JSON解析器拿起值直接执行标记在生锈
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)] — JSON支持[Serde](https://github.com/serde-rs/serde) 框架 [![build badge](https://api.travis-ci.org/serde-rs/json.svg?branch=master)](https://travis-ci.org/serde-rs/json)
  * [simd-lite/simd-json](https://github.com/simd-lite/simd-json) [[simd-json](https://crates.io/crates/simd-json)] — 高性能JSON解析器基于simdjson港
* MsgPack
  * [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) — 一个纯粹的铁锈MessagePack实现低/高水平[![build badge](https://api.travis-ci.org/3Hren/msgpack-rust.svg?branch=master)](https://travis-ci.org/3Hren/msgpack-rust)
* PEM
  * [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs) [[pem](https://crates.io/crates/pem)] — 基于锈方法解析和编码PEM-encoded数据[![build badge](https://api.travis-ci.org/jcreekmore/pem-rs.svg?branch=master)](https://travis-ci.org/jcreekmore/pem-rs)
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) — [![build badge](https://api.travis-ci.org/stepancheg/rust-protobuf.svg?branch=master)](https://travis-ci.org/stepancheg/rust-protobuf)
  * [tokio-rs/prost](https://github.com/tokio-rs/prost) — [![continuous integration](https://github.com/tokio-rs/prost/workflows/continuous%20integration/badge.svg?branch=master)](https://github.com/tokio-rs/prost/actions)
* RON (锈迹斑斑的对象记号)
  * [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron) — [![build badge](https://api.travis-ci.org/ron-rs/ron.svg?branch=master)](https://travis-ci.org/https://github.com/ron-rs/ron)
* Serde
  * [vityafx/serde-aux](https://github.com/vityafx/serde-aux/) - 与Serde库一起使用的额外工具. [![CI](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/serde-aux.svg)](https://crates.io/crates/serde-aux)
* TOML
  * [toml-rs/toml](https://github.com/toml-rs/toml) — [![CI](https://github.com/toml-rs/toml/actions/workflows/ci.yml/badge.svg)](https://github.com/toml-rs/toml/actions/workflows/ci.yml)
* XML
  * [Florob/RustyXML](https://github.com/Florob/RustyXML) — 编写的XML解析器生锈[![build badge](https://api.travis-ci.org/Florob/RustyXML.svg?branch=master)](https://travis-ci.org/Florob/RustyXML)
  * [media-io/yaserde](https://github.com/media-io/yaserde) — 另一个序列化器/反序列化器专门用于XML[![build badge](https://api.travis-ci.org/media-io/yaserde.svg?branch=master)](https://travis-ci.org/media-io/yaserde)
  * [netvl/xml-rs](https://github.com/netvl/xml-rs) — 流XML库[![build badge](https://api.travis-ci.org/netvl/xml-rs.svg?branch=master)](https://travis-ci.org/netvl/xml-rs)
  * [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document) — 生锈的XML库[![build badge](https://api.travis-ci.org/shepmaster/sxd-document.svg?branch=master)](https://travis-ci.org/shepmaster/sxd-document)
  * [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath) — XPath图书馆生锈[![build badge](https://api.travis-ci.org/shepmaster/sxd-xpath.svg?branch=master)](https://travis-ci.org/shepmaster/sxd-xpath)
  * [tafia/quick-xml](https://github.com/tafia/quick-xml) — 高性能XML阅读器/写入器[![build badge](https://api.travis-ci.org/tafia/quick-xml.svg?branch=master)](https://travis-ci.org/tafia/quick-xml)
* YAML
  * [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust) — 失踪的YAML 1.2实现生锈。[![build badge](https://api.travis-ci.org/chyh1990/yaml-rust.svg?branch=master)](https://travis-ci.org/chyh1990/yaml-rust)
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml)] — YAML的支持[Serde](https://github.com/serde-rs/serde) framework [![build](https://img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions?query=branch%3Amaster)
  * [vitiral/stfu8](https://github.com/vitiral/stfu8) [[stfu8](https://crates.io/crates/stfu8)] — 可以说是文本格式在utf - 8[![build badge](https://api.travis-ci.org/vitiral/stfu8.svg?branch=master)](https://travis-ci.org/vitiral/stfu8)

### 文件系统 Filesystem
> 文件系统

[[文件系统](https://crates.io/keywords/filesystem)]
* 业务
  * [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) [[dbus-udisks2](https://crates.io/crates/dbus-udisks2)] - UDisks2 DBus API
  * [pop-os/sys-mount](https://github.com/pop-os/sys-mount) [[sys-mount](https://crates.io/crates/sys-mount)] — 高水平的抽象的“山”/“umount2”系统调用。
  * [vitiral/path_abs](https://github.com/vitiral/path_abs) [[path_abs](https://crates.io/crates/path_abs)] — 绝对可序列化的路径类型和相关的方法。[![build badge](https://api.travis-ci.org/vitiral/path_abs.svg?branch=master)](https://travis-ci.org/webdesus/fs_extr://travis-ci.org/vitiral/path_abs)
  * [webdesus/fs_extra](https://github.com/webdesus/fs_extra) — 扩大机会标准库std:: fs和std:: io[![build badge](https://api.travis-ci.org/webdesus/fs_extra.svg?branch=master)](https://travis-ci.org/webdesus/fs_extra)
* 临时文件
  * [Stebalien/tempfile](https://github.com/Stebalien/tempfile) — 临时文件的库[![build badge](https://api.travis-ci.org/Stebalien/tempfile.svg?branch=master)](https://travis-ci.org/Stebalien/tempfile)
  * [Stebalien/xattr](https://github.com/Stebalien/xattr) [[xattr](https://crates.io/crates/xattr)] — 列表和操作unix扩展文件属性[![build badge](https://api.travis-ci.org/Stebalien/xattr.svg?branch=master)](https://travis-ci.org/Stebalien/xattr)
  * [zboxfs/zbox](https://github.com/zboxfs/zbox) [[zbox](https://crates.io/crates/zbox)] — Zero-details, shadow嵌入式文件系统。[![build badge](https://api.travis-ci.org/zboxfs/zbox.svg?branch=master)](https://travis-ci.org/zboxfs/zbox)

### 函数式编程 Functional Programming
> 函数式编程

[[函数式编程](https://crates.io/keywords/fp)]
* Prelude
  * [JasonShin/fp-core.rs](https://github.com/JasonShin/fp-core.rs) — 一个库函数式编程的生锈
  * [myrrlyn/tap](https://github.com/myrrlyn/tap) - 后缀位置的管道行为

### 游戏开发 Game development
> 游戏开发

另见 [Are we game yet?](https://arewegameyet.rs)
* Allegro
  * [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) — [Allegro 5](https://liballeg.org/) 捆绑 [![build badge](https://api.travis-ci.org/SiegeLord/RustAllegro.svg?branch=master)](https://travis-ci.org/SiegeLord/RustAllegro)
* [Awesome Quads](https://github.com/ozkriff/awesome-quads) — 一个策划miniquad / macroquad-related代码的链接列表
* [Awesome wgpu](https://github.com/rofrol/awesome-wgpu) — 一个策划wgpu代码和资源的列表
* bracket-lib (previously RLTK)
  * [bracket-lib](https://github.com/amethyst/bracket-lib) [[bracket-lib](https://crates.io/crates/bracket-lib)] - 为Rust实现的Roguelike工具包（RLTK）。. [![Rust](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml/badge.svg)](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml)
* Challonge
  * [vityafx/challonge-rs](https://github.com/vityafx/challonge-rs) [[challonge](https://crates.io/crates/challonge)] — 客户端库Challonge REST API。有助于组织比赛。[![CI](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml)
* Corange
  * [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs) — [Corange](https://github.com/orangeduck/Corange) 捆绑
* 实体-组件系统 (ECS)
  * [amethyst/specs](https://github.com/amethyst/specs) — 规范平行ECS[![build badge](https://api.travis-ci.org/amethyst/specs.svg?branch=master)](https://travis-ci.org/amethyst/specs)
  * [legion](https://github.com/amethyst/legion) — 一个特性丰富的高性能ECS库以最小的样板[![build badge](https://github.com/amethyst/legion/workflows/CI/badge.svg?branch=master)](https://github.com/amethyst/legion/actions)
* 游戏引擎
  * [Bevy](https://github.com/bevyengine/bevy) 是一个令人耳目一新的简单的数据驱动的游戏引擎，用Rust构建. - [![Crates.io](https://img.shields.io/crates/v/bevy.svg)](https://crates.io/crates/bevy)
    [![Crates.io](https://img.shields.io/crates/d/bevy.svg)](https://crates.io/crates/bevy)
  * [Fyrox](https://fyrox.rs/) — 生锈的3 d游戏引擎[![Crates.io](https://img.shields.io/crates/v/fyrox.svg)](https://crates.io/crates/fyrox) [![license](https://img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md) [![Crates.io](https://img.shields.io/crates/d/fyrox.svg)](https://crates.io/crates/fyrox)
  * [ggez](https://github.com/ggez/ggez) — 一个轻量级游戏制作2 d游戏框架,用最小的摩擦[![Crates.io](https://img.shields.io/crates/v/ggez.svg)](https://crates.io/crates/ggez) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ggez/ggez/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/ggez.svg)](https://crates.io/crates/ggez)
  * [Kiss3d](http://kiss3d.org) — 保持简单,愚蠢的3 d图形引擎与生锈[![Crates.io](https://img.shields.io/crates/d/kiss3d.svg)](https://crates.io/crates/kiss3d)
  * [oxidator](https://github.com/Ruddle/oxidator) — 实时战略游戏/引擎用防锈、WebGPU
  * [Piston](https://www.piston.rs/) — [![Crates.io](https://img.shields.io/crates/v/piston.svg?style=flat-square)](https://crates.io/crates/piston) [![Crates.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/piston.svg)](https://crates.io/crates/piston)
  * [Unrust](https://github.com/unrust/unrust) — unrust - 一个纯粹的基于rust的（webgl 2.0 / native）游戏引擎。
* [Godot](https://godotengine.org/)
  * [godot-rust/gdnative](https://github.com/godot-rust/gdnative) [[gdnative](https://crates.io/crates/gdnative)] - 与Godot游戏引擎的Rust绑定 [![CI](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml)
* [Raylib](https://www.raylib.com/)
  * [deltaphc/raylib-rs](https://github.com/deltaphc/raylib-rs) [[raylib](https://crates.io/crates/raylib)] — 生锈的绑定raylib
* [SDL](http://www.libsdl.org/) [[sdl](https://crates.io/keywords/sdl)]
  * [brson/rust-sdl](https://github.com/brson/rust-sdl) — SDL1绑定[![build badge](https://api.travis-ci.org/brson/rust-sdl.svg?branch=master)](https://travis-ci.org/brson/rust-sdl)
  * [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) — SDL2绑定[![build badge](https://api.travis-ci.org/Rust-SDL2/rust-sdl2.svg?branch=master)](https://travis-ci.org/Rust-SDL2/rust-sdl2)
* SFML
  * [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) — [SFML](https://www.sfml-dev.org/) 捆绑
* Tcod-rs
  * [tomassedovic/tcod-rs](https://github.com/tomassedovic/tcod-rs) — Libtcod绑定生锈。
  * 警告。不再维护
* Toornament-rs
  * [vityafx/toornament-rs](https://github.com/vityafx/toornament-rs) - Toornament.com的Rust的API绑定. [![CI](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/toornament.svg)](https://crates.io/crates/toornament)
* Victorem
  * [VictoremWinbringer/Victorem](https://github.com/VictoremWinbringer/Victorem) [[Victorem](https://crates.io/crates/Victorem)] — 简单的UDP游戏服务器和UDP客户端框架来创建简单的2 d和3 d网络游戏原型[![build badge](https://api.travis-ci.org/VictoremWinbringer/Victorem.svg?branch=master)](https://travis-ci.org/VictoremWinbringer/Victorem)

### 地理空间 Geospatial
> 地理空间

[[geo](https://crates.io/keywords/geo), [gis](https://crates.io/keywords/gis)]

* [DaveKram/coord_transforms](https://github.com/DaveKram/coord_transforms) [[coord_transforms](https://crates.io/crates/coord_transforms)] — 坐标转换(2 d, 3 d和地理空间)[![build badge](https://api.travis-ci.org/DaveKram/coord_transforms.svg?branch=master)](https://travis-ci.org/DaveKram/coord_transforms)
* [Georust](https://github.com/georust) — 地理空间的工具和库编写的生锈
* [rust-reverse-geocoder](https://github.com/gx0r/rrgeo) — 一种快速、离线反向geocoder生锈,受到启发[thampiman/reverse-geocoder](https://github.com/thampiman/reverse-geocoder)
* [vlopes11/geomorph](https://github.com/vlopes11/geomorph) [[geomorph](https://crates.io/crates/geomorph)] — 之间的转换UTM、LatLon和MGRS坐标[![build badge](https://api.travis-ci.org/vlopes11/geomorph.svg?branch=master)](https://travis-ci.org/vlopes11/geomorph)

### 图算法 Graph algorithms
> 图算法

* [s1ck/graph](https://github.com/s1ck/graph) - 一个高性能图算法的库 [![graph CI status](https://img.shields.io/github/workflow/status/s1ck/graph/CI/main?label=CI)](https://github.com/s1ck/graph/actions/workflows/rust.yml)

### 图形 Graphics
> 图形

[[graphics](https://crates.io/keywords/graphics)]

* Font
  * [RazrFalcon/rustybuzz](https://github.com/RazrFalcon/rustybuzz) - 渐进式的harfbuzz移植到Rust中 [![build badge](https://api.travis-ci.org/RazrFalcon/rustybuzz.svg?branch=master)](https://travis-ci.org/RazrFalcon/rustybuzz)
  * [redox-os/rusttype](https://github.com/redox-os/rusttype) — 纯锈替代像FreeType的库[![build badge](https://api.travis-ci.org/redox-os/rusttype.svg?branch=master)](https://travis-ci.org/redox-os/rusttype)
* [gfx-rs/gfx](https://github.com/gfx-rs/gfx) — 一个高性能、bindless图形API生锈。[![build badge](https://api.travis-ci.org/gfx-rs/gfx.svg?branch=master)](https://travis-ci.org/gfx-rs/gfx)
* [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) - 基于gfx-hal的本地WebGPU实现. [![build badge](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)
* OpenGL [[opengl](https://crates.io/keywords/opengl)]
  * [brendanzab/gl-rs](https://github.com/brendanzab/gl-rs) — [![build badge](https://api.travis-ci.org/brendanzab/gl-rs.svg?branch=master)](https://travis-ci.org/brendanzab/gl-rs)
  * [glium/glium](https://github.com/glium/glium) — 安全的OpenGL包装生锈语言。[![build badge](https://api.travis-ci.org/glium/glium.svg?branch=master)](https://travis-ci.org/glium/glium)
  * [glutin](https://crates.io/crates/glutin) — 铁锈的选择[GLFW](https://www.glfw.org/) [![build badge](https://api.travis-ci.org/rust-windowing/glutin.svg?branch=master)](https://travis-ci.org/rust-windowing/glutin)
  * [Kiss3d](http://kiss3d.org) — 绘制简单的几何图形和玩俏皮话[![build badge](https://api.travis-ci.org/sebcrozet/kiss3d.svg?branch=master)](https://api.travis-ci.org/repositories/sebcrozet/kiss3d)
  * [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) — [![build badge](https://api.travis-ci.org/PistonDevelopers/glfw-rs.svg?branch=master)](https://travis-ci.org/PistonDevelopers/glfw-rs)
* PDF
  * [fschutt/printpdf](https://github.com/fschutt/printpdf) — PDF写库[![build badge](https://api.travis-ci.org/fschutt/printpdf.svg?branch=master)](https://travis-ci.org/fschutt/printpdf)
  * [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) — PDF文件的操作 [![build badge](https://api.travis-ci.org/J-F-Liu/lopdf.svg?branch=master)](https://travis-ci.org/J-F-Liu/lopdf)
  * [kaj/rust-pdf](https://github.com/kaj/rust-pdf) — [![build badge](https://api.travis-ci.org/kaj/rust-pdf.svg?branch=master)](https://travis-ci.org/kaj/rust-pdf)
  * [WASM-PDF](https://github.com/jussiniinikoski/wasm-pdf) – 用JavaScript和WASM（WebAssembly）生成PDF文件 [![build badge](https://api.travis-ci.org/jussiniinikoski/wasm-pdf.svg?branch=master)](https://travis-ci.org/jussiniinikoski/wasm-pdf)
* [Vulkan](https://www.vulkan.org/) [[vulkan](https://crates.io/keywords/vulkan)]
  * [erupt](https://gitlab.com/Friz64/erupt) [[erupt](https://crates.io/crates/erupt)] — [![build badge](https://gitlab.com/Friz64/erupt/badges/main/pipeline.svg)](https://gitlab.com/Friz64/erupt/-/pipelines)
  * [vulkano](https://github.com/vulkano-rs/vulkano) [[vulkano](https://crates.io/crates/vulkano)] — [![build badge](https://api.travis-ci.org/vulkano-rs/vulkano.svg?branch=master)](https://travis-ci.org/vulkano-rs/vulkano)

### GUI GUI
> GUI

[[gui](https://crates.io/keywords/gui)]

* [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs) — 一个简单的、跨平台的GUI自动化图书馆生锈。
* Cocoa
  * [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) — [![build badge](https://api.travis-ci.com/servo/core-foundation-rs.svg?branch=master)](https://travis-ci.org/servo/core-foundation-rs)
* [DioxusLabs/dioxus](https://github.com/dioxuslabs/dioxus) - 一个可移植的、高性能的、符合人体工程学的框架，用于在Rust中构建跨平台的用户接口. ![rust ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)
* [Druid](https://github.com/linebender/druid) [[druid](https://crates.io/crates/druid)] — [Druid](https://linebender.org/druid/),一个数据优先的Rust原生UI设计工具箱. [![build badge](https://github.com/linebender/druid/workflows/.github/workflows/ci.yml/badge.svg)](https://github.com/linebender/druid/actions)
* [emilk/egui](https://github.com/emilk/egui) - 简单、快速、高度可移植的Rust即时模式GUI库。egui可以在网络上、本地和你最喜欢的游戏引擎中运行。. [![Build Status](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions?workflow=CI)
* [emoon/rust_minifb](https://github.com/emoon/rust_minifb) — minifb跨平台窗口设置有可选的位图呈现。它还配有简单的鼠标和键盘输入。主要为原型设计
* [FLTK](https://www.fltk.org/)
  * [fltk-rs](https://github.com/fltk-rs/fltk-rs) — FLTK锈绑定[![Build](https://github.com/fltk-rs/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/fltk-rs/fltk-rs/actions)
* [Flutter](https://flutter.dev/)
  * [flutter-rs](https://github.com/flutter-rs/flutter-rs) — 在飞镖建立颤振桌面应用程序
* [fschutt/azul](https://github.com/fschutt/azul) — 免费、功能,IMGUI-oriented GUI桌面应用程序的快速开发框架编写的铁锈,Mozilla WebRender呈现引擎的支持。[![build badge](https://api.travis-ci.org/fschutt/azul.svg?branch=master)](https://travis-ci.org/fschutt/azul)
* [GTK+](https://www.gtk.org/) [[gtk](https://crates.io/keywords/gtk)]
  * [gtk-rs/gtk3-rs](https://github.com/gtk-rs/gtk3-rs) - 锈的GTK3绑定 ![CI](https://github.com/gtk-rs/gtk3-rs/workflows/CI/badge.svg)
  * [relm](https://github.com/antoyo/relm) — 异步的,基于GTK的GUI库,灵感来自榆树[![build badge](https://api.travis-ci.org/antoyo/relm.svg?branch=master)](https://travis-ci.org/antoyo/relm)
* [iced-rs/iced](https://github.com/iced-rs/iced) [[iced](https://crates.io/crates/iced)] — 一个跨平台的GUI库锈专注于简单和类型安全。灵感来自榆树。
* [ImGui](https://github.com/ocornut/imgui)
  * [imgui-rs](https://github.com/imgui-rs/imgui-rs) — 生锈的绑定ImGui[![Build Status](https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  * [Kiss-ui](https://github.com/KISS-UI/kiss-ui) — 一个简单的UI框架建立在IUP[![Build Status](https://api.travis-ci.org/cybergeek94/kiss-ui.svg?branch=master)](https://travis-ci.org/cybergeek94/kiss-ui)
* [ivanceras/sauron-native](https://github.com/ivanceras/sauron-native) - 一个真正的本地和跨平台GUI库。一个统一的代码可以作为本地GUI、Html Web和TUI运行. [![Build Status](https://api.travis-ci.com/ivanceras/sauron-native.svg?branch=master)](https://app.travis-ci.com/github/ivanceras/sauron-native)
* [libui](https://github.com/andlabs/libui)
  * [rust-native-ui/libui-rs](https://github.com/rust-native-ui/libui-rs) — libui绑定[![build badge](https://api.travis-ci.org/rust-native-ui/libui-rs.svg?branch=master)](https://travis-ci.org/rust-native-ui/libui-rs).
* [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear)
  * [nuklear-rust](https://github.com/snuk182/nuklear-rust) — 生锈的绑定Nuklear
* [OrbTk](https://github.com/redox-os/orbtk) — 轨道部件工具箱是一个多平台(G)使用SDL2 UI工具包[![Build and test](https://github.com/redox-os/orbtk/workflows/build/badge.svg?branch=develop)](https://github.com/redox-os/orbtk/actions)
* [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/) — 一个易于使用的,立即寻址模式的2 d GUI库编写完全生锈[![build badge](https://api.travis-ci.org/PistonDevelopers/conrod.svg?branch=master)](https://travis-ci.org/PistonDevelopers/conrod)
* [Qt](https://doc.qt.io)
  * [cyndis/qmlrs](https://github.com/cyndis/qmlrs) — QtQuick绑定[![build badge](https://api.travis-ci.org/cyndis/qmlrs.svg?branch=master)](https://travis-ci.org/cyndis/qmlrs)
  * [rust-qt](https://github.com/rust-qt)
  * [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs) — 集成Qml和铁锈通过构建QMetaObject在编译时间。[![build badge](https://api.travis-ci.org/woboq/qmetaobject-rs.svg?branch=master)](https://travis-ci.org/woboq/qmetaobject-rs)
* [rise-ui](https://github.com/rise-ui/rise) — 简单的基于组件的跨平台的GUI工具包开发美丽的和用户友好的界面。
* [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs) — [nativefiledialog](https://github.com/mlabbe/nativefiledialog) 捆绑
* [Sciter](https://sciter.com/)
  * [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter) — Sciter绑定[![build badge](https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true)](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
* [slint-ui/slint](https://github.com/slint-ui/slint) [[slint](https://crates.io/crates/slint)] — [Slint](https://slint-ui.com) 是一个为嵌入式设备和桌面应用程序有效开发流体图形用户界面的工具包. [![Build Status](https://github.com/slint-ui/slint/workflows/CI/badge.svg?branch=master)](https://github.com/slint-ui/slint/actions?query=workflow%3ACI)
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) — 建立更小、更快,更安全的桌面应用程序与web前端,由[WRY](https://github.com/tauri-apps/wry). [![test library](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)
* [tauri-apps/wry](https://github.com/tauri-apps/wry) - Webview渲染库.

### 图像处理 Image processing
> 图像处理

* [abonander/img_hash](https://github.com/abonander/img_hash) — 感性形象哈希和比较平等和相似性。[![Build Status](https://api.travis-ci.org/abonander/img_hash.svg?branch=master)](https://travis-ci.org/abonander/img_hash)
* [image-rs/image](https://github.com/image-rs/image) — 基本的图像处理函数和方法从图像格式转换[![build badge](https://api.travis-ci.org/image-rs/image.svg?branch=master)](https://travis-ci.org/image-rs/image)
* [image-rs/imageproc](https://github.com/image-rs/imageproc) — 一个图像处理库,基于图像库。[![Build Status](https://api.travis-ci.org/image-rs/imageproc.svg?branch=master)](https://travis-ci.org/image-rs/imageproc)
* [rust-cv/cv](https://github.com/rust-cv/cv) — 生锈的简历是一个项目来实现计算机视觉算法,抽象的系统生锈。[no_std] 在可能的情况下被支持. ![build badge](https://github.com/rust-cv/cv/workflows/tests/badge.svg)
* [teovoinea/steganography](https://github.com/teovoinea/steganography) [[steganography](https://crates.io/crates/steganography)] — 一个简单的隐写术的图书馆[![build badge](https://api.travis-ci.org/teovoinea/steganography.svg?branch=master)](https://travis-ci.org/teovoinea/steganography)
* [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) — 生锈的绑定OpenCV[![build badge](https://api.travis-ci.org/twistedfall/opencv-rust.svg?branch=cv2)](https://travis-ci.org/twistedfall/opencv-rust)

### 语言规范 Language specification
> 语言规范

* [shnewto/bnf](https://github.com/shnewto/bnf) — 一个库解析Backus-Naur上下文无关语法形式。[![build badge](https://api.travis-ci.org/shnewto/bnf.svg?branch=master)](https://travis-ci.org/shnewto/bnf)

### 日志记录 Logging
> 日志记录

[[log](https://crates.io/keywords/log)]

* [estk/log4rs](https://github.com/estk/log4rs) — 高度可配置的日志框架仿照Java的Logback和log4j库[![CircleCI](https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)
* [jesusprubio/leg](https://github.com/jesusprubio/leg) — 优雅的打印对懒惰的开发者。让你的综合领先指标更好的以最小的努力。[![Build Status](https://github.com/jesusprubio/leg/workflows/CI/badge.svg)](https://github.com/jesusprubio/leg/actions/workflows/ci.yml)
* [rbatis/fast_log](https://github.com/rbatis/fast_log) — 锈异步日志高性能异步日志记录[![Build Status](https://api.travis-ci.com/rbatis/fast_log.svg?branch=master)](https://travis-ci.org/rbatis/fast_log)
* [rust-lang/log](https://github.com/rust-lang/log) — 日志实现生锈[![Build Status](https://api.travis-ci.org/rust-lang/log.svg?branch=master)](https://travis-ci.org/rust-lang/log)
* [seanmonstar/pretty-env-logger](https://github.com/seanmonstar/pretty-env-logger) — 一个漂亮的,易于使用的记录器生锈。[![Build Status](https://api.travis-ci.org/seanmonstar/pretty-env-logger.svg?branch=master)](https://travis-ci.org/seanmonstar/pretty-env-logger)
* [slog-rs/slog](https://github.com/slog-rs/slog) — 结构化、可组合测井的生锈[![Build Status](https://api.travis-ci.org/slog-rs/slog.svg?branch=master)](https://travis-ci.org/slog-rs/slog)
* [tokio-rs/tracing](https://github.com/tokio-rs/tracing) — 一个应用程序跟踪async-aware结构化框架日志级别,错误处理,指标等等[![Build Status](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)

### Macro Macro
> Macro

* cute
  * [mattgathu/cute](https://github.com/mattgathu/cute) — 宏观的Python-esque列表理解生锈。[![Build Status](https://api.travis-ci.org/mattgathu/cute.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
* [Linq-in-Rust](https://github.com/StardustDL/Linq-in-Rust) - 类似C#-LINQ表达式的宏和方法. [![CI](https://github.com/StardustDL/Linq-in-Rust/workflows/CI/badge.svg?branch=master)](https://github.com/StardustDL/Linq-in-Rust/actions?query=workflow%3ACI)

### 标记语言 Markup language
> 标记语言

* CommonMark
  * [raphlinus/pulldown-cmark](https://github.com/raphlinus/pulldown-cmark) — [CommonMark](https://commonmark.org/) Rust中的解析器

### 移动 Mobile
> 移动

* 安卓/iOS
  * [ivanschuetz/rust_android_ios](https://github.com/ivanschuetz/rust_android_ios) — 使用共享的铁锈自由的一个例子分别为Android和iOS使用rust-swig和cbindgen。
* 通用型
  * [Geal/rust_on_mobile](https://github.com/Geal/rust_on_mobile)
* iOS
  * [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) — 货物脂肪子命令会自动创建一个通用的iOS应用程序库使用。[![build badge](https://api.travis-ci.org/TimNN/cargo-lipo.svg?branch=master)](https://travis-ci.org/TimNN/cargo-lipo)

### 网络编程 Network programming
> 网络编程

* 蓝牙
  * [bluez/bluer](https://github.com/bluez/bluer) [[bluer](https://crates.io/crates/bluer)] — 官方BlueZ绑定生锈。[![build badge](https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)
* CoAP
  * [Covertness/coap-rs](https://github.com/Covertness/coap-rs) — 一个[Constrained Application Protocol(CoAP)](https://datatracker.ietf.org/doc/html/rfc7252) 用于Rust的库. [![build badge](https://api.travis-ci.org/Covertness/coap-rs.svg?branch=master)](https://travis-ci.org/Covertness/coap-rs)
* Docker
  * [fussybeaver/bollard](https://github.com/fussybeaver/bollard) — 码头工人守护进程API生锈
* FTP
  * [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp) — 一个[FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) 用于Rust的客户端 [![build badge](https://api.travis-ci.org/mattnenterprise/rust-ftp.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-ftp)
* gRPC
  * [tikv/grpc-rs](https://github.com/tikv/grpc-rs) — gRPC库锈建立在C核心库和期货[![Build Status](https://api.travis-ci.org/tikv/grpc-rs.svg?branch=master)](https://travis-ci.org/tikv/grpc-rs)
* HTTP
  * [Hurl](https://github.com/Orange-OpenSource/hurl) — 运行和测试与纯文本和libcurl HTTP请求[![CI](https://github.com/Orange-OpenSource/hurl/workflows/CI/badge.svg)](https://github.com/Orange-OpenSource/hurl/actions)
* IPNetwork
  * [achanda/ipnetwork](https://github.com/achanda/ipnetwork) — 一个图书馆与IP网络在纯生锈[![build badge](https://api.travis-ci.org/achanda/ipnetwork.svg?branch=master)](https://travis-ci.org/achanda/ipnetwork)
  * [candrew/netsim](https://github.com/canndrew/netsim) — 锈图书馆网络仿真和测试[![build badge](https://api.travis-ci.org/canndrew/netsim.svg?branch=master)](https://travis-ci.org/canndrew/netsim)
  * [jesusprubio/online](https://github.com/jesusprubio/online) — 库来检查你的网络连接[![CI](https://github.com/jesusprubio/online/actions/workflows/ci.yml/badge.svg)](https://github.com/jesusprubio/online/actions/workflows/ci.yml)
* Low level
  * [actix/actix](https://github.com/actix/actix) — 演员库生锈[![build badge](https://api.travis-ci.org/actix/actix.svg?branch=master)](https://travis-ci.org/actix/actix)
  * [dylanmckay/protocol](https://github.com/dylanmckay/protocol) — 定制的TCP / UDP协议定义
  * [libpnet/libpnet](https://github.com/libpnet/libpnet) — 一个跨平台、低水平网络[![build badge](https://api.travis-ci.org/libpnet/libpnet.svg?branch=master)](https://travis-ci.org/libpnet/libpnet)
  * [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) — 一个独立的、事件驱动的TCP / IP堆栈是专为裸机,实时系统[![build badge](https://api.travis-ci.org/smoltcp-rs/smoltcp.svg?branch=master)](https://travis-ci.org/smoltcp-rs/smoltcp)
  * [tokio-rs/tokio](https://github.com/tokio-rs/tokio) — 快速发展的网络应用程序框架和高度可伸缩的生产部署客户端和服务器。
* message-io
  * [lemunozm/message-io](https://github.com/lemunozm/message-io) — 事件驱动的消息库来构建网络应用程序容易和快速。支持TCP、UDP和WebSockets。[![build badge](https://img.shields.io/github/workflow/status/lemunozm/message-io/message-io%20ci)](https://github.com/lemunozm/message-io/actions?query=workflow%3A%22message-io+ci%22)
* MQTT
  * [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt) - 一个供开发人员建立与 "中国 "通信的应用程序的库。 [MQTT protocol](https://mqtt.org) 通过TCP和WebSockets，有或没有TLS. [![Build and Test](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) — [nanomsg](https://nanomsg.org/) 捆绑 [![build badge](https://api.travis-ci.org/thehydroimpulse/nanomsg.rs.svg?branch=master)](https://travis-ci.org/thehydroimpulse/nanomsg.rs)
* NATS
  * [nats-io/nats.rs](https://github.com/nats-io/nats.rs) — NATS锈端,云本地消息传递系统。[![Build Status](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)
* Nng
  * [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) [[Nng](https://crates.io/crates/nng)] — [Nng (nanomsg v2)](https://nng.nanomsg.org/index.html) 捆绑 [![build badge](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
* NNTP
  * [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp) [[nntp](https://crates.io/crates/nntp)] — 一个[NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol)用于Rust的客户端 [![build badge](https://api.travis-ci.org/mattnenterprise/rust-nntp.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-nntp)
* P2P
  * [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p) — 铁锈libp2p网络栈的实现。[![Circle CI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
* POP3
  * [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3) [[pop3](https://crates.io/crates/pop3)] — 一个[POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) 用于Rust的客户端 [![build badge](https://api.travis-ci.org/mattnenterprise/rust-pop3.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-pop3)
* QUIC
  * [cloudflare/quiche](https://github.com/cloudflare/quiche) — cloudflare的实现QUIC传输协议和HTTP / 3 ![build](https://img.shields.io/github/workflow/status/cloudflare/quiche/Stable)
  * [mozilla/neqo](https://github.com/mozilla/neqo) — 的实现QUIC写在生锈
  * [quinn-rs/quinn](https://github.com/quinn-rs/quinn) — 期货QUIC实现生锈[![build badge](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
* Raknet
  * [b23r0/rust-raknet](https://github.com/b23r0/rust-raknet) — RakNet协议实现的生锈[![Build Status](https://img.shields.io/github/workflow/status/b23r0/rust-raknet/Rust)](https://github.com/b23r0/rust-raknet/actions/workflows/rust.yml)
* RPC
  * [ENQT-GmbH/remoc](https://github.com/ENQT-GmbH/remoc) [[remoc](https://crates.io/crates/remoc)] - Remoc提供频道(广播，mpsc, oneshot，观看)类似于东京的和特征呼叫任何远程传输. [![build badge](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml)
  * [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs) — 一个RPC库为发展中microservices容易生锈和简单的方法。[![build badge](https://api.travis-ci.org/smallnest/rpcx-rs.svg?branch=master)](https://travis-ci.org/smallnest/rpcx-rs)
* Socket.io
  * [1c3t3a/rust-socketio](https://github.com/1c3t3a/rust-socketio) [[rust_socketio](https://crates.io/crates/rust_socketio)] — 一个实现的[socket.io](https://socket.io) 用Rust编写的客户端. [![build badge](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml/badge.svg)](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml)
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) — [libssh2](https://www.libssh2.org/) 捆绑 [![build badge](https://api.travis-ci.com/alexcrichton/ssh2-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/ssh2-rs)
  * [Thrussh](https://pijul.org/thrussh) [[thrussh](https://crates.io/crates/thrussh)] — SSH库从头写在生锈,支持[libsodium](https://doc.libsodium.org/)
* Stomp
  * [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs) — 一个[STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) Rust中的客户端实现 [![build badge](https://api.travis-ci.org/zslayton/stomp-rs.svg?branch=master)](https://travis-ci.org/zslayton/stomp-rs)
* ZeroMQ
  * [erickt/rust-zmq](https://github.com/erickt/rust-zmq) — [ZeroMQ](https://zeromq.org/) 绑定 [![build badge](https://api.travis-ci.org/erickt/rust-zmq.svg?branch=master)](https://travis-ci.org/erickt/rust-zmq)

### 解析 Parsing
> 解析

* [Folyd/robotstxt](https://github.com/Folyd/robotstxt) - Google robots.txt解析器和匹配器C++库的本地Rust移植。
* [freestrings/jsonpath](https://github.com/freestrings/jsonpath) — [JsonPath](https://goessner.net/articles/JsonPath/) 用Rust编写的引擎。也支持Webassembly和Javascript [![Build Status](https://api.travis-ci.org/freestrings/jsonpath.svg?branch=master)](https://travis-ci.org/freestrings/jsonpath)
* [Geal/nom](https://github.com/Geal/nom) — 解析器组合子库[![build badge](https://api.travis-ci.org/Geal/nom.svg?branch=master)](https://travis-ci.org/Geal/nom)
* [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) — 解析表达式语法解析器生成器(挂钩)
* [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) — LR(1)解析器生成器的生锈[![Build status](https://api.travis-ci.org/lalrpop/lalrpop.svg?branch=master)](https://travis-ci.org/lalrpop/lalrpop)
* [m4rw3r/chomp](https://github.com/m4rw3r/chomp) – 一个快速的单体式解析器组合器 [![build badge](https://api.travis-ci.org/m4rw3r/chomp.svg?branch=master)](https://travis-ci.org/m4rw3r/chomp)
* [Marwes/combine](https://github.com/Marwes/combine) — 解析器组合子库[![build badge](https://api.travis-ci.org/Marwes/combine.svg?branch=master)](https://travis-ci.org/Marwes/combine)
* [nrc/zero](https://github.com/nrc/zero) [[zero](https://crates.io/crates/zero/)] — 零二进制数据的解析
* [pest-parser/pest](https://github.com/pest-parser/pest) — 优雅的解析器[![Build Status](https://api.travis-ci.org/pest-parser/pest.svg?branch=master)](https://travis-ci.org/pest-parser/pest)
* [ptal/oak](https://github.com/ptal/oak) — 盯住类型解析器生成器(编译器插件)
* [replicadse/wavefront_rs](https://github.com/replicadse/wavefront_rs) — 波阵面OBJ格式的解析器。[![crates.io](https://img.shields.io/crates/v/wavefront_rs.svg)](https://crates.io/crates/wavefront_rs) [![crates.io](https://img.shields.io/crates/d/wavefront_rs?label=crates.io%20downloads)](https://crates.io/crates/wavefront_rs) [![build badge](https://github.com/replicadse/wavefront_rs/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/wavefront_rs/actions)
* [s-panferov/queryst](https://github.com/s-panferov/queryst) — 锈启发的查询字符串解析库[gs](https://github.com/ljharb/qs#readme)
* [softdevteam/grmtools](https://github.com/softdevteam/grmtools/) - 一个具有更好的纠错功能的LR解析器

### 外围设备 Peripherals
> 外围设备

* 串行端口
  * [Susurrus/serialport-rs](https://gitlab.com/susurrus/serialport-rs) [[serialport](https://crates.io/crates/serialport)] — 一个跨平台的库,提供对一个串行端口的访问

### 特定于平台的 Platform specific
> 特定于平台的

* 跨平台
  * [svartalf/rust-battery](https://crates.io/crates/battery) — 跨平台信息的笔记本电脑电池[![build badge](https://api.travis-ci.org/svartalf/rust-battery.svg?branch=master)](https://travis-ci.org/svartalf/rust-battery)
  * [vityafx/thread-priority](https://github.com/vityafx/thread-priority/) - 简单、跨平台的线程优先级管理. [![CI](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/thread-priority.svg)](https://crates.io/crates/thread-priority)
* FreeBSD
  * [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) [[jail](https://crates.io/crates/jail)] — 锈FreeBSD监狱图书馆的实现
* Linux
  * [arvancloud/nginx-rs](https://github.com/arvancloud/nginx-rs) — [Nginx](https://www.nginx.com) 捆绑 [![build badge](https://api.travis-ci.org/arvancloud/nginx-rs.svg?branch=master)](https://travis-ci.org/arvancloud/nginx-rs)
  * [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs) — [inotify](https://en.wikipedia.org/wiki/Inotify) 捆绑 [![Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)
  * [pop-os/distinst](https://github.com/pop-os/distinst/) — Linux发行版安装程序
  * [yaa110/rust-iptables](https://github.com/yaa110/rust-iptables) [[iptables](https://crates.io/crates/iptables)] — [iptables](https://www.netfilter.org/projects/iptables/index.html) 捆绑 [![build badge](https://api.travis-ci.org/yaa110/rust-iptables.svg?branch=master)](https://travis-ci.org/yaa110/rust-iptables)
* Unix-like
  * [nix-rust/nix](https://github.com/nix-rust/nix) — 类unix API绑定[![Cirrus Build Status](https://api.cirrus-ci.com/github/nix-rust/nix.svg)](https://cirrus-ci.com/github/nix-rust/nix)
  * [rustix](https://github.com/bytecodealliance/rustix) — 安全的铁锈绑定POSIX / Unix / Linux / Winsock2系统调用[![Actions Status](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions?query=workflow%3ACI)
  * [zargony/fuse-rs](https://github.com/zargony/fuse-rs) — [FUSE](https://github.com/libfuse/libfuse) 捆绑
* Windows
  * [retep998/winapi-rs](https://github.com/retep998/winapi-rs) — Windows API绑定[![Rust](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml/badge.svg?branch=dev)](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml)

### 脚本 Scripting
> 脚本

[[scripting](https://crates.io/keywords/scripting)]

* [duckscript](https://crates.io/crates/duckscript) — [Simple, extendable and embeddable scripting language.](https://github.com/sagiegurari/duckscript) [![build badge](https://github.com/sagiegurari/duckscript/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/duckscript/actions)
* [fleabitdev/gamelisp](https://github.com/fleabitdev/glsp) — 锈游戏开发的LISP-lisk脚本语言
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon) —  一个静态类型,函数式编程语言
* [KusionStack/KCLVM](https://github.com/KusionStack/KCLVM) - 一种基于约束的记录和功能语言，主要用于配置和政策场景中.
* [metacall/core](https://github.com/metacall/core) [[metacall](https://crates.io/crates/metacall)] — 跨平台通晓多种语言的运行时支持NodeJS, JavaScript,打印稿,Python、Ruby、C[![build badge](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)
* [mun](https://github.com/mun-lang/mun) — 编译静态类型的脚本语言,头等舱热重载的支持[![build badge](https://api.travis-ci.org/mun-lang/mun.svg?branch=master)](https://travis-ci.org/mun-lang/mun)
* [murarth/ketos](https://github.com/murarth/ketos) — 一种函数式编程语言Lisp方言作为脚本和扩展语言生锈
* [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) — 一个生锈的动态脚本语言
* [rhaiscript/rhai](https://github.com/rhaiscript/rhai) — 小和快速嵌入式脚本语言类似于JavaScript和生锈[![build badge](https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)
* [rune-rs/rune](https://github.com/rune-rs/rune) — 生锈的可嵌入的动态编程语言

### 模拟 Simulation
> 模拟

[[模拟](https://crates.io/keywords/simulation)]

* [nyx-space](https://crates.io/crates/nyx-space) - 高保真、快速、可靠和经过验证的天体动力学工具包库，用于航天器任务设计和轨道确定 [![Build Status](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)

### 任务调度 Task scheduling
> 任务调度

* [delay-timer](https://github.com/BinChengZhao/delay-timer) — 管理时间的延迟任务。像crontab,但异步任务是可能的。
  [![Build](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg)](
  https://github.com/BinChengZhao/delay-timer/actions)


### 模板引擎 Template engine
> 模板引擎

* Handlebars
  * [botika/yarte](https://github.com/botika/yarte) — Yarte Y代表* * * *等* * * *各异的* * R * * T * * * *科大emplate * * E * * ngine,是最快的模板引擎。[![Build Status](https://api.travis-ci.org/botika/yarte.svg?branch=master)](https://travis-ci.org/botika/yarte)
  * [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) — 车把模板引擎与继承,自定义辅助支持。[![build badge](https://api.travis-ci.org/sunng87/handlebars-rust.svg?branch=master)](https://travis-ci.org/sunng87/handlebars-rust)
* HTML
  * [djc/askama](https://github.com/djc/askama) — 根据金贾的模板渲染引擎[![build badge](https://api.travis-ci.org/djc/askama.svg?branch=master)](https://travis-ci.org/djc/askama)
  * [kaj/ructe](https://github.com/kaj/ructe) — HTML模板系统生锈[![build badge](https://api.travis-ci.org/kaj/ructe.svg?branch=master)](https://travis-ci.org/kaj/ructe)
  * [Keats/tera](https://github.com/Keats/tera) — 模板引擎基于Jinja2和Django模板语言。[![Actions Status](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)
  * [lambda-fairy/maud](https://github.com/lambda-fairy/maud) — 编译时HTML模板[![build badge](https://api.travis-ci.org/lambda-fairy/maud.svg?branch=master)](https://travis-ci.org/lambda-fairy/maud)
  * [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs) — 编译时HTML模板[![build badge](https://api.travis-ci.org/Stebalien/horrorshow-rs.svg?branch=master)](https://travis-ci.org/Stebalien/horrorshow-rs)
* Mustache
  * [rustache/rustache](https://github.com/rustache/rustache) — [![build badge](https://api.travis-ci.org/rustache/rustache.svg?branch=master)](https://travis-ci.org/rustache/rustache)

### 文本处理 Text processing
> 文本处理

* [becheran/wildmatch](https://github.com/becheran/wildmatch) [[wildmatch](https://crates.io/crates/wildmatch)] — 简单的字符串匹配questionmark star-wildcard运营商[![Actions Status](https://github.com/becheran/wildmatch/workflows/Build/badge.svg?branch=master)](https://github.com/becheran/wildmatch/actions)
* [BurntSushi/suffix](https://github.com/BurntSushi/suffix) — 线性时间后缀数组建设(Unicode支持)[![build badge](https://api.travis-ci.org/BurntSushi/suffix.svg?branch=master)](https://travis-ci.org/BurntSushi/suffix)
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) — 弹性选项卡(即停止。、文本列对齐)[![build badge](https://api.travis-ci.org/BurntSushi/tabwriter.svg?branch=master)](https://travis-ci.org/BurntSushi/tabwriter)
* [cpc](https://github.com/probablykasper/cpc) - 解析和计算数学字符串，支持单位和单位转换，从 "1+2 "到 "1%的圆(1光年/14!s到公里/小时)".
* [Daniel-Liu-c0deb0t/triple_accel](https://github.com/Daniel-Liu-c0deb0t/triple_accel) [[triple_accel](https://crates.io/crates/triple_accel)] - 使用SIMD加速的Rust编辑距离程序；支持快速Hamming、Levenshtein、限制性Damerau-Levenshtein等距离计算和字符串搜索 [![build badge](https://github.com/Daniel-Liu-c0deb0t/triple_accel/workflows/Test/badge.svg?branch=master)](https://github.com/Daniel-Liu-c0deb0t/triple_accel/actions)
* [fancy-regex/fancy-regex](https://github.com/fancy-regex/fancy-regex) [[fancy-regex](https://crates.io/crates/fancy-regex)] - 正则表达式的实现旨在支持一套相对丰富的功能，如回看和回溯. [![crates](https://img.shields.io/crates/v/fancy-regex.svg)](https://crates.io/crates/fancy-regex) [![build badge](https://github.com/fancy-regex/fancy-regex/workflows/ci/badge.svg)](https://github.com/fancy-regex/fancy-regex/actions/workflows/ci.yml)
* [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) — 自然语言检测图书馆基于三元模型[![build badge](https://api.travis-ci.org/greyblake/whatlang-rs.svg?branch=master)](https://travis-ci.org/greyblake/whatlang-rs)
* [Lucretiel/joinery](https://github.com/Lucretiel/joinery) [[joinery](https://crates.io/crates/joinery)] – 通用的字符串+可迭代连接 [![build badge](https://api.travis-ci.org/Lucretiel/joinery.svg?branch=master)](https://travis-ci.org/Lucretiel/joinery)
* [mgeisler/textwrap](https://github.com/mgeisler/textwrap) [[textwrap](https://crates.io/crates/textwrap)] — 文本自动换行(支持断字)[![build badge](https://api.travis-ci.org/mgeisler/textwrap.svg?branch=master)](https://travis-ci.org/mgeisler/textwrap)
* [ps1dr3x/easy_reader](https://github.com/ps1dr3x/easy_reader) — 读者可以向前,向后和随机导航通过巨大的文件没有使用迭代器[![build badge](https://api.travis-ci.org/ps1dr3x/easy_reader.svg?branch=master)](https://travis-ci.org/ps1dr3x/easy_reader)
* [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams) [[ngrams](https://crates.io/crates/ngrams)] — 构造[n-grams](https://en.wikipedia.org/wiki/N-gram) 从任意的迭代器 [![build badge](https://api.travis-ci.org/pwoolcoc/ngrams.svg?branch=master)](https://travis-ci.org/pwoolcoc/ngrams)
* [rust-lang/regex](https://github.com/rust-lang/regex) — 正则表达式(RE2公司风格)[![build badge](https://api.travis-ci.com/rust-lang/regex.svg?branch=master)](https://travis-ci.org/rust-lang/regex)
* [strsim-rs](https://crates.io/crates/strsim) — 字符串相似性度量[![build badge](https://api.travis-ci.org/dguo/strsim-rs.svg?branch=master)](https://travis-ci.org/dguo/strsim-rs)
* [yaa110/rake-rs](https://github.com/yaa110/rake-rs) [[rake](https://crates.io/crates/rake)] — RAKE算法的多语言实现对生锈[![build badge](https://api.travis-ci.org/yaa110/rake-rs.svg?branch=master)](https://travis-ci.org/yaa110/rake-rs)

### 文本搜索 Text search
> 文本搜索

* [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs) [[simsearch](https://crates.io/crates/simsearch)] — 简单、轻量级的模糊搜索引擎,在内存中,寻找类似的字符串
* [BurntSushi/fst](https://github.com/BurntSushi/fst) [[fst](https://crates.io/crates/fst)] — [![build badge](https://api.travis-ci.org/BurntSushi/fst.svg?branch=master)](https://travis-ci.org/BurntSushi/fst)
* [CurrySoftware/perlin](https://github.com/CurrySoftware/perlin) [[perlin](https://crates.io/crates/perlin)]
* [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch) — 超相关、即时和typo-tolerant全文搜索API。[![Build Status](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)
* [tantivy](https://github.com/quickwit-oss/tantivy) [[tantivy](https://crates.io/crates/tantivy)] — horse-speed全文搜索引擎库编写的生锈。[![Build Status](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)

### 不安全的 Unsafe
> 不安全的

* [zerocopy](https://crates.io/crates/zerocopy) — 公用事业安全对任意字节序列作为本地锈蚀类型

### 虚拟化 Virtualization
> 虚拟化

* [beneills/quantum](https://github.com/beneills/quantum) — 先进的铁锈量子计算机模拟器[![build badge](https://api.travis-ci.org/beneills/quantum.svg?branch=master)](https://travis-ci.org/beneills/quantum)
* [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) — 一个独立的运行时WebAssembly[![Build Status](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)](https://github.com/bytecodealliance/wasmtime/actions?query=workflow%3ACI)
* [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) CrOSVM — 让Chrome OS上运行Linux应用程序在一个快速、安全的虚拟化环境
* [oxidecomputer/propolis](https://github.com/oxidecomputer/propolis) - 用于illumos bhyve内核模块的基于Rust的用户空间程序
* [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs) — 硬件加速虚拟化OS X
* [unicorn-rs/unicorn-rs](https://github.com/unicorn-rs/unicorn-rs) — 锈绑定的独角兽CPU仿真器[![Build Status](https://api.travis-ci.org/ekse/unicorn-rs.svg?branch=master)](https://travis-ci.org/ekse/unicorn-rs)

### 网络编程 Web programming
> 网络编程

See also [Are we web yet?](https://www.arewewebyet.org) 和 [Rust web framework comparison](https://github.com/flosse/rust-web-framework-comparison).

* 客户端/WASM
  * [cargo-web](https://crates.io/crates/cargo-web) — 客户端网络的货物子命令[![Build Status](https://api.travis-ci.org/koute/cargo-web.svg?branch=master)](https://travis-ci.org/koute/cargo-web)
  * [sauron](https://github.com/ivanceras/sauron) - 严格遵守榆树架构的客户端网络框架. [![Build Status](https://api.travis-ci.org/ivanceras/sauron.svg?branch=master)](https://travis-ci.org/ivanceras/sauron)
  * [seed](https://seed-rs.org/) — 一个生锈的框架来创建web应用程序
  * [stdweb](https://crates.io/crates/stdweb) — 一个客户端Web标准库[![Build Status](https://api.travis-ci.org/koute/stdweb.svg?branch=master)](https://travis-ci.org/koute/stdweb)
  * [yew](https://crates.io/crates/yew) — 锈使客户端web应用程序的框架
* HTTP客户端
  * [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) — [libcurl](https://curl.se/libcurl/) 捆绑 [![build badge](https://api.travis-ci.com/alexcrichton/curl-rust.svg?branch=master)](https://travis-ci.org/alexcrichton/curl-rust)
  * [async-graphql](https://github.com/async-graphql/async-graphql) - 一个用Rust实现的GraphQL服务器库 [![Build Status](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-rust.juniper)](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)
  * [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) [[yukikaze](https://crates.io/crates/yukikaze)] — 美丽和优雅Yukikaze基于超小HTTP客户端库。[![build badge](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
  * [graphql-client](https://github.com/graphql-rust/graphql-client) — 类型的,正确GraphQL请求和响应在生锈。[![Github actions Status](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)
  * [hyperium/hyper](https://github.com/hyperium/hyper) — 一个HTTP实现[![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) — 生锈的符合人体工程学的HTTP客户端。[![build badge](https://api.travis-ci.org/seanmonstar/reqwest.svg?branch=master)](https://travis-ci.org/seanmonstar/reqwest)
* HTTP服务器
  * [actix/actix-web](https://github.com/actix/actix-web) — 一个轻量级的异步web框架与websocket支持生锈[![build badge](https://api.travis-ci.org/actix/actix-web.svg?branch=master)](https://travis-ci.org/actix/actix-web)
  * [branca](https://crates.io/crates/branca) — 布兰卡的纯锈实现身份验证和加密API的令牌。[![build badge](https://api.travis-ci.org/return/branca.svg?branch=master)](https://travis-ci.org/return/branca)
  * [carllerche/tower-web](https://github.com/carllerche/tower-web) [[tower-web](https://crates.io/crates/tower-web)] — 一种快速、样板免费,铁锈的web框架[![build badge](https://api.travis-ci.org/carllerche/tower-web.svg?branch=master)](https://travis-ci.org/carllerche/tower-web)
  * [danclive/sincere](https://github.com/danclive/sincere) — 生锈的微web框架(稳定)基于超和多线程。[![build badge](https://api.travis-ci.org/danclive/sincere.svg?branch=master)](https://travis-ci.org/danclive/sincere)
  * [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt) — JSON Web标记实现在生锈。[![build badge](https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master)](https://travis-ci.org/GildedHonour/frank_jwt)
  * [Gotham](https://github.com/gotham-rs/gotham) — 一个灵活的web框架,不牺牲安全,安全或速度。[![build badge](https://api.travis-ci.org/gotham-rs/gotham.svg?branch=master)](https://travis-ci.org/gotham-rs/gotham)
  * [Graphul](https://github.com/graphul-rs/graphul) — 一个Express-inspired web框架编写的生锈。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/graphul)
  * [handlebars-rust](https://github.com/sunng87/handlebars-rust) — 一个铁web框架中间件。[![build badge](https://api.travis-ci.org/sunng87/handlebars-iron.svg?branch=master)](https://travis-ci.org/sunng87/handlebars-iron)
  * [hyperium/hyper](https://github.com/hyperium/hyper) — 一个HTTP实现[![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [Iron](https://github.com/iron/iron) — middleware-based服务器框架[![build badge](https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master)](https://travis-ci.org/GildedHonour/frank_jwt)
  * [Juniper](https://github.com/graphql-rust/juniper) — GraphQL服务器库生锈[![build badge](https://api.travis-ci.org/graphql-rust/juniper.svg?branch=master)](https://travis-ci.org/graphql-rust/juniper)
  * [miketang84/sapper](https://github.com/miketang84/sapper) — 一个轻量级的web框架建立在异步超,锈语言实现。
  * [Nickel](https://github.com/nickel-org/nickel.rs/) — 灵感来自于[Express](http://expressjs.com/) [![build badge](https://api.travis-ci.org/nickel-org/nickel.rs.svg?branch=master)](https://travis-ci.org/nickel-org/nickel.rs)
  * [Ogeon/rustful](https://github.com/Ogeon/rustful) — 基于rest的web框架生锈[![build badge](https://api.travis-ci.org/Ogeon/rustful.svg?branch=master)](https://travis-ci.org/Ogeon/rustful)
  * [poem-web/poem](https://github.com/poem-web/poem) - 采用Rust编程语言的全功能和易于使用的网络框架. [![CI](https://github.com/poem-web/poem/actions/workflows/ci.yml/badge.svg)](https://github.com/poem-web/poem/actions/workflows/ci.yml)
  * [Rocket](https://github.com/SergioBenitez/Rocket) — 火箭是铁锈web框架(夜间),关注易用性,表达能力,和速度[![build badge](https://api.travis-ci.org/SergioBenitez/Rocket.svg?branch=master)](https://travis-ci.org/SergioBenitez/Rocket)
  * [Rustless](https://github.com/rustless/rustless) — 醒个API micro-framework启发[Grape](https://github.com/ruby-grape/grape) 和 [Hyper](https://github.com/hyperium/hyper) [![build badge](https://api.travis-ci.org/rustless/rustless.svg?branch=master)](https://travis-ci.org/rustless/rustless)
  * [Salvo](https://github.com/salvo-rs/salvo) — 一个易于使用的超级webframework基地和东京。[![build build](https://github.com/salvo-rs/salvo/workflows/CI%20(Linux)/badge.svg?branch=master&event=push)](https://github.com/salvo-rs/salvo/actions)
  * [Saphir](https://github.com/richerarc/saphir) — 累进web框架与底层控制,没有痛苦。
  * [seanmonstar/warp](https://github.com/seanmonstar/warp) — 一个语言,可组合、web服务器框架变形速度。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/warp)
  * [tiny-http](https://github.com/tiny-http/tiny-http) — 低水平HTTP服务器库[![build badge](https://api.travis-ci.org/tiny-http/tiny-http.svg?branch=master)](https://travis-ci.org/tiny-http/tiny-http)
  * [tokio/axum](https://github.com/tokio-rs/axum) - 用Tokio、Tower和Hyper构建的符合人体工程学的模块化网络框架 [![Build badge](https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/tokio-rs/axum/actions/workflows/CI.yml)
  * [tomaka/rouille](https://github.com/tomaka/rouille) — Web框架在生锈[![build badge](https://api.travis-ci.org/tomaka/rouille.svg?branch=master)](https://travis-ci.org/tomaka/rouille)
* 杂项
  * [cargonauts](https://github.com/cargonauts-rs/cargonauts) — web框架用于建筑维护良好构造web应用程序。
  * [causal-agent/scraper](https://github.com/causal-agent/scraper) [[scraper](https://crates.io/crates/scraper)] - 用CSS选择器进行HTML解析和查询。[![Build Status](https://github.com/causal-agent/scraper/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/causal-agent/scraper/actions)
  * [hominee/dyer](https://github.com/hominee/dyer) [[dyer](https://crates.io/crates/dyer)] - dyer是为可靠、灵活、快速的基于请求-响应的服务而设计的，包括数据处理、网络抓取等，提供一些友好、灵活、全面的功能而不影响速度。
  * [juhaku/utoipa](https://github.com/juhaku/utoipa) - 简单、快速、代码优先和编译时生成的Rust的OpenAPI文档 [![crates.io](https://img.shields.io/crates/v/utoipa.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipa) [![Utoipa build](https://github.com/juhaku/utoipa/actions/workflows/build.yaml/badge.svg)](https://github.com/juhaku/utoipa/actions/workflows/build.yaml)
  * [osohq/oso](https://github.com/osohq/oso) [[oso](https://crates.io/crates/oso)] - 一个用于授权的策略引擎，嵌入到你的应用程序中。[![Build Status](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+workflow%3ADevelopment)
  * [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) [[soup](https://crates.io/crates/soup)] - 库类似于Python的BeautifulSoup，旨在使HTML文档的快速和简单的操作和查询。[![构建状态](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  * [pyrossh/rust-embed](https://github.com/pyrossh/rust-embed) — 宏观静态资产嵌入锈二进制
  * [serenity-rs/serenity](https://github.com/serenity-rs/serenity) [[serenity](https://crates.io/crates/serenity)] - 一个用于Discord API的Rust库
  * [softprops/openapi](https://github.com/softprops/openapi) — 一个图书馆openapi规范文件进行处理
  * [svix/svix-webhooks](https://github.com/svix/svix-webhooks) [[svix](https://crates.io/crates/svix)]- 一个用于发送webhooks和验证签名的库.
  * [tbot](https://gitlab.com/SnejUgal/tbot) [[tbot](https://crates.io/crates/tbot)] - 用Rust轻松制作很酷的Telegram机器人 [![pipeline status](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  * [teloxide/teloxide](https://github.com/teloxide/teloxide/) - 用于Rust的优雅的Telegram机器人框架 [![Build Status](https://github.com/teloxide/teloxide/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/teloxide/teloxide/actions)
  * [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) [[select](https://crates.io/crates/select)] — 从HTML文档库中提取有用的数据,适合于web抓取。[![Build Status](https://api.travis-ci.org/utkarshkukreti/select.rs.svg?branch=master)](https://travis-ci.org/utkarshkukreti/select.rs)
* 反向代理
  * [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) [[sozu](https://crates.io/crates/sozu)] — 一个HTTP反向代理 [![CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)
* 静态网站生成器
  * [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) — 静态网站发电机用生锈[![Build Status](https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)
  * [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) [[mdblog](https://crates.io/crates/mdblog)] — 静态网站从减价文件生成器。
  * [getzola/zola](https://github.com/getzola/zola) [[zola](https://www.getzola.org/)] — 一个固执己见的静态网站和所有内置发电机。[![Build Status](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)
  * [grego/blades](https://github.com/grego/blades) [[blades](https://getblades.org/)] — 燃烧的快死的简单的静态网站生成器。
  * [leven-the-blog/leven](https://github.com/leven-the-blog/leven) [[leven](https://crates.io/crates/leven)] — 一个简单的、并行的博客生成器。[![build badge](https://api.travis-ci.org/quadrupleslap/leven.svg?branch=master)](https://travis-ci.org/quadrupleslap/leven)
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs) — 轻量级的、事件驱动的WebSockets生锈[![build badge](https://api.travis-ci.org/housleyjk/ws-rs.svg?branch=stable)](https://travis-ci.org/housleyjk/ws-rs)
  * [rust-websocket](https://github.com/websockets-rs/rust-websocket) — 一个框架来处理WebSocket连接(包括客户端和服务器)[![build badge](https://api.travis-ci.org/websockets-rs/rust-websocket.svg?branch=master)](https://travis-ci.org/websockets-rs/rust-websocket)
  * [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) — 轻量级基于流的WebSocket实现生锈。
  * [vi/websocat](https://github.com/vi/websocat) — CLI交互WebSockets, Netcat功能,旋度和Socat。[![build badge](https://api.travis-ci.org/vi/websocat.svg?branch=master)](https://travis-ci.org/vi/websocat)
  * [vityafx/urlshortener-rs](https://github.com/vityafx/urlshortener-rs) — 一个非常简单的urlshortener库生锈。[![CI](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/urlshortener.svg)](https://crates.io/crates/urlshortener)

## 注册表 Registries
> 注册表允许你将你的Rust库作为crate包发布，与他人公开或私下分享

* [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.com/cargo-registry/) — 完全包管理SaaS管理,以一流的支持公共和私人货物/生锈注册(+其他)。有一个慷慨的免费和开源也是完全免费的。
* [Crates](https://crates.io) — 生锈的官方公共注册中心/货物。
* [w4/chartered](https://github.com/w4/chartered) - 一个私人的、经过认证的、有权限的货物登记册 [![CI](https://github.com/w4/chartered/actions/workflows/ci.yml/badge.svg)](https://github.com/w4/chartered/actions/workflows/ci.yml)

## 资源 Resources
> 资源

* 基准
  * [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs) — 生锈的实现[The Computer Language Benchmarks Game](https://benchmarksgame-team.pages.debian.net/benchmarksgame/) [![build badge](https://api.travis-ci.org/TeXitoi/benchmarksgame-rs.svg?branch=master)](https://travis-ci.org/TeXitoi/benchmarksgame-rs)
* 演讲和演示
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) — 提出的[Julia Evans](https://twitter.com/@b0rk) @ Rustconf 2016.
  * [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) — 提出的[Nicholas Matsakis](https://github.com/nikomatsakis) @ C++Now 2018
  * [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) — 提出的[Michael Gattozzi](https://github.com/mgattozzi) @ RustConf 2017
* [Discover Rust Libraries & Code Snippets](https://kandi.openweaver.com/explore/rust) - 精心策划的Kandi上的Rust图书馆、作者、工具包、教程和学习资源列表
* 学习
  * [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming) - 社区策划的关于Rust的现场直播列表.
  * [awesome-rust-mentors](https://rustbeginners.github.io/awesome-rust-mentors/) — 有用的铁锈导师愿意承担学员列表和eductate他们关于生锈和编程。
  * [Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/)
  * [CodeCrafters.io](https://app.codecrafters.io/tracks/rust) — 构建自己的复述,Git,码头工人,或者SQLite生锈
  * [Easy Rust](https://github.com/Dhghomon/easy_rust) - Learn Rust in easy English.
  * [exercism.org](https://exercism.org/tracks/rust) — 编程练习,帮助你学习新概念生锈。
  * [Hands-on Rust](https://pragprog.com/titles/hwrust/hands-on-rust/) - 通过制作游戏来学习Rust的实践指南--作者 [Herbert Wolverson](https://github.com/thebracket/) (paid)
  * [Idiomatic Rust](https://github.com/mre/idiomatic-rust) —  同行评议的文章/谈判/回购教惯用生锈。
  * [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/) — 深入探讨生锈的内存管理规则,通过实施一些不同类型的列表结构。
  * [Little Book of Rust Books](https://lborb.github.io/book/) - 策划的锈蚀书籍和方法列表
  * [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust) — 推荐的资源列表由编程社区投票。
  * [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) - 这是一本介绍Rust语言的书。
  * [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
  * [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) — 一组简单的例子,展示良好的实践来完成常见的编程任务,使用生锈的板条箱的生态系统。
  * [Rust for professionals](https://overexact.com/rust-for-professionals/) — 有经验的软件开发人员的快速介绍生锈。
  * [Rust Gym](https://github.com/warycat/rustgym) - 用Rust解决的编码面试问题大集合.
  * [Rust in Action](https://www.manning.com/books/rust-in-action) — 实践指南系统编程和生锈[Tim McNamara](https://github.com/timClicks) (paid)
  * [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) — 一个系列的视频[Carol Nichols](https://github.com/carols10cents) and [Jake Goulding](https://github.com/shepmaster) (paid)
  * [Rust Language Cheat Sheet](https://cheats.rs/)
  * [Rust Online Courses at Classpert](https://classpert.com/search/rust) — 锈在线课程的列表(支付)Classpert在线课程搜索
  * [Rust Tiếng Việt](https://rust-tieng-viet.github.io/) - 学习越南语的锈蚀.
  * [rust-how-do-i-start](https://github.com/jondot/rust-how-do-i-start) - 一个致力于回答这个问题的 repo。"那么，Rust。我应该如何开始？"。一个只为初学者精心挑选的资源和学习轨道.
  * [rust-learning](https://github.com/ctjhoa/rust-learning) — 一组有用的参考资料以了解生锈
  * [Rustlings](https://github.com/rust-lang/rustlings) — 小练习让你用来阅读和写作生锈的代码
  * [Rusty CS](https://github.com/AbdesamedBendjeddou/Rusty-CS) - 计算机科学课程，有助于在Rust中练习所学的学术知识
  * [stdx](https://github.com/brson/stdx) — 学习这些箱子第一次为一个扩展性病
  * [Take your first steps with Rust](https://learn.microsoft.com/en-us/training/paths/rust-first-steps/) - 奠定你在Rust中建立快速和有效的程序所需的知识基础.
  * [宾夕法尼亚大学的Comp Sci Rust编程课程](http://cis198-2016s.github.io/schedule/)
* 播客
  * [New Rustacean](https://newrustacean.com) — 播客学习生锈
  * [Rustacean Station](https://rustacean-station.org/) — 一个社区项目创建播客内容生锈
* [Rust Design Patterns](https://github.com/rust-unofficial/patterns)
* [Rust Guidelines](http://aturon.github.io/)
* [Rust Servers, Services and Apps - MEAP](https://www.manning.com/books/rust-servers-services-and-apps) - 在Rust中构建后端服务器、服务和前端，以获得快速、可靠和可维护的应用程序.
* [Rust Subreddit](https://www.reddit.com/r/rust/) — subreddit(论坛)锈病相关问题,文章和资源发布和讨论
* [RustBooks](https://github.com/sger/RustBooks) — RustBooks列表
* [RustCamp 2015 Talks](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t)
* [RustViz](https://github.com/rustviz/rustviz) — 从简单的铁锈程序生成可视化帮助用户更好地理解铁锈一生和借贷机制。

## 许可证 License
> 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
