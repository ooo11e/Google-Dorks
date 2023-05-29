### ...

> ...

### (1)

> site:XXXX

> site:XXXX  inurl:&

### Config files
> site:XXXX  ext:xml | ext:conf | ext:cnf | ext:reg | ext:inf | ext:rdp | ext:cfg | ext:txt | ext:ora | ext:env | ext:ini

### Database files
> site:XXXX  ext:sql | ext:db | ext:dbf | ext:mdb | ext:sql.gz | ext:sql.gz | ext:db.gz | ext:db.gz

### Backup files
> site:XXXX  ext:bkf | ext:bkp | ext:bak | ext:old | ext:backup

### .git folder
> site:XXXX  inurl:"/.git"

### Exposed documents
> site:XXXX  ext:doc | ext:docx | ext:odt | ext:pdf | ext:rtf | ext:sxw | ext:psw | ext:ppt | ext:pptx | ext:pps | ext:csv

### SQL errors
> site:XXXX  AND ( intext:"sql syntax near" | intext:"syntax error has occurred" | intext:"incorrect syntax near" | intext:"unexpected end of SQL command" | intext:"Warning: mysql_connect()" | intext:"Warning: mysql_query()" | intext:"Warning: pg_connect()" )

### PHP errors
> site:XXXX  AND ( "PHP Parse error" | "PHP Warning" | "PHP Error" )
> site:XXXX  inurl:phpmyadmin "Index of" 

### Login pages
> site:XXXX  AND ( inurl:login | inurl:signin | intitle:login | intitle:signin | inurl:auth | inurl:signup | inurl:register | intitle:signup )

### Open redirects
> site:XXXX  AND ( inurl:redir | inurl:url | inurl:redirect | inurl:return | inurl:location | inurl:next | inurl:dest | inurl:src=http | inurl:r=http )

### Apache Struts RCE
> site:XXXX  ( ext:action | ext:struts | ext:do )

### Wordpress files
> site:XXXX  AND ( inurl:wp-content | inurl:wp-includes )
> site:XXXX  inurl:wp-config.php intext:DB_PASSWORD
> site:XXXX  intitle:"Index of" "wp-admin"

### Other files
> site:XXXX  AND ( intitle:index.of | ext:log | inurl:shell | inurl:backdoor | inurl:wso | inurl:cmd | shadow | passwd | boot.ini | inurl:backdoor | inurl:readme | inurl:license | inurl:install | inurl:setup | inurl:config | inurl:"/phpinfo.php" | inurl:".htaccess" | ext:swf )
> site:XXXX  AND ( ext:env | ext:log | ext:sql | ext:yml | ext:pem | ext:ini | ext:logs | ext:ibd | ext:txt | ext:php.txt | ext:old | ext:key | ext:frm | ext:bak | ext:zip | ext:swp | ext:conf | ext:db | ext:config | ext:ovpn | ext:svn | ext:git | ext:cfg | ext:exs | ext:dbf | ext:mdb | ext:pem | ext:pub | ext:yaml | ext:zip | ext:asc | ext:xls | ext:xlsx )



> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  
> site:XXXX  




> site:XXXX  ext:bkf | ext:bkp | ext:cfg | ext:dbf | ext:mdb | ext:odt | ext:rtf | ext:sxw | ext:psw | ext:struts 
> site:XXXX  ext:csv | ext:php | ext:jsp | ext:asp  | ext:aspx | ext:action | ext:do | ext:rb | ext:xml | ext:phtml 
> site:XXXX  ext:yaml | ext:txt | ext:reg | ext:ini | ext:ora | ext:env | ext:inf | ext:rdp | ext:cnf | ext:conf 
> site:XXXX  ext:old | ext:backup | ext:bak | ext:bakp  | ext:log | ext:sql | ext:jspx
> site:XXXX  ext:doc | ext:pdf | ext:xls | ext:ppt

> site:XXXX  inurl:login | inurl:signin | intitle:login | intitle:signin | inurl:auth | inurl:signup | inurl:register | intitle:signup

> site:XXXX  intext:'sql syntax near' | intext:'syntax error has occurred' | intext:'incorrect syntax near' | intext:'unexpected end of SQL command' | intext:'Warning: mysql_connect()' | intext:'Warning: mysql_query()' | intext:'Warning: pg_connect()'

> site:XXXX  ext:php intitle:phpinfo 'published by the PHP Group'

> site:XXXX  inurl:readme | inurl:license | inurl:install | inurl:setup | inurl:config

