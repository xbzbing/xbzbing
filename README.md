## Hello Word

近期沉迷于做 DSH 的小玩具

## About me

搞安全的全栈工程师，后端 PHP、Python、Java、Go，前端只会早年的手搓 jQuery 和 Vue，但现在有 AI 了🙂

## DSH 小玩具

「一切皆插件」的设计可玩性很高，我直接放弃了 ClaudeCode 转投 DSH，顺手做了一堆小玩具：

1. **[dsh-auth-gateway](https://github.com/xbzbing/dsh-auth-gateway)**：为 DSH 增加远程访问能力，支持账密+TOTP。公司支持开发机远程访问，以前 ssh+tmux 属实有些厌倦了，还是 GUI 看着舒服，不舒服的地方直接改。
2. **[dsh-git-panel](https://github.com/xbzbing/dsh-git-panel)**：为 DSH 增加一个 IDEA 风格的 Git 面板，我不太喜欢侧边栏，电脑屏幕上还是工作区面板看着舒服。主要功能是 Git 管理、变更审查、代码阅读，主要作用是缓解人类在 AI Coding 时的焦虑情绪，增加一点项目的参与感。
3. **[dsh-openviking-manager](https://github.com/xbzbing/dsh-openviking-manager)**：字节的长记忆产品[OpenViking](https://github.com/volcengine/OpenViking)管理器，OpenViking 用起来不错，多台机器可以根据 peerId 共享项目记忆，又不会导致并行的多个项目记忆混乱。但 OpenViking 的默认配置倾向于 All In One，插件对默认配置做了修改。
4. **[dsh-hub-desktop](https://github.com/xbzbing/dsh-hub-desktop)**：这是一个 PC 应用，可以管理多个 dsh 实例，包括本地和远程实例（远程实例通过 [dsh-auth-gateway](https://github.com/xbzbing/dsh-auth-gateway) 访问），主要是为了解决在同一个浏览器一边看文档一边改需求需要频繁切换浏览器标签的问题。可惜没有签名，反正我是自用，签名友好的 PC .exe 就直接 release 了，macOS 需要自行编译。我感觉还是挺好用的🤣
5. **dsh-my-superagent**：这是最终版本的玩具，我先再玩几个月🤣
