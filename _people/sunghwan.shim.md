---
layout: page
title: Sunghwan Shim (심성환)
excerpt: "Sunghwan Shim's website"
---

{%- assign person_id = "sunghwan.shim" %}
{%- assign person = site.data.people | where:"id",person_id | sample %}

I am an **Undergraduate Student at [Hanyang university,  Departnmet of Computer Science & Enginerring](http://cs.hanyang.ac.kr)**. I am delighted to be advised by [Prof. Jeehoon Kang]({{ site.baseurl }}{% include person_url.md person_id="jeehoon.kang" %}).

I am interested in verifying concurrent and parallel systems. In particular, I want to solve various real-world problems associated with these topics. I believe these studies will help


{% include person_contact.md person_id=person_id %}


{% include person_education.md person_id=person_id %}


#### Experiences

- Backend developer, Team Dotout, March, 2017 - April, 2018
  (topic: live streaming service with enhanced user-streamer interaction)
