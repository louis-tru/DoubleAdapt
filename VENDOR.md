# DoubleAdapt 第三方源码钉扎

- 仓库：https://github.com/SJTU-DMTai/DoubleAdapt
- Next fork：https://github.com/louis-tru/DoubleAdapt 分支 `next-cpu-fallback`
- 论文：https://arxiv.org/abs/2306.09862
- 上游 Commit：`e20b6e46ccbd2b6b8180ff3db62f68b16721684c`（2024-12-25）
- 本地路径：`deps/DoubleAdapt`
- 许可证：官方仓库没有 LICENSE 文件；`main.py` 头部写 Microsoft MIT License。本目录只供 research 实验 183 导入，不进入 `core`。

实验 183 直接导入 `IncrementalManager`、`DoubleAdaptManager`、数据/模型适配器与 `organize_all_tasks` / `get_rolling_data`，不另写同名简化算法。
