## 입9팔9
목업이미지 
<a href=""> 최종 발표 영상 </a>

<br>

## 🗼 배포
<a href=""> 서비스링크 </a>
서비스 이용을 위한 테스트 계정

- ID: 21test@test.com
- Password: 123456
  <br>

## 1. 프로젝트 소개

> 데일리룩과 취향을 공유하며 지속가능한 패션을 함께 만들어가는 서비스

 <br>

## 2. 팀원소개<br>

|                                                                        최범관                                                                         |                                                                        박경보                                                                         |                                                                        유하은                                                                         |                                                                         한상헌                                                                         |
| :---------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://github.com/yonainthefish/FE05-Project-Sooryen/assets/124084624/4ac018c7-f9f3-49c1-89e8-9e0523c69919.jpg" width="170" height="170"/> | <img src="https://github.com/yonainthefish/FE05-Project-Sooryen/assets/124084624/f8f06190-ece0-4a5d-ada4-d7df6cca0455.png" width="170" height="170"/> | <img src="https://github.com/yonainthefish/FE05-Project-Sooryen/assets/124084624/dac4ccc0-c4c2-4240-8e4b-067a4b2eeb7d.jpg" width="170" height="170"/> | <img src="https://github.com/yonainthefish/FE05-Project-Sooryen/assets/124084624/9d2c1f67-82c0-4d91-8bf9-09be962044f4.jpg" width="170" height="170" /> |
                                                                  
|                                                 <a href="https://github.com/KwanBeom">🔗 KwanBeom </a>                                                  |                                              <a href="https://github.com/kyeongboo-coder">🔗 kyeongboo-coder </a>                                              |                                               <a href="https://github.com/yonsinthefish">🔗 yonainthefish </a>                                               |                                                 <a href="https://github.com/Skyllerrr">🔗 skyllerrr </a>                                                  |
|                                <img src="https://img.shields.io/badge/FrontEnd-3178C6?style=plastic&logoColor=blue"/>                                 |                                <img src="https://img.shields.io/badge/FrontEnd-3178C6?style=plastic&logoColor=blue"/>                                 |                                <img src="https://img.shields.io/badge/FrontEnd-3178C6?style=plastic&logoColor=blue"/>                                 |                                 <img src="https://img.shields.io/badge/FrontEnd-3178C6?style=plastic&logoColor=blue"/>                                 |



## 3. 개발 환경<br>

### [Github flow]
 ```
팀원 간의 코드리뷰와 소통이 강조되는 GitHub Flow를 사용하여 작업을 진행했습니다.
main, feat 브랜치를 사용하였고, 각 페이지의 기능별로 feature 브랜치를 생성하여 코드리뷰 후 PR을 통해 main에 merge하는 방식으로 협업하였습니다.
```

### [코드컨벤션]
```
코트 컨벤션 자동화
Prettier를 활용해 자신이 작성한 코드를 정해진 코딩 스타일에 맞게 변환할 수 있습니다.
ESLint를 활용해 자신이 작성한 코드 품질이 괜찮은지 검사할 수 있습니다.

```

### [커밋컨벤션]
```
Feat : 기능 추가 (브랜치 맨처음 커밋, 기능 추가)
Add : 코드 추가 (어떠한 기능 내에 기능을 더 추가)
Modify : 코드 수정, 파일 삭제(버그 수정, 코드 지우고, 추가하고, 수정하는 모든 과정들)
Style : 컴포넌트 및 UI 구현 (스타일드 컴포넌트)
Delete : 코드 삭제
```


### [폴더구조]
```
 입9팔9
├── public
└── src
    ├── assets/images
    ├── components
    ├── contexts/ModalContext
    ├── hooks
    ├── pages
    ├── routes
    ├── style
    └── utils
```

## 4. 팀 협업 방식
```
✅ GitHub issue : 프로젝트 작업 개선사항 및 추가 될 기능을 기록하여 작업일정을 팀원들과 공유했습니다. 
✅ 데일리스크럼 : 매일 9시 ,17 금일 작업 내용과 진행 상황을 공유했습니다.
✅ GitHub wiki : 팀내 공유되야 하는 정보와 회의내용을 기록하였습니다.
✅ Live share : VSC 의 Live share를 사용하여 더 나은 코드를 위한 토론을 진행하였습니다.

```


## 5.  구현 기능
추후 gif로 추가예정



## 6.  개선 노력
✅ 추후 확장 및 유지 보수를 고려해 재사용되는 컴포넌트는 별도로 common 폴더에서 관리하고 있습니다. 
✅ 효율적인 작업상황을 고려하여 반복되는 함수는 utils 폴더로 따로 분리하여 사용했습니다.  
✅ 이후 리팩토링시 진행 예정인 다크모드, 반응형 작업을 위해 변수컬러와, rem 단위를 사용하여 작업에 진행했습니다. 
✅ 더 나은 사용자 경험
- 사용자 경험을 고려하여 UX 디자인 제작 (Footer를 통해 화면에서 바로 접근하기 어려운 페이지를 라우팅 하였습니다.)
- 로딩 애니메이션을 추가하여 사용자가 로딩 상태를 인지할 수 있도록 했습니다.
✅ useParams 사용

- 프로필 페이지 구현
useParams를 이용해 사용자의 아이디를 받아와 정보를 띄워줍니다. 내 프로필에서는 상품 등록 및 프로필 수정 페이지로 이동할 수 있는 버튼이 나타나고, 다른 유저의 프로필에서는 팔로우 버튼이 나타납니다.
댓글 모달 클릭시 내 댓글이면 삭제, 다른 유저의 댓글이면 신고 기능을 사용할 수 있습니다.

## 7. 
✅ 스타일 재작업 필요
문제 기능 구현 후 각자 담당 페이지를 스타일링 하였는데 코드를 합쳐서 보니 스타일링 통일이 되지 않았습니다.
원인 피그마 디자인을 직접 만든 뒤 그를 토대로 스타일링 작업을 하여 정확한 pixel 값이 맞춰지지 않은 상태였고, 코드 재활용이 가능한 요소에도 4명 각자의 스타일로 마크업과 스타일링이 이루어졌습니다.
해결 기준을 세워서 전체 페이지 마크업과 스타일링을 다시 해야 했고 중간에 스타일드 컴포넌트명 컨벤션이 필요함을 깨닫게 되어 한사람이 전체 코드를 통일하는 작업을 거쳤습니다. 이번과 같이 팀프로젝트에서 최소한의 디자인 파일을 가지고 개발을 하는 경우 한사람이 마크업과 스타일링을 맡아서 진행하거나 명확한 컨벤션을 가지고 모두가 이를 지키며 작업해야 한다는 것을 배웠습니다.
