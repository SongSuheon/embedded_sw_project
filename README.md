# embedded_sw_project

파이썬을 사용해 Adafruit 1.3" Color TFT Bonnet for Raspberry Pi에서 작동하는 게임 만들기

# 게임 이름 : Doge TO The Mars
## 게임 소개
도지코인이 폭락하는 상황속에서(도지 코인이 하늘에서 떨어짐) 도지코인에 투자했던 개미들(사우스 파크 캐릭터들)이 탈출을 시도하는데 이를 일론머스크가 트윗을 날려 막는다.</br>
하늘에서 떨어지는 도지코인을 획득하면 점수가 증가하며 일론머스크는 트윗을 날려 사우스 파크 캐릭터를 제거하거나 점프를 해서 피해야 한다.</br>
목숨은 총 3개이며  사우스 파크 캐릭터와 충돌하면 목숨이 하나씩 감소한다. 목숨이 0개가 되면 게임이 종료된다. </br>
점수를 최대한 높게 획득해서 다른 친구와 스코어 점수로 경쟁하는 게임이다.
</br>
## 시작화면
아무키나 누르면 게임을 시작한다.
</br>
## 게임화면
#### 1.일론 머스크
조이스틱 좌,우로 움직일수 있으며 #5키를 누르면 점프 #6키를 누르면 미사일(트윗)을 날릴 수 있다.
#### 2.미사일(트위터 파란새)
일론 머스크 바로 앞에서 발사되며 일론 머스크의 위치에 따라 발사 위치가 달라진다.
#### 3.개미들 (사우스 파크 캐릭터들)
화면 오른쪽에서 등장하며 5명의 캐릭터가 랜덤하게 왼쪽으로 도망을 친다. </br> 
일론머스크와 충돌하면 "CRASH"가 화면에 뜨면서 일론 머스크의 목슴을 하나 제거한다
#### 4.도지코인
하늘에서 랜덤한 위치에서 떨어진다.
</br>
## 엔딩화면
사우스 파크 캐릭터가 춤을추면서 게임 종료를 알린다.</br>
up key를 누르면 재도전 할 수 있다.

