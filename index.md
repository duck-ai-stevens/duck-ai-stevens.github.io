---
layout: home
---
<script>
function toggleContent(button) {
    const content = button.previousElementSibling;
    content.classList.toggle('collapsed');
    if (content.classList.contains('collapsed')) {
        button.textContent = 'More';
    } else {
        button.textContent = 'Less';
    }
}
</script>

<!-- Add this CSS to control appearance -->
<style>
.expandable-content {
    max-height: 7em; /* Adjust how much you want to initially show */
    overflow: hidden;
    position: relative;
    transition: max-height 0.3s ease;
}

.expandable-content.collapsed {
    max-height: 3.2em;
}

.expandable-content:not(.collapsed) {
    max-height: 1000em; /* Expand fully */
}

.expand-btn {
    margin-top: 0.5em;
    padding: 0.4em 0.8em;
    font-size: 0.9em;
    background-color: #eee;
    border: 1px solid #ccc;
    cursor: pointer;
    border-radius: 5px;
}
</style>

<!-- ![topic_banner](/_images/banner.jpg) -->

The 1st iCNS/ECE Symposium on AI Research and Innovations (DuckAI 2025) is a one-day event organized by the Center for Innovative Computing and Networked Systems (iCNS) and the Department of Electrical and Computer Engineering at Stevens. It aims to bring together industry partners, researchers, faculty, and students to discuss recent developments of AI techniques and applications. The event features two technical sessions with invited talks and one poster & demo session. Around 30 student teams will showcase their AI projects for Spring’25. This event is open to the public with free registration.


## Event Details

* Thursday, May 15, 2025
* 8:30 a.m. – 3:00 p.m.
* **Burchard 111**, Stevens Institute of Technology

<!-- 

## Agenda

* 8:30 AM - Check in
* 9:15 AM - Opening Remarks by ECE Department Chair: Dr. Min Song
* 9:30 AM - Invited Talk Session 1 - Host: Dr. Hao Wang
* 10:20 AM - Coffee Break
* 10:40 AM - Invited Talk Session 2 - Host: Dr. Shucheng Yu
* 11:30 AM - Lunch
* 1:00 PM - Student Project Poster & Demo
* 2:30 PM - Award announcement
* 3:00 PM - Adjourn -->

Registration link: [https://forms.gle/iPaCFxUheVo6YdGZ7](https://forms.gle/iPaCFxUheVo6YdGZ7)


**Keynote Speakers**
<div class="home" style="font-size: 1em;">
    <ul class="responsive-table" style="margin-left: 0; border-bottom: 0.1em solid whitesmoke;">
        <li class="table-row">
            <div class="col-12 col-md-12">
                <div class="image--cover-container">
                    <img src="" class="image--cover">
                </div>
            </div>
            <div class="col-12 col-md-12">
                <p><b><a href="">Santosh Borse</a></b> | IBM </p>
                <b>TBD</b>
                <div class="expandable-content collapsed">
                    <p>TBD.</p>
                    <p><b>Short Bio:</b> TBD.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>  
        </li>
        <li class="table-row">
            <div class="col-12 col-md-12">
                <div class="image--cover-container">
                    <img src="" class="image--cover">
                </div>
            </div>
            <div class="col-12 col-md-12">
                <p><b><a href="">Zengye Wang</a></b> | Armistice Capital LLC </p>
                <b>TBD</b>
                <div class="expandable-content collapsed">
                    <p>TBD.</p>
                    <p><b>Short Bio:</b> TBD.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>  
        </li>
        
    </ul>
</div>


## Organizers:

* [Shucheng Yu](https://www.stevens.edu/profile/syu19) (ECE@Stevens Institute of Technology)
* [Hao Wang](https://intellisys.haow.us/haowang/) (ECE@Stevens Institute of Technology)
 
<!-- 
**Important Dates:**
* ~~Submission deadline: April 1, 2025~~
* ~~Acceptance notification: April 15, 2025~~
* Final version: May 30, 2025
* PER Camera ready: June 30, 2025
* Workshop date: June 13, 2025 -->
