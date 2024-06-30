# Egg Guard(에그 가드)

## 시연영상 👉🏻 [Click!](https://youtu.be/VVW5W62DMWA)

## 📅 프로젝트 개요

💵 **기간**

2024.06.04 ~ 2024.06.11 - 기획 및 설계
2024.06.12 ~ 2024.06.27 - 개발

💵 **이지 팀원 소개**

<table>
    <tr>
        <td><img src="https://avatars.githubusercontent.com/u/68572832?v=4" width="180"></td>
        <td><img src="https://avatars.githubusercontent.com/u/39377091?v=4" width="180"></td>
        <td><img src="https://avatars.githubusercontent.com/u/68230815?v=4" width="180"></td>
        <td><img src="https://avatars.githubusercontent.com/u/94967088?v=4" width="180"></td>
    </tr>
    <tr align=center>
        <td><a href='https://github.com/subsub97'>박소연</a></td>
        <td><a href='https://github.com/sooyeon-kr'>오수연</a></td>
        <td><a href='https://github.com/sooyeon-kr'>임찬솔</a></td>
        <td><a href='https://github.com/sooyeon-kr'>장호익</a></td>
    </tr>
</table>

💵 **기획 배경**

-   투자로 수익을 내는 사람들은 `어떤 산업`에서 `무엇`을 `언제 사고` 산 것을 `언제 팔아야`하는 지를 잘 알고 있습니다. 기업에 대한 가치를 어떻게 매기는 걸까요?
-   주변에 이러한 지인이 있다면, 매일 매일 물어보고 따라하고 싶지 않나요?

-   수익률이 높은 개인 투자자의 경험을 간접적으로 얻고, 이를 통해 투자 통찰력을 확장하도록 도와주는 `포트폴리오 구독 서비스`를 기획하였습니다.

-   `수익률이 낮은 개인 투자자`는 _벤치마킹_ 을 통해 투자의 개선점을 찾거나 투자 전략과 같은 _투자 지식을 습득_ 할 수 있습니다.
-   `수익률이 높은 개인 투자자`는 수익률을 _자랑할 수 있는 공간_ 이 될 수 있으며, 포트폴리오 게시를 통해 _부가적인 수입 창출_ 이 가능합니다.

> 더 이상 감이 아닌, **명확한 투자 기준**으로 **높은 수익률의 포트폴리오**를 구성해보세요!

💵 **핵심 기능**

-   _한국투자증권 openAPI_ 를 활용한 `실계좌 추가`
-   _한국투자증권 openAPI_ 를 활용한 구독 포트폴리오의 `보유종목 조회` 및 `최근 거래내역(3개월) 조회`
-   _네이버 증권 데이터_ 를 활용한 백테스팅으로 `과거 투자 성과 조회`
-   _KRX(한국거래소) 정보데이터시스템 제공의 표준 산업 분류 코드_ 를 활용한 _워드 클라우드 형태_ 의 `투자를 많이한 산업 Top5`
-   _한국투자증권 openAPI_ 와 _표준 산업 분류 코드_ 를 활용한 구독 포트폴리오 `투자한 산업 및 종목별 Top5`, `어제 거래 현황`

## 💡서비스 소개

### _Egg Guard(에그가드)_

에그가드는, 포트폴리오 구독 웹 서비스입니다.

> (수익률이 높은 개인 투자자)

1. `계좌`를 `추가`합니다.  
   (앱키, 시크릿키, 계좌번호)

2. 내 포트폴리오 페이지로 이동하여, `포트폴리오 등록`을 합니다.
   (제목 / 소개 / 내용 / 월 구독료 입력)

3. 내 포트폴리오를 구독한 사람의 `질문에 답변`을 달아, 자신의 투자 이유와 같은 내용을 전달합니다.

> (수익률이 낮은 개인 투자자)

1.  마이페이지로 이동하여, `크레딧을 충전`합니다.

2.  포트폴리오 페이지로 이동하여, 원하는 `포트폴리오를 구독`합니다.

3.  포트폴리오 상세페이지로 이동하여, `과거 투자 성과 조회`, `최근 거래 내역 조회`, `보유 종목 조회` 등을 통해 비율로만 알 수 있었던 내용에 대해 자세히 보며 `투자 경험`을 `간접적으로 경험`하며 `분석`합니다.

4.  질의응답 페이지로 이동하여, `궁금한 점에 대해서 의견을 주고 받습니다`.

**Egg Guard를 통해 수익률을 높여보세요**

