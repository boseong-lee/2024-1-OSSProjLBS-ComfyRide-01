# A4.2 OSS 프로젝트 회의록

# **1차 회의(Kick-Off 미팅)**

- 일시 : 2024-03-15 15:00 ~ 17:00
- 장소 : 동국대학교 블루팟
- 참석자 : 이보성, 김민재, 장주리
- 의제 목록
  - 프로젝트 주제 및 구현 계획 수립
  - 프로젝트 정기 회의 일정 및 협업 툴 논의
  - 프로젝트 역할 분담
- 의제별 논의 요지
  - 프로젝트 주제 및 구현 계획 수립
    - 사용자가 자신의 취향에 맞는 옷을 복수개를 선택하면 해당 옷에 부여된 스타일 코드를 조합해 사용자에게 맞는 패션을 추천하는 앱을 구현한다.
    - 머신러닝을 이용하여 새로운 데이터에 라벨링을 한다.
    - 사용자가 선택할 스타일(옷)은 인터넷 쇼핑몰에서 데이터를 추출한다.
    - 앱 개발 프레임워크는 'Flutter', 데이터베이스는 'Firebase' 사용 예정이다.
    - 스타일 유형 정의에 필요한 데이터 수집을 용이하게 하기 위해 JavaScript를 사용하여 간단한 웹 인터페이스를 구현할 예정이다.
    - 머신러닝은 구글 클라우드 비전 API 사용 예정이다.
  - 프로젝트 정기 회의 일정 및 협업 툴 논의
    - 정기회의는 팀원들의 시간표를 고려하여 매주 목요일 15:00 ~ 17:00에 진행한다.
    - 프로젝트 관련 소통은 Slack을 사용하고, 협업 툴은 Notion, Github, Figma를 사용
      한다.
  - 프로젝트 역할 분담
    - 프로젝트의 주역할은 아래와 같이 분담했다.
    - 프로젝트 전체 관리 및 백엔드 : 이보성
    - 머신러닝 및 팀 레포 관리 : 김민재
    - 프론트엔트 및 회의록 작성 : 장주리
- 액션 아이템
  - 이보성 : 4월 14일까지 Flutter 프로젝트 생성 및 Firebase 연동을 진행
  - 김민재, 장주리 : 4월 13일까지 Office, Feminine, Casual 각 유형별 패션 사진을 30개 이상 수집
- 공유사항 및 차기 회의 일정
  - 차기 회의는 4월 15일 월요일 수업 종료 이후에 진행한다.
  - 회의록은 정기 회의시에만 작성한다.
  - 금일까지 모든 팀원은 프로젝트 협업 툴 Notion, Figma 초대를 수락한다.

### 회의사진

<img src="./imgs/meeting_0315.png" alt="회의사진" width="400" height="300">

# **2차 회의**

- 일시 : 2024-04-15 19:00 ~ 21:00
- 장소 : 동국대학교 경영관 능금사랑
- 참석자 : 이보성, 김민재, 장주리
- 의제 목록
  - 머신러닝에 사용될 이미지 데이터 등록 작업
  - 추후 개발 일정 논의
- 의제별 논의 요지
  - 머신러닝에 사용될 이미지 데이터 등록 작업
    - 지난주 수집한 이미지 데이터를 Firebase에 등록한다.
    - 등록은 JavaScript로 간단하게 구현한 웹 인터페이스를 활용한다.
  - 추후 개발 일정 논의
    - 아래와 같이 개발 일정 설계 및 간트 차트 제작했다.
      `<img src="./imgs/Gantt%20Chart_0417.png" alt="회의사진" height="300">`
    - 역할 분담 : 빨간색-이보성, 초록색-김민재, 파랑색-장주리, 보라색-합동
- 액션 아이템
  - 이보성 : 2024년 4월 30일까지 추천 알고리즘 설계
  - 김민재 : 2024년 4월 30일까지 머신러닝 API 학습
  - 장주리 : 2024년 4월 30일까지 구체적인 앱 UI 설계
- 공유사항 및 차기 회의 일정
  - 차주는 시험기간인 관계로 정기 회의는 생략하고, 4월 25일 목요일 15:00에 차기
    회의를 진행한다.

# **3차 회의**

- 일시 : 2024-04-22 17:00 ~ 19:00
- 장소 : 동국대학교
- 참석자 : 이보성, 김민재, 장주리
- 의제 목록
  - FTTI 기능 구체적으로 정의
  - 프로젝트 방향성 논의
  - 쇼핑몰 연계 방향
