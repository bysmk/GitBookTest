
---
description: 스튜디오의 기본 사용 방법이에요
---

# Studio4

## 메뉴 바 - Menu Bar

기본적으로 스튜디오의 상단에 위치하고 있습니다. 원하는 위치에 이동시킬 수 있습니다.

편집된 스튜디오의 저장 및 불러오기등의 기능은 여기서 사용할 수 있습니다.

![](../.gitbook/assets/studio\_manual\_220622\_01.png)

1. 파일 메뉴 (FileMenu)
2. 실행 취소 , 다시 실행 (Undo , Redo)
3. MultiTest 탭 메뉴
4. 빠른 실행 메뉴 (Quick Menu)

### 파일 메뉴 - File Menu11

<div class = "t1">

| Icon                                                                    | Action                          |      Key     | Description                                                                 |
| ----------------------------------------------------------------------- | ------------------------------- | :----------: | --------------------------------------------------------------------------- |
| ![New](<../.gitbook/assets/new (5) (19) (3) (1) (1) (1) (10) (27).png>) | New                             |    Ctrl+N    | 템플릿 팝업을 열어 다른 템플릿 맵을 실행할 수 있습니다.                                            |
|                                                                         | Open From File                  |    Ctrl+O    | 로컬 파일이 저장된 폴더를 엽니다.                                                         |
|                                                                         | Open From DITOLAND              | Ctrl+Shift+O | 템플릿 팝업을 열어 DITOLAND 클라우드에 저장된 파일을 보여줍니다.                                    |
| ![Save](<../.gitbook/assets/save (3) (1) (1) (10) (44).png>)            | Save To File                    |    Ctrl+S    | 현재 편집중인 맵을 로컬 파일로 저장합니다.                                                    |
| ![Save](<../.gitbook/assets/save (3) (1) (1) (10) (45).png>)            | Save To File As                 | Ctrl+Shift+S | 현재 편집중인 맵을 새 로컬 파일로 저장합니다.                                                  |
|                                                                         | Publish To DITOLAND             |              | 현재 편집중인 맵을 클라우드 저장소에 저장합니다.                                                 |
|                                                                         | Publish To DITOLAND As          |              | 현재 편집중인 맵을 클라우드 저장소의 새 슬롯에 저장합니다.                                           |
|                                                                         | Export All Script Data To Files |              | 현재 편집중인 맵의 모든 Script를 파일로 추출합니다.                                            |
|                                                                         | Import All Files To Script Data |              | Export한 모든 Script 파일을 읽어 맵에 적용합니다.                                          |
|                                                                         | Reset Layout                    |              | WorldTree , Property , ToolBOX , Palette , Script Editor의 위치를 초기 위치로 되돌립니다. |
|                                                                         | Game Setting                    |              | 플레이어에 노출되는 기능을 설정합니다.                                                       |
|                                                                         | About                           |              | 스튜디오의 버전정보를 확인합니다.                                                          |
|                                                                         | Help                            |              | 제작 가이드 사이트로 이동합니다.                                                          |
|                                                                         | Log Out                         |              | 계정을 로그아웃하며 로그인 페이지로 이동합니다.                                                  |
|                                                                         | Exit                            |              | 스튜디오를 종료합니다.                                                                |
</div>

### 빠른 실행 메뉴 - Quick Menu

<div class = "t2">

| Icon                                                                     | Action              |   Key  | Description                                                            |
| ------------------------------------------------------------------------ | ------------------- | :----: | ---------------------------------------------------------------------- |
| ![Publish](<../.gitbook/assets/publish (1) (1) (1) (10) (18).png>)       | Publish To DITOLAND |        | File Menu의 Publish To DITOLAND 기능과 동일합니다.  현재 편집중인 맵을 클라우드 저장소에 저장합니다. |
| ![Save](<../.gitbook/assets/save (3) (1) (1) (10) (46).png>)             | Save To File        | Ctrl+S | File Menu의 Save To File기능과 동일합니다.  현재 편집중인 맵을 로컬 파일로 저장합니다             |
| ![Save](<../.gitbook/assets/new (5) (19) (3) (1) (1) (1) (10) (22).png>) | New                 | Ctrl+N | File Menu의 New 기능과 동일합니다.  템플릿 팝업을 열어 다른 템플릿 맵을 실행할 수 있습니다.            |
</div>

