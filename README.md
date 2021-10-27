# WEETEWEETE(위트위트)
   ##  Introduction to weeteweete project (Front-End)
   > Colorize your life with weete weete<br/>
   > 색은 특별함을 담는 가장 강력한 요소입니다. <br/>
   > 'color'라는 가치관에 생각과 감정을 정리하는 노트를 판매하는 모트모트 페이지가 매력적으로 느껴졌습니다. <br/>
   > 모트모트만의 매력과 페이지의 디자인/기획이 마음에 들어 디자인/기획 부분만 클론했습니다. <br/>
   > 개발은 초기 세팅부터 직접 구현했으며, 데모 영상에서 알 수 있듯이 모든 부분이 백앤드와 통신으로 이루어져 있습니다. 
   
   ## WEETEWEETE TEAM MEMBER & TERM
- 개발기간 : 2021/8/2 ~ 2021/8/13
- 개발 인원 : 프론트엔드 4명, 백엔드 2명
- 팀원 <br/>

	[프론트엔드]
  - 최호정: nav, footer, 메인페이지, 제품리스트페이지, 상품 리뷰
  - 차예은: 결제 form
  - 배윤아: 로그인/회원가입, 아이디/비밀번호 찾기, 결제 table
  - 이나현: 상세페이지, 장바구니<br/>
  
   [백엔드] <br/>
   - WEETEWEETE BACKEND LINK: https://github.com/wecode-bootcamp-korea/23-1st-Weeteweete-backend
   - 백선호: 로그인/회원가입, 비밀번호 초기화, 아이디 찾기, 로그인 데코레이터, 상품 결제, 상품 리뷰<br/>
   - 임종성: 모델링, 메인페이지, 상세페이지, 메뉴페이지, 장바구니 CRUD,  상품 리뷰


#### WEETEWEETE 시연 영상은 여기로 👉 https://youtu.be/_oMzIV2oyxE

   ## 적용 기술
   - Front-End : React.js, sass, react-router-dom <br/>
   - Back-End : Python, Django web framework, Bcrypt, My SQL, RESTful API<br/>
   - Common : RESTful API, trello <br/>

   ## 구현 기능 - 내가 구현한 기능 ✅ 표시
   - 필수구현
	   - 로그인 / 회원가입 ✅
	   - 제품 리스트 페이지
	   - 상세 페이지
	   - 결제 페이지 ✅
	   - 장바구니
   - 추가구현
	   - 아이디 / 비밀번호 찾기 ✅
	   - 상품 리뷰
	   - 재고 수량

> 토글 버튼을 누르면 동작 화면과 자세한 설명을 볼 수 있습니다.

<details>
<summary>로그인 / 회원가입</summary>
<div markdown="1">       

![](https://images.velog.io/images/winter_ya/post/eb9781fa-c32c-499a-847f-e79effd47c52/ezgif.com-gif-maker%20(5).gif)
- 회원가입 시 유효성 검사
	
	- 유효성 검사를 만족하는 경우 서버에 정보를 넘겨줍니다.
	- 유효성 검사를 만족하지 못하는 경우 서버에게 정보를 넘겨주지 않고 경고창을 띄웁니다. 
![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/84803633/139050949-7781eae6-455c-4a63-9dc1-07b7adfa7fe0.gif)<br/>
- 로그인
	- RESTful API를 호출하며 POST 요청을 합니다. 
	- 서버에서 토큰을 발급해주면 localStorage에 저장합니다. 

</div>
</details>
	  
<details>
<summary>아이디 찾기 및 비밀번호 찾기(임시 비밀번호)</summary>
<div markdown="1">       

![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/84803633/139050988-08c007f1-5b0f-4541-b761-87436c587621.gif)<br/>
- 아이디 찾기
	- RESTful API를 호출하여 POST 요청을 합니다.
	- 서버에서 내가 입력한 이름과 이메일에 등록되어 있는 회원정보에 있는 아이디를 받습니다.
![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/84803633/139051014-5f94a825-b011-42dc-b5bc-6be4e715e5b1.gif)<br/>
- 비밀번호 찾기
	- 아이디 찾기와 비슷한 레이아웃을 가지고 있어 컴포넌트를 재사용하였습니다.
	- RESTful API를 호출하여 PATCH 요청을 합니다. 
	- 서버에서 내가 입력한 아이디, 이름, 이메일에 등록되어 있는 회원정보에 있는 비밀번호를 삭제한 후 발급한 임시 비밀번호를 받습니다.  


</div>
</details>
<details>
<summary>결제 페이지</summary>
<div markdown="1">       

![ezgif com-gif-maker (6)](https://user-images.githubusercontent.com/84803633/139051126-253843a8-124e-483b-a7a0-c8ed795d8f20.gif)
- 결제 페이지


</div>
</details>



   ## Reference
이 프로젝트는 모트모트 사이트를 참조하여 학습목적으로 만들었습니다.<br/>
실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.<br/>
이 프로젝트에서 사용하고 있는 사진 대부분은 자체 제작한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.<br/>
   
   - 모트모트: https://motemote.kr/
