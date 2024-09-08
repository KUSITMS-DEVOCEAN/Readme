# 1️⃣ 리서치 및 시장조사

기업의 조직 문화와 개발 문화가 반영된 **기술 블로그**는 자사 개발자들의 지식과 기술 그리고 일상을 외부 이용자들과 공유함으로써 개발자들의 커뮤니티를 형성합니다.

### 📊 경쟁사 분석

|  | Devocean | NaverD2 | Kakao Tech | Toss Tech | 우아한 기술블로그 |
| --- | --- | --- | --- | --- | --- |
| 해당 기업 |  SK | Naver | 카카오 | 토스 | (주)우아한형제들 |
| 주요 내용 | - SK그룹에서 사용되는 기술에 관한 블로그 <br> - 개발자들과 외부 이용자 간의 소통 커뮤니티 <br> - Tech 행사 관련 정보와 ‘데보션영’ 프로그램 정보 제공 | * Naver 개발자들의 실전 개발 경험과 지식에 관한 블로그 <br> * 개발자 행사 소식과 산출물 공유 <br> * Naver에서 지원하는 개발자 프로그램 소개 <br> * Naver 오픈 API 가이드와 SDK 제공 | * 카카오의 기술, 개발 조직, 문화에 관한 블로그 <br> * 카카오가 주최하거나 후원 및 참여하는 다양한 기술 이벤트 소개 <br> * 카카오 플랫폼 서비스 관련 질문 및 답변을 올리는 개발자 커뮤니티 사이트 <br> * 카카오가 만든 개발 도구와 라이브러리 공개 | * 개발 분야뿐만 아니라, 디자인 분야를 포함하는 블로그 <br> * 토스 개발자 컨퍼런스 ‘SLASH’ 세션 소개 | * (주)우아한형제들 개발자들의 기술과 코드 또는 일상과 주관에 관한 블로그 |
|  접속 디바이스  분류 | Desktop(82.1%)<br>Mobile(17.9%) | Desktop(88.5%)<br>Mobile(11.5%) | Desktop(51%)<br>Mobile(49%) | Desktop(84.2%)<br>Mobile(15.8%) | Desktop(51%)<br>Mobile(49%) |
| 내/외부 사용자 간의 커뮤니티 기능   | O | X | O | X(블로그 내 게시물의 댓글 작성이 활성화되어 있음) | X |
| 게이미피케이션 요소 | O | X | X | X | X |
| 마이페이지 존재 여부 | O | X | X | X(댓글 작성은 회원가입을 하지 않아도, 익명으로 작성 가능) | X |


### 💫인사이트

	💡 웹의 UI/UX 개선을 통하여 웹 사용자의 유입량을 증가
사용자가 접속한 디바이스를 분류한 결과, Devocean은 웹 접속이 모바일 접속과 비교하여 약 5배가 높습니다. Devocean은 경쟁사 중 유일하게 모바일 앱 서비스를 제공하고 있으나, 서비스 사용자의 특성을 고려하여 웹의 사용자 편의성을 증대시킬 필요가 있습니다. 

따라서, 구체적으로 웹의 마이페이지 개선을 통해 사용자 편의성을 증대시켜 웹 사용자의 유입량을 증가시키고자 합니다. 

	💡 마이페이지를 개선하고 게이미피케이션 요소를 고도화하여 사용자의 활동량을 증가
경쟁사와 비교한 결과, Devocean만의 차별성은 내부 사용자뿐만 아니라 외부 사용자 간의 커뮤니티를 활성화하기 위한 목적으로 마이페이지가 존재하며 배지 시스템과 같은 게이미피케이션 요소가 있다는 것입니다. 

사용자의 편의성을 고려하여 마이페이지를 개선하고 배지 시스템 외의 랭킹, 활동 대시보드와 같은 게이피케이션 요소를 추가하여 외부 사용자의 활동량을 증가시킬 수 있습니다. 

### 📍Positioning Map

