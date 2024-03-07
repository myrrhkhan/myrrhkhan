# Hi!

(Last updated March 6, 2024.)

I'm Myrrh Khan (he/him) and I'm currently a CS student at Worcester Polytechnic Institute (WPI) in Massachusetts, minoring in Robotics Engineering (RBE). I'll be graduating in May 2025. I've been programming since the begining of my sophomore year of high school in 2019.

### Work Experience:
- \[10/2023-Present\] **Experiential Robotics Platform (XRP) Developer** at WPI OpenSTEM: I'm maintaining code for the XRP educational robotics kit, a kit that runs on a Raspberry Pi Pico W and is used to teach programming in K-12 schools and at the collegiate level. 
	- For the first few months, I collaborated with a coworker to create a lightweight frontend for a webserver in SvelteJS to control the robot and give statistics. I helped my coworker (who had more web development experience but no experience in Svelte) with the syntax and features of Svelte, while he helped me with the design and structure of the frontend.
	- Since then, I have experimented with using a program called PestoLink to wirelessly control robots with laptops or phones and have reported bugs.
	- Now, I am trying to find a way to use multiprocessing via MicroPython to run the webserver. The first goal is to have the webserver run, the next goal is to have the webserver transfer data to the main process, and the end goal is to have the two processes communicate.
- \[09/2021-05/2022\] **Swim Coach in Training (CIT)** for the Franklin Farm Froggers Swim Team: I coached swimmers aged 5-12 weekly during the team's winter conditioning season. I supervised one age group during a given practice. I received practice instructions from the head coach and relayed them to the swimmers, adjusting the instructions and giving feedback as needed, and ensuring that the swimmers had fun.

