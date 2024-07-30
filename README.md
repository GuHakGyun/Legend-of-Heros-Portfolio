# [Unity 3D]Legend of Heros
# 1. 게임소개
<div align="center">
    <img src="https://github.com/user-attachments/assets/f857304f-e751-4448-8d17-fedce98e2661" alt="pngScreenShot" style="display: block;">
    <span style="display: block; margin: 0; padding: 0; line-height: 0;"><게임 이미지></span>
    </div><br/>


* 유니티를 배우면서 팀프로젝트를 통해 제작한 3D 게임 포트폴리오 입니다.
* 제가 담당한 부분은 **굵은 표시**로 표현하였습니다.
* 개발기간 : 2024. 05.27 ~ 2024.06.21 ( 약 4주 )
* 형상관리 : Git SourceTree
<br/>

# 2. 개발 환경
* Unity 2022.3.25f1 LTS
* C#
* Window 10
<br/>

# 3. 참여인원 및 역할

| 참여 인원 | 역할 |
| ------------ | -------------------------------- |
| **구학균** | **캐릭터 클래스(전사,궁수), 캐릭터 이동 및 애니메이션 구현, 스킬이펙트 표현 및 충돌감지** |
| [김양현](https://github.com/yangstar98) | 스킬 및 아이템 생성, 상태이상 구현, 보스몬스터 구현, 사운드 제어|
| [김재훈](https://github.com/JaerHoon) | 일반몬스터 구현, UIUX, 스테이지 연출, 맵 디자인 및 오브젝트 상호작용|
<br/>

# 4. 사용 기술 
| 사용 기술 | 설명 |
| ------------ | -------------------------------- |
| 디자인 패턴| 싱글톤을 활용하여 Manager 관리 <br> ScriptableObject를 이용하여 캐릭터 및 몬스터 데이터 관리 |
| 유한상태머신| 파라미터에 따른 애니메이션 연출 <br> Sub-State Machine을 활용한 콤보공격 구현 |
| Layer Mask| Layer를 활용하여 플레이어가 범위 내 몬스터를 인식함 <br> 몬스터는 범위 내 플레이어를 인식하여 추적 및 공격 시전 |
| Avatar Mask| Transform으로 뼈대를 설정하여 자연스러운 애니메이션 연출 |
| Object Pooling| 자주 사용하는 객체는 Pool로 관리(몬스터,투사체,데미지 텍스트 등) |

