---
title:  "React Native 셋팅하기"
search: false
categories: 
  - Javascript
  - ReactNative
last_modified_at: 2020-07-21T23:11:52
---

> 참고 사이트 <br/><a href="https://reactnative.dev/">https://reactnative.dev/</a>

# 사전 준비

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/homebrew.png" style="width: 20px;"/>&nbsp;&nbsp;Homebrew 설치
:    <a href="https://brew.sh/"><small>홈페이지로 이동</small></a><br/>
터미널에 아래와같이 입력한다.
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/nodejs.png" style="width: 20px;"/>&nbsp;&nbsp;Node.js 설치
:   <a href="https://nodejs.org/"><small>홈페이지로 이동</small></a><br/>
홈페이지에서 상황에 맞는 파일을 다운받아 설치한다.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/yarn.png" style="width: 20px;"/>&nbsp;&nbsp;Yarn 설치
:    <a href="https://yarnpkg.com/getting-started/install"><small>홈페이지로 이동</small></a><br/>
npm을 사용할 경우 설치하지 않아도 된다. 만약 설치할 경우 터미널에 아래와같이 입력한다.
```
npm install -g yarn
```

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/vscode.png" style="width: 20px;"/>&nbsp;&nbsp;VSCode 설치
:   <a href="https://code.visualstudio.com/"><small>홈페이지로 이동</small></a><br/>
홈페이지에서 설치파일을 다운받아 설치한다.

###### 터미널에서 바로 실행할 수 있도록 설정하는 방법
  1. VSCode 실행
  2. command + shift + p 누르기
  3. "shell" 검색
  4. 셀 명령: PATH에 'code' 명령 설치 선택
{: .notice}