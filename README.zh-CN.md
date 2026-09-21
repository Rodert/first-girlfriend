# first-girlfriend

[English](README.md) | [简体中文](README.zh-CN.md)

> 它不是美女写真 Skill，而是一台初恋记忆生成器。

`first-girlfriend` 会把对成年女性或场景的简单描述，扩展成带有怀旧质感的自然抓拍摄影提示词：一个平凡的瞬间，因为温度、距离和恰到好处的不完美，而像一段真实记忆。

## 它生成什么

- 处在日常生活场景中的自然成年人物
- 从暗恋到多年后重看照片，合理的镜头人物关系
- 从 2005 年 CCD 到现代手机照片的年代质感
- 服务于记忆感的构图偏移、肤质、光线、失焦和运动痕迹

它刻意避开商业写真、性化表达、年龄歧义，以及过度精修的 AI 美女感。

## 使用方式

将此仓库安装为 Codex Skill 后，用自然语言描述你想要的瞬间。也可以补充以下可选控制项：

| 控制项 | 可用值 |
| --- | --- |
| `scene` | after-school, first-date, library, summer, winter, travel, candid, years-later |
| `distance` | stranger, crush, first-date, girlfriend, long-distance, breakup, years-later |
| `era` | 2005, 2010, 2015, present |

```text
夏天，公交站，years-later。一个成年女性穿白衬衫和牛仔裤，刚下班。
```

Skill 会返回一段可直接用于图片生成的英文提示词，并说明它选择的场景、关系距离和年代。完整效果见[示例](examples/examples.md)，各场景规则见 [prompts](prompts)。

## 设计原则

重点不只是人物的外表，也是照片透露出的拍摄者与人物之间的关系：

> 像是由一个偷偷喜欢她的人拍下的。

这种关系会影响人物的注意力、镜头距离和精致程度；但绝不意味着偷拍、胁迫或未成年主体。

## 目录

```text
.
├── SKILL.md
├── README.md
├── README.zh-CN.md
├── prompts/
│   ├── candid.md
│   ├── date.md
│   ├── school.md
│   ├── summer.md
│   ├── travel.md
│   ├── winter.md
│   └── years-later.md
└── examples/
    └── examples.md
```

## 许可证

[Apache-2.0](LICENSE)
