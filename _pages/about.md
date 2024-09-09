---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a fourth-year undergraduate student majoring in Computer Science and Mathematics at NYU. I'm currently working with [Prof. Lerrel Pinto](https://www.lerrelpinto.com) in the Generalizable Robotics and AI Lab (GRAIL). 

I am interested in developing algorithms for learning generalizable policies and in scaling robot learning to the real-world. 

# Research
<div class="content">
    <video class="video" width="250" muted autoplay playsinline loop>
        <source src="files/vqbet.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <div class="text-container">
        <h3>Behavior Generation with Latent Actions</h3>
        <p style="font-size: smaller; font-style: italic; color: red;">Spotlight (3.5%)  <span style="font-style: italic; color: grey;">@ International Conference of Machine Learning (ICML) 2024</span></p>
        <p>Seungjae Lee, Yibin Wang, <b>Haritheja Etukuru</b>, H. Jin Kim, Nur Muhammad Mahi Shafiullah*, Lerrel Pinto*</p>
        <div>
            <a href="https://arxiv.org/abs/2403.03181" class="button">Paper</a>
            <a href="https://github.com/jayLEE0301/vq_bet_official" class="button">Code</a>
            <a href="https://sjlee.cc/vq-bet/" class="button">Project Site</a>
        </div>
    </div>
</div>

<div class="content">
    <video class="video" width="250" muted autoplay playsinline loop>
        <source src="files/dobb-e-thumbnail.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <div class="text-container">
        <h3>On Bringing Robots Home</h3>
        <p style="font-size: smaller; font-style: italic; color: red;">Best Demo Finalist <span style="font-style: italic; color: grey;">@ International Conference in Robotics and Automation (ICRA) EXPO 2024</span></p>
        <p>Nur Muhammad (Mahi) Shafiullah*, Anant Rai*, <b>Haritheja Etukuru</b>, Yiqian Liu, Ishan Misra, Soumith Chintala, Lerrel Pinto</p>
        <div class="button-container">
            <a href="https://arxiv.org/abs/2311.16098" class="button">Paper</a>
            <a href="https://github.com/notmahi/dobb-e" class="button">Code</a>
            <a href="https://dobb-e.com" class="button">Project Site</a>
        </div>
    </div>
</div>

<style>
    .content {
        display: flex;
        align-items: flex-start;
        flex-direction: row;
        margin-top: 0; /* Remove extra margin on top */
    }

    .video {
        align-self: center; /* Align video vertically with text */
    }

    .text-container {
        margin-left: 20px;
        margin-top: 0; /* Remove margin-top to reduce space above the text */
    }

    .button-container {
        margin-top: 10px; /* Add space between text and buttons */
    }

    .button {
        padding: 8px 12px;
        background-color: #e0e0e0;
        text-decoration: none;
        margin-right: 5px;
        border-radius: 3px;
        margin-bottom: 10px; /* Add space below each button */
    }

    /* For smaller screens or portrait mode */
    @media (max-width: 600px), (orientation: portrait) {
        .content {
            flex-direction: column;
            align-items: center;
        }

        .video {
            margin-top: 10px;
            margin-bottom: 0px; /* Add more space below the video in portrait */
            width: 300px;
        }

        .text-container {
            margin-left: 0;
            margin-top: 0px;
            margin-bottom: 50px; /* Add extra space below the text container */
        }

        .button-container {
            margin-top: 20px; /* Add more space between text and buttons */
        }
    }
</style>
