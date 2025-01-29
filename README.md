# doxie

10.10.10.43

```
curl http://10.10.10.43:8080/list
{"path":"","device":"Doxie_04E634","files":[{"name":"DOXIE","type":"folder"},{"name":"System Volume Information","type":"folder"}]}

curl http://10.10.10.43:8080/list/doxie
{"path":"doxie","device":"Doxie_04E634","files":[{"name":"JPEG","type":"folder"}]}

curl http://10.10.10.43:8080/list/doxie/jpeg
{"path":"doxie/jpeg","device":"Doxie_04E634","files":[]}

```
