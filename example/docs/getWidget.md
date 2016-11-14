## getWidget

Gets the specified widget.

```
GET /widgets/{id}
If-None-Match: (ifNoneMatch)
--- response
eTag: (eTag)
--- 200 OK
(widget)
--- 304 Not Modified
(if notModified)
```

| request | type | description |
| --- | --- | --- |
| id | string | The widget ID. |
| ifNoneMatch | string |  |

| response | type | description |
| --- | --- | --- |
| widget | [Widget](Widget.md) | The requested widget. |
| eTag | string |  |
| notModified | boolean |  |

<!-- DO NOT EDIT: generated by fsdgenmd -->