---
title: 정형외과 사용 설명서
permalink: /docs/home/
redirect_from: /docs/index.html
---

## 시작하기

실제 병원을 찾기까지 많은 고민을 하게됩니다.   
그리고 병원을 찾게되면 무슨 말을 어디부터 어디까지 이야기 해야할지, 큰 보따리를 짧은 시간에 말씀하시게 되는 경우가 있습니다.   
물론 말씀은 많이 하셨는데 진료실을 나서면서 이런 이야기는 괜히 했고, 저런 이야기를 미처 못했다는 아쉬움이 남는 경험을 할 수도 있습니다.   

세상을 사는 방법이 다 비슷하듯이, 내가 원하는 '좋은 대답'이나 해답을 찾기 위해서는 역시 '좋은 질문'이 중요합니다.   

 뭐 굳이 준비 안하셔도 되지만 ':)' 간단한 질문 요령부터 말씀드리겠습니다.   
 (정말 준비 안하셔도 됩니다. 선생님들이 다 알아서 해주시니까요. 그래도 뭔가 원활한 진료를 원한다하시면 참고해 주십시오.)   


1. 어디가 아프거나 불편한지.
   - 통증 부위
   - 그 부위의 (앞쪽 / 안쪽 / 바깥쪽 / 뒷쪽) 위치
   - 어떤 때 아픈지 (유발되는 자세 또는 행동) : ex) 걸을 때, 굽힐 때, 혹은 가만히 있어도 아프다.

2. 언제부터 아픈지.
   - 몇 주 혹은 몇 일 전 부터 아프다.
   - '(대략적으로) 몇 년 전부터 아프다.'도 좋습니다.
   - 다쳐서 아픈 것인지, 그냥 아파진 것인지   

이렇게 크게 두 가지 정보만 말씀해 주셔도 진료 상에 더 필요한 정보는 필요 없을 정도입니다. 정말 간단한 정보지만 대개 오랫동안 불편감을 겪어 오셨기 때문에 그동안의 고생을 짧은 시간 안에 표현하고싶은 경우가 많은 것 같습니다. 하지만 진료를 더 깊고 자세히 이어나가고자 하는 경우에는 위의 두 가지를 필수로 말씀 주셔야 합니다. '좀 됐어요. 자세히는 몰라요.'라고 하셔도 의사들은 집요하게 기간을 되물을 수 밖에 없습니다. 중요하기 때문입니다.    

## Writing content

### Docs

Docs are [collections](https://jekyllrb.com/docs/collections/) of pages stored under `_docs` folder. To create a new page:

**1.** Create a new Markdown as `_docs/my-page.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: My Page
permalink: /docs/my-page/
---

Hello World!
```

**2.** Add the pagename to `_data/docs.yml` file in order to list in docs navigation panel:

```
- title: My Group Title
  docs:
  - my-page
```

### Blog posts

Add a new Markdown file such as `2017-05-09-my-post.md` and write the content similar to other post examples.

### Pages

The home page is located under `index.html` file. You can change the content or design completely different welcome page for your taste. (You can use [bootstrap componenets](http://getbootstrap.com/components/))

In order to add a new page, create a new html or markdown file under root directory and link it in `_includes/topnav.html`.
