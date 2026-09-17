### Jabo

前端工程师。把在生产项目里踩过的坑，做成别人能直接用的东西。

> 一条原则：能用一行引入的，不让人配三个插件；能自动做的，不让人手动 `import`。

---

#### 播放器组件（已发布 npm）

**[vue-super-player](https://github.com/Jabo2017/vue-super-player)** &nbsp;·&nbsp; [npm](https://www.npmjs.com/package/vue-super-player) &nbsp;·&nbsp; [在线演示](https://jabo2017.github.io/vue-super-player/)

多内核视频播放器（Vue 3 + TypeScript）：原生 / hls.js / flv.js / Aliplayer 四个内核可插拔，按播放地址自动选内核，props / 事件 / 方法全统一。hls.js 与 flv.js 走 CDN 懒加载，主包 gzip 仅 4KB。

```bash
npm i vue-super-player
```

**[vue-aliplay-player](https://github.com/Jabo2017/vue-aliplay-player)** &nbsp;·&nbsp; [npm](https://www.npmjs.com/package/vue-aliplay-player) &nbsp;·&nbsp; [在线演示](https://jabo2017.github.io/vue-aliplay-player/)

阿里云 Aliplayer 的 Vue 3 封装：TypeScript 全类型、SDK CDN 懒加载（零依赖打包）、样式运行时自动注入；支持点播 / 直播 / `vid`+`playauth` / 截图水印 / License 接入。

```bash
npm i vue-aliplay-player
```

#### 工程化与工具

**[vue2-migration-scanner](https://github.com/Jabo2017/vue2-migration-scanner)** &nbsp;·&nbsp; [npm](https://www.npmjs.com/package/vue2-migration-scanner) &nbsp;·&nbsp; [示例报告](https://jabo2017.github.io/vue2-migration-scanner/)

Vue 2 迁移债务扫描器：检出 10 类遗留写法（生命周期 / `.sync` / `slot-scope` / `filters` / 全局 API / mixins …）与依赖风险，输出「文件:行号」清单，并用 MDI 指数把迁移成本量化成数字。零依赖，`npx` 直接跑。

```bash
npx vue2-migration-scanner
```

**[vue3-rspack-starter](https://github.com/Jabo2017/vue3-rspack-starter)** &nbsp;·&nbsp; [在线演示](https://jabo2017.github.io/vue3-rspack-starter/)

Vue 3 + TypeScript + Rspack 起步模板，内置 Pinia、vitest 与 Pages 部署配置。

#### AI 应用

**[translate-project](https://github.com/Jabo2017/translate-project)** &nbsp;·&nbsp; [在线演示](https://jabo2017.github.io/translate-project/)

多模式翻译工作台：极速翻译（MyMemory）+ AI 翻译（Novita LLM 流式输出），Vue 3 / TypeScript / Vite。

**[automatic-resume](https://github.com/Jabo2017/automatic-resume)** &nbsp;·&nbsp; [在线演示](https://jabo2017.github.io/automatic-resume/)

Markdown 简历编辑器 + 打字机式自动书写预览。

---

#### 技术栈

![Vue](https://img.shields.io/badge/Vue_3-42b883?style=flat-square&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646cff?style=flat-square&logo=vite&logoColor=white)
![Rspack](https://img.shields.io/badge/Rspack-ff6b00?style=flat-square&logo=rspack&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5fa04e?style=flat-square&logo=nodedotjs&logoColor=white)
![Vue 2 迁移](https://img.shields.io/badge/Vue_2_%E8%BF%81%E7%A7%BB-35495e?style=flat-square&logo=vuedotjs&logoColor=white)

---

#### 正在关注

- **Vue 2 → Vue 3 的大规模迁移**：怎么把「感觉要很久」变成「有数字的方案」 —— [vue2-migration-scanner](https://github.com/Jabo2017/vue2-migration-scanner)
- **视频播放**：HLS / FLV / 点播 / 直播 的多内核统一抽象
- **AI 落地**：在真实业务里用上模型能力，而不是做个 demo
