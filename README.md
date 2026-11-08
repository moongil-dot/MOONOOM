# 통합 대시보드 — GitHub Pages 배포 방법 (무료)

이 폴더의 `index.html` 하나가 앱 전체예요. **회사 데이터(재고, 업무, 미출, 일정)는 들어 있지 않아요.**
공개 주소에 올려도 데이터가 노출되지 않고, 각 휴대폰에서 엑셀을 불러와 쓰는 방식이에요.

## 1. 저장소 만들기
1. https://github.com 에 로그인(없으면 무료 가입)
2. 오른쪽 위 `+` → `New repository`
3. Repository name: `inventory-dashboard` (원하는 영문 이름)
4. **Public** 선택 (무료 Pages는 공개 저장소만 돼요) → `Create repository`

## 2. 파일 올리기
1. 저장소 화면에서 `uploading an existing file` 클릭 (또는 `Add file` → `Upload files`)
2. `index.html` 파일을 끌어다 놓기 → 아래 `Commit changes`

## 3. Pages 켜기
1. 저장소 `Settings` → 왼쪽 `Pages`
2. Source: `Deploy from a branch`
3. Branch: `main` / `(root)` → `Save`
4. 1~2분 뒤 같은 화면에 주소가 나와요: `https://내GitHub아이디.github.io/inventory-dashboard/`

## 4. 휴대폰에서 쓰기
1. 휴대폰 Chrome(또는 삼성 인터넷)에서 위 주소 열기 (https라서 카메라 사용 가능)
2. `엑셀 불러오기` → 폰의 파일/원드라이브에서 `재고관리` 엑셀 선택
3. 검색창 오른쪽 아이콘: 바코드 카메라, 기본 카메라
4. Chrome 메뉴 `⋮` → `홈 화면에 추가`하면 앱처럼 바로 열려요

## 알아둘 점
- 불러온 데이터는 **그 휴대폰 브라우저에만** 저장돼요. 브라우저 데이터를 지우면 다시 불러와야 해요.
- 엑셀이 바뀌면 휴대폰에서 `엑셀 불러오기`를 다시 누르면 돼요.
- 이 방식은 Claude 안의 대시보드와 데이터가 따로예요. 일정, 일일 작업, 열 선택 공유는 기기마다 따로 저장돼요.
- 주소를 아는 사람은 앱을 열 수 있지만, 엑셀을 불러오기 전에는 아무 데이터도 보이지 않아요.
- 엑셀 읽기 도구는 인터넷(cdnjs)에서 불러오므로, 처음 열 때 인터넷이 필요해요.
