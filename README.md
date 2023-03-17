# PhyscData
Java PhyscData<br>
## 클래스
클래스는 임의의 데이터형을 자유로의 조합하여 만들 수 있는 자료 구조이다.<br><br>
어늘 그룹의 신제검사 데이터를 처리하는 것을 예로 들면, 데이터가 이름/키/시력의 3개라면<br>
각각의 항목에 대해 벼열을 구성한다. name[0]의 "홍길동" 키는 height[0]에 저장되고 시력은<br>
vision[0]에 저장 될 것. 그러나 각 개인의 데이터가 같은 인덱스에 저장되는 관계가 프로그램에<br>
직접 나타나지는 않는다. 실제 업무에서는 보통 개인별 카드에 시력과 키 등의 데이터를 적어 놓고,<br>
이 카드를 사람 수 만큼 준비한다. 프로그램에서도 이와 같이 구현하는 것이 좋다.<br>
## 클래스 활용 프로그램
신체검사 데이터의 알람표를 나타내고 평균 키와 시력의 분포를 나타냄.<br><br>
![image](https://user-images.githubusercontent.com/126844692/225786297-71e4661e-3ed2-4ad1-819a-8bd09417ee10.png)<br>
## 설명
사용자의 이름, 키, 몸무게, 좌우시력, 혈액형, 혈액형을 입력받아 입력받은 모든 정보를 출력하고<br>
표준체중을 구해서 표준체중과 실제 몸무게에 따라 적합한 메세지를 출력하고,<br>
또, 좌우시력에 따라 0.6이하이면 안경이나 렌즈를 착용하도록 적합한 메세지를 출력합니다.<br>
클래스명, 변수등은 자유롭게 합니다.<br><br>

### 1) 시력 분포(0.0에서 0.1단위로 21개)
![image](https://user-images.githubusercontent.com/126844692/225800857-06ee505c-b27a-44b8-8f0d-ecafa8f46037.png)<br>

### 2) 이름, 키, 시력
![image](https://user-images.githubusercontent.com/126844692/225800649-2d391994-fd43-49c5-b3b9-f458ed4dc473.png)<br>

### 3) 생성자
![image](https://user-images.githubusercontent.com/126844692/225800477-c481b6e3-649e-46ce-9e79-cdde4e7a625b.png)<br>

### 4) 키의 평균값 구하기
![image](https://user-images.githubusercontent.com/126844692/225800977-1d3b71e6-d629-43fc-a141-b5c862957598.png)<br>

### 5-1) 시력 분포 구하기
![image](https://user-images.githubusercontent.com/126844692/225801099-50fcd2ef-6a5d-44f0-8b22-4ea706ce9afd.png)<br>

### 5-2) 시력 분포 구하기
![image](https://user-images.githubusercontent.com/126844692/225801299-2a316733-e577-4e9b-af5f-74d07fde3c0b.png)<br>

## 결과
![image](https://user-images.githubusercontent.com/126844692/225802384-08eb7817-a657-4a6d-87a3-b863758eb914.png)<br>

## 클래스 본체와 멤버
1. 클래스 본체에서는 다음과 같은 내용을 선언할 수 있다.<br><br>

- 멤버(필드/메서드/중첩(nested)클래스/중첩(ensted)인터페이스<br>
- 클래스 초기화/ 인스턴스 초기화<br>
- 생성자<br>
2. 필드/메서드/생성자를 선언할 때 public/protected/private을 지정할 수 있다.<br>
3. 메서드/생성자는 다중으로 정의(오버로드)할 수 있다.<br>
4. final로 선언한 필드는 한 번만 값을 대입할 수 있다.<br>
5. 생성자는 새로 생성한 인스턴스의 초기화를 위해 사용된다.<br>
