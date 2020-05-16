# vscode html, json 파일에 indent 적용하기

기본적으로 OS설정을 따라 indent가 적용되는데 파일 별로 설정을 다르게 하려면
프로젝트 내 설정 파일을 바꿔서 해결할 수 있다.

~~~json
{
    "files.insertFinalNewline": true,
    "files.trimTrailingWhitespace": true,
    "[html]": {
      "editor.insertSpaces": true,
      "editor.tabSize": 2
    },
    "[json]": {
        "editor.insertSpaces": true,
        "editor.tabSize": 2
    }
}
~~~

