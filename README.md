<h1>Jimin-Onjung</h1>
<br>
<h1>봉사와 기부를 한번에! - '온정'</h1>

<h2>1. 기획의도</h2>
<h3>1. 서비스 제작배경 및 필요성</h3>
<h4>1-1 서비스 제작 배경</h4>

<img src="/image/기획배경.png">

최근 한국의 자원봉사 참여율이 큰 폭으로 감소하고 있습니다. **2023년 기준, 자원봉사 참여율은 10.6%로 집계되었으며, 2015년 이후 지속적으로 하락**하는 추세를 보이고 있습니다. 특히, 코로나19 이후 **자원봉사 활동 참여 인원이 절반 이상** 줄어들었으며, 사회적 거리두기가 완화된 이후에도 봉사활동 참여율은 여전히 회복되지 못하고 있는 상황입니다. 이러한 감소 현상은 청소년과 성인 모두에게서 공통적으로 나타나고 있습니다.

이에 따라 온정은 **봉사와 기부를 연결하는 통합 플랫폼을 기획**하여 **자원봉사의 가치를 새롭게 조명하고, 더 많은 이들의 참여**를 독려하고자 합니다.

 <h2>2. 기대효과</h2>

<img src="/image/기대효과.png">

**자원봉사의 확산과 나눔 문화의 정착**

자원봉사 활동을 통해 사회적 책임감과 공동체 의식을 고취시키고, 기부에 대한 긍정적 인식을 확대하여 봉사와 기부가 자연스럽게 연결되는 선순환 구조를 구축하고자 합니다. 이러한 구조를 기반으로 지속 가능한 참여를 촉진하며, 나아가 전반적인 자원봉사 참여율의 향상과 기부 문화의 확산을 기대합니다.

<h2>3. 프로젝트 사용 툴</h2>
- Java<br>
- Java Spring Data<br>
- Java Script<br>
- tomcat<br>
- MySQL<br>
- Spring Boot<br>
- Visual Studio Code<br>
- Sourcetree<br>
- git, github<br>
- JSON<br>
- JDK 17.0.10<br>
- Slack<br>

<h2>4. ERD </h2>
<img src="/image/erd.png">

<h2>5. 담당업무 </h2>
<h4>5-1 프론트엔드</h4>
<img src="/image/front.png">

▶회원가입
<ul>
<li>사용자 회원가입</li>
</ul>

▶로그인
<ul>
<li>사용자 로그인</li>
</ul>

▶메인페이지
<ul>
<li>로그인/비로그인 헤더</li>
<li>슬라이드 배너</li>
<li>랭킹</li>
<li>무한 롤링</li>
<li>푸터</li> 
</ul>

▶후원 게시판
<ul>
 <li>후원 게시판 작성</li></li>
 <li>후원 게시판 수정</li>
 <li>후원 게시찬 상세</li>
 <li>후원 게시판 목록</li>
</ul>

<h4>5-2 백엔드</h4>
<img src="/image/back.png">

