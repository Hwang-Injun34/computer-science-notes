# 📚 Computer Science Notes

> 운영체제와 Linux를 중심으로 컴퓨터공학의 핵심 개념을 학습하고, 직접 정리한 문서와 실습 기록을 보관하는 저장소입니다.

개념을 단순히 암기하는 데 그치지 않고, 프로그램과 운영체제가 실제로 어떻게 동작하는지 이해하는 것을 목표로 학습하고 있습니다.

---

## 📂 Contents

| 분야 | 학습 내용 | 문서 |
|---|---|---:|
| [Operating System](./operating-system/fundamentals/) | 가상화, 병행성, I/O, 파일 시스템, 분산 시스템 | 8편 |
| [Linux Basics](./operating-system/linux/basics/) | Linux 기본 개념과 사용법 | 4편 |
| [Linux System Programming](./operating-system/labs/) | `fork`, `exec`, `pthread`, `pipe`, `socket`, Go | 6편 |
| [C](./programming/c/) | C 언어와 시스템 프로그래밍 기초 | 2편 |
| [x86-64 Assembly](./programming/assembly/) | 레지스터, 메모리, 시스템 콜 | 4편 |
| [Go Concurrency](./programming/go/concurrency/) | Goroutine, Channel, 동시성 패턴 | 6편 |
| [Linear Algebra](./mathematics/linear-algebra/) | 벡터, 행렬, 정사영, 좌표계, 텐서 | 3편 |

---

## 💻 Operating System & Linux

### Operating System

운영체제가 CPU, 메모리, 저장장치 등의 자원을 어떻게 추상화하고 관리하는지 학습한 내용입니다.

| 구분 | 주제 |
|---:|---|
| 1~3편 | 가상화 |
| 4~5편 | 병행성 |
| 6편 | I/O |
| 7편 | 디스크와 파일 시스템 |
| 8편 | 분산 시스템 |

📄 [운영체제 학습 문서 보기](./operating-system/fundamentals/)

### Linux Basics

Linux의 기본 개념과 사용법을 학습한 내용입니다.

- Linux 기본 구조
- 셸과 터미널
- 파일과 디렉터리
- 사용자와 권한
- 프로세스와 시스템 자원

📄 [Linux 기초 문서 보기](./operating-system/linux/basics/)

### Linux System Programming

운영체제에서 학습한 개념을 Linux 환경에서 직접 구현하고 확인한 기록입니다.

- `fork()`를 이용한 프로세스 생성
- `exec()`를 이용한 실행 프로그램 교체
- `pthread`를 이용한 멀티스레드 프로그래밍
- `pipe`를 이용한 프로세스 간 통신
- `socket`을 이용한 네트워크 통신
- Go를 이용한 Linux 시스템 프로그래밍

📄 [Linux 시스템 프로그래밍 실습 보기](./operating-system/labs/)

---

## 🧑‍💻 Programming Languages

### C

*Learn C the Hard Way*를 기반으로 C 언어와 시스템 프로그래밍의 기초를 학습했습니다.

- 포인터와 메모리
- 배열과 문자열
- 구조체
- 동적 메모리 할당
- 파일 입출력
- 디버깅과 오류 처리

📄 [C 학습 문서 보기](./programming/c/)

### x86-64 Assembly

CPU와 메모리 수준에서 프로그램이 동작하는 원리를 이해하기 위해 x86-64 Assembly를 학습했습니다.

- CPU 레지스터
- 메모리 주소 지정
- 스택과 함수 호출
- 조건 분기와 반복
- Linux 시스템 콜
- NASM 기반 저수준 프로그래밍

📄 [Assembly 학습 문서 보기](./programming/assembly/)

### Go Concurrency

Goroutine과 Channel을 중심으로 Go의 동시성 모델을 학습했습니다.

- Goroutine
- Channel
- Buffered Channel
- `select`
- Mutex와 WaitGroup
- Race Condition과 Deadlock
- Pipeline과 Worker Pool

📄 [Go 동시성 학습 문서 보기](./programming/go/concurrency/)

---

## 📐 Mathematics

### Linear Algebra

벡터와 행렬의 연산을 계산식뿐만 아니라 공간과 변환의 관점에서 이해하고 정리했습니다.

| 문서 | 주요 내용 |
|---|---|
| 벡터와 정사영, 텐서 | 벡터 연산, 정사영, 항등 텐서 |
| 행렬과 벡터공간 | 행렬, 선형 결합, 랭크, 영공간 |
| 벡터기하와 좌표계 | 내적, 외적, 기저, 좌표계 |

📄 [선형대수학 문서 보기](./mathematics/linear-algebra/)

---

## 📝 Documentation Principles

- 책과 기술 자료를 바탕으로 학습한 내용을 직접 이해한 방식으로 재구성합니다.
- 운영체제 이론을 Linux의 명령어와 시스템 프로그래밍 실습으로 연결합니다.
- 개념, 코드, 실행 결과 및 학습 과정에서 얻은 해석을 함께 기록합니다.
- 잘못 이해한 내용은 학습을 이어가며 지속적으로 수정하고 보완합니다.

---
