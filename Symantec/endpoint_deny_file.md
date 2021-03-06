
# endpoint_deny_file.md

This action specifies a file be denied on an endpoint. e.g Deny file from being written to disk.

```
{
  "id": "02b423e8-0375-4039-8097-069aaaf76ef9",
  "action": "deny",
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
    "start_time": "2018-06-25T19:39:43.246Z",
    "stop_time": "2018-06-25T19:39:43.246Z",
    "duration": 0,
    "response_requested": "ack"
  }
}
```

**RESPONSE**

```
{
  "id_ref": "02b423e8-0375-4039-8097-069aaaf76ef9",
  "status": 200,
  "status_text": "string",
  "results": {
    "command_ref": "INTERNALREFERENCEVALUEABC123"
  }
}
```
