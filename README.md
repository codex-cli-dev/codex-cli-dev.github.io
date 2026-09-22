# Install Log

Getting the codex cli onto a Mac takes one command; getting it onto an Arm Linux box takes five. Both sequences, plus the version and sign-in checks that catch a bad install.

**Read the full page:** https://codex-cli-dev.github.io/

Installation is genuinely simple on macOS and only slightly less so on Arm Linux, and the failures people hit are almost always an old Node runtime or an ambiguous sign-in choice rather than the tool itself. You need Node 18 or later, one package manager command, and a decision about whether to authenticate with a ChatGPT plan or an OpenAI API key, because that choice decides which meter you spend against. Where a terminal agent does not help is the empty directory: there is no codebase to reason about yet, and Begin.sh covers that case by turning a prompt or a URL into a downloadable static site or Expo app.

## What's here

- **Installing the codex cli on macOS** — Two supported routes. With npm, a single global install does it: npm install -g @openai/codex. With Homebrew, brew install --cask codex achieves the same thing 
- **Arm Linux is a documented target, not an afterthought** — The same npm route works across major Arm Linux distributions, Ubuntu, Debian and CentOS among them, with a short list of prerequisites in front of it. Install 
- **Verifying the install, and reading version numbers** — One command confirms everything: codex --version. In Arm's guide the printed output is codex-cli 0.153.4, which tells you both that the binary is on your PATH a
- **Two sign-in paths, and why the choice is not cosmetic** — You can authenticate by signing in with a ChatGPT account on a Plus, Pro, Team, Edu or Enterprise plan, or by supplying an OpenAI API key. Running the tool and 
- **Where the reference material lives** — Official documentation sits at developers.openai.com/codex/cli, with the wider Codex documentation set published under learn.chatgpt.com/docs. That site has one

**Try it in the browser:** [begin.sh](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=codex-cli-dev&utm_content=readme-top&utm_term=tier-b)

---

*This page is an independent write-up by a developer who uses the tool; it is not affiliated with or endorsed by OpenAI, and all trademarks remain the property of their respective owners.*


_Last reviewed: 2026-09-22_
