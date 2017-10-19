# leejaeyung
## This is ljkstudio website test by Hugo.
[깃 사용하기]

11. 폴더를 생성 후 '윈도우키 + r' ->  'cmd' 입력 후 엔터를 하시면 다음과 같은 커맨드 창이 뜹니다. 또는 Git을 설치하셨다면 'Git Bash'로 시작하시는걸 추천드립니다.
그리고 테스트파일을 만들어서 GitHub 에 테스트를 진행해 볼건데 그 테스트 파일을 '어느경로에 만들 것인지' 길을 잡아줍니다.
cd 입력후 아까 생성한 폴더의 경로를 다음과 같이 입력해 주면 경로가 바뀌게 됩니다. 바뀐 이 경로에 1~6. 번 까지의 GitHub에 있던 테스트를 진행해 보도록 합니다.
1~6.번 까지의 명령어 용도 입니다.
1. echo "# gitest01" >> README.md : README.md 라는 파일을 만들려고 하는데 이 파일의 내용은 # gitest01 로 할께
2. git init : 현재 너가 지정해준 경로에 git 저장소를 생성할꺼야.
3. git add README.md : README.md 라는 파일을 커밋 영역에 넣어둘 준비상태에 둘꺼야. 작업공간과 저장소 사이의 대기실(index 영역 또는, stage 영역 이라고 부름)에 들어가 있어.
4. git commit -m "first commit" : 지금 대기실(index or stage area)에 있는 녀석들을 커밋장소에 들어가게되는데 지금 first commit 라는 딱지를 달고 커밋장소에 입장하게 되.
5. git remote add origin https://github.com/gitest01/gitest01.git : 이 저장소 (https://github.com/gitest01/gitest01.git)의 별칭을 origin으로 할께. 이걸 Clone(복제)하게 되면 origin 이라는 별칭을 볼 수 있을 꺼야.
6. git push -u origin master : 좋아 커밋상태에 있는 내용들을 원격저장소로 밀어보내줄께!. 다음부턴 그냥 git push 명령어만 입력해도 원격저장소로 이어질수 있게 옵션도 좀 달아줬어!


출처: http://recoveryman.tistory.com/251 [회복맨 블로그]
