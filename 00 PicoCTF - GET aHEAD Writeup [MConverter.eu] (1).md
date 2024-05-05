PicoCTF - GET aHEAD Writeup

Open (<http://mercury.picoctf.net:53554/>) in Firefox with Burp Suite
configured

Turn on intercept in Proxy tab, make sure Burp Suite intercept both
request and response in setting

Click button "Choose Red"

Change "GET" into "HEAD" in the first line and forward the request

flag: picoCTF{r3j3ct_th3_du4l1ty_2e5ba39f}
