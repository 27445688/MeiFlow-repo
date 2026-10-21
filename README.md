# MeiFlow 越狱源

魅流 MeiFlow 的安装包与更新都从这个源发布（只有 `.deb` 与索引，不含源码）。

**添加源**（Sileo / Zebra → 源 → 添加）：

```
https://27445688.github.io/MeiFlow-repo/
```

要求：iOS 16.0–17.x，RootHide 或 Dopamine RootHide 越狱，arm64e。添加后在“软件包”里搜索 MeiFlow 安装；之后有新版本时 Sileo 会在“更新”里提示。

源文件：`Packages`（索引）、`Packages.gz` / `Packages.bz2`、`Release`、`debs/`（各版本安装包）。索引由主仓库的 `scripts/make_repo.py` 生成。
