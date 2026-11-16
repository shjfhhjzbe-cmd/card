# 贺卡修改说明

本目录是贺卡的发布目录。双击 index.html 可在浏览器预览。点击「打开贺卡」，再用播放器的播放按钮听配乐。

| 文件 | 用途 |
| --- | --- |
| index.html | 贺卡标题、祝福、排版和配色 |
| cover.svg | 示例封面 |
| music.wav | 6 秒原创合成配乐，点击播放 |
| README.md | 本说明 |

1. **改文字**：用文本编辑器打开 index.html。修改 h1 标签里的标题，以及 class="letter" 下面各个 p 标签里的祝福。title 是浏览器标签页标题。
2. **换封面**：把自己的 JPG 或 PNG 放进本目录，把 img 的 src="cover.svg" 改为新文件名，例如 src="photo.jpg"。也要更新 alt 里的图片描述。
3. **换音乐**：把 MP3 或 WAV 放进本目录，把 audio 的 src="music.wav" 改为新文件名，例如 src="song.mp3"。保持文件名大小写一致。音乐由访客点击播放。
4. **改样式**：在 style 内改 body（页面背景与字体）、.card（卡片）、.cover（封面尺寸）、summary（按钮）。保存后刷新本地浏览器查看。
5. **发布更新**：打开 https://github.com/shjfhhjzbe-cmd/card ，在 main 分支点 Add file → Upload files。上传本目录里改过的文件到仓库根目录，保持 index.html 在最外层。点击 Commit changes 后等 Pages 自动部署。
6. **验收**：用手机无痕窗口打开 https://shjfhhjzbe-cmd.github.io/card/ ，展开祝福并播放音乐。网址不变，之前写好的 NFC 卡不用重写。

GitHub 仓库和贺卡页面是公开的。仅上传你愿意公开的文字、照片和音频。
