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
    * The poster session will be at the lab underneath the library

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


## Keynote Speakers
<div class="home" style="font-size: 1em;">
    <ul class="responsive-table" style="margin-left: 0; border-bottom: 0.1em solid whitesmoke;">
        <li class="table-row">
            <div class="col-12 col-md-12">
                <div class="image--cover-container">
                    <img src="_images/google.jpg" class="image--cover">
                </div>
            </div>
            <div class="col-12 col-md-12">
                <p><b><a href="">Josh Gordon, Yufeng Guo</a></b> | Google </p>
                <b>Google's AI tools for Developers</b>
                <div class="expandable-content collapsed">
                    <p>Join this session to learn how to get started with Google's latest AI tools and models, including Gemini, Gemma, JAX, and Keras. We'll cover the latest models, and how to get started.</p>
                    <p><b>Short Bio:</b> Josh leads AI Developer Relations at Google (fun fact, a groupJosh founded back in 2015). Josh also is an adjunct professor at Columbia, whereJosh occasionally teach classes on deep learning. Josh has extensive experience across many areas of AI---from classical methods, to deep learning, to the latest in generative AI---as well as applications across many fields. Josh wears many hats at Google, and have management and leadership experience.</p>
                    <p>Yufeng Guo is a Developer Advocate at Google, specializing in Cloud AI. He is dedicated to making machine learning more understandable and usable for all. Yufeng is the creator of the YouTube series “AI Adventures,” which explores the art, science, and tools of machine learning.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>  
        </li>
        <li class="table-row">
            <div class="col-12 col-md-12">
                <div class="image--cover-container">
                    <img src="_images/SantoshBorse.jpeg" class="image--cover">
                </div>
            </div>
            <div class="col-12 col-md-12">
                <p><b><a href="https://medium.com/@sanborse">Santosh Borse</a></b> | IBM </p>
                <b>Preparing data for LLM pre training and post training</b>
                <div class="expandable-content collapsed">
                    <p>Data Prep Kit ( https://github.com/data-prep-kit/data-prep-kit ) is built to support both structured and unstructured data across diverse domains, It enables development team to focus on model development by reducing the time and effort required for data preprocessing. Santosh will take your though the challenges in pre training data and how DPK is used to solve those challenges. Data Prep Kit is a open source project, Santosh will also go through the open source contribution opportunities for participants.</p>
                    <p><b>Short Bio: </b>Santosh Borse is an experienced software engineer with 20 years of expertise in designing, developing, and managing complex software systems. He currently works as a <b>Senior Research Engineer @ IBM Research</b>, where he focuses on preparing and processing data for training the IBM Granite series models. Throughout his career, Santosh has held roles ranging from Junior Developer to Architect, contributing to impactful projects across AI, NLP, IoT, cloud computing, and more. He is also a named inventor on several granted patents in emerging technologies. Driven by a passion for problem-solving and innovation, Santosh believes in <b>making the world a better place through software</b>—a principle that continues to guide his work every day.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>  
        </li>
        <li class="table-row">
            <div class="col-12 col-md-12">
                <div class="image--cover-container">
                    <img src="_images/zengye.jpeg" class="image--cover">
                </div>
            </div>
            <div class="col-12 col-md-12">
                <p><b><a href="">Zengye Wang</a></b> | Armistice Capital LLC </p>
                <b>Data Engineering in Hedge Funds: Managing Data at Scale for Finance</b>
                <div class="expandable-content collapsed">
                    <p>This talk highlights the role of data engineering in the fast-paced environment of hedge funds. It covers how engineers design and maintain scalable data pipelines, ensure data quality and integrity, and support a wide range of teams from research to compliance. Learn how modern data infrastructure enables better decision-making in the financial industry.</p>
                    <p><b>Short Bio:</b> Zengye is a full stack quantitative engineer---frontend, backend, site reliability, distributed computing, model implementation. He previously worked at multiple hedge funds and is experienced with production systems.</p> 
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
