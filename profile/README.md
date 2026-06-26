## 🎓 SELF UNIVERSITY — Tasks

### 🧩 Puzzles / Practicum Arena
- **Difficulty levels:** easy, medium, hard
- **Stack-Based mechanic:** each puzzle has multiple stacks (Stack 1, Stack 2, Stack 3, Stack 4) — you must select the correct answer for each stack
- **Scoring system:** correctness ratings (0.5, 0.7, 0.9, 1.0) — answers with varying degrees of correctness
- **XP rewards:** easy=50 XP, medium=70 XP, hard=100 XP
- **Acceptance Rate** — percentage of successful solutions
- **Attempts:** can be solved multiple times
- **Hints** when answering incorrectly (shows explanation)
- **Bookmarking system** for puzzles
- **Solutions:** users can publish their solutions in different languages (Python, JavaScript, C++, Text) and like others' solutions
- **Progress tracking:** shows which puzzles are solved and which are in progress
- **Filtering:** by difficulty (easy/medium/hard), by topic (TCP/IP, Memory, Encapsulation, Systems, Networking, Algorithms), search by name or number
- **Timer** — built-in stopwatch for tracking solving time
- **Terminal easter eggs** — solving puzzles in the terminal rewards coins

---

### 🖥️ Terminal (Puzzle Terminal)
- **Custom command line** directly on the website
- **Sound packs:** Cherry MX Blue, Typewriter, Windows XP Error (purchased in the shop)
- **Terminal fonts:** IBM Terminal, Futuristic, Comic Sans (purchased in the shop)
- **Commands:** help, clear, ping, curl, ip link, cat /proc/cpuinfo, cat /proc/meminfo, netstat, ps, whoami, date, echo
- **Secret commands** — easter eggs with rewards (coins)
- **Modes:** mini-window or fullscreen
- **Custom WebTerminal** for the homepage

---

### 📊 Knowledge Graph
- **Visualization of all puzzles** as a graph with nodes and edges
- **Color coding:** easy=green, medium=orange, hard=red
- **Animations:** glow on completed nodes, particle movement along edges
- **Interactivity:** zoom, pan (drag), hover tooltips
- **Filtering** by difficulty
- **Statistics:** how many solved, how many failed, completion percentage
- **Progress bar**

---

### 👤 User Profiles
- **Public profile** for every user (by username)
- **Information:** name, username, bio, location, GitHub, Twitter, website
- **Statistics:** XP, level, rank, modules, courses, puzzles, streak
- **Submission Grid** — GitHub-style activity grid for the past year (clickable, shows daily activity)
- **Course Circles** — progress visualization by course (TCP/IP, Memory, Algorithms, TLS)
- **Puzzle Circle** — ring progress bar for all puzzles (colored by difficulty)
- **Avatar with aura** — neon glow, matrix aura, lightning aura, or blue flame aura (purchased in shop)
- **Rank Badge** — animated rank icon next to avatar
- **Item collection** — shows equipped items (badges, themes)
- **User posts** on profile page

---

### 🏆 Progression System
- **XP (experience):** awarded for modules (+50), puzzles (50-100), daily login (5-1000)
- **Levels:** formula `level = floor(0.1 * sqrt(xp)) + 1`
- **Ranks (20 ranks):**
  - Novice → Apprentice → Scholar → Researcher → Engineer → Architect → Specialist → Expert → Master → Grandmaster → Sage → Titan → Oracle → Wizard → Phantom → Dragon → Phoenix → Leviathan → Immortal → Creator
- **Achievements:**
  - New User (10 XP)
  - First Steps (50 XP) — first module
  - Knowledge Seeker (150 XP) — 5 modules
  - Scholar (300 XP) — 10 modules
  - Network Guru (200 XP) — all TCP/IP modules
  - 7-Day Streak (150 XP)
  - Polyglot (400 XP) — modules in 3 different courses
- **Leaderboard** — global user ranking by XP
- **Global rank** — position in the overall leaderboard

---

### 🔥 Daily Streak
- **Daily login** with rewards:
  - Day 1: 5 XP
  - Day 2: 10 XP
  - Day 3: 15 XP
  - Day 7: 50 XP
  - Day 14: 100 XP
  - Day 30: 200 XP
  - Day 60: 500 XP
  - Day 100: 1000 XP
- **Streak Freeze:** protects streak for 1 missed day (1 free on registration, purchasable with coins)
- **Coins** for streaks (10-100 coins depending on day)
- **Visual display** of streak on profile (🔥 icon + day count)

---

