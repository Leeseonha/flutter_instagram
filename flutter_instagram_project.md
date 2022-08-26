# [Flutter] instagram Project





- ```
  최신 버전 추가
  터미널 > flutter pub add get
  ```





- 백 버튼에 대한 관리를 해줘야 하므로 WillPopScope 사용한다

- bottom_nav_controller.dart파일


  - 아래와 같은 코드를 명확하게 하기 위해 enum PageName을 사용한다

    ```
    if(value==0) {} 경우 home event
    if(value==1) {} 경우 search event
    * if로 구분하면 나중에 알아보기 힘드므로 명확하게 할 필요가 있다
    ```

- ​

