## 1 프로젝트 전체 분석

You are a senior blockchain software architect.
DO NOT write the whitepaper yet.
First, inspect the entire repository.
Analyze every important source.
This includes, but is not limited to:
README.md
docs/
docs/ai/
front/
back/
contract/
deployment/
package.json
build.gradle
application.yml
Solidity contracts
Database schema
REST APIs
Generate a document named:
PROJECT_ANALYSIS.md
The document must contain:
Overall Project Summary

Folder Structure

Implemented Features

Missing Features

Business Logic

Frontend Architecture

Backend Architecture

Smart Contract Architecture

Database Structure

API Summary

Deployment Architecture

Security Mechanisms

Known Limitations

TODOs discovered from the source code

IMPORTANT
Never invent functionality.
If something is not implemented,
explicitly state that.
Write in Korean.

Do not generate the whitepaper.
Only generate PROJECT_ANALYSIS.md.

## 2 시스템 아키텍처 문서

Using PROJECT_ANALYSIS.md,
generate
SYSTEM_ARCHITECTURE.md
Describe the entire system architecture.
Include:
Overall architecture
Frontend
Backend
Database
Smart Contract
Blockchain
Wallet
Deployment
Explain communication between every component.
Generate Mermaid diagrams whenever possible.
The document should be suitable for software engineers.
Do not omit implementation details.

Write in Korean.

IMPORTANT

Only describe what actually exists in the repository.
Do not invent functionality.
If something is not implemented, explicitly state:
"현재 MVP에서는 구현되지 않았으며 향후 구현 예정입니다."
Writing Style Requirements
Write in Korean.
Write like an experienced software engineer writing official technical documentation.
Do not write like ChatGPT.
Do not use:
emojis
icons
decorative symbols
marketing language
exaggerated expressions
Avoid words such as:
혁신적인
강력한
획기적인
최고의
매우
손쉽게
차세대
Use factual and objective language only.
Assume the reader is a senior software engineer.
Do not explain obvious concepts.
Use clean Markdown with only headings, bullet lists, tables, and code blocks.
Do not use callout boxes or decorative formatting.
Verify that every statement matches the current implementation before writing.

## 3 스마트 컨트랙트 기술 문서

Using PROJECT_ANALYSIS.md,
generate
SMART_CONTRACT_DESIGN.md
Analyze every Solidity contract.
Explain:
Overall design
State Machine
Storage Layout
Events
Modifiers
Access Control
Lifecycle
ERC20 interaction
NFT interaction
Security
Gas considerations
Explain every public function.
Do not summarize.
Explain each function individually.
Write in Korean.

IMPORTANT

Only describe what actually exists in the repository.
Do not invent functionality.
If something is not implemented, explicitly state:
"현재 MVP에서는 구현되지 않았으며 향후 구현 예정입니다."
Writing Style Requirements
Write in Korean.
Write like an experienced software engineer writing official technical documentation.
Do not write like ChatGPT.
Do not use:
emojis
icons
decorative symbols
marketing language
exaggerated expressions
Avoid words such as:
혁신적인
강력한
획기적인
최고의
매우
손쉽게
차세대
Use factual and objective language only.
Assume the reader is a senior software engineer.
Do not explain obvious concepts.
Use clean Markdown with only headings, bullet lists, tables, and code blocks.
Do not use callout boxes or decorative formatting.
Verify that every statement matches the current implementation before writing.

## 4 백엔드 기술 문서

Using PROJECT_ANALYSIS.md,

generate

BACKEND_DESIGN.md

Analyze the backend.

Explain:

- Spring Boot Architecture
- MyBatis
- Package Structure
- Controllers
- Services
- Mappers
- Database
- API Flow
- Authentication
- Wallet Mapping
- Transaction Flow
- Error Handling

Include sequence diagrams if appropriate.

Write in Korean.

IMPORTANT

Only describe what actually exists in the repository.
Do not invent functionality.
If something is not implemented, explicitly state:
"현재 MVP에서는 구현되지 않았으며 향후 구현 예정입니다."
Writing Style Requirements
Write in Korean.
Write like an experienced software engineer writing official technical documentation.
Do not write like ChatGPT.
Do not use:
emojis
icons
decorative symbols
marketing language
exaggerated expressions
Avoid words such as:
혁신적인
강력한
획기적인
최고의
매우
손쉽게
차세대
Use factual and objective language only.
Assume the reader is a senior software engineer.
Do not explain obvious concepts.
Use clean Markdown with only headings, bullet lists, tables, and code blocks.
Do not use callout boxes or decorative formatting.
Verify that every statement matches the current implementation before writing.

## 5 프론트엔드 기술 문서

Using PROJECT_ANALYSIS.md,

generate

FRONTEND_DESIGN.md

Explain:

- Vue Architecture
- Component Structure
- Routing
- State Management
- Wallet Connection
- Smart Contract Interaction
- API Communication
- UI Flow
- Transaction Flow
- Error Handling

Generate diagrams where appropriate.

Write in Korean.

IMPORTANT

