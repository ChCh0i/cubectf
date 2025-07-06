# Legal Snacks
<p align="center">
  <img src=https://github.com/user-attachments/assets/f2a9f9a4-1e82-4e71-a69b-fc7beca0073f>
</p>

![image](https://github.com/user-attachments/assets/6a5db3fe-dab4-42c2-b292-5bd1fd0957b6)

## 분석
![image](https://github.com/user-attachments/assets/d371178b-4a1f-49ad-b784-92a4024d1f0b)
- 회원가입을 하면 세션을 부여받고 로그인 되는것을 확인가능.

![image](https://github.com/user-attachments/assets/3429b098-37df-435f-b16b-8378be174218)
- 플래그는 ```Elite Hacker Snack``` 을 구매해야 얻을수 있는것으로 보인다.

![image](https://github.com/user-attachments/assets/cb7f5882-aaf7-4271-a5a2-87d77ca0e7f4)
- 사용자의 잔고는 100$ 이고 플래그의 가격은 99999.99$ 이다.

![image](https://github.com/user-attachments/assets/fc7d090c-79e6-4123-8e4c-25a61cd108d6)
- 품목을 카트에 담을때의 요청을 보면 해당 상품의 넘버와 수량을 요청으로 보내는것을 확인이가능하다.

## Poc
![image](https://github.com/user-attachments/assets/9ca1d8f2-6459-4d5c-a31d-108b5e058b5a)
- 해당 품목의 수량을 음수로 대입했을때 정상적으로 응답과 세션이 발급되는것을 확인할수있다.

![image](https://github.com/user-attachments/assets/547fdff4-6c14-4475-be1e-dd611b98c20b)
- 카트를 보면 음수로 대입한 품목들의 금액이 음수가 되어 플래그 구매 가격을 깎는것을 확인가능하다.

![image](https://github.com/user-attachments/assets/8ffa3591-449d-4025-9709-56d4b1ac6eaa)
- flag획득