- 의제별 논의 요지
  - FTTI 기능 구체적으로 정의
    1) 사용자 로그인
    2) 사용자가 자신의 취향에 맞는 스타일 10개 선택
    3) 사용자 취향을 바탕으로 FTTI 유형과 설명 보여줌
    4) FTTI별 스타일 보여줌
    5) 스타일 사진 선택하면 쇼핑몰로 연계 → 추가 기능
  - 프로젝트 방향성 논의
    - 이미지 데이터를 대량으로 수집해 머신러닝 기능을 극대화 시키고, 스타일 유형을 더 다양하게 하여 앱의 퀄리티를 높이자는 의견이 제시됨
    - 프로젝트에 주어진 시간, 비용 등의 측면을 고려했을 때 현실적으로 실천하기 어려울 것 같다는 판단을 함
    - 이번 프로젝트에서는 FTTI의 목표에 집중하여,  의제 1에서 정의한 기초적인 기능 구현을 목표로 진행하기로 함
    - 앱 퀄리티 및 규모 확장 등은 프로젝트 이후에 판단하여 고도화 시키기로 함
  - 쇼핑몰 연계 방향
    - 스타일 사진 선택 시 실제 쇼핑몰 사이트로 연결을 할지, 임의의 웹사이트를 구현해서 해당 사이트로 연결 될지에 대한 논의함
    - 쇼핑몰 연계 - 이미 수집한 300개 이상의 이미지 데이터의 쇼핑몰을  직접 찾아 DB에 해당 쇼핑몰 링크를 추가해야하는 번거로움이 있음
    - 임의의 쇼핑몰 구현 - 간단한 쇼핑몰 웹사이트를 구현해 현재 DB에 등록된 이미지 데이터를 등록하여 사용자가 스타일 선택시 해당 쇼핑몰로 연결되게 함.
    - 후자의 방법이 시간적, 기술적으로 효율적일 것 같아서 임의의 쇼핑몰을 직접 구현하기로 협의함
- 액션 아이템
  시험기간으로 따로 없음
- 공유사항 및 차기 회의 일정
  앞으로 정기회의는 수업시간을 활용해 진행하기로 함(매주 월,수 17:00 ~ 18:50)

# **4차 회의**

- 일시 : 2024-04-24 17:00 ~ 19:00
- 장소 : 동국대학교
- 참석자 : 이보성, 김민재, 장주리
- 의제 목록
  - BM구성에 대한 협의
  - 중간발표 준비해야할 사항
  - 앱 시현에 대한 협의
  - FTTI 유형 수 협의
  - 깃허브 merge 관련 협의
- 의제별 논의 요지
  - BM구성에 대한 협의
    - 쇼핑몰 연계까지가 가장 큰 목표인데, 현실적으로 상황이 여유치 않으니 가장 가까운 목표부터 달성해도된다. BM은 추후 확장 목표로 잡고 기능 구현하는 것을 목표로 진행 (교수님 코멘트)
    - 핵심 아이디어만 구현하고, 나머지는 추후 구현하는 대신 프로젝트 포커스를 잘 잡아야함(교수님 코멘트)
    - 교수님 코멘트를 바탕으로 이번 프로젝트에서는 현재 운영중인 쇼핑몰 링크로 연결되게 구현하고, 쇼핑몰과의 협업은 추후 기능 확장으로 계획하기로 함
  - 중간발표 준비해야할 사항
    - 유스케이스 작성(전체 프로젝트 범위 그리고 그 안에서 구현 범위 표시)
    - 대안 설정은 요구사항 분석 결과를 바탕으로 기능 범위를 지정해야 함
    - 중간 발표 전까지 설계는 완료하고, 기본 플로우는 구현 되게 하기로 함
  - 앱 시현에 대한 협의
    - 구현은 애뮬레이터나 APK파일 사용해서 시뮬레이션 보여주기로 함
  - FTTI 유형 수 협의
    - FTTI 유형은 총 7개로 정의할 예정
  - 깃허브 merge 관련 협의
    - 깃헙에 Pull Request 업로드 후 팀원 모두 확인하에 문제 없으면 Merge하기로 협의함
- 액션 아이템
  - 시험기간으로 따로 없음
- 공유사항 및 차기 회의 일정
  - 차기 회의는 다음 수업시간에 진행하기로 함

# **5차 회의**

- 일시 : 2024-04-29 17:00 ~ 19:00
- 장소 : 동국대학교 강의실
- 참석자 : 이보성, 김민재, 장주리
- 의제 목록
  - FTTI 유형 정립
  - 이미지 데이터 수집
  - 이번주 개발일정 회의 및 간트차트 수정
