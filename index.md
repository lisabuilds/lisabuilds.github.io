---
layout: default
---

<div class="hero">
    <div class="hero-content">
       <div class="intro-text">
       <h1>Hi, I'm <span class="highlight">Lisa</span>
                <div class="profile-image">
                    <img src="{{ '/assets/images/profile.jpeg' | relative_url }}" alt="Lisa Zhang" />
                </div>
            </h1>
            

            <div class="tech-stack">
            <span class="tag">AI interpretablity</span>
            <span class="tag">Agentic Workflows</span>
            <span class="tag">Distributed Training</span>
            <span class="tag">RL</span>
        </div>
            <div class="bio">
                <p>I'm an AI Engineer specializing in LLMs and RL. Currently, I work on building distributed autonomous agents systems at Travelers. Previously, I founded NearMeNow, where I led a team of engineers in developing a real-time, scalable web app to connect people with their nearby social activities.</p>
                
                <p>What I am doing when I'm free? I like to spend time experimenting new tech advances in LLM fiekds. I currently play around setting up RL environment to try a few techniques for complex rewarding models.</p>

                <p>I'm particularly passionate about AI interpretablity, distributed training, and Reinforcement Learning With Human Feedback in the loop. When I'm not coding, you can find me trying out new things in the feild ...
                </p>
            </div>
                        <div class="cta-links">
                <a href="{{ '/about' | relative_url }}" class="cta-link">More About Me →</a>
            </div>
            </div>
     
    </div>

</div>


<div class="container">
    <div class="section-header">
        <h2>Projects Overview</h2>
        <a href="{{ '/projects' | relative_url }}" class="view-all">View All Projects →</a>
    </div>
    
    <div class="projects">
        <div class="project-card">
            <h3>LLaMA-3 Fine-tuning with RLHF</h3>
            <p>Enhanced underwriting accuracy by 30% through distributed fine-tuning of LLaMA-3-70B using reinforcement learning from human feedback.</p>
        </div>

        <div class="project-card">
            <h3>Multi-Agent Processing System</h3>
            <p>Built a distributed multi-agent system orchestrated by Kafka to automate risk assessments and quote generation, processing over 10,000 submissions weekly in near real-time.</p>
        </div>
    </div>
</div>