> site:XXXX  intitle:index.of

> site:XXXX  inurl:apidocs | inurl:api-docs | inurl:swagger | inurl:api-explorer

### (2)

> site:.s3.amazonaws.com 'XXXX'

> site:stackoverflow.com 'XXXX'

> site:pastebin.com | site:paste2.org | site:pastehtml.com | site:slexy.org | site:snipplr.com | site:snipt.net | site:textsnip.com | site:bitpaste.app | site:justpaste.it | site:heypasteit.com | site:hastebin.com | site:dpaste.org | site:dpaste.com | site:codepad.org | site:jsitor.com | site:codepen.io | site:jsfiddle.net | site:dotnetfiddle.net | site:phpfiddle.org | site:ide.geeksforgeeks.org | site:repl.it | site:ideone.com | site:paste.debian.net | site:paste.org | site:paste.org.ru | site:codebeautify.org  | site:codeshare.io | site:trello.com 'XXXX'

> site:linkedin.com employees 'XXXX'

> site:atlassian.net 'XXXX'

> site:s3.amazonaws.com 'XXXX'

> site:blob.core.windows.net 'XXXX'

> site:googleapis.com 'XXXX'

> site:drive.google.com 'XXXX'

> site:dev.azure.com 'XXXX'

> site:onedrive.live.com 'XXXX'

> site:digitaloceanspaces.com 'XXXX'

> site:sharepoint.com 'XXXX'

> site:s3-external-1.amazonaws.com 'XXXX'

> site:s3.dualstack.us-east-1.amazonaws.com 'XXXX'

> site:dropbox.com/s 'XXXX'

> site:box.com/s 'XXXX'

> site:docs.google.com inurl:'/d/' 'XXXX'

### (3)

