# git-study
깃허브 하나하나 공부해가기

<hr>

# 깃허브에 파일 업로드
1. Github에 새 저장소 생성
2. 업로드하려고 하는 폴더 마우스 우클릭 (Git Bash here)
3. 초기 설정
```
git config --global user.name <내 깃허브 이름>
git config --global user.email <내 깃허브 메일 주소>
```
4. 파일 준비
```
git init
git add .
git status
git commit -m "주석 내용"
```
5. 깃허브에 업로드하기
```
git remote add origin <깃허브 저장소 주소>
git push -u origin master
```

<hr>

# 번외. 깃허브 오류 
#### 1. git push -u origin main 할때 발생하는 오류
```
error code
error: failed to push some refs to 'https://github.com/~~
```
*해결방법*
```
git branch -M main
git push -u origin main
```
