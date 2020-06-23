# 내부 시스템에서 HTTPS 호출 시 발생하는 bad handshake.. SSL error

내부 시스템은 local 인증서를 사용하기 때문에
어느 정도 사용하다 보면 발생하게 된다. 

이는 requests 호출 시 옵션으로 verify=false를 주면 해결할 수 있다.

```python
request.get(url, verify=false)
```
