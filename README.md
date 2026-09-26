> **本库已归档（只读）。** 内容已全部迁入统一内容库 [`lishui`](https://github.com/lishuiorg/lishui)：
> 本站条目现位于 `content/lishui-towns/` 与 `content/en/lishui-towns/`，来源层并入该库的 `sources/`（全局共享，6 例重复已合并）。
> 本库保留仅供查阅历史，不再更新；校验工作流已随底座变更移除，现行校验在 `lishui` 库内运行。
> 迁移的理由与取舍见《三层结构集中方案》。

# lishui-towns · 溧水街镇内容库

溧水一方「溧水街镇」分站的内容库。这里存放的是**内容**，站点代码在 `site-jiezhen`，共享底座在 `lishui-kit`，部署到 `jiezhen.lishui.org`。

分站计划见《溧水街镇分站计划》；总体架构、内容模型、双语规则与许可以《溧水一方建设规划 v1.3》为准。

## 两层结构

| 目录 | 放什么 |
| --- | --- |
| `sources/` | **来源层。** 每条外部资料的著录卡：`fulltext/` 公有领域旧志全文，`excerpts/` 受版权保护资料的摘录卡，`records/` 政府页面与名录的链接档案 |
| `content/` | **成果层。** 本站自撰的条目，中文稿在 `towns/`、`villages/`、`articles/` 下，英文稿在 `en/` 下的对称路径 |

成果层文字采用 [CC BY 4.0](LICENSE) 授权。来源层各条目的授权状态见其 `rights` 字段，不随本库授权一并转移。
