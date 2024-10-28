## Hi Farmer!! 👋 
<img src="https://img.shields.io/badge/Python-3DDC84?style=flat-square&logo=Python&logoColor=blue&fontColor=yellow"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=D260F7&width=435&lines=Python+Backend+Developer" alt="Typing SVG" /></a>

# CLI 작업 관리 애플리케이션

Python으로 만든 간단한 커맨드 라인 인터페이스(CLI) 작업 관리 애플리케이션입니다. 사용자가 명령줄을 통해 할 일을 추가, 조회, 완료, 삭제할 수 있으며, 작업 정보는 JSON 파일에 저장됩니다.

## 목차
- [사용 기술](#사용-기술)
- [기능](#기능)
- [설치](#설치)
- [사용법](#사용법)
- [작동 화면](#작동-화면)
- [브랜치 전략](#브랜치-전략)
- [기여하기](#기여하기)

## 사용 기술

- **Python**: 핵심 프로그래밍 언어로 사용.
- **JSON**: 작업 데이터를 저장하고 불러오기 위해 사용.
- **Git**: 버전 관리를 위해 사용하며, 프로젝트의 브랜치를 관리하고 변경 사항을 추적.

## 기능

- **할 일 추가**: 사용자가 새로운 작업을 간단하게 추가할 수 있습니다.
- **할 일 조회**: 모든 작업과 그 상태(완료 또는 미완료)를 리스트 형태로 보여줍니다.
- **할 일 완료 표시**: 작업을 완료로 표시할 수 있습니다.
- **할 일 삭제**: 특정 작업을 목록에서 삭제할 수 있습니다.
- **영구 저장**: JSON 파일(`tasks.json`)에 데이터를 저장하여 프로그램 종료 후에도 작업을 유지합니다.

## 설치

1. **저장소 클론**:
    ```bash
    git clone https://github.com/your-username/cli-task-manager.git
    cd cli-task-manager
    ```

2. **Python 설치 확인**:
    - 이 프로젝트는 Python 3.6 이상이 필요합니다. [Python 다운로드 링크](https://www.python.org/downloads/)에서 설치할 수 있습니다.

3. **애플리케이션 실행**:
    ```bash
    python task_manager.py
    ```

## 사용법

프로그램을 실행하면 다음과 같은 메뉴가 나타납니다:

