# PLC

컵 검출 X000가 ON하고 있을 떄,커피공급 버튼 X001을 누르면(X0001 ON) 커피공급 출력 Y051가 동작해, CUP에 뜨거운 물이 따라진다. 뜨거운 물은 버튼을 누르고 있는 동안만 흘러들어가져
버튼으로부터 손을 떼어 놓으면 정지한다. 컵 검출 X000가 OFF 때에는 커피공급 버튼 X001를 눌러도 뜨거운 물은 따라지지 않는다. 탱크의 물이 적게 되면 하한 LS X003가 ON해, 물 보충밸브
Y053가 작동을 정지한다. 물 보충 동작을 5회 실시하면, 커피 교환 표시 램프가 점등한다. 확인 버튼을 누르면, 커피교환 표시 램프가 소등한다.

X00 컴 검출 센서
X01 커피 공급 버튼
X02 커피 잔량 확인 버튼
X03 물 탱크 하한 리밋 센서
X04 물 탱크 상한 리밋 센서 

Y50 커피 잔량 알림 램프
Y51 커피 공급 밸브
Y53 물 보충 밸브

<img src="https://github.com/user-attachments/assets/a1d14fc9-4ee5-470f-a035-e215787d254b" style="width:500px;">


