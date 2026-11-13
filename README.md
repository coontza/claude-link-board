# claude-link-board

Claude 앱(Claude Code 데스크톱)에서 여러 대화방을 함께 돌릴 때, 사용자가 봐야 할 링크만 모아 보여 주는 '링크 방' 스킬입니다.

- 링크 방은 아직 안 본 링크만 보여 주고, 사용자가 그 방에 쓴 말(컨펌 완료·수정사항)을 그대로 총괄 방에 전합니다.
- 총괄 방은 전해 받은 말을 사용자가 직접 한 답으로 보고 바로 일합니다.
- 스킬 본문: [link-board/SKILL.md](link-board/SKILL.md)

## 설치

Claude에게 "https://github.com/coontza/claude-link-board 의 link-board 스킬 설치해줘"라고 하면 됩니다. 터미널에서 직접 할 때:

```bash
git clone https://github.com/coontza/claude-link-board ~/claude-link-board
```

```bash
ln -s ~/claude-link-board/link-board ~/.claude/skills/link-board
```

## 새 판 받기

```bash
git -C ~/claude-link-board pull
```
