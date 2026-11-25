# Edge_System

노트북 웹캠 입력을 YOLOv5로 검출하고, 착석/휴대폰 사용/졸음/이탈을 판정해 서버에 게시한다.

## 예정 파일

| 파일 | 내용 | 구분 |
|---|---|---|
| yolov5/ | YOLOv5 원본 | 외부 원본 (별도 커밋) |
| yolov5/changedetection.py | 상태 변화 시점 게시 | 공통평가 02에서 가져옴 |
| yolov5/seat.py | 좌석 ROI 착석 판정, 세션 분할 | 신규 (F1) |
| yolov5/phone_state.py | 이동량 계산, 거치/사용 상태 전이 | 신규 (F2) |
| yolov5/calibrate.py | 캘리브레이션 샘플 수집 | 신규 (F2) |
| yolov5/drowsy.py | 엎드림과 정지 판정 | 신규 (F3) |
| yolov5/api_client.py | 세션, 구간, 설정 API 호출 | 신규 |

## 실행

(구현 후 작성)
