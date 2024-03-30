주의할점)<br/> 
1.파이어베이스 연동이 되어있어 연동이 안되어있으면 실행이 안될수도있습니다<br/>
2.제 핸드폰 기준으로 layout을 짜다보니 다른핸드폰에선 뒤틀려 보일수도있습니다<br/>
<br/> <br/> 
주요기능)<br/> 
1.기본적인 로그인 기능<br/> 
2.회원가입시 기입하는 정보 DB에등록<br/> 
3.회원가입시 입력받는 Profile 사진 (핸드폰 갤러리에서 가져와야함) url 전환후 DB에 등록<br/>
4.메인 화면 진입시 우측 상단 Setting 에 프로필 사진이 뜨게 했구 프로필 사진 누르면 회원가입떄 입력받은 data를 수정하고 db에 update하는 기능을 만들 예정입니다<br/>
  ㄴ프로필사진 클릭시 수정 페이지까진 만들었지만 , 데이터 수정 부분은 만드는 중입니다<br/>
5.기본적인 UI를 조금 바꿔봤습니다! <br/>
<br/><br/>
각 layout 요소?들 ID) <br/>
<login layout> : 로그인하는 레이아웃<br/>
textview : 50,35<br/>
1.@+id/editTextText ->아이디 입력 받는칸 <br/>
2.@+id/editTextNumberPassword ->비밀번호 입력 받는칸<br/>
3.@+id/go_to_register_btn ->회원가입 버튼<br/>
4.@+id/go_to_login_btn ->로그인버튼<br/>
<br/><br/>
<sign_up layout> : 회원가입 레이아웃<br/>
1.@+id/imageView<br/>
2.@+id/Et_s_id ->아이디 입력받는곳<br/>
3.@+id/Et_s_pw->비밀번호 입력받는곳<br/>
4.@+id/Et_s_name->강아지 이름 입력받는곳<br/>
5.@+id/Et_s_age ->반려견 나이 입력받는곳<br/>
6.@+id/Et_s_weight->반려견 몸무게<br/>
7.@+id/Et_s_ar ->반려견 활동수치<br/>
8.@+id/Et_s_allergy ->반려견 활동수치 <br/>
9.@+id/Tv_s_go" ->활동수치 보러가기<br/>
10.@+id/Btn_s_register ->회원가입 완료<br/>
<br/><br/>
<mainactivity layout> : 앱의 메인이되는곳<br/>
1.@+id/setting_btn ->세팅을하는 버튼<br/>
2.@+id/calender_btn->캘린더 버튼(다이어리)<br/>
3.@+id/chatbot_btn ->gpt버튼<br/>

