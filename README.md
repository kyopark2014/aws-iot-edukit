# AWS IoT Edukit Workshop

[AWS IoT Edukit Workshop](https://edukit.workshop.aws/en/)에는 M5stack을 위한 여러가지 예제를 제공하고 있습니다. 해당 예제를 통해 M5stack을 제어하고 AWS IoT Core와 연결 할 수 있습니다. 

### 1) Visual Studio Code 환경 구성

M5Stack에 펌웨어를 업그레이드 하거나 삭제하는 동작은 Visual Studio Code를 이용해 편리하게 할 수 있습니다. 

[Visual Studio Code에 PlatformIO IDE Extension 설치 및 활용](https://github.com/kyopark2014/aws-iot-edukit/blob/main/edukit-platformio.md)에서는 M5Stack을 Visual Studio Code에 연결 후 Build, Upload, Monitoring 하는 방법을 설명하고 있습니다.



### 2) CLOUD CONNECTED BLINKY

Workshop sample중 하나인 [CLOUD CONNECTED BLINKY](https://edukit.workshop.aws/en/blinky-hello-world.html)에서는 M5stack을 IoT Core에 등록하는 script를 실행 할 수 있고, 이를 통해 연결이 되면 MQTT로 IoT Core에 메시지를 보낼 수 있습니다. IoT Core에서 blinky 명령을 실행하면 M5Stack의 LED를 제어 할 수 있습니다. 

[AWS Edukit(M5Stack) - Blinky](https://github.com/kyopark2014/aws-iot-edukit/blob/main/edukit-blinky.md)에서는 M5Stack을 IoT Core에 등록하는 script를 실행하고, M5Stack에 펌웨어 업그레이드를 진행하고, IoT Core에서 전송한 명령어로 Blinky 동작을 수행하는 과정을 설명합니다.

### 3) SMART THERMOSTAT


[AWS Edukit(M5Stack) - Thermostat](https://github.com/kyopark2014/aws-iot-edukit/blob/main/edukit-thermostat.md)에서는 IoT core에 인증서를 생성하고 이를 이용해 M5Stack을 연결한 후, Json으로 된 데이터를 수신하는 과정을 [SMART THERMOSTAT](https://edukit.workshop.aws/en/smart-thermostat.html)을 활용해 설명합니다. 
