# SSMT-WorkSpace_Access-Library
SSMT 工作空间信息公共存取库

## 目录约定（测试版）

- `games/<GamePreset>/<Author>/<Entry>/metadata.json`：可导入的工作空间元信息。
- `index/v1/<GamePreset>.json`：客户端按游戏读取的检索索引。
- `schema/metadata.schema.json`：元信息 JSON Schema。

当前格式为 v1 测试版。元信息不得包含本机绝对路径、Frame Analysis 路径或其他隐私数据。
