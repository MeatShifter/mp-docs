# Windows: GUID (Globally Unique Identifier)

Globally Unique Identifier or GUID for short.

To generate a GUID for windows in reg string format execute the following code in PowerShell.

```ps
'{'+[guid]::NewGuid().ToString()+'}'
```
