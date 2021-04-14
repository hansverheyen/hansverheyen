---
layout: default
---
<div class="project-wrapper">
    {% for project in site.portfolio %}
    {% if project.class =='wk' %}
    <div class="project-linkerkant">
        <div class="title">
            <h1>{{page.title}}</h1>
            <p>{{page.keywords}}<p></p>
        </div>
        <div class="beschrijving"> 
            <p>{{content}}</p>
         

        </div> 
    </div>
        <div class="project-img">
            
            <div class="ofm">
                <div class="pic"><img src="{{site.baseurl}}{{page.img1}}"  alt=""></div>
                <div class="pic"><img src="{{site.baseurl}}{{page.img2}}"  alt=""></div>
                <div class="pic"><img src="{{site.baseurl}}{{page.img3}}"  alt=""></div>
                
            </div>
        </div>  
        {% endif %}
        {% endfor %}
</div>