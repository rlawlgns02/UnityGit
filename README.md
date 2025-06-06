# UnityGit
## 게임프로젝트와 깃허브 연동하는법

## 1. 레포 생성하기
- 게임의 이름또는 가상의 프로젝트 이름을 레포 이름으로 정한다
- 만약 공개를 원하면 `Public` 비공개로 하고 싶다면 `Private`를 선택한다 (일반적으로 `Private` 추천)
- README파일은 따로 추가하지 않는다(체크 안함)
- [ ] Add a README file (그대로 놔둠) 
- **중요** Add.gitignore에서 Unity라면 Unity , UnrealEngine이라면 UnrealEngine선택<br>
![image](https://github.com/user-attachments/assets/964a85bd-2fc1-4a2f-9171-b83cb041c51e)
- 다 만든 후에 Create repository 클릭
![image](https://github.com/user-attachments/assets/ee88fc4f-3f04-4045-8af5-f0b519d98180)

## 2. 공동 작업자 추가
- 레포를 만든 후에 Settings - Collaborators로 이동
![image](https://github.com/user-attachments/assets/90f9c94d-931b-438e-87d1-bb5fb9049873)
- Add people을 누른후에 공동 작업자의 username, fullname, email중 아무것이나 입력
![image](https://github.com/user-attachments/assets/682aa24e-5522-4835-b0ba-819f5deb4829)
- 프로필을 선택한 후에 `Add to repository`클릭 <br>
![image](https://github.com/user-attachments/assets/18ae5c00-e1f1-4497-b6de-d3349ee95f27)
- 초대 받은 작업자는 이메일 확인 후 수락

## 3. github 연동
- `<> Code` 부분을 눌러서 `Open With GitHub Desktop` 클릭
![image](https://github.com/user-attachments/assets/91ccec38-29cb-45cc-811e-b0d5f93575fa)
- 만약 GitHub Desktop이 없다면 `https://github.com/apps/desktop` 에서 다운로드
- 보통 바로 열리지만 만약 바로 열리지 않았다면 URL을 이용해 클론

## 4. github 업로드
- 만약 자신의 게임 프로젝트를 올리고 싶다면 `Push origin` 버튼 클릭
