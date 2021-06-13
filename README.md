# HTML_Project
소공 나만의 다이어리 프로젝트


<영상>

1.https://youtu.be/vS7n4_C-EXM


<준비물>

1.visual studio code

2.mongoDB

3.Robomongo    DB의 상황을 편리하게 보여주는 앱

<가상환경 안에서 쓸 라이브러리 설치 목록> <= cmd에 venv\Scripts\activate.bat 파일의 경로를 복붙해줘서 실행>
1.pip install flask

2.pip list

3.pip install flask-pymongo

4.pip install flake8



<가상환경 설치>

1.http://blog.naver.com/PostView.nhn?blogId=gracehappyworld&logNo=221490620526 를 따라해본다. 
파일명들만 myweb 등 영상과 동일하게 설정


<mongoDB 설치>
1) https://www.mongodb.com/try/download/community 에서 mongoDB community server 다운로드

2)

![2](https://user-images.githubusercontent.com/17828537/121804444-6870c300-cc81-11eb-9d81-582c5197bef3.png)


<robomongo 설치>
1)https://robomongo.org/download 

2)
 
![1](https://user-images.githubusercontent.com/17828537/121804438-63137880-cc81-11eb-8992-ad3f5d369d12.png)
 
3)

![3](https://user-images.githubusercontent.com/17828537/121804474-8dfdcc80-cc81-11eb-8ae6-6af41ca5300e.png)

4)

![4](https://user-images.githubusercontent.com/17828537/121804485-9bb35200-cc81-11eb-96d0-2546eb459619.png)



추가적으로
1)가상환경(여기서는 Python 디렉토리)과 동일 디렉토리 선상에 포스트에 저장된 이미지들과 업로드 파일들을 따로 저장해주는 디렉토리를 
만들어준다


![5](https://user-images.githubusercontent.com/17828537/121804529-c9989680-cc81-11eb-8dec-d5595a068c77.png)

![6](https://user-images.githubusercontent.com/17828537/121804531-cac9c380-cc81-11eb-8990-9ab2dfdbabbf.png)

![7](https://user-images.githubusercontent.com/17828537/121804584-0d8b9b80-cc82-11eb-8d52-3dbcb096d976.png)






<실행>
(venv) 들어간 상태에서 python run.py 타입 후 웹사이트에서 member/join 타입



<robomongo>
 1) 사진처럼 myweb 안의 collections 안에 보면 board 즉 올린 글들의 목록과 내용, members 즉 가입자들이 DB에 저장되어있는 것을 확인할 수 있다.
