<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1a1a2e&height=180&section=header&text=SHRUTI%20JADHAV&fontSize=42&fontColor=39FF14&fontAlignY=40&animation=fadeIn&desc=RAG%20Systems%20%E2%80%A2%20Computer%20Engineer%20%E2%80%A2%20Full-Stack%20Builder&descAlignY=58&descColor=8be9a8" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2500&pause=800&color=39FF14&center=true&vCenter=true&width=650&lines=%24+whoami;shruti+jadhav+%E2%80%94+computer+engineering%2C+mumbai;%24+cat+focus.txt;building+systems+that+retrieve%2C+reason%2C+and+respond;%24+status;shipping+narrow+and+reliable+%3E+broad+and+fragile)](https://git.io/typing-svg)

</div>

<br/>

```bash
guest@shruti-dev:~$ cat about.md
```

> I build systems that retrieve, reason, and respond — mostly RAG pipelines and the
> interfaces around them. I care less about listing every tool I've touched and more
> about what the thing actually does when someone uses it: does the answer stay
> grounded in the source, does the UI hold up under real use, does it break when the
> input isn't clean.
>
> Based in Mumbai. Computer Engineering background. Open to interesting problems.

<br/>

```bash
guest@shruti-dev:~$ cat how_i_work.md
```

- `01` I'd rather ship something narrow that works reliably than something broad that mostly works.
- `02` If a project uses a hosted API, I want to know what happens the day that API changes its pricing or its rate limits. That's part of why `pdf-rag-system` runs fully local.
- `03` I read the failure cases before I read the happy path. Most of what I learn on a project comes from the thing that broke, not the thing that worked on the first try.

<br/>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Toolbox.png" width="30"/> Selected Work

<br/>

<table>
<tr>
<td width="100%">

```diff
+ pdf-rag-system
```

**a PDF question-answering system, built to run fully local.**

Most RAG demos lean on a hosted API and call it done. This one doesn't: FastAPI backend, LangChain for orchestration, FAISS for the vector store, Llama 3.2 for generation — no external keys, no per-call billing.

The hard part wasn't wiring the pieces together, it was retrieval quality. Early versions would confidently answer from the wrong chunk of the document, or blend two unrelated sections into one answer. Getting that under control meant paying attention to chunk size and overlap, and being honest about when the model should say "not in this document" instead of guessing.

`Python` `FastAPI` `React` `LangChain` `FAISS` `Llama 3.2`

</td>
</tr>

<tr>
<td width="100%">

```diff
+ Gemini-clone
```

**a from-scratch rebuild of Gemini's chat interface.**

Real-time streaming responses, persistent chat history, a UI considered enough that it doesn't feel like a demo. The point wasn't to have a chatbot project on the profile — it was to understand what a production chat product actually has to handle: partial message state while streaming, history that survives a refresh, an interface that doesn't jank when responses arrive in chunks instead of all at once.

`React` `JavaScript`

</td>
</tr>

<tr>
<td width="100%">

```diff
+ sign-language-recognition
```

**a sign language recognition model, in progress.**

Early-stage computer vision work exploring how far a lightweight model can get on gesture classification before reaching for heavier architectures like LSTMs. Still figuring out where a simpler model is enough and where the extra complexity actually earns its keep.

`Python`

</td>
</tr>
</table>

<br/>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" width="30"/> Stack

<div align="center">

![Python](https://img.shields.io/badge/-Python-0d1117?style=for-the-badge&logo=python&logoColor=39FF14)
![React](https://img.shields.io/badge/-React-0d1117?style=for-the-badge&logo=react&logoColor=39FF14)
![FastAPI](https://img.shields.io/badge/-FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=39FF14)
![LangChain](https://img.shields.io/badge/-LangChain-0d1117?style=for-the-badge&logo=chainlink&logoColor=39FF14)
![JavaScript](https://img.shields.io/badge/-JavaScript-0d1117?style=for-the-badge&logo=javascript&logoColor=39FF14)
![Flask](https://img.shields.io/badge/-Flask-0d1117?style=for-the-badge&logo=flask&logoColor=39FF14)
![Vite](https://img.shields.io/badge/-Vite-0d1117?style=for-the-badge&logo=vite&logoColor=39FF14)
![SQLite](https://img.shields.io/badge/-SQLite-0d1117?style=for-the-badge&logo=sqlite&logoColor=39FF14)
![Git](https://img.shields.io/badge/-Git-0d1117?style=for-the-badge&logo=git&logoColor=39FF14)

</div>

<br/>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" width="30"/> Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=shruti11931&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=39FF14&icon_color=39FF14&text_color=8be9a8" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=shruti11931&theme=dark&hide_border=true&background=0d1117&stroke=39FF14&ring=39FF14&fire=39FF14&currStreakLabel=39FF14" width="49%"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shruti11931&theme=react-dark&hide_border=true&bg_color=0d1117&color=39FF14&line=39FF14&point=8be9a8" width="98%"/>

</div>

<br/>

<div align="center">

```bash
guest@shruti-dev:~$ echo "open to interesting problems"
open to interesting problems
guest@shruti-dev:~$ _
```

[![Email](https://img.shields.io/badge/-shrutijadhav112008%40gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=39FF14)](mailto:shrutijadhav112008@gmail.com)

<!-- <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:0d1117&height=100&section=footer" width="100%"/> -->

</div>
