<h1 align="center"> Hi 👋 I'm Idhibhat (Margin) </h1>

I'm a backend developer with a growing passion for **distributed systems**, infrastructure, and building tools that scale.  
Currently a Computer Engineering undergrad graduating in 2026 — looking for internships and research opportunities in systems and software engineering.

## 🌱 A little about me

- 🎓 Computer Engineering Student @ [Chulalongkorn University](https://www.chula.ac.th/en/)
- 💼 Software Engineer Intern @ [Agoda](https://www.agoda.com/)
- 📖 Self-learning distributed systems (raft, K8s, fault tolerance, distributed storage/computation)
- 🇯🇵 日本語を自習しています（JLPT N2）

For work experience, see my [resume](https://drive.google.com/file/d/1XgbYMgG7tpFdXE8JW8BoRq99pAd-xu0B/view)

## ⚒️ Interests and Technologies

- **Core Topics**: Distributed Systems, System Design, Fault Tolerance, Scalability
- **Programming Languages**: Go, Python, TypeScript/JavaScript, Java, C++, SQL
- **Backend/Infra**: REST, PostgreSQL, Redis, gRPC, JWT
- **Cloud & DevOps**: AWS (EC2, S3, Lambda, VPC), Docker, Terraform, CI/CD
- **Libs & Frameworks**: React, Next.js, Spring, Nest.js, .NET
- **Currently Exploring**:
  - Writing systems components from scratch (e.g. pub/sub, consensus, RPC)
  - Aggregate systems (e.g. distributed databases, message queues)
  - Kubernetes + observability tooling

## 🗂️ Notable Projects

### Group Projects

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    🧑‍🎓 Freshmen Orientation (RPKM67) Web API
  </summary>
  <ul>
    <li>API for registration, house selection, e-stamps, checkins in university orientation event</li>
    <li>Led backend development for a freshmen orientation platform serving 7,000+ users</li>
    <li>Implemented microservices, Google OAuth, caching, monitoring dashboards, and GitOps</li>
    <li>Tech: Go, Gin, gRPC, Redis, PostgreSQL, S3, Prometheus, Grafana</li>
    <li> <a href="https://github.com/isd-sgcu/rpkm67-backend" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    📚 Online Bookstore E-Commerce Platform
  </summary>
  <ul>
    <li>Software Engineering Course Project</li>
    <li>Features: selling/buying books, chat, transaction/delivery management, admin backoffice</li>
    <li>Implemented scrum practices, code reviews, e2e testing</li>
    <li>Tech: TypeScript, React (Next.js), Prisma, PostgreSQL, Abby WS, Docker</li>
    <li> <a href="https://github.com/seg-org/bookbook" target="_blank">GitHub Repo</a> |
        <a href="https://bookbook.bookpanda.dev" target="_blank">Deployment</a> 
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    📬 Recreating Facebook Messenger
  </summary>
  <ul>
    <li>Chat application implemented the system design way</li>
    <li>Features: Google login, real-time chat, group chats, reactions, unread messages, read status</li>
    <li>Tech: Go, PostgreSQL, WebSockets, TypeScript, React (Next.js), Docker</li>
    <li> <a href="https://github.com/bookpanda/messenger-clone" target="_blank">GitHub Repo</a> |
        <a href="https://messenger.bookpanda.dev" target="_blank">Deployment</a> 
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    🧠 Converting PDFs to brainrot videos
  </summary>
  <ul>
    <li>Streamlit app to turn any PDFs into Brainrot reels</li>
    <li>Tech: Python, FastAPI, AWS (S3, SNS, Polly, Textract), Gemini API, Terraform</li>
    <li> <a href="https://github.com/bookpanda/pdf-2-brainrot" target="_blank">GitHub Repo</a> |
        <a href="https://pdf2brainrot.streamlit.app" target="_blank">Deployment</a> 
    </li>
  </ul>
</details>

### Low-Level Projects

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    🐙 Buiding Git from scratch
  </summary>
  <ul>
    <li>Implemented fundamental Git internals: cat-file, hash-object, ls-tree, write-tree, commit-tree</li>
    <li>Tech: C++, CMake, Linux, SHA1</li>
    <li> <a href="https://github.com/bookpanda/git-from-scratch" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    🛜 Buiding HTTP server from scratch
  </summary>
  <ul>
    <li>TCP open/close connection with persistent connection header</li>
    <li>gzip compression for response body</li>
    <li>Concurrent request handling with worker threads</li>
    <li>Tech: C++, CMake, gzip</li>
    <li> <a href="https://github.com/bookpanda/webserver-from-scratch" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    💾 Buiding SQLite from scratch
  </summary>
  <ul>
    <li>Reading DB pages bytes-by-bytes (big endian format)</li>
    <li>Structure: pages, cells, records, Varints encoding</li>
    <li>Reading data and index B-Trees, both interior and leaf pages</li>
    <li>RegEx to parse SQL queries: SELECT, FROM, WHERE</li>
    <li>Tech: C++, CMake, gzip</li>
    <li> <a href="https://github.com/bookpanda/sqlite-from-scratch" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

### System Design Implementations

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    ⛓️‍💥 URL shortener
  </summary>
  <ul>
    <li>base62 encoding, caching reads, unique id counter</li>
    <li>Tech: Java, Spring, PostgreSQL, Redis</li>
    <li> <a href="https://github.com/bookpanda/design-bitly" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    📦 Dropbox
  </summary>
  <ul>
    <li>presigned URLs for direct client-S3 uploads, S3 notifications, shares table</li>
    <li>Tech: Java, Spring, S3, DynamoDB</li>
    <li> <a href="https://github.com/bookpanda/design-dropbox" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

### Other Side Projects

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    🛂 SSO Implementation
  </summary>
  <ul>
    <li>Implemented Single Sign On with 2 services: central auth service (CAS), consumer service</li>
    <li>logging to consumer service will redirect to CAS for Google login</li>
    <li>CAS creates session and sends service ticket back to consumer service</li>
    <li>Read more in the repo...</li>
    <li>Tech: Go, C#, .NET, TypeScript, React, PostgreSQL, Redis</li>
    <li> <a href="https://github.com/bookpanda/sso-cas" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    🎈 Fly.io Distributed Systems Challenge
  </summary>
  <ul>
    <li>My solution to fly.io Distributed Systems Challenge</li>
    <li>Tech: Go</li>
    <li> <a href="https://github.com/bookpanda/fly-io-dist-sys" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    ☁️ 100% IaC WordPress Deployment on AWS
  </summary>
  <ul>
    <li>Deployed WordPress and MariaDB EC2 in VPC</li>
    <li>Network partition into public and private subnets</li>
    <li>Tech: EC2, VPC, IGW, NAT, ENI, S3, IAM</li>
    <li> <a href="https://github.com/bookpanda/2110524-wordpress-vpc" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    🟩 GitHub Contribution Graph but it's Anime
  </summary>
  <ul>
    <li>Daily cron job generating watch history graph based on score and duration</li>
    <li>Literally what you see at the bottom of this README.md</li>
    <li>API from Anilist.co</li>
    <li>Tech: TypeScript, Github Actions</li>
    <li> <a href="https://github.com/bookpanda/anime-stats" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    ♠️ Generating Anki Cards from Spotify Lyrics
  </summary>
  <ul>
    <li>Wanted to learn the meaning of lyrics in Japanese songs</li>
    <li>Too lazy to manually create Flashcard decks</li>
    <li>Tech: TypeScript, React, Python, Azure Translation API</li>
    <li> <a href="https://github.com/bookpanda/Lyrics2Anki" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

## 🏫 Notable Coursework Repos

- [Cloud Computing](https://github.com/bookpanda/2110524-CLOUD-COMP-TECH)
- [Data Science and Data Engineering](https://github.com/bookpanda/2110446-DATA-SCI-ENG)
- [Natural Language Processing](https://github.com/bookpanda/2110572-NLP-SYS)
- [Operating Systems](https://github.com/bookpanda/2110313-OS-SYS-PROG)
- [Database Systems](https://github.com/bookpanda/2110322-DB-SYS)
- [Algorithms](https://github.com/bookpanda/2110327-ALGORITHM-DESIGN)
- [Data Structures](https://github.com/bookpanda/2110211-INTRO-DATA-STRUCT)
- [Object Oriented Programming](https://github.com/bookpanda/2110215-PROG-METH-I)
- [Embedded Lab](https://github.com/bookpanda/2110366-EMBEDDED-SYS-LAB)
- [Hardware Synthesis Lab](https://github.com/bookpanda/2110363-HW-SYN-LAB-I)

## 📜 Certifications
<div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px;">
<a href="https://www.credly.com/badges/e83a6bcb-89fa-46d0-ae77-2f9a596cca6f/public_url" target="_blank">
  <image src="https://images.credly.com/size/680x680/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" 
  alt="AWS Certified Solutions Architect – Associate" style="width: 120px; height: auto;"/>
</a>
<a href="https://www.credly.com/badges/a9931a40-ce76-4d7b-9e96-5627126fafc6/public_url" target="_blank">
  <image src="https://images.credly.com/size/680x680/images/00634f82-b07f-4bbd-a6bb-53de397fc3a6/image.png" 
  alt="AWS Certified Cloud Practitioner" style="width: 120px; height: auto;"/>
</a>
</div>

# アニメ 視聴履歴

<img src="./src/generated/calendar.svg" />

<h2>最後の１０アニメ</h2>

{{ last10Animes }}

<details>

  <summary>最後の１００アニメ</summary>

  {{ last100Animes }}

</details>
