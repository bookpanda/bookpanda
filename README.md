<h1 align="center"> Hi 👋 I'm Idhibhat (Margin) </h1>

I'm a backend developer with a growing passion for **distributed systems**, infrastructure, and building tools that scale.  
Currently a Computer Engineering undergrad graduating in 2026 — looking for internships and research opportunities in systems and software engineering.

## 🌱 A little about me

- 🎓 Computer Engineering @ [Chulalongkorn University](https://www.chula.ac.th/en/)
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

### Distributed Systems

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    🪵 Raft consensus algorithm + distributed key-value store
  </summary>
  <ul>
    <li>Raft: elections, heartbeats, log replication, and fault tolerance</li>
    <li>KV: persistence and exactly-once delivery</li>
    <li>Tech: Go</li>
    <li> <a href="https://github.com/bookpanda/raft" target="_blank">GitHub Repo</a>
    </li>
  </ul>
</details>

<details>
  <summary style="cursor: pointer; font-weight: bold;">
    🎈 Fly.io Distributed Systems Challenge
  </summary>
  <ul>
    <li>Snowflake ID, broadcast, grow-only counter, Kafka-style log, totally-available transactions</li>
    <li>Tech: Go</li>
    <li> <a href="https://github.com/bookpanda/fly-io-dist-sys" target="_blank">GitHub Repo</a>
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

|                                                                                               Cover                                                                                               | Anime                                                                                                                                                 |                                                                                            Cover                                                                                           | Anime                                                                                                                                                                     |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|                     <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx20593-ri6S0Qt3mFkv.jpg" alt="Hanamonogatari" style="width:70px;height:auto" />                     | <a href="https://anilist.co/anime/20593" target="_blank"><b>花物語</b></a> <br/> 10/7/2025 - 13/7/2025 (1 日前) <br/> <h3>7.8/10</h3>                      |         <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx17074-xMhVAZsEDH66.png" alt="Monogatari Series Second Season" style="width:70px;height:auto" />         | <a href="https://anilist.co/anime/17074" target="_blank"><b>〈物語〉シリーズ セカンドシーズン</b></a> <br/> 24/6/2025 - 9/7/2025 (5 日前) <br/> <h3>8.6/10</h3>                             |
| <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/b11981-koz1IoISs3eU.jpg" alt="Puella Magi Madoka Magica the Movie Part III: Rebellion" style="width:70px;height:auto" /> | <a href="https://anilist.co/anime/11981" target="_blank"><b>劇場版 魔法少女まどか☆マギカ 叛逆の物語</b></a> <br/> 22/6/2025 - 23/6/2025 (21 日前) <br/> <h3>8.4/10</h3>   |             <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx9756-QnUGwlwwnsuN.jpg" alt="Puella Magi Madoka Magica" style="width:70px;height:auto" />            | <a href="https://anilist.co/anime/9756" target="_blank"><b>魔法少女まどか☆マギカ</b></a> <br/> 14/6/2025 - 22/6/2025 (22 日前) <br/> <h3>8.7/10</h3>                                  |
|                     <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx11597-x2vd4KSHcI1S.jpg" alt="Nisemonogatari" style="width:70px;height:auto" />                     | <a href="https://anilist.co/anime/11597" target="_blank"><b>偽物語</b></a> <br/> 8/6/2025 - 14/6/2025 (30 日前) <br/> <h3>7.9/10</h3>                      |                  <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx177709-e5Qx6RlsBgD5.png" alt="SAKAMOTO DAYS" style="width:70px;height:auto" />                 | <a href="https://anilist.co/anime/177709" target="_blank"><b>SAKAMOTO DAYS</b></a> <br/> 19/5/2025 - 23/5/2025 (52 日前) <br/> <h3>8.1/10</h3>                              |
|                       <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx174788-9LsUnn0oEppv.jpg" alt="LOOK BACK" style="width:70px;height:auto" />                       | <a href="https://anilist.co/anime/174788" target="_blank"><b>ルックバック</b></a> <br/> 19/5/2025 - 19/5/2025 (56 日前) <br/> <h3>8.3/10</h3>                 |                  <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx5081-9GocceQ5Z865.jpg" alt="Bakemonogatari" style="width:70px;height:auto" />                  | <a href="https://anilist.co/anime/5081" target="_blank"><b>化物語</b></a> <br/> 13/5/2025 - 19/5/2025 (56 日前) <br/> <h3>8.2/10</h3>                                          |
|   <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx163134-yieRFbvUOH9a.jpg" alt="Re:ZERO -Starting Life in Another World- Season 3" style="width:70px;height:auto" />   | <a href="https://anilist.co/anime/163134" target="_blank"><b>Re:ゼロから始める異世界生活 3rd season</b></a> <br/> 6/4/2025 - 8/4/2025 (97 日前) <br/> <h3>9/10</h3> | <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx176496-9BDMjAZGEbq4.png" alt="Solo Leveling Season 2 -Arise from the Shadow-" style="width:70px;height:auto" /> | <a href="https://anilist.co/anime/176496" target="_blank"><b>俺だけレベルアップな件 Season 2 -Arise from the Shadow-</b></a> <br/> 29/3/2025 - 2/4/2025 (103 日前) <br/> <h3>9/10</h3> |

<details>

  <summary>最後の１００アニメ</summary>

  |                                                                                                                      Cover                                                                                                                      | Anime                                                                                                                                                                            |                                                                                                                  Cover                                                                                                                  | Anime                                                                                                                                                                    |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                                            <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx151807-it355ZgzquUd.png" alt="Solo Leveling" style="width:70px;height:auto" />                                            | <a href="https://anilist.co/anime/151807" target="_blank"><b>俺だけレベルアップな件</b></a> <br/> 23/3/2025 - 28/3/2025 (108 日前) <br/> <h3>8.3/10</h3>                                      |                              <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx151514-Y0d82Ah2ZOHX.jpg" alt="Orb: On the Movements of the Earth" style="width:70px;height:auto" />                             | <a href="https://anilist.co/anime/151514" target="_blank"><b>チ。-地球の運動について-</b></a> <br/> 12/3/2025 - 17/3/2025 (119 日前) <br/> <h3>8.5/10</h3>                            |
|                                  <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx9989-hImMg6kCMm6I.jpg" alt="Anohana: The Flower We Saw That Day" style="width:70px;height:auto" />                                  | <a href="https://anilist.co/anime/9989" target="_blank"><b>あの日見た花の名前を僕達はまだ知らない。</b></a> <br/> 22/2/2025 - 24/2/2025 (140 日前) <br/> <h3>8.2/10</h3>                               |                                           <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx1535-kUgkcrfOrkUM.jpg" alt="Death Note" style="width:70px;height:auto" />                                          | <a href="https://anilist.co/anime/1535" target="_blank"><b>DEATH NOTE</b></a> <br/> 12/1/2025 - 9/2/2025 (155 日前) <br/> <h3>9/10</h3>                                    |
|                                              <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx171018-60q1B6GK2Ghb.jpg" alt="DAN DA DAN" style="width:70px;height:auto" />                                             | <a href="https://anilist.co/anime/171018" target="_blank"><b>ダンダダン</b></a> <br/> 31/12/2024 - 6/1/2025 (189 日前) <br/> <h3>8.8/10</h3>                                            |                   <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx119661-GDbUZxrZMz01.png" alt="Re:ZERO -Starting Life in Another World- Season 2 Part 2" style="width:70px;height:auto" />                  | <a href="https://anilist.co/anime/119661" target="_blank"><b>Re:ゼロから始める異世界生活 2nd Season Part 2</b></a> <br/> 22/12/2024 - 26/12/2024 (200 日前) <br/> <h3>8.9/10</h3>      |
|                          <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx108632-lQWnmw7XaNOK.jpg" alt="Re:ZERO -Starting Life in Another World- Season 2" style="width:70px;height:auto" />                          | <a href="https://anilist.co/anime/108632" target="_blank"><b>Re:ゼロから始める異世界生活 2nd Season</b></a> <br/> 18/12/2024 - 22/12/2024 (204 日前) <br/> <h3>8.3/10</h3>                     |                           <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx21355-wRVUrGxpvIQQ.jpg" alt="Re:ZERO -Starting Life in Another World-" style="width:70px;height:auto" />                           | <a href="https://anilist.co/anime/21355" target="_blank"><b>Re:ゼロから始める異世界生活</b></a> <br/> 12/12/2024 - 18/12/2024 (208 日前) <br/> <h3>8.4/10</h3>                         |
|                                           <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx113717-9sNnN8WRgK15.jpg" alt="Ranking of Kings" style="width:70px;height:auto" />                                          | <a href="https://anilist.co/anime/113717" target="_blank"><b>王様ランキング</b></a> <br/> 4/12/2024 - 12/12/2024 (214 日前) <br/> <h3>8.2/10</h3>                                         |                                          <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx153288-25FBfFJzEQ5O.jpg" alt="Kaiju No.8" style="width:70px;height:auto" />                                         | <a href="https://anilist.co/anime/153288" target="_blank"><b>怪獣８号</b></a> <br/> 28/11/2024 - 3/12/2024 (223 日前) <br/> <h3>8.3/10</h3>                                    |
|                                <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx2904-Fet9Q33suC7G.jpg" alt="Code Geass: Lelouch of the Rebellion R2" style="width:70px;height:auto" />                                | <a href="https://anilist.co/anime/2904" target="_blank"><b>コードギアス 反逆のルルーシュ R2</b></a> <br/> 7/11/2024 - 27/11/2024 (229 日前) <br/> <h3>9.5/10</h3>                                |                              <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx1575-hsmWM2ydNm1m.jpg" alt="Code Geass: Lelouch of the Rebellion" style="width:70px;height:auto" />                             | <a href="https://anilist.co/anime/1575" target="_blank"><b>コードギアス 反逆のルルーシュ</b></a> <br/> 26/10/2024 - 6/11/2024 (250 日前) <br/> <h3>9/10</h3>                             |
|                                         <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx153518-IVXPDY5ph3kO.jpg" alt="Delicious in Dungeon" style="width:70px;height:auto" />                                        | <a href="https://anilist.co/anime/153518" target="_blank"><b>ダンジョン飯</b></a> <br/> 14/10/2024 - 26/10/2024 (261 日前) <br/> <h3>8.8/10</h3>                                         |                                       <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx99420-k5Tel6yRMwA8.png" alt="Girls' Last Tour" style="width:70px;height:auto" />                                       | <a href="https://anilist.co/anime/99420" target="_blank"><b>少女終末旅行</b></a> <br/> 9/10/2024 - 13/10/2024 (274 日前) <br/> <h3>8/10</h3>                                     |
|                                         <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx166531-dAL5MsqDHUkj.jpg" alt="Oshi no Ko Season 2" style="width:70px;height:auto" />                                         | <a href="https://anilist.co/anime/166531" target="_blank"><b>【推しの子】第2期</b></a> <br/> 3/10/2024 - 8/10/2024 (279 日前) <br/> <h3>8.7/10</h3>                                        |                         <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx162804-TBeptcAfvqTd.jpg" alt="Alya Sometimes Hides Her Feelings in Russian" style="width:70px;height:auto" />                        | <a href="https://anilist.co/anime/162804" target="_blank"><b>時々ボソッとロシア語でデレる隣のアーリャさん</b></a> <br/> 26/9/2024 - 2/10/2024 (285 日前) <br/> <h3>8.2/10</h3>                   |
|                           <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx21450-D7XFwEQjZ5GA.jpg" alt="JoJo's Bizarre Adventure: Diamond is Unbreakable" style="width:70px;height:auto" />                           | <a href="https://anilist.co/anime/21450" target="_blank"><b>ジョジョの奇妙な冒険 ダイヤモンドは砕けない</b></a> <br/> 7/9/2024 - 26/9/2024 (291 日前) <br/> <h3>8.4/10</h3>                             |                <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx20799-S1eyqBDlx51E.jpg" alt="JoJo's Bizarre Adventure: Stardust Crusaders - Battle in Egypt" style="width:70px;height:auto" />                | <a href="https://anilist.co/anime/20799" target="_blank"><b>ジョジョの奇妙な冒険 スターダストクルセイダース エジプト編</b></a> <br/> 31/8/2024 - 6/9/2024 (311 日前) <br/> <h3>8.4/10</h3>             |
|                             <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx20474-xuqem5GBlBtb.jpg" alt="JoJo's Bizarre Adventure: Stardust Crusaders" style="width:70px;height:auto" />                             | <a href="https://anilist.co/anime/20474" target="_blank"><b>ジョジョの奇妙な冒険 スターダストクルセイダース</b></a> <br/> 19/8/2024 - 30/8/2024 (318 日前) <br/> <h3>8.3/10</h3>                          |                                 <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx14719-VT5dRzTBSZ0w.jpg" alt="JoJo's Bizarre Adventure (TV)" style="width:70px;height:auto" />                                | <a href="https://anilist.co/anime/14719" target="_blank"><b>ジョジョの奇妙な冒険 (TV)</b></a> <br/> 8/8/2024 - 19/8/2024 (329 日前) <br/> <h3>8.2/10</h3>                            |
|                                            <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx164212-eKh15LQxkTEx.jpg" alt="Girls Band Cry" style="width:70px;height:auto" />                                           | <a href="https://anilist.co/anime/164212" target="_blank"><b>ガールズバンドクライ</b></a> <br/> 4/8/2024 - 7/8/2024 (341 日前) <br/> <h3>8.4/10</h3>                                         |                              <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx163078-akhThKoWpWOb.jpg" alt="Jellyfish Can’t Swim in the Night" style="width:70px;height:auto" />                              | <a href="https://anilist.co/anime/163078" target="_blank"><b>夜のクラゲは泳げない</b></a> <br/> 29/7/2024 - 3/8/2024 (345 日前) <br/> <h3>8.3/10</h3>                                |
|                                       <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx155908-2ZOxqbagDxNv.jpg" alt="Laid-Back Camp Season 3" style="width:70px;height:auto" />                                       | <a href="https://anilist.co/anime/155908" target="_blank"><b>ゆるキャン△ SEASON３</b></a> <br/> 22/7/2024 - 28/7/2024 (351 日前) <br/> <h3>8.1/10</h3>                                   |                     <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx166240-PBV7zukIHW7V.png" alt="Demon Slayer: Kimetsu no Yaiba Hashira Training Arc" style="width:70px;height:auto" />                     | <a href="https://anilist.co/anime/166240" target="_blank"><b>鬼滅の刃 柱稽古編</b></a> <br/> 20/7/2024 - 21/7/2024 (358 日前) <br/> <h3>8.4/10</h3>                                |
|                        <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx166873-xO0BRPkmwFll.png" alt="Mushoku Tensei: Jobless Reincarnation Season 2 Part 2" style="width:70px;height:auto" />                        | <a href="https://anilist.co/anime/166873" target="_blank"><b>無職転生Ⅱ ～異世界行ったら本気だす～ 第2クール</b></a> <br/> 12/7/2024 - 19/7/2024 (360 日前) <br/> <h3>8.6/10</h3>                        |                     <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx136804-7FVftG67FPBc.jpg" alt="KONOSUBA -God's blessing on this wonderful world! 3" style="width:70px;height:auto" />                     | <a href="https://anilist.co/anime/136804" target="_blank"><b>この素晴らしい世界に祝福を！３</b></a> <br/> 6/7/2024 - 10/7/2024 (369 日前) <br/> <h3>8.4/10</h3>                           |
|                                   <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx166216-vCMkF4e3x5FB.jpg" alt="The Dangers in My Heart Season 2" style="width:70px;height:auto" />                                  | <a href="https://anilist.co/anime/166216" target="_blank"><b>僕の心のヤバイやつ 第2期</b></a> <br/> 9/6/2024 - 17/6/2024 (392 日前) <br/> <h3>8.8/10</h3>                                     |                                     <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx98572-zJQd23nzJips.jpg" alt="Himouto! Umaru-chan R" style="width:70px;height:auto" />                                    | <a href="https://anilist.co/anime/98572" target="_blank"><b>干物妹! うまるちゃん R</b></a> <br/> 4/6/2024 - 8/6/2024 (401 日前) <br/> <h3>7/10</h3>                                 |
|                                                 <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx20987-9Tq7kZTeJPMo.jpg" alt="null" style="width:70px;height:auto" />                                                 | <a href="https://anilist.co/anime/20987" target="_blank"><b>干物妹！うまるちゃん</b></a> <br/> 21/5/2024 - 3/6/2024 (406 日前) <br/> <h3>6.6/10</h3>                                         |                                    <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx161645-QLbzHXiYRgV2.jpg" alt="The Apothecary Diaries" style="width:70px;height:auto" />                                   | <a href="https://anilist.co/anime/161645" target="_blank"><b>薬屋のひとりごと</b></a> <br/> 24/4/2024 - 18/5/2024 (422 日前) <br/> <h3>9/10</h3>                                   |
|                                              <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx66-ZqYQWl6LsfeI.png" alt="Azumanga Daioh" style="width:70px;height:auto" />                                             | <a href="https://anilist.co/anime/66" target="_blank"><b>あずまんが大王 THE ANIMATION</b></a> <br/> 30/4/2024 - 10/5/2024 (430 日前) <br/> <h3>7.7/10</h3>                                |                               <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx146066-zzKl6P6OeEjy.jpg" alt="Classroom of the Elite Season 3" style="width:70px;height:auto" />                               | <a href="https://anilist.co/anime/146066" target="_blank"><b>ようこそ実力至上主義の教室へ 3rd Season</b></a> <br/> 18/4/2024 - 23/4/2024 (447 日前) <br/> <h3>8.3/10</h3>                |
|                                    <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx154587-qQTzQnEJJ3oB.jpg" alt="Frieren: Beyond Journey’s End" style="width:70px;height:auto" />                                    | <a href="https://anilist.co/anime/154587" target="_blank"><b>葬送のフリーレン</b></a> <br/> 19/3/2024 - 2/4/2024 (468 日前) <br/> <h3>10/10</h3>                                           |                               <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx99426-ti5BL69Ip3kZ.png" alt="A Place Further Than the Universe" style="width:70px;height:auto" />                              | <a href="https://anilist.co/anime/99426" target="_blank"><b>宇宙よりも遠い場所</b></a> <br/> 12/3/2024 - 19/3/2024 (482 日前) <br/> <h3>8.6/10</h3>                                 |
|                                     <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx103047-odblDHHEdehK.jpg" alt="Violet Evergarden: the Movie" style="width:70px;height:auto" />                                    | <a href="https://anilist.co/anime/103047" target="_blank"><b>劇場版 ヴァイオレット・エヴァーガーデン</b></a> <br/> 12/3/2024 - 12/3/2024 (489 日前) <br/> <h3>8.7/10</h3>                             |                                  <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx101432-NQSedsCDQ6dP.png" alt="Violet Evergarden: Special" style="width:70px;height:auto" />                                 | <a href="https://anilist.co/anime/101432" target="_blank"><b>ヴァイオレット・エヴァーガーデン きっと"愛"を知る日が来るのだろう</b></a> <br/> 11/3/2024 - 11/3/2024 (490 日前) <br/> <h3>8.2/10</h3>       |
|                         <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx109190-e8mv1qdmpjLW.jpg" alt="Violet Evergarden: Eternity and the Auto Memory Doll" style="width:70px;height:auto" />                        | <a href="https://anilist.co/anime/109190" target="_blank"><b>ヴァイオレット・エヴァーガーデン 外伝~永遠と自動手記人形~</b></a> <br/> 10/3/2024 - 10/3/2024 (491 日前) <br/> <h3>8.3/10</h3>                   |                                       <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx21827-ubzq619ZA2E9.png" alt="Violet Evergarden" style="width:70px;height:auto" />                                      | <a href="https://anilist.co/anime/21827" target="_blank"><b>ヴァイオレット・エヴァーガーデン</b></a> <br/> 4/3/2024 - 9/3/2024 (492 日前) <br/> <h3>8.8/10</h3>                            |
|                                                <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx21234-XmqW39aQ9o7O.jpg" alt="ERASED" style="width:70px;height:auto" />                                                | <a href="https://anilist.co/anime/21234" target="_blank"><b>僕だけがいない街</b></a> <br/> 1/3/2024 - 3/3/2024 (498 日前) <br/> <h3>8.4/10</h3>                                            |                               <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx108725-ZKivuyr4Jtc9.jpg" alt="The Promised Neverland Season 2" style="width:70px;height:auto" />                               | <a href="https://anilist.co/anime/108725" target="_blank"><b>約束のネバーランド2</b></a> <br/> 20/2/2024 - 27/2/2024 (503 日前) <br/> <h3>6.8/10</h3>                               |
|                                        <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx101759-8UR7r9MNVpz2.jpg" alt="The Promised Neverland" style="width:70px;height:auto" />                                       | <a href="https://anilist.co/anime/101759" target="_blank"><b>約束のネバーランド</b></a> <br/> 17/2/2024 - 21/2/2024 (509 日前) <br/> <h3>9.2/10</h3>                                        |                     <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx114745-fBgTC12T7IAy.jpg" alt="Made in Abyss: The Golden City of the Scorching Sun" style="width:70px;height:auto" />                     | <a href="https://anilist.co/anime/114745" target="_blank"><b>メイドインアビス 烈日の黄金郷</b></a> <br/> 8/2/2024 - 16/2/2024 (514 日前) <br/> <h3>9.2/10</h3>                           |
|                                 <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx100643-fPH9OgEKKvcI.jpg" alt="Made in Abyss: Dawn of the Deep Soul" style="width:70px;height:auto" />                                | <a href="https://anilist.co/anime/100643" target="_blank"><b>メイドインアビス 深き魂の黎明</b></a> <br/> 7/2/2024 - 7/2/2024 (523 日前) <br/> <h3>9/10</h3>                                      |                                         <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx97986-TQ7dCgbS3y5s.jpg" alt="Made in Abyss" style="width:70px;height:auto" />                                        | <a href="https://anilist.co/anime/97986" target="_blank"><b>メイドインアビス</b></a> <br/> 25/1/2024 - 5/2/2024 (525 日前) <br/> <h3>9.4/10</h3>                                   |
|                                       <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx153152-Xnwmx7wuoIWV.jpg" alt="The Dangers in My Heart" style="width:70px;height:auto" />                                       | <a href="https://anilist.co/anime/153152" target="_blank"><b>僕の心のヤバイやつ</b></a> <br/> 10/1/2024 - 20/1/2024 (541 日前) <br/> <h3>8.2/10</h3>                                        |                                       <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx128893-Gc2t8b8M0mVu.jpg" alt="Hell’s Paradise" style="width:70px;height:auto" />                                       | <a href="https://anilist.co/anime/128893" target="_blank"><b>地獄楽</b></a> <br/> 28/12/2023 - 8/1/2024 (553 日前) <br/> <h3>8.3/10</h3>                                      |
|                                       <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx145064-hSNRJM03pvv1.jpg" alt="JUJUTSU KAISEN Season 2" style="width:70px;height:auto" />                                       | <a href="https://anilist.co/anime/145064" target="_blank"><b>呪術廻戦 第2期</b></a> <br/> 18/12/2023 - 29/12/2023 (563 日前) <br/> <h3>9.1/10</h3>                                       |                                       <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx131573-rpl82vDEDRm6.jpg" alt="JUJUTSU KAISEN 0" style="width:70px;height:auto" />                                      | <a href="https://anilist.co/anime/131573" target="_blank"><b>呪術廻戦 0</b></a> <br/> 28/12/2023 - 28/12/2023 (564 日前) <br/> <h3>8.5/10</h3>                                 |
|                             <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx140596-wBtzi7evAMlf.jpg" alt="DON'T TOY WITH ME, MISS NAGATORO 2nd Attack" style="width:70px;height:auto" />                             | <a href="https://anilist.co/anime/140596" target="_blank"><b>イジらないで、長瀞さん 2nd Attack</b></a> <br/> 6/12/2023 - 17/12/2023 (575 日前) <br/> <h3>7.8/10</h3>                          |                               <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx120697-BA2TqxB1I5bJ.jpg" alt="DON'T TOY WITH ME, MISS NAGATORO" style="width:70px;height:auto" />                              | <a href="https://anilist.co/anime/120697" target="_blank"><b>イジらないで、長瀞さん</b></a> <br/> 23/11/2023 - 5/12/2023 (587 日前) <br/> <h3>7.5/10</h3>                             |
|                           <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx20792-Q53sZsUAh5FF.jpg" alt="Fate/stay night: Unlimited Blade Works 2nd Season" style="width:70px;height:auto" />                          | <a href="https://anilist.co/anime/20792" target="_blank"><b>Fate/stay night [Unlimited Blade Works] 2ndシーズン</b></a> <br/> 11/11/2023 - 23/11/2023 (599 日前) <br/> <h3>8.1/10</h3> |                            <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx19603-ycT0pyEgDVQu.jpg" alt="Fate/stay night: Unlimited Blade Works" style="width:70px;height:auto" />                            | <a href="https://anilist.co/anime/19603" target="_blank"><b>Fate/stay night [Unlimited Blade Works]</b></a> <br/> 24/10/2023 - 10/11/2023 (612 日前) <br/> <h3>8.1/10</h3> |
|                      <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx162314-qIWdAAFtvY8J.jpg" alt="Attack on Titan Final Season THE FINAL CHAPTERS Special 2" style="width:70px;height:auto" />                      | <a href="https://anilist.co/anime/162314" target="_blank"><b>進撃の巨人 The Final Season完結編 後編</b></a> <br/> 5/11/2023 - 5/11/2023 (617 日前) <br/> <h3>9.1/10</h3>                     |                                      <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx11741-oEy1fJHYm2zJ.jpg" alt="Fate/Zero Season 2" style="width:70px;height:auto" />                                      | <a href="https://anilist.co/anime/11741" target="_blank"><b>Fate/Zero 2ndシーズン</b></a> <br/> 19/10/2023 - 23/10/2023 (630 日前) <br/> <h3>8.5/10</h3>                       |
|                                               <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx10087-M4Hd9qrHGrXk.png" alt="Fate/Zero" style="width:70px;height:auto" />                                              | <a href="https://anilist.co/anime/10087" target="_blank"><b>Fate/Zero</b></a> <br/> 7/10/2023 - 18/10/2023 (635 日前) <br/> <h3>8/10</h3>                                          |                        <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx146065-IjirxRK26O03.png" alt="Mushoku Tensei: Jobless Reincarnation Season 2" style="width:70px;height:auto" />                       | <a href="https://anilist.co/anime/146065" target="_blank"><b>無職転生Ⅱ ～異世界行ったら本気だす～</b></a> <br/> 27/9/2023 - 7/10/2023 (646 日前) <br/> <h3>8.4/10</h3>                      |
|                <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx141534-Tmnlz4mvYhaU.jpg" alt="Mushoku Tensei: Jobless Reincarnation Cour 2 - Eris the Goblin Slayer" style="width:70px;height:auto" />                | <a href="https://anilist.co/anime/141534" target="_blank"><b>無職転生 ～異世界行ったら本気だす～ 第2クール エリスのゴブリン討伐</b></a> <br/> 27/9/2023 - 27/9/2023 (656 日前) <br/> <h3>7.6/10</h3>              |                         <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx127720-ADJgIrUVMdU9.jpg" alt="Mushoku Tensei: Jobless Reincarnation Cour 2" style="width:70px;height:auto" />                        | <a href="https://anilist.co/anime/127720" target="_blank"><b>無職転生 ～異世界行ったら本気だす～ 第2クール</b></a> <br/> 21/9/2023 - 27/9/2023 (656 日前) <br/> <h3>8.8/10</h3>                 |
|                                <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx108465-1ANspF1EWyFx.jpg" alt="Mushoku Tensei: Jobless Reincarnation" style="width:70px;height:auto" />                                | <a href="https://anilist.co/anime/108465" target="_blank"><b>無職転生 ～異世界行ったら本気だす～</b></a> <br/> 12/9/2023 - 20/9/2023 (663 日前) <br/> <h3>8.5/10</h3>                               |                                        <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx113415-LHBAeoZDIsnF.jpg" alt="JUJUTSU KAISEN" style="width:70px;height:auto" />                                       | <a href="https://anilist.co/anime/113415" target="_blank"><b>呪術廻戦</b></a> <br/> 6/8/2023 - 13/9/2023 (670 日前) <br/> <h3>8.7/10</h3>                                      |
|                           <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx150075-QIGcA7oVyO6l.jpg" alt="KONOSUBA -An Explosion on This Wonderful World!" style="width:70px;height:auto" />                           | <a href="https://anilist.co/anime/150075" target="_blank"><b>この素晴らしい世界に爆焔を！</b></a> <br/> 24/7/2023 - 4/8/2023 (710 日前) <br/> <h3>7.7/10</h3>                                    |                                          <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx150672-WqmmwZ4nMzAy.png" alt="Oshi No Ko" style="width:70px;height:auto" />                                         | <a href="https://anilist.co/anime/150672" target="_blank"><b>【推しの子】</b></a> <br/> 12/7/2023 - 23/7/2023 (722 日前) <br/> <h3>8.5/10</h3>                                   |
|                                        <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx136430-gsBsJjA7hGh9.jpg" alt="Vinland Saga Season 2" style="width:70px;height:auto" />                                        | <a href="https://anilist.co/anime/136430" target="_blank"><b>ヴィンランド・サガ SEASON2</b></a> <br/> 21/6/2023 - 11/7/2023 (734 日前) <br/> <h3>8.9/10</h3>                                |                    <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx145139-rRimpHGWLhym.png" alt="Demon Slayer: Kimetsu no Yaiba Swordsmith Village Arc" style="width:70px;height:auto" />                    | <a href="https://anilist.co/anime/145139" target="_blank"><b>鬼滅の刃 刀鍛冶の里編</b></a> <br/> 16/6/2023 - 22/6/2023 (753 日前) <br/> <h3>8.3/10</h3>                              |
|                      <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx142329-kET1PIXJv2eW.jpg" alt="Demon Slayer: Kimetsu no Yaiba Entertainment District Arc" style="width:70px;height:auto" />                      | <a href="https://anilist.co/anime/142329" target="_blank"><b>鬼滅の刃 遊郭編</b></a> <br/> 7/6/2023 - 14/6/2023 (761 日前) <br/> <h3>8.6/10</h3>                                          |                        <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx129874-g6ZKXB94Hui1.jpg" alt="Demon Slayer: Kimetsu no Yaiba Mugen Train Arc" style="width:70px;height:auto" />                       | <a href="https://anilist.co/anime/129874" target="_blank"><b>鬼滅の刃 無限列車編 (TV)</b></a> <br/> 3/6/2023 - 6/6/2023 (769 日前) <br/> <h3>8.4/10</h3>                            |
|                                    <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx101922-WBsBl0ClmgYL.jpg" alt="Demon Slayer: Kimetsu no Yaiba" style="width:70px;height:auto" />                                   | <a href="https://anilist.co/anime/101922" target="_blank"><b>鬼滅の刃</b></a> <br/> 16/5/2023 - 3/6/2023 (772 日前) <br/> <h3>8.3/10</h3>                                              |                                     <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx131586-JhC0wcBi09EZ.jpg" alt="86 EIGHTY-SIX Part 2" style="width:70px;height:auto" />                                    | <a href="https://anilist.co/anime/131586" target="_blank"><b>86－エイティシックス－ 第2クール</b></a> <br/> 10/5/2023 - 17/5/2023 (789 日前) <br/> <h3>8.8/10</h3>                       |
|                                            <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx116589-qT34qzsZtk9V.jpg" alt="86 EIGHTY-SIX" style="width:70px;height:auto" />                                            | <a href="https://anilist.co/anime/116589" target="_blank"><b>86－エイティシックス－</b></a> <br/> 3/5/2023 - 10/5/2023 (796 日前) <br/> <h3>8.3/10</h3>                                      |                                   <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx104460-EwUV9ZJMCtnR.jpg" alt="Laid-Back Camp The Movie" style="width:70px;height:auto" />                                  | <a href="https://anilist.co/anime/104460" target="_blank"><b>映画 ゆるキャン△</b></a> <br/> 1/5/2023 - 2/5/2023 (804 日前) <br/> <h3>8.3/10</h3>                                  |
|                                        <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx104459-pywEKGQON613.jpg" alt="LAID-BACK CAMP SEASON2" style="width:70px;height:auto" />                                       | <a href="https://anilist.co/anime/104459" target="_blank"><b>ゆるキャン△ SEASON２</b></a> <br/> 24/4/2023 - 30/4/2023 (806 日前) <br/> <h3>8.3/10</h3>                                   |                                        <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx98444-Vzysp1EsrzgD.jpg" alt="Laid-Back Camp" style="width:70px;height:auto" />                                        | <a href="https://anilist.co/anime/98444" target="_blank"><b>ゆるキャン△</b></a> <br/> 17/4/2023 - 23/4/2023 (813 日前) <br/> <h3>8.1/10</h3>                                    |
|                                                <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx142770-dDaDIRnsv5jN.jpg" alt="Suzume" style="width:70px;height:auto" />                                               | <a href="https://anilist.co/anime/142770" target="_blank"><b>すずめの戸締まり</b></a> <br/> 19/4/2023 - 19/4/2023 (817 日前) <br/> <h3>8.2/10</h3>                                         |                                         <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx101348-2fhDFPCuMNiz.jpg" alt="Vinland Saga" style="width:70px;height:auto" />                                        | <a href="https://anilist.co/anime/101348" target="_blank"><b>ヴィンランド・サガ</b></a> <br/> 8/4/2023 - 17/4/2023 (819 日前) <br/> <h3>9.5/10</h3>                                 |
|                      <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx151384-gv0q8wOE6D58.jpg" alt="Kaguya-sama: Love is War -The First Kiss That Never Ends-" style="width:70px;height:auto" />                      | <a href="https://anilist.co/anime/151384" target="_blank"><b>かぐや様は告らせたい -ファーストキッスは終わらない-</b></a> <br/> 6/4/2023 - 7/4/2023 (829 日前) <br/> <h3>8.6/10</h3>                        |         <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx104174-aoNLSSN6bT4L.png" alt="Steins;Gate 0: Valentine's of Crystal Polymorphism -Bittersweet Intermedio-" style="width:70px;height:auto" />         | <a href="https://anilist.co/anime/104174" target="_blank"><b>シュタインズ・ゲート ゼロ 結晶多形のバレンタイン</b></a> <br/> 6/4/2023 - 6/4/2023 (830 日前) <br/> <h3>7.2/10</h3>                  |
|                                             <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx21127-7ARWZkDXKiiD.jpg" alt="Steins;Gate 0" style="width:70px;height:auto" />                                            | <a href="https://anilist.co/anime/21127" target="_blank"><b>シュタインズ・ゲート ゼロ</b></a> <br/> 28/3/2023 - 6/4/2023 (830 日前) <br/> <h3>8.7/10</h3>                                      |                             <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx143338-zhyDVYgEzsm5.png" alt="The Angel Next Door Spoils Me Rotten" style="width:70px;height:auto" />                            | <a href="https://anilist.co/anime/143338" target="_blank"><b>お隣の天使様にいつの間にか駄目人間にされていた件</b></a> <br/> 25/2/2023 - 5/4/2023 (831 日前) <br/> <h3>7.2/10</h3>                  |
|                                              <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx9253-tIUXF2gfU8Sg.jpg" alt="Steins;Gate" style="width:70px;height:auto" />                                              | <a href="https://anilist.co/anime/9253" target="_blank"><b>シュタインズ・ゲート</b></a> <br/> 19/3/2023 - 27/3/2023 (840 日前) <br/> <h3>9.2/10</h3>                                         | <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx21574-CTRsdAGe4mDp.png" alt="KONOSUBA -God's blessing on this wonderful world!: God's Blessings On This Wonderful Choker!" style="width:70px;height:auto" /> | <a href="https://anilist.co/anime/21574" target="_blank"><b>この素晴らしい世界に祝福を！ この素晴らしいチョーカーに祝福を!</b></a> <br/> 19/3/2023 - 19/3/2023 (848 日前) <br/> <h3>7.5/10</h3>          |
| <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/b97996-px2KGexuEZpg.jpg" alt="KONOSUBA -God's blessing on this wonderful world! 2: God's Blessings on These Wonderful Works of Art!" style="width:70px;height:auto" /> | <a href="https://anilist.co/anime/97996" target="_blank"><b>この素晴らしい世界に祝福を！ 2 この素晴らしい芸術に祝福を!</b></a> <br/> 19/3/2023 - 19/3/2023 (848 日前) <br/> <h3>7.4/10</h3>                   |             <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx102976-2Yi5icRbjukO.png" alt="KONOSUBA -God's blessing on this wonderful world!- Legend of Crimson" style="width:70px;height:auto" />            | <a href="https://anilist.co/anime/102976" target="_blank"><b>この素晴らしい世界に祝福を！紅伝説</b></a> <br/> 18/3/2023 - 18/3/2023 (849 日前) <br/> <h3>8.3/10</h3>                        |
|                          <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx21699-Fkbnkl9ZC6fW.png" alt="KONOSUBA -God's blessing on this wonderful world! 2" style="width:70px;height:auto" />                         | <a href="https://anilist.co/anime/21699" target="_blank"><b>この素晴らしい世界に祝福を！2</b></a> <br/> 11/3/2023 - 15/3/2023 (852 日前) <br/> <h3>8.4/10</h3>                                   |                       <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx21202-qQoJeKz76vRT.png" alt="KONOSUBA -God's blessing on this wonderful world!" style="width:70px;height:auto" />                      | <a href="https://anilist.co/anime/21202" target="_blank"><b>この素晴らしい世界に祝福を！</b></a> <br/> 6/3/2023 - 10/3/2023 (857 日前) <br/> <h3>8.3/10</h3>                             |
|                      <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx146984-GXrLeT6vQqyP.jpg" alt="Attack on Titan Final Season THE FINAL CHAPTERS Special 1" style="width:70px;height:auto" />                      | <a href="https://anilist.co/anime/146984" target="_blank"><b>進撃の巨人 The Final Season完結編 前編</b></a> <br/> 5/3/2023 - 5/3/2023 (862 日前) <br/> <h3>8.9/10</h3>                       |                                        <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx143270-rfkyiYXhek5w.jpg" alt="Lycoris Recoil" style="width:70px;height:auto" />                                       | <a href="https://anilist.co/anime/143270" target="_blank"><b>リコリス・リコイル</b></a> <br/> 18/2/2023 - 24/2/2023 (871 日前) <br/> <h3>8.4/10</h3>                                |
|                                         <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx132405-qP7FQYGmNI3d.jpg" alt="My Dress-Up Darling" style="width:70px;height:auto" />                                         | <a href="https://anilist.co/anime/132405" target="_blank"><b>その着せ替え人形は恋をする</b></a> <br/> 4/2/2023 - 18/2/2023 (877 日前) <br/> <h3>7.8/10</h3>                                     |                        <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/nx100049-mgvPLctBJprp.jpg" alt="Re:ZERO -Starting Life in Another World- OVAs" style="width:70px;height:auto" />                        | <a href="https://anilist.co/anime/100049" target="_blank"><b>Re:ゼロから始める異世界生活 OVAs</b></a> <br/> 3/2/2023 - 4/2/2023 (891 日前) <br/> <h3>7.6/10</h3>                       |
|                                             <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx127230-DdP4vAdssLoz.png" alt="Chainsaw Man" style="width:70px;height:auto" />                                            | <a href="https://anilist.co/anime/127230" target="_blank"><b>チェンソーマン</b></a> <br/> 2/1/2023 - 9/1/2023 (917 日前) <br/> <h3>8.7/10</h3>                                            |                                       <img src="https://s4.anilist.co/file/anilistcdn/media/anime/cover/medium/bx130003-HTDmeL4RGeJ4.png" alt="BOCCHI THE ROCK!" style="width:70px;height:auto" />                                      | <a href="https://anilist.co/anime/130003" target="_blank"><b>ぼっち・ざ・ろっく！</b></a> <br/> 30/12/2022 - 1/1/2023 (925 日前) <br/> <h3>9.1/10</h3>                               |

</details>