### 💰 Shop & Economy
- **Currency:** coins
- **Item categories:**
  - **Badges:** Senior Tomato, Vibe Coder, Claude Hallucination, Legacy Grandpa, Junior JSON-Dependent, Rockstar Developer, Bug Magnet
  - **Themes:** Neon Hacker, Cyberpunk 2077, Deep Ocean, Sunset Vibes, Matrix
  - **Avatar Effects:** RGB Nickname (color cycling), Neon Avatar Glow, Matrix Aura, Lightning Aura, Blue Flame Aura
  - **Sound Packs:** Cherry MX Blue, Typewriter, Windows XP Error
  - **Terminal Fonts:** IBM Terminal, Futuristic, Comic Sans
  - **Anon Masks:** Guy Fawkes, Doge, Claude (for anonymous posting)
  - **Microphone:** pin post to top for 24 hours
  - **Cases:** Engineer (random), Senior (rare+), CTO (epic/legendary)
  - **Consumables:** Streak Freeze, XP Boost (2x for 24h), Coin Multiplier (2x for 24h)
- **Rarities:** common, rare, epic, legendary
- **Equipment:** can equip one item of each type
- **Case opening animation**

---

### 💬 Social Features
- **Posts (Feed):** create posts with text, mentions (@username), and tags
- **Anonymous posts:** via masks (Guy Fawkes, Doge, Claude)
- **Pin posts:** via microphone (globally pinned post)
- **Post comments:** with likes, replies, and deletion
- **Likes** on posts
- **Share** posts (copy link)
- **Polls:** create polls within posts, voting
- **Trends:** page with tags and content by topic, tag search
- **Global feed** of all users on `/users` page

---

### 💬 Group Chats
- **Create groups:** public and private (invite-only)
- **Send messages** with mentions (@username)
- **Edit and delete** your own messages
- **Invites** to private groups
- **Notifications** for invites
- **Member list** for groups
- **Roles:** owner and member
- **Delete group** (owner only)
- **Rate limit:** 3 groups per hour

---

### ⚔️ Duels
- **Create duel:** choose opponent, puzzle, wager (100-5000 coins)
- **Prize pool:** wager × 2
- **Accept/decline** duels
- **Timer:** 5 minutes to solve
- **Auto-forfeit** when time expires
- **Notifications** for duels (challenge, accepted, won, lost)
- **Solve puzzle** directly in chat (DuelPuzzleSolver)
- **Redirect to puzzle page** with `?duel=...` parameter
- **Anti-cheat:** must actually solve the puzzle

---

### 🤝 Friends System
- **Friends:** mutual follows (I follow you + you follow me)
- **Send gifts:** items and coins between friends
- **Display** friends on profile
- **"Friend" indicator** on profile

---

### 📝 Discussions
- **Create discussions** for modules
- **Tags** for categorization
- **Likes** on discussions
- **Comments** with nested replies
- **Sorting:** latest, popular, oldest
- **Delete** your own discussions and comments

---

### 📝 Blog
- **Static blogs** with MDX content
- **Likes** on blogs
- **Comments** with replies and likes
- **Bookmarks** on blogs
- **Interactive components** inside blogs (same as modules)

---

### 🔔 Notifications
- **Notification types:**
  - new_follower — new follower
  - achievement_earned — achievement unlocked
  - module_completed — module completed
  - rank_up — rank promotion
  - streak_milestone — streak milestone reached
  - chat_invite — chat invitation
  - duel_challenge — duel challenge
  - duel_won / duel_lost / duel_accepted
- **Bell icon** in header with unread count
- **Dropdown** with recent notifications
- **Full notifications page**
- **Mark all as read**

---

### 🔍 Search & Community
- **Users page:** search by name or username, sort by XP/modules/name
- **Top 3 leaderboard** with medals 🥇🥈🥉
- **Group chats** visible on Users page
- **Feed** of all posts on Users page

---

### 🎨 UI Customization
- **Themes:** light and dark (toggle via ThemeSwitch)
- **Custom themes** from the shop
- **RGB nickname** with color cycling animation
- **Avatar auras**
- **Sound packs** and **fonts** for terminal

---

### 🌐 Internationalization (i18n)
- **Two languages:** English and Russian
- **Toggle** in settings or via URL (`/en/...` or `/ru/...`)
- **Persistence** of language choice in cookies and localStorage
- **Translated:** interface, settings, notifications, shop, profiles, leaderboard

---

### ⚙️ Profile Settings
- Edit: username, bio, location, GitHub, Twitter, website
- Switch interface language

---

### 📄 Feedback
- **Types:** Bug Report, Feature Request, Improvement, Other
- **Private submissions** (visible only to admin)
- **Statuses:** new, acknowledged, fixed, closed
- **Voting** on submissions
- **Admin panel:** reply to submissions, change status
- **Delete** your own submissions

---

### 🔐 Authentication
- **Clerk** for authentication (Sign In / Sign Up)
- **Webhook** for syncing users with Convex
- **Route protection** — redirect to sign-in for unauthenticated users

---

### 📊 Analytics & Data
- **Convex** as real-time database
- **Tables:** users, submissions, followers, achievements, puzzles, shopItems, userInventory, duels, notifications, discussions, comments, posts, polls, groupChats, chatMessages, dailyLogins, bookmarks, notes, feedback, and more
- **Indexes** for fast queries

---

### 📱 Mobile-First Design
- Fully responsive interface
- Mobile Navigation (hamburger menu)
- Optimized for mobile devices
