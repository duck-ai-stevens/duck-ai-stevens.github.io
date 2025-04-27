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

![topic_banner](/_images/banner.jpg)

**Keynote Speakers**
<div class="home" style="font-size: 1em;">
    <ul class="responsive-table" style="margin-left: 0; border-bottom: 0.1em solid whitesmoke;">
        <li class="table-row">
            <div class="col col-2" data-label="Time">
                <div class="image--cover-container">
                    <img src="/_images/Shantenu.jpg" class="image--cover">
                </div>
            </div>
            <div class="col col-10" data-label="Description">
                <p><b><a href="https://radical.rutgers.edu/people/shantenu-jha">Dr. Shantenu Jha</a></b> | Rutgers University</p>
                <b>AI-Coupled HPC Workflow Applications: A New Paradigm for Extreme-Scale Scientific Applications</b>
                <div class="expandable-content collapsed">
                    <p>Extreme-scale computing is facing several significant inflection points. On one hand, computing trends challenge the scaling of large, monolithic tasks. On the other hand, scientific applications increasingly require seamless orchestration of diverse and heterogeneous tasks. In response, workflow applications integrating AI and traditional HPC are becoming more critical and poised to drive the next wave of “algorithmic Moore’s Law.” This presentation will discuss the primary modes (AI-x-HPC, where x = in, out, and about) and motifs (steered ensembles, online training, inverse design, etc.) for integrating AI and HPC tasks. It will motivate and discuss integrated AI-HPC workflow applications across various scientific domains and the efforts to advance the state of the art of these workflow applications on extreme-scale computing platforms.</p>
                    <p><b>Short Bio:</b> Shantenu is a professor of computer engineering at Rutgers University-New Brunswick, the head of computational sciences at the DOE's Princeton Plasma Lab, and concurrently a research scholar in computer science at Princeton University. His research interests lie in AI for science and are driven by the modest goal of achieving a 10 orders-of-magnitude increase in scientific performance in less than 10 years. He has received the NSF CAREER Award (2013), the ACM Gordon Bell Special Award (2020), and numerous other awards in supercomputing, and was the winner of IEEE SCALE 2018. In his ample spare time, he enjoys perfecting the art of being boring while obsessively reading dismal to abysmal science.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>  
        </li>
        <li class="table-row">
            <div class="col col-2" data-label="Time">
                <div class="image--cover-container">
                    <img src="/_images/lwu11.png" class="image--cover">
                </div>
            </div>
            <div class="col col-10" data-label="Description">
                <p><b><a href="https://sites.google.com/site/leiwupes/">Dr. Lei Wu</a></b> | Stevens Institute of Technology</p>
                <b>Leveraging Machine Learning for Boosting Performance of Power Systems Optimization Problems</b>
                <div class="expandable-content collapsed">
                    <p>With the growing scale and complexity of modern power grids, available data could provide useful information and insights into the underlying power grid, and machine learning methods could be valuable to help understand and reveal the relationship between system parameters and optimal operations, finally addressing optimal operation problems in a more efficient and accurate way. In this talk, we will discuss three examples to marriage the data-driven and machine learning methods to power systems optimization problems for improving computational performance, including: (i) a data-driven approach by leveraging historically solved unit commitment (UC) instances to promptly solve new UC problems; (ii) a closed-loop predict-and-optimize framework for deriving better forecasts that could lead to an enhanced UC solution quality; and (iii) an adaptive dynamic programming-based approach for conducting effective optimal schedules of energy-limited resources within a limited time horizon while considering their potential future values.</p>
                    <p><b>Short Bio: </b>Dr. Lei Wu is the Anson Wood Burchard Chair Professor of the ECE Department at Stevens Institute of Technology.  His current research involves optimization and statistical analysis applied to power system operations and electricity markets, the public policy and technical issues associated with electricity transmission and distribution under market restructuring, the economic implications of the integration of renewables, and the co-optimization of critical interdependent infrastructures.  He has a demonstrated track record in completing research and development projects funded by agencies such as the DOE and NSF, including funds from DOE, NSF, and NYSERDA on the design and development of community microgrids and distributed renewable resource integration, and on the operational flexibility of hydro resources.  He is a Fellow of IEEE.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>  
        </li>
        <li class="table-row">
            <div class="col col-2" data-label="Time">
                <div class="image--cover-container">
                    <img src="/_images/ShaoleiRen_full_2.jpg" class="image--cover">
                </div>
            </div>
            <div class="col col-10" data-label="Description">
                <p><b><a href="https://shaoleiren.github.io">Dr. Shaolei Ren</a></b> | University of California, Riverside</p>
                <b>AI, Energy, and Public Health</b>
                <div class="expandable-content collapsed">
                    <p>The energy sector is a major source of harmful air pollutants—such as fine particulate matter—that can travel long distances, penetrate deep into the lungs, and contribute to serious health conditions, including asthma, heart disease, and cancer. As a result, the rapid growth of artificial intelligence (AI) and energy-intensive data centers is contributing to a growing public health burden. Moreover, the use and maintenance of backup generators at data centers further degrade local air quality, compounding these health risks. Despite these challenges, AI also holds transformative potential to improve public health by, for example, enabling health-informed demand response and optimizing the allocation of healthcare resources. In this talk, I will explore the complex interconnections among AI, energy, and public health. I will introduce the concept of Health-Informed AI, which both mitigates the public health impacts of AI and harnesses AI to advance public health. Through this lens, I will outline pathways for aligning AI development with cleaner air and healthier communities.</p>
                    <p><b>Short Bio: </b>Shaolei Ren is an Associate Professor of Electrical and Computer Engineering at the University of California, Riverside. His research broadly focuses on AI, energy, and public health. His work has generated broader societal impacts, shaping AI policies adopted by international organizations such as the United Nations, UNESCO, and WHO. Additionally, his research has driven industry innovations, including the development of the first real-time water footprint reporting tool for computing. He is a recipient of the NSF CAREER Award (2015) and several paper awards, including at ACM e-Energy (2024, 2016) and IEEE ICC (2016). He received his Ph.D. from the University of California, Los Angeles.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>  
        </li>
        <!-- <li class="table-row">
            <div class="col col-2" data-label="Time">
                <div class="image--cover-container">
                    <img src="/_images/Anshumali-Shrivastava.jpg" class="image--cover">
                </div>
            </div>
            <div class="col col-10" data-label="Description">
                <p><b><a href="https://www.cs.rice.edu/~as143/">Dr. Anshumali Shrivastava</a></b> | Rice University</p>
                <b>TBD</b>
                <div class="expandable-content collapsed">
                    <p>TBD.</p>
                    <p>TBD.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>  
        </li> -->
    </ul>
</div>



**Organizers/Program Chairs:**

* [Jian Li](https://sites.google.com/stonybrook.edu/jianli) (Stony Brook University)
* [Hao Wang](https://intellisys.haow.us/haowang/) (Stevens Institute of Technology)
* [Devesh Tiwari](https://coe.northeastern.edu/people/tiwari-devesh/) (Northeastern University)
* [Jiawei (Joe) Zhou](https://joezhouai.com) (Stony Brook University)

**Important Dates:**
* ~~Submission deadline: April 1, 2025~~
* ~~Acceptance notification: April 15, 2025~~
* Final version: May 30, 2025
* PER Camera ready: June 30, 2025
* Workshop date: June 13, 2025
