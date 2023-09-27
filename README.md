# springtoy

아래에 관련된 백엔드 코드를 작성하였습니다
1.장바구니 목록보기
2.장바구니에 담기
3.장바구니에서 선택된 목록 삭제
4.주문하기
5.주문목록보기


실행방법
1. sql 데이터베이스에 테이블을 추가합니다.
     --시퀀스 생성
     Create sequence id_seq;
     --테이블 생성
      Create Table CART(id number() primary key,
                        productId number() foreign key,
                        name varchar2(),
                        price varchar2(),
                        quantity varchar2()) 
   
3. 아파치 톰캣으로 연결하였습니다.   
4. run on server로 메인 페이지를 엽니다. (to be added)
5. 상품 추가 버튼을 눌러 상품을 추가합니다. (to be added)
6. 장바구니에 넣기 버튼을 눌러서 장바구니로 넣습니다. (to be added)
7. 장바구니 보기 버튼을 눌러서 장바구니를 확인합니다. 
8. 주문하기 버튼을 눌러서 주문을 합니다.
9. 주문 목록버튼을 눌러서 주문 목록을 확인합니다. 
      