## ToolBar

메뉴바 하단에 스튜디오에서 사용되는 기능들이 나열되어있습니다.

스튜디오에서 월드를 편집할때 쓰이는 대부분의 기능을 여기에서 간단하게 사용할 수 있습니다.

ToolBar에서 사용할 수 있는 기능들은 편집 상황에 따라서 변경됩니다.

![](../.gitbook/assets/studio\_manual\_220622\_02.png)

ToolBar 내의 확장 메뉴를 클릭할 경우 연관된 다양한 메뉴들을 확인할 수 있습니다.

### Play Test Tab

![](../.gitbook/assets/20200804\_164433.png)

Play Test 탭에선 실제로 지금까지 만든 게임을 업로드 전에 미리 확인해볼 수 있는 기능들을 지원합니다. 총 4가지 모드를 지원하며 추가 메뉴 버튼을 누르는 것으로 다른 모드를 선택할 수 있습니다.

지원하는 모드들은 하기와 같습니다.

<div class = "t3">

| Icon                                                                             | Action          | Description                                                           |
| -------------------------------------------------------------------------------- | --------------- | --------------------------------------------------------------------- |
| ![Play Mode](<../.gitbook/assets/play (5) (13) (1) (1) (1) (10) (18).png>)       | Play Mode       | 실제 게임과 동일하게 시뮬레이션 하며, 캐릭터를 0,0,0 좌표로 스폰 됩니다.                          |
| ![Play Here Mode](<../.gitbook/assets/playhere (5) (6) (1) (1) (10) (13).png>)   | Play Here Mode  | 캐릭터가 무조건 현재 카메라 좌표에서 스폰 되며 시뮬레이션을 시작합니다.                              |
| ![Run Camera Mode](<../.gitbook/assets/runcamera (2) (1) (1) (1) (10) (18).png>) | Run Camera Mode | 게임 시뮬레이션은 시작하지만 플레이어블 캐릭터는 생성하지 않습니다. 하지만 FreeCam 모드로 게임을 탐색할 수 있습니다. |
| ![Multi Test](../.gitbook/assets/multiplay.png)                                  | Multi Test      | Player를 거치지 않고 다수의 플레이어와 함께 게임을 플레이하는 상황을 재현할 수 있습니다.                 |

</div>

### Object Control Tab

![](<../.gitbook/assets/objectcontroltab-2 (2) (1) (1) (1) (2) (2).png>)

Object Control 탭에서는 오브젝트의 위치 , 크기 , 각도를 변경할 수 있는 기본 동작들을 설정할 수 있습니다. 총 4가지 모드를 지원하며 현재 활성화된 모드는 주황색으로 표시됩니다.

각 모드는 단축키 1, 2, 3, 4로 쉽게 활성화 할 수 있습니다.

현재 활성화된 모드에 따라서 객체를 선택했을 때 기즈모(Gizmo)가 각각 다르게 출력됩니다.

![](<../.gitbook/assets/gizmo (5) (8) (1) (1) (1) (10) (15).png>)

<div class = "t4">

| Icon                                                                  | Action     | Key | Description                                  |
| --------------------------------------------------------------------- | ---------- | :-: | -------------------------------------------- |
| ![Select](<../.gitbook/assets/select (2) (1) (1) (10) (18).png>)      | Select     |  1  | 객체를 선택합니다. 선택한 객체는 드래그 동작으로 위치를 변경시킬 수 있습니다. |
| ![Move](<../.gitbook/assets/move (5) (14) (3) (1) (1) (10) (18).png>) | Move       |  2  | 객체의 위치를 변경할 수 있습니다.                          |
| ![Rotate](<../.gitbook/assets/rotate (1) (1) (2) (4).png>)            | Rotate     |  3  | 객체의 각도를 변경할 수 있습니다.                          |
| ![Scale](<../.gitbook/assets/scale (5) (11) (1) (1) (10) (18).png>)   | Scale Mode |  4  | 객체의 사이즈 및 스케일을 변경할 수 있습니다.                   |

</div>

### Object Control Setting Tab

![](<../.gitbook/assets/objectcontrolsettingtab (5) (13) (6) (1) (1) (10) (17).png>)

