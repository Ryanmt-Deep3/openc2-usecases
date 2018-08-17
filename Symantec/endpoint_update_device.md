
# endpoint_update_device.md

This action triggers a content update session from the update server.

```
{
  "id": "00c74fe8-0d44-40ce-b01b-026e4b3f7c89",
  "action": "update",
  "target": {
    "device": {}
  },
  "actuator": {
    "endpoint": {
      "asset_id": "endpoint6.example.com"
    }
  },
  "args": {
    "start_time": "2018-06-25T14:39:35.166Z",
    "stop_time": "2018-06-25T14:39:35.166Z",
    "duration": 0,
    "response_requested": "ack"
  }
}
```

**RESPONSE**

```
{
  "id_ref": "00c74fe8-0d44-40ce-b01b-026e4b3f7c89",
  "status": 200,
  "status_text": "string",
  "results": {
    "command_ref": "INTERNALREFERENCEVALUEABC123"
  }
}
```
