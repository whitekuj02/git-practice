# 5주차 Shell Commands (CLI-2)

| 명령어·기호 | 역할 | 예시 |
| --- | --- | --- |
| `>` | 명령어 출력을 파일에 저장 | `ls -lh > file_list.txt` |
| `>>` | 출력을 파일 끝에 추가 | `ls -lh >> file_list.txt` |
| `cat` | 텍스트 파일 내용 출력 | `cat file_list.txt` |
| `<` | 파일을 표준 입력으로 사용 | `sort < words.txt` |
| `sort` | 입력 내용을 정렬하여 출력 | `sort < words.txt > sorted_words.txt` |
| `\|` | 앞 명령어의 출력을 다음 명령어의 입력으로 전달 | `ls -lh \| less` |
| `less` | 출력을 화면 단위로 확인 (`q`로 종료) | `ls -lh \| less` |
| `wc -l` | 입력의 줄 수 계산 | `ls \| wc -l` |
| `echo` | 문자열 출력 | `echo "Hello Shell Script!"` |
| `*` | 일치하는 파일·디렉터리 이름으로 확장 | `echo *` |
| `~` | 현재 사용자의 홈 디렉터리 경로로 확장 | `echo ~` |
| `\` (줄 끝) | 긴 명령어를 다음 줄에 이어서 입력 | `ls -l \`<br>`-h` |
| `ls -l` | 파일의 권한 등 상세 정보 확인 | `ls -l` |
| `chmod 600` | 소유자만 읽기·쓰기 가능하도록 권한 변경 | `chmod 600 README.md` |
| `chmod 644` | 소유자는 읽기·쓰기, 그룹·기타 사용자는 읽기만 허용 | `chmod 644 words.txt` |
| `sudo` | 관리자 권한으로 명령어 실행 | `sudo some_command` |
| `sudo -i` | 관리자 셸 세션 시작 | `sudo -i` |
| `exit` | 관리자 셸 세션 종료 | `exit` |
| `nano` | 텍스트 파일 작성·편집 | `nano myscript.sh` |
| `sh` | 셸 스크립트 실행 | `sh myscript.sh` |
| `history` | 이전에 실행한 명령어 확인·저장 | `history`<br>`history > history_command.txt` |
| `wget` | 인터넷 파일을 현재 디렉터리에 다운로드 | `wget URL` |
| `curl -o` | 파일 이름을 지정하여 다운로드 | `curl -o horse.jpg URL` |
| `curl -O` | 원래 파일 이름으로 다운로드 | `curl -O URL` |
| `grep` | 검색어와 일치하는 줄 출력 | `grep "test" file.txt` |
| `grep -i` | 대소문자를 구분하지 않고 검색 | `grep -i "test" file.txt` |
| `grep -v` | 검색어와 일치하지 않는 줄 출력 | `grep -v "test" file.txt` |
| `grep -n` | 검색 결과에 줄 번호 표시 | `grep -n "test" file.txt` |
| `grep -r` | 디렉터리와 하위 디렉터리의 파일까지 검색 | `grep -r "test" ./` |

