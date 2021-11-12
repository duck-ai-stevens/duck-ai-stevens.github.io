---
layout: page
title: About
permalink: /about/
---



  <div>
        <div style="width:100%;">
            <!-- <h2>Instructors</h2> -->
            <!-- <div class="image--cover-container">
                <img src="{{site.data.people.instructor.profile_pic | prepend: site.baseurl }}" class="image--cover">
                <p>{{site.data.people.instructor.name}}</p>
            </div> -->

            <div class="profile-pic-gallary ">
                <h2>Faculties</h2>
                {% for ins in site.data.people.instructors %}
                <div class="image--cover-container">
                    <img src="{{ins.profile_pic | prepend: site.baseurl }}" class="image--cover">
                    {% if ins.webpage %}
                    <p><a href="{{ ins.webpage }}">{{ins.name}}</a></p>
                    {% else %}
                    <p>{{ins.name}}</p>
                    {% endif %}
                </div>
                {% endfor %}
            </div>
        </div>

        <div style="width:100%; float: left">
            <div class="profile-pic-gallary ">
                <h2>Students</h2>
                {% for ta in site.data.people.teaching_assistants %}
                <div class="image--cover-container">
                    <img src="{{ta.profile_pic | prepend: site.baseurl }}" class="image--cover">
                    {% if ta.webpage %}
                    <p><a href="{{ ta.webpage }}">{{ta.name}}</a></p>
                    {% else %}
                    <p>{{ta.name}}</p>
                    {% endif %}
                </div>
                {% endfor %}
            </div>
        </div>

        <div style="width:100%; float: left">
            <div class="profile-pic-gallary ">
                <h2>Website Admin</h2>
                <div class="image--cover-container">
                    <img src="/_images/pp/honglu.jpeg" class="image--cover">
                    <p>Honglu Li <a href="mailto:hli67@lsu.edu">hli67@lsu.edu</a></p>
                </div>
            </div>
        </div>

    </div>
