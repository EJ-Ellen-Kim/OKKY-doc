---
title: OKKY Menu Hierarchy & Code
version: 1.0
author: Eunjin Kim
updated: 2025-10-24
status: draft
---

# OKKY Menu Hierarchy & Code

This document defines the **Information Architecture (IA)** for OKKY's current web service and the **code naming** scheme.

## Naming Rules (Summary)
- Top-level: First-letter capitalized (e.g., QNA, Knowledge, Community)
- Sub-menus: `[ParentMenuName]_[EnglishName]` (e.g., Knowledge_Tips)
- Korean multi-word names → **CamelCase** (e.g., JobSeekers)

## Menu Hierarchy & Code

```
Home : HOME

Q&A : QNA
  기술 : QNA_Tech
  커리어 : QNA_Career
  기타 : QNA_Etc

지식 : Knowledge
  Tech 뉴스 : Knowledge_TechNews
  팁 : Knowledge_Tips
  칼럼 : Knowledge_Column
  리뷰 : Knowledge_Review
  IT보도자료 : Knowledge_ITPress

커뮤니티 : Community
  사는얘기 : Community_Life
  AI : Community_AI
  취준생 : Community_JobSeekers
  모임&스터디 : Community_Study
  IT정책토론 : Community_ITPolicy
  피드백 : Community_Feedback

이벤트 : Event
  IT행사 : Event_IT
  홍보&광고 : Event_Promotion

부트캠프 : Bootcamp
  교육과정 : Bootcamp_Course

Jobs : Jobs
  계약직 : Jobs_Contract
  정규직 : Jobs_Fulltime
  Talent : Jobs_Talent
  좋은회사/나쁜회사 : Jobs_CompanyReview

Contact : Contact
  Release : Contact_Release
  버그 및 제안 : Contact_Bug
  게시판 생성 요청 : Contact_BoardRequest
  공지사항 : Contact_Notice
  OKKY 행사 : Contact_Event
```
