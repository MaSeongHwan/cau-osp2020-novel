# 릴레이 소설 프로젝트

2020년 2학기 중앙대학교 예술공학대학 오픈소스프로그래밍 수업의 과제입니다.

## 릴레이 소설 #1

### 소설 요건
아래 요건에 따라 소설을 함께 작성합니다.

- 제목: **"고양이의 하루"**
- 시점: **3인칭 전지적 작가 시점** 및 **1인칭 고양이 시점**
- 구조: **5막 구조 (발단-전개-위기-절정-결말)**
- 기타:
    * 주인공 고양이는 이야기 중간에 죽지 않음.
    * 주인공 고양이는 다른 생물로 변신하지 않음.

### 라운드 마감일

- 발단:  2020년 11월 16일 (월)
- 전개:  2020년 11월 19일 (목)
- 위기:  2020년 11월 23일 (월)
- 절정:  2020년 11월 26일 (목)
- 결말:  2020년 11월 30일 (월)

### 작성 규칙
- 5막 구조에 따라 **총 5회**의 라운드로 시행함.
- 기본 점수를 확보하기 위해서는 각 라운드(발단, 전개, 위기, 절정, 결말)에서 최소 1회 작성 필요.
- `manuscript.md` 파일에 작성.
- Fork한 다음 새로운 Branch를 생성하여 작성.
- 단일 Pull Request 당 **최소 5문장, 최대 10문장**.
- 문장은 **마침표**(.)로 계수.
- 새로운 문단 시작은 자유롭게 가능.
- 대사 또는 독백은 아래와 같이 **마크다운 코드 블록**으로 표기.

    ```
    대사는 이렇게 표기합니다.
    ```

- 내용 흐름이 어색하거나 형식이 잘못된 경우 Merge하지 않을 수 있음.
- 여러 Pull Request가 들어오는 경우 매니저(GitHub Collaborators)가 내용을 보고 선택할 수 있음.
- 소설 중간 어느 곳이든 **삽화 이미지**를 **본인이 직접 작성**하여 제출할 수 있음.
- 삽화 이미지의 퀄리티가 낮은 경우 Merge하지 않음.
- 오타, 맞춤법, 띄어쓰기, 서식 등을 자유롭게 수정하여 Pull Request 가능.
- 규칙은 소설이 작성되면서 얼마든지 수정될 수 있음.
- 상식 선에서 불쾌하거나 선정적인 내용 Pull Request시 **F학점**.
- GitHub `Issues` 항목에서 질의응답, 토론주제, 건의사항, 아이디어 등 자유롭게 작성 가능.

### 평가 규칙
- 한 라운드에서 소설 내용 작성으로 1회 Merge 성공 시 기본 점수 **10점** 부여.
- 한 라운드에서 한 사람이 **추가로** Merge 할 수 있는 최대 횟수는 **2회**이며, Merge당 추가 점수 **5점** 부여.
- 따라서 소설 내용 작성만으로 한 라운드에서 얻을 수 있는 점수는 총 **20점**.
- 삽화 이미지는 라운드에 상관없이 하나 당 **추가 점수 5점** 부여.
- 오타, 맞춤법, 띄어쓰기, 서식 등 참여도에 따라 별도 추가 점수 **최대 20점**까지 차등 부여.

### 명명 규칙
- 각 소설 파트의 영문명은 다음과 같이 정의.
   * 발단: exposition
   * 전개: complication
   * 위기: crisis
   * 절정: climax
   * 결말: resolution
- 브랜치는 "**소설파트-학번-번호**" 로 명명.
   * 예1) 발단에 처음으로 내용을 추가하는 경우: "exposition-20201234-01"
   * 예2) 절정에 두 번째로 내용을 추가하는 경우: "climax-20201234-02"
   
- 커밋 메시지는 "**[파트:작성 종류] 작성 요약**" 으로 명명.
   * 작성 종류에는 [소설], [삽화], [정정], [관리], [기타] 가 있음.
   * 예1) [절정:소설] 내용 추가
   * 예2) [위기:삽화] 고양이가 점프하는 그림 삽입
   * 예3) [발단:소설] 고양이가 독백하는 내용 추가
   * 예4) [결말:정정] 오타 3개 수정
   * 예5) [전개:정정] 띄어쓰기 수정