![image](https://github.com/user-attachments/assets/e3973ec7-c44e-4b13-9c16-c2e887cd34ef)
아래의 세 가지를 통하여 ‘사용자의 자발적인 참여를 유도하는’ 서비스로 포지셔닝 하고자 합니다.

1. 활동 대시보드 추가
2. 나의 활동 내용을 확인하는 기능 추가
3. 목표지향적인 배시 시스템 구축

(포지셔닝은 사용자의 자발적인 참여/동기유발 요소 기준을 축으로 잡아 설정하였습니다.)

# 2️⃣ 솔루션 도출

## 📊 활동 대시보드

✅ **활동 대시보드**를 통한 동기부여 및 월간 활동 조회

![image](https://github.com/user-attachments/assets/73ab4c12-7935-4177-8883-dbec234810b0)<br>
마이페이지 우상단에 활동 대시보드 삽입
	
- 활동 대시보드에 들어가는 커뮤니티 활동 캘린더, 이번달 읽은 블로그, 커뮤니티 랭킹은 **월간 데이터를 한눈에 조회**할 수 있도록 함
- 대시보드의 각 요소는 **월간 활동을 다각도로 분석**하며, 이를 통해 효과적인 활동 동기부여를 유도함

![image](https://github.com/user-attachments/assets/af0e4513-717c-4d4d-ad2b-7455d85a43a4)
활동 대시보드의 세 가지 요소

|  | **분석 요소** | **기대효과** |
| --- | --- | --- |
| **1. 커뮤니티 활동 캘린더** | 사용자의 한달 간 활동 빈도 | **활발한 활동량을 유도** |
| **2. 이번달 읽은 블로그** | 사용자가 읽은 블로그의 카테고리 | **활동 카테고리 보고**|
| **3. 커뮤니티 랭킹** | 사용자의 게시물이 받은 호응 | **높은 질의 활동을 유도** |

**→ 활동의 질, 활동의 양, 활동 카테고리를 대시보드를 활용해 한눈에 시각화**

## 1. 커뮤니티 활동 캘린더<br>
![image](https://github.com/user-attachments/assets/246f746e-5994-4c0d-9c4b-bc014bf2f9c2)<br>
활동 대시보드_커뮤니티 활동 캘린더

📌 **기능 정의**

**출석, 좋아요, 댓글, 게시물**을 통해 오늘 하루의 활동량을 기록하는 캘린더

📌 **기능 상세**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 1.1 | 컬러 칩 | **네 가지 색상의 컬러칩을 활용해 사용자의 한 달간의 활동을 캘린더에 표시함. <br><컬러칩 기준><br><br>1. 주황색 칩: 로그인**하여 홈페이지에 접속할 경우, 해당 날짜에 자동으로 주황색 칩 추가<br><br>**2. 파란색:** 커뮤니티에 사용자가 한 개 이상의 게시물에 **좋아요**를 누를 경우, 해당 날짜에 자동으로 파란색 칩 추가<br><br>**3. 남색:** 커뮤니티에 사용자가 한 개 이상의 게시물에 **댓글을 작성**할 경우, 해당 날짜에 자동으로 남색 칩 추가 <br><br>**4. 보라색:** 커뮤니티에 사용자가 한 개 이상의 **게시물을 작성**할 경우, 해당 날짜에 자동으로 보라색 칩 추가 |

📌 **필요 이유**

사용자의 활동을 한달에 걸쳐 장기적으로 평가하는 다른 대시보드 기능을 보완하여 **잦은 접속과 활동을 유도**할 수 있는 효과적인 게이미피케이션 요소

📌 **기대효과**

활동량 자체를 늘릴 수 있는 **간단한 행동**을 기준으로 일일미션을 구성함으로써 두가지 효과를 유도한다

1. 게임과 유사한 간단한 일일 출석과제를 통한 동기부여로 **사용자 간의 소통 증대**
2. 한 달 간의 활동량을 효과적으로 가시화해 **히스토리를 효과적으로 확인**할 수 있게 함

📌 [Reference](https://acidic-buffer-cde.notion.site/Reference-30c2453394c14f66b0eb27990232ec37?pvs=4)

## 2. 이번달 읽은 블로그 <br>
![image](https://github.com/user-attachments/assets/6b81c4ee-09d5-4836-8610-c0ffda99bd1b)<br>
활동 대시보드_이번 달 읽은 블로그

📌 **기능 정의** 

사용자가 한 달간 읽은 **블로그 게시물 수**와 **카테고리 종류**를 보여주는 화면

📌 **기능 상세**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 2.1 | 읽은 블로그 수 및 원 그래프 | 읽은 블로그의 카테고리를 **원 그래프에 색상으로 구분**하여 표시<br>그래프의 중앙에는 **읽은 블로그 게시물 수**를 나타냄<br><br><원그래프 및 색상 구분 시스템><br><br>읽은 블로그의 카테고리 중 가장 많이 조회한 상위 3개의 카테고리를 3가지의 색으로 구분하여 표시 + 나머지 7개의 카테고리를 1개로 묶은 “기타” |
| 2.2 | 카테고리 및 백분율 (%) | 가장 높은 백분율을 가장 진한 색으로, 백분율이 낮을수록 연한 색으로 나타내고 카테고리 명 상단에 해당하는 색을 정사각형으로 표시 |

📌 **필요 이유**

- **대시보드 활동 중 유일하게 Tech의 블로그 활동 현황을 표시함.** 
(일일미션과 랭킹은 커뮤니티 활동을 기준으로 함)
- 전문적인 지식을 SK 내외부로 공유하고, 소통하는 개발문화를 추구하는 **데보션의 행동원리를 위해서**는 높은 퀄리티의 블로그 활동을 활성화해야 함.

📌 **기대효과**

- 사용자가 자신의 활동량에서 더 나아가 **데보션에서 어떤 게시글을 읽고 있는 지** 실시간으로 조회할 수 있도록 함

## 3. 커뮤니티 랭킹<br>
![image](https://github.com/user-attachments/assets/2d6bd6f3-2620-4782-9958-2451f397453d)<br>
활동 대시보드_커뮤니티 랭킹
![image](https://github.com/user-attachments/assets/b47ad1d2-fbc3-4e5f-b627-0c9b6c0d3c44)
활동 대시보드_커뮤니티 랭킹_나의 랭킹 (하위페이지)

📌 **기능 정의** 

사용자의 게시물이 **한달 동안 다른 사용자들로부터 받은 반응 (조회수, 받은 좋아요, 저장된 횟수)** 을 기준으로 점수를 산정하여 전체 유저 중에서 **사용자의 백분위**를 보여주는 그래프

📌 **기능 상세**

**<활동대시보드_커뮤니티 랭킹>**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 2.1 | 랭킹 보기 | 랭킹 우상단의 **‘랭킹 보기 >’ 버튼을 클릭하면 실제 순위를 제공하는 페이지**로 이동 |
| 2.2 | 월 정보 및 사용자 총점 | **현재 월**과 사용자가 **현재 월에 얻은 총점**을 표시 |
| 2.3 | 랭킹 피라미드 및 백분위 | **<랭킹 산정 기준>**<br><br>*사용자가 **커뮤니티**에 작성한 게시물에 대한*<br><br> **- 조회수**<br><br> **- 받은 좋아요**<br> **- 저장된 횟수**<br><br> **<랭킹 피라미드 및 백분위>**<br><br> **25% 단위로 피라미드를 4개의 구역으로 구분함.** <br>사용자가 해당하는 **백분위의 정확한 수치**를 1% 단위로 표기. |
| 2.4 | 내 게시물이 받은 호응 | 랭킹에 반영되는 요소들의 **달성량 표시** |



**<활동대시보드_커뮤니티 랭킹_나의 랭킹> (하위 페이지)**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 1 | 기간 설정 | → 하위페이지를 만들어 **사용자의 실제 랭킹**과 **타 사용자의 랭킹을 보여주어 비교**하도록 함 |
| 2 | 나의 랭킹 | 사용자의 실제 순위와 함께 다양한 정보를 제공 |
| 2.1 | 나의 순위 | 사용자의 랭킹을 **순위**로 직관적으로 보여줌.  |
| 2.2 | 나의 정보 | 사용자의 **프로필 정보, 획득 점수, 작성 게시물 수**를 표시 |
| 2.3 | 나의 커뮤니티 게시글 조회수, 받은 좋아요, 저장된 횟수 표시 | 랭킹에 반영되는 요소들의 달성량 표시 |
| 3 | 이달의 랭킹 | **나의 랭킹과 동일한 방식으로** 다른 사용자들의 순위와 프로필 정보를 표시 |

📌 **필요 이유**

- 활동 대시보드의 다른 기능들과의 **상호보완성**, **경쟁이라는 가장 강력한 동기부여**를 만듦

📌 **기대효과**

이번달 읽은 블로그가 사용자의 단순 활동량을 늘렸다면, 랭킹은 사용자가 자신의 활동을 **다른 사용자들로부터 평가 받기 때문**에 **사용자가 질 높은 게시물을 작성하도록 자연스럽게 유도**한다

  # 💻 나의 활동

✅ **나의 활동 모아보기**를 통한 효율적인 히스토리 조회

![image](https://github.com/user-attachments/assets/e4f3e9b2-a94b-490d-b9bd-48f350f2cabd)
마이페이지 우하단에 나의 활동 삽입

- 기존 데보션의 나의 활동은 두가지 측면에서 사용의 **불편함이 존재**
    
![image](https://github.com/user-attachments/assets/68dcc31c-fc28-463f-b840-da4da978c441)
    현재 앱에서만 조회 가능한 나의 활동 화면
    
   1. 앱에서만 조회 가능하며, **웹에서는 조회할 수 없음**
   2. 커뮤니티를 클릭하면 게시물로 이동하지만, 댓글을 클릭하면 남긴 댓글 리스트만 확인 가능한 등 어느 게시물에 남긴 댓글인지 확인하기 어렵다는 
    → **로직 상의 불편함 존재.** 
- **개선된 로직**으로 **사용자의 히스토리를 편하게** 모아볼 수 있는 기능을 필요로 함


## 1. 나의 활동
![image](https://github.com/user-attachments/assets/60f99727-b527-419b-92d8-a7306f8e12ea)<br>
나의 활동


![image](https://github.com/user-attachments/assets/6a5ede6b-4b7b-4952-b8bb-e5018d911f11)<br>
나의 활동_전체보기

📌 **기능 정의** 

사용자의 **활동 히스토리**를 **통일된 로직**으로 보기 편하게 제공하는 화면

📌 **기능 상세**

**<나의 활동>**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 1.1 | 나의 활동 세로 탭 | 세로로 활동 히스토리의 카테고리를 표기<br><br>**Tech, 커뮤니티, 스토리** 중 하나의 카테고리에 해당하는 탭을 선택하면 탭에 해당하는 하위 카테고리가 나타남.<br><br>**Tech → 블로그, 뉴스, OpenLab<br>커뮤니티 → X <br>스토리 → 데보션영, AI Fellowship, 후원후기**<br><br>의 하위 카테고리가 나타남.  |
| 1.2 | 탭에서 확인 가능한 게시물 | 탭에서 카테고리와 하위 카테고리를 선택하면 **확인 가능한 게시물의 종류**가 나타남.  |
| 1.3 | 전체보기 | 마이페이지 화면에서는 선택된 히스토리에서 게시물 두개씩만 보여줌. 더 보고 싶은 경우 우하단의 **“전체보기”** 버튼을 클릭 |

**<나의 활동_전체보기>**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 1 | 나의 활동_전체보기 | 4개의 게시물을 보여주고, 아래의 페이지 넘버링을 통해 이전 히스토리를 확인할 수 있도록 함 |

📌 **기대효과**

- **히스토리**를 한번에 몰아볼 수 있도록 하여 **사용성 증대**


# 📝 나의 정보


✅ 기존의 **나의 정보를 개선**, **새로운 배지 시스템** 삽입
 

![마이페이지 좌측에 나의 정보 삽입](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/c3f863d5-7383-48a2-99d3-b356fd1e2ed0/image.png)

마이페이지 좌측에 나의 정보 삽입

- 기존에 가로로 길게 배치되어 있던 나의 정보를 좌측의 프로필 이미지 및 닉네임과 합쳐, **정보의 유사성**을 기준으로 묶음

![현재 웹에서 확인 가능한 나의 정보 화면](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/8af51714-417d-471a-b770-844a9f32b95d/image.png)

현재 웹에서 확인 가능한 나의 정보 화면

- 불필요한 마일리지 정보는 간소화시켜 표시하고, 
**마일리지 내역보기 →  쇼핑하러가기**로 마일리지를 활용해 할 수 있는 행위를 구체적으로 설명하는 방식으로 **UX Writing 개선**

![현재 마일리지 정보 표시 화면](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/5103f4fd-4531-4f2d-952b-edffac49800e/image.png)

현재 마일리지 정보 표시 화면

- 앱에서만 확인 가능하던 **기존 배지의 로직을 개선**하고, **시스템은 간소화**하되 **차등성은 강화**한 배지 도입
***+ 사용자의 프로필 이미지가 삽입되는 곳이라면 어디든 우측에 배지 이미지가 삽입되도록 함***
</aside>

<aside>

1. 나의 정보

![나의 정보](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/90a6c55f-46c4-43b5-bf36-7a19424b6ba4/image.png)

나의 정보

📌 **기능 정의** 

기존의 **가로**로 펼쳐져 있던 나의 정보를 좌측의 프로필 이미지와 닉네임, 메일 하단에 **세로**로 합쳐 **정보간 통일성을 고려해 변경**한 화면

📌 **기능 상세**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 0 | 나의 정보 | 기존 나의 정보를 새롭게 구조화 |
| 0.1 | 회원정보 관리 | 사용자 본인이 남들에게 보여지는 **자신의 프로필 페이지를 확인할 수 있도록 함** |
| 0.2 | 뱃지 이미지 | 사용자의 프로필 이미지 우하단에 뱃지 이미지가 보이게 함 |
| 0.3 | 회원 정보 관리 | 기존의 나의 정보에서 가로로 펼쳐져 있던 정보를 모아 세로로 구조화

**- 소속, 활동 분야, 한줄 소개, Github 링크, Linked In 링크** |

📌 **기대효과**

- **정보의 유사성을 기준**으로 묶인 새로운 프로필 화면으로 **편안한 UI 경험 제공**
</aside>

<aside>

1. 배지

![배지](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/dec75a8f-9401-4226-a796-51a5255977c1/image.png)

배지

![배지 종류 및 시스템](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/a274a61e-4505-4560-ae5f-91a26322cf69/image.png)

배지 종류 및 시스템

![배지_전체보기 (하위페이지)](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/d800c54a-c8c1-4efd-b5f8-58c8c25e4b48/image.png)

배지_전체보기 (하위페이지)

📌 **기능 정의** 

간소화하되, **차등성을 강화**한 배지 시스템 구축, **좌측 나의 정보 구역**에 시각화

📌 **기능 상세

<배지>**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 0 | 배지 | **‘내 마일리지’** 와 **‘방문 수’** 만 나타내는 간소화된 형태의 배치 |
| 0.1 | 배지 인포메이션 | 마일리지 획득 기준을 설명하는 인포메이션을 **마이페이지에서 바로 확인**할 수 있도록 개선 |
| 0.2 | 전체보기 | **남은 배지**와 **이전 년도**에 획득한 뱃지 조회 가능 |
| 0.3 | 다음 배지 | 다음 배지를 표시 |
| 0.4 | 다음 배지 획득 기준 | 다음 배지를 획득하기 위해 남은 활동을 막대그래프로 표시 |

**<배지 종류 및 시스템>**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 1 | 배지 종류 및 시스템 | <배지 종류>
좌측에서부터 순서대로 다섯 개의 배지가 존재. 

**- 뉴비탐험가, 활동챌린저, 개발전문가, 커넥션 메이커, 마스터

커뮤니티 활동 (좋아요, 댓글, 게시물)**을 통해 **1년동안** 순서대로 다섯 개의 배지를 획득하는 것을 목표로 활동

1년이 지나면 배지는 처음으로 리셋, 이전 년도의 배지를 전체

<배지 시스템> |

**<배지_전체보기> (하위페이지)**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 1 | 현재 배지 | 현재 배지 상태를 표시하는 영역 |
| 1.1 | 현재 월 및 배지 | 현재 연도와 월, 가장 최근 획득한 배지와 배지명을 표시 |
| 1.2 | 다음 배지까지 남은 활동 | 다음배지까지 남은 활동을 표시 |
| 2 | 연도별 최종 배지 | 연도별로 최종으로 획득한 배지를 표시 |
| 3 | 배지 획득 현황 지도 | 해당 연도의 배지 획득 현황을 표시 |
| 3.1 | 획득 완료한 배지 | 획득한 배지 이미지와 배지명, 획득 날짜를 표시 |
| 3.2 | 달성 도전 중인 배지 | 달성 도전 중인 **바로 다음 배지**를 표시 |
| 3.3 | 달성 도전 다음 단계의 배지 | 달성 도전 중인 배지를 획득해야만 획득할 수 있는 **2단계 이상의 배지** 표시 |

📌 **기대효과**

- **간소화된 배지시스템**이지만, **차등성을 강화**한 직관적인 배지로 사용자의 수준을 한 눈에 알 수 있게 함
- 사용자들의 프로필 이미지 옆에 **상시 표시되는 배지 이미지**를 통해 동기부여
</aside>

<aside>

1. 마일리지

![마일리지](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/5307885d-64ae-42f3-a8a5-e330c3132721/image.png)

마일리지

📌 **기능 정의** 

불필요한 마일리지 정보를 없애 **간소화**하고, **의도성을 담은 UX Writing**으로 개선한 마일리지 화면

📌 **기능 상세**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 0 | 마일리지 | **‘내 마일리지’** 와 **‘방문 수’** 만 나타내는 간소화된 형태의 배치 |
| 0.1 | 인포메이션 | 마일리지 획득 기준을 설명하는 인포메이션을 **마이페이지에서 바로 확인**할 수 있도록 개선 |
| 0.2 | 쇼핑하러가기
 | **마일리지 내역보기 → 쇼핑하러가기**로 텍스트 변경 |
| 0.3 | 마일리지 (P) | 사용자의 사용가능한 마일리지 포인트를 나타냄 |
| 0.4 | 방문 수 | 사용자가 로그인하여 홈페이지에 접속한 횟수를 보여줌 |

📌 **기대효과**

- 마일리지를 통해 할 수 있는 **행위를 연상시키는 새로운 UX Writing**으로 개선
- 불필요한 정보 제거를 통해 **간소화된 UI** 제공
</aside>

# 3️⃣ 추가 과제 (Thanks To 페이지 개발)

<aside>
✅

> **산재되어 있던 프로젝트 결과물을 한번에** 모아볼 수 있는 페이지 개발
> 

![Thanks To의 About 페이지
(데보션 소개, 파트너십, 교육 후기 등을 조회할 수 있는 페이지)](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/a05a114b-08e2-424f-89bc-9e1c594a1450/image.png)

Thanks To의 About 페이지
(데보션 소개, 파트너십, 교육 후기 등을 조회할 수 있는 페이지)

![Thanks To의 Project 페이지 
(프로젝트 결과물을 조회할 수 있는 페이지)](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/b555a6a0-9d80-48b4-96c7-79a2e8274b0e/image.png)

Thanks To의 Project 페이지 
(프로젝트 결과물을 조회할 수 있는 페이지)

- 기존의 프로젝트 결과물은 **한 곳에서 모아볼 수 없고**, **홈페이지 여기저기에 산재**되어 있다는 문제가 있음.

![현재 데보션 영 프로젝트 결과물의 위치 (스토리 → 데보션 영 → 개발과제 or 전체)
](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/f34890f8-4887-40c9-9f0e-bb235dbc777a/image.png)

현재 데보션 영 프로젝트 결과물의 위치 (스토리 → 데보션 영 → 개발과제 or 전체)

![현재 OpenLab 프로젝트 결과물의 위치 (Tech → OpenLab)](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/3d201759-0780-4239-9c27-391a3ef79045/image.png)

현재 OpenLab 프로젝트 결과물의 위치 (Tech → OpenLab)

- 프로젝트 결과물이 산재되어 있는만큼, **결과물 조회가 프로그램 공유 및 지원까지 이어지기 어려움. 지원을 유도할 수 있는 CTA 버튼 삽입**
</aside>

<aside>

1. About 탭

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/28655e8e-f328-423a-92d1-91ef994aaea0/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/7dc37357-5452-4c6d-9caf-962910c38878/image.png)

📌 **기능 정의** 

데보션 프로그램에 대한 **소개, 파트너쉽 업체 소개, 프로그램 소개, 활동후기, 지원하기**를 모아놓은 탭

📌 **기능 상세**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 1 | 상단탭 | Thanks To 페이지를 구성하는 두 개의 탭, **About** 과 **Project** |
| 2 | 데보션 소개 요소 | About 탭 가장 상단에서 확인할 수 있는 데보션 관련 정보를 담은 세 개의 박스 |
| 3 | 데보션 영 프로그램 소개 버튼 | 데보션 영 프로그램의 결과물로 바로 이동할 수 있는 버튼 |
| 4 | OpenLab 프로그램 소개 버튼 | OpenLab 프로그램의 결과물로 바로 이동할 수 있는 버튼 |
| 5 | 리뷰 콘텐츠 | 데보션 **교육 프로그램 수료생의 후기**를 **카드형태**로 제시 |
| 6 | 지원하러 가기 버튼 | **교육 프로그램에 바로 지원하러 갈 수 있는 버튼**을 삽입 |

📌 **기대효과**

- 통일된 로직으로 프로젝트 결과물을 모아보기 **편한 UI 환경 제공**
- 프로그램 소개 외에도 파트너사, 활동 후기, 바로 지원하기 등의 추가 소개와 기능을 통해 **프로그램 자체의 활성화 기여**
</aside>

<aside>

1. Project 탭

![프로젝트 탭](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/da766220-38cf-4312-b9eb-be0b829c06a5/image.png)

프로젝트 탭

![프로젝트 탭_데보션영 선택](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/7726cd0a-c9d1-4ce9-aa0c-90b9bdabf4fd/image.png)

프로젝트 탭_데보션영 선택

![프로젝트 탭_데보션 영 선택_프로젝트 선택](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/3ef18763-0690-45aa-b3d1-2907ee8141c8/image.png)

프로젝트 탭_데보션 영 선택_프로젝트 선택

📌 **기능 정의** 

데보션 영과 OpenLab 의 결과물을 모아놓은 페이지

📌 **기능 상세

<프로젝트 탭>**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 1 | 프로그램 선택 탭 | 상단에 데보션 영과 OpenLab 각각의 프로그램에 대한 프로젝트 결과물을 볼 수 있도록 하는 버튼 |
| 2 | 데보션 영 프로젝트 영역 | 데보션 영 프로그램을 통해 만들어진 프로젝트 결과물의 전반을 나타내는 영역 |
| 2.1 | 기수 필터 | 데보션 영의 프로젝트를 기수별로 모아볼 수 있게 하는 기능 |
| 2.2 | 지원하러 가기 버튼 | **About 페이지 하단의 지원하러 가기와 동일**한 버튼 |
| 2.3 | 프로젝트 결과물 카드 | 프로젝트 결과물의 **제목**과 **대표 이미지**를 카드로 보여줌 |
| 2.4 | 전체 보기 | **데보션 영 결과물만** 조회할 수 있는 페이지로 넘어가는 버튼 |
| 3 | OpenLab 프로젝트 영역 | **“데보션 영” 영역의 기능과 동일** |
| 3.1 | 기수 필터 | “ |
| 3.2 | 지원하러 가기 버튼 | “ |
| 3.3 | 프로젝트 결과물 카드 | “ |
| 3.4 | 전체 보기 | “ |

**<프로젝트 탭_데보션영 선택>**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 1 | Our Activities | 큐시즘과 유사하게 **데보션영의 활동 정보를 표시**하는 영역 |

**<프로젝트 탭_데보션 영 선택_프로젝트 선택>**

|  | 기능 명 | 기능 상세 |
| --- | --- | --- |
| 1 | 게시물 | 데보션 인사이드에서 가져오 게시물 내용을 그대로 넣은 페이지 |
| 2 | 다른 글 둘러보기 | 해당 게시물과 같은 기수에서 나온 프로젝트 결과물 중 **랜덤**으로 세개의 게시물이 뜨도록 함.  |

📌 **기대효과**

- 통일된 로직으로 프로젝트 결과물을 모아보기 **편한 UI 환경 제공**
- **About 탭과 Project 탭 모두에서 프로그램에 지원하도록 넛지**
</aside>

# 4️⃣ IA (정보 구조도)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/bd5ffbf0-5101-4bbf-b277-d2ad0e0b0665/image.png)

---

# 기본과제 개발

## 📌 역할 분담

| 구분 | 이름 | 맡은 역할 |
| --- | --- | --- |
| FE | 최호 | 마이페이지 활동 대시보드, 뱃지 전체보기  |
| FE | 성태현 | 마이페이지 나의 활동 대시보드, 나의 활동 전체보기, 랭킹 전체보기 |
| BE | 윤소민 | 프로젝트 개시 페이지 백엔드 개발, 읽은 블로그 분석 API, 랭킹 상세보기 API, 랭킹 API |
| BE | 이건 | 일일미션 API, 리뉴얼 배지 API, 활동현황 API, 가입일 조회 API |

## 📌 개발 기간

- 2024.08.28 ~ 2024.09.08

## 📌 개발 환경

- JSP
- JQuery
- Java 8
- 전자정부프레임워크
- Spring 2.x
- MySQL 5.7
- MyBatis
- Apache Tomcat 8

## 📌 개발 중 고려한 점

### 배지 알림 서비스

- 기존의 배지 시스템에서 배지 획득 시 알림 전송
- 이에 따라 리뉴얼 배지 획득 성공 시 배지 알림 전송
- 또한 년도별 최초 로그인 시 배지 지급 기능 추가

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/3cc0bc80-af02-4f14-808a-1b0b8d094d44/image.png)

### 기존 API 룰 준수

- 기존 API 구현 방식에서 ApiBase를 상속받아 Controller 구현 및 에러 처리 진행
- 이러한 룰을 따라서 구현 및 에러 처리 진행

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/36514b0d-8441-4c38-a105-c4011efe9355/image.png)

### 응답에 대해 공통 로직 메서드 추출

- controller 단에서 계속해서 공통되는 응답 VO 생성에 대해 메서드 추출을 통한 가독성 향상

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/c40f7868-13e2-4e85-ba0c-758004d081ed/image.png)

### 정적 팩토리 메서드 도입을 통한 가독성 향상

- VO 별 정적 팩토리 메서드 도입을 통한 가독성 향상

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/f6c94bf7-14f6-444b-8956-15cb9a8caa75/image.png)

### 인터페이스를 통한 확장성 고려

- Service 단에서 interface 도입을 통해 확장성 고려

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/a8706fb2-974c-49b8-9829-a2947167f0ec/image.png)

### Stream API 적극 도입

- Stream API를 도입하여 가독성 향상
- Enum 타입 활용을 통한 매직넘버 치환

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/9648e7f4-81d0-4183-91bb-9dd64acf973a/c8fcd12e-9f37-4d73-91cd-813a92023d85/image.png)

### 책임 분리를 통한 확장성 고려

- 도메인 로직은 도메인 service 혹은 DAO에, 통계 관련한 로직은 Statistics 도메인으로 분리하여 구현
- 이에 따라 책임이 분리되며 확장성 증가

## 📌 추가 기본 세팅

```kotlin
CREATE TABLE `tb_board_view`
(
    `id`             bigint(20) unsigned NOT NULL AUTO_INCREMENT,
    `tb_board_id`    bigint(20)          NOT NULL COMMENT 'tb_board 테이블 id',
    `viewer_id`      bigint(20)          NOT NULL COMMENT 'tb_ext_user_info 테이블 inx',
    `tb_category_nm` varchar(40)         NOT NULL COMMENT 'tb_category 테이블 nm',
    `view_date` datetime NOT NULL COMMENT '조회한 일자',
    PRIMARY KEY (`id`),
    UNIQUE KEY `unique_board_view` (`tb_board_id`, `viewer_id`, `tb_category_nm`)
) ENGINE = InnoDB
  AUTO_INCREMENT = 18
  DEFAULT CHARSET = utf8mb4
  COLLATE = utf8mb4_unicode_520_ci
    COMMENT='블로그 viewer 저장';
CREATE TABLE tb_renewal_badge (
	idx 			INT(11) 		AUTO_INCREMENT PRIMARY KEY COMMENT 'id',
    nm				VARCHAR(20) 	NOT NULL COMMENT '이름',
    description 	VARCHAR(50) 	NOT NULL COMMENT '설명',
    file_idx		INT(11) 		NOT NULL COMMENT '파일 인덱스',
    like_condition	INT(11)			NOT NULL COMMENT '좋아요 조건',
    post_condition	INT(11)			NOT NULL COMMENT '게시글 조건',
    reply_condition	INT(11)			NOT NULL COMMENT '댓글 조건',
    badge_level		INT(11)			NOT NULL UNIQUE COMMENT '배지 레벨',
    reg_date		TIMESTAMP DEFAULT CURRENT_TIMESTAMP NOT NULL,
    upd_date		TIMESTAMP DEFAULT CURRENT_TIMESTAMP NOT NULL ON UPDATE CURRENT_TIMESTAMP,
    FOREIGN KEY (file_idx) REFERENCES tb_file(idx)
) 	engine = InnoDB
	AUTO_INCREMENT = 1
    DEFAULT CHARSET = utf8mb4
    COLLATE = utf8mb4_unicode_520_ci;
    

CREATE TABLE tb_ext_acquired_badge (
	user_id			INT(11)		NOT NULL COMMENT 'userId',
    acquired_year	VARCHAR(7)	NOT NULL COMMENT '획득 년도',
    badge_id		INT(11)		NOT NULL COMMENT '배지 id',
    acquired_date	TIMESTAMP DEFAULT CURRENT_TIMESTAMP NOT NULL COMMENT '획득일',
    PRIMARY KEY (user_id, acquired_year, badge_id),
    FOREIGN KEY (badge_id) REFERENCES tb_renewal_badge (idx)
)	engine = InnoDB
    DEFAULT CHARSET = utf8mb4
    COLLATE = utf8mb4_unicode_520_ci;

INSERT INTO tb_renewal_badge (nm, description, file_idx, like_condition, post_condition, reply_condition, badge_level) VALUES ('뉴비 탐험가', '최초 로그인 시 자동 부여', 7818, 0, 0, 0, 1);
INSERT INTO tb_renewal_badge (nm, description, file_idx, like_condition, post_condition, reply_condition, badge_level) VALUES ('활동 챌린저', '활동 챌린저', 7819, 5, 0, 5, 2);
INSERT INTO tb_renewal_badge (nm, description, file_idx, like_condition, post_condition, reply_condition, badge_level) VALUES ('개발 전문가', '개발 전문가', 7820, 15, 2, 15, 3);
INSERT INTO tb_renewal_badge (nm, description, file_idx, like_condition, post_condition, reply_condition, badge_level) VALUES ('커넥션 메이커', '�커넥션 메이커', 7821, 30, 5, 30, 4);
INSERT INTO tb_renewal_badge (nm, description, file_idx, like_condition, post_condition, reply_condition, badge_level) VALUES ('마스터', '마스터', 7822, 50, 10, 50, 5);

```
