<img src="./banner.svg" width="100%" />

<br/>

I build systems that retrieve, reason, and respond — mostly RAG pipelines and
the interfaces around them. I care less about listing every tool I've touched
and more about what the thing actually does when someone uses it: does the
answer stay grounded in the source, does the UI hold up under real use, does
it break when the input isn't clean.

Based in Mumbai. Computer Engineering background. Open to interesting problems.

<br/>

### How I work

- I'd rather ship something narrow that works reliably than something broad
  that mostly works.
- If a project uses a hosted API, I want to know what happens the day that
  API changes its pricing or its rate limits. That's part of why `pdf-rag-system`
  runs fully local.
- I read the failure cases before I read the happy path. Most of what I learn
  on a project comes from the thing that broke, not the thing that worked
  on the first try.

<br/>

### Selected work

**pdf-rag-system** — a PDF question-answering system, built to run fully local.
> Most RAG demos lean on a hosted API and call it done. This one doesn't:
> FastAPI backend, LangChain for orchestration, FAISS for the vector store,
> Llama 3.2 for generation — no external keys, no per-call billing.
>
> The hard part wasn't wiring the pieces together, it was retrieval quality.
> Early versions would confidently answer from the wrong chunk of the document,
> or blend two unrelated sections into one answer. Getting that under control
> meant paying attention to chunk size and overlap, and being honest about
> when the model should say "not in this document" instead of guessing.
>
> `Python` · `FastAPI` · `React` · `LangChain` · `FAISS` · `Llama 3.2`

**Gemini-clone** — a from-scratch rebuild of Gemini's chat interface.
> Real-time streaming responses, persistent chat history, a UI considered
> enough that it doesn't feel like a demo. The point wasn't to have a chatbot
> project on the profile — it was to understand what a production chat product
> actually has to handle: partial message state while streaming, history that
> survives a refresh, an interface that doesn't jank when responses arrive in
> chunks instead of all at once.
>
> `React` · `JavaScript`

**sign-language-** — a sign language recognition model, in progress.
> Early-stage computer vision work exploring how far a lightweight model can
> get on gesture classification before reaching for heavier architectures like
> LSTMs. Still figuring out where a simpler model is enough and where the
> extra complexity actually earns its keep.
>
> `Python`

<br/>

### Where this is headed

- Sharpening the retrieval side of RAG — chunking strategy, re-ranking, and
  where local models start to fall behind hosted ones (and where they don't)
- Taking `sign-language-` from a classification demo to something that handles
  continuous signing, not just isolated gestures
- More comfortable putting things in front of real users earlier, instead of
  polishing in private for too long

<br/>

### Background

```
2024 — 2026   Computer Engineering coursework, Mumbai
2025          Started building full RAG pipelines beyond tutorial-level projects
2026          pdf-rag-system: first fully local, no-API-key RAG deployment
2026          Gemini-clone: production-grade chat UI, built to understand
              real chat-app engineering, not just to have a chatbot demo
```

<br/>

### Tools I reach for

| | |
|---|---|
| **Languages** | Python, JavaScript |
| **ML / retrieval** | LangChain, FAISS, Llama 3.2 |
| **Backend** | FastAPI |
| **Frontend** | React |
| **Tooling** | Git, VS Code |

<br/>

<details>
<summary>GitHub activity</summary>
<br/>

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=shruti11931&show_icons=true&theme=transparent&hide_border=true&title_color=5eead4&icon_color=a78bfa&text_color=8892a6" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shruti11931&layout=compact&theme=transparent&hide_border=true&title_color=5eead4&text_color=8892a6" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/shruti11931/shruti11931/output/github-contribution-grid-snake.svg" />
</p>

</details>

<br/>

<sub>shrutijadhav112008@gmail.com</sub>
