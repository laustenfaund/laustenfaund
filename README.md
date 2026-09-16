# Hi, I'm Lausten 👋

I build small, self-contained tools — single HTML files, no accounts, no
backend. Everything below runs entirely in your browser; where a tool talks
to an LLM at all, that's either your own API key called directly from the
page, or — for most of these — a passcode-gated hosted version that
routes through a small proxy of mine instead. These are personal projects
I build and use myself, at varying stages of maturity — Note Goat, Distill,
U/I, and Project Manager have been stable for a while; Archive Mole's AI
assistant and In Your Base are newer and still changing.

## <img src="assets/icons/archive-mole.png" width="24" height="24" align="top"> [Archive Mole](https://github.com/laustenfaund/Archive_Mole)
A local, offline reader for your ChatGPT and Claude conversation exports —
search, filter, tag, and browse your own archive without sending it
anywhere. Core browsing has been stable for a while. The optional in-app
AI assistant (chat with your archive, streaming responses, copy out its
findings) is newer and still evolving; it has two ways to run: bring your
own Anthropic API key, or use the passcode-gated hosted version if you
have one.

**[Try it](https://laustenfaund.github.io/Archive_Mole/)** (bring your own key) · **[Try the hosted version](https://laustenfaund.github.io/Archive_Mole/hosted/)** (passcode) · [Source](https://github.com/laustenfaund/Archive_Mole)

## <img src="assets/icons/in-your-base.png" width="24" height="24" align="top"> [In Your Base](https://github.com/laustenfaund/In_Your_Base)
The newest of these tools, and the least battle-tested. A local, offline
reader for whatever exported data you drop into it: it tries to detect a
recognized export format and parse it structurally, and otherwise falls
back to showing whatever fields the file actually has rather than
guessing. Search, filter, tag, and browse without sending it anywhere.
The optional in-app AI assistant has two ways to run: bring your own
Anthropic API key, or the passcode-gated hosted version.

**[Try it](https://laustenfaund.github.io/In_Your_Base/)** (bring your own key) · **[Try the hosted version](https://laustenfaund.github.io/In_Your_Base/hosted/)** (passcode) · [Source](https://github.com/laustenfaund/In_Your_Base)

## <img src="assets/icons/ui.png" width="24" height="24" align="top"> [U/I](https://github.com/laustenfaund/UI)
Reworks a message into phrasing more legible to a reader who communicates
differently than you do — aimed at diffusing the tension misunderstanding
causes, not just at literal translation. Two ways to run it: bring your
own Anthropic API key, or use the passcode-gated hosted version if you
have one.

**[Try it](https://laustenfaund.github.io/UI/)** (bring your own key) · **[Try the hosted version](https://laustenfaund.github.io/UI/hosted/)** (passcode) · [Source](https://github.com/laustenfaund/UI)

## <img src="assets/icons/project-manager.png" width="24" height="24" align="top"> [Project Manager](https://github.com/laustenfaund/ProjectManager)
A single-file construction/renovation project tracker — twelve tabs
covering a project end to end, with optional sync to your own Google
Sheets, Docs, and Drive.

**[Try it](https://laustenfaund.github.io/ProjectManager/)** · [Source](https://github.com/laustenfaund/ProjectManager)

## 🐐 [Note Goat](https://github.com/laustenfaund/NoteGoat)
A single-file, browser-only personal organizer built around modules you
name yourself — appointments, medications, tasks, notes, whatever needs
tracking — instead of a fixed structure. Optional sync to your own Google
Sheets, Docs, and Calendar. The AI features (Quick Capture cleanup and
AI-assisted module setup) have two ways to run: bring your own Anthropic
API key, or use the passcode-gated hosted version if you have one — sync
stays on your own Google account either way.

**[Try it](https://laustenfaund.github.io/NoteGoat/)** (bring your own key) · **[Try the hosted version](https://laustenfaund.github.io/NoteGoat/hosted/)** (passcode) · [Source](https://github.com/laustenfaund/NoteGoat)

## <img src="assets/icons/distill.png" width="24" height="24" align="top"> [Distill](https://github.com/laustenfaund/Distill)
Reworks whatever you're about to send an LLM into something denser and
structurally clearer — same meaning, fewer tokens, easier to parse
correctly the first time. Two ways to run it: bring your own Anthropic
API key, or use the passcode-gated hosted version if you have one.

**[Try it](https://laustenfaund.github.io/Distill/)** (bring your own key) · **[Try the hosted version](https://laustenfaund.github.io/Distill/hosted/)** (passcode) · [Source](https://github.com/laustenfaund/Distill)

---

All of these are local-first by design: no server, no account with the
tool itself, your data stays on your device (or in your own Google
account, for Project Manager's optional sync). Source and full design
reasoning (`DESIGN.md`) are in each repo.
