Sketch
---

### 주요 프로그램
  * Sketch : GUI디자인을 위한 기본적인 툴
  * Zeplin : 완성된 GUI 디자인을 개발자에게 전달하는 툴
  * Principle : 실제 제품처럼 작동하고 영상을 녹화 할 수 있는 프로토타이핑 툴
  * Sketch Mirror : Sketch 화면을 모바일에서 확인하는 앱
  * Principle Mirror : Principle화면을 모바일에서 확인하는 앱
  * 어도비 XD, Figma 등도 있음
  
  
### 플러그인
  * Sketch Runner : 명령어를 통해서 스케치 기능 제어가능. 작업속도 향상
  * Invision Craft : 스톡 이미제를 불러오거나 디자인 서식을 복붙하는 디테일한 작업이 편리해짐
  * Swatches : 웹, 앱에 적합한 스와치 모음. Open color는 컬러 팔레트
  * Automate-Sketch : 자주 사용하는 여러 기능들을 스케치 러너 명령어나 단축키로 빠르게 접근가능
  * Meterial : 매터리얼 디자인을 쉽게 적용
  

### Principle
  * 직관적
  * 에니메이션 부드럽고 녹화 편리함
  * 코드 필요없음
  * Dribble에서 대세 = 라이브러리 많음
  * 애프터 이펙트와 비슷한 방식


### PPI(Pixels Per Inch) = 화소밀도 / DPI(Dots per Inch)
  * 스크린 사이즈 : 스크린의 대각선 길이를 인치로 표션 (iMac 27 = 27")
  * 해상도(resolution) : 픽셀수로 표현 (iMac 27 = 2560*1440)
  * dp(Device Pixel) : 안드로이드 사이즈 단위. 밀도가 다른 디바이스에서 px로 표기하면 밀도가 클수록 작게 보임 dp로 표기하면 동일한 비율로 표현됨
  * sp(Scale-independent Pixels) : 안드로이드 사이즈 단위. 텍스트 사이즈에서만 사용됨
  * pt(Point) : iOS 사이즈 단위. dp와 같음
  * 화소밀도가 높을 수록 화면을 선명해진다. 스크린사이즈와 해상도, 화소 밀도는 비례하지 않고 기기마다 다르다.
  


### 작업방식
  * 작은사이즈 -> 큰 사이즈가 기본
  * 웹이나 앱이나 1x에서 시작
  * 반응형 웹은 모든 Break Point별 디자인이 필요
    1. 웹: 모바일 -> 패드 -> 데스크탑 -> FHD(1920*1080)
    2. 안드로이드: 안드로이드 기본사이즈 -> 사이즈별 최적화 
    3. iOS: iPhone8 -> 각 화면별 최적화
  * statcounter 통계 이용필요
  
  
  
### Material Design & Human Interface Guideline
 * 매터리얼 디자인 : 여러 기기에서 (구글)제품을 표준화할 수 있는 디자인 제안
  - 구글 = 안드로이드 = 다양한 디바이스  = 자유로운 마켓 & 개발 친화적 환경 = 뭐든지 만들 수 있는 종이컨셉
  
 * 휴먼 인터페이스 가이드라인 : 애플 기기에서 아름답고 쓰기 편한 환경을 지향
  - 애플 = iOS = 독자적 기기 = 폐쇄적인 마켓&까다로운 개발 환경 = 하드웨어를 돋보이게 하는 미니멀리즘
  
  
 
 ### 8-Point 그리드 시스템
 
  1. 8bit = 1byte
   - 스마트폰은 아이폰에서 시작했기 때문에 아이폰의 pt단위
   - 디자인 요소들의 사이즈는 8의 배수로(주요 스크린 사이즈들이 8의 배수)
   - 작은 단위는 4의 배수로.(매트리얼 디자인은 4dp가 기본)
   
  2. 적용 요소들
   - Font sizes
   - Line heights
   - Padding
   - Margins
   - Roundings
   - Fixed width, Fixed heights
   
  3. 응용방식
   - Grid Setting -> Grid Block Size : 8px
   - Nudge, Push, Shove 플러그인  -> set Nudge to 4, Set Push to 16, Set Shove to 48
 

### 타이포그래피 관리

 1. 유의할 점
  - Material Type System의 권장 사이즈, 두께, 명도를 응용
  - 텍스트 정렬은 Align Text Baseline을 이용해야 베이스라인에 맞게 정렬
  - 행간은 Set Line Height로 배수로 조절 할 수 있음
  
 2. 텍스트 스타일 활용
  - 텍스트 선택 -> Create new Text Style
  
 3. 심볼활용
  - 자주 텍스트를 변경해야할 때 -> Create Symbol



  

