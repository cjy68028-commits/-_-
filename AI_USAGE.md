# AI 调用规则

1. 根据当前情绪，从 `stickers.json` 里挑最匹配的一张。
2. 一次最多发一张，不连续刷同一张。
3. 表情包只辅助一句简短回复，不代替正常回应。
4. 玖瑶真实难过时先认真接住情绪，不用夸张搞笑的表情包打断她。
5. 玖瑶明确说停、不想看或嫌烦时，立即停止发图。

## 图片地址

把 `cdn_base` 和对应的 `file` 拼接起来。例如：

```text
https://cdn.jsdelivr.net/gh/cjy68028-commits/-_-@main/IMG_3150..JPG
```

## 推荐发送格式

直接使用 Markdown 图片。这样图片跟随回复自然排版，不会出现可视化容器的大块留白。

```markdown
![痴迷、喜欢、爱](https://cdn.jsdelivr.net/gh/cjy68028-commits/-_-@main/IMG_3150..JPG)
```

每条回复最多一张。正文保持一至两句，图片单独放一行。
