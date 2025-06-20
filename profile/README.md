## 🚀 프로젝트 소개

---

기존 모놀리스 아키텍처에서 ***마이크로서비스 아키텍처(MSA)*** 로 재설계하여 확장성과 유연한 배포가 가능하게 만드는 프로젝트입니다.

---

<br>

# 컨벤션 정리

## 🌿 Git branch 전략

> **기능 개발 단계 - 프론트 🎨**
> 
- main : (배포) deploy branch
- develop : (개발) develop branch
- feat/(기능): feature & fix branch by name

> **기능 개발 단계 - 백엔드 ⚙️**
> 
- main : (배포) deploy branch
- develop : (개발) develop branch
- feat/(기능주제): feature & fix branch by name

## 📝 Commit message prefix

| Prefix      | 설명                                  | 추가 설명                                                                          |
| :---------- | :------------------------------------ | :--------------------------------------------------------------------------------- |
| **feat.** | ✨ 새로운 기능 추가 / 기능 변경          | 사용자에게 새로운 기능을 제공하거나 기존 기능을 변경할 때                          |
| **fix.** | 🐛 버그 수정                             | 코드의 버그를 해결했을 때                                                          |
| **refactor.** | ♻️ 리팩토링 (기능 변경 없이 코드 개선)   | 기능 변경 없이 코드 구조를 개선하거나 가독성을 높일 때                             |
| **chore.** | ⚙️ 설정 파일, 패키지 등 코드 수정 없는 작업 | 빌드 시스템, 라이브러리 설치, 설정 파일 변경 등 코드 자체에 영향을 주지 않는 작업 |
| **docs.** | 📚 문서 수정                             | README 파일, 위키, Notion 링크 등 문서 관련 변경 시                                |
| **style.** | 🎨 코드 포맷팅, 세미콜론 추가, lint 수정 등 | 코드의 동작에는 영향을 주지 않지만, 코드의 "스타일(형식)"을 정리할 때             |



news Database → title/create_time/category/id

favorite Database → create_at

---

Group : com.mini2

Artifact :  interest-service