Object Control의 방식이나 값들을 변경할 때 사용합니다.

<div class = "t5">

| Icon                                                                          | Action             | Description                                                      |
| ----------------------------------------------------------------------------- | ------------------ | ---------------------------------------------------------------- |
| ![World](<../.gitbook/assets/world (4) (1) (1) (10) (12).png>)                | World Coordination | 현재 기즈모를 World 축으로 사용합니다.  클릭할 경우 Local Coordination으로 변경합니다.     |
| ![Local](<../.gitbook/assets/local-4 (4) (1) (1) (2) (3).png>)                | Local Coordination | 현재 기즈모를 Local 축으로 사용합니다.  클릭할 경우 World Coordination으로 변경합니다.     |
| ![Grid](<../.gitbook/assets/gridsnap (5) (14) (4) (1) (1) (1) (10) (18).png>) | Grid Snap          | 기즈모 및 드래그로 객체를 이동시킬 때 Move , Rotate , Scale Size 값들을 변경할 수 있습니다. |

</div>

### Base Object Select Tab

![](../.gitbook/assets/20210401\_120124.jpg)

객체를 배치할 때 배치되는 객체의 모양을 설정할 때 사용합니다. 총 6가지 모드를 지원하며 추가 메뉴 버튼을 누르는 것으로 다른 모드를 선택할 수 있습니다.

<div class = "t6">

| Icon                                                                         | Action          | Description           |
| ---------------------------------------------------------------------------- | --------------- | --------------------- |
| ![Cube](<../.gitbook/assets/cube-3 (1) (1) (2) (1).png>)                     | Cube            | 육면체형 객체를 배치합니다.       |
| ![Sphere](<../.gitbook/assets/sphere (5) (9) (7) (1) (1) (1) (10) (18).png>) | Sphere          | 구형 객체를 배치합니다.         |
| ![Cylinder](<../.gitbook/assets/cylinder-4 (3) (1) (1) (1) (2) (2).png>)     | Cylinder        | 원통형 객체를 배치합니다         |
| ![Plane](<../.gitbook/assets/plane (5) (9) (2) (1) (1) (10) (17).png>)       | Plane           | 사각 판형 객체를 배치합니다       |
| ![Pyramid](<../.gitbook/assets/pyramid (2) (1) (1) (10) (18).png>)           | Pyramid         | 피라미드형 객체를 배치합니다       |
| ![Wedge](<../.gitbook/assets/wedge (5) (2) (1) (1) (1) (10) (20).png>)       | Wedge           | 삼각기둥형 객체를 배치합니다       |
| ![Cone](../.gitbook/assets/cone1.png)                                        | Cone            | 원뿔형 객체를 배치합니다         |
| ![Corner](../.gitbook/assets/corner.png)                                     | Corner          | 기울어진 피라미드형 객체를 배치합니다. |
| ![CylinderQuater](<../.gitbook/assets/cylinder quarter.png>)                 | CylinderQuater  | ¼ 원통형 객체를 배치합니다.      |
| ![HemishereQuater](<../.gitbook/assets/hemisphere quarter.png>)              | HemishereQuater | ¼ 구형 객체를 배치합니다.       |
| ![Hepta](../.gitbook/assets/hepta.png)                                       | Hepta           | 칠면체형 객체를 배치합니다.       |
| ![HexaPrism](../.gitbook/assets/hexaprism.png)                               | HexaPrism       | 육각기둥형 객체를 배치합니다.      |
| ![PentaPrism](../.gitbook/assets/pentaprism.png)                             | PentaPrism      | 오각기둥형 객체를 배치합니다.      |
| ![Prism](../.gitbook/assets/prism.png)                                       | Prism           | 삼각기둥형 객체를 배치합니다.      |
| ![Semicircle](../.gitbook/assets/semicircle.png)                             | Semicircle      | 반원 판형 객체를 배치합니다.      |
| ![Tetra](../.gitbook/assets/tetra.png)                                       | Tetra           | 사면체형 객체를 배치합니다.       |
| ![Torus](../.gitbook/assets/torus.png)                                       | Torus           | 도넛 모양 객체를 배치합니다.      |
| ![TorusQuarter](<../.gitbook/assets/torus quarter.png>)                      | TorusQuarter    | ¼ 도넛 모양 객체를 배치합니다.    |
| ![Trapezoid](../.gitbook/assets/trapezoid.png)                               | Trapezoid       | 사다리꼴 사각 기둥 객체를 배치합니다. |
| ![Triangle](../.gitbook/assets/triangle.png)                                 | Triangle        | 삼각 판형 객체를 배치합니다.      |
</div>

