### ...

> ...

###

> site:XXXX  intext:"index of /.git"
> site:XXXX  inurl:%3F
> site:XXXX  intitle:"index of"
> site:XXXX  intext:"sql syntax near" | intext:"incorrect syntax near"


### Normal

> site:XXXX

### Juicy Extensions

> site:XXXX  ext:log | ext:txt | ext:conf | ext:cnf | ext:ini | ext:env | ext:sh | ext:bak | ext:backup | ext:swp | ext:old | ext:~ | ext:git | ext:svn | ext:htpasswd | ext:htaccess

### Code Leaks

> site:pastebin.com "XXXX"

> site:jsfiddle.net "XXXX"

> site:codebeautify.org "XXXX"

> site:codepen.io "XXXX"

### Cloud Storage

> site:atlassian.net "XXXX"

> site:s3.amazonaws.com "XXXX"

> site:blob.core.windows.net "XXXX"

> site:googleapis.com "XXXX"

> site:drive.google.com "XXXX"

> site:dev.azure.com "XXXX"

> site:onedrive.live.com "XXXX"

> site:digitaloceanspaces.com "XXXX"

> site:sharepoint.com "XXXX"

> site:s3-external-1.amazonaws.com "XXXX"

> site:s3.dualstack.us-east-1.amazonaws.com "XXXX"

> site:dropbox.com/s "XXXX"

> site:box.com/s "XXXX"

> site:docs.google.com inurl:"/d/" "XXXX"

### XSS prone parameters

> site:XXXX  inurl:&  inurl:q= | inurl:s= | inurl:search= | inurl:query=

### Open Redirect prone parameters

> site:XXXX  inurl:&  inurl:url= | inurl:return= | inurl:next= | inurl:redir=

### SQLi Prone Parameters

> site:XXXX  inurl:&  inurl:id= | inurl:pid= | inurl:category= | inurl:cat= | inurl:action= | inurl:sid= | inurl:dir=

### SSRF Prone Parameters

> site:XXXX  inurl:&  inurl:http | inurl:url= | inurl:path= | inurl:dest= | inurl:html= | inurl:data= | inurl:domain=  | inurl:page=

### LFI Prone Parameters

> site:XXXX  inurl:&  inurl:include= | inurl:dir= | inurl:detail= | inurl:file= | inurl:folder= | inurl:inc= | inurl:locate= | inurl:doc= | inurl:conf=

### RCE Prone Parameters

> site:XXXX  inurl:&  inurl:cmd= | inurl:exec= | inurl:query= | inurl:code= | inurl:do= | inurl:run= | inurl:read= | inurl:ping=

### High % inurl keywords

> site:XXXX  inurl:config | inurl:env | inurl:setting | inurl:backup | inurl:admin | inurl:php

### Sensitive Parameters

> site:XXXX  inurl:&  inurl:email= | inurl:phone= | inurl:password= | inurl:secret=

### API Docs

> site:XXXX  inurl:apidocs | inurl:api-docs | inurl:swagger | inurl:api-explorer

### File upload endpoints

> site:XXXX  "choose file"
