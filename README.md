# Sunyl的音乐室

面向小学生的奥尔夫节奏训练网页，用卡通火车、节奏符号和节拍提示音，帮助学生练习稳定拍、节奏模仿与节奏组合。适合作为奥尔夫音乐教学中的节奏活动辅助工具，可配合声势律动、拍手、快板和打击乐器开展课堂练习。

## 在线使用

👉 https://s200938910-oss.github.io/sunyl-music-room/

## 本地使用

下载仓库后双击「点我开始.html」，用当前版本的 Edge 或 Chrome 打开。无需联网，无需安装任何东西。

## 主要功能

1. 火车从左向右持续行驶，中央设有节拍基准线。
2. 支持 80–160 BPM 调速，以及 2、3、4 拍子切换。
3. 四节车厢可设置四分、八分、十六分、二分音符、附点及常用节奏组合。
4. 支持四分、八分休止符，休止时提示音静默。
5. 开始前有四拍预备提示：三个黄灯、一个绿灯。
6. 车厢按所选拍子数量分组着色，连续循环运行。
7. 支持开始、暂停、继续、停止和全屏。
8. 右上角可切换简体中文和 English，切换不会中断播放。

## 技术说明

纯 HTML、CSS 和 JavaScript，无后端、数据库或安装依赖。火车贴图已内嵌，提示音由 Web Audio 生成。用当前版本的 Edge 或 Chrome 打开即可离线使用。需要点击「开始」启动声音；刷新页面会恢复默认设置。

## 文件说明

| 文件 | 用途 |
| --- | --- |
| `点我开始.html` | 主程序。下载后双击即可离线使用。 |
| `index.html` | 与主程序内容完全一致，供 GitHub Pages 作为网站首页。 |
| `使用说明.txt` | 面向老师的操作步骤。 |

> 维护提示：`index.html` 与 `点我开始.html` 必须保持内容一致，更新主程序时请同步更新两份文件。

## 定位说明

本页面是可用于奥尔夫音乐教学活动的辅助练习工具，不代表官方认证或完整的奥尔夫教学课程。

## 关键词

奥尔夫音乐教学、小学音乐、节奏训练、稳定拍、声势律动、节奏模仿、节奏创编、打击乐、快板、音乐课堂、互动教学

---

## English

**Sunyl's Music Room** — a rhythm-training web page for primary-school music classes.

An interactive rhythm practice tool built around a cartoon train, rhythm symbols and beat cues. Students work on steady beat, rhythm imitation and rhythm combinations while the train runs across the screen. It is designed as a companion activity for Orff-based music lessons and works well alongside body percussion, clapping, clappers and classroom percussion instruments.

**Live demo:** https://s200938910-oss.github.io/sunyl-music-room/

### Features

1. The train runs continuously from left to right, with a beat reference line in the centre.
2. Tempo adjustable from 80 to 160 BPM; switch between 2, 3 and 4 beats per bar.
3. Four carriages can each be set to quarter, eighth, sixteenth, half, dotted notes and common rhythm combinations.
4. Quarter and eighth rests are supported; the click falls silent on a rest.
5. A four-beat count-in precedes playback: three amber lights, then one green.
6. Carriages are colour-grouped by the number of beats selected, and the pattern loops continuously.
7. Start, pause, resume, stop and fullscreen controls.
8. Switch between Simplified Chinese and English in the top-right corner without interrupting playback.

### Technical notes

Pure HTML, CSS and JavaScript. No backend, no database, no build step and no dependencies. Train artwork is embedded in the file and the beat sound is synthesised with the Web Audio API. Open the file in a current version of Edge or Chrome to use it offline. Sound starts only after you press "Start"; refreshing the page restores the default settings.

### Files

| File | Purpose |
| --- | --- |
| `点我开始.html` | Main application. Double-click to use offline. |
| `index.html` | Identical copy of the main application, served as the GitHub Pages homepage. |
| `使用说明.txt` | Step-by-step instructions for teachers (Chinese). |

### Disclaimer

This page is an auxiliary practice tool for Orff-based music teaching activities. It is not officially certified and is not a complete Orff curriculum.
