# sparta_clonepage
HTML과 CSS로 간단히 만든 신년운세 웹페이지

URL : https://new-year.spartacodingclub.kr/CxBoeNEQrH22/index.html
  
간단한 페이지이기 때문에 **Internal Style Sheet** 로 css를 적용하였습니다.
  
## index.html
![main](https://user-images.githubusercontent.com/79749251/146311493-f5858722-5fb4-4053-989f-40b3b09fd1b3.png)  
  
**flex**를 사용하여 요소들을 정렬하였고, 마우스를 올리면 이름이 나타나고 배경색이 바뀌도록 하였습니다.  
background-image에 a 태그를 걸어 image 클릭 시 적용 url로 이동하도록 하였습니다.

## result.html
![result](https://user-images.githubusercontent.com/79749251/146311341-b007c4d2-1604-41de-bb6b-6cdfc6e0f8c8.png)  
  
뒤로 가기 버튼을 누르면 back 함수가 실행되어 index.html 로 돌아갑니다.  
<hr/>

![share](https://user-images.githubusercontent.com/79749251/146313801-4b93e858-47ed-4df4-a186-9047627e1778.png)  

공유하기 버튼을 누르면 share 함수가 실행되어 해당 페이지의 url이 자동으로 복사되고, 입력창에 붙여넣기를 하면 복사되었던 url이 나타납니다.  
 
 ## 반응형 웹페이지 (response webpage)
  ![mobile1](https://user-images.githubusercontent.com/79749251/146314466-1fa64d72-386c-497d-a347-d9f00d76951d.png)  
  
화면의 가로값이 780px 보다 작아지면 요소들의 배치가 세로로 정렬되고 스크롤로 이동할 수 있습니다.  

<hr/>

![mobile2](https://user-images.githubusercontent.com/79749251/146315212-fbe43aaf-697c-41c0-9227-28971b77bf82.png)

result.html 역시 화면의 가로값이 708px보다 작아지면 요소들이 화면에 맞춰 가운데 정렬합니다.
