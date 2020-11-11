---
layout: page
title: Sunghwan Shim (심성환)
excerpt: "Sunghwan Shim's website"
---

{%- assign person_id = "sunghwan.shim" %}
{%- assign person = site.data.people | where:"id",person_id | sample %}

<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.baseurl}}/assets/chunmyong.park.jpeg" alt="{{ person.name }}">

I am an **Undergraduate Student at []({{ site.url }}), [Hanyang university,  Departnmet of Computer Science & Enginerring](http://cs.hanyang.ac.kr)**. I am delighted to be advised by [Prof. Jeehoon Kang]({{ site.baseurl }}{% include person_url.md person_id="jeehoon.kang" %}).

I am interested in verifying concurrent and parallel systems. In particular, I want to solve various real-world problems associated with these topics. I believe these studies will help 


{% include person_contact.md person_id=person_id %}


{% include person_education.md person_id=person_id %}


#### Experiences

- Intern, KakaoBrain, July, 2019 - August, 2019.

  (topic: Implement python library using PyTorch)

- Intern, DeepBio, January, 2018 - February, 2018.

  (topic: Research deep learning issues)

- Research Assistant, Deep Learning Lab (DLLAB), Handong Global University, March, 2017 – June, 2019.

  (director: Prof. Injung Kim)

  (topic: Implement deep learning library using C/C++)


#### Publications

The full list of the publications can be found at [Google Scholar]({{ person.google_scholar }}); more information at my [Curriculum Vitae](https://cmpark0126.github.io/assets/docs/PARKCHUNMYONG_cv.pdf).
