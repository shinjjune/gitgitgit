
## git 특강(2019_08_29)



##### index
```
1. git init
2. git remote add origin https://github.com/shinjjune/movie_app_2019
3. git add .
4. git commit -m "#1.0 Creating your first React App"
5. git push origin master
```

```
git에 이중폴더 올라갔을 경우 (회색폴더 둘)
1. git status
deleted : ES6 <- 이중 파일
2. git rm ES6
3. git commit -m "delete"
4. giit push

끝!!!
```


#### git을 통한 협업하기 (push/pull)

- git bash

```
mkdir codes
cd codes

code .
```

VScode

github -> repository ->settings ->collaborators

- codes/README.md



```
# 끝말잇기
git을 통한 협업 프로젝트

## 협업시작
부하는 들어라. 끝말잇기 시작해라.
```

- git bash

```
git init
git status

git add readme.md
git commit -m "first commit" (m : messeage)
git log
git log --oneline
```

대장은 협업 repository 만든다

git remote add origin https://github.com/JHscar/ggutmalpjt.git

git push - u origin master





#### <부하>

```
mkdir buha

cd buha
```

clone을 통해 코드를 가져온다.

```
git clone https://github.com/JHscar/ggutmalpjt.git
code .

git pull origin master

git add README.md

git commit -m "blabla"

git push origin master
```



#### <대장>

```
git pull origin master

git add README.md

git commit -m "blabla"

git push origin master
```





### fork

내가 수정해서 제안해볼게

내거를 수정해서 pull-request

create pull request



### git branch

->  실전에서 하게될 협업 Flow

branching

```
mkdir branch
cd branch

VSCODE
branch/index.html
```



##### emmet:코드 야매, 효과적으로 구성

#### 해당 hash 로 이동
checkout #hash

#### branch 병합
git merge side

#### branch 만들고 동시에 이동
git checkout -b member

#### branch 지우는 법
git branch -d side


[1일차 실습과제]
1. Git 학습내용 마크다운 정리
2. Git & Github 추가내용 정리
 - 생활코딩 등 외부 소스 활용
3. Git Branching 실습 https://learngitbranching.js.org/?locale=ko


#### branch???

![branch](https://user-images.githubusercontent.com/47058441/63921922-a71e9480-ca7e-11e9-95ef-da88b491677a.JPG)
