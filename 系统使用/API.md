# API 和Debug API

Hop节点公开了两个 HTTP API 端点`API`和`Debug API`完成查看运行节点的主要接口。可以使用熟悉的 HTTP 请求进行查询，并将在适当的情况下以语义上准确的[HTTP 状态和错误代码](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)以及[JSON](https://www.json.org/json-en.html)格式的数据有效负载进行响应。

## API

API 端点公开了向网络上传和下载内容的所有功能。默认情况下，它在`:1633`端口上运行。

### [API参考](https://github.com/redesblock/hop/blob/main/openapi/API.yaml)

# Debug API

默认情况下禁用 Debug API，但可以通过将`debug-api-enable`配置选项设置为 来启用`true`。Debug API 公开了在 节点运行时检查其状态的功能，以及一些不应向公共 网络公开的其他功能。默认情况下，调试 API 在`:1635`端口上运行。

### [Debug API参考](https://github.com/redesblock/hop/blob/main/openapi/DebugAPI.yaml)