> (XXXX) ( site:*.*.9.* | site:*.*.8.* | site:*.*.7.* | site:*.*.6.* | site:*.*.5.* | site:*.*.4.* | site:*.*.3.* | site:*.*.2.* | site:*.*.1.* | site:*.*.0.* )
> (XXXX) ( site:*.*.19.* | site:*.*.18.* | site:*.*.17.* | site:*.*.16.* | site:*.*.15.* | site:*.*.14.* | site:*.*.13.* | site:*.*.12.* | site:*.*.11.* | site:*.*.10.* )
> (XXXX) ( site:*.*.29.* | site:*.*.28.* | site:*.*.27.* | site:*.*.26.* | site:*.*.25.* | site:*.*.24.* | site:*.*.23.* | site:*.*.22.* | site:*.*.21.* | site:*.*.20.* )
> (XXXX) ( site:*.*.39.* | site:*.*.38.* | site:*.*.37.* | site:*.*.36.* | site:*.*.35.* | site:*.*.34.* | site:*.*.33.* | site:*.*.32.* | site:*.*.31.* | site:*.*.30.* )
> (XXXX) ( site:*.*.49.* | site:*.*.48.* | site:*.*.47.* | site:*.*.46.* | site:*.*.45.* | site:*.*.44.* | site:*.*.43.* | site:*.*.42.* | site:*.*.41.* | site:*.*.40.* )
> (XXXX) ( site:*.*.59.* | site:*.*.58.* | site:*.*.57.* | site:*.*.56.* | site:*.*.55.* | site:*.*.54.* | site:*.*.53.* | site:*.*.52.* | site:*.*.51.* | site:*.*.50.* )
> (XXXX) ( site:*.*.69.* | site:*.*.68.* | site:*.*.67.* | site:*.*.66.* | site:*.*.65.* | site:*.*.64.* | site:*.*.63.* | site:*.*.62.* | site:*.*.61.* | site:*.*.60.* )
> (XXXX) ( site:*.*.79.* | site:*.*.78.* | site:*.*.77.* | site:*.*.76.* | site:*.*.75.* | site:*.*.74.* | site:*.*.73.* | site:*.*.72.* | site:*.*.71.* | site:*.*.70.* )
> (XXXX) ( site:*.*.89.* | site:*.*.88.* | site:*.*.87.* | site:*.*.86.* | site:*.*.85.* | site:*.*.84.* | site:*.*.83.* | site:*.*.82.* | site:*.*.81.* | site:*.*.80.* )
> (XXXX) ( site:*.*.99.* | site:*.*.98.* | site:*.*.97.* | site:*.*.96.* | site:*.*.95.* | site:*.*.94.* | site:*.*.93.* | site:*.*.92.* | site:*.*.91.* | site:*.*.90.* )
> (XXXX) ( site:*.*.109.* | site:*.*.108.* | site:*.*.107.* | site:*.*.106.* | site:*.*.105.* | site:*.*.104.* | site:*.*.103.* | site:*.*.102.* | site:*.*.101.* | site:*.*.100.* )
> (XXXX) ( site:*.*.119.* | site:*.*.118.* | site:*.*.117.* | site:*.*.116.* | site:*.*.115.* | site:*.*.114.* | site:*.*.113.* | site:*.*.112.* | site:*.*.111.* | site:*.*.110.* )
> (XXXX) ( site:*.*.129.* | site:*.*.128.* | site:*.*.127.* | site:*.*.126.* | site:*.*.125.* | site:*.*.124.* | site:*.*.123.* | site:*.*.122.* | site:*.*.121.* | site:*.*.120.* )
> (XXXX) ( site:*.*.139.* | site:*.*.138.* | site:*.*.137.* | site:*.*.136.* | site:*.*.135.* | site:*.*.134.* | site:*.*.133.* | site:*.*.132.* | site:*.*.131.* | site:*.*.130.* )
> (XXXX) ( site:*.*.149.* | site:*.*.148.* | site:*.*.147.* | site:*.*.146.* | site:*.*.145.* | site:*.*.144.* | site:*.*.143.* | site:*.*.142.* | site:*.*.141.* | site:*.*.140.* )
> (XXXX) ( site:*.*.159.* | site:*.*.158.* | site:*.*.157.* | site:*.*.156.* | site:*.*.155.* | site:*.*.154.* | site:*.*.153.* | site:*.*.152.* | site:*.*.151.* | site:*.*.150.* )
> (XXXX) ( site:*.*.169.* | site:*.*.168.* | site:*.*.167.* | site:*.*.166.* | site:*.*.165.* | site:*.*.164.* | site:*.*.163.* | site:*.*.162.* | site:*.*.161.* | site:*.*.160.* )
> (XXXX) ( site:*.*.179.* | site:*.*.178.* | site:*.*.177.* | site:*.*.176.* | site:*.*.175.* | site:*.*.174.* | site:*.*.173.* | site:*.*.172.* | site:*.*.171.* | site:*.*.170.* )
> (XXXX) ( site:*.*.189.* | site:*.*.188.* | site:*.*.187.* | site:*.*.186.* | site:*.*.185.* | site:*.*.184.* | site:*.*.183.* | site:*.*.182.* | site:*.*.181.* | site:*.*.180.* )
> (XXXX) ( site:*.*.199.* | site:*.*.198.* | site:*.*.197.* | site:*.*.196.* | site:*.*.195.* | site:*.*.194.* | site:*.*.193.* | site:*.*.192.* | site:*.*.191.* | site:*.*.190.* )
> (XXXX) ( site:*.*.209.* | site:*.*.208.* | site:*.*.207.* | site:*.*.206.* | site:*.*.205.* | site:*.*.204.* | site:*.*.203.* | site:*.*.202.* | site:*.*.201.* | site:*.*.200.* )
> (XXXX) ( site:*.*.219.* | site:*.*.218.* | site:*.*.217.* | site:*.*.216.* | site:*.*.215.* | site:*.*.214.* | site:*.*.213.* | site:*.*.212.* | site:*.*.211.* | site:*.*.210.* )
> (XXXX) ( site:*.*.229.* | site:*.*.228.* | site:*.*.227.* | site:*.*.226.* | site:*.*.225.* | site:*.*.224.* | site:*.*.223.* | site:*.*.222.* | site:*.*.221.* | site:*.*.220.* )
> (XXXX) ( site:*.*.239.* | site:*.*.238.* | site:*.*.237.* | site:*.*.236.* | site:*.*.235.* | site:*.*.234.* | site:*.*.233.* | site:*.*.232.* | site:*.*.231.* | site:*.*.230.* )
> (XXXX) ( site:*.*.249.* | site:*.*.248.* | site:*.*.247.* | site:*.*.246.* | site:*.*.245.* | site:*.*.244.* | site:*.*.243.* | site:*.*.242.* | site:*.*.241.* | site:*.*.240.* )
> (XXXX) ( site:*.*.256.* | site:*.*.255.* | site:*.*.254.* | site:*.*.253.* | site:*.*.252.* | site:*.*.251.* | site:*.*.250.* )
