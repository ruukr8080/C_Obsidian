# instance

객체보다 좀 더 구체화된 개념인데,

소프트웨어 안에서 **"객체"는 저장된 상태와 실행 가능한 코드로 구현**된다.

이 구현체를 우리는 "인스턴스"라고 표현한다.

인스턴스는 클래스에서 객체를 인스턴스화한 것이라고 말할 수 있다.

좀 더 구체적으로 말하면 new 연산자와 생성자를 통해서 객체를 구체화했다고 말할 수 있다.

>`객체는 인스턴스보다 더 포괄적인 단계이다.
>`런타임에 작동하는 객체를 인스턴스라고 말할 수 있다.
`   객체는 인스턴스의 묶음이라고 볼 수 있다.



---

  
```start-multi-column
ID: ID_fphy
Number of Columns: 2
Largest Column: standard
```

o 붕어빵 틀 = Class 
o 각각의 붕어빵 = Instance   
o 붕어빵 = Object
o 제작 = 인스턴스(Instance)화 하다
--- column-end ---



--- column-end ---

--- end-multi-column 
```java
public class 붕어빵틀 {

        // declarations
        private String source;    

        // Constructor

        public 붕어빵 (){
		//fields
                
                this.source = source;
        }

        // method

        public void 제작(){

                System.out.println(name + "붕어빵 완성 ");

        }

}

 

---------------------------- 만들어보자.java --------------------------------------

public class Main {  
  
public static void main(String[] args){  
  
// new 연산자로 불러옴  
  
  
  
FishTool sue = new FishTool();  
  
FishTool kimchi = new FishTool();  
  
FishTool curry = new FishTool();  
  
FishTool susi = new FishTool();

//슈크림맛,김치 맛, 카레 맛, 스시 맛 제작 가능.

        }

}
```



