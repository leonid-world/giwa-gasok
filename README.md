# 🚀 GIWA Receivable Finance

> **GIWA Network 기반 RWA(Real World Asset) 매출채권 토큰화 플랫폼**
>
> 기업의 매출채권을 NFT로 토큰화하여 만기 이전에도 자금을 조달할 수 있도록 지원하는 온체인 금융 플랫폼입니다.

---

## 📖 프로젝트 소개

기존 매출채권 금융은 복잡한 심사 절차와 높은 진입장벽으로 인해 중소기업이 자금을 확보하기까지 많은 시간과 비용이 소요됩니다.

**GIWA Receivable Finance**는 블록체인 기술을 활용하여 매출채권을 NFT로 토큰화하고, 투자자가 해당 채권에 자금을 공급할 수 있는 구조를 제공합니다.

이를 통해

- 💰 기업은 만기 이전에 유동성을 확보하고
- 📈 투자자는 안정적인 단기 투자 기회를 얻으며
- 🔒 모든 거래는 스마트 컨트랙트를 통해 투명하게 관리됩니다.

---

# 📚 프로젝트 문서

| 문서                                                      | 설명                                |
| --------------------------------------------------------- | ----------------------------------- |
| 👥 **[Team Profile](./profile/Profile.md)**               | 팀 소개 및 프로젝트 배경            |
| 📊 **[Pitch Deck](./pitchdeck/PitchDeck.md)**             | 문제 정의, 솔루션, 비즈니스 모델    |
| 📘 **[Technical Whitepaper](./whitepaper/WhitePaper.md)** | 시스템 구조 및 스마트 컨트랙트 설계 |

---

# 🌐 서비스

| 구분                              | 링크                                                                                |
| --------------------------------- | ----------------------------------------------------------------------------------- |
| 🌍 Live Demo                      | https://giwa-ui.vercel.app                                                          |
| 📜 Smart Contract (GIWA Explorer) | https://sepolia-explorer.giwa.io/address/0xc72A8FE507E6D9C21c1D3cDc83C7dbB15E740327 |

---

# 🏗️ 시스템 아키텍처

> 아키텍처 이미지를 추가해주세요.

```
Vue.js
     │
     ▼
Spring Boot API
     │
     ├──────────────► MySQL
     │
     ▼
GIWA Smart Contract
     │
     ▼
GIWA Network
```

---

# 🔄 서비스 흐름

```text
Seller
   │
   ▼
매출채권 등록

   │
   ▼
Buyer 검증

   │
   ▼
NFT 토큰화

   │
   ▼
투자자 Funding

   │
   ▼
Buyer 상환

   │
   ▼
투자자 수익 실현
```

---

# 🛠️ 기술 스택

## Frontend

- Vue.js
- PrimeVue
- ethers.js

## Backend

- Spring Boot
- MyBatis
- MySQL

## Blockchain

- Solidity
- OpenZeppelin
- GIWA Network

## Infrastructure

- Railway
- Vercel

---

# 📦 Repository

| Repository                                                          | Description        |
| ------------------------------------------------------------------- | ------------------ |
| **[Frontend](https://github.com/leonid-world/giwa-ui)**             | Vue.js Client      |
| **[Backend](https://github.com/leonid-world/giwa-api)**             | Spring Boot API    |
| **[Smart Contract](https://github.com/leonid-world/giwa-contract)** | Solidity Contracts |

---

# 📄 License

MIT License