### Object Color & Material Select Tab

![](../.gitbook/assets/20200804\_165506.png)

객체를 배치할 때 배치되는 객체의 색깔과 재질을 설정할 수 있습니다.

### Base FX Select Tab

![](../.gitbook/assets/studio\_manual\_220622\_03.png)

FX 객체를 배치할 때 배치되는 FX 종류를 설정할 때 사용합니다. 총 6가지 모드를 지원하며 추가 메뉴 버튼을 누르는 것으로 다른 모드를 선택할 수 있습니다.

<div class = "t7">

| Icon                                                                           | Action        | Description             |
| ------------------------------------------------------------------------------ | ------------- | ----------------------- |
| ![Emitter](<../.gitbook/assets/emitter-2 (5) (1) (1) (1) (2) (5).png>)         | Emitter       | Emitter FX를 배치합니다.      |
| ![Smoke](<../.gitbook/assets/smoke (1) (1) (10) (18).png>)                     | Smoke         | Smoke FX를 배치합니다.        |
| ![Trail](<../.gitbook/assets/trail (5) (14) (2) (1) (1) (10) (18).png>)        | Trail         | Trail FX를 배치합니다         |
| ![Fire](<../.gitbook/assets/fire-3 (2) (1) (1) (1) (2).png>)                   | Fire          | Fire FX를 배치합니다          |
| ![Beam](<../.gitbook/assets/beam (5) (14) (5) (1) (1) (10) (18).png>)          | Beam          | Beam FX를 배치합니다          |
| ![Explosion](<../.gitbook/assets/explosion (3) (5) (1) (1) (1) (10) (15).png>) | Explosion     | Explosion FX를 배치합니다     |
| ![ParticleBurst](../.gitbook/assets/burst.png)                                 | ParticleBurst | ParticleBurst FX를 배치합니다 |
| ![LineTrail](../.gitbook/assets/linetrail.png)                                 | LineTrail     | LineTrail FX를 배치합니다     |
| ![Plane](../.gitbook/assets/plane.png)                                         | Plane         | Plane FX를 배치합니다         |
| ![Cylinder](../.gitbook/assets/cylinder.png)                                   | Cylinder      | Cylinder FX를 배치합니다      |
| ![Tornado](../.gitbook/assets/tornado.png)                                     | Tornado       | Tornado FX를 배치합니다       |
</div>

### UI 편집 시 ToolBar 메뉴

![](../.gitbook/assets/studio\_manual\_220622\_04.png)

UI 편집 모드가 되면 ToolBar의 메뉴들이 변경됩니다. UI 편집을 종료할 경우 메뉴들은 원래대로 돌아옵니다.

<div class = "t8">

| Icon                                                                           | Action           | Description                 |
| ------------------------------------------------------------------------------ | ---------------- | --------------------------- |
| ![Frame](<../.gitbook/assets/frame-4 (6) (1) (1) (1).png>)                     | Frame Widget     | Frame Widget 객체를 배치합니다.     |
| ![Image](<../.gitbook/assets/image (5) (9) (1) (1) (10) (18).png>)             | Image Widget     | Image Widget 객체를 배치합니다.     |
| ![Button](<../.gitbook/assets/button (5) (13) (3) (1) (1) (10) (17).png>)      | Button Widget    | Button Widget 객체를 배치합니다.    |
| ![](<../.gitbook/assets/text (5) (9) (7) (1) (1) (1) (10) (18).png>)           | Text Widget      | Text Widget 객체를 배치합니다.      |
| ![TextBox](<../.gitbook/assets/textbox (5) (9) (4) (1) (1) (10) (17).png>)     | TextBox Widget   | TextBox Widget 객체를 배치합니다.   |
| ![ScrollBox](<../.gitbook/assets/scrollbox (5) (9) (4) (1) (1) (10) (18).png>) | ScrollBox Widget | ScrollBox Widget 객체를 배치합니다. |
</div>


## 태스크 바

![](../.gitbook/assets/20200804\_170322.png)

TaskBar는 화면 하단에 위치하며 위치를 변경할 수 없습니다.\
TaskBar에서는 ScriptEditor를 제외한 1차 팝업들을 On / Off 할 수 있습니다.\
현재 활성화된 기능은 버튼이 노란색으로 출력됩니다.

<div class = "t9">

| Icon                                                                          | Action    | Description             |
| ----------------------------------------------------------------------------- | --------- | ----------------------- |
| ![WorldTree](<../.gitbook/assets/worldtree (2) (1) (1) (10) (18).png>)        | WorldTree | WolrdTree를 On / Off 합니다 |
| ![Property](<../.gitbook/assets/property (5) (12) (1) (1) (1) (10) (18).png>) | Property  | Property를 On / Off 합니다  |
| ![ToolBox](<../.gitbook/assets/toolbox (5) (1) (1) (10) (18).png>)            | ToolBox   | ToolBox를 On / Off 합니다   |
| ![Palette](<../.gitbook/assets/palette (6) (8) (1) (1) (10) (19).png>)        | Palette   | Palette를 On / Off 합니다   |
| ![UI Editor](../.gitbook/assets/UIeditor.png)                                 | UI Editor | UI Editor를 On / Off 합니다 |
</div>


## 카메라 이동

월드가 포커스 되어 있을 때 키보드를 사용해서 카메라를 이동시킬 수 있습니다.

카메라 이동 단축키 :

<div class = "t10">

| Key                             | Action         | Description                                            |
| ------------------------------- | -------------- | ------------------------------------------------------ |
| W                               | 전진             | 카메라가 전진합니다.                                            |
| S                               | 후진             | 카메라가 후진합니다.                                            |
| A                               | 좌              | 카메라가 좌로 이동합니다.                                         |
| D                               | 우              | 카메라가 우로 이동합니다.                                         |
| E                               | 상승             | 카메라가 상승합니다. (바라보는 각도 기준)                               |
| Q                               | 하강             | 카메라가 하강합니다. (바라보는 각도 기준)                               |
| Shift                           | 변속             | 이동 키와 같이 누르면 카메라의 속도가 변경됩니다.                           |
| F                               | 포커스            | 현재 선택된 파츠에 포커싱 합니다.                                    |
| Right Mouse Button Drag         | 카메라 회전         | 현재 좌표를 유지하며 카메라를 회전합니다.                                |
| Middle Mouse Button             | 카메라 이동         | 현재 좌표를 유지하며 카메라를 이동합니다                                 |
| Middle Mouse Button + On Object | 오브젝트 기준 카메라 회전 | 선택된 오브젝트 기준으로 카메라를 회전 시킵니다. (마우스 커서가 대상위에 있을때만 동작합니다.) |
| Mouse Scroll Wheel Up/Down      | 전진/후진          | 카메라가 천천히 전진/후진 합니다.                                    |
| Ctrl + Middle Mouse Button      | 카메라 축 이동       | 카메라가 바라보는 방향을 중심으로 회전합니다.        </div>                      |

## 그룹 단축키&#x20;

단축키를 이용해 오브젝트 그룹을 생성 및 그룹을 해제할 수 있습니다.

<div class = "t11">

| Action | Key              | Description           |
| ------ | ---------------- | --------------------- |
| 그룹 생성  | Ctrl + G         | 선택한 오브젝트를 그룹으로 생성합니다. |
| 그룹 해제  | Ctrl + Shift + G | 선택한 그룹을 해제합니다.        |
</div>

## 멀티 플레이 테스트

Play Test Tab

Menu Bar의 MultiTest 탭메뉴에서 Client 수를 설정하여 멀티 플레이 테스트를 실행할 수 있습니다.

![](../.gitbook/assets/20200804\_173131.png)

이후 Play Test Tab에서 Multi Test 버튼을 누르는 것으로 추가 설정 없이 멀티 플레이 테스트를 실행할 수 있습니다.

![](../.gitbook/assets/20200804\_170652.png)

멀티 플레이 테스트는 일반 플레이 테스트와는 다르게, 상단 아웃레이 메뉴에 Add Client 메뉴가 추가되며, Client 수를 다시 지정하여 원하는 멀티 플레이 상황을 재현할 수 있습니다.

