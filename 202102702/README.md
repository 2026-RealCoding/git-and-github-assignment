새로운 작업이 주어졌을 때
→ develop 브랜치에서 feature 브랜치를 분기한다.
예: feature/login, feature/signup
작업을 완료했을 때
→ PR은 develop 브랜치로 Merge 요청한다.
master에 이미 Merge된 작업에서 수정사항이 생겼을 때
→ hotfix 브랜치를 사용한다.
보통 master(main)에서 hotfix 브랜치를 분기해서 수정한 뒤, 다시 master와 develop 둘 다 반영한다.