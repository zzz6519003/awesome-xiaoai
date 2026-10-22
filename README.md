# awesome-xiaoai

针对小爱音箱的 hack / 研究清单，重点关注 AI 助手、智能家居集成、音乐播放与控制等方向。

> 说明：这类项目往往依赖不同的固件版本、Home Assistant、Python 环境和设备协议，实际可用性需要结合你的设备型号和网络环境进行验证。

## 目录

- [AI / 语音助手](#ai--语音助手)
- [Home Assistant / 智能家居](#home-assistant--智能家居)
- [音乐与播放](#音乐与播放)
- [通用工具与接口](#通用工具与接口)
- [推荐阅读](#推荐阅读)

## AI / 语音助手

- [yihong0618/xiaogpt](https://github.com/yihong0618/xiaogpt)  
  让小爱同学接入 GPT / 语音助手，常用于把小爱音箱改造成 AI 聊天助手。

- [yihong0618/MiService](https://github.com/yihong0618/MiService)  
  小爱服务相关的接口封装/控制层，适合做设备接入、API 研究和二次开发。

- [idootop/mi-gpt](https://github.com/idootop/mi-gpt)  
  基于小米/小爱生态的 GPT 接入方案，适合尝试 AI 能力扩展。

- [longbai/xiaobot](https://github.com/longbai/xiaobot)  
  小爱音箱机器人/智能对话相关项目，偏实用脚本与自动化集成。

## Home Assistant / 智能家居

- [al-one/hass-xiaomi-miot](https://github.com/al-one/hass-xiaomi-miot)  
  Home Assistant 上最常见的米家设备集成，支持设备控制、状态同步和自动化。

- [shaonianzhentan/ha_cloud_music](https://github.com/shaonianzhentan/ha_cloud_music)  
  在 Home Assistant 场景下接入云音乐/播放服务，适合音箱娱乐扩展。

- [hanxi/xiaomusic](https://github.com/hanxi/xiaomusic)  
  与小米音箱/云音乐相关的集成方案，适合研究音频播放与设备联动。

## 音乐与播放

- [shaonianzhentan/ha_cloud_music](https://github.com/shaonianzhentan/ha_cloud_music)  
  用于把云音乐与 Home Assistant / 智能音箱场景打通的方案。

- [hanxi/xiaomusic](https://github.com/hanxi/xiaomusic)  
  关注本地/云端音乐推送与音箱播放联动。

## 通用工具与接口

- [yihong0618/MiService](https://github.com/yihong0618/MiService)  
  适用于理解小爱音箱/米家设备的服务接口、命令与控制流。

- [al-one/hass-xiaomi-miot](https://github.com/al-one/hass-xiaomi-miot)  
  适合做设备接入、状态管理和自动化规则。

## 推荐阅读

- [xiaogpt](https://github.com/yihong0618/xiaogpt)  
  入门首选：最经典、最容易快速上手的“AI 改造”项目。

- [hass-xiaomi-miot](https://github.com/al-one/hass-xiaomi-miot)  
  如果你想把小爱音箱/米家设备接入家庭自动化，优先考虑它。

- [MiService](https://github.com/yihong0618/MiService)  
  适合研究设备协议、服务接口与小爱生态通信方式。

## 关注点

- 设备型号和固件版本差异很大，很多 Hack 需要按具体硬件调整。
- 如果你使用 Home Assistant，优先考虑 `hass-xiaomi-miot` 和音乐集成方案。
- 如果你想要 AI 对话能力，优先看看 `xiaogpt` 和 `mi-gpt` 这类项目。
- 需要注意网络、音频、权限和协议兼容性问题，很多项目并非“开箱即用”。

## 结论

这个仓库的目标是维护一个“针对小爱音箱的开源 hack / 集成清单”，重点覆盖：

- AI 助手接入
- 米家设备控制
- Home Assistant 集成
- 云音乐/播放扩展
- 通用 API 与设备接口研究

如果你需要进一步扩展，可以继续补充：

- MQTT / 本地控制方案
- Xiaomi MiIO / MIoT 相关项目
- 语音唤醒/离线识别方案
- 智能音箱自动化脚本