- 의제별 논의 요지
  - FTTI 유형 정립
    - FTTI 유형 총 14개로 정의하기로 함
    - 유형별 코드, 설명, 명칭에 대해 추후 다음 회의때 확정 짓기로 함
  - 이미지 데이터 수집
    - 취향 분석 및  추천에 사용할 이미지 데이터 수집(쇼핑몰 링크 포함)
    - O, F, C 각 10개씩 수집
  - 이번주 개발일정 회의 및 간트차트 수정
    - 이번주까지 진행할 사항 : 소셜로그인 구현, 취향 선택 페이지 구현, FTTI 유형에 대한 알고리즘 구현
- 액션 아이템
  - 이보성 : 취향 페이지 구현 (~5/4)
  - 김민재 : FTTI 유형 알고리즘 구현 (~5/4)
  - 장주리 : 소셜로그인 구현 및 이미지 데이터 수집 (~5/4)
- 공유사항 및 차기 회의 일정
  - 차기 회의는 차기 수업 시간인 수요일 수업시간에 진행하기로 함

### 회의사진

<img src="./imgs/meeting_0429.png" alt="회의사진" width="400" height="300">

# **6차 회의**

- 일시 : 2024-05-08 19:00 ~ 21:00
- 장소 : 구글 온라인 미팅
- 참석자 : 이보성, 김민재, 장주리
- 의제 목록
  - FTTI 앱 구현 테스트
  - 중간 발표 역할분담
- 의제별 논의 요지
  - FTTI 앱 구현 테스트
    - 지금까지 구현된 사항 테스트 함. 전체적인 앱 흐름 구현은 완료 됐고, 중간발표 이후에 FTTI 유형 확정 지어서 해당 정보 바탕으로 앱 구현 완료하기로 함
    - 완료된 기능 : 로그인 기능, 스타일 선택 기능, 스타일 선택시 쇼핑몰 연계 기능
    - 보완 필요 기능 : FTTI 설명 페이지
    - 보완 필요 기능은 금일까지 마무리해서 github에 업로드 하기로 했고, 가독성 및 통일성을 위해 코드 리팩토링하기로 함
  - 중간 발표 역할분담
    - 중간발표 준비에 대한 역할 분담을 아래와 같이 진행함
    - 장주리 : PPT작성 및 앱 UI 설계서 작성, 회의록 작성
    - 이보성 : 중간보고서 작성
    - 김민재 : 유스케이스, 시스템 구성, 시퀀스도표 작성
    - 해당 역할 5/11(토) 08시까지 마무리 후 회의 진행하기로 함
- 액션 아이템
  - 이보성 : 금일까지 FTTI 설명 페이지 구현, 차기 회의까지 중간보고서 작성
  - 김민재 : 차기 회의까지  유스케이스, 시스템 구성, 시퀀스도표 작성
  - 장주리 : 금일까지 코드 리팩토링 및 차기 회의까지 PPT작성 및 앱 UI 설계서 작성
- 공유사항 및 차기 회의 일정
  - 차기 회의는 5월 11일 토요일 08시에 온라인으로 진행하기로 함

### 회의사진

<img src="./imgs/meeting_0508.png" alt="회의사진" width="500">

# **7차 회의**

- 일시 : 2024-05-12 10:00 ~ 11:00
- 장소 : 구글 온라인 미팅
- 참석자 : 이보성, 김민재, 장주리
- 의제 목록
  - 중간보고서 리뷰
- 의제별 논의 요지
  - 중간보고서 리뷰
    - 자료 조사 결과 타 선행 사례에 비해 FTTI 앱의 사용성이 간편하고, 데이터 수는 비교적 적은 점이 있어 선행 사례 분석 내용 보완하기로 함
    - 간트차트에 개발 단위별 구현 및 테스트 일정 추가하기로 함
    - 주어진 시간과 기술적 한계로 인해 사용 경험이 있는 flutter 프레임워크와 firestore DB를 사용하는 등의 현실적 제한 요소 보완하기로 함
    - 시퀀스 다이어그램은 전체 시스템 구성도의 로그인, 스타일 추천 기능에 대해서 작성하기로 함
- 액션 아이템
  - 중간보고서 제출 자료 수정 보완
    - 이보성 : 중간보고서 수정
    - 김민재 : 시퀀스다이어그램 작성
    - 장주리 : 간트차트 수정
- 공유사항 및 차기 회의 일정
  - 5월 13일 월 중간발표

### 회의사진

<img src="./imgs/meeting_0621.png" alt="회의사진" width="500">

[👉***README로 돌아가기***](https://github.com/CSID-DGU/2024-1-OSSProj-ComfyRide-01)
