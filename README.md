# C 언어 쉘 프로그램

## 목차
1. [소개](#소개)
2. [주요 기술](#주요-기술)
3. [설치 및 실행 방법](#설치-및-실행-방법)
4. [사용법](#사용법)
5. [실행 화면](#실행-화면)

---

## 소개

이 프로젝트는 C 언어로 시스템 라이브러리를 이용하여 쉘과 쉘 명령어를 구현한 것입니다. 사용자는 쉘을 통해 다양한 명령어를 실행할 수 있으며, cd, cat, rm, ls, mkdir 등의 기능을 수행할 수 있습니다. 또한, 사용자 명령어는 백그라운드 실행 및 리다이렉션을 지원합니다.

---

## 주요 기술

- **C 언어 라이브러리**: `<stdio.h>`, `<stdlib.h>`, `<string.h>`, `<unistd.h>`, `<stdbool.h>`, `<sys/wait.h>`, `<limits.h>`, `<signal.h>`
- **프로세스 제어**: `fork()`, `execvp()`, `wait()`
- **신호 처리**: `signal()`
- **디렉터리 조작**: `chdir()`, `getcwd()`

---

## 설치 및 실행 방법

1. 쉘 프로그램을 컴파일합니다:
   ```bash
   gcc -o main main.c

2. 쉘을 실행합니다:
   ```bash
   ./main

---

## 사용법
- 쉘 사용법
  - 쉘을 실행하고 프롬프트에서 명령어를 입력합니다.
  - cd <directory> 명령어를 통해 디렉터리를 변경할 수 있습니다.
  - exit 명령어를 통해 쉘을 종료할 수 있습니다.
  - & 기호를 사용하여 명령어를 백그라운드에서 실행할 수 있습니다.
  - <, >, | 기호를 사용하여 입력, 출력 리다이렉션 및 파이프를 사용할 수 있습니다. 
- 명령어 목록
   - cat, cd, cp, ln, ls, mkdir, mv, pwd, rm, rmdir, pipe, redirection, &

---

## 실행화면   
![run](https://github.com/Sihyeon0123/System-Programing-Team-Project-I/assets/129951793/7ba3a35d-a9f4-4c87-8f24-20099767927f)
