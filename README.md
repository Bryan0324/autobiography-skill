# Autobiography Growth Weaver

An AI skill for writing autobiographies that demonstrate personal growth through concrete, verifiable stories—not by repeating a résumé.

## Language versions

英文版與繁體中文版 Skill 描述相同的工作流程。
中文文件請參考 [`README.md`](README.zh-TW.md)。



The English and Traditional Chinese skill instructions describe the same workflow. If one version is updated, update the other to keep their behavior aligned.

For Traditional Chinese documentation, see [`README.zh-TW.md`](README.zh-TW.md).

## Repository structure

```text
autobiography-growth-weaver/
├── README.md
├── README.zh-TW.md
├── LICENSE
└── skills/
    └── autobiography-growth-weaver/
        ├── SKILL.md
        └── SKILL.zh-TW.md
```

- `SKILL.md`: English skill instructions.
- `SKILL.zh-TW.md`: Traditional Chinese skill instructions.
- `README.md`: English project overview and usage guidance.
- `README.zh-TW.md`: Traditional Chinese project overview and usage guidance.
- `LICENSE`: MIT license.

## What it does

- Detects when a growth claim lacks a concrete story.
- Checks the story chain: scene → initial assumption → friction → action → evidence → reflection → later transfer.
- Searches available and authorized materials before asking the writer for more information.
- Distinguishes verifiable facts from personal motivations and feelings that only the writer can confirm.
- Asks a small number of targeted questions when evidence is missing.
- Helps compare drafts, outline a narrative, diagnose paragraphs, and revise prose without inventing facts.

## Usage

Use the skill instructions in `skills/autobiography-growth-weaver/SKILL.md` with an AI tool that supports custom skills or instructions. Follow the host tool's required installation layout if it has one.

Provide multiple autobiography drafts, a résumé or activity list, and any authorized supporting materials such as project reports, experiment logs, source code, README files, slides, or reflection notes. The AI should inspect available evidence before asking focused questions about unresolved story gaps.

## Example prompts

- “Compare these two autobiography drafts and identify the growth claims that need concrete stories.”
- “Audit this draft for unsupported reflections. Search the provided project notes first, then ask me only the questions needed to fill the gaps.”
- “Revise this autobiography so that each major change in my thinking is grounded in a specific episode.”

## Design principles

1. **Growth, not résumé repetition.**
2. **Evidence before embellishment.**
3. **Ask about gaps, not everything.**
4. **Never fabricate events, motivations, emotions, or results.**
5. **Keep the writer's voice.**

## License

MIT. See [`LICENSE`](LICENSE).