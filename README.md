# 3S-CTF

![img](https://github.com/user-attachments/assets/497ffaee-d2c7-45aa-a362-ff6314352196)



![img](https://github.com/user-attachments/assets/dbcbb452-02fa-4799-a41e-c0b0f76351b8)




![img](https://github.com/user-attachments/assets/d4b7ccc7-b1f0-44f4-83e7-f33302a1c768)



![img](https://github.com/user-attachments/assets/1eeb3492-a33b-4896-bc7a-8730226daadf)


![img](https://github.com/user-attachments/assets/f799a555-f8c4-48fa-b7f6-614eaf89eb43)


![img](https://github.com/user-attachments/assets/6fca0d65-dcb3-4570-b060-b23b67e41cce)

3S{Airbus A400M Atlas C1_ZM403_01:25_12:48_15:14} 

3S{A400M_ZM403_01:25_12:48_15:14} 

왜 둘다 아니란거지..?

![img](https://github.com/user-attachments/assets/a4dba980-7801-4f3b-b79b-343f03d0b45d)



갑자기 설명이 추가됐다...



3S{airbusa400matlasc1_ZM403_01:25_12:48_15:14} 

3S{a400m_ZM403_01:25_12:48_15:14} 
둘 다 아니란다 잘 모르겠다.




Minjun's travel2
1.pdf

![img](https://github.com/user-attachments/assets/ed416b83-f33b-4d42-b05b-902e69a3c24a)



![img](https://github.com/user-attachments/assets/05ad6a86-5e2b-48a7-9247-e1664f766ec7)



![img](https://github.com/user-attachments/assets/a1427b96-414a-4732-9b14-4799684245b1)


CHAI797


2.pdf
CHAI797인가..?

![img](https://github.com/user-attachments/assets/28975233-5d11-445c-9eb0-498c47c85f67)



아니란다


![img](https://github.com/user-attachments/assets/4e2fed69-f24b-4f7b-8779-01cc06e94ddc)

![img](https://github.com/user-attachments/assets/4047e2a0-f078-4559-a540-ace6e85148c9)

![img](https://github.com/user-attachments/assets/592789dc-77fc-49e7-91aa-e11965be91af)
첫번째 파일 내용을 넣으니 풀렸다



![img](https://github.com/user-attachments/assets/05447ba2-de09-4e93-ae27-16ffa65ca45f)




![img](https://github.com/user-attachments/assets/cc8ab28a-89c5-4460-8576-e16750e2286d)


hxd로 까보니
![img](https://github.com/user-attachments/assets/db22e136-d42e-4956-b829-5846c9ce20f6)



시작부터 틀린건 아니다.
![img](https://github.com/user-attachments/assets/cdef98de-0d65-4842-8595-d8e0b8e53f63)




png 파일 꺼내봐도 아닐 것 같긴 한데 일단 png 파일 먼저 꺼내보면


![img](https://github.com/user-attachments/assets/9da9f2b2-e7fe-4ece-b7f2-ca3a927c3ae3)



이건 아니고

보다보니까 PK 파일 형식들이 있는 것 같아서

![img](https://github.com/user-attachments/assets/62d625e5-6af0-4b33-a0c1-1f9287af2771)




헤더 3개

![img](https://github.com/user-attachments/assets/7cda40fb-b8fa-439d-9e73-6a3a1279496b)


푸터 2개를 발견했다.

![img](https://github.com/user-attachments/assets/76e370b4-5862-442b-abd8-e85db60ceee9)


PK파일 하나 카빙했더니 이런다.

다른거 하나 더..?

![img](https://github.com/user-attachments/assets/927b97b8-8785-4efa-881a-eeffaa6d4ab3)



힌트라고 뭐가 뜬다..

근데 헥스디 끝부분을 자세히 보니

![img](https://github.com/user-attachments/assets/0d6849a9-c9a5-4027-a36d-01e75f2dfba8)



Hint2.png파일 하나 더 있는 것 같다.. 왜 jpg 하나만 떴지?


생각해보니 아까 PK 헤더는 3개고 푸터만 2개인것 같았다. 이번 pk파일 열 때도 손상됐다고 뜨기도 해서 2번째 헤더부터 마지막 푸터까지 끌어내봤다.

![img](https://github.com/user-attachments/assets/a5449aac-e03b-4657-89e8-8ba626f88a8c)


이렇게 2개 다 뜬다.

![img](https://github.com/user-attachments/assets/07f2e351-0101-4a8c-aefe-a09da692dc33)


또 뭐가 잘못돼있나보다.





Guess This!!

﻿What are Cistercian numbers -- the forgotten ciphers of Medieval monks (zmescience.com)



위 사이트를 방문하면

![img](https://github.com/user-attachments/assets/9419bd60-e1d8-41a1-858c-0f742a4dde46)



해당 사진은

2930 2023 9108 7317 8184 1520 2638 8862 0380 5320

인것을 알 수 있는데 이걸 16진수로 돌려보고 아스키로 해봐도 플래그는 아니다.
