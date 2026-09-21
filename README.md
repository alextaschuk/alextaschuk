<h1 align="center">Hello, I'm Alex!</h1>

I have a degree in computer science from UBC. While I was in school, I gained an interest in networking and backend systems. 

In my free time, I enjoy:

- Reading
- Listening to, discussing, and finding new music
- Rock climbing

## Projects

**[Literary Quote Clock Rewrite](https://github.com/alextaschuk/Lit-Clock-Cpp-Rewrite)** | _C++_

- A Rewrite of my Literary Quote Clock (originally written in Python) to familiarize myself with C++. This gave me more control over the formatting and layout of text on the screen, so text is more readable in this version compared to the Python clock.

 <img width="362" height="268" src="https://github.com/user-attachments/assets/3f922768-398e-4a0d-a000-04cd4dbd8780" />



**[TCP Congestion Anomaly Detection](https://github.com/alextaschuk/TCP-Congestion-Anomaly-Detection)** | _C_
- Created a custom multithreaded transport-layer protocol that reimplements TCP's core functionality without the Berkeley sockets TCP stack (doesn't use TCP syscalls like `listen()`).
- I trained a stacked LSTM on RTT/congestion timing data to predict imminent congestion events (triple ACKs/timeouts) before they occur.

**[Clock-Based Text Detection using Deep Learning](https://github.com/alextaschuk/Clock-Based-Text-Detection)** | _Python_

- Built two data pipelines to explore how machine learning could be used to detect sentences in literature that mention an explicit hour and minute of the day.
- The first pipeline used a fine-tuned transformer model (spoiler alert, it wasn't very good). The second pipeline used a fine-tuned token classifier to tag any temporal text, then GPT-5.4 mini to filter any tagged text that wasn't clock-related (e.g., remove "yesterday" but keep "1:43 P.M.").
- The pipelines' performance was benchmarked by tokenizing three books, then passing them into each pipeline and examining their precision and recall abilities.

**[University Capstone Project](https://github.com/COSC-499-W2025/capstone-project-team-18)** | _Python_, _SQL_, _Electron_
- A year-long school project with 5 teammates in which we developed a full-stack desktop app for generating resumes and portfolios.
- Users upload a compressed file (e.g., .zip, .tar) that contains coding projects to the app, the app analyzes the projects, then generates a usable resume and web portfolio with statistics and information about each project. Project information, generated resumes, and generated portfolios are all user-customizable.
- Users can connect their GitHub account to the app and deploy generated web portfolios to a static GitHub Pages site to share with others.
 
  <img width="600" src="https://github.com/user-attachments/assets/0ce66e34-dd45-42ec-9dbf-fca80f226155" />

**[Literary Quote Clock](https://github.com/alextaschuk/Literary-Quote-Clock)** | _Python_
- A clock that tells the time using quotes from books using a Raspberry PI Zero 2WH and an e-paper display. The clock can be made using an IT8951 screen, a non-IT8951 screen, or a jailbroken Kindle.

 <img width="600" src="https://github.com/user-attachments/assets/b9857c63-bfdf-496d-ba85-337cea9d65de" />

**[Selectify](https://github.com/alextaschuk/selectify) ([albumselector.com](https://albumselector.com))** | _Python_
- A website that selects a random album for you to listen to from your saved albums on Spotify. The site was originally deployed locally via a reverse proxy, Gunicorn, and port forwarding; it was accessible to anyone, regardless of whether they were connected to my home network or not.
 
  <img width="600" src="https://github.com/ataschuk/selectify/assets/120518938/2f6190b4-eacb-4c83-b850-c9c388457c46"/>

<!--## Languages
Python, C, C++, Java, JavaScript

[![GitHub Stats](https://github-stats-extended.vercel.app/api/top-langs?username=alextaschuk&layout=compact&hide_progress=true&langs_count=3&theme=onedark)](https://github-stats-extended.vercel.app/api/top-langs?username=alextaschuk&layout=compact&hide_progress=true&langs_count=3&theme=onedark)-->

## How to Get in Touch
- [LinkedIn](https://www.linkedin.com/in/alextaschuk/)
