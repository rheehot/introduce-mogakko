🎨 **2020-06-26 수정**

🎉 **[노마드코더 뉴스레터](https://us16.campaign-archive.com/?u=a99b43453db5050f1f26b2744&id=4bf886217d)에 올라갔어요!**

✅ **지금 정식 서비스 중입니다!**

[https://mo-gak-ko.xyz](https://mo-gak-ko.xyz)

# 📌 모각코란

**모여서 각자 코딩**, 줄여서 **모각코**라고 부릅니다.

주 사용층은 개발자를 희망하는 학생부터 현직 개발자까지 다양한 직군과 회사를 다니는 사람들을 위한 **개발 소모임 매칭 서비스**입니다.

팀프로젝트를 하고싶은 분들은 팀원도 구할 수 있어요.

이 서비스를 이용하면 트렌드 변화가 빠른 업계 특성 상 다양한 개발자와 교류를 하면서 정보를 빠르게 얻을 수 있어요.

---

## ✨ 어떤 계기로 만드셨어요

노마드코더 슬랙에서 제작 요청이 들어와서 만들게 되었어요.

---

## 👥 누구와 함께 만드나요

기획부터 프론트, 백엔드, 배포까지 1인 개발 중입니다.

---

## ⚙️ 사용한 기술 스택은 무엇인가요

실제 서비스기 때문에 코드는 공개할 수 없어요.

제 블로그에 오시면 일부분 보실 수 있습니다.

### 프론트

- HTML + CSS + Typescript
- React
- Apollo

### 백엔드

- Node.js + Typescript
- GraphQLServer
- Prisma2
- JWT
- OAuth2.0

### 배포

- Oracle Cloud VM 인스턴스 (정식 서비스용)
- Heroku (베타 서비스용)

---

## 💬 모각코만의 특징이 있나요

개발자 특성 상 Github 계정은 누구나 가지고 있고(없다 해도 개발 좋아하면 만들 것) 불필요한 기능은 배제하면서 나름 무료에 근접하게 만들 수 있었습니다.

### 세부내용

1. 로그인으로 **Github OAuth2.0**만을 사용하여 DB에 **password**를 저장하지 않음.
2. 국민 메신저를 놔두고 웹에서 채팅을 구현할 필요가 없기 때문에 **SNS**로 참여자간 소통을 함.
3. 최대한 무료로 서비스를 런칭하기 위해 모임의 배경 이미지도 **본인 깃허브 profile image**를 재활용하는 극한의 절약 실천.
4. **username**과 **profile_image** 또한 깃허브 로그인을 다시 하면 변경 되어지도록 만듦.
5. 백엔드 배포로 AWS EC2 e2.micro에 비해 성능은 떨어지지만 적어도 1년 뒤에 유료로 전환되어지지 않는 평생 무료인 Oracle Cloud VM을 사용함.

---

## 🔧 진행 상황

오늘, 6월 10일 기준으로 아래와 같습니다.

- **Front-end** : 정식 서비스 중 + 추천장소 개발 중
- **Back-end** : 정식 서비스 중
- **Deploy :** 정식 서비스 중

모각코 개발 진행하면서 개인 블로그에 포스팅을 하고 있습니다.

[https://velog.io/@jhj46456/series/Mo-Gak-Ko](https://velog.io/@jhj46456/series/Mo-Gak-Ko)

## 👇 홈페이지 URL

[https://mo-gak-ko.xyz](https://mo-gak-ko.xyz)

## 🌈 홈페이지 사진

사용된 아이콘은 모두 **SIL**, **OFL** svg 아이콘이에요.

판매를 제외하고 어떤 용도로든 사용이 가능해요.

### 메인

![image](https://user-images.githubusercontent.com/46839654/85648786-8776ed80-b6dc-11ea-9be9-d1d5bc3fd0cd.png)

> 노마드코더 로고는 사용 허가를 받았어요.

### 모임 등록

![image](https://user-images.githubusercontent.com/46839654/84260945-dd348d00-ab55-11ea-9b94-93ffcd7f99c1.png)

> 모바일 Card까지 고려를 해서 지역은 6자, 제목은 18자로 Validation을 걸었어요.
>
> 또한, URL Validation을 하고 있어요.

### 모임 세부정보(참여X)

![image](https://user-images.githubusercontent.com/46839654/84261618-04d82500-ab57-11ea-8ddf-43975607fa54.png)

> 비참여자와 외부에서 API에 접근하여 모임의 비공개 정보를 얻을 수 없게 보안을 높였어요.
>
> 자기소개를 입력하고 참가 신청을 할 수 있어요.

### 모임 세부정보(신청O)

![image](https://user-images.githubusercontent.com/46839654/84261751-45d03980-ab57-11ea-9bbb-a774f9d1d55d.png)

> 요청된 상태에서는 취소가 가능해요.

### 모임 세부정보(참여O)

![image](https://user-images.githubusercontent.com/46839654/84261194-53d18a80-ab56-11ea-85a4-35fd3a116c75.png)

> 모임에 참가요청이 생기면 **방장**은 참가 허가/거부를 할 수 있어요.

![image](https://user-images.githubusercontent.com/46839654/84261283-7cf21b00-ab56-11ea-95c8-95409a633df6.png)

> 모임에 참여한 참가자는 방장이 강퇴할 수 있어요.

![image](https://user-images.githubusercontent.com/46839654/84261370-9c894380-ab56-11ea-9f61-4483b16e5a11.png)

> **채팅방 참가** 버튼을 누르면 링크가 생겨요.

### 모임 수정

![image](https://user-images.githubusercontent.com/46839654/84261442-bc206c00-ab56-11ea-9730-47ace8a1b60d.png)

> URL을 통한 직접 접근을 차단했고, 방장만 접근 가능한 페이지에요.
>
> 모임 삭제도 가능해요.

### 알림

![image](https://user-images.githubusercontent.com/46839654/85648899-c016c700-b6dc-11ea-9fd3-2305df5c856a.png)

![image](https://user-images.githubusercontent.com/46839654/85648937-d91f7800-b6dc-11ea-8acb-8e46742cd0aa.png)

> 모임에 요청이 오거나 요청 허가/거부, 강퇴 당하면 알림이 와요.

![image](https://user-images.githubusercontent.com/46839654/84262008-c727cc00-ab57-11ea-90ac-5017de3fb1c3.png)

> 이것처럼요.
