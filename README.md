## 연습문제1 - 커밋하기

1. git-example 이라는 디렉토리를 여러분의 컴퓨터에서 생성해줍니다.

2. index.html 파일을 터미널만을 이용하여 생성합니다.

3. 첫번째 커밋을 해주세요.

## 연습문제2 - 로컬 깃 레포지터리에서 깃허브 깃 레포지터리로 푸쉬

1. 깃허브에 가서 git-example 이라는 똑같은 이름의 레포지터리를 생성합니다.

2. 여러분의 컴퓨터의 git-example 깃 레포지터리에서, 방금 생성한 깃허브의 git-example 레포지터리를 연결시켜 줍니다.

3. 로컬 디렉토리의 내용을 깃허브 레포지터리로 push 해주세요.

4. 파일이 제대로 올라갔는지 깃허브에서 확인해보세요.

## 연습문제3 - 이미 존재하는 깃 레포지터리 클론 후 push

1. 로컬 머신에 있는 git-example 디렉토리를 지워주세요

2. 깃허브에 있는 git-example을 여러분의 컴퓨터로 다시 클론합니다.

3. git log를 통해 커밋 히스토리를 확인해보세요.

4. style.css 라는 파일을 만들고 새로운 커밋을 해주세요.

5. 금방 커밋한 내용을 깃허브에 push 해주고 깃허브 레포지터리를 확인하여 커밋이 제대로 올라갔는지 확인합니다.

## 연습문제4 - 브랜치 생성과 merge

1. dowonhak/js-calculator 레포지터리를 여러분의 컴퓨터로 클론합니다.

2. 여러분의 로컬 컴퓨터에 클론된 레포지터리에서 'subtract-feature' 라는 브랜치를 생성후 그 브랜치로 이동하여 줍니다.

3. `git branch`를 통하여 'subtract-feature' 브랜치로 이동이 되었는지 확인해주세요.

4. calc.js의 subtract 함수를 다른 함수들과 같게 수정하고 커밋을 해주세요.

5. master 브랜치로 이동하여 subtract-feature 브랜치를 master 브랜치로 합쳐줍니다.(merge)

6. subtract-feature 브랜치를 지워주세요.

## 연습문제5 - 실수 되돌리는 법

1. js-calculator 레포지터리에서 calc.js 파일의 add 함수의 `console.log(num1 + num2)` 문을 `return num1 + num2` 문으로 바꿔주세요.

2. 커밋을 하면서 'completed multiply function' 이라고 메세지를 잘못 입력하여 주세요.

3. 커밋 메세지를 'Completed subtract function'으로 고쳐주세요.

## 연습문제6 - 버젼 되돌아가기

1. git log를 통해 커밋 히스토리를 확인해주세요.

2. 'created calc.js' 라는 메세지를 가진 커밋으로 돌아가주세요. 워킹 디렉토리와, 스테이징 공간에 모든 변화가 사라져야 합니다.

## 연습문제7 - stash

1. calc.js 파일의 multiply 함수에 주석을 아무거나 달아주세요.

2. 파일을 저장하고, 커밋을 하지 말고, stash를 사용하여 "Working on multiply function" 이라고 메세지를 주고 stash 목록에 저장하여 줍니다.

3. 저에게 stash 목록을 보여주세요.

## 연습문제8 - 협업(fork, pull request)

1. dowonhak/ex-pullRequest를 여러분의 계정으로 fork 해주세요.

2. 여러분의 계정으로 fork 된 레포지터리를 여러분의 컴퓨터로 클론합니다.

3. dowonhak/ex-pullRequest의 issue란에 가셔서 여러분의 맞는 이슈를 찾으셔서, issue 이름에 맞는 브랜치를 생성해주세요.

4. 방금 생성한 브랜치에서, issue의 내용에 맞는 작업을 해준 후, **여러분의 레포지터리로** push 하여 줍니다. push를 하실때, 지금 작업하시고 계신 브랜치 이름으로 push하여 주세요.

5. pull request를 해주시면 됩니다. pull request를 하실 때 여러분의 이슈를 본문에서 언급해주세요.


