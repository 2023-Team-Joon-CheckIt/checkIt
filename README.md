# CheckIt

## **Introduction**

![스크린샷 2023-11-22 오후 9.46.59.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/cea18d12-6bc3-41d2-a60e-7e9e4cba29e6/f88dd058-e29c-4bae-92ad-07e47cab3f80/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-22_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.46.59.png)

> **그래프 기반 독서 기록 서비스**
> 
> 
> - 서점 사이트 크롤링하여 책 데이터를 저장해요
> - 나만의 서재 만들어 기록할 수 있어요
> - 등록한 책을 쌓아볼 수 있어요
> - 일주일 독서 추세를 그래프로 볼 수 있어요
> 

## **System Architecture**

///// 아키텍처 /////

## **Tech Stack**

- Frontend
- Backend
- Database&Storage
- DevOps

## How to run

## **Features**

- 메인 페이지 + 로그인
    
    ///// gif /////
    
    - 밀리의 서재 서비스와 비슷하게 구현
    - 스크롤 위치에 따른 이벤트를 적용시켜 동적인 메인페이지 퍼블리싱 진행
- 검색 페이지
    
    ///// gif /////
    
    - swiper 를 사용한 슬라이더 구현
    - 인기있는 도서 안내
        - 가장 좋아요 수를 많이 받은 책
    - 최근 출시작 안내
        - 가장 최근에 출시된 신작
    - 책 검색 기능
    - 내 서재 등록
        - 읽기, 다 읽은 책 버튼을 활용한 내 서재 관리
    - 좋아요 기능
        - 좋아요 버튼을 눌러 “찜한 책” 등록 가능
- 내 서재 페이지
    
    ///// gif /////
    
    - Pagination 을 이용하여 서재 구현
        - 읽은 페이지 기록
        - 리뷰 작성 기능
- 독서 통계 페이지
    
    ///// gif /////
    
    - **Three.js** 를 이용한 독서 기록 시각화
        - 읽은 책의 페이지 수에 따라 책 컴포넌트 두께를 다르게 설정
        - 추후 책 표지에 책 이름 및 책 선택 효과를 더 동적으로 구현 예정
    - **Chart.js** 를 이용한 독서 기록 시각화
        - 완독 날짜를 기준, 일주일 단위로 독서량 체크

## Swagger

Frontend와 Backend 통신을 위한 API 문서화는 Swagger를 이용했다.

![스크린샷 2023-11-22 오후 9.36.42.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/cea18d12-6bc3-41d2-a60e-7e9e4cba29e6/07b62093-ec59-47d7-b07d-f6ad47e30f48/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-22_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.36.42.png)

![스크린샷 2023-11-22 오후 9.36.57.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/cea18d12-6bc3-41d2-a60e-7e9e4cba29e6/84bda430-a90e-4d0c-a407-658b8edbd8ef/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-22_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.36.57.png)

![스크린샷 2023-11-22 오후 9.37.11.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/cea18d12-6bc3-41d2-a60e-7e9e4cba29e6/05c59264-e130-48f8-b45d-933631a5112a/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-22_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.37.11.png)

![스크린샷 2023-11-22 오후 9.37.22.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/cea18d12-6bc3-41d2-a60e-7e9e4cba29e6/ba1849cb-a6fe-4193-9406-9bc1f1a75d0a/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-22_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.37.22.png)

## ERD

![스크린샷 2023-10-28 오전 1.10.41.png](https://file.notion.so/f/f/cea18d12-6bc3-41d2-a60e-7e9e4cba29e6/cbe45bdc-8272-46ad-a5fd-c13ee2005205/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-10-28_%E1%84%8B%E1%85%A9%E1%84%8C%E1%85%A5%E1%86%AB_1.10.41.png?id=73063164-8b9f-4c09-9a23-9046b35b00bd&table=block&spaceId=cea18d12-6bc3-41d2-a60e-7e9e4cba29e6&expirationTimestamp=1700755200000&signature=Wq2c8SMtxfLmz98LA0I3FVSxDASooDbvbHp5IsM6__A&downloadName=%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA+2023-10-28+%E1%84%8B%E1%85%A9%E1%84%8C%E1%85%A5%E1%86%AB+1.10.41.png)

## Our Team


| Name | 박희경 | 송지민 | 김선재 | 정우희 | 권찬영 | 고원준 | |
| ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| Profile | <img width="100px" alt="박희경" src="https://avatars.githubusercontent.com/u/101381901?v=4"> | <img width="100px" alt="송지민" src="https://avatars.githubusercontent.com/u/84628898?v=4"> | <img width="100px" alt="김선재" src="https://avatars.githubusercontent.com/u/83015089?v=4"> | <img width="100px" alt="정우희" src="https://avatars.githubusercontent.com/u/121246589?v=4"> | <img width="100px" alt="권찬영" src="https://avatars.githubusercontent.com/u/85063965?v=4"> | <img width="100px" alt="고원준" src="https://avatars.githubusercontent.com/u/86594108?v=4"> | 
| Role | Backend, DevOps | Backend, DevOps | Frontend | Frontend | Backend | Frontend | 
| gitHub  | [@gmlrude](https://github.com/gmlrude) | [jiminsong490](https://github.com/jiminsong490) | [@sunjae98](https://github.com/sunjae98) | [@Joy0w0](https://github.com/Joy0w0) | [@fnzl54](https://github.com/fnzl54) | [@KoneJ](https://github.com/KoneJ) | 
