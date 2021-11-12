Hoi, ik ben Martijn. 👋 🇱🇺

I'm a passionate developer that loves working on projects and refining my skills. I taught myself to code back in 2004 (I also got a CS bachelor much later) and have worked on many different projects professionally and personally since then. I started off making huge messes in `PHP` (back when OOP was still uncommon), and have since touched many different languages such as `C#`, `Swift` and `Lua`, and now I have developed a passion for working with `React` and `TypeScript`.

---

If you want to know my professional experience, [my LinkedIn](https://www.linkedin.com/in/martijnhols/) has the highlights. If you want to hear me ramble very rarely, [my Twitter](https://twitter.com/MartijnHols) is the place to be. But if you're visiting my GitHub profile you are probably more interested in my Open Source work. Here are some of the Open Source highlights:

### WoWAnalyzer
https://github.com/WoWAnalyzer/WoWAnalyzer (AGPL)

<img height="100" align="right" src="https://user-images.githubusercontent.com/4565223/141450335-7e4cba09-e3d8-4848-89d8-80fe8dc35d6c.png" />

I started WoWAnalyzer back in 2017 and set up the framework for myself and others to be able to set up *analysis* as easily as possible. I wrote the majority of the architecture, React code, UI and UX, CI, and a fair amount of the more complicated analysis to make other contributors lives easier. This was the second large React project that I have created. Looking at it now I admit I think it's quite messy, but that's to be expected of >3 year old code that was developed before things like functional components, hooks, styled components, etc. I have gotten much more familiar with React and setting up the architecture for maintainable projects. This is by far my largest Open Source work.

### actions-cache
https://github.com/MartijnHols/actions-cache (MIT)

This is a fork of GitHub's [actions/cache](https://github.com/actions/cache) that gives full control over caching in CI allowing developers to achieve the quickest possible workflows (which in turn speeds up their development speed and happiness). In addition to what the standard action can do, this also allows you to use the cache to share artifacts across multiple jobs, prevent duplicate work and handle any special cases desirable. I also think using the manual control makes workflows more maintainable and the docs are pretty good if I say so myself. I use this in several private projects, and in WoWAnalyzer.

### iOS Edge Drag Navigation
https://gist.github.com/MartijnHols/709965559cbdb6b241c12e5866941e69

This is an article about how to properly handle page transitions when the user drags the edge of their screen to navigate back/forward in Safari. While short, it shows some of my modern design principles (although parts were omitted for simplification).

### @emico/eslint-config
https://github.com/EmicoEcommerce/eslint-config (MIT)

While I was working for Emico, we wanted an ESLint config that focussed on consistent quality code from all developers without getting in the way. None of the existing ESLint rulesets we could find met that criteria. To solve this [I developed](https://xkcd.com/927/) a custom ESLint config that only restricted important things while leaving code style issues to be automatically fixed in precommit hooks. This minimizes the interruptions while writing code, allowing developers to work at high speed while also keeping code style very consistent.
