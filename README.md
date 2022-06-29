# Arduino-Airplane
Arduino airplane with MPU-6050(GY-521) 6DOF sensor and SG90 servo motor and visualize using processing

## 아두이노 비행기
- MPU-6050(GY-521) 6축 자이로 센서 1개
- SG90 서보모터 1개

## processing을 이용한 시각화
1. processing 설치
2. processing 라이브러리 폴더에 toxiclibs_p5, toxiclibscore 각각 추가
3. arduino_airplane_processing.pde 파일 실행
4. 39번줄 port = new Serial(this, "/dev/cu.usbserial-120", 115200); 에서 ""안을 자신의 아두이노 포트 이름으로 수정 (윈도우일 경우 COM숫자)