Only describe what actually exists in the repository.
Do not invent functionality.
If something is not implemented, explicitly state:
"현재 MVP에서는 구현되지 않았으며 향후 구현 예정입니다."
Writing Style Requirements
Write in Korean.
Write like an experienced software engineer writing official technical documentation.
Do not write like ChatGPT.
Do not use:
emojis
icons
decorative symbols
marketing language
exaggerated expressions
Avoid words such as:
혁신적인
강력한
획기적인
최고의
매우
손쉽게
차세대
Use factual and objective language only.
Assume the reader is a senior software engineer.
Do not explain obvious concepts.
Use clean Markdown with only headings, bullet lists, tables, and code blocks.
Do not use callout boxes or decorative formatting.
Verify that every statement matches the current implementation before writing.

## 6 보안 및 기술 의사결정

Using PROJECT_ANALYSIS.md,

generate

SECURITY_AND_TECHNICAL_DECISIONS.md

Explain:

Security

- ReentrancyGuard
- SafeERC20
- Access Control
- Input Validation
- Invalid State Protection

Technical Decisions

Why:

- NFT
- ERC721
- GIWA
- Spring Boot
- Vue
- Railway
- Vercel
- MySQL
- MetaMask

List remaining risks.

List future improvements.

Write in Korean.

IMPORTANT

Only describe what actually exists in the repository.
Do not invent functionality.
If something is not implemented, explicitly state:
"현재 MVP에서는 구현되지 않았으며 향후 구현 예정입니다."
Writing Style Requirements
Write in Korean.
Write like an experienced software engineer writing official technical documentation.
Do not write like ChatGPT.
Do not use:
emojis
icons
decorative symbols
marketing language
exaggerated expressions
Avoid words such as:
혁신적인
강력한
획기적인
최고의
매우
손쉽게
차세대
Use factual and objective language only.
Assume the reader is a senior software engineer.
Do not explain obvious concepts.
Use clean Markdown with only headings, bullet lists, tables, and code blocks.
Do not use callout boxes or decorative formatting.
Verify that every statement matches the current implementation before writing.

## 7 백서 초안 생성

Using

PROJECT_ANALYSIS.md

SYSTEM_ARCHITECTURE.md

SMART_CONTRACT_DESIGN.md

BACKEND_DESIGN.md

FRONTEND_DESIGN.md

SECURITY_AND_TECHNICAL_DECISIONS.md

Generate

WHITEPAPER_DRAFT.md

Target audience:

- Hackathon judges
- Blockchain developers
- Investors with technical background

Structure:

1. Project Overview

2. Problem Statement

3. Proposed Solution

4. Architecture

5. Business Flow

6. Smart Contract

7. Backend

8. Frontend

9. Security

10. Technical Decisions

11. MVP Scope

12. Roadmap

13. Expected Impact

Do not include marketing language.

Everything must match the implementation.

Write in Korean.

IMPORTANT

Only describe what actually exists in the repository.
Do not invent functionality.
If something is not implemented, explicitly state:
"현재 MVP에서는 구현되지 않았으며 향후 구현 예정입니다."
Writing Style Requirements
Write in Korean.
Write like an experienced software engineer writing official technical documentation.
Do not write like ChatGPT.
Do not use:
emojis
icons
decorative symbols
marketing language
exaggerated expressions
Avoid words such as:
혁신적인
강력한
획기적인
최고의
매우
손쉽게
차세대
Use factual and objective language only.
Assume the reader is a senior software engineer.
Do not explain obvious concepts.
Use clean Markdown with only headings, bullet lists, tables, and code blocks.
Do not use callout boxes or decorative formatting.
Verify that every statement matches the current implementation before writing.

## 8 최종 기술백서 완성

Review every generated document.

Improve consistency.

Remove duplicated explanations.

Verify that every statement matches the implementation.

If something is not implemented,

replace it with

"현재 MVP에서는 구현되지 않았으며 향후 구현 예정입니다."

Then generate the final document:

WHITEPAPER.md

Requirements:

- Professional engineering document
- Suitable for hackathon submission
- Consistent terminology
- Proper Markdown
- Mermaid diagrams
- Technical accuracy
- No hallucination
- No marketing exaggeration

Write in Korean.

IMPORTANT

Only describe what actually exists in the repository.
Do not invent functionality.
If something is not implemented, explicitly state:
"현재 MVP에서는 구현되지 않았으며 향후 구현 예정입니다."
Writing Style Requirements
Write in Korean.
Write like an experienced software engineer writing official technical documentation.
Do not write like ChatGPT.
Do not use:
emojis
icons
decorative symbols
marketing language
exaggerated expressions
Avoid words such as:
혁신적인
강력한
획기적인
최고의
매우
손쉽게
차세대
Use factual and objective language only.
Assume the reader is a senior software engineer.
Do not explain obvious concepts.
Use clean Markdown with only headings, bullet lists, tables, and code blocks.
Do not use callout boxes or decorative formatting.
Verify that every statement matches the current implementation before writing.

Before generating WHITEPAPER.md,

review every previously generated document.

Remove duplicated content.

Unify terminology throughout the document.

Ensure consistency between architecture, API, database, and smart contract descriptions.

The final document should read naturally as if it were written by a senior software engineer.

Do not make the writing overly polished or AI-like.

Prioritize technical accuracy over completeness.