### ⚙️ 기술 스택

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-3178C6.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![tailwindcss](https://img.shields.io/badge/tailwindcss-%06B6D4.svg?style=for-the-badge&logo=tailwindcss&logoColor=white)
![shadcnui](https://img.shields.io/badge/shadcnui-000000.svg?style=for-the-badge&logo=shadcnui&logoColor=white)

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![sequelize](https://img.shields.io/badge/sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)  
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
​

​

## 📂시스템 아키텍처

![구조도](./src/architecture.png)

## 🖼 주요 화면

## 랜딩페이지

### 💵 메인

|     | 웹                         | 모바일                        |
| --- | -------------------------- | ----------------------------- |
|     | ![Web](./src/web_main.png) | ![Mobile](./src/mob_main.png) |

## 회원관리

### 💵 회원가입

|     | 웹                            | 모바일                           |
| --- | ----------------------------- | -------------------------------- |
|     | ![Web](./src/web_signup1.png) | ![Mobile](./src/mob_signup.png)  |
|     | ![Web](./src/web_signup2.png) | ![Mobile](./src/mob_singup2.png) |

## 마이페이지

### 💵 계좌 추가

|     | 웹                                      | 모바일                                     |
| --- | --------------------------------------- | ------------------------------------------ |
|     | ![Web](./src/web_mypage_addaccount.png) | ![Mobile](./src/mob_mypage_addaccount.png) |

## 나의 포트폴리오 페이지

### 💵 포트폴리오 등록(게시) / 등록(게시) 취소

|     | 웹                                    | 모바일                                   |
| --- | ------------------------------------- | ---------------------------------------- |
|     | ![Web](./src/web_myportfolio_pub.png) | ![Mobile](./src/mob_myportfolio_pub.png) |

## 포트폴리오 메인페이지

### 💵 포트폴리오 구독

|     | 웹                                   | 모바일                                 |
| --- | ------------------------------------ | -------------------------------------- |
|     | ![Web](./src/web_portfolio_main.png) | ![Mobile](./src/mob_mainportfolio.png) |

## 포트폴리오 상세페이지

### 💵 보유종목조회

|     | 웹                                | 모바일                               |
| --- | --------------------------------- | ------------------------------------ |
|     | ![Web](./src/web_detail_main.png) | ![Mobile](./src/mob_detail_info.png) |

### 💵 최근거래내역

|     | 웹                                       | 모바일                                     |
| --- | ---------------------------------------- | ------------------------------------------ |
|     | ![Web](./src/web_detail_transaction.png) | ![Mobile](./src/mob_detail_transation.png) |

### 💵 과거 투자 성과 조회

|     | 웹                                 | 모바일                                |
| --- | ---------------------------------- | ------------------------------------- |
|     | ![Web](./src/web_detail_back1.png) | ![Mobile](./src/mob_detail_back.png)  |
|     | ![Web](./src/web_detail_back2.png) | ![Mobile](./src/mob_detail_back2.png) |

### 💵 질의 응답

|     | 웹                               | 모바일                              |
| --- | -------------------------------- | ----------------------------------- |
|     | ![Web](./src/web_detail_qna.png) | ![Mobile](./src/mob_detail_qna.png) |

## 포트폴리오 구독페이지

### 💵 구독 취소

|     | 웹                             | 모바일                            |
| --- | ------------------------------ | --------------------------------- |
|     | ![Web](./src/web_sub_main.png) | ![Mobile](./src/mob_sub_main.png) |

## 포트폴리오 분석페이지

### 💵 투자한 산업 및 종목별 Top5

|     | 웹                                    | 모바일                                   |
| --- | ------------------------------------- | ---------------------------------------- |
|     | ![Web](./src/web_sub_statistics1.png) | ![Mobile](./src/mob_sub_statistics1.png) |

### 💵 어제 거래 내역 한눈에 보기

|     | 웹                                    | 모바일                                   |
| --- | ------------------------------------- | ---------------------------------------- |
|     | ![Web](./src/web_sub_statistics3.png) | ![Mobile](./src/mob_sub_statistics2.png) |

## 컨벤션

### 📍 Git 컨벤션

```
<컨벤션> : <설명>
```

| 컨벤션   | 설명                                                                                                                            |
| -------- | ------------------------------------------------------------------------------------------------------------------------------- |
| feat     | 새로운 기능과 관련된 것을 의미한다.                                                                                             |
| fix      | 오류와 같은 것을 수정했을 때 사용한다.                                                                                          |
| docs     | 문서와 관련하여 수정한 부분이 있을 때 사용한다.                                                                                 |
| style    | 코드의 변화와 관련없는 포맷이나 세미콜론을 놓친 것과 같은 부분들을 의미한다.                                                    |
| refactor | 코드의 리팩토링을 의미한다.                                                                                                     |
| test     | test를 추가하거나 수정했을 때를 의미한다.                                                                                       |
| chore    | build와 관련된 부분, 패키지 매니저 설정 등 여러가지 production code와 무관한 부분 들을 의미한다. 말 그대로 자질구레한 일들이다. |
| add      | 이미지 등의 정적 자원 추가를 의미한다.                                                                                          |
| init     | 초기 설정 세팅을 의미한다.                                                                                                      |
| rename   | 파일 혹은 폴더 명을 수정하거나 옮기는 작업을 의미한다.                                                                          |