![](../.gitbook/assets/20200804\_173823.png)

![](../.gitbook/assets/20200804\_154156.jpg)

## 스카이 뷰

![](../.gitbook/assets/studio\_manual\_220622\_05.png)

위에서 월드를 내려다 보듯이 카메라를 설정할 수 있습니다.

스카이뷰 모드일땐, 카메라 회전은 불가하며 Q / E 단축키 및 마우스 휠을 사용해 높낮이를 조정할 수 있습니다.

스카이뷰 기본값은 1,000으로 설정되어있으며, 스튜디오 설정 > 스카이뷰 높이에서 기본값을 변경할 수 있습니다.

스카이뷰 버튼을 다시 클릭하여, 기본 카메라 모드로 돌아올 수 있습니다.


<div class = "t12">

| Icon                                                                                     | Action    | Description                         |
| ---------------------------------------------------------------------------------------- | --------- | ----------------------------------- |
| <img src="../.gitbook/assets/studio_manual_220622_05_3.png" alt="" data-size="original"> | 스카이뷰 모드   | 위에서 월드를 내려다 보듯 카메라를 설정할 수 있는 모드입니다. |
| <img src="../.gitbook/assets/studio_manual_220622_05_2.png" alt="" data-size="original"> | 기본 카메라 모드 | 기본 카메라 모드 입니다.                      |
</div>


## 뷰 필터

![](../.gitbook/assets/studio\_manual\_220622\_06.png)

뷰필터에서는 월드에서 최적화 및 객체를 확인하기 위해 숨김처리 하는데에 사용합니다. 총 3가지 탭이 있으며, 각각 오브젝트 / Icon / ETC(네비메쉬)을 지원합니다.

각 탭에서 필요한 객체의 체크박스를 활성/비활성화할 수 있습니다.

뷰필터가 월드 트리 숨김처리보다 상위단으로, 월드 트리에서 보이는 상태라하더라도 뷰필터에서 숨김상태라면 숨김상태로 처리됩니다.

![](../.gitbook/assets/studio\_manual\_220622\_07.png)

<div class = "t13">

| Action | Description                     |
| ------ | ------------------------------- |
| 오브젝트   | Transform을 가지고 있는 객체를 숨김처리 합니다. |
| Icon   | Icon을 가지고 있는 객체의 Icon을 숨김처리합니다. |
| ETC    | 네비매쉬를 숨김처리 합니다.                 |
</div>


## Save(저장) 및 Publish(게시)

제작한 Land를 내 PC에 저장 또는 온라인 서버에 게시할 수 있습니다. 이를 통해 스튜디오를 종료한 후에도 언제든지 저장시점이후부터 편집을 이어갈 수 있습니다.

### Save(저장)

내 PC에 맵파일을 저장할 수 있습니다.

![](../.gitbook/assets/20201209\_165435.png)

Menu Bar의 'File Menu'에서 'Save To File'(저장) 또는 'Save To File As'(다른이름으로 저장)을 클릭합니다.

![](../.gitbook/assets/20201209\_165836.jpg)

저장할 경로를 지정하여 맵 파일을 저장합니다.

### Publish(게시)

맵을 온라인 서버에 게시합니다. 이렇게 하면 Studio를 실행할 수 있는 모든 PC에서 Land를 편집할 수 있습니다.\
Publish한 랜드는 게임에 Start Land 또는 Connect Land로 연결하여 다른 유저들에게 공개할 수 있습니다.

![](../.gitbook/assets/20201209\_170547.jpg)

Menu Bar의 'File Menu'에서 'Publish To DITOLAND'(게시)나 'Publish To DITOLAND As'(다른이름으로 게시)를 클릭하거나 Quick Menu에서 'Upload Map 아이콘'을 클릭합니다.

![](../.gitbook/assets/20201209\_171046.jpg)

'+ NEW SLOT' 버튼을 클릭하여 새로운 슬롯에 추가하거나 'Upload Map 아이콘'을 클릭하여 등록된 랜드를 업데이트 할 수 있습니다.

![](../.gitbook/assets/20201209\_171413.jpg)

![](../.gitbook/assets/20201209\_171559.jpg)

**Title**\
랜드 이름을 입력합니다. Start Land로 선택 시 게임 이름으로도 저장됩니다

