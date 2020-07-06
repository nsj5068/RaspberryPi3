# RaspberryPi3

라즈베리파이3를 가지고 공부하는 공간
주로 Python과 MariaDB, 웹서버로는 Thinkspeak를 사용

### 1. 라즈비안 설치 
1. MicroSD 카드를 사용, 포멧(FAT-32(exFAT)형식으로)
2. https://www.raspberrypi.org/downloads/raspberry-pi-os/

<img src="https://user-images.githubusercontent.com/64456822/86572230-9ba8cd80-bfad-11ea-9966-e92c42e2eed8.JPG" width="650px" height="400px"></img>

  1) NOOBS 또한 해당 링크에서 따로 다운 받을 수 있음. 
  2) OS with desktop and recommended software: 그래픽환경과 자주 사용하는 프로그램들을 포함하는 버젼
  3) OS with desktop: 그래픽 환경 지원
  4) OS Lite : Command 모드만 지원
  
3. 해당 파일을 microSD 카드에 복제
4. balenaEtcher-Portable 실행
  1) Select image 선택 후 Raspbian 다운받은 파일 선택
  2) Select target은 자동으로 microSD가 들어있는 USB가 선택됨
5. Flash! 버튼을 누르면 복사시작
6. 완료하고, 다시 microSD카드가 들어있는 USB를 뽑았다가 다시 삽입
7. boot 라는 라벨이 붙혀진 USB드라이브로 잡힘.
8. boot 파일 안에 다음 파일을 복사
   1) ssh : 메모장을 킨 후, 아무것도 안 쓴채로 다른 이름으로 저장, ssh 로 저장함.
   2) wpa_supplicant.conf
   
   
  
  
