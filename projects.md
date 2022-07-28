---
layout: page
title: Projects
sidebar_link: true
sidebar_sort_order: 2
---

_Click title link for more info about each project!_

<details>
  <summary><h2 class="project-title">Socialyze: Friendship Discovery</h2></summary>

  <p>Socialyze is a web-based social media platform for MIT students to connect with each other, while providing a forum for students to discover events and other group activities on campus.</p>

  <ul>
    <li>Curated seamless user experience using functional <b>CSS animations</b> and the Chakra UI component library (<b>React.js</b>).</li>
    <li>Designed robust backend in <b>Node.js</b> <b>(MongoDB and Next.js)</b>, using <b>GraphQL</b> APIs for relevant database access. Hosted unsupervised ML-based recommendation system on this backend to find ideal matches for our users based on previous activity.</li>
    <li>Built real-time messaging system from scratch with individual and group message capabilities <b>(Express.js, Socket.io)</b>.</li>
  </ul>

</details>

<div class="video-container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/VRR51J8598w" title="Socialyze: Discover Your Interests" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


---

<details>
  <summary><h2 class="project-title">Tango: AI Dance Coach</h2></summary>

  <p>Tango is a computer-vision powered dance coaching software that provides users with live feedback and summary metrics for any dance that they would like to learn. Users are able to upload a video of our choosing, which they can then follow along and learn with our live annotations! </p>

  <ul>
    <li>Implemented <b>MediaPipe</b>'s Pose Estimation algorithm to track users' limbs using their laptop webcam. </li>
    <li>Processed uploaded video using MediaPipe and drew live annotations on these videos using <b>OpenCV</b>, tracking the positions of each of the performers' limbs and superimposing them onto our user's body.</li>
    <li>Used dynamic time warping over a sliding window to find the similarity between limb angles over time, estimating accuracy scores <b>(Python, FastAPI)</b></li>
    <li>Developed UI to guide users through the process of uploading, dancing, and learning their results <b>(React.js, Chakra UI)</b></li>
  </ul>

</details>

<div class="video-container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/8-6WGpPql-4" title="Tango Demo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

---

<details>
  <summary><h2 class="project-title">AI-Powered Gesture Interface For Automobile Control</h2></summary>

  <p>Noticing the rapid innovations being worked on in the field of human-computer interfaces for personal vehicles, as well as the need for an accessible and solution, our team of 5 developed an interconnected embedded system to prototype a car interface controlled primarily through the use of computer vision and hand gestures.</p>

  <ul>
    <li>Utilized the ESP32 microcontroller’s HC-06 Bluetooth and WiFi capabilities (coded using <b>C++</b> and the <b>Arduino</b> framework)</li>
    <li>Developed a backend computer vision algorithm to detect hand gestures from still Arducam images (developed with <b>OpenCV</b> in <b>Python</b>)</li>
    <li>Integrated several pieces of crucial hardware such as the Arducam and DFPlayer MP3 system to provide a fully integrated user experience that interfaces with the user's mobile device.</li>
    <li>Demonstrated prototype for a gesture-based control system for a car's navigation, media control, temperature, and communication capabilities.</li>
  </ul>

</details>

<div class="video-container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/265pv4jGRmo" title="AI-Powered Gesture Interface For Automobiles" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

---

<details>
  <summary><h2 class="project-title">Mission Connected</h2></summary>

  <p>Mission Connected is a cross-platform close forum for high school club officers to communicate with their members. After experiencing struggles with club communication as both an active club member and officer, I developed a mobile app for both <a href="https://github.com/anirudhv27/missionconnectedios">iOS</a> and <a href="https://github.com/anirudhv27/missionconnectedandroid">Android</a> to centralize communication and streamline club discovery and approval. </p>

  <ul>
    <li>Storyboarded and implemented club selection, dashboard, and event publishing tabs</li>
    <li>Developed admin tool for school administrators to approve new club proposals and provide feedback.</li>
    <li>Implemented <b>Google OAuth</b> to make application secure and authenticated</li>
    <li>Integrated several open-source projects into the application to provide the best functionality to the app's users.</li>
  </ul>

  <p>I used <b>Firebase</b> for my app's backend.</p>

</details>

<div class="video-container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/RuD-W7nY72k" title="Mission Connected Demo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>