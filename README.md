# first-girlfriend

[English](README.md) | [简体中文](README.zh-CN.md)

> Not a beautiful-girl prompt skill. It is a memory generator.

`first-girlfriend` turns a simple description of an adult woman or scene into a nostalgic, candid photography prompt: an ordinary moment remembered with warmth, distance, and enough imperfection to feel real.

## What It Makes

- Natural, adult subjects in everyday places
- A believable relationship to the camera, from a quiet crush to years-later memory
- Era-aware texture from 2005 CCD snapshots to present-day phone photos
- Imperfect framing, skin texture, light, focus, and motion when they serve the memory

It deliberately avoids glamour photography, sexualization, age ambiguity, and overproduced AI-beauty aesthetics.

## Use It

Install this repository as a Codex skill, then describe the moment in plain language. Optional controls:

| Control | Values |
| --- | --- |
| `scene` | after-school, first-date, library, summer, winter, travel, candid, years-later |
| `distance` | stranger, crush, first-date, girlfriend, long-distance, breakup, years-later |
| `era` | 2005, 2010, 2015, present |

```text
夏天，公交站，years-later。一个成年女性穿白衬衫和牛仔裤，刚下班。
```

The skill returns a ready-to-use English image-generation prompt and a concise note of the creative choices. See [examples](examples/examples.md) and [scene direction](prompts).

## Design Principle

The question is not only what she looks like. It is what the photograph reveals about the person behind the camera:

> As if photographed by someone who secretly likes her.

That relationship affects attention, camera distance, and polish. It never implies surveillance, coercion, or a minor subject.

## Contents

```text
.
├── SKILL.md
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

## License

[Apache-2.0](LICENSE)
