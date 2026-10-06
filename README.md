# SoftKorea-T-SUM
TSUM 프로젝트 활동

여러분들은 각자 브랜치라는 것을 만들 겁니다. 

브랜치란 쉽게말해 자신만의 작업 공간이고,
main은 우리 모두의 작업 결과물이라고 보면 됩니다.

즉 main은 온전하고, branch는 불온전한 개발 작업 공간이라고 생각하면 됩니다.

여러분들이 branch를 생성한 뒤 main에다가 merge를 시도하면 해당 레포지토리의 주인인 제가 pull request를 받게 됩니다. 저는 여러분들이 pull request를 날리면 그걸 main에다가 통합을 할지, 아니면 거절을 할지를 선택합니다. 

이런 과정을 통해 계속해서 main을 구성해나가는것이 저희들이 할 일입니다. 

브랜치는 다음과 같은 방식으로 만듭니다.
1. 명령 프롬프트에 git clone <레포지토리_주소> 를 입력하세요.
2. 브랜치 명은 자신의 영어이름으로 하겠습니다. ex) wooyoung
3. git checkout -b 본인영어이름 (내가 지금 어떤 브랜치에 있는지 확인하고 싶다면 git branch를 터미널에 입력)
4.git add . // 내가 오늘 작업한 내용 추가
5. git commit -m "대충 뭐 했습니다."
6.git push origin 본인 브랜치 이름.

즉 작업 순서는 add => commit => push 순서 입니다. 꼭 기억하세요.

7. 마지막으로 깃허브 사이트에 가서 pull request를 하면 끝!! 해당 repository의 주인인 제가 accept를 하면 여러분들의 작업이 main에 등록되게 됩니다.


