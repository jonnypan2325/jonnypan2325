I'm a 4th-year CS major at the University of California, Irvine, specializing in **AI/ML & Intelligent Systems**, with a strong interest in full-stack development and computer vision.

*(Last updated: Aug 12, 2026)*

### Current work:
I have been a **Software Intern at MyCase (8am)** since June 2026. Currently, I am engineering AI-assisted template generation workflows and document previews for lawyers.


I'm also working on some personal projects and am a project coordinator for the Artificial Intelligence Club at U.C. Irvine.

Prev @ Canon U.S.A., I worked on a multi-agent RAG Chatbot to assist service technicians and developed a document classification/extraction pipeline 

## Skills & Technologies



* **Machine Learning**: GANs, Transformers, Reinforcement Learning, Deep Learning, LLMs, NLP, RAG
* **Computer Vision**: Signal Processing, Image Processing, Geospatial Analysis
* **Web & Tools**: FastAPI, Next.js, Docker, RESTful APIs, GitHub Actions, CI/CD
* **Cloud**: Azure, GCP
* **Programming**: Python, Java, JavaScript/TypeScript
* **Development**: Agile Development, Algorithm Design


---

## Featured Projects

### Personal Website + Persistent Counter
[![Live Site](https://img.shields.io/badge/Live_Site-jonathanpan.me-FF5D01?logo=astro&logoColor=white)](https://jonathanpan.me)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/jonnypan2325.github.io-blue?logo=github)](https://github.com/jonnypan2325/jonnypan2325.github.io)

The site you land on if you Google me. Mostly became an excuse to work out how far you can push a static site that has no backend at all.
- Built with Astro and Tailwind, ships zero client JS by default, auto-deploys to GitHub Pages on every push via GitHub Actions
- "Send a wave" pixel-art counter: GitHub Pages can only serve files, so the shared count lives in a Cloudflare Worker backed by Workers KV
- Cloudflare Turnstile gates the endpoint invisibly (no puzzle to solve), with per-IP hourly caps and an anti-hammer guard stored in KV
- Pushover fires a notification to my phone when someone sends a wave, throttled server-side to at most one per minute so it can't be spammed
- SEO work: JSON-LD Person/WebSite schema with sameAs identity claims, rel="me" profile links, canonical URLs, generated sitemap, Open Graph cards, and an llms.txt for AI crawlers

### Strava Map Art Generator (In-Progress)

Ever wanted to draw a picture with your running route? I'm building an algorithm that converts hand-drawn sketches into actual GPS routes on real streets.
- Uses Iterative Closest Point alignment to match your sketch to OpenStreetMap data
- Handles multi-part drawings and automatically figures out how to connect them
- Generates Eulerian circuits so you get a continuous, traversable route (no teleporting between streets!)
- Exports to GPX files you can load onto your watch or phone

*(inspired by a [reddit post](https://www.reddit.com/r/Strava/comments/10mfsm9/how_do_you_create_strava_art/) a while back)*

### LeShrine (2nd Place - IrvineHacks 2025 Meme Hack)
[![Devpost](https://img.shields.io/badge/Devpost-LeShrine-003E54?logo=devpost)](https://devpost.com/software/leshrine)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/LeShrine-blue?logo=github)](https://github.com/jonnypan2325/LeShrine)

A Chrome extension that replaces every ad on the internet with LeBron James. Won 2nd place in the meme category at IrvineHacks.
- Intercepts ad network requests before they load using the declarativeNetRequest API
- Swaps blocked ads with iconic LeBron images and "Blocked by James!" sound effects
- New tab page shows his game schedule, highlights, and stats
- Triggers audio on user interactions to track how many ads you've "blocked"
- Built entirely in vanilla JavaScript and CSS

### Crossy Road Reinforcement Learning (Project in AI/ML)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/Crossy--Roads--RL-blue?logo=github)](https://github.com/jonnypan2325/Crossy-Roads-RL)

A reinforcement learning project that trains AI agents to play Crossy Road using deep learning algorithms
- Built a custom Gymnasium environment with roads, rivers, trains, and moving obstacles
- Implemented DQN, PPO, and A2C algorithms using Stable-Baselines3
- Phased curriculum and progressive training for difficulty scaling
- Used TensorBoard for tracking training metrics and analyzing performance
- Pygame visualization to watch or record the agent's attempts

### Camera Localization (Project in Computer Vision)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/Camera_Geolocation-blue?logo=github)](https://github.com/jonnypan2325/Camera_Geolocation)

A computer vision project where I implemented camera localization using stereo vision.
- Camera calibration pipeline for both intrinsic and extrinsic parameters
- 3D pose estimation through OpenCV and triangulation
- Interactive multi-view visualization to step through frames
- Validated results against ground truth measurements with error analysis

### MNIST Neural Network Workshop (AI@UCI)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/MNIST--NN-blue?logo=github)](https://github.com/jonnypan2325/MNIST-NN)
[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-brightgreen)](https://jonnypan2325.github.io/MNIST-NN/)

A workshop I organized for AI@UCI that walks through building neural networks from scratch. The goal was making the learning curve less steep.
- Progressive curriculum: linear classifiers → perceptrons → simple NNs → fully connected NNs → CNNs
- Visualizations show what's actually happening under the hood (decision boundaries, feature transformations, training dynamics)
- Hands on Jupyter notebooks with adjustable parameters and step by step instructions

---

### Interests
When I'm not coding, you can find me:
*  Surfing
*  Playing golf
*  On the ski slopes
*  Photography (#teamCanon)
*  Cooking up something new in the kitchen


<br />

### Get in Touch
Feel free to reach out on Linkedin!

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/jonathanypan/)
