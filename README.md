<h1 align="center">Hello, I'm Alex!</h1>

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) 

I have a degree in computer science from UBC. While I was in school, I gained an interest in networking and backend systems. 

Outside of programming, I enjoy:

- Reading
- Listening to, discussing, and finding new music
- Rock climbing

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/alextaschuk) 

## Projects

**[Literary Quote Clock (Rewrite)](https://github.com/alextaschuk/Lit-Clock-Cpp-Rewrite)** | _C++_
- A clock that tells the time using quotes from books.
- Image generation on this version is significantly faster.
- The custom text-rendering pipeline includes more intuitive text formatting and has more accurate vertical text spacing, improving the readability of quotes compared to the Python clock.
- Includes scripts to automate installing and uninstalling the clock, boot-time startup, and enable daily updates.

  <img width="362" height="268" src="https://github.com/user-attachments/assets/3f922768-398e-4a0d-a000-04cd4dbd8780" />


**[TCP Congestion Anomaly Detection](https://github.com/alextaschuk/TCP-Congestion-Anomaly-Detection)** | _C_, _TensorFlow_
- A multi-threaded implementation of TCP that I made from scratch in C. It has connection management, reliable data transfer, flow control, and concurrent client-server communication.
- Implemented Tahoe, Reno, and New Reno congestion control algorithms and retransmission mechanisms.
- Designed and trained an LSTM to predict congestion events (triple ACKs/timeouts) before they occur.


**[Clock-Related Text Detection in Novels with Deep Learning](https://github.com/alextaschuk/Clock-Based-Text-Detection)** | _Python_, _transformers_
- A Python data-processing pipeline to identify clock-related temporal expressions (e.g., "half-past eight in the evening") in novels using fine-tuned transformer models.
  1. Integrated a fine-tuned BERT token classifier with GPT-5.4 mini to filter non-clock-related temporal expressions and extract relevant sentence context.
  2. A fine-tuned RoBERTa seq2seq model was on its own.
- The multi-stage pipeline was benchmarked against the RoBERTa model to analyze the pipelines' precision and recall abilities against each other and their failure modes—including duplicate results from overlapping context windows and sentences dropped by each stage—to identify prompt and fine-tuning improvements.


**[University Capstone Project](https://github.com/COSC-499-W2025/capstone-project-team-18)** | _Python_, _SQL_, _Electron_
- A desktop app that analyzes a user's coding projects to generate personalized resumes and web portfolios.
- Project information, generated resumes, and generated portfolios are all user-customizable.
- Users can connect their GitHub account and deploy their generated static web portfolio to GitHub Pages to share with others.
 
  <img width="500" src="https://github.com/user-attachments/assets/0ce66e34-dd45-42ec-9dbf-fca80f226155" />


**[Literary Quote Clock](https://github.com/alextaschuk/Literary-Quote-Clock)** | _Python_
- A clock that tells the time using quotes from books.
- The clock can be made using a Raspberry PI Zero 2WH with either an IT8951 e-paper display or a non-IT8951 EPD, or can be installed on a jailbroken Kindle.

  <img width="362" src="https://github.com/user-attachments/assets/b9857c63-bfdf-496d-ba85-337cea9d65de"/>


**[Selectify](https://github.com/alextaschuk/selectify) ([albumselector.com](https://albumselector.com))** | _Python_
- A website that selects a random album for you to listen to from your saved albums on Spotify. The site was originally deployed locally via a reverse proxy, Gunicorn, and port forwarding; it was accessible to anyone, regardless of whether they were connected to my home network or not.
 
  <img width="600" src="https://github.com/ataschuk/selectify/assets/120518938/2f6190b4-eacb-4c83-b850-c9c388457c46"/>

<!--## Languages
Python, C, C++, Java, JavaScript

[![GitHub Stats](https://github-stats-extended.vercel.app/api/top-langs?username=alextaschuk&layout=compact&hide_progress=true&langs_count=3&theme=onedark)](https://github-stats-extended.vercel.app/api/top-langs?username=alextaschuk&layout=compact&hide_progress=true&langs_count=3&theme=onedark)-->
