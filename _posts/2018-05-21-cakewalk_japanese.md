---
layout: post
title: "[전자책제작후기]일본어 무작정 따라하기"
date: 2018-05-21T10:08:35+00:00
description: 일본어 무작정 따라하기 전자책 제작 후기입니다.
image: http://bookimg.gilbut.co.kr/book/BN000972/rn_zoom_BN000972.jpg
category: '전자책세미나_강의'
  
tags: 
  - ebook
  - epub
  - 일무따
  - 일본어 무작정 따라하기
  - 전자책
  - 후지이 아사리
twitter_text: '[전자책제작후기]일본어 무작정 따라하기'
introduction: '하지만, 제작에 들어갔을 때 의외의 복병이 있었으니... 그건 바로, 억양 표시였습니다.'
---

<https://youtu.be/TUg8r0ZEX5M>

지금으로부터 4년 전이 2014년에 우연치 않게 이 책을 맡게 되었습니다. 당시에는 어학서 전자책 담당자가 아니었지만, 해당 담당자가 일에 치이는 관계로 임시로 제가 맡게 된 책이었습니다. 당시를 돌이켜 보면 ePub3가 거의 통영되지 않은 상황에서 MP3 파일 재생 기능만 넣던 시기였습니다. 그래서, 이왕 맡은 김에 자바스크립트로 정답 확인 기능을 간단하게 구현하자는 목표를 잡았었습니다.

하지만, 제작에 들어갔을 때 의외의 복병이 있었으니&#8230; 그건 바로, 억양 표시였습니다.

영어 학습서들에 들어 있는 회화의 억양표시는 많이 보셨을 겁니다. 이 책 역시 현지 일본인들이 어떻게 발음하는지 알 수 있도록 억양에 대한 설명 부분이 있었습니다. 보통 이런 경우는 해당 텍스트와 억양 표시를 이미지로 따서 넣는 경우가 많습니다. 하지만, 이렇게 할 경우에는 이미지의 해상도가 낮아 가독 편의성에 영향을 줄 여지가 있습니다. 지금도 어학서 뿐만 아니라 수학 관련 도서를 ePub으로 만들 때 난해한 점들이 바로 이런 텍스트를 이미지로 처리해야 하는 경우가 아닐까 싶습니다.

이런 저런 방법을 고려하다가 좀&#8230; 무식하고 잔인한(?) 방법을 썼습니다. CSS의 border 속성을 이용해서 억양 선을 구성하는 여러 선(왼쪽 선, 오른쪽 선, 위 연결선, 아래 연결선 등)의 조합으로 억양을 표기하기로 한 겁니다.

<img src="https://i0.wp.com/is1-ssl.mzstatic.com/image/thumb/Purple5/v4/40/fe/dd/40fedd1d-5ad0-8cf7-16be-eed3c4310c1d/source/480x360bb.jpg?w=900&#038;ssl=1" alt="억양 표시" data-recalc-dims="1" />

스크린샷에 보이는 빨간 선들이 바로 CSS를 이용한 결과물입니다. 말과 이론은 쉬운데&#8230; 이걸 구현하려면 일일이 일본어 문장과 단어 사이에 span 태그로 각각의 억양 부속 속성들을 넣어주어야 했습니다. 디자인 초안을 했던 저도 시간과 노력(눈이 빠질 정도&#8230;)이 꽤 들어갔으니, 이어서 작업했던 분들은 오죽했을까요. 그 분들의 노력 덕에 완성은 할 수 있었습니다. 그리고, 현재 이 책은 4년이 지난 지금도 어학서 전자책의 주력 매출을 구성하는 책이 되었습니다. 본래 유명 저자 선생님의 베스트셀러였던 덕이었고, 담당했던 저로서는 당시에 좀 무리가 되어도 해보자라는 마음이 충만했던 시기였습니다.(지금은 좀 무리가 아닐지&#8230;^^;)

그래도, 이런 어려운 과제를 하고 나면 개인적으로는 큰 성취감을 얻을 수 있습니다. 그리고, 회사적으로도 차후 비슷한 도서 제작을 위한 일종의 CSS 자료를 가지게 된 셈이기도 하고요.
  
저는 가끔 매너리즘이 오는 걸 느낄때 초기에 작업했던 도서들을 돌아보곤 합니다. 지금 기준으로 보면 허술한 부분도 꽤 있지만, 그러한 것들이 쌓이고 쌓여서 이제는 조금 쉽게 일을 할 수 있게 되었다는 걸 느끼게 해주니까요.10년 정도 더 일하고 지금을 돌아보면 여전히 그런 감성을 느낄 수 있을지는 모르겠지만, 자신이 도전해서 얻은 결과들을 돌아보는 건 감회가 새롭지 않을까 싶습니다.