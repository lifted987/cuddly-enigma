Create a modern, visually exciting web app called **“NewsAnime”** that transforms global news stories into short, engaging anime-style visual stories.

The app should take real-world news articles from around the world, summarize them accurately, and turn each story into an anime-inspired visual presentation while clearly separating **real facts from creative visualization**.

Use **HTML, CSS, and vanilla JavaScript** for the frontend. Make it beginner-friendly, responsive, interactive, and visually polished.

### CORE IDEA

Users can:

* Browse global news
* Search for news by topic or country
* Select a news story
* Read a short factual summary
* See the story transformed into anime-style scenes
* Navigate through scenes like a manga/anime episode
* Compare the original news information with the creative visualization
* Share interesting stories

### HOMEPAGE

Create a cinematic hero section:

**“The World, Reimagined as Anime.”**

Subtitle:

**“Turn today's global news into immersive anime-style stories.”**

Include:

* 🔎 Search news
* 🌍 Browse Global News
* 🔥 Trending Stories
* 📰 Latest News
* 🎬 Anime Stories

Add category buttons:

* 🌎 World
* 🏛 Politics
* 💰 Business
* 💻 Technology
* ⚽ Sports
* 🔬 Science
* 🌱 Climate
* 🎭 Entertainment

### NEWS CARDS

Each news story should display:

* News image/anime thumbnail
* Headline
* Country
* Category
* Publication time
* Short summary
* Source
* “Create Anime” button

Example:

**Major Technology Breakthrough Announced**

🌍 Japan
💻 Technology
🕐 2 hours ago

“Scientists announce a new development that could change the future of renewable energy.”

**[Watch Anime Version]**

### NEWS → ANIME EXPERIENCE

When the user selects a story, create an anime-story interface.

Show:

**REAL NEWS**

Headline
Source
Date
Location
Factual summary

Then:

**ANIME ADAPTATION**

Turn the story into a sequence of fictionalized anime scenes.

Example:

**Scene 01 — The Announcement**

A futuristic laboratory in Tokyo.

Narration:

“Scientists gathered early Tuesday morning to reveal a major breakthrough...”

**Scene 02 — The Discovery**

Researchers examine glowing technology inside a futuristic laboratory.

**Scene 03 — The Impact**

People around the world react to the announcement.

Make it clear that the anime visuals are a **creative representation of the real event**, not actual footage.

### ANIME PLAYER

Create a cinematic anime viewer containing:

* Large anime scene
* Scene number
* Story narration
* Captions
* Play/Pause
* Previous Scene
* Next Scene
* Progress bar
* Volume button
* Fullscreen button

Example:

```text
┌────────────────────────────────────┐
│                                    │
│          ANIME SCENE               │
│                                    │
│                                    │
│   “The world watches in silence...”│
│                                    │
├────────────────────────────────────┤
│ ●━━━━━━●━━━━━━━━━━━○              │
│ ◀ Previous     ▶ Play     Next ▶   │
└────────────────────────────────────┘
```

### VISUAL STYLE

Use a premium anime-inspired aesthetic:

* Dark cinematic background
* Deep navy/black
* Purple and blue gradients
* Bright accent colors
* Glowing UI elements
* Glassmorphism cards
* Large anime artwork
* Smooth transitions
* Dramatic typography
* Subtle particle effects
* Responsive animations

The design should feel like a combination of:

**Netflix + Crunchyroll + modern news website + manga reader.**

### NEWS CATEGORIES

Include dedicated sections for:

🌎 World News
🇺🇸 United States
🇬🇧 United Kingdom
🇳🇬 Nigeria
🇯🇵 Japan
🇨🇳 China
🇮🇳 India
🇪🇺 Europe
🌍 Africa

Allow users to select a country and see news from that region.

### SEARCH

Create an interactive search system.

Users can search:

* News headlines
* Countries
* Topics
* People
* Events

Examples:

“AI”

“Nigeria”

“Climate change”

“Space”

“Football”

Search results should update dynamically.

### NEWS FILTERS

Add filters for:

**Category**

* World
* Politics
* Business
* Technology
* Sports
* Science
* Entertainment

**Region**

* Africa
* Europe
* Asia
* North America
* South America
* Middle East
* Oceania

**Time**

* Latest
* Today
* This Week

### FACT-CHECK / SOURCE PANEL

Every story should include a clear information panel:

**Source:** News organization
**Published:** Date/time
**Location:** Country/city
**Original Article:** Link
**Last Updated:** Date/time

Add a visible label:

**FACTUAL NEWS**

And another label:

**CREATIVE ANIME VISUALIZATION**

Make it impossible for users to mistake fictional anime scenes for real news footage.

### STORY TIMELINE

For major news events, create a timeline:

```text
08:00 — Event begins
10:30 — Major announcement
12:15 — Officials respond
15:00 — Public reaction
18:00 — Latest development
```

Then allow each timeline event to become an anime scene.

### TRENDING SECTION

Create a section:

**🔥 Trending Worldwide**

Display stories based on popularity.

Each card should show:

* Headline
* Country
* Category
* Views
* Anime views
* Rating/popularity indicator

### USER FEATURES

Allow users to:

* ❤️ Save stories
* ⭐ Rate anime adaptations
* 🔖 Bookmark stories
* 📤 Share stories
* 🌓 Switch light/dark mode
* Choose preferred news categories
* Choose preferred countries

### RESPONSIVE DESIGN

Mobile:

* Full-screen anime viewer
* Swipe between scenes
* Bottom navigation
* Compact news cards

Tablet:

* Two-column news grid
* Larger anime viewer

Desktop:

* Large cinematic anime player
* News information sidebar
* Scene timeline
* Related stories panel

### NAVIGATION

Use:

**Home | News | Anime | Trending | Saved | Profile**

### EMPTY STATES

If there are no stories:

**“No news stories found.”**

If anime generation is unavailable:

**“Anime adaptation is currently unavailable. Try another story.”**

### LOADING STATES

Create animated skeleton loaders for:

* News cards
* Anime scenes
* Search results
* Story details

### SAMPLE DATA

Create sample news stories from different regions:

* Nigeria
* United States
* United Kingdom
* Japan
* China
* India
* France
* South Africa
* Brazil
* Australia

Clearly label sample/demo stories as **DEMO DATA**.

### IMPORTANT CONTENT RULES

Do not invent real-world events and present them as factual.

For real news:

* Preserve the original meaning.
* Do not fabricate quotes.
* Do not alter important facts.
* Show the original source.
* Show publication date.
* Clearly distinguish fact from fictional anime presentation.

The anime adaptation can use fictional characters, environments, dialogue, visual metaphors, and dramatic storytelling, but it must not imply that fictional scenes are authentic photographs or video of the real event.

### FUTURE AI FEATURES

Structure the frontend so it can later connect to AI services for:

* News summarization
* Storyboard generation
* Anime image generation
* Character generation
* Voice narration
* Text-to-speech
* Automatic subtitles
* Background music
* Video generation

For the first version, use placeholder anime images and sample storyboards.

### PROJECT STRUCTURE

Create:

```text id="1qjv6x"
newsanime/
├── index.html
├── style.css
├── script.js
├── images/
└── data/
    └── news.js
```

Use only **HTML, CSS, and vanilla JavaScript**.

Make the code beginner-friendly with comments explaining important sections.

The final result should feel like a futuristic platform where users can **discover real global news and experience each story through an engaging anime-style visual narrative**, while maintaining a clear distinction between factual reporting and creative visualization.
