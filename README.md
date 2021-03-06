# Software-Engineering Team 6

### 👨‍💻 ‘내가 가진 식재료를 바탕으로 메뉴를 추천해주는 어플’
- 내가 보유한 식재료만으로 곧바로 조리할 수 있는 음식들을 보여줌으로써 어떤 요리를 만들 수 있을지 고민하거나 인터넷을 뒤져볼 필요가 없어진다.
- 요리를 만들고 식사를 마치면 본인이 가지고 있는 식재료에서 음식 조리에 사용된 재료는 자동으로 차감되기 때문에 식재료가 얼마나 남았는지 알 수 있고, 장을 언제 보러 가야 할지 미리 파악할 수 있다.
- 사용자는 제공되는 기존의 레시피를 이용하여 음식을 조리해먹을 수 있으며 자기만의 레시피를 만들고 다른 사용자들과 공유할 수도 있다.
또한, 다른 사용자들로부터 자기가 만든 레시피에 대한 추천과 피드백을 받을 수 있으므로 이전보다 더 나은 요리를 만들 수 있다.


### 👪 주요 고객층
- 평소에 요리에 자신이 없고 익숙하지 않은 사람들
- 한정된 식재료를 이용하여 최적의 식사를 하고싶은 자취생
- 매번 레시피에 필요한 식재료를 딱딱 맞춰서 구하기 번거로운 사람들
- 식재료가 떨어질 때쯤에는 매번 장을 언제 봐야하나 고민하고 냉장고를 들여다봐야 하는 주부들

### 🎯 기능적 요구사항
- 음식을 만들기 위해서 반드시 필요한 재료와 그렇지 않은 재료를 구분하고 만들 수 있는 요리 위주로 선별해서 보여줄 수 있어야 한다.
- 요리를 완성하면 요리에 사용된 재료를 자동으로 차감시킬 수 있어야 하고, 사용자가 보유한 재료가 얼만큼 남았는지 수치 상으로 보여줄 수 있어야 한다.
- 내가 만든 나만의 레시피를 공유할 수 있어야 하고, 다른 사용자가 공유한 레시피 또한 볼 수 있어야 한다.
- 내가 가지고 있는 식재료의 유통기한 및 보관 방법을 알려줄 수 있어야 한다.
- 내가 가지고 있는 식재료가 얼마나 남았는지 알려줄 수 있어야 한다.
- 내가 전에 조리했던 요리를 나만의 '요리 일기'에 기록함으로써 내가 며칠 전에 어떤 요리를 했는지 알 수 있어야 한다.

### 🏹 비기능적 요구사항
- 조리 가능한 요리가 다양할 경우 최근 조리 내역을 반영하여 사용자가 보다 다양한 음식을 접할 수 있어야 한다.

### 💻 필요한 기기
- Android OS를 지원하는 핸드폰

### 🏢 경쟁사 분석
- 상품형태에 의한 경쟁
 ● 요리백과 만개의 레시피 : 가장 대중적으로 알려진 어플이며 이름에 걸맞게 레시피 수 가 상당하다. 차별점으로 요리클래스가 연결되어있어 결재 후 바로 수강할 수 있다.
 ● 백주부 요리레시피 : 요리연구가로 많이 알려진 백종원씨의 방송에 나온 레시피가 정리되어 있다고 하여 유명해진 어플이며, 그 외 다른 유튜버, TV 프로그램에서 나온 
                        레시피 및 맛집 정보를 제공한다.
 ● 밥타임 : 저희 팀이 만들려하는 어플과 유사한 점이 많은 어플이며, 냉장고 속 식재료를 직접 등록할수있고 그를 통해 레시피 추천, 유통기한 관리, 식단관리를 해준다.
 ● 이밥차 : 요리잡지 판매부수 1위인 이밥차에서 만든 어플이며, 요리사진들이 고퀄리티여서 식욕을 자극시킨다. 또 잡지에 실린 요리들의 레시피를 제공한다.
 ● 해먹남녀 : 레시피 선두주자로 구글올해의 베스트어플 2회 선정될만큼 잘 만들어진 어플이며, 사용자의 취향을 고려한 레시피를 추천해준다. 
               앱안에 별도의 커뮤니티 공간있는데 다른 어플에 비해 굉장히 활성화 되어있다. 흡사 인스타 같다.
 ● 아내의 식탁 : 오직 주부들을 위해 만들어진 어플이다. 주부들을 타겟으로 해서 그런지 전통적인 한식과 퓨전한식 레시피가 주류이다. 
                  초보 주부를 위해서 재료손질법 보관법 알짜정보 노하우 를 정리해놓았다. 
 ● Kitchen Stories : 12개 이상의 언어로 번역되어있어 사용자가 외국인이 많은 어플이다.또 베지테리언과 같이 규정식을 먹는 사용자를 위해 카테고리가 따로 마련되어있다.
                      키친팁을 알려주는데 칼을 잡는 방법부터 재료 손실방법까지 요리를 처음하는 사람들에게 도움이되는 팁이 많이 정리되어있고 레시피를 보고 
                      요리를 진행할때 혹시나 키친팁을 읽지 않고 진행하는 사용자를 위해 레시피 중간중간에 키친팁을 넣어 놓아 선택적으로 볼수있게 해놓았다.

- 상품범위에 의한 경쟁
 ● 삼성냉장고 '패밀리 허브' : 뷰 인사이드 : 냉장고 속 식품인식 카메라로 유통기한 관리한다, 스마트폰 연동하여 언제 어디서나 냉장고 속 식재료를 알수있다. 
                               푸드레시피 추천 기능 : 냉장고 속 식재료를 이용한 레시피 추천, 레시피를 음성으로 읽어줌 
                               푸드 쇼핑 : 제휴된 쇼핑몰을 통해 원스톱 장보기

- 본원적 효익에 의한 경쟁
 ● 세계최대 레시피사이트 쿡패드 : 1997년 부터 23년 축척된 339만 개의 레시피가 정리되어있다. 
 ● 네이버 요리백과 : 단순 레시피만 제공합니다. 레시피를 보고 따라하기에는 부족한 감이 있다. 

### 🤝 팀 구성
| Participants | Roles | Skills | Training Needs |
|:------------:|:-----:|:------:|:--------------:|
| 송진호 | 팀장, 서버 개발, DB 설계 및 구현 | C, Java, Python, HTML, Javascript, Node.js(Express.js), MySQL | UML 모델링 |
| 김태호 | 문서작성 및 테스터 | C, Java | UML 모델링 |
| 류준형 | 안드로이드 개발, 테스터 | C, Java, Javascript(jQuery), MySQL, PHP, Python(NumPy, Matplotlib, TensorFlow-Keras), Flask | UML 모델링 |
| 박근모 | 안드로이드 개발, 테스터| C, Java, Android, Python, HTML, CSS | UML 모델링 |

