# 新媒体前沿：平台观察海报展

厦门大学新闻传播学院《新媒体前沿》（Frontiers of New Media）课程，2026 年秋季。

在线展示：https://sujunbin.github.io/New-Media-Frontiers/

## 内容

学生以小组为单位，选择一个平台、追踪一个平台机制，以研究海报呈现诊断结果。

## 授权

- 每份海报均经小组全体成员书面授权后公开，著作权归作者所有。
- 除另有说明外，海报以 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh-hans) 协议发布。
- 每份海报存档于 Zenodo 并获得 DOI；引用时以 Zenodo 资源页面为准。
- 本仓库的网页代码以 MIT 协议发布。

## 维护说明

新增海报时，在 `posters/` 放入 `gNN.png`（缩略图）和 `gNN.pdf`，然后在 `posters.json` 中加入一条记录：

```json
{
  "group": 1,
  "platform": "抖音",
  "title": "海报题名",
  "authors": "作者甲、作者乙",
  "abstract": "150 字以内的摘要",
  "image": "posters/g01.png",
  "pdf": "posters/g01.pdf",
  "doi": "10.5281/zenodo.0000000"
}
```

如发现隐私或版权问题，请在本仓库提交 [Issue](https://github.com/sujunbin/New-Media-Frontiers/issues)。
