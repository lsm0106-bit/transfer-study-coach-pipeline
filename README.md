# 편입 학습 코치: 격리 테스트 스냅샷

이 저장소는 Google Apps Script 편입 학습 코치의 비운영용 스냅샷입니다. 개인 학습 기록, 실제 자료, 원본 시트 ID는 포함하지 않습니다.

## 공개 파일과 안전성
- `Code.gs.txt`는 `v0.1.0-archival-snapshot` 릴리스 첨부 파일입니다. 41,848 Unicode 문자(UTF-8 48,229바이트)이며 SHA-256은 `96d2a1b54bb20d270e4bf040ba49de5f21c514035195985b0232447e0ecf48fe`입니다. `TEST_SPREADSHEET_ID`는 `REPLACE_WITH_TEST_SPREADSHEET_ID`로 남아 있습니다.
- `appsscript.json`은 저장소 루트에 있습니다. `spreadsheets.currentonly` 범위만 선언합니다.
- `setupPipeline()`은 비활성화되어 있습니다. `runSyntheticIntegrationTests()`는 지정한 시트에 탭과 합성 행을 쓰므로, 실행이 필요하면 실제 자료와 분리된 폐기 가능한 합성 테스트 시트만 사용하세요. 원본 프로젝트나 학습 시트에 연결해 실행하지 마세요.

## 버전과 검증 한계
게시한 `Code.gs.txt`는 41,848자 초기 스냅샷입니다. 별도의 최신 검증 소스는 47,110자이며 SHA-256은 `a949bc34ab6adc19335c8991efa6e82d1400a73c08a617607b372e3be72f1855`입니다. 격리 Apps Script 테스트에서 최신 소스의 복구·날짜 경계 5건과 편집기에서 겹친 동시 저장 2건이 통과했다고 보고됐습니다. 메뉴 팝업은 `script.container.ui` 권한 부족으로 검증되지 않았습니다. 해당 결과는 이 저장소의 초기 스냅샷이 테스트를 통과했다는 뜻이 아닙니다.

이 코드는 실사용 배포본이 아닙니다. 게시 과정에서 원본 Apps Script 프로젝트나 시트를 실행하거나 수정하지 않았으며, 실사용 안전성 검증도 하지 않았습니다.