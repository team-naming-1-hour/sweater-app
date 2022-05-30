# sweater

"뭘 입을지 고민하는 시간을 줄여줄 수 있을까?"라는 주제로 출발하여 제작하게 된 '기온별 의상 추천 앱'입니다.

## 앱 다운로드

https://play.google.com/store/apps/details?id=com.teamnaming1hour.sweather  
출시일 2022.5.4

## 프로젝트 개요

옷을 잘 입고 싶은, 적어도 못입고 싶진 않은 우리는 외출하기 전 더 좋은 코디를 찾기 위해 옷장 앞에서 많은 시간을 보냅니다.

그럼 우리가 좋은 코디를 고르게 되는 과정은 어떻게 될까요?
저희는 그 과정을 아래와 같이 분석했습니다.

1. 가진 옷들을 확인합니다.
2. 기온을 확인하고 기온에 맞춰 입을 수 있는 옷의 폭을 제한합니다.(여름이면 패딩,코트를 제외)
   - 이 과정에서 구글링을 통해 기온별 의상표를 참조하기도 합니다.
3. 날씨를 확인하고 날씨에 맞춰 입을 수 없는 옷들을 제외합니다.(ex. 바람이 많이 불면 치마를 제외)
4. 본인의 기호에 따라 특정 옷을 골라 입습니다.
   - 사람에 따라 타인의 코디를 검색해 비슷한 색매치,코디 매치를 하기도 합니다.

이 과정은 생각보다 긴 시간을 소요합니다. 우리가 옷장 앞을 서성이며 스마트폰을 만지작거리게 만드는 요인이기도 합니다.

그럼 이 과정을 어떻게 줄여줄 수 있을까요? **스웨더**는 아래와 같은 과정으로 이 과정을 단축하려합니다.

1. 외출할 지역의 기온 정보를 불러와 기온에 맞춰 입을 수 있는 옷을 제한
2. 외출할 지역의 날씨 정보를 불러와 입을 수 없는 일부 옷을 제외
3. 남은 옷들이 포함된 코디맵을 찾아 보여줍니다.
   - 만약 입고 싶은 옷이 있다면 그 옷이 포함된 코디맵을 찾아 보여줍니다.

### 기능

- **기온 정보 제공**: 날씨에 맞춰 옷을 입을 수 있도록 날씨 정보 제공
- **코디 추천 기능**: 날씨와 유저의 정보를 기반으로 코디를 추천해 주는 기능
  - 유저의 성별, 외출할 지역, 체질(더위를 타는 정도) 등을 고려해 코디를 추천해줍니다.
- **코디 필터 기능**: 입고 싶은 옷 또는 가진 옷들이 포함된 코디가 추천되도록 코디를 필터링할 수 있습니다.

자세한 기능 설명을 보려면 아래 링크를 클릭해주세요  
[자세한 기능 설명 보기](./functions.md)

## 사용 환경

- 안드로이드 4.4(version 19) 이상

## 개발 환경

- Visual Studio code

## 개발 기간

2022/03/01 ~ 2022/05/28

## 기술 스택

- Flutter(2.0)
- Firebase
  - Firebase Functions

## 개발자

팀 이름: teamnaming1hour

김현호 [@spaff13](https://github.com/spaff13)

- 앱 개발

유동원 [@Tuna-is-DW](https://github.com/Tuna-is-DW)

- 앱 개발

양기조 [@dev2820](https://github.com/dev2820)

- 테스트 작성
- 앱 개발(서브)
- BE (Firebase Functions로 데이터 요청 처리)

황지원 [@Jiwonii97](https://github.com/Jiwonii97)

- 날씨 API 개발
- 데이터 크롤링
- DB 관리
- 데이터 샘플링
