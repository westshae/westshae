# Welcome to westshae's Github! (Last updated 20/9/24)

### My current focuses
Working on entreneurial full-stack development projects, both short term and long term.

### Experience
1. Computer Science degree with a cybersecurity specialization, Victoria University of Wellington
2. Previously: Junior Full-stack Developer at SportyNZ for 9 months using Typescript, Angular, C# .NET
3. Previously: Junior Automation Engineer at NZDF for 9 months using Powershell, Python, Azure, etc.

### Key Proficencies
1. TypeScript/Javascript: Primary language for all my full-stack projects (dozens of them) plus industry
2. NodeJS: Primary runtime used for all backend projects, current NestJS (Abstraction over ExpressJS)
3. ReactJS: Current primary framework.
4. Angular: Previous primary framework. Used for 6+ projects plus industry
5. Java: First language learnt (self-taught), used for entirety of university, used for a dozen minecraft plugin projects.
6. C#: Used for industry, plus large group university project.
7. Linux: Used for my personal device for 2+ years, as well as for hosting various Minecraft/Webdev projects.
8. GDScript: Used in a current game development project

### Standout Projects
1. Drinkers' Game: A ReactJS/ExpressJS/Typescript project. https://github.com/westshae/Drinkers-Game
This socketio-based project is a web-game made for my custom drinking game. Every 5-10 minutes, everyone connected to the lobby will receive a notification, in which they need to complete a certain action (answer a quiz right, do an action, etc), and those who didn't do it in time drink. It runs via rounds emitted via the backend, which loads player data/state from memory.

2. Roots' of Empires: A Godot GDScript-based project. https://github.com/westshae/Roots-of-Empires
This project is a local game made to be a mix between various strategy games from Paradox Interactive focused on alternative histories. It takes in a bunch of PNGs with data, such as height maps, rivers, water, land, cultural borders, and prints this data onto the game's primary PNG map, then splits all of these pixels into different provinces which hold the combination of all of its pixel's values.

3. Shaeo.org: A ReactJS/ExpressJS/Typescript project. https://github.com/westshae/Shaeo.org
This project was made as a channel to see if I could start and launch a potential startup project in 2 weeks. The project itself allows you to set structured goals, using the S.M.A.R.T goals framework. This project alos was used to learn stripe integration, and supabase authentication and DB api.

4. Website-Interactable-Element-Scraper: A JS/Puppeteer project. https://github.com/westshae/Website-Interactable-Element-Scraper
This project would go a website, scrape the links (Useful on website indexers), then go to those websites, take a screenshot of the entire page, then using the HTML plus the image, draw a box on the image (and save the coordinates) of all inputs, such as buttons, links, inputs, etc.

5. Social-Optim-Scripts: A JS/Puppeteer project. https://github.com/westshae/social-optim-scripts
This project was used to scrape Youtube data. This includes loading up Tor, going to the homepage, removing all unnecessary files (css, images, etc) and saving all of the links to channels, and would scroll down until youtube blocked it.
From here, it would go to each individual channel's videos page, and repeat this same process, but this time saving the video id, their subscribers, the video's views, and the video's thumbnail CDN link (no limiting), then would save all of this. There was also a script that iterates through all of the CDN thumbnail links and saved them.

6. Webgame: A Typescript/Angular/NestJS/DiscordBot/PostgreSQL Mono repo. https://github.com/westshae/webgame
This project was planned to be a massively-multiplayer online strategy game styled like civilization games. The key standout feature was your "character" was always online, and would make decisions when you were offline based on the decisions you made when offline, with a level of randomness based on how long you were offline. The entirety of the gameloop and logic was server side.

7. WorldQuests: A Java Minecraft Plugin. https://github.com/westshae/WorldQuests
A minecraft plugin that creates dynamic quests for the players of a server using the minecraft statistics api to detect how much of an action they've done to be more performant than recording every player event.

8. WarEffects: A Java Minecraft Plugin. https://github.com/westshae/wareffects
A minecraft plugin that emulates nuclear explosions/gas cloud for geo-politic servers. There is a command-given item which costs money (using VaultAPI), which when placed creates a field of particals that give certain minecraft effects to the players in range, such as poison, damaging, etc. These can be protected from using a custom set of armour, a hazmat suit, which uses weaker armour to add strategy to wars.

9. Settlements: A Java Minecraft Plugin: https://github.com/altoyamc/settlements
A minecraft plugin based on older factions plugins, with the intention for geo-politics servers. The key standout feature of this was instead of a "1 leader holds all the power" level control of the groups/factions, it implemented voting for actions. For example, inviting a new player to the group could be initiated by anyone, but it required a majority vote to pass. This plugin also implemented land claiming to protect land.
