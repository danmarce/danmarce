@danmarce is a software developer in Ecuador. I work for @BMICompanies.

AS I'm old, I know a lot of things, several dialects of SQL, C#, VB, VB.Net, Batch, SH, Python, Clarion (yes, this is an obscure one), how to do electrical wiring, build a computer, fix things (you know, right to repair) and configure operating systems.

But all is hard earned. In 2015 I lost a lot of my files, code, drawings, stories, as I prioritized privacy over offside backups. The few things that survived, I uploaded here, Open Source. These are old, and they have limited usefulness. 

With the loss, I got busy with life and work, and almost not did personal projects. Too tired, too little time. Still I was able to create a nice home-lab 

It was the advent of modern LLMs that helped me retake things. I can design more, code less, and still learn. So I've created a few things. My personal policy enforces that if something is created with an LLM involved, I'll disclose it, and open source the code, as a way to give back. I want to be positive, and I think that LLMs will help Open Source, as more people will be able to create things. Yes, there is a lot of things coded on vibes, but there is also lots of experienced developers who are creating things.

[annoyances.studio](https://github.com/annoyances-studio) is a small org that I created to solve things I find annoying. The first app is [Margin•](https://github.com/annoyances-studio/margin), a simple note taking app, to replace alternatives, and store notes in plain markdown and folders. You can pick the storage back-end. It also works a "reader" for documentation generated in markdown, for example Claude skills or documentation repositories.

I've build note taking apps across the decades, one example is in the old code, but Margin , is the fist one really multi-platform.

As for LLMs, well I am more on researching and local models in my lab. With limited resources, you need to be creative. This is why the MCP Siblings exist. The purpose of them is to give more "Intelligence" to a small model, hopefully allowing more people to run these models at home.

>Someone has said that **the cleverest people are not those who know everything, but those who know where to look for and find any information that is at the moment required.** Which is only another way of saying that they have methodical minds and habits and know how and where to store their knowledge
>Victor Steinbok 

The siblings, are designed to be deployed using docker. I hope you might find something useful

- [adsb-mcp](https://github.com/danmarce/adsb-mcp): Is a set of tools for people with ADS-B feeder, will allow an LLM to answer questions about planes overhead. It adds a FIDS board for your old devices or Home Assistant

- [weather-mcp](https://github.com/danmarce/weather-mcp): Weather, so the LLM can answer about it. Returns a "plate" with the weather (this can be an image or text, if your LLM client is stdio as Claude Code), an also returns as text, do the LLM can understand it.

- [search-mcp](https://github.com/danmarce/search-mcp): A simple search tool using DDGS. A local LLM NEEDS a search tool, to find current information.

- [news-mcp](https://github.com/danmarce/news-mcp): This one will collect information from RSS feeds and store it, It does so every few minutes. This way the LLM an answer if you ask for news, and even a small LLM can translate this to your language.

- [igepn-mcp](https://github.com/danmarce/igepn-mcp): A tool to show information about geophysical events in Ecuador, so the LLM can ask about local volcanoes and earthquakes.

- [forge-mcp](https://github.com/danmarce/forge-mcp): A tool to generate images using Forge. This adds image generation to a small model (Or even Claude itself, it is pretty good at prompting)
