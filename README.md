# friendly-palm-tree
### yarn2, next 사용

1. yarn2
```
$ yarn init -2
# yarn set version berry
```

2. https://nextjs.org/docs/getting-started 매뉴얼대로 실행
```
$ yarn add next react react-dom
$ yarn add --dev typescript @types/react @types/node
$ yarn dev
```

https://yarnpkg.com/getting-started/editor-sdks
```
$ yarn dlx @yarnpkg/sdks vscode
```


### 궁금한 점
기존 프로젝트는 yarn 1.x 버전을 쓰고 테스트 하는 버전은 berry로 쓰고 싶은데 yarn 버전을 프로젝트별로 따로 처리할 수 있는 방법은 없나?
전역에 있는 yarn에 적용해야만 버전이 바뀌는건가?
프로젝트 내에서 암만 버전 바꿔도 적용이 안되는 것 같다...