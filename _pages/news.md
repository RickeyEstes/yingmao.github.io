---
layout: page
permalink: /news/
title: News
description:
nav: true
rank: 2
---

{% assign sorted = site.news | sort: 'date' | reverse %}
{% for news in sorted %}
  <div class="post">
    <ul>
      <article>
        <li> {{ news.date | date: "%b %d, %Y" }} {{ news.content }}  </li>
      </article>
    </ul>  
    </div>    
{% endfor %}




- Mar. 15, 2020 <br>
`MAC-layer rate control for 802.11 networks` accepted by Springer Wireless Network.

- Dec. 18, 2019 <br>
`A woa-based optimization approach for task scheduling in cloud computing systems` was accepted by IEEE Systems Journal.

- Oct. 10, 2019 <br>
`Progress-based Container Scheduling for Short-lived Applications in a Kubernetes Cluster` authored with Fordham Students has been accepted to IEEE Big Data 2019. Congratulations to Yuqi Fu, Shaolun Zhang, and Jose Terrero.

- Jul. 2, 2019 <br>
`Target-based Resource Allocation for Deep Learning Applications in a Multi-tenancy System` authored with Fordham Students has been accepted to IEEE HPEC 2019. Congratulations to Wenjia Zheng, Yun Song, Zihao Guo, Yongcheng Cui and Suwen Gu.

- May 23, 2019 <br>
`FlowCon: Elastic Flow Configuration for Containerized Deep Learning Applications` authored with Fordham Students has been accepted to IEEE ICPP 2019. Congratulations to Wenjia Zheng, Mike Tynes and Henry Gorelick.`

- May 12 2019 <br>
`One paper has been accepted to IEEE SmartData 2019`

- Apr. 15, 2019 <br>
`One paper has been accepted to IEEE SECON 2019`

- Apr. 10, 2019 <br>
`I have been awarded Fordham Faculty Research Grant.`

- Jan. 06, 2019 <br>
 `I have been awarded Google Cloud Education Grant`

- Nov. 15, 2018 <br>
`I have been selected as the Fordham-IBM Research Fellow.`

- Oct. 10, 2018 <br>
`I have been awarded the Nvidia GPU Seed Grant.`

- Aug. 28, 2018 <br>
`New start at Fordham.`


---
