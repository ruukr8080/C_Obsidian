# [[클래스 기반 OOP|클래스 기반 OOP ex]] 


###### 클래스 정의
 Person 클래스를 정의합니다. Person 클래스는 name과 age라는 두 개의 속성과 talk()라는 하나의 메서드를 가지고 있습니다. name 속성은 사람의 이름을 나타내고, age 속성은 사람의 나이를 나타냅니다. talk() 메서드는 사람이 말하는 행위를 나타냅니다.
```JavaScript
class Person {
  name: string;
  age: number;

  constructor(name: string, age: number) {
    this.name = name;
    this.age = age;
  }

  talk() {
    console.log(`안녕하세요. 저는 ${this.name}입니다.`);
  }
}

```

###### 객체 생성

>`이 코드는 Person 클래스에 따라 홍길동이라는 이름과 30세인 사람 객체를 생성합니다.`
```JavaScript
const person = new Person("홍길동", 30);

```

######  객체의 속성 사용
>`person 객체의 name 속성과 age 속성을 출력
```js
console.log(person.name); // 홍길동
console.log(person.age); // 30


```

###### 객체의 메서드 사용
>` `person` 객체의 `talk()` 메서드를 호출
```js
person.talk();

```


