![[Pasted image 20230918061020.png]]
외부에서 접근 못하게 할 수 있음.

외부에서 접근하려면 캡슐화 된 클래스 내부에 게터세터 메소드가 있으면 
외부에서 접근 가능.

- getter : 외부에서 변수의 데이터를 읽어올때 사용되는 메소드. ex) `public int getAge( ) { ... }`
- setter : 외부에서 변수에 데이터를 쓰고자 할 때  사용되는 메소드. ex) `public void setAge(int age) { ... }`

```start-multi-column
ID: ID_9y8g
Number of Columns: 2
Largest Column: standard
```

###### 작성
```java
public class Person {
	
	private int age;
	
	
	public int getAge() {
		return age;
	}
	
	public void setAge(int age) {
		if (age %3E= 0) {
			this.age = age;			
		}
	}
}
```

--- column-end ---

###### 실행
```java
public class HelloWorld {
	public static void main(String[] args) {

		Person p1 = new Person();
		
		p1.setAge(20);
		System.out.println(p1.getAge() + "살 입니다.");
	}
}

```

--- end-multi-column

```start-multi-column
ID: ID_qp7g
Number of Columns: 1
Largest Column: standard
```

###### 결과
```java

20살 입니다.

```


--- column-end ---



--- end-multi-column






