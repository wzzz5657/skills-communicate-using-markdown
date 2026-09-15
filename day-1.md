# Daily Learning
## Morning Planning
- [x] 拉取V1项目
- [x] 学习github相关内容
- [ ] 拼高达
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" height = "200" align="right">

## Review
使用 [ffmpeg](https://www.ffmpeg.org) 将图片或视频从深色模式转换为浅色模式

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```

测试Lua能不能正常显示

```lua
local str = 'hello world'
```
