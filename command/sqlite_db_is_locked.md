# sqlite is locked

sqlite3는 동시 접속이 가능하지 않기 때문에 close() call 없이 동시 접속 시 datebase가 막히게 된다.
이때 강제로 db process를 풀어주면 해결할 수 있다.

~~~shell
> fuser db.name
> kill -9 1234
~~~

