# SOPT_hw2
sopt 과제2 안드로이드파트_김기현

<기본 과제 1>
---------------
Bottom Navigation, ViewPager, RecyclerView 이용해서 직접 실습 해보기
</br>

실습한 결과물 사진
---------------
<div>
<img width="200" src="https://user-images.githubusercontent.com/59547069/81177190-3e11f800-8fe1-11ea-9447-d167cd67f674.png">
<img width="200" src="https://user-images.githubusercontent.com/59547069/81177199-40745200-8fe1-11ea-92f9-0884b61c2f9d.png">
<img width="200" src="https://user-images.githubusercontent.com/59547069/81177207-423e1580-8fe1-11ea-9754-6a93ade36438.png">
</div>
</br>

<div>
<img width="200" src="https://user-images.githubusercontent.com/59547069/81177220-466a3300-8fe1-11ea-809a-2390cd61f15e.png">
<img width="200" src="https://user-images.githubusercontent.com/59547069/81177229-48cc8d00-8fe1-11ea-96a5-87b2b8dc98a4.png">
</div>
</br>

<기본 과제 2>
---------------
RecyclerView의 itemDecoration, clipToPadding 에 대해 공부해보고 적용해보기
itemDecoration과 clipToPadding의 기능이 무엇인지 요약해서 업로드하기
</br>

* itemDecoration 이란?
---------------
RecyclerView 내부에 있는 추상클래스이다.
리사이클러뷰에서 아이템 여백을 주는 방법

<div>
<img width="200" src="https://user-images.githubusercontent.com/59547069/81188091-e202a000-8fef-11ea-927d-ab5b46392a9c.png">
<img width="200" src="https://user-images.githubusercontent.com/59547069/81188164-f777ca00-8fef-11ea-9620-ad8f84d8dbb0.png">
<img width="200" src="https://user-images.githubusercontent.com/59547069/81188199-fe064180-8fef-11ea-999c-86e82fda3b3a.png">
</div>
</br>

* clipToPadding 이란?
---------------
RecyclerView를 사용할 때 padding을 그냥 주면 스크롤 할 때 padding 공간만큼 위 아래가 가려지게 된다.
그래서 android:clipToPadding="false"로 해주면 스크롤 시 패딩을 스크롤 영역으로 활용할 수 있다.

-- android:clipToPadding="true"인 경우 --
 <div>
<img width="200" src="https://user-images.githubusercontent.com/59547069/81189076-1aef4480-8ff1-11ea-822e-a4870ce40ecd.png">
<img width="200" src="https://user-images.githubusercontent.com/59547069/81189081-1dea3500-8ff1-11ea-8c38-0ec2be18c5ba.png">
<img width="200" src="https://user-images.githubusercontent.com/59547069/81189088-1fb3f880-8ff1-11ea-8911-a1bb14c0c836.png">
</div>
</br>

-- android:clipToPadding="false"인 경우 --
<div>
<img width="200" src="https://user-images.githubusercontent.com/59547069/81189260-5b4ec280-8ff1-11ea-8c53-d8efd300d05d.png">
<img width="200" src="https://user-images.githubusercontent.com/59547069/81189271-5db11c80-8ff1-11ea-87cf-a300df47e077.png">
</div>
</br>

<성장 과제 1> ___ 업로드 예정
---------------
네이버 웹툰 뷰를 짜기 (힌트 : Grid 형태)
