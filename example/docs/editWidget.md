## editWidget

Edits widget.

```
POST /widgets/{id}
{
  "ops": [ { ... }, ... ]
}
--- 200 OK
(widget)
--- 202 Accepted
(job)
```

| request | type | description |
| --- | --- | --- |
| id | string | The widget ID. |
| ops | object[] | The operations. |

| response | type | description |
| --- | --- | --- |
| widget | [Widget](Widget.md) | The edited widget. |
| job | [WidgetJob](WidgetJob.md) | The pending job. |

<!-- DO NOT EDIT: generated by fsdgenmd -->
