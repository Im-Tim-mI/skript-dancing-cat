# Dancing Cat

**English** | [繁體中文](README.zh-TW.md)

Summons a named cat 5 blocks in front of you that spins in place for about 5 seconds to rising note sounds, then vanishes. An optional add-on greets every player with a dancing cat when they join.

> This repository has two editions of the same script: **繁體中文 (zh-TW)** is the original used on the author's Traditional Chinese server, and **English** is a full translation (commands, messages and variable names) with the same features.

## Features

- The cat is invulnerable, silent, has no AI or gravity and isn't saved, so it never wanders off or stays behind
- Spins 18° per tick for 100 ticks with five note sounds
- Optional add-on runs the command for every player 3 seconds after they join

## Requirements

- [Paper](https://papermc.io/) server (developed on Paper 26.2 / Minecraft 26.2)
- [Skript](https://github.com/SkriptLang/Skript) (developed on 2.16.2)
- [skript-reflect](https://github.com/SkriptLang/skript-reflect) (developed on 2.6.3)

## Installation

1. Install the plugins listed under [Requirements](#requirements).
2. Download **one** edition:

   | Edition | File(s) |
   |---|---|
   | English | [`en/dancing-cat.sk`](en/dancing-cat.sk)<br>[`en/auto-cat-on-join.sk`](en/auto-cat-on-join.sk) (optional add-on) |
   | 繁體中文 (original) | [`zh-TW/跳舞貓咪.sk`](zh-TW/%E8%B7%B3%E8%88%9E%E8%B2%93%E5%92%AA.sk)<br>[`zh-TW/登入自動貓咪.sk`](zh-TW/%E7%99%BB%E5%85%A5%E8%87%AA%E5%8B%95%E8%B2%93%E5%92%AA.sk) (optional add-on) |

3. Copy the `.sk` file(s) into `plugins/Skript/scripts/` on your server.
4. Run `/sk reload dancing-cat` (use the file name you copied) or restart the server.

> [!IMPORTANT]
> Install **only one** edition. Both editions are the same script in different languages - loading both makes them clash or run twice.

## Commands

| Command (English edition) | zh-TW edition | Description | Permission |
|---|---|---|---|
| `/dancingcat`<br>alias: `/cat` | `/貓咪` | Summon a dancing cat | everyone (players only) |

## Notes

- Install the add-on only together with the main script of the same edition.

## License

**MIT + Commons Clause** - see [LICENSE](LICENSE) for the full text.

- ✅ You may use, copy, modify and share this script.
- ✅ You **may** install and run it - including modified versions - on Minecraft servers that charge money or are run for profit.
- ❌ You may **not** sell the script itself or modified versions of it, directly or indirectly, or require payment to obtain its files or source code.

Copyright (c) 2026 廷廷小教室、廷廷的家（Tim945）