▶로그인
<ul>
<li>Kakao DEVELOPER API를 통한 카카오 간편 로그인 지원</li>
<li>비밀번호 재설정 시 SMTP Gmail을 사용하여 재설정 링크 발송을 통한 비밀번호 재설정</li>
</ul>
▶회원가입
<ul>
<li>회원가입 시 Cool SMS API를 사용하여 휴대폰 번호 본인인증</li>
<li>회원가입 시 SMTP Gmail을 사용하여 이메일 본인인증</li>
</ul>
▶마이페이지: 마이프로필/프로필 수정
<ul>
<li>회원의 총 봉사활동 횟수, 총 봉사활동 시간, 총 기부 포인트, 총 후원 정 수 조회(Rest)</li>
<li>프로필 수정 시 회원 닉네임과 한 줄 소개 수정 가능, 회원 프로필 사진 수정 및 업로드 가능</li>
</ul>
▶마이페이지: 결제 내역
<ul>
<li>회원의 결제 내역 조회(Rest)</li>
<li>날짜 직접 지정, 최근 1년, 1개월, 3개월, 6개월, 초기화 필터 제공</li>
</ul>
▶마이페이지: 후원 내역
<ul>
<li>회원의 최근 후원 내역 조회(Rest)</li>
<li>날짜 직접 지정, 최근 1년, 1개월, 3개월, 6개월, 초기화 필터 제공</li>
</ul>
▶마이페이지: 기부 내역
<ul>
<li>회원의 최근 기부 내역 조회(Rest)</li>
<li>날짜 직접 지정, 최근 1년, 1개월, 3개월, 6개월, 초기화 필터 제공</li>
</ul>
▶마이페이지: 봉사 활동 내역
<ul>
<li>회원의 최근 봉사 활동 내역 조회(Rest)</li>
<li>날짜 직접 지정, 최근 1년, 1개월, 3개월, 6개월, 초기화 필터 제공</li>
<li>회원의 봉사 활동에 따른 후기 작성 가능</li>
</ul>
▶마이페이지: 내 알림
<ul>
<li>회원의 최신 알림 목록 10개 조회(Rest)</li>
<li>읽지 않은 알림은 빨간색 *로 표시, 알림 읽음 처리 시 빨간색 * 사라짐</li>
<li>알림 클릭 시 각 알림이 발생한 게시글로 이동</li>
</ul>
▶마이페이지: 내 봉사 활동 후기
<ul>
<li>회원의 최근 봉사 후기 내역 조회(Rest)</li>
<li>날짜 직접 지정, 최근 1년, 1개월, 3개월, 6개월, 초기화 필터 제공</li>
<li>회원이 작성한 봉사 후기 수정 및 삭제 가능</li>
</ul>
▶마이페이지: 봉사 활동 신청 현황
<ul>
<li>단체 회원이 자신이 작성한 모집 게시글에 지원한 일반 회원 내역을 조회(Rest)</li>
<li>지원한 일반 회원의 신청 상태를 승인 및 거절로 변경 가능</li>
<li>지원한 일반 회원의 신청 상태 변경 시 일반 회원에게 알림 생성</li>
</ul>

▶메인페이지
<ul>
<li>헤더에 세션 삽입, 로그인 시 세션 유지</li>
<li>로그인 시 헤더에 알림과 프로필 사진 출력, 프로필 사진 클릭 시 마이페이지 이동 및 로그아웃 드롭다운 출력</li>
<li>헤더와 메인 페이지에 각각의 게시판 링크 연결</li>
<li>메인페이지 상단 슬라이드 배너 최신 후원 게시글 10개 출력</li>
<li>메인페이지 중단 봉사활동 시간, 기부, 후원 랭킹 월별 출력</li>
<li>메인페이지 하단 배너 최신 봉사 후기 게시글 10개 출력</li>
</ul>

▶알림
<ul>
<li>인터셉터를 통해 로그인 시 헤더에 읽지 않은 알림 출력</li>
<li>알림 클릭 시 읽음 처리 후 마이페이지의 내 알림으로 이동</li>
<li>읽지 않은 알림이 있을 시, 헤더에서 종 아이콘 옆 빨간색 *로 표시</li>
</ul>

<h2>6. 느낀점</h2>
<h3>6-1 문제를 해결했던 부분</h3>
<h4>📌 알람 인터셉터 구현 과정에서의 안정성 문제 해결</h4>

❗문제 상황❗<br>
알람 기능을 구현하기 위해 인터셉터를 활용해 로그인한 사용자의 알람 데이터를 뷰에 전달하려 했으나 전달되지 않음
<img src="/image/잘못된 코드.PNG">

<br>
<br>
🚨문제 원인🚨<br>
<img src="/image/오류.PNG">
<br>
<br>
🚀해결 방법🚀<br>
<img src="/image/완성코드.PNG">
로그인되지 않은 사용자 처리 로직 추가로 NullPointerException 문제 해결!
<br><br>
<h4>📌 타임리프 문법으로 해결한 헤더 프로필</h4>
❗문제 상황❗<br>
프로필 사진을 수정했을 때 헤더에 바로 반영되지 않고 재로그인 시에 프로필 사진이 출력됨<br>
<br>
🚨문제 원인🚨<br>
타임리프 템플릿 로직 부족<br>
<br>
🚀해결 방법🚀<br>
타임리프 템플릿에서 동적으로 URL을 반영하도록 설정
<br><br>
<h3>6-2 총평</h3>
<strong>✨기획: 서버를 생각하고 화면을 구현하자!</strong><br><br>
이번 프로젝트를 진행하면서, 서버와 화면 구현 간 발생한 문제들을 통해 <strong>서버를 기반으로 한 화면 설계의 중요성</strong> 을 깊이 깨닫게 되었습니다. 
기획할 땐 완벽히 기획했다고 생각했지만, 막상 프로젝트를 진행하다보니 수정할 곳이 많았습니다.
<br>
<br>
특히, 비밀번호 재설정, OAuth 데이터 처리, 알람 인터셉터와 같은 기능들은 서버 로직과 화면의 연계가 필수적이었음에도 불구하고, 초기 설계에서 이를 충분히 고려하지 않았던 점이 어려움으로 작용했습니다.
서버와 화면 간의 연계는 단순히 기능 구현의 문제가 아니라, 시스템 전체의 안정성과 확장성을 결정짓는 핵심 요소인 것을 다시 한번 깨닫게 되었습니다.
이번 프로젝트를 통해, 서버를 기반으로 한 화면 설계가 얼마나 중요한지, 이를 통해 왜 개발자들이 유지보수하기 쉬운 시스템을 설계하는 것을 그토록 강조하는지 알게되었습니다.
<br>
<br>
<strong>✨협업: 협업의 중요성</strong><br><br>
이번 프로젝트를 통해 또 하나 느낀 점은, 내가 맡은 작업뿐 아니라 팀원들의 작업도 굉장히 중요하다는 것입니다.
제가 맡은 마이페이지와 메인페이지의 기능은 다른 팀원들이 맡은 게시판 기능의 완성도에 크게 의존적이었습니다.

