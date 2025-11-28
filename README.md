# opensource-sw-homework
top, ps, jobs, kill
# 🐧 Linux 프로세스 관리 명령어 조사 (과제 #2)

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## 🎯 개요
이 문서는 **'오픈소스SW개론'** 과제 #2로, Linux의 주요 프로세스 및 작업 관리 명령어인 `top`, `ps`, `jobs`, `kill`에 대해 조사한 결과를 정리했습니다. 

---

## 1. 📈 top (시스템 실시간 모니터링)

`top` 명령어는 시스템의 **실시간 상태**와 실행 중인 **프로세스 활동**을 동적으로 확인하는 데 사용됩니다.

### 📋 주요 기능
* **자원 모니터링**: CPU, 메모리 사용량, 실행 시간 등 시스템 자원 사용 현황을 동적으로 표시합니다.
* **실시간 갱신**: 기본적으로 3초마다 화면을 갱신합니다.

### 💻 사용 예시
    ```bash
# 기본 실행
    top
    ```
# 종료 시 'q' 키 입력