### Top Projects:
- \[ONGOING\] *[Violet](https://github.com/myrrhkhan/Vi)* (GoatHacks 2024 Honorable Mention): 
	- Tauri (Electron alternative), Rust, HTML/CSS/JavaScript (SvelteJS), Python, Tensorflow, Transformers, Object-Character Recognition (OCR).
	- a standalone handwriting-to-text converter app built on the Tauri framework. Backend in Rust and a frontend in HTML/CSS/SvelteJS. Utilizes a Python script that uploads a machine learning model that I trained with Tensorflow and keras on an OCR dataset to convert to text. Transitioning to a Python executable that uses Transformers and a pre-trained model to increase accuracy and ease of distribution.
- \[FINISHED\] *Glinda*, a Linda-based compute farm for CS 4513 (Distributed Computing Systems): 
	- Rust, HTML/CSS/JavaScript (React)
	- Used Rust to implement a server that used REST API calls and a client that interacted with the server. Wrapped the server and client in a multithreaded Tauri app with React as a frontend. User would input strings and the app would use multiple clients to count the number of vowels in the strings.
- \[FINISHED\] Mock Hospital Database: 
	- Oracle SQL, Java, ER diagrams
	- Collaborated in a group to design an ER diagram for a hospital database. Implemented the mock database in Oracle SQL. Wrote a Java app to interact with the database.
- \[FINISHED\] Robotic Tin Whistle for MU 2801 (Making Music with Machines)
	- Arduino, circuits and soldering, MIDI
	- Collaborated to build a robotic tin whistle with solenoids, a solenoid valve, and an Arduino that a signal via USB serial (converted via a given MIDI Ableton patch) to control the solenoids.

### Skills:

#### Languages:
- Java
	- First Robotics Competition (FRC) programming: programmed tank drive and other parts of robot, and mentored younger teammates in programming.
	- CS 2103 (Advanced Intro to Object-Oriented Programming), 10/22-12/22:
		- Graph search engine with BFS linked lists, and hashmaps.
			- Was given IMDB database of actors and top five movies they were in and was tasked with finding shortest path between given actors and movies.
		- Particle simulator using Java heaps.
		- Graphing calculator simulator using context-free-grammars.
	- CS 2223 (Intro to Algorithms), 03/23-05/23:
		- Implemented Gray Code and Dijkstra's Algorithm
		- Subirachs' Magic Square, calculated number of 4-element combos that add up to magic sum, calculated number of any combination that added up to magic sum, and found a sum with the highest number of combinations in the square.
			- Method: square can be represented as array of 16 numbers. Sum of just last number can be encoded as 0b0000000000000001, sum of last two numbers can be encoded as 0b0000000000000011, etc., all the way until 2^16. Iterated through each possibility and saved sum and number of combinations as a HashMap. While saving, checked if sum == magic sum and if number of 1 chars == 4.
		- Found number of inversions in array A (where i < j but A\[i\] > A\[j\])
			- Tasked with implementing in O(nlogn) time, but used bubble sort, which was O(n^2), when I should've used merged sort instead.
		- Completed N-Queens problem (where queens on chessboard cannot attack each other in the next move.) 
			- Took board (in form of text file) as input. If board was illegal, make board legal. If board was partially complete (including illegal boards that were made legal), make board complete. Finally, find next legal move by moving queens up one row.
		- Other projects:
	- Other projects:
		- MIDI piano in Advanced Intro to OOP
		- Algorithms, measuring ratio between Fibonacci-like sequences and time complexity to naively calculate them (exponential, O(1.6183399^n)) using inheritance.
		- Implemented Gauss-Jordan elimination algorithm for linear algebra in Algorithms.
		- Algorithms, implemented a hash table that read from a file and would hash words into a table. Calculated number of values in hash table, load factor, longest runs of open and closed cells, and word with biggest drift.
		- Algorithms, used dynamic programming to find highest value path through a table of values.
- Python
	- I have been using Matplotlib, NumPy, and Pandas since 2020, and have used it to analyze data in numerous labs for physics and robotics engineering classes. I once used Matplotlib to plot the positions of three AprilTags in real-time, with the locations being given by an MQTT server.
	- Machine Learning:
		- Violet (see above)
		- Participated in a series of classes offered by WPI via an organization called AI4All. My first group project involved doing sentiment analysis on Spotify lyrics using PyTorch and the BERT pretrained model, and my second project involved classifying images of lungs with/without pneumonia via SVGs.
	- In high school, I tried to write an app that sent messages between my robotics team's Slack Workspace and its programming subteam's Discord server. Abandoned the project due to my lack of knowledge in multithreading at the time, but I'd like to pick it up again someday.
- C/C++
	- CS 2303 (Intro to Systems Programming)
	- CS 3013 (Operating Systems)
		- 
- x86 Assembly
- Rust
	- Glinda (see above)
	- Gunmetal: an environment variable editor to mimic the "Edit Environment Variables" dialog on Windows, which I wrote to learn Tauri, Rust, and SvelteJS, leading to other projects. Project on hold due to lack of potential users and due to complexity of parsing bashrc and zshrc files.
- Matlab
- SQL (Oracle)
	- Mock Hospital Database (see above)
- HTML/CSS/JavaScript
	- React:
		- [https://myrrhkhan.github.io](https://myrrhkhan.github.io)
		- Glinda (see above)
	- SvelteJS:
		- Gunmetal (see above), Violet (see above), XRP development (see above, work experience)
- R
- Racket

### Longer Bio:

I started programming in Java through my high school's FIRST Robotics Competition (FRC) team. When I joined, the programming subteam's size was 5x larger than the previous year, so I found myself learning much of the programming on my own. Much of programming started to click at the start of the COVID pandemic, when I had more time to program. I began my Python journey on my own by experimenting with code to graph COVID-19 data, and later, at the suggestion of a family member, started learning Tensorflow on my own and running neural networks on images. I was also put in charge of adapting our programming subteam's workflow transition to COVID, therefore strengthening my skills in Git and allowing me to learn more about GitHub's features. During my senior year, I taught my team how to use GitHub's pull request features to better organize our workflow.

Nowadays, my main interests within CS are all over the place, but currently, I like pursuing projects with systems programming, web development, and machine learning.
