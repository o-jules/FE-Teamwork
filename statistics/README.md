# 代码量化统计

统计代码量：主要指标包含文件数，行数，甚至是基于具体语言语义的词数，语句数等；以及它们增长的规律。

## 工具

## Shell

- 统计行数

```bash
(find PROJECT_PATH -name '*.FILE_EXTENSION' -print0 | xargs -0 cat) | wc -l
```

## 插件

- https://plugins.jetbrains.com/plugin/4509-statistic