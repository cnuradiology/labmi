---
excerpt: "Publications"
permalink: publications/
classes: wide
years: [2024,2023,2022,2021,2020,2019,2018,2017,2016, 2015,2014,2013, 2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002]
---

<style>
.centeralign {
  text-align: center;
  color:#1F416F;
  font-weight: bold;
}
.centeralign2 {
  color:#1F416F;
  font-weight: bold;
}
</style>


<h6 class="centeralign2"> Submitted / in preparation </h6>
<ol type="1" class="text-justify"> <small>
<li>Binh D. Le, Kyung-Jin Oh, Anh T. Le, Long Hoang, Ilwoo Park (preprint). Investigation and quantification of composition variability in urinary stone analysis. Investigative and Clinical Urology</li>
<li>Le Thanh Quang, Byung Hyun Baek, Woong Yoon, Seul Kee Kim, Ilwoo Park (in preparation). Comparison of Normalization Techniques for Radiomics Features from Magnetic Resonance Imaging in Predicting Histologic Grade of Meningiomas </li>
</small>
</ol>   


{% for y in page.years %}
  {% bibliography -f references -q @*[year={{y}}]* %}
{% endfor %}
[//]:  <h6 id="{{y}}" class="pubyear"><div class="centeralign2">{{y}}</div></h6>