**Description**\
랜드 설명을 입력합니다. Start Land로 선택 시 게임 설명으로도 저장됩니다.

**LandType**\
Start Land : 게임을 시작하는 랜드로 설정하며 게임을 생성합니다.\
Connect Land : 기존 생성된 게임에 연결되는 Connect Land로 생성합니다.\
None : 게임에 연결하지 않은 상태로 생성합니다.(웹 사이트에서 연결을 설정할 수 있습니다.)

**최대 접속 인원**\
서버당 접속할 수 있는 최대 인원을 설정합니다.

모든 항목을 입력한 후 'Create' 버튼을 클릭하여 저장합니다.

![](../.gitbook/assets/20201209\_173656.jpg)

랜드의 업로드가 완료되었습니다. 'View in web browser' 버튼을 클릭하여 웹 사이트의 랜드 설정 화면으로 바로갈 수 있습니다.\
'OK' 버튼을 클릭하여 팝업을 닫고 랜드를 계속 편집할 수 있습니다.

## 월드 공개 설정

월드는 최초 생성 시 비공개로 설정됩니다.\
공개를 원한다면 웹 사이트에 접속하여 설정을 변경해야 합니다.

### 월드 관리

![](<../.gitbook/assets/Untitled (6) (1).png>)

'홈 > 만들기 > 월드 관리' 화면으로 이동하여 등록된 월드를 확인할 수 있습니다.

### 월드 공개 설정

![](<../.gitbook/assets/Untitled (1).png>)

공개를 원하시면 '월 설정' 버튼을 클릭하여 이동한 게임 설정 화면에서 공개로 전환할 수 있습니다.



<style>
    .t1 table th:first-of-type { width : 1%; }
    .t1 table th:nth-of-type(2) { width : 10%; }
    .t1 table th:nth-of-type(3) { width : 20%; }
    .t1 table th:nth-of-type(4) { width : 40%; }
    
    .t2 table th:first-of-type { width : 10%; }
    .t2 table th:nth-of-type(2) { width : 30%; }
    .t2 table th:nth-of-type(3) { width : 20%; }
    .t2 table th:nth-of-type(4) { width : 40%; }
    
    .t3 table th:first-of-type { width : 10%; }
    .t3 table th:nth-of-type(2) { width : 30%; }
    .t3 table th:nth-of-type(3) { width : 60%; }
    
    .t4 table th:first-of-type { width : 10%; }
    .t4 table th:nth-of-type(2) { width : 20%; }
    .t4 table th:nth-of-type(3) { width : 10%; }
    .t4 table th:nth-of-type(4) { width : 60%; }
    
    .t5 table th:first-of-type { width : 10%; }
    .t5 table th:nth-of-type(2) { width : 30%; }
    .t5 table th:nth-of-type(3) { width : 60%; }
    
    .t6 table th:first-of-type { width : 10%; }
    .t6 table th:nth-of-type(2) { width : 20%; }
    .t6 table th:nth-of-type(3) { width : 70%; }
    
    .t7 table th:first-of-type { width : 10%; }
    .t7 table th:nth-of-type(2) { width : 40%; }
    .t7 table th:nth-of-type(3) { width : 50%; }
    
    .t8 table th:first-of-type { width : 10%; }
    .t8 table th:nth-of-type(2) { width : 40%; }
    .t8 table th:nth-of-type(3) { width : 50%; }
    
    .t9 table th:first-of-type { width : 10%; }
    .t9 table th:nth-of-type(2) { width : 40%; }
    .t9 table th:nth-of-type(3) { width : 50%; }
    
    .t10 table th:first-of-type { width : 30%; }
    .t10 table th:nth-of-type(2) { width : 25%; }
    .t10 table th:nth-of-type(3) { width : 45%; }

    .t11 table th:first-of-type { width : 25%; }
    .t11 table th:nth-of-type(2) { width : 25%; }
    .t11 table th:nth-of-type(3) { width : 50%; }

    .t12 table th:first-of-type { width : 10%; }
    .t12 table th:nth-of-type(2) { width : 30%; }
    .t12 table th:nth-of-type(3) { width : 60%; }

    .t13 table th:first-of-type { width : 20%; }
    .t13 table th:nth-of-type(2) { width : 80%; }
</style>
