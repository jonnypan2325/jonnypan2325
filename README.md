I'm a 4th-year CS major at the University of California, Irvine, specializing in **AI/ML & Intelligent Systems**, with a strong interest in full-stack development and computer vision.

*(Last updated: Oct 30, 2026)*

### Current work:
I'm finishing my senior year and looking for **New Grad SWE / Forward Deployed Engineer** roles.

I'm also building personal projects and am a project coordinator for the Artificial Intelligence Club at U.C. Irvine.

**Previously, SWE intern @**
- **MyCase (8am)** (June – Sept 2026): document previews and AI-assisted template generation workflows for lawyers
- **Canon U.S.A.** (Sept 2025 – June 2026, return offer): document classification and field extraction pipeline
- **Canon U.S.A.** (June – Sept 2025): multi-agent RAG chatbot to assist service technicians

## Skills & Technologies

* **Languages**: Python, TypeScript/JavaScript, Ruby, Java, C
* **AI/ML**: LLMs, RAG, Multi-Agent Systems, Transformers, Deep Learning, Reinforcement Learning (Stable-Baselines3), GANs, NLP
* **Computer Vision**: OpenCV, MediaPipe, Image & Signal Processing, Geospatial Analysis
* **Frontend**: React, Next.js, Astro, Tailwind CSS
* **Backend**: Ruby on Rails, Flask, FastAPI, RESTful APIs
* **Cloud & DevOps**: GCP (Firestore), Azure, Vercel, Cloudflare Workers, Docker, GitHub Actions CI/CD
* **Testing**: pytest, Vitest

---

## Featured Projects

### Personal Website + Persistent Counter
[![Live Site](https://img.shields.io/badge/Live_Site-jonathanpan.me-FF5D01?logo=astro&logoColor=white)](https://jonathanpan.me)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/personal--website-blue?logo=github)](https://github.com/jonnypan2325/personal-website)

The site you land on if you Google me. Mostly became an excuse to work out how far you can push a static site that has no backend at all.
- Built with Astro and Tailwind, ships zero client JS by default, auto-deploys to GitHub Pages on every push via GitHub Actions
- "Send a wave" pixel-art counter: GitHub Pages can only serve files, so the shared count lives in a Cloudflare Worker backed by Workers KV
- Cloudflare Turnstile gates the endpoint invisibly (no puzzle to solve), with per-IP hourly caps and an anti-hammer guard stored in KV
- Pushover fires a notification to my phone when someone sends a wave, throttled server-side to at most one per minute so it can't be spammed
- SEO work: JSON-LD Person/WebSite schema with sameAs identity claims, rel="me" profile links, canonical URLs, generated sitemap, Open Graph cards, and an llms.txt for AI crawlers

### VroomMates
[![Live Site](https://img.shields.io/badge/Live_Site-vroommates.vercel.app-000000?logo=vercel&logoColor=white)](https://vroommates.vercel.app)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/VroomMates-blue?logo=github)](https://github.com/jonnypan2325/VroomMates)

A carpool planner for friends heading to the same place, like a concert or a trailhead. Give it the drivers (with seat counts), the passengers, and the destination, and it decides who rides with whom and in what pickup order, then draws each driver's route on Google Maps.
- Exact optimizer (bitmask dynamic programming over pickup sets) that minimizes total driving distance, bounded at 12 passengers and 8 drivers so every request solves quickly
- React frontend with Google Maps, Places Autocomplete, and Directions; Flask API that validates input and enforces the limits
- Google sign-in with server-side ID-token verification, and saved trips and locations per account in Firestore
- Frontend and API deployed as separate Vercel projects, with Firestore reached through Vercel OIDC and Workload Identity Federation (no stored service-account keys)
- 140+ backend tests covering the optimizer, API, auth, and saving

### Hamster Reaction
[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-brightgreen)](https://jonnypan2325.github.io/hamster-reaction/)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/hamster--reaction-blue?logo=github)](https://github.com/jonnypan2325/hamster-reaction)

Make a face, hand, or body gesture at your webcam and the app answers with a matching hamster.
- Recognizes 18 gestures (thumbs up, side eye, flexing, crossed arms, and more) from MediaPipe face, hand, and pose landmarks
- All inference runs on-device in a Web Worker at about 20 fps: no server, and no video is uploaded or saved
- A temporal stabilizer confirms a gesture over several frames so the hamster doesn't flicker between reactions
- React + TypeScript + Vite, tested with Vitest, deployed to GitHub Pages by GitHub Actions

### Crossy Road Reinforcement Learning (Project in AI/ML)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/Crossy--Roads--RL-blue?logo=github)](https://github.com/jonnypan2325/Crossy-Roads-RL)

A reinforcement learning project that trains AI agents to play Crossy Road using deep learning algorithms
- Built a custom Gymnasium environment with roads, rivers, trains, and moving obstacles
- Implemented DQN, PPO, and A2C algorithms using Stable-Baselines3
- Phased curriculum and progressive training for difficulty scaling
- Used TensorBoard for tracking training metrics and analyzing performance
- Pygame visualization to watch or record the agent's attempts

### Strava Map Art Generator (In-Progress)

Ever wanted to draw a picture with your running route? I'm building an algorithm that converts hand-drawn sketches into actual GPS routes on real streets.
- Uses Iterative Closest Point alignment to match your sketch to OpenStreetMap data
- Handles multi-part drawings and automatically figures out how to connect them
- Generates Eulerian circuits so you get a continuous, traversable route (no teleporting between streets!)
- Exports to GPX files you can load onto your watch or phone

*(inspired by a [reddit post](https://www.reddit.com/r/Strava/comments/10mfsm9/how_do_you_create_strava_art/) a while back)*

### Camera Localization (Project in Computer Vision)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/Camera__Localization-blue?logo=github)](https://github.com/jonnypan2325/Camera_Localization)

A computer vision project where I implemented camera localization using stereo vision.
- Camera calibration pipeline for both intrinsic and extrinsic parameters
- 3D pose estimation through OpenCV and triangulation
- Interactive multi-view visualization to step through frames
- Validated results against ground truth measurements with error analysis

### LeShrine (2nd Place - IrvineHacks 2025 Meme Hack)
[![Devpost](https://img.shields.io/badge/Devpost-LeShrine-003E54?logo=devpost)](https://devpost.com/software/leshrine)
[![Repo](https://img.shields.io/badge/Repository-jonnypan2325/LeShrine-blue?logo=github)](https://github.com/jonnypan2325/LeShrine)

A Chrome extension that replaces every ad on the internet with LeBron James. Won 2nd place in the meme category at IrvineHacks.
- Intercepts ad network requests before they load using the declarativeNetRequest API
- Swaps blocked ads with iconic LeBron images and "Blocked by James!" sound effects
- New tab page shows his game schedule, highlights, and stats
- Built entirely in vanilla JavaScript and CSS

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
