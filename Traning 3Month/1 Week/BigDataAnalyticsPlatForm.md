# ICT폴리텍대학 빅데이터 UI 훈련 과정

## 21-07-08

## 빅데이터 분석 프로세스의 개념

빅데이터 분석의 주요 목적은 웹 서버 로그, 인터넷 클릭 정보, 소셜 미디어 활동 보고서, 이동전화 통화 기록 그리고 센서들이 감지한 정보 등 새로운 종류의 데이터(Data Source)나 많은 양의 트랜잭션 데이터(Transation Data)를 분석할 수 있도록 하여 기업이 경영과 관련하여 더 좋은 의사결정을 하도록 도와주는 것이다. 빅데이터를 분석하여 의미있는  지식을 찾기 위해서는 여러 단계를 포함하는 순환 과정을 거치게 된다. 빅데이터 수집, 저장 관리, 처리와 분석 및 지식 시각화, 이용, 폐기 등을 통한 여러 단계를 거치고 있다.
+ 트랜잭션 : 하나의 논리적 단위를 구성하는 데이터베이스 연산의 모임


![bigdata_processing](https://user-images.githubusercontent.com/76871728/124844348-00d33c80-dfcf-11eb-8284-c675bb80c04c.jpg)

출처 : ADAM의 네이버 블로그, https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=simadam222&logNo=221290114513

## 빅데이터 플랫폼(Big Data Analytics PlatForm)

다양한 데이터 소스에서 수집한 데이터를 분석 처리하여 지식을 추출하고, 이를 기반으로 지능화된 서비스를 제공하는데 필요한 ICT환경을 빅데이터 플랫폼이라 한다. 빅데이터 플랫폼이 빅데이터 처리에 필요한 전체의 순환 과정을 수행하기 위해서는 확정성있는 대용량 처리 능력, 이기종(서로 다른 두개의 종류) 데이터 수집 및 통합 처리 능력, 빠른 데이터 접근 및 처리 능력, 대량의 데이터를 저장 관리할 수 있는 능력, 대량의 이기종 데이터를 원하는 수준으로 분석할 수 있는 능력등을 갖춰야 한다. 다양한 데이터 소스로부터 데이터 수집, 저장관리, 처리와 분석 및 지식 시각화를 통해 지식을 이용하기까지 각 단계를 지원하는데 필요한 공통 소프트웨어를 빅데이터 플랫폼이라고 한다.

![slide_5](https://user-images.githubusercontent.com/76871728/124844984-af2bb180-dfd0-11eb-85a9-aa805eb361ae.jpg)

빅데이터 플랫폼은 데이터를 수집해서 지식을 발굴하는데 필요한 빅데이터 처리 플랫폼 기술과 대용량의 고속 저장 공간 및 고성능의 계산 능력을 갖춘 컴퓨터 등 컴퓨터 기반을 제공하는 빅데이터 컴퓨팅 인프라 기술로 구성된다.

## 데이터 관리 개념과 유형

### 데이터 관리 개념

데이터란 숫자, 영상, 단어 형태의 단위를 말한다. Datum(데이터의 단수)이 여러 개 모여 데이터를 형성하면 자료가 되며 다양한 자료가 의미있는 가치를 형성하면 정보가 된다.데이터베이스는 데이터의 효율적이고 통합적인 저장을 가르키는 용어이다. 서로 유관한 데이터를 효율적으로 관리하기 위해 수집한 데이터의 집합체이며, 각 데이터는 상호 유기적 관계에 의해 구성되어 있다.데이터 관리는 파일 관리에서부터 편리성을 모도하는 데이터베이스로 반전되어 왔고 여러가지 진화하는 과정을 거쳐 왔다.

#### 파일 시스템

컴퓨터 파일에 이름을 붙이고, 저장 및 검색을 위해 논리적으로 그것들을 어디에 위치시켜야 하는지 등을 나타내는 방법이다. 파일의 실제 데이터와 메타 데이터(파일의 위치, 크기, 소유자, 허가권 등)를 유지와 저장하는 체계이다. 도스, 윈도우, OS/2, 매킨토시 및 유닉스 기반의 운영 체계들은 모두 파일이 계층적인 구조로 위치하는 파일 시스템에 해당된다. 파일은 계층 구조 내의 바른 위치인 디렉터리 또는 서브디렉터리 내에 놓여진다. 파일 시스템들은 파일의 이름을 붙이는 규칙을 가지고 있다. 예를 들어 윈도우의 FAT16, FAT32, NTFS, 리눅스의 ext2, raiserFS, ext3 등이 있다.

#### 데이터베이스

한 조직의 응용 시스템들을 공용(Shared)하기 위해 통합(Integrated), 저장(Stored)한 운영(Operational) 데이터의 집합이다. 데이터베이스를 관리하기 위한 시스템인 DBMS(Data Base Management System)가 탄생하였다. 데이터베이스의 특징은 여러가지가 있다.

1. 실시간 접근성(real time accessibility) : 사용자의 질의에 대하여 즉시 처리하여 응답한다.
2. 계속적인 진화(continuous evolution) : 삽입, 삭제, 갱신을 통하여 항상 최근의 정확한 데이터를 동적으로 유지한다.
3. 동시 공유(concurrent sharing) : 여러 사용자가 동시에 원하는 데이터를 공유할 수 있는 특징을 갖는다.
4. 내용에 의한 참조(content reference) : 데이터베이스에 있는 데이터를 참조할 때 투플(tuple)의 주소나 위치가 아닌 사용자가 요구하는 데이터 내용에 따라 참조한다.
5. 데이터 논리적 독립성(independence) : 응용프로그램과 데이터베이스를 독립시킴으로써 데이터 논리적 구조를 변경시키더라도 응용프로그램은 변경되지 않는다.

#### DBMS(Data Base Management System

DBMS란, 다수의 사용자들이 데이터베이스 내의 데이터를 접근할 수 있도록 해주는 소프트웨어 도구를 의미한다. 

DBMS의 기능은
1. 정의 : DBMS는 사용자에 필요한 데이터의 형식, 구조, 제약조건들을 정의한다.
2. 구축 : DBMS가 관리하는 기억 장치에 데이터를 저장하는 기능이다.
3. 조작 : DBMS는 DB에 저장된 데이터에 접근하여 사용할 수 있는 기능을 제공한다. 즉, 사용자 요구에 따라 데이터를 삽입, 삭제, 수정, 검색하는 연산을 효율적으로 처리한다.
4. 공유 : 여러 사용자가 데이터베이스에 동시에 접근하게 한다.
5. 제어 : DBMS는 데이터를 여러 사용자가 공유해도 항상 정확하고 안전하게 유지하는 기능을 제공한다. 데이터를 조작하는 연산을 한 후에도 내용이 일관되면서 무결성을 유지하게 하고, 장애가 발생해도 회복이 가능하도록 제어한다. 그리고 권한이 있는 사용자에게만 데이터 접근을 허용하여 보안을 유지하도록 제어한다.
6. 유지보수 : 변화하는 요구사항을 반영할 수 있도록 한다.

DBMS의 특징은
1. 데이터의 독립성
 + 물리적 : 데이터베이스 사이즈를 늘리거나 파일을 늘리더라도 관련된 응용 프로그램을 수정이 불필요하다.
 + 논리적 : 데이터베이스는 논리적 구조를 가지므로 응용프로그램의 논리적 요구를 만족시킬 수 있다.
2.  데이터의 무결성
어느 경로에 잘못된 데이터가 발생하는 경우의 수를 방지한다.
3. 데이터의 보안성
허가된 사용자만 데이베이스 내의 데이터를 접근할 수 있도록 계정관리나 권한을 설정함으로써 모든 데이터에 보안을 구현할 수 있다.
4. 데이터의 일관성
연관된정보를 논리적구조로 관리함을써 작업중에 하나의 데이터만 변경한 경우 나머지 데이터와 일치하지 않은 경우의 수를 배제할 수 있다.
5. 데이터 중복의 최소화 
데이터를 통합해서 관리함으로 자료의 중복성과 데이터의 종속성을 해결할 수 있다.

DBMS의 종류는
1. 계층 DBMS : 데이터 간의 관계가 트리 형태의 구조이다. 트리는 부모-자식 관계로 표현되며 부모와 자식 간에는 1:다수로 구성될 수 있다. 구조가 간단하고 구현, 수정, 검색이 쉽지만 부모 자식 간에 다수:다수 관계 처리가 불가능하고, 구조 변경이 어렵다.
2. 네트워크 DBMS: 계층 DBMS의 단점인 다수:다수 관계 처리를 가능하게 하는 그물 형 구조이다. 하짐나 구조가 복잡하다는 단점이 있어서 구조를 변경할 때 많은 어려움이 따른다.
3. 관계 DBMS : 데이터들을 행(row)과 열(Column)로 구성된 테이블 구조로 단순화 시킨 모델이다. SQL(Structured Query Language)를 사용하여 테이터를 관리 및 처리하는데 유용하지만, 비정형 데이터들을 다루거나 실시간 분석에는 적합하지 않다.
4. NoSQL : Not only SQL이라는 뜻으로 SQL뿐만 아니라 다양한 특성을 지원한다는 의미이다. 데이터 간의 관계를 정의하지 않는 모델이다. 관계 DBMS의 복잡도와 용량의 한계를 극복하기 위한 목적으로 만들어졌다. 비정형 데이터 처리에 유리하지만 스키마 변경이 불가능해 데이터값에 문제가 발생하면 감지가 어렵다.

### 데이터 관리 유형

전통적인 정보 시스템에서 데이터 관리는 각 응용 프로그램 또는 응용 시스템(Applications)별로 수행되었다. 전통적인 방법에서부터 데이터 관리의 방법이 어떻게 이루어져 왔는지 나열해 본다.

#### 수작업 처리 시스템(Manual Data Processing System)

컴퓨터가 등장하기 전에도 정보 처리 시스템은 존재하였다. 거래에 기록된 내역을 장부에 기록하여 보관하는 것이 컴퓨터에서는 파일로 저장하는 것과 같다. 수작업 처리 시스템은 정확성이 떨어지며 신속하지 않고, 자료당 처리 비용이 많이 드는 단점이 있다.

#### 파일 처리 시스템

기업의 단위업무(급여관리, 재고관리, 구매관리 등)를 처리하는 응용 시스템별로 데이터 관리를 독립적으로 수행하는 전산자료 처리 시스템을 파일 시스템이라고 한다. 파일 시스템에서는 전사적인 정보 시스템 계획이나 모델이 존재하지 않는다. 파일의 정보를 타부서와 **공유가 가능하지 않았고, 파일을 따로 구축해서 중복이 발생**하였으며, 정보의 품질이 떨어지고 처리 비용이 증가한다라는 단점이 있다. 즉, 파일 시스템은 부서 간의 정보를 통합적으로 요구하는 **관리자의 요구 사항에 대응하지 못하는 구조적 결함**을 가지고 있다.

#### 데이터베이스 시스템

데이터베이스는 파일 시스템의 단점을 보완해서 나온 시스템이다. 단일 사용자가 데이터베이스를 만들고 수정, 유지, 보수하며, 설계와 보고서 작성을 직접하고 PC 서버에 데이터베이스 시스템을 구성해 놓고 다수의 사용자와 데이터베이스를 공유하는 형태의 개인용 PC 데이터베이스, 다수의 사용자의 컴퓨터(Client)가 네트워크로 연결되어 데이터베이스 서버에 있는 데이터베이스 정보를 공유하는 형태의 클라이언트/서버형(C/S)데이터베이스, 여러 지역에 컴퓨터가 분산되어 있으며 각각의 데이터베이스를 논리적으로 하나의 데이터베이스로 통합하는 분산형 데이터베이스가 포함된다.기업의 의사결정에 필요한 모든 데이터를 과거의 데이터까지 포함하여 축적한 대용량의 정보 저장소인 데이터웨어하우스(Data Warehouse), 단일 주제별 또는 지역별, 단일 부서 또는 사용자 집단 등 의사결정 그룹별로 구축되는 데이터 마트(Data Mart)도 **넒은 의미에서는 데이터베이스에 포함**된다.
