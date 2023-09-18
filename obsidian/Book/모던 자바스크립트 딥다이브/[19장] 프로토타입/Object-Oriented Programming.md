# 객체지향 프로그래밍
## [[Object-Oriented Programming|객체란]]
내 눈 앞에 있는 <u>모니터, 책상, 시계, 핸드폰</u>과 같은 유형의 사물부터
눈에 보이지 않는<u> 어떤 논리, 사상, 철학, 개념, 공식,기분 </u>등과 같은 무형의 대상들까지 
<span style="background:#d3f8b6">우리가 보고 느끼고 인지할 수 있는 그 모든 것이 객체다.</span>

프로그래밍에서 발생하는 모든 사건과 현상을 객체들 간의 상호작용을 통해 프로젝트를 완성하는게 객체지향 프로그래밍이다 .

---



```start-multi-column
ID: ID_47ds
Number of Columns: 2
Largest Column: standard
```

### 특징이자 장점

--- column-end ---

#### [[Abstration | 추상화 한다.]]
>현실 세계의 사물이나 개념을 객체로 추상화하여 복잡한 문제를 단순화할 수 있다.
---
#### [[inheritance|상속]] 가능
>상위 객체의 속성과 기능을 하위 객체가 상속받을 수 있다.  
---
#### [[다형성]]
>  하나의 객체가 여러 가지 타입을 가질 수 있는 것
---
#### [[Encapsulation | 캡슐화]]
>객체의 내부 구현을 외부에서 숨겨 객체의 안정성 향상시킴.

--- end-multi-column

```start-multi-column
ID: ID_dytf
Number of Columns: 2
Largest Column: standard
```

### 기본 구성 요소

--- column-end ---

#### 클래스
>  객체를 생성하기 위한 일종의 설계도

#### [[Object-Oriented Programming|객체]]
> 클래스의 [[instance|인스턴스]]

#### 메서드, [[message ofprogramming|메시지]]
> 클래스로부터 생성된 객체를 사용하는 방법으로서 객체에 명령을 내리는 메시지라 할 수 있다



--- end-multi-column


---