제가 맡은 기능이 아무리 완벽하게 구현되었더라도, 팀원들의 작업이 완료되지 않으면 제 작업은 의미가 없어지거나 중단될 수밖에 없었습니다.
이 과정에서 팀원들의 작업 진행 상황에 따라 기획과 설계를 수정해야 했고, 이를 통해 협업에서 상호 의존성의 중요성을 깊이 느꼈습니다.

또한, VO와 DTO 혼용 문제로 인해 세션 데이터를 관리하는 데 어려움을 겪은 경험도 있었습니다.
어떤 작업에서는 VO 객체를, 다른 작업에서는 DTO 객체를 사용하는 방식으로 통일되지 않다 보니, 데이터 불일치로 인한 오류가 발생했습니다.
이를 통해, 협업에서 명확한 데이터 규칙을 사전에 정하고 통일하는 것이 얼마나 중요한지 알게 되었습니다.

협업을 진행하면서 Git 충돌과 병합 문제도 자주 발생했습니다.
서로 같은 부분을 수정하거나, 연관된 작업을 동시에 진행할 때 소통 부족으로 인해 충돌이 생기는 경우가 꽤 있었습니다.
특히, 누군가 수정한 내용을 모르고 다시 수정하거나, 팀원 간 작업 내용을 공유하지 않아 이미 해결된 문제를 반복적으로 수정해야 하는 비효율적인 상황도 있었습니다.

이러한 경험들은 제게 협업의 핵심은 단순히 자신의 작업을 잘 수행하는 것만이 아니라, 팀원들과 작업 상태를 명확히 공유하고 소통하는 것이라는 것을 알려주었습니다.
앞으로는 더 적극적으로 소통하고, 협업 과정에서의 문제를 최소화하기 위해 기획 단계에서부터 명확한 협의와 규칙을 설정하고 실천해 나가고자 합니다.
<br><br>
<strong>✨미래: 도전하며 성장하는 개발자!</strong><br><br>
이번 프로젝트를 시작하며 세웠던 제 목표는 '다양한 경험 해보기'였습니다. 
저는 API를 사용해 프로젝트를 진행해 본 적이 없었기에, 회원가입, 로그인 등 API가 필요한 기능을 담당하고 싶었습니다.
파트를 나눌 때 제가 주도적으로 자원하여 맡았고, 이를 통해 새로운 기술을 배우고 적용할 기회를 가질 수 있었습니다.
특히, OAuth 카카오 로그인 기능을 맡으면서, 외부 API를 활용하는 방법을 익히게 되었습니다.
이 과정에서 API 문서의 중요성과, 문서를 기반으로 한 설계가 얼마나 큰 영향을 미치는지 몸소 경험할 수 있었습니다.
처음에는 Kakao Developer를 사용할 때 응답 데이터 구조를 이해하지 못해 기능 구현에 많은 시간을 소요했지만, 이를 해결하고 이해하며 API 활용 능력을 키울 수 있었습니다.
이미 알고 있는 기능들을 구현하는 것 보다 시간은 많이 걸렸지만 새로운 기술을 배우는 과정에서 겪는 어려움을 해결하며 성장하는 저를 발견할 수 있었습니다.
앞으로도 새로운 도전을 두려워하지 않고, 익숙하지 않은 기술과 환경에 도전하며 더 성장하는 개발자가 되고 싶습니다.
