---
title: "内容模型与索引"
summary: "把 thoughts/posts/books 映射到统一索引。"
---
第二章关注内容模型。

索引在服务启动时构建一次，运行期只做只读查询，避免请求时重复解析 Markdown。
