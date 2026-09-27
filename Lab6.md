# 6주차 Git Commands (Git-1)

| 명령어 | 역할 | 예시 |
| --- | --- | --- |
| `git --version` | 설치된 Git 버전 확인 | `git --version` |
| `sudo apt install git-all` | Debian 계열 Linux에 Git 설치 | `sudo apt install git-all` |
| `git config --global user.name` | 사용자 이름 설정(전역) | `git config --global user.name "이름"` |
| `git config --global user.email` | 사용자 이메일 설정(전역) | `git config --global user.email name@example.com` |
| `git config --global init.defaultBranch` | 새 저장소의 기본 브랜치 이름 설정 | `git config --global init.defaultBranch main` |
| `git config --list` | Git 설정 목록 확인 | `git config --list` |
| `git config --list --show-origin` | 설정값과 해당 설정의 출처 확인 | `git config --list --show-origin` |
| `git config user.name` | 설정된 사용자 이름 확인 | `git config user.name` |
| `git init` | 현재 디렉터리에 Git 저장소 초기화 | `git init` |
| `git status` | 저장소와 파일의 상태 확인 | `git status` |
| `git add` | 지정한 파일을 스테이징하여 커밋 준비 | `git add README.md`<br>`git add main.py words.txt` |
| `nano` | 텍스트 파일 작성·편집 | `nano words.txt` |
| `git add .` | 현재 디렉터리와 하위 파일들을 한꺼번에 스테이징 | `git add .` |
| `git rm --cached` | 새로 추가한 파일의 스테이징 취소(첫 커밋 전) | `git rm --cached file_list.txt` |
| `nano .gitignore` | Git에서 무시할 파일 목록 작성 | `nano .gitignore` 실행 후 `file_list.txt` 입력 |
| `git commit -m` | 스테이징한 내용을 메시지와 함께 커밋 | `git commit -m "initial commit"` |
| `git log` | 커밋 기록 확인 | `git log` |
| `git branch` | 브랜치 목록과 현재 브랜치 확인 | `git branch` |
| `git branch -m` | 브랜치 이름 변경 | `git branch -m master main` |

