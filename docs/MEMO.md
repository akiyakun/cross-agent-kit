# MEMO


`AGENTS.md` や `CLAUDE.md` は、一般的に 「AIエージェント向け指示ファイル（Agent Instruction Files）」 と呼ばれる。

Claudeにはローカル用の `CLAUDE.local.md` という仕組みががあるが、Codexに似たような仕組みはない。



# ユーザー個人・全プロジェクト共通の指示ファイル

| OS          | Claude Code                       | Codex                            |
| ----------- | --------------------------------- | -------------------------------- |
| macOS       | `~/.claude/CLAUDE.md`             | `~/.codex/AGENTS.md`             |
| Windows     | `%USERPROFILE%\.claude\CLAUDE.md` | `%USERPROFILE%\.codex\AGENTS.md` |
| Linux / WSL | `~/.claude/CLAUDE.md`             | `~/.codex/AGENTS.md`             |

いずれも ユーザー個人・全プロジェクト共通の指示ファイルだよ！

Windowsの場合、例えばユーザー名が `kudo` なら、次のパスになるの。

- Claude Code：`C:\Users\akiya\.claude\CLAUDE.md`
- Codex：`C:\Users\akiya\.codex\AGENTS.md`



