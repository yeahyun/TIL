# TIL _#01 GIT / GITHUB

### 01. Git이란?

</br>

Git은 통상 **형상 관리 도구(Configuration Management Tool)** 중 하나이며, 쉽게 **버전 관리 시스템** 이라고 생각하면 된다. Git은 소스코드를 여러 개발 PC와 저장소에 분산하여 저장하기 때문에, 중앙 서버에 장애가 발생해도 로컬 저장소에 커밋을 할 수 있으며, 로컬 저장소들을 이용	하여 중앙 저장소의 복원도 가능하다. </br>

​	**1. 버전 관리**

​	 ![img](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F9ba4cac4-9990-492d-a573-c43f82aa30f4%2Fvc_explain.png?table=block&id=3a2201cd-3a1e-42b1-866c-3fee1baeac09&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=890&userId=&cache=v2)

​	지금까지 과제나 파일 수정이 있을때마다 우리는 이렇게 저장해 왔다. 하지만 **Git을 사용하면 하나의 파일로도 버전을 관리할 수 있게 된다.** </br>

</br>

​	**2. 작업 단위 나누기** 
​	프로그래밍을 하다보면 분명 아까는 되었는데, 지금 코드 고치니까 프로젝트가 동작을 안하는 순간이 있다. 		기능을 완성할 때마다 작업 내역을 저장	하면 어떤 부분을 만들 때 에러가 발생했는지 쉽게 파악할 수 있다.

</br>

</br>

​	**3. 협업해서 하나의 프로젝트를 진행할때 유용** 
​	프로젝트를 나누어서 작업하고 하나로 합치는 것이 편하다. 누가, 언제, 어떤 부분을 수정했는지 한 눈 에 파악할 수 있다. 

</br>

</br>

</br>

#### 02. Git은 왜 쓰나요?

</br>

여기서 생각해보자. '구글 드라이브' 같은 일반 공유 폴더를 이용하여 회사에서 팀프로젝트 작업을 진행했을때, 파일을 덮어쓰기 형태로 관리한다면, 다른 사람이 작업한 내용을 내 파일로 덮어써버리는 비극이 발생할 수 있다.

하지만 Git을 사용하면 같은 파일명의 내용이 어떤 부분이 다른지를 자동으로 비교하고, 어떤 것을 반영할지 선택할 수 있다.즉, 개발자 A와 B가 있다고 가정하였을때,A가 먼저 올린 파일에서B가 무엇인가를 수정하여 Git에 올렷을경우,Git에서 자동으로 B가 어떤 부분을 수정하였는지 비교해준다는 것이다.

```
-> Git으로 모든 파일의 내용이 자동으로 비교가 될까?

  기본 설정으로는 

    - 코드파일 (Python, HTML, JavaScript, Java, ...)
    - MarkDown파일 (text 파일의 일종)
    - CSV 파일
  
  등이 가능하다.
  이미지 파일, Word파일, PDF 파일ㄹ, 엑셀 파일은 여러가지 설정을 해주어야 가능하다.
```



</br>

</br>

</br>

<hr></hr>

</br>

</br>

</br>

#### 03. Github이란?

</br>

**Git**과 **Github**는 엄연히 다르다.

**Github은 Git 원격 저장소 + Git으로 할 수 있는 커뮤니티 기능 서비스이다.** 
Github은 Git으로 된 프로젝트 저장 공간을 제공하고, 편하게 사용하기 위한 여러가지 부가기능을 가지고있다. 쉽게말하면 개발자의 SNS와도 같다. </br>

​	**1. 인터넷으로 연결되어있는 프로젝트 저장소**

​		컴퓨터에 있는 내 Git 프로젝드를 저장 </br>

​	**2. 개발자들의 커뮤니티**

​		다른 개발자의 공개 프로젝트를 구경하고, 내가 관심있는 주제/ 프로젝트 소식을 볼 수 있다.

​		프로젝트를 함께 만드는데 참여하는 것 즉, ''프로젝트에 기여하기(contribution)' 하기 위한 여러 기능도 제공한다. </br> </br> </br>



#### 04. GIthub 왜 쓰나요?

</br>

간단하다.  앞서 말했듯이, 깃허브는 한 마디로 프로그래머들의 SNS. 그곳에 가면 많은 개발자들을 만날 수 있고, 다른 사람들이 어떤 일을 하는지,  어떤 프로젝트에 있어서 더 좋은 제안을 하거나 수정할 수 있다. 추가적으로 깃허브는 공동 작업을 가능케한다. 이 모든게 오픈 소스이기 때문에 가능한 일이다. </br> </br>

또한 어떻게보면 나의 개발일지 및 내가 만든 프로그램을 올려두어 포트폴리오에도 사용할 수 있다는 사실. 열심히 하자..!