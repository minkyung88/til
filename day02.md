# 2일차 정리

### github

1. push

```bash
git init
git log --oneline
touch a.txt
git add a.txt
git commit -m "add a.txt"
git push origin master
```

2. igonore

```bash
git init
touch .gitignore
git add .
git commit -m "add .gitignore"
git log --oneline
```

3. pull - clone으로 인한 파일 업로드

```bash
touch .gitignore
git add .
git commit -m "add .gitignore"
git log --oneline
git pull origin master
```

4. clone 만들기- git bash에서

```bash
git clone [github에서 복사한 코드 붙여넣기]
```

