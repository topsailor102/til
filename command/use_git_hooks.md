# pre-commit

git commit 시 확인하고 싶은 문법이나 rule을 자동으로 적용할 수 있는 방법이다.
.git/hoooks/ 폴더가 기본적으로 동작하는 파일들이 모여 있지만,
Git 2.9 부터hook 경로를 변경할 수 있게되어 공유 가능하게 되었다.

기본적인 사용 방법은 .git/hooks/xxx.sample 파일에서 확장자인 .sample을 제거한 후,
실행 권한 (chmod +x xxx)을 주면 동작하게 된다. 

## [참고할 만한 사이트]
* [나쁜 commit 막기](https://medium.com/@ikaruce/git-나쁜-commit을-막기-10a906bc8352)
* [Git Hooks Example](https://support.gitkraken.com/working-with-repositories/githooksexample/)

