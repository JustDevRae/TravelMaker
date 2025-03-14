# TravelMaker
여행 체험 상품 등록 및 예약 서비스를 제공하는 플랫폼.

## 개발 기간
2024.07.16 ~ 2024.09.02

## 주요 기능
1️⃣ 소셜/로그인/회원가입 <br>
2️⃣ 검색과 카테고리를 통한 체험 필터링 <br>
3️⃣ 체험 예약 및 후기 작성 <br>
4️⃣ 체험 등록 및 수정 <br>
5️⃣ 닉네임, 비밀번호, 프로필 이미지 수정

## 참여 인원
|      **김민재**|                                                           **김승래**|                 **이승헌**|                                                        **주강산**|                                                               **장혜민**|
| :-: | :-: | :-: | :-: | :-: |
|[<img src="https://avatars.githubusercontent.com/u/162538553?v=4" height=100> <br/> @PixeIDark](https://github.com/PixeIDark)| [<img src="https://avatars.githubusercontent.com/u/160004698?v=4" height=100> <br/> @JustDevRae](https://github.com/JustDevRae) | [<img src="https://avatars.githubusercontent.com/u/36994104?v=4" height=100> <br/> @heony704](https://github.com/heony704) | [<img src="https://avatars.githubusercontent.com/u/162934516?v=4" height=100> <br/> @JooKangsan](https://github.com/JooKangsan) | [<img src="https://avatars.githubusercontent.com/u/162106484?v=4" height=100> <br/> @hnitam](https://github.com/hnitam) |

## 기술스택
- **Typescript**
- **Next.js(App Router)** 
- **TailwindCSS** 
- **Axios** 
- **React-Query** 
- **React-Hook-Form**
- **Zod**
- **Zustand**
- **pnpm**

## 폴더 구조
```
├── src/
│   ├── middleware.ts
│   ├── apis/
│   │   ├── activitiesAPI.ts
│   │   ├── API.type.ts
│   │   ├── ApiError.ts
│   │   ├── authAPI.ts
│   │   ├── axiosInstance.ts
│   │   ├── myActivitiesAPI.ts
│   │   ├── myNotificationsAPI.ts
│   │   ├── myReservationAPI.ts
│   │   ├── OauthAPI.ts
│   │   ├── usersAPI.ts
│   ├── app/
│   │   ├── error.tsx
│   │   ├── favicon.ico
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   ├── (auth)/
│   │   │   ├── layout.tsx
│   │   │   ├── signin/
│   │   │   │   ├── page.tsx
│   │   │   ├── signup/
│   │   │   │   ├── page.tsx
│   │   ├── (home)/
│   │   │   ├── layout.tsx
│   │   │   ├── page.tsx
│   │   │   ├── search/
│   │   │   │   ├── page.tsx
│   │   │   │   ├── _components/
│   │   │   │   │   ├── ActivityGrid.tsx
│   │   │   │   │   ├── SortDropdown.tsx
│   │   │   │   │   ├── TabList/
│   │   │   │   │   │   ├── index.tsx
│   │   │   │   │   │   ├── Tab.tsx
│   │   │   ├── utils/
│   │   │   │   ├── activitySectionQuery.ts
│   │   │   ├── [activityId]/
│   │   │   │   ├── page.tsx
│   │   │   │   ├── queryOptions.ts
│   │   │   │   ├── _components/
│   │   │   │   │   ├── Contents.tsx
│   │   │   │   │   ├── Images.tsx
│   │   │   │   │   ├── Map.tsx
│   │   │   │   │   ├── MobileFooter.tsx
│   │   │   │   │   ├── ReservationModal.tsx
│   ├── components/
│   │   ├── Button.tsx
│   │   ├── Modal.tsx
│   │   ├── Popup.tsx
│   │   ├── Tooltip.tsx
│   ├── contexts/
│   │   ├── ReactQueryProviders.tsx
│   ├── hooks/
│   │   ├── useDropdownToggle.ts
│   │   ├── useImageError.ts
│   │   ├── useMediaQuery.ts
│   │   ├── useUpdateQuery.ts
│   ├── lib/
│   │   ├── GoogleAnalytics.tsx
│   ├── store/
│   │   ├── kakaoSocialStatusStore.ts
│   │   ├── socialLoginStore.ts
│   ├── utils/
│   │   ├── createQueryString.ts
│   │   │   ├── formatDateToKorean.ts
│   │   │   ├── formatKoreanWon.ts
│   │   │   ├── formatTime.ts
│   │   │   ├── getUserInfoFromCookie.ts
│   │   │   ├── logoutCookies.ts
│   │   │   ├── schema.ts
```

