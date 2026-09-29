# Python Print Examples — Jupyter Notebook Guide

이 저장소는 Python의 다양한 `print()` 사용법과 실행 결과를 Cell 단위로 쉽게 확인할 수 있는 Jupyter Notebook 형식의 예제 가이드입니다.

---

## 파일 목록

### 1) `main_print_v1.ipynb`
- **설명**: `print()` 활용 종합 예제를 셀(Cell) 단위로 구분한 대화형 실습 노트.
- **동작/기능**:
  - 기본 출력 및 옵션 활용 (`sep`, `end`)
  - 다양한 포맷팅 방식 (f-string, `str.format()`, `%` 포맷팅)
  - 딕셔너리 출력 및 여러 줄 출력 (`\n`, 삼중따옴표)
  - f-string 내 연산식 및 함수 적용 예제
  - 코드 셀별 즉시 실행 결과 확인 가능
- **실행 방법**:
  - **VS Code**: 
    1. 파일 열기 (`main_print_v1.ipynb`)
    2. 우측 상단 **Select Kernel** 클릭 후 Python 환경 선택
    3. 각 셀 좌측의 **Run Cell (▶)** 버튼 클릭 또는 `Shift + Enter`
  - **Jupyter Lab / Notebook**:
    - 터미널에서 `jupyter lab` 또는 `jupyter notebook` 실행 후 해당 파일 열기

---

## 필수 설치 요소 (Requirements)

Notebook 환경 실행을 위해 아래 패키지 설치가 필요합니다:

```bash
pip install jupyter ipykernel

# Python Print Examples — Quick Guide

이 저장소는 Python의 다양한 `print()` 사용법을 기본 출력부터 f-string, format() 함수, 옵션 활용까지 한눈에 파악할 수 있도록 정리한 예제입니다.

---

## 파일 목록

### 1) `main_print_v1.py`
- **설명**: 표준 `print()` 함수 활용법 종합 예제.
- **동작/기능**:
  - **기본 및 다중값 출력**: 콤마(`,`) 구분을 이용한 자동 띄어쓰기 출력
  - **문자열 포맷팅**:
    - `f-string` (Python 3.6+ 권장 방식)
    - `str.format()` 함수 활용
    - `%` 포맷팅 (C언어 스타일 서식 지정자)
  - **줄바꿈 및 구분자 옵션**: `end`, `sep` 옵션 제어
  - **복합 자료형 출력**: 딕셔너리 및 데이터 구조체 출력
  - **f-string 응용**: 내부 연산자/함수 호출 및 멀티라인(`"""`) 서식 출력
- **실행 방법**:
  - **VS Code**: 파일 열기 후 우측 상단 **Run Python File (▶)** 클릭
  - **터미널**:
    - Windows: `python main_print_v1.py` (또는 `py main_print_v1.py`)
    - macOS/Linux: `python3 main_print_v1.py`

    # Python Print Examples — Rich Library Guide

이 저장소는 `rich` 라이브러리를 활용해 콘솔 출력을 스타일리시한 컬러, 패널(박스), 테이블 형태로 시각화하는 방법을 정리한 예제입니다.

---

## 파일 목록

### 2) `main_print_v2.py`
- **설명**: `rich` 라이브러리를 활용한 고성능 콘솔 출력 예제.
- **동작/기능**:
  - **스타일/컬러 텍스트 출력**: `rprint()` 및 마크업 태그(`[bold green]`, `[cyan]` 등)를 통한 텍스트 스타일링
  - **패널(Panel) 출력**: 테두리가 있는 박스 형태의 멀티라인 프로필 정보 시각화
  - **테이블(Table) 출력**: 딕셔너리/레코드 데이터를 깔끔한 표(Table) 형태로 구성하여 출력
  - **표준 옵션 지원**: `rich.print`에서도 `sep`, `end` 옵션을 동일하게 활용 가능
- **실행 준비**:
  ```bash
  pip install rich

  # Python Print Examples — Requirements Guide

이 저장소의 예제 코드 및 Jupyter Notebook 환경을 실행하기 위해 필요한 주요 파이썬 패키지 의존성 목록입니다.

---

## 파일 목록

### 3) `requirements.txt`
- **설명**: 프로젝트 실행에 필요한 외부 라이브러리 및 실행 환경 패키지 버전 정보.
- **주요 패키지 구성**:
  - **콘솔 스타일링**: `rich` (터미널 서식/테이블/패널 출력)
  - **Jupyter Notebook 커널**: `ipykernel`, `ipython`, `jupyter_client`, `jupyter_core`
  - **코드 강조 및 텍스트 파싱**: `Pygments`, `markdown-it-py`, `colorama`
  - **비동기 및 유틸리티**: `pyzmq`, `tornado`, `psutil`, `traitlets`
- **설치 방법**:
  - 프로젝트 루트 디렉터리에서 아래 명령어를 실행하여 모든 의존성 패키지를 한 번에 설치합니다.
  - **Windows / macOS / Linux**:
    ```bash
    pip install -r requirements.txt
    ```