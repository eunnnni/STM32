# STM32

1. Choose protocol

   a. I2C (Inter-Integrated Circuit)
      I2C 개념 참조 https://wikidocs.net/160156
      반이중(쌍방향이지만 송수신 한번에 하나씩만 가능) / SDA, SCL 선 두개만 이용
   
   b. SPI (Serial Peripheral Interface)
      SPI 개념 참조 https://eteo.tistory.com/160
      전이중(쌍뱡향, 동시에 송수신 가능) / SCK, MISO, MOSI, ss 선 네개 이용 / 속도 더 빠름

   -> 굳이 SPI를 사용할 필요가 없어보임. I2C 프로토콜 선택

   
2. I2C 
