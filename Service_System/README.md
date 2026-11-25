# Service_System

세션, 구간, 근거 캡처, 설정값을 보관하고 REST API로 제공한다. PythonAnywhere에서 구동.

## 예정 구성

| 위치 | 내용 | 구분 |
|---|---|---|
| mysite/, blog/ | Image Blog, 토큰 로그인, 게시 API | 공통평가 01에서 가져옴 (별도 커밋) |
| study/models.py | StudySession, Segment, DetectorConfig | 신규 |
| study/views.py | 목록, 획득, 설정 API | 신규 |
| study/calibration.py | 임계값 산출 | 신규 (F2) |
| study/tests.py | API와 재계산 테스트 | 신규 |

## 실행

(구현 후 작성)
