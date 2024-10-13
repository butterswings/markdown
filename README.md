# markdown

markdown on github

## 标题

以n个#加空格开头，表示第n级标题

```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
```

## 文本样式

| style | 语法| 输出|
| --------------- | --------------- | --------------- |
| 加粗 | `**text**` | **text** |
| 斜体 | `*text*` | *text* |
| 加粗与斜体 | `***text***` | ***text*** |
| 删除线 | `~~text~~` | ~~text~~ |
| 粗体和嵌入的斜体 | `**te_x_t**` | **te_x_t** |
| 上标 | `text<sup>text</sup>` | text<sup>text</sup> |
| 下标| `<textsub>text</sub>` | text<sub>text</sub> |

## 引用文本

使用>加空格表示引用文本，同时具有缩进

```markdown
> the text is quote
```

this text is not quote
> the text is quote

## 引用代码

以``包裹的片段不会被格式化

```markdown
`git commit`
```

以连续的三个`表示代码块

```markdown
 git status
 git add
 git commit
```

## colors

似乎支持不好，暂时跳过此节
`#000000`
