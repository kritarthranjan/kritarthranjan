```text
kritarth@dev:~$ whoami
kritarth-ranjan  # AI/ML developer

kritarth@dev:~$ cat focus.txt
local-first AI
retrieval you can verify
models that train on a free T4

kritarth@dev:~$ tree projects/ -L 1
projects/
├── quorum/        multi-agent research, claim checking, cited answers
├── quicdraw-ai/   U-Net diffusion for sketches on a small GPU
├── aethervexa/    AI watermark and provenance analysis (Windows)
└── rag-eval/      RAG test harness, no infrastructure needed

kritarth@dev:~$ ls more/
jobmatch-ai/  password-manager/

kritarth@dev:~$ cat stack.txt
python  pytorch  fastapi  langgraph  qdrant  docker

kritarth@dev:~$ cat rule.txt
if I can't measure it, I don't claim it
kritarth@dev:~$ cat contact.txt
````

web&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[`kritarth.byethost5.com`](https://kritarth.byethost5.com/)<br>
linkedin&nbsp;&nbsp;[`linkedin.com/in/kritarth-ranjan`](https://linkedin.com/in/kritarth-ranjan)<br>
github&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[`github.com/kritarthranjan`](https://github.com/kritarthranjan)

```text
kritarth@dev:~$ █
```
````

So the structure is: one code block from `whoami` through the `cat contact.txt` line, the three link lines, then a short code block holding only the last prompt.

- **Alignment:** the `&nbsp;` entities keep the columns lined up, because plain spaces collapse outside code blocks.
- **Look:** wrapping each link in backticks makes it render in monospace, so it still matches the terminal text, and it's clickable and blue.
- **Trade-off:** the contact lines now sit between two gray blocks, so there's a visible gap in the terminal. That's the cost of clickable links in text form.

You can make the other project names clickable the same way. Put each `tree` line outside the code block as a link, or keep the dedicated link line under the block. Say which you prefer.

The SVG version has the same limit, since links inside an `<img>` aren't clickable. The workaround is to cut the SVG into slices (top, one slice per link line, bottom) and wrap each link slice in a markdown link. It stays pure black and clickable, but it's more files to maintain. I can generate that set if you want it.

kritarth@dev:~$ █
```

[quorum](https://github.com/kritarthranjan/Quorum) · [quicdraw-ai](https://github.com/kritarthranjan/QuicDraw-AI) · [aethervexa](https://github.com/kritarthranjan/AETHERVEXA) · [website](https://kritarth.byethost5.com/) · [linkedin](https://linkedin.com/in/kritarth-ranjan)
