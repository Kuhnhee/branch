# Git Branch


## Git 기초
- `git init`
- `git add`
- `git commit`
- `git log`

## Git 원격저장소 (remote)
- `git remote add [저장소이름] [저장소주소]`
- `git remote` : 원걱저장소의 리스트(이름)
- `git remote -v` : 원격저장소의 리스트(이름, 주소)

### Git 브랜치(branch)
- `git branch` : Branch 리스트 출력
- `git branch [브랜치이름]` : 새로운 Branch 생성
- `git checkout [브랜치이름]` & `git switch [브랜치이름]` : Branch 이동
- `git branch -d [브랜치이름]` : Branch 삭제
- `git branch -b [브랜치이름]` & `git switch -c [브랜치이름]` : Branch 생성 & 이동
- `git merge [브랜치이름]` : 현재 Branch에서 특정 Branch를 병합