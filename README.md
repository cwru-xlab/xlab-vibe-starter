# xLab Vibe Coding Starter — Emoji Catcher

A tiny working game to start from. Open `index.html` in your browser to play.

## Workshop flow
1. **Clone** this repo and open the folder in VS Code: `git clone https://github.com/cwru-xlab/xlab-vibe-starter.git`
2. Create your own branch. Never work on `main`: `git checkout -b feature/<your-name>`
3. Use Claude Code to change the game. See `PROMPTS.md`.
4. Commit after every change that works.
5. Push your branch and open a pull request. Don't merge it; the leader reviews.
6. Open `index.html` in your browser to play your version.

## Git cheat sheet
| Command | Meaning |
|---|---|
| `git checkout -b name` | Make a new branch and move to it |
| `git status` | What changed? |
| `git add -A` | Stage everything |
| `git commit -m "message"` | Save a checkpoint |
| `git push -u origin name` | Upload the branch |
| `gh pr create --fill` | Open a pull request |
| `gh pr merge --merge` | Merge it |

## Safety
Never commit API keys or the `~/.claude/settings.json` file. Do not screenshot it either.
