### Hi there, I'm Kauan! 👋

I'm a Computer Science student at UFSC with a passion for C++, algorithms, and complex problem-solving. My main focus is building efficient, high-performance applications.

---

###  My Tech Stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cpp,java,c,python,git,linux,spring,html,css,js,mysql" />
  </a>
</p>

* **Areas of Interest:** Competitive Programming, Algorithm Analysis and Design, Data Structures, Graph Theory.

### My Projects (At least the biggest ones)


* **[AvaliaUFSC](https://www.github.com/Itaxo01/AvaliaUFSC)**: A Fullstack web application for rating and reviewing professors and courses from the Federal University of Santa Catarina. 
	- The application is fully integrated with the university site for the scrapping of professors and courses, along with student verification, allowing access and use only for authenticated students. 
	- Allows the access to ratings and reviews for each pair of (Course, professor), along with interaction with the reviews (Comments and likes).
	- Uses a vast set of tools, such as **thymeleaf** for the dynammic construction of pages through the stored data, **fuseJS** for the search mechanism, **JSoup** for data scrapping, and a lot of Spring functionalities for the management of the database, http sessions and API requests. 
	- Made with **Java Spring Boot** for the back-end and **JavaScript and HTML/CSS** for the front-end.

* **[Interactive Graphical System](https://github.com/Itaxo01/ComputacaoGrafica/)**: An interactive graphical system built without graphical libraries or engines, purely in C++ (with an experimental CUDA branch).
 	- It renders objects completely from scratch, executing a full pipeline that includes transformations, perspective, clipping, rasterization, shaders, and more.
    - It's heavily parallelized on the CPU, using custom implementations of Intel TBB's `for_each` that achieve almost the same performance. Everything is done strictly on the CPU (except for the CUDA branch, which I haven't invested much time into yet).
    - Because it doesn't use the GPU for rendering, the performance is naturally lower than a standard engine. The goal was to build everything from the ground up, so that was expected. Even so, it does a great job and can handle models with about 300K faces—which is probably higher than anything previously built in this course.
    - I used [Dear ImGui](https://github.com/ocornut/imgui) and [GLFW](https://github.com/glfw/glfw) for the UI. The UI itself *does* use OpenGL, but our core pipeline runs entirely on the CPU, rasterizing to a FrameBuffer that is simply passed to OpenGL as a 2D texture.
      
---

### Competitive Programming

I actively solve problems on platforms like Atcoder and Codeforces. This is where I sharpen my skills in:
* Problem solving in general
* Algorithms analysis and design
* Dynamic Programming
* Graph Theory (DFS, BFS, Dijkstra)
* Advanced Data Structures (Segment Trees, Sparse Tables, etc.)

Check out my [Competitive-Programming](https://www.github.com/Itaxo01/Competitive-Programming) repo for my solutions! (Although they're not that organized nor updated frequently)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Itaxo01/Itaxo01/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Itaxo01/Itaxo01/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/Itaxo01/Itaxo01/output/github-snake.svg" />
</picture>

---

### How to Reach Me

* **LinkedIn:** [linkedin.com/in/kauan-fank](https://www.linkedin.com/in/kauan-fank)
* **Email:** [kauan.fank@gmail.com](mailto:kauan.fank@gmail.com)
