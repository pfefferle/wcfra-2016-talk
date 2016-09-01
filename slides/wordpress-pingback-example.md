Pingback Example:

```
POST /pingback-endpoint HTTP/1.1
Host: aaronpk.example
Content-Type: text/xml

<?xml version="1.0" encoding="iso-8859-1"?>
<methodCall>
<methodName>pingback.ping</methodName>
<params>
 <param>
  <value>
   <string>https://waterpigs.example/post-by-barnaby</string>
  </value>
 </param>
 <param>
  <value>
   <string>https://aaronpk.example/post-by-aaron</string>
  </value>
 </param>
</params>
</methodCall>
```
