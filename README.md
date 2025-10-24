>이 저장소는 C++ 학습을 위한 STL, 알고리즘 문제 풀이를 정리한 공간입니다.
---

## 📂 분류
###
```
STL/
├──Containers/
│ └── vector/
│   └── main.cpp
algorithm/
├──Boj/
│ └── 1000/
│   └── main.cpp
```

## 💡 커밋 메시지 규칙

- `stl: STL 실습 완료`
- `solve: 문제 풀이 완료`
- `docs: 문서 편집`
- `chore: 디렉토리 수정`

## 🔷 STL 구성 요소 요약

| 대분류          | 주요 구성 요소 예시                         | 설명                                 |
|------------------|--------------------------------------------|--------------------------------------|
| Containers       | `vector`, `map`, `set`, `deque` 등          | 데이터를 저장하고 관리하는 자료구조 |
| Algorithms       | `sort`, `find`, `accumulate`, `remove` 등  | 컨테이너 데이터를 처리하는 함수들   |
| Iterators        | `begin()`, `end()`, `advance()` 등          | 컨테이너 내부 데이터를 순회하는 도구|
| Function Objects | `less`, `greater`, `function`, 람다         | 함수처럼 동작하는 객체               |
| Utilities        | `pair`, `tuple`, `optional`, `variant` 등   | STL 사용을 보조하는 도구들          |
| Adapters         | `stack`, `queue`, `priority_queue`          | 특정 자료구조를 쉽게 사용할 수 있도록 구성된 어댑터 |

---

## 📦 STL 컨테이너 분류

| 분류                        | 컨테이너 예시                             |
|-----------------------------|-------------------------------------------|
| Sequence Containers          | `vector`, `deque`, `list`, `array`        |
| Associative Containers       | `set`, `map`, `multiset`, `multimap`      |
| Unordered Associative        | `unordered_set`, `unordered_map` 등       |
| Container Adapters           | `stack`, `queue`, `priority_queue`        |

---

## ⚙️ STL 알고리즘 분류

| 범주          | 함수 예시                                      |
|---------------|------------------------------------------------|
| 정렬           | `sort`, `stable_sort`, `nth_element`           |
| 검색           | `find`, `binary_search`, `count`               |
| 수정           | `reverse`, `remove`, `unique`                 |
| 누적/반복       | `accumulate`, `for_each`, `transform`         |
| 조건 판단       | `all_of`, `any_of`, `none_of`                 |

> 사용 시 `<algorithm>` 헤더 필요

---

## 🔁 이터레이터 종류

| 종류             | 예시 컨테이너       | 특징                          |
|------------------|----------------------|-------------------------------|
| 입력 반복자        | `istream_iterator`   | 한 방향 입력                  |
| 출력 반복자        | `ostream_iterator`   | 한 방향 출력                  |
| 전방 반복자        | `forward_list`       | 한 방향 여러 번 순회 가능     |
| 양방향 반복자      | `list`, `set`        | 앞뒤 이동 가능                |
| 임의 접근 반복자   | `vector`, `deque`    | 인덱스 기반 접근              |

---

## 🧩 함수 객체 & 람다

| 항목           | 예시                              | 설명                     |
|----------------|------------------------------------|--------------------------|
| 비교 함수 객체  | `greater<int>`, `less<int>`        | 정렬 기준 변경에 사용     |
| 람다 표현식     | `[](int x){ return x % 2 == 0; }`  | 즉석 함수 선언 가능       |
| std::function | `std::function<void(int)>`         | 함수 객체 래퍼           |

---

## 🔧 유틸리티 도구

| 도구           | 예시                      | 설명                           |
|----------------|---------------------------|--------------------------------|
| `pair`         | `pair<int, string>`        | 두 값 묶기                      |
| `tuple`        | `tuple<int, string, bool>` | 여러 값 묶기                    |
| `optional`     | `optional<int>`            | 값이 없을 수도 있는 객체        |
| `variant`      | `variant<int, string>`     | 여러 타입 중 하나를 담는 객체   |

---

## 📄 알고리즘 문제 풀이 목록

| 번호 | 플랫폼 | 제목 | 코드 |
|------|--------|------|------|
| 42576 | 프로그래머스 | 완주 하지못한 선수 | [🔗 코드 보기](./Programmers/42576/main.cpp) |
| 42577 | 프로그래머스 | 전화번호 목록 | [🔗 코드 보기](./Programmers/42577/main.cpp) |
| 42748 | 프로그래머스 | K번째수 | [🔗 코드 보기](./Programmers/42748/main.cpp) |
| 12906 | 프로그래머스 | 같은 숫자는 싫어 | [🔗 코드 보기](./Programmers/12906/main.cpp) |
| 42746 | 프로그래머스 | 가장 큰 수 | [🔗 코드 보기](./Programmers/42746/main.cpp) |
| 42587 | 프로그래머스 | 프로세스 | [🔗 코드 보기](./Programmers/42587/main.cpp) |
| 12915 | 프로그래머스 | 문자열 내 마음대로 정렬하기 | [🔗 코드 보기](./Programmers/12915/main.cpp) |
| 17682 | 프로그래머스 | 2018 KAKAO BLIND RECRUITMENT [1차] 다트 게임 | [🔗 코드 보기](./Programmers/17682/main.cpp) |
| 43165 | 프로그래머스 | 타겟 넘버 | [🔗 코드 보기](./Programmers/0/43165.cpp) |
| 43162 | 프로그래머스 | 네트워크 | [🔗 코드 보기](./Programmers/43162/main.cpp) |
| 43163 | 프로그래머스 | 단어 변환 | [🔗 코드 보기](./Programmers/43163/main.cpp) |
| 43164 | 프로그래머스 | 여행경로 | [🔗 코드 보기](./Programmers/43164/main.cpp) |
| 49189 | 프로그래머스 | 가장 먼 노드 | [🔗 코드 보기](./Programmers/49189/main.cpp) |
| 12939 | 프로그래머스 | 최댓값과 최솟값 | [🔗 코드 보기](./Programmers/12939/main.cpp) |
| 12909 | 프로그래머스 | 올바른 괄호 | [🔗 코드 보기](./Programmers/12909/main.cpp) |
| 12941 | 프로그래머스 | 최솟값 만들기 | [🔗 코드 보기](./Programmers/12941/main.cpp) |
| 12951 | 프로그래머스 | JadenCase 문자열 만들기 | [🔗 코드 보기](./Programmers/12951/main.cpp) |


<!--
| 0 | 프로그래머스 | 제목 | [🔗 코드 보기](./Programmers/0/main.cpp) |