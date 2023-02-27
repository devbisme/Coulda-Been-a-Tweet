# Consistency

They say the most important thing in any endeavor is *consistency*. This is where I'll try to write something *every day*. It won't be much, probably just a link or two to something I've read. All the entries will be chronological, with the newest at the top.

------------------------------------------
### Feb 27, 2023
+ This [blog post](https://newsletter.theaiedge.io/p/deep-neural-networks-all-the-building?publication_id=1238074&post_id=103792603&isFreemail=true) contains a good timeline with links to important papers in deep learning.

------------------------------------------
### Feb 26, 2023
+ [In-Q-Tel](https://www.iqt.org/) is basically the venture capital arm of the US intelligence community (think CIA). Here is one of [their reports](https://assets.iqt.org/pdfs/The_Biorevolution_Feb_2023.pdf/web/viewer.html) describing how the ability to both read and *write* DNA will affect national security and economic competitiveness.

------------------------------------------
### Feb 25, 2023
+ I updated my [KiCad on Docker repo](https://github.com/devbisme/docker_kicad) so it supports versions 5, 6 and 7. Now I can run any of those versions with a simple command like `kicad5` and they don't interfere with each other.

------------------------------------------
### Feb 24, 2023
+ I ordered one of these [CH32V003 RISC-V microcontroller dev kits](https://www.aliexpress.us/item/3256804709476544.html?spm=a2g0o.productlist.main.1.725670cdLyYDkV&algo_pvid=695670c4-a9f6-4d50-833c-17991705eead&algo_exp_id=695670c4-a9f6-4d50-833c-17991705eead-0&pdp_ext_f=%7B%22sku_id%22%3A%2212000030983160842%22%7D&pdp_npi=3%40dis%21USD%2112.5%2111.87%21%21%21%21%21%40210212c016772437895204285d0724%2112000030983160842%21sea%21US%21162974069&curPageLogUid=IVAZeaas6Tv2). Shipping is more than the cost of the kit!
+ [AlphaCode](https://www.deepmind.com/blog/competitive-programming-with-alphacode) is an AI from DeepMind specifically aimed at the task of generating good solutions for competitive coding contests.

------------------------------------------
### Feb 23, 2023
+ I pointed to [PlantUML](https://plantuml.com/) a few days ago and now here's a [Mermaid cheatsheet](https://jojozhuang.github.io/tutorial/mermaid-cheat-sheet/) for doing similar text-based graphics within a Markdown file. All these things seem to rely on the remarkably long-lived [graphviz](https://graphviz.org/) tool.

------------------------------------------
### Feb 22, 2023
+ Looks like we have another web-based PCB design suite: [Flux](https://docs.flux.ai/). Your design is stored in their central database and I'm not sure if you can export your design files. So what happens if the company ceases to exist or if the server is just down?
+ [Lots of interest in demographics](https://stenoresearch.com/watch-series/introducing-the-problem-index-which-countries-have-the-worst-demographics/) since the developed/developing world has a problem keeping their birthrates above replacement level. Check out the [South Korean birthrate](https://www.bloomberg.com/news/articles/2023-02-22/south-korea-fertility-rate-falls-again-adding-to-economic-risks).

------------------------------------------
### Feb 21, 2023
+ This [Dockerfile](https://github.com/code2k13/pipico_build_setup) gives you a self-contained build environment for Raspberry Pico programs.
+ Want to program the 10&cent; [CH32V003 microcontroller](http://www.wch-ic.com/products/CH32V003.html) but hate the idea of using their proprietary tools? This [repo](https://github.com/cnlohr/ch32v003fun) supports an open source alternative using GCC.
+ [Extensive guide](https://github.com/dair-ai/Prompt-Engineering-Guide) to prompt engineering for various generative AI tools.
+ Here's a [large categorized list of EDA tools](https://hdl.github.io/awesome/) for describing electronic systems.

------------------------------------------
### Feb 20, 2023
+ Raspberry Pi is selling a [small hardware debug module](https://www.raspberrypi.com/news/raspberry-pi-debug-probe-a-plug-and-play-debug-kit-for-12/) to make it easier to access the SWD port of a Pico (or any other ARM processor).
+ Just to maintain the ARM theme, here's [part 1](https://thechipletter.substack.com/p/the-arm-story-part-1-from-acorns-6e2?publication_id=1063960&post_id=100242940&isFreemail=true) and [part 2](https://thechipletter.substack.com/p/the-arm-story-part-2-archimedes-to-4fd) of a history about ARM.
+ [Here's](https://github.com/Ying1123/FlexGen) another FOSS solution for running large language modules with just a single GPU.

------------------------------------------
### Feb 19, 2023
+ Somewhere on my travels through ChatGPT-land, I ran across [Colossal-AI](https://www.hpc-ai.tech/blog/colossal-ai-chatgpt), a FOSS toolkit for replicating ChatGPT using fewer compute resources (i.e., GPUs) and with faster training. I'm not expert enough and haven't tried it to see if that's true or just BS. But it's open source so you can look for yourself.
+ If you're into making animated visualizations in the browser, [SwissGL](https://github.com/google/swissgl) is a minimalistic wrapper on top of the WebGL2 JS API. This looks like a quick way to get GPU-assisted visualizations onto the web.
+ [What will soda cans look like in forty years?](https://www.reddit.com/r/Futurology/comments/116f83f/given_how_soda_cans_have_changed_over_the_years/)

------------------------------------------
### Feb 18, 2023
+ I was reading this [article](https://aruva.medium.com/using-chatgpt-to-build-system-diagrams-part-i-69efc7603926) about using ChatGPT to create system modeling diagrams by having it output markdown containing Mermaid (which is amazing by itself). But this led me to the FOSS tool [PlantUML](https://plantuml.com/) that lets you generate many types of diagrams from a text description: UML, mindmaps, mathematics, etc. Using ChatGPT to drive text-based tools like these with natural language inputs gives them capabilities that aren't readily available in GUI-based tools.
+ Interesting [article](https://foreignpolicy.com/2023/02/16/ukraine-russia-war-drone-warfare-china/) about how both Ukraine and Russia are somewhat dependent upon drones from a private company ([DJI](https://www.dji.com/)) in China. DJI has applied geofencing to restrict the use of their drones in wars in the Middle East, but not in Ukraine (so far).

------------------------------------------
### Feb 17, 2023
+ Meta is handing out a lot of [negative reviews to its workers](https://www.wsj.com/articles/og-mark-returns-at-meta-as-facebook-parent-gives-thousands-of-staff-subpar-reviews-56e648b4). It also wants to [solve the noise problem](https://www.wsj.com/articles/inside-metas-push-to-solve-the-noisy-office-ba43042) in its offices. I guess having fewer employees would be one way to do that...
+ This [article](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/) covers how ChatGPT works. Along the way, it talks about models, neural nets, training, embeddings, semantics, etc. I haven't read it in detail, but I plan to. Better than reading WSJ articles about Meta...

------------------------------------------
### Feb 16, 2023
+ I use [PySpice](https://pypi.org/project/PySpice/) as a Python interface to ngspice to provide circuit simulation capabilities in [SKiDL](https://github.com/devbisme/skidl). Now there's a fork called [OpenSPICE](https://github.com/thejackal360/OpenSPICE) that adds a native Python simulator. There's not a lot of documentation I could find outside of [this article](https://hackaday.com/2023/02/14/openspice-a-portable-python-circuit-simulator/). In the comments, there's also a link to [PyLTSpice](https://pypi.org/project/PyLTSpice/) which lets you drive LTSpice through a Python interface.

------------------------------------------
### Feb 15, 2023
+ I've always been interested in forecasting, even though I suck at it. [Superforecasting](https://www.amazon.com/Superforecasting-Science-Prediction-Philip-Tetlock-ebook/dp/B00RKO6MS8) is a great book on how to make better predictions of the future, and [this article](https://www.arcdigital.media/p/superforecasters-in-the-cosmic-bazaar?r=lle6p) is a good, broad-brush exposition of the principles.
+ I frequently use the website [remove.bg](https://www.remove.bg/) to get rid of backgrounds in images I want to use as clip-art. I just ran across the [rembg](https://pypi.org/project/rembg/#description) Python package that does the same thing locally, and the code can be viewed [here](https://github.com/danielgatis/rembg).
+ [New private-sector, DARPA-like organizations](https://www.spec.tech/library/introducing-speculative-technologies) are springing up to advance foundational technologies. 

------------------------------------------
### Feb 14, 2023
+ Maybe you're like me: sometimes you use Pandas, but you don't really *know* Pandas. If so, [this *extensive* visual guide to Pandas](https://betterprogramming.pub/pandas-illustrated-the-definitive-visual-guide-to-pandas-c31fa921a43) may be for you. (Note: This is hosted on Medium so you may be able to view it or you may not. Who knows...) And if actually learning how it works is too much, there's a Python package called [sketch](https://pypi.org/project/sketch/) that uses AI to assist you in using Pandas.

------------------------------------------
### Feb 13, 2023
+ Looks like Z Library [isn't going down without a fight](https://torrentfreak.com/z-library-returns-on-the-clearnet-in-full-hydra-mode-230213/).
+ I'm a big fan of using programming languages for doing CAD work. [GhostSCAD]() puts a Go wrapper around OpenSCAD to achieve that. CadQuery (Python) and JSCad (Javascript) are other alternatives mentioned in the comments.
+ [Maya Posch](https://hackaday.com/author/mayaposch/) writes a lot of good articles at Hackaday like this one on [methane pyrolysis](https://hackaday.com/2023/02/13/methane-pyrolysis-producing-green-hydrogen-without-carbon-emissions/). Also check out the [mining and refining](https://hackaday.com/tag/mining-and-refining/) section by [Dan Maloney](https://hackaday.com/author/dpsm64/) for facts about the stuff that makes up our industrial society.

------------------------------------------
### Feb 12, 2023
+ Japan is going [full bore on nuclear](https://japannews.yomiuri.co.jp/business/companies/20230210-90175/). Looks like the government will be paying for their share of the build-out by charging "carbon fees" to companies using fossil fuels.
+ Looks like Intel Foundry service [isn't going to be directly supporting RISC-V](https://www.electropages.com/blog/2023/01/intel-terminates-risc-v-development-project-what-happened).

------------------------------------------
### Feb 11, 2023
+ You can get a lot of prepackaged Docker containers for FOSS EDA tools [here](https://hdl.github.io/containers/). [This page](https://hdl.github.io/containers/ToolsAndImages.html) lists the available tools. Most of these are HDL/FPGA/VLSI design tools so don't expect to get containers for things like KiCad and FreeCAD.
+ A while ago, I built a [Docker container for KiCad](https://github.com/devbisme/docker_kicad5). It's for version 5, but it should be easy to modify it for versions 6 and 7 (when it becomes available).

------------------------------------------
### Feb 10, 2023
+ [Here's](https://www.hackster.io/news/one-man-s-trash-is-another-man-s-compute-cluster-b6735c5d8385) the latest effort to repurpose old smartphones into a compute cluster. Unfortunately, the phones are loaded with the [Ubuntu Touch](https://ubuntu-touch.io/) linux variant and that isn't supported on any of the old phones I have lieing around.
+ A couple of pro-nuke articles about [uninformed fears of nuclear waste](https://zionlights.substack.com/p/everything-i-believed-about-waste-was-wrong) and [the nuclear renaissance](https://quillette.com/2023/02/09/the-dawn-of-nuclear-energy-abundance/).

------------------------------------------
### Feb 9, 2023
+ Instead of [running Doom on a soldering iron](https://www.youtube.com/watch?v=qCC941xKuBs), it seems the new trend is to implement ChatGPT in as few lines as possible. [Here's one](https://jaykmody.com/blog/gpt-from-scratch/) that does it in 60 lines of NumPy.

------------------------------------------
### Feb 8, 2023
+ Last week, America was incensed that [a Chinese spy ballon traversed our airspace](https://www.reuters.com/world/us-briefed-40-nations-china-spy-balloon-incident-diplomats-official-say-2023-02-08/). This week, we learned that [we blew up Russia's Nordstream gas supply lines](https://seymourhersh.substack.com/p/how-america-took-out-the-nord-stream?r=5mz1)...

------------------------------------------
### Feb 7, 2023
+ I finished ["How to Drive a Nuclear Reactor"](https://www.amazon.com/Drive-Nuclear-Reactor-Springer-Praxis/dp/3030338754). It describes the systems of a **P**ressurized **W**ater **R**eactor (the most common type) and how a control-room operator starts, manages, and stops it. It's a bit more technical than your standard popsci book, but not as challenging as a textbook. Worth a read if you're interested in nuclear power.
+ [Helion Energy](https://research.contrary.com/reports/helion-energy) is trying to build a 50MW fusion reactor that fits in a shipping container and costs $10M by 2030. Seems wildly optimistic but I look forward to being surprised.

------------------------------------------
### Feb 6, 2023
+ Over the course of my life, I've noticed that being smart (or being acknowledged as smart) has ascended in importance. But I would say that most people labeled as smart are merely *adept* (skilled within some area of knowledge). I think that [OODA](https://en.wikipedia.org//wiki/OODA_loop) provides a better framework to judge a person's intelligence by seeing if they can 1) **O**bserve things others don't notice, 2) **O**rient them into an existing set of facts, 3) **D**ecide what to do based on this new knowledge, and 4) actually **A**ct upon their decision. The number of people who can do this in one field, much less many, is *extremely* small. They often don't fit the stereotype of *smart*. And I am not one of them.
+ There's been a lot of talk-talk recently by US "thought leaders" about re-emphasizing manufacturing. [This article](https://danwang.co/definite-optimism-as-human-capital/) beats the same drum, except it's from 2017. So the talk has been going on for a while. Despite things like the CHIPS Act and the Inflation Reduction Act (LOL), I'm still waiting to see increases in manufacturing employment. Or lots and lots of robots...
+ [K6](https://k6.io) will generate “virtual users” who continuously run test scenarios defined using Javascript.

------------------------------------------
### Feb 5, 2023
+ Interesting [blog post by Jay Carlson](https://jaycarlson.net/2023/02/04/the-cheapest-flash-microcontroller-you-can-buy-is-actually-an-arm-cortex-m0/) about a new Cortex-M0+ microcontroller that costs less than 10&#162;.
+ Ian Norris - Blog - Understanding the limits of large language models https://inorris.com/Blog/GPT/ 