# 객체 지향 언어의 역사
# [[객체지향 언어의 시초]]
## Simula 시뮬라
객체 지향 언어의 시초는 1960s에 개발된 [[Simula|Simula67]]이다. 
시뮬라67이 채택하고 있는 가장 중요한 개념은 [[Class|Class]]의 도입으로서 이 아이디어는 [스몰토크](https://ko.wikipedia.org/wiki/%EC%8A%A4%EB%AA%B0%ED%86%A0%ED%81%AC "스몰토크"), C++ 등에도 사용되었다. 하지만 시뮬라 67의 발표 이후 10여년 간 객체 지향 언어는 전혀 주목을 받지 못하였다. 1970년대 컴퓨터 산업을 주도한 IBM, AT&T, 미 국방성 등에서 관심을 두지 않았기 때문에 시뮬라 67은 실용적인 언어로 발전하지는 못하였다. 하지만 이의 학문적 가치는 인정받고 있다.

---
# [[객체지향 언어의 실질적 조상]]
## Smaltalk 스몰토크

객체 지향 언어로서의 실질적 원조는 제록스 기업의 [팰러앨토](https://ko.wikipedia.org/wiki/%ED%8C%B0%EB%9F%AC%EC%95%A8%ED%86%A0 "팰러앨토") 연구소에서 [앨런 케이](https://ko.wikipedia.org/wiki/%EC%95%A8%EB%9F%B0_%EC%BC%80%EC%9D%B4 "앨런 케이")의 책임 하에 만들어진 [스몰토크](https://ko.wikipedia.org/wiki/%EC%8A%A4%EB%AA%B0%ED%86%A0%ED%81%AC "스몰토크")이다. 이 언어 역시 아이디어는 시뮬라 67에서 얻어왔지만 **<font color='FF50BE'>가장 순수한 객체 지향 언어로 만들어졌으며 현재에도 인정받고 있다</font>**. 미국에서 많은 사용자들을 확보하고 있다. 1970년대 말 스몰토크가 만들어질 당시 제록스에서는 3가지 가정을 하고 이 가정에 초점을 맞추어 스몰토크의 문법과 의미를 정의하였다. 첫 번째는 전 세계의 모든 사람이 [컴퓨터](https://ko.wikipedia.org/wiki/%EC%BB%B4%ED%93%A8%ED%84%B0 "컴퓨터")를 사용할 것이라는 가정이었고, 두 번째는 모든 사용자가 [그래픽](https://ko.wikipedia.org/wiki/%EA%B7%B8%EB%9E%98%ED%94%BD "그래픽")이 지원되는 [모니터](https://ko.wikipedia.org/wiki/%EB%AA%A8%EB%8B%88%ED%84%B0 "모니터")와 [마우스](https://ko.wikipedia.org/wiki/%EB%A7%88%EC%9A%B0%EC%8A%A4 "마우스")를 기본 설비로 사용하며 윈도 환경에서 작업할 것이라는 가정이었다. 마지막으로 모든 사람이 각자의 [응용 프로그램](https://ko.wikipedia.org/wiki/%EC%9D%91%EC%9A%A9_%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8 "응용 프로그램")을 쉽게 개발할 수 있어야 한다는 것이었다. 첫 번째와 두 번째 가정은 현실에서 거의 사실화되었으나 마지막 가정은 제록스의 실수였다. 현재 많은 컴퓨터 사용자들은 그들의 응용 프로그램을 스스로 개발하지 않는다. 이러한 점 때문에 스몰토크의 순수성과 독창성에 비하여 크게 성공하진 못하였다.

# [[ 미국 국방부에서 인정 된 객체지향 언어]]
## Ada 에이다
에이다는 1980년대 초 객체 지향 프로그래밍 언어로 미 국방성에서 개발한 것이다. 미 국방성은 에이다 개발 전까지 [코볼](https://ko.wikipedia.org/wiki/%EC%BD%94%EB%B3%BC "코볼")과 [포트란](https://ko.wikipedia.org/wiki/%ED%8F%AC%ED%8A%B8%EB%9E%80 "포트란")을 이용하여 [시스템](https://ko.wikipedia.org/wiki/%EC%8B%9C%EC%8A%A4%ED%85%9C "시스템")을 개발하였는데 프로젝트 규모가 점점 커져 가면서 그것의 유지와 보수 비용의 문제가 따랐다. 이 문제를 해결하기 위하여 코볼과 포트란의 환경의 개발을 시도하였으나, 한계를 느끼고 새로운 언어를 도입하게 된다. 미 국방성은 새로운 언어에 대한 정의를 공모하였으며, 여러 업체들이 제시한 언어들을 기준으로 에이다를 정의하였다. 그 당시에는 [파스칼](https://ko.wikipedia.org/wiki/%ED%8C%8C%EC%8A%A4%EC%B9%BC_(%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D_%EC%96%B8%EC%96%B4) "파스칼 (프로그래밍 언어)")이 인기가 좋아서 에이다의 문법은 기본적으로 파스칼의 문법을 기반으로 하였다.

에이다의 <font color="#eebbd8">큰 특징은 예외 처리 기능의 도입</font>이다. 이는 시스템의 신뢰도를 높이기 위한 중요한 기능이며, 미 국방성 프로젝트가 중요시 하는 신뢰도를 증가시키기 위한 필수적인 기능으로 볼 수 있다. 하지만 에이다는 큰 단점을 가지고 있었는데, [상속](https://ko.wikipedia.org/wiki/%EC%83%81%EC%86%8D_(%EA%B0%9D%EC%B2%B4_%EC%A7%80%ED%96%A5_%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D) "상속 (객체 지향 프로그래밍)")의 개념을 언어에 반영하지 않았다. 또한 대부분의 객체 지향 언어가 대부분 [동적 바인딩](https://ko.wikipedia.org/w/index.php?title=%EB%8F%99%EC%A0%81_%EB%B0%94%EC%9D%B8%EB%94%A9&action=edit&redlink=1 "동적 바인딩 (없는 문서)") 방식을 채택하고 있는 반면에 에이다는 [정적 바인딩](https://ko.wikipedia.org/w/index.php?title=%EC%A0%95%EC%A0%81_%EB%B0%94%EC%9D%B8%EB%94%A9&action=edit&redlink=1 "정적 바인딩 (없는 문서)")방식을 사용하고 있었다.

---

# [[현재까지의 객체지향 대표]] 
## JAVA

Java 는 썬 마이크로시스템즈의 제임스 고슬링(James Gosling)과 다른 연구원들이 개발한 객체 지향적 프로그래밍 언어이다. 1991년 그린 프로젝트(Green Project)라는 이름으로 시작해 1995년에 발표했다. 처음에는 가전제품 내에 탑재해 동작하는 프로그램을 위해 개발되었지만 현재 웹 애플리케이션 분야에 가장 많이 사용하는 언어 중 하나이고, 안드로이드를 비롯한 모바일 기기용 소프트웨어 개발에도 널리 사용되고 있다. 현재 버전 20까지 출시했다.

자바의 개발자들은 유닉스 기반의 배경을 가지고 있었기 때문에 문법적인 특성은 파스칼이 아닌 C++의 조상인 C 언어와 비슷하다. 자바를 다른 컴파일언어와 구분 짓는 가장 큰 특징은 컴파일된 코드가 플랫폼 독립적이라는 점이다. 자바 컴파일러는 자바 언어로 작성된 프로그램을 바이트코드라는 특수한 바이너리 형태로 변환한다. 바이트코드를 실행하기 위해서는 JVM(자바 가상 머신, Java Virtual Machine)이라는 특수한 가상 머신이 필요한데, 이 가상 머신은 자바 바이트코드를 어느 플랫폼에서나 동일한 형태로 실행시킨다. 때문에 자바로 개발된 프로그램은 CPU나 운영 체제의 종류에 관계없이 JVM을 설치할 수 있는 시스템에서는 어디서나 실행할 수 있으며, 이 점이 웹 애플리케이션의 특성과 맞아떨어져 폭발적인 인기를 끌게 되었다.](<1990년대 중반 이후로 각광받고 있는 객체 지향 언어는 [자바](https://ko.wikipedia.org/wiki/%EC%9E%90%EB%B0%94_(%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D_%EC%96%B8%EC%96%B4) "자바 (프로그래밍 언어)")로 가전 제품에 사용될 [소프트웨어](https://ko.wikipedia.org/wiki/%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4 "소프트웨어")의 개발 목적으로 [썬 마이크로시스템즈](https://ko.wikipedia.org/wiki/%EC%8D%AC_%EB%A7%88%EC%9D%B4%ED%81%AC%EB%A1%9C%EC%8B%9C%EC%8A%A4%ED%85%9C%EC%A6%88 "썬 마이크로시스템즈")의 [제임스 고슬링](https://ko.wikipedia.org/wiki/%EC%A0%9C%EC%9E%84%EC%8A%A4_%EA%B3%A0%EC%8A%AC%EB%A7%81 "제임스 고슬링")에 의하여 고안된 언어이다. 1993년 고슬링은 [월드 와이드 웹](https://ko.wikipedia.org/wiki/%EC%9B%94%EB%93%9C_%EC%99%80%EC%9D%B4%EB%93%9C_%EC%9B%B9 "월드 와이드 웹")에 자바 언어를 적용할 것을 결정하면서 [핫자바](https://ko.wikipedia.org/wiki/%ED%95%AB%EC%9E%90%EB%B0%94 "핫자바")라는 [웹 브라우저](https://ko.wikipedia.org/wiki/%EC%9B%B9_%EB%B8%8C%EB%9D%BC%EC%9A%B0%EC%A0%80 "웹 브라우저")를 개발하였고, 이는 1995년 이후 [넷스케이프사](https://ko.wikipedia.org/wiki/%EB%84%B7%EC%8A%A4%EC%BC%80%EC%9D%B4%ED%94%84%EC%82%AC "넷스케이프사") 쪽에서 지원을 받게 되었다. 자바 언어의 장점은 언어의 단순성과 [플랫폼](https://ko.wikipedia.org/wiki/%ED%94%8C%EB%9E%AB%ED%8F%BC "플랫폼") 독립성이다. 특히 언어의 단순성 입장에서 객체 지향 패러다임에 충실하게 언어가 고안되었기 때문에 C++보다 오용의 소지가 다소 적다.>)