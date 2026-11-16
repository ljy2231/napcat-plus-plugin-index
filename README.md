# Napcat-Plus 插件索引

这是 Napcat-Plus 的公开、只读插件目录。初始目录为空；插件条目须经来源、许可及信息审核后添加。

## 当前状态

- 索引文件：[index.json](index.json)。
- 本仓库不托管插件包，不提供在线安装，也不声称已对插件安全性进行审计。
- Napcat-Plus 当前版本尚未接入本索引。安装功能仍需独立实现可信元数据验证、安全解压、原子替换及回滚。
- 优先链接作者官方项目；转载或托管插件包前必须确认许可与授权。

## 索引格式

`version` 为目录版本字符串；`updateTime` 为 ISO 8601 时间；`plugins` 为数组。单条记录使用 `id`、`name`、`version`、`description`、`author`、`homepage`、`downloadUrl` 和 `tags` 字段。当前目录只用于浏览，`downloadUrl` 应为空字符串。`homepage` 使用不含凭据的 GitHub HTTPS 项目地址。

目录内容不代表官方对第三方代码安全性或使用许可作出保证。提交条目前请提供项目来源、维护状态和许可证依据；具体客户端及其资源可能分别适用不同许可。
