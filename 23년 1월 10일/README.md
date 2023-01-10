# 오늘 한것

1. 클론 코딩

2. transform에 대해 공부

pytorch에서 transform이란 데이터를 텐서 형태로 바꾸어 준다고 생각하면 편하다.

3.  torch.utils.data.DataLoader, torch.utils.data.Dataset
이건 내장 데이터를 가지고 오는 코드임

4. 파이토치에서 데이터를 불러오는 함수
dataiter = iter(trainloader) # 이렇게 정의해 두고(즉 데이터를 가져오는 방법을 정의)
images, labels = next(dataiter) # 를 실행하면 다음 batch가 나옴

즉 iter 함수로 새로운 객체를 만들고, next함수로 불러온다.

5. conv2d
2d는 이미지, 영상에 쓰이고, 1d는 text에 쓰인다.

6. maxpooling
![image](https://user-images.githubusercontent.com/95357946/211567206-1d5d9be3-0001-4802-b4c0-b984fe3069b7.png)
1,1,5,6에서 가장 큰수인 6을 가지고 오는 것.

pooling은 

1. Max Pooling : 정해진 크기 안에서 가장 큰 값만 뽑아낸다.
2. Average Pooling : 정해진 크기 안의 값들의 평균을 뽑아낸다.

# loss.backward() 
학습에서 역전파를 구현하는 방법
