---
permalink: /
title: "About me"
author_profile: true
modified: 2024-07-23
redirect_from: 
  - /about/
  - /about.html
---
Hello! My name is Haisong Gong from Yichun, Jiangxi province. I am currently a Ph.D. candidate specializing in the field of Artificial Intelligence. My research focuses on _applications of large language models_ and tasks such as _misinformation detection_, _hallucination detection_, and _fact verification_. Additionally, I have a keen interest in _small molecule generation_. If you are interested in academic collaboration, please feel free to contact me at <a href="mailto:gonghaisong2021@ia.ac.cn">gonghaisong2021@ia.ac.cn</a>.

I graduated in 2021 with a Bachelor's degree in Automation from the School of Electronics and Information Engineering at Tongji University, where I ranked first in my major. Following my undergraduate studies, I was directly admitted to pursue a Ph.D. at the Institute of Automation, Chinese Academy of Sciences, under the supervision of [Liang Wang](http://www.ia.cas.cn/rcdw/yjy/202404/t20240422_7129880.html), [Shu Wu](http://www.ia.cas.cn/rcdw/fyjy/202404/t20240422_7129885.html), and [Qiang Liu](http://www.ia.cas.cn/rcdw/fyjy/202404/t20240422_7129892.html).

## 📚 Publications
{% assign sorted_publications = site.publications | sort: 'date' | reverse %}  
<ul>  
    {% for post in sorted_publications %}  
    {% include singleitem.html %}
    {% endfor %}  
</ul>  

See more details (codes, abstracts, pdf resources) in [Publications]({{site.url | append: "/publications"}})

<!-- ## Honors -->
<!-- ## Skills -->