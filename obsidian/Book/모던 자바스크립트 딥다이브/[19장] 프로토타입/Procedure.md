# 프로시저 (Procedure)
- 매개변수를 받아 여러 작업을 수행하여 값을 반환할 수 있다.


>데이터베이스에 대한 일련의 작업을 정리한 절차를 관계형 데이터베이스 관리 시스템에 저장한 것으로 영구저장모듈
>
>(Persistent Storage Module) 이라고도 불립니다.
>
 보통 저장 프로시저를 프로시저라고 부르며, 일련의 쿼리를 마치 하나의 [[function|함수]]처럼 실행하기 위한 쿼리의 집합입니다.
>
>즉, 특정 작업을 위한 쿼리들의 블록입니다.

---

# 함수와 프로시저의 차이




```start-multi-column
ID: ID_qr51
Number of Columns: 2
Largest Column: standard
```


[[function|함수]]

1.  여러 작업을 하기 위한 <font color="#eebbd8">*기능*</font>이고, 코드의 집합임
2. <font color="#c3d69b">매개변수</font> :매개변수를 입력 형식으로만 받을 수 있습니다.
3. <font color="#c3d69b">반환값</font> : 반환값을 반드시 가져야함.
4. <font color="#c3d69b">쿼리문 내에서 실행 불가능</font> : SELECT,WHERE 문 등에서 사용이 가능합니다.
5. <font color="#c3d69b">처리 장소</font> : 클라이언트(화면)에서 값을 건네 받고 서버에서 필요한 값을 가져와서 클라이언트에서 작업을 하고 반환합니다.

즉, 클라이언트(화면)에서 실행이 되어 프로시저보단 속도가 느립니다.


--- column-end ---

[[Procedure| 프로시저]]

1. 일련의 작업을 정리한 <font color="#eebbd8">*절차*</font>임.
2. <font color="#c3d69b">매개변수</font> : 매개변수를 입력,출력,입출력 형식으로 받을 수 있습니다.
3. <font color="#c3d69b">반환값</font> : 반환값을 가지지 않을 수도 있음.
4. <font color="#c3d69b">쿼리문 내에서 실행 가능</font> : SELECT,WHERE 문 등에서 사용 불가합니다.
5. <font color="#c3d69b">처리 장소</font> : 클라이언트(화면)에서 값을 건네받아 서버에서 작업을 한 뒤 클라이언트에게 전달합니다.

즉, 서버에서 실행이 되어 속도면에서 빠른 성능을 보여줍니다.


--- end-multi-column

