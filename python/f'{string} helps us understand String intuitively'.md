# [PEP 498 -- Literal String Interpolation](https://www.python.org/dev/peps/pep-0498/)

ver 3.6부터 적용된 이 형식은 기존에 % 나 .format의 형태로 변수를 문장에 적용하던 방식에서
직관적으로 이해가 가능하도록 변경되었다.

```python
person = "Mina"
skill = "f-string"
level = f'{person} can use {skill} as of now.'
```
