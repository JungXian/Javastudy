1. 깃 시작하기
<img width="525" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/e115cad8-ecb6-41a6-a865-671848ad8ad8">

git init 명령어로 폴더 생성



2. commit, revert, reset 체험하기


<img width="494" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/e54da4a3-ad7c-4182-9a8d-b113ba8e9420">


git status 명령어를 입력하여 추가된 파일 생성


<img width="368" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/0d952f65-e7b5-4be2-9589-8ab3b0654918">

git add 명령어 입력하여 Commit 준비 

<img width="458" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/69aef554-93fc-41d4-998f-15351aa0fc2a">

git status로 상태 확인

<img width="463" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/c386acc1-1e40-471a-b37f-eb7ce795ed01">

git add . 명령어로 파일 추가
현재 사진으로 뜨는 이유는 git-practice안에 JavaStudy파일이 생성되어있기 때문


<img width="410" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/7b404c55-6385-491e-813c-4e9b381410ea">

git commit 명령어를 이용하여 VIM모드 전환


<img width="391" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/536216af-d3fd-40b0-8cbc-e52cdb86a5ca">

i -> first commit -> Esc -> :q 순서대로 명령어 입력

<img width="378" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/04408547-9ecb-4ca5-90d5-9650e75aba80">

:Q! 입력하여 VIM모드 헤제


------------------------VIM 명령어----------------------------

입력 시작 ; i

입력 종료 : esc

저장 없이 종료 : :q

저장 없이 강제 종료 : :q!

저장하고 종료 : :wq

위로 스크롤 : K

아래로 스크롤 : J



<img width="335" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/1b72f725-e2eb-40ed-bf45-08efbea153ed">

git diff 명령어를 입력하여 구체적으로 보여줌

<img width="404" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/4a512b59-d72b-4e7b-8600-4e521dc3aa19">


git commit -m을 입력


<img width="398" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/3e8d0eb1-3649-4881-a557-af8cbd8c2542">


git log를 이용하여 내역 확인


<img width="379" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/508baddf-1951-4ad4-8bf8-6d84132af2c2">

git commit -am 으로 명령 한번에 적용


<img width="784" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/f33ade95-69e4-4af2-bcc1-c3919307d995">

소스트리에 변경된 것 확인 가능


<img width="425" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/52870c51-b501-48ce-a8c0-d0ef66310a48">

commit을 이용하여 변경사항 저장 


<img width="425" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/289ac967-16b9-48a8-ae48-261cfe312a3a">

Commit 내역 확인


<img width="386" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/273bb019-9e86-4fdf-b401-9d605ea61154">

git revert를 이용하여 Add George to Tigers 변화 복구


revrt를 이용하여 충돌 작업 체험

<img width="736" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/0515b828-b437-45e0-91d0-ab2df18d344e">

revert가 제대로 수행되지 않고 오류 발생


<img width="455" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/8caf3061-1fa8-4c2a-aa45-a480c6610b50">

git rm명령을 이용해 파일 삭제 후 revert --continue로 작업 재개

<img width="392" alt="image" src="https://github.com/JungXian/Javastudy/assets/160801488/4ad90bf5-d92f-4f58-b74d-dec86850c585">

git reset --hard를 이용하여 리버트 이전으로 되돌리기

