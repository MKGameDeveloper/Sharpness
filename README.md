Developed with Unreal Engine 4.261

YouTube Link : https://youtu.be/NAeZh7c9z6A?si=Gf-i_2Zuf5fA8Otq

프로젝트명: Sharpness (2023.12 – 2024.03)

장르: Soul Like
사용 엔진: Unreal 4.26
협업 유무 : X

[담당 구현 기술]

	Framework 부모 클래스를 상속받는 자식클래스 정의로 Character 구현
: 기본 Class 구현 후 상속을 통한 Character 관리의 효율성 증진

	Notify를 통한 실시간 Collision 및 효과 구현
: 공격 Collision의 활성화 여부와 해당 액션의 효과들을 Notify를 통하여 구현

	몬스터 AI 구현
: 추격하는 과정에서 플레이어와의 거리를 체크하여 공격 및 스킬 가능 여부를 판단하고 추격의 형태를 변경하는 AI 구현

	Custom Depth를 통한 Outline 구현
: Custom Depth 기능을 사용하여 일정 깊이가 되었을 경우 해당 객체의 Outline을 그려주어 가려져 있는 물체를 쉽게 볼 수 있도록 해주는 기능을 구현

	캐릭터의 Weapon, Armor 등과 연동 되는 Inventory 구현
: 상호작용 시 캐릭터의 방어구와 무기를 즉시 변경할 수 있는 기능을 가진 인벤토리를 구현. 아이템에 커서를 일정 시간 가져다 댈 시 아이템 정보를 불러올 수 있는 기능을 구현
