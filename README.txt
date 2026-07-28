

MAP CLICK FIX
- 세계관 그래픽과 기능은 유지
- 지도 지역 버튼의 클릭/터치 이벤트를 명시적으로 연결
- 지도 장식 레이어가 버튼을 가로막지 않도록 pointer-events와 z-index 수정
- PC 클릭 및 아이패드 터치 대응


FINAL LAST REVISION
- 홈: 다이애나와 루비를 한 장의 캐릭터 그룹으로 합침
- 학습루틴/두뇌루틴: 화이팅하며 뛰는 다이애나 적용
- 특별미션: 마법을 부리는 다이애나 적용
- 독서 프로젝트: 전체 독서 장면 유지
- 독서 기록 앨범: 좌우가 이어지는 펼친 마법 기록장 디자인
- 달빛은행: 어색한 반투명 캐릭터 박스 삭제, 펼친 통장 디자인으로 통합
- 세계관: 지역 버튼 클릭 시 openModal이 호출되도록 오류 수정
- 달빛일기: 체크형 기록 마지막에 선택형 자유 한 줄 입력 추가
- 설정에서 자유 한 줄 안내문 수정 가능
- 통계와 PDF 성장 리포트에 최근 달빛일기 내용 표시


PROJECT LUNA V1 GRAPHIC COMPLETE
- Existing functions, points, settings, approvals, diary and reading logic preserved
- Learning / brain / daily habit routine panels changed to magical notebook presentation
- Routine characters enlarged and integrated inside the notebook instead of floating in empty space
- Diana and Ruby on the home screen positioned as one closer companion group
- Unlocked world regions now open with a full-screen zoom, golden door, sparkle and adventure card sequence
- Locked regions still show the existing locked 안내 popup


PROJECT LUNA V2 BACKUP ALPHA
- V1 화면과 기존 기능 유지
- 하루 한 번 브라우저 자동 백업
- 자동 백업 3~60개 보관 설정
- JSON 백업 파일 내보내기 및 복원
- 이전 형식 백업과 V2 형식 백업 모두 불러오기
- 복원/불러오기 전에 현재 상태 안전 백업
- 주의: 브라우저 자동 백업은 Safari 데이터 삭제 시 사라질 수 있으므로 JSON 파일도 주기적으로 보관 권장


PROJECT LUNA V1.1 REAL USE FINAL
- 오늘부터 아이가 실제 사용할 안정화 버전
- V1 그래픽, 세계관, 루틴, 독서, 승인센터, 달빛일기 유지
- 엄마 전용 백업센터에 날짜별 실사용 메모 추가
- 아이 반응과 가장 오래 본 화면 선택 기록
- 같은 날짜 메모 수정 및 최근 30개 확인
- 성장 통계와 PDF 성장 리포트에 엄마 메모 포함
- 엄마 메모 저장 때 안전 스냅샷 생성
- JSON 백업에 엄마 메모까지 포함

권장 실사용 방법
1. 첫날에는 아이에게 사용법을 자세히 설명하지 말고 자연스럽게 눌러보게 해주세요.
2. 저녁에 설정 > 데이터 관리 > 엄마의 오늘 메모에 짧게 관찰 내용을 남겨주세요.
3. 3~7일 사용 후 불편했던 버튼, 가장 좋아한 화면, 자주 건너뛴 활동을 모아 다음 수정에 반영하세요.
4. 여행 전과 일주일에 한 번은 JSON 백업 파일을 별도로 받아 보관하세요.


V1.1.1 MOM MEMO FIX
- 엄마 메모 저장 시 state.parentMemos 배열을 항상 보정
- Safari에서 ID 요소가 전역변수로 잡히지 않아도 저장되도록 수정
- 저장 버튼에 직접 이벤트 연결
- 메모 저장 후 설정 전체를 다시 그리지 않고 기록 목록만 갱신
- 자동 스냅샷 오류가 있어도 메모 본문 저장은 완료
- 저장 실패 시 화면에 오류 메시지 표시


PROJECT LUNA V1.2 REAL USE GITHUB
- 학습루틴, 두뇌루틴, 생활루틴의 10개 활동을 왼쪽 세로 목록으로 변경
- 오른쪽에는 지금 해야 할 한 가지와 캐릭터를 크게 표시
- 완료/현재/나중에 항목을 색상으로 구분
- 기존 기능, 설정, 저장, 백업, 엄마 메모 유지
- CSS를 styles.css로 분리
- GitHub Pages용 assets 폴더 구조와 .nojekyll 포함


PROJECT LUNA V2.0 REAL USE
- 왼쪽 루틴 목록과 오른쪽 노트 높이 통일
- 가운데 현재 할 일 영역 확대
- 오른쪽 캐릭터 축소
- 기존 저장/백업/엄마메모/독서/세계관 유지
