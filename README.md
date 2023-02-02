# HoRi0506.github.io

이 프로젝트는 github blog를 html로 구현하는 것입니다.

See [Demo](https://HoRi0506.github.io/)

## 설명(Described)

github flavored markdown은 수식 표현을 제공합니다.

예를 들면,

### Binet's formula

$F_n=\dfrac{\left(\dfrac{1+\sqrt{5}}{2}\right)^n-\left(\dfrac{1-\sqrt{5}}{2}\right)^n}{\sqrt{5}}$

or

```math
$F_n=\dfrac{\left(\dfrac{1+\sqrt{5}}{2}\right)^n-\left(\dfrac{1-\sqrt{5}}{2}\right)^n}{\sqrt{5}}$
```

## 설치하는 법(How to install)

```shell
$ git clone {addr}
$ cd {repo name}
$ pip install -r requirements.txt
```

## 시작하는 법(How to start)

```shell
$ python main.py
```

## 기능 설명

## 정답 확인하는 함수

```python
def checker(answer: int, guess: int) -> bool:
	if guess==answer:
		print('Correct!')
	else:
		print('Wrong!')
```

## 더 많은 정보

- [google](https://www.google.co.kr)
