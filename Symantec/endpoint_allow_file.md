
# endpoint_allow_file.md

This action tells openC2 to allow the file on the computer. e.g In an endpoints case, whitelist.

```

{
  "id": "019f3756-0aec-4010-a0f5-050ebf2dd680",
  "action": "allow",
  "target": {
    "file": {
      "extensions": "string",
      "hashes": {
        "type": "SHA256",
        "value": "dc94bbd73a1fce1b04c663a008408dd209cfe355483eea2044f2a4616aad7110"
      },
      "size": 0,
      "name": "netgato.exe",
      "name_enc": "string",
      "created": "string",
      "modified": "string",
      "accessed": "string",
      "is_encrypted": true,
      "encryption_algorithm": "string",
      "decryption_key": "string"
    }
  },
  "actuator": {
    "endpoint": {
      "asset_id": "endpoint6.example.com"
    }
  },
  "args": {
    "start_time": "2018-06-25T14:01:03.952Z",
    "stop_time": "2018-06-25T14:01:10.952Z",
    "duration": 0,
    "response_requested": "ack",
  }
}
```

**RESPONSE**

```
{
  "id_ref": "019f3756-0aec-4010-a0f5-050ebf2dd680",
  "status": 200,
  "status_text": "string",
  "results": {
    "command_ref": "INTERNALREFERENCEVALUEABC123"
  }
}
```
