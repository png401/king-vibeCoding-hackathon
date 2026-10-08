# 장애물 / 레어템 이미지 넣는 법

이 폴더에 아래 이름으로 이미지 파일을 올리면, 게임이 자동으로 사용합니다.
코드 수정 없이 그냥 깃허브에 파일만 올리면 돼요 (없는 파일은 자동으로 무시됩니다).

## 피해야 하는 일반 장애물
```
images/obstacle1.png
images/obstacle2.png
images/obstacle3.png
images/obstacle4.png
images/obstacle5.png
images/obstacle6.png
images/obstacle7.png
images/obstacle8.png
```
1개만 올려도 되고, 8개를 다 안 채워도 됩니다.

## 맞혀야 하는 초레어템 (맞은 개수가 결과창에 표시됨)
```
images/rare.png
```
이 파일만 맞으면 피하지 않고 맞아야 점수가 되고, 결과창에 맞은 개수만큼 아이콘이 줄줄이 나와요.

## 공통 규칙
- 파일명은 정확히 위와 같이 (소문자, 숫자 포함) 맞춰주세요.
- 확장자는 꼭 **.png**로 올려주세요 (다른 확장자는 인식 안 돼요). jpg 사진이면 png로 변환해서 올려주세요.
- 정사각형 이미지를 권장해요 (원형으로 잘려서 표시됩니다). 세로/가로가 다르면 가운데 부분만 보여요.
