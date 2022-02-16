- 👋 Hi, I’m @meenjoon
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
meenjoon/meenjoon is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


[게임 설명]

신찬식의 도플갱어 죽이기

  - 신찬식은 엄청나게 쌘 나의 도플갱어를 죽이기 위해 사냥을 하여 능력치를 올리고 돈을 모아 상점에서 무기와 방어구를 
  구입하고 스킬을 찍어 힘을 키워야 합니다.
  - 10분 안에 신찬식_나이트메어 를 죽여야 게임이 클리어 됩니다.


[기능]

  1. 내정보보기 : 현재 내 정보를 확인 할 수 있습니다.
  
  2. 스킬 : 레벨과 스킬포인트를 통해 스킬을 찍어 사냥할 때 사용할 수 있습니다.
  
  3. 상점 : 무기와 방어구 포션을 구매,판매 할 수 있습니다.
  
  4. 인벤토리 : 내가 가진 무기와 방어구와 전리품 포션을 볼 수 있으며, 착용모드/착용해제모드 가 있습니다.
  
  5. 사냥하기 : 레벨에 맞는 몬스터들과 싸워 경험치를 얻어 레벨업을 하고, 전리품을 얻어 상점에 팔아 돈을 얻을 수 있습니다.
   
   - 나의 능력치와 레벨에 따라 몬스터를 선택하여 싸울 수 있습니다.
   - 신찬식은 기본공격/스킬공격/포션먹기/도망치기 선택 할 수 있고, 적절한 선택을 통해 몬스터를 처치해야합니다. 
   - 단, 몬스터의 공격은 몬스터의 등급에 따라 스킬 유무가 있으며 스킬이 있는 몬스터의 경우에는 주어진 마나에 딸
     기본공격과/스킬공격은 랜덤입니다.
   
  6. 휴식의 방 : 사냥을 하여 피가 없을때 휴식의 방에 들어가서 돈을 내고 체력과 마나를 풀로 채울 수 있습니다.


[Thread]

  1. 텍스트 Thread
    -프롤로그, 엔딩을 더 게임답게 하기 위해 한 글자씩 출력
  
  2. 몬스터 공격 Thread
    -몬스터의 공격을 몇 초 간격마다 자동으로 공격합니다(단, 스킬을 가진 몬스터는 마나가 있는 한 기본공격/스킬공격을 랜덤으로 받아 공격합니다.)
   
  3. 음악 Thread
    -각 상황마다 배경음악, 효과음을 재생합니다.
    -배경음악 : 로비메뉴BGM, 사냥터BGM, 휴식의방BGM, 상점BGM, 인벤토리BGM
    -효과음 : 물약 사용 효과음, 몬스터 처치 효과음, 캐릭터 죽음 효과음, 엔딩 효과음, 몬스터 공격 효과음
    
  4. 게임 제한시간 Thread
    -신찬식_나이트메어를 10분안에 잡지 못하면 실패입니다.
  
  
[GUI]
  
  1. 시간 알림 GUI: 0초부터 10분까지의 시간을 보여줍니다.
  
  
  
