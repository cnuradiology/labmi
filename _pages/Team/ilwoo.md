---
excerpt: "About Ilwoo Park"
permalink: /team/ilwoo
classes: wide
---
<style> 
.teamImage{
    width: 300px;
    height: 300px;
    object-fit: cover;
    border-radius: 50%;
    display: block;
    margin-left: auto;
    margin-right: auto;
} 

.centeralign {
  text-align: center;
}
#boxcolor {
  background-color: #1F416F ;
  padding: 50px;
    border-radius: 20px;
} 
.white {
  color: white;
}
.centeralign2 {
  font-weight: bold;
  color: white;
}
.leftpadding {
  padding-left: 10px
}
</style>



{% for member in site.data.team_members %}
{% if member.name == "Prof. Ilwoo Park" %}
<div id="boxcolor">
<div class="row">
    <div class="col-md-6">
        <h3 class="centeralign2">{{member.name }}</h3> 
        <p class="white leftpadding"><b>{{member.title}}</b> <br>
          <i class="fas fa-fw fa-phone-square-alt" aria-hidden="true"></i>
          {{member.fon}}<br>
          {% if member.secretary %}
            <i class="fas fa-fw fa-phone-square-alt" aria-hidden="true"></i>
            {{member.secretary}}<br>
          {% endif %}
          <i class="fas fa-fw fa-house-user" aria-hidden="true"></i>
          {{member.office}}<br>
          <i class="fas fa-fw fa-mail-bulk" aria-hidden="true"></i>
          {{member.mail}}
        </p>
    </div>
    <div class="col-md-6">
        <div class="mask">
        <img src="../assets/images/teampic/{{ member.photo }}" width="25%" class="image teamImage">
        </div>
    </div>
</div>
</div>
<br>
<div>
    <b> Research Interests:</b>
    <br>
    {{member.research_interests}}
</div>

{% endif %}
{% endfor %}