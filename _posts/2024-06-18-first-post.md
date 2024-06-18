---
layout: post
title: First post
date: 2024-06-18 15:13 +0900
categories: [blog]
---

수업과 과제에 쫓기며 대학생활을 보냈더니 어느덧 4학년이 되어있었다. 내가 수강했던 수업 중 제대로 이해하지 못하고 넘어간 부분이 너무나 많기에, 빠졌던 부분을 채워넣고 지식을 아카이빙하는 용도로 블로그를 시작한다.

## github blog
USERNAME.github.io 형식 도메인의 블로그를 많이 보았는데, 자유도가 높은 것들 중 가장 진입장벽이 낮기에 해당 방식을 선택했다. 블로그는 사실 일방적인 정보게시이므로 BackEnd가 필요없어 빠르고 가벼운 SSG(Static Site Generator)을 이용할 것이다. 그 중에서 가장 많이 이용하는 Jekyll의 [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) 템플릿을 이용했다.  
윈도우로 열심히 튜토리얼 따라해보다가 열받아서 그냥 ubuntu로 진행한다. 편안~  
Jekyll이 Ruby로 작성되었기에 Ruby 설치해주고 어찌저찌 튜토리얼 따라서 만들었다.
## post
Chirpy에서 [새로운 포스트 작성하는 방법](https://chirpy.cotes.page/posts/write-a-new-post/#naming-and-path)에 대한 document가 있으나 직접 파일 생성하고 타임스탬프 찍기에는 귀찮으므로 [jekyll-compose](https://github.com/jekyll/jekyll-compose)라는 플러그인을 이용했다.  
root directory에서```bundle exec jekyll post 'postname'```실행해주면 잘 만들어진다.  
post는 .md(markdown) 이므로 markdown을 사용할 줄 알아야 한다. 예전에 obsidian으로 끄적거릴 때 써본 것이 전부라 [튜토리얼 사이트](https://www.markdowntutorial.com/kr/)에서 연습해보았다.  

블로그세팅끝! 1학년때 기억부터 끄집어내서 열심히 내용정리 해봐야겠다.