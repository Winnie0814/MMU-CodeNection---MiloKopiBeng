# MARIS by MiloKopiBeng 
Team: Winnie Teo Wan Yi (L), Michelle Lim Pei Ling, Lim Cher Earn, Tan Yin Le <br>
Problem Statement: Stress & Workload Manager <br>
Video Presentation:  <br>
Presentation Slides: https://canva.link/3dr5621kbuyf9s4 <br>
<h1>1. Project Overview</h1>
<br>

<p align="justify">
The problem:
  
Causes of burnout: <br>
i.   Academic workload: Assignments, projects, exams, presentations, and deadlines can accumulate at the same time.<br>
ii.  Time pressure: Students often struggle to balance studying with part-time jobs, commuting, errands, and personal responsibilities.<br>
iii. Poor workload awareness: Students may not realize how overloaded they are until stress and exhaustion become severe.<br>
iv.  Lack of recovery: Students may sacrifice time for their hobbies.<br>
v.   Poor task prioritization: Students may focus on urgent tasks while repeatedly postponing less urgent but important activities.<br>
vi.  Lack of personalized support: Different students have different study time, study habits, hobbies, and stress triggers. Therefore, a one-size-fits-all solution may not work well.

Stakeholders: <br>
University students need the system to help them managing workload, stress, recovery, and study habits.

Similar apps exist in the market: <br>
Todoist. Todoist is useful application for organizing tasks, setting deadlines, and managing priorities. But, its main focus is task management rather than understanding a student's overall mental, physical, social, and time-related workload. It also does not provide the same level of personalized burnout prevention through AI schedule recommendations, hobby-based recovery activities, or wearable-based stress alerts that our proposed system provided.
</p>
<br>
<hr>

<p>
Our Solution: 

Our solution is an AI-powered workload management application to reduce students stress and avoid from burnout. The application will suggest some relax activities by following each student's preferences, which includes their hobbies, discipline, and daily responsibilities that they choose during their first visit. An AI watch system monitors user's heart rate and sends a rest notification when the user's heart rate exceeds 120 BPM. Besides, users can also earn coins from completing tasks and use them to play stress-relief games such as Memory Game and Stress Escape. In addition, an AI chatbot provides accessible emotional support and guidance, while encouraging students to seek professional psychological help when necessary.
</p>
<br>


<h1>2. Ideation & Process</h1>
<h2>2.1 Ideas We Considerd</h2>
<table border=2 >
  <tr>
    <th><b>Idea</b></th>
    <th><b>Why it was dropped / kept</b></th>
  </tr>
  <tr>
    <td>User preferences (Chosen) </td>
    <td>The first time visit users will be asked about their preferences, such as their hobbies and preferred activities. These preferences will then be used in the spin wheel to recommend suitable activities for users to do during their break time.</td>
  </tr>
  <tr>
    <td>To-Do List + Detail AI analyze (Chosen) </td>
    <td>The AI analyzes the importance of each task and and their estimated time to complete. Then, the system will also suggest a way for users to complete their tasks in the simplest and clearest way as possible. Not only that, an AI chatbot will also pop up after users complete a task to ask about their current feelings and stress levels.
</td>
  </tr>
  <tr>
    <td>Heart rate monitor watch (Chosen) </td>
    <td>Users can take an immediate break and stop their current task when their heart rate exceeds 120 bpm. This can help users to prevent from becoming overloaded and allows them to rest before continuing their tasks.</td>
  </tr>
  <tr>
    <td>Games (Chosen) </td>
    <td>The games encourage users to complete their tasks. Besides, it also provide an effective way to reduce user's stress.</td>
  </tr>
  <tr>
    <td>Leaderboard (not chosen)</td>
    <td>We also thought about adding a leaderboard to motivate students by comparing their progress with others, making them to feel more eager in completing          their tasks. However, the competition might not be suitable for the app as it increases frustration, especially students that are overwhelmed with their           tasks. Since our goal is to help students to work according to their own pace, we decided to not include the feature.</td>
  </tr>
  <tr>
    <td>Screen Time Blocking (not chosen)</td>
    <td>We thought about including this feature when students start to do their tasks. However, our app focuses more on workload management and preventing burnout, not restricting distractions. Therefore, we think that this feature is not our main feature that can support our objective.</td>
  </tr>

</table>
<h2>2.2 Ideation Boards</h2>
https://www.figma.com/design/APIdv8gRfvNeJf9uEsCXGD/MMU-Hackathon-Wireframe?node-id=483-998&p=f&t=ekuVCWmQYWfiGoYx-0
<h2>2.3 Mentor Consultation</h2>
<table border=2 >
  <tr>
    <th><b>Date</b></th>
    <th><b>Mentor</b></th>
    <th><b>Feedback Received</b></th>
    <th><b>What Was Changed</b></th>
  </tr>
  <tr>
    <td>9 September 2026</td>
    <td>Marcus Mah Qing Fung</td>
    <td>
      -	The system should estimate the user’s daily or weekly work capacity. <br>
      -	Each task can receive a workload score so that it can be compared against the student’s estimated capacity. It lets the system to identify whether the student is currently within a manageable workload or they have overloaded. <br>
      -	The task list should not just be a basic to-do list, but a more effective feature that can analyse user’s tasks. It should do workload analysis and capacity calculation. <br>
      -	The system can then explain whether the user is within capacity or exceeding their capacity and recommend which tasks should be prioritised, postponed or removed.</td>
    <td>-The task list has been enhanced with an AI-powered task analysis feature that analyse the user’s tasks. The AI will analyze the tasks into small tasks which makes students easy to follow.  <br>
- A daily check-in is added that allows the system to understand student’s actual condition instead of relying only on task information. The system will ask students to fill in their report factors such as energy level, stress level and available time and use this information to adjust the user’s estimated capacity for the day.   <br>
- The daily check-in is combine with capacity and AI analysis. These features work together and AI will analyse which tasks are causing overload and suggest realistic adjustments. <br>
    </td>
  </tr>
</table>
<h1>3. Design & Prototype</h1>
Figma Link: https://www.figma.com/design/APIdv8gRfvNeJf9uEsCXGD/MMU-Hackathon-Wireframe?node-id=0-1&p=f&t=scmWPXBUBO2nfBfa-0
<br>
Prototype Link: https://figma.com/proto/APIdv8gRfvNeJf9uEsCXGD/MMU-Hackathon-Wireframe?node-id=0-1&p=f&t=scmWPXBUBO2nfBfa-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=284%3A671&show-proto-sidebar=1
<h1>4. What Makes It Different</h1>
<p>Unlike typical burnout or productivity apps that mainly track tasks, screen time, or remind users to take breaks, our app provides active and personalised burnout support. The AI will analyze a student’s workload, capacity, energy level, and emotions to identify when they may be overloaded. When students feel overwhelmed, the AI acts like a supportive tutor by helping them prioritise tasks, suggesting how to approach them, and showing when they may need to reduce their workload. Breaks are given if the system detects a burnout. The app will recommend students to take a break through a spin wheel and relaxing pet-based games. Students can also connect with peer communities for social support. This makes the app different by combining workload management, burnout prevention, recovery, and social connection in one platform.

Ideation 
Spin Wheel 
We feel that many students do not know how to take effective breaks. When they finally take a break, they choose to doomscroll their phones because they are too mentally tired to decide what to do. However, this can make breaks longer than intended and leave students to feel more drained. This inspired our Spin Wheel feature. When the system detects that a student’s workload and energy level indicate a need for rest, the wheel suggests simple break activities for them. This removes the pressure of choosing an activity and encourages students to step away from their workload, recover their energy, and manage burnout before returning to their tasks.
Daily Check-in 
Students often plan their workload based on how much time they have but overlook whether they actually have the energy and mental capacity to complete it. The daily check-in lets students to record and the system compares their workload to identify possible overload and recommend adjusting tasks or taking breaks. This helps students understand how much they can realistically handle each day and prevent burnout before it worsens.
Pet Companion 
We came up with the Pet Companion because students under heavy workloads can sometimes feel stressed, lonely, or mentally drained. Not everyone has someone to talk to when they feel overwhelmed. We wanted to create a small source of comfort that students can interact with during their breaks and helping them relax. Instead of pending breaks doomscrolling, students can play short activities with their pet to relax and emotionally recharge. The pet also encourages healthy habits such as taking breaks and completing daily check-ins, making burnout management feel more engaging and less like another task.

</p>
