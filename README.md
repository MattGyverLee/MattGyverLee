### Hi, I'm Matthew Lee

I build tools that bridge AI and the long tail of language work — software for linguists, Bible translators, and language communities who don't usually get first-class tooling.

I work at **SIL Global** in language technology, with a focus right now on making domain-specific software *agent-native* via the Model Context Protocol (MCP).

---

#### What I'm working on

**[FLExToolsMCP](https://github.com/MattGyverLee/FlexToolsMCP)** — An MCP server that lets Claude, Copilot, or Gemini write FLExTools scripts and manipulate FieldWorks lexicon data in natural language. Indexes ~1,400 LibLCM/FlexLibs functions so an AI can actually find the right call. Built in connection with SIL's AI Integration Advisory Board.

FLExToolsMCP can hanfle requests as small as: 
> *"Replace any instance of `k` with `c` in the lexeme form" → AI generates, tests, and runs the operation.*

Or as large as:
> *"Build for me a 2000 word sample FLEx lexicon for Swahili, complete with the necessary affixes set up the the parser with rules to handle phonological changes.*

**[FLExTools](https://github.com/MattGyverLee/flextools)** — Python scripting utility for SIL FieldWorks Language Explorer. The host environment FlexToolsMCP targets — every module the MCP generates ultimately runs here.

**[Prestige](https://github.com/MattGyverLee/prestige)** — A desktop + PWA player for **Basic Oral Language Documentation (BOLD)** corpora. Loads a SayMore session, shows synchronized video + multi-track waveforms + ELAN annotations, and runs offline so community teams can share oral histories without installing dev tooling. [Background paper (PhD defense)](https://mattgyverlee.github.io/docs/Matthew%20Lee%20Defense%20Copy.pdf).

**[Keyman](https://keyman.com)** — Open-source cross-platform keyboard input system supporting 2,000+ languages across Android, iOS, Windows, macOS, Linux, and the web. I contribute validation and parsing tooling and have been making the ecosystem AI-assistable.

**[Keyboard App Builder](https://software.sil.org/keyboardappbuilder/)** — SIL tool that wraps Keyman keyboards into branded Android apps so language communities can publish their own keyboards on Google Play. *(Repo is private; link goes to the product page.)*

---

#### Also worth a look

- **[flexlibs](https://github.com/MattGyverLee/flexlibs)** — Python library for FLEx projects. My **v2.0** rewrite adds comprehensive **Operations classes** (CRUD APIs organized by FLEx domain: Grammar, Lexicon, Texts & Words, Notebook, Lists, System), and **v2.2 Wrapper Classes + Smart Collections** that handle polymorphic FieldWorks types automatically — no more manual `ClassName` checks or casting. ~1,400 functions, fully backward-compatible with v1.x. This is the foundation FlexToolsMCP indexes.
- **[KeymanMCP](https://github.com/MattGyverLee/KeymanMCP)** & **[ParseKB](https://github.com/MattGyverLee/ParseKB)** — Making Keyman keyboard development AI-assistable; parsing and converting between keyboard formats.

---

#### Themes you'll see across my repos

- **MCP servers for specialized software** — FLEx, Keyman, and other tools whose user base is small enough that generic LLMs don't know the API surface.
- **Bible translation & Scripture engagement** — Paratext, FLEx, lectionaries, versification.
- **Linguistics & phonology** — phonetic transcription, distinctive features, oral corpora.
- **Lots of Python, increasing TypeScript**, plus whatever the host application speaks (C#, Pascal, XSLT).

---

Find me on GitHub: [@MattGyverLee](https://github.com/MattGyverLee)
