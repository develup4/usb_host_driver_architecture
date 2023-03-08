# usb_host_driver_architecture
<img width="1177" alt="image" src="https://user-images.githubusercontent.com/8960704/223727563-9868bb3f-f562-448a-823d-c3a2ead368c1.png">

## 기본적인 기능
- USB 디바이스의 연결을 관리한다.
- USB 디바이스의 제어 및 데이터 전송을 관리한다.
- USB 디바이스의 전원을 관리한다.
- Mass Storage Class

<img width="1190" alt="image" src="https://user-images.githubusercontent.com/8960704/223727820-33afdcd2-5b06-4398-a19e-2bc85fc8347a.png">

## 참고 URL
https://www.usb.org/defined-class-codes

## 품질 요구사항
### 성능
- 디바이스의 연결, 제어 등의 성능이 빠를 수록 좋다.
### 변경 용이성 / 확장성
- 하드웨어 사양의 변경이 용이할 수록 좋다.
- 다양한 클래스로의 확장이 용이할 수록 좋다.

## 과제 환경에 대한 설정
- 어떤 기능 및 품질 측면에서 장점이 있는지 등 시스템의 동작 및 사업 환경은 각자 설정한다.
- 솔루션이 최적화된 것을 판단할 수 있는 품질 시나리오가 검토되어야 한다.
- 제약 사항의 변경에 대해서도 검토되어야 한다.

## 최종 산출물
https://github.com/develup4/usb_host_driver_architecture/blob/master/usb_host_driver_architecture_final.pdf

## 디렉토리 구조
### document
도메인 지식에 대한 정리, 후보 구조에 대한 엑셀 파일, 전체 클래스 다이어그램(StarUML)이 있습니다.
### requirement
요구사항에 대한 문서가 있습니다.
### sequence
시퀀스 다이어그램을 위한 메타 파일들이 있습니다.

## License
GPL license
