---
layout: default
title: Markdown Practice
permalink: /markdown-practice/
---

{% raw %}{% include navigation.html %}{% endraw %}

# Markdown Practice

Markdown 문법을 익히기 위한 연습 페이지입니다.

## 1. 제목과 글자 강조

# 제목 1
## 제목 2
### 제목 3

일반 텍스트 입니다.

**굵게 표시할 내용입니다.**

*기울임으로 표시할 내용입니다.*

~~취소선을 표시할 내용입니다.~~

## 2. 목록 만들기

순서가 없는 목록:

- Python
- C#
- Unity
- AI

순서가 있는 목록:

1. 개념 학습
2. 코드 작성
3. 실행 및 테스트
4. 결과 정리

## 3. 링크와 인용문

[Github 바로가기](http://github.com/ChoiGood)

> 직접 실습하고 결과를 확인하는 것이 중요합니다.

## 4. 코드 블록

Python 코드:

```python
def greet(name):
  print(f"Hello, {name}!")

greet("ChoiGood")
```

C# 코드:

```csharp
using UnityEngine;

public class Player : MonoBehaviour
{
  void Start()
  {
    Debug.Log("Hello Unity!");
  }
}
```

## 5. 표 만들기

| 기술 | 용도 |
|---|---|
| Python | AI 및 데이터 처리 |
| C# | Unity 게임 개발 |
| Markdown | 문서 작성 |
| Git | 버전 관리 |

## 6. 체크리스트

- [x] Markdown 파일 생성
- [x] 제목과 목록 작성
- [ ] 코드 블록 연습
- [ ] Git과 VS Code 연동

## 7. 이미지 삽입

이미지는 다음 문법으로 삽입할 수 있습니다.

```markdown
![이미지 설명](이미지 주소)
```

## 학습 정리

오늘은 Markdown의 기본 문법과 코드 블록 작성 방법을 연습했습니다.

---

## Git 연동 실습

이번에는 VS Code에서 Markdown 파일을 수정하고,
Git을 사용해 GitHub 저장소에 반영했습니다.

- 작업 환경: Visual Studio Code
- 버전 관리: Git
- 원격 저장소: GitHub
- 배포: GitHub Pages

