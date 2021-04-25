---
layout: layouts/post.njk
title: BMW | Detail
thumbnail: /static/images/project-1-logo.jpg
tags: posts
wallpaper: /static/images/bmw.jpg

testimony:
  quote:  Technology gives us the technical foundation we need to create helpful tools, using technology to create cars was the man's greatest use of that tool.
  cite: Mervin DuLocke
  occupation: Chief executer officer

chapter:
  heading_1: BMW
  content_1: BMW  is a German multinational corporation which produces luxury vehicles and motorcycles. Their high range in automobiles ensures the success of this large company. The company might've been founded in Germany but is nowadays appreciated in somewhat each country.
  heading_2: some.png
  content_2: If you delve into BMW’s history, you will notice that the BMW logo  has been an essential element in all of its advertising campaigns. The logomark was first used as a symbol of recognition and differentiation in 1917 – years before the BMW aircraft engine manufacturer  would bring its first vehicles to market. But at that point, the company was still a long way away from a brand claim and wordmark.
  heading_3: A highly interactive webpage
  content_3: Automated driving, electro-mobility, on-demand mobility and connectivity-mobility have never been so fascinating, and automobile advancement never so exciting and promising as it is today. BMW would like to create a platform that brings you closer to this fascination and the latest technological trends. 
  heading_4: tyuiopuyà
  content_4: Our client was in need of a highly interactive webpage. When reaching out to us we did not hesitate one bit and were keen to offer our services to the high-end automobile company. We Used mainly Javascript to provide interaction on the page. 
  
technology:
  name: Javascript
  image: /static/images/javascript2.jpg

client:
  name: BMW
  synopsis: Who are they ?
  logo: /static/images/bmw-logo.jpg
  link: https://www.bmw.com/en/index.html
  request: A highly interactive webpage
  
---
<div class="technology__container">
    <div class="technology__wrapper">
        <div class="technology__wrapper--first">
        <h2>{{chapter.heading_3}}</h2>
        <p>{{chapter.content_4}}</p>
        </div>
        <div class="technology__wrapper--second">
        <img src="{{technology.image | url}} ">
        <h2>{{technology.name}}</h2>
        </div>
    </div>
</div>