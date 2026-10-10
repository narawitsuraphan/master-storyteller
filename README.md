# AI Storyteller Skill

`master-storyteller` is a reusable writing skill for AI assistants. It guides fiction from an initial idea to a polished story while keeping the prose specific, character-driven, and natural.

## What is an AI skill?

An AI skill is a focused set of reusable instructions that helps an assistant recognize when a workflow applies and how to carry it out. It guides an AI assistant’s process; it is not a separate model or application.

## What this skill helps with

- Writing stories, fairy tales, fables, chapters, and scenes.
- Developing characters, plots, and narrative outlines.
- Revising a user’s draft while preserving its voice and intent.
- Improving specificity, character voice, subtext, pacing, continuity, and polish.

For short or clear requests, **Quick mode** drafts the story directly. For longer work, **Full mode** develops a blueprint and outline first, then drafts in stages with checkpoints.

This skill is designed for fiction and narrative work. It is not intended for essays, summaries, marketing copy, or factual writing.

## Download and install in Codex

1. Download [`storyteller_skill.md`](./storyteller_skill.md).
2. Create a folder named `master-storyteller` in your Codex skills directory.
3. Save the downloaded file in that folder as `SKILL.md`.

Default locations:

- Windows: `%USERPROFILE%\.codex\skills\master-storyteller\SKILL.md`
- macOS and Linux: `~/.codex/skills/master-storyteller/SKILL.md`
- If `CODEX_HOME` is set, use `$CODEX_HOME/skills/master-storyteller/SKILL.md` instead.

Restart Codex if the skill does not appear. You can invoke it with `$master-storyteller`; Codex may also select it automatically when a request matches its description.

## License

Copyright 2026 narawitsuraphan.

The skill is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](./LICENSE). You may share and adapt it, including commercially. When you do, credit `narawitsuraphan`, link to [this repository](https://github.com/narawitsuraphan/ai-storyteller-skill) and the license, and indicate if you made changes. See the license for the full terms.

## ภาษาไทย

**Skill** คือชุดคำแนะนำเฉพาะงานที่ช่วยให้ AI รู้ว่าควรเลือกใช้แนวทางเมื่อใดและควรทำงานอย่างไร `master-storyteller` ช่วยเขียนนิทาน เรื่องสั้น ฉาก ตัวละคร โครงเรื่อง และปรับร่างงานเขียน โดยเน้นรายละเอียดที่เฉพาะเจาะจง น้ำเสียงตัวละคร จังหวะ และการขัดเกลางาน

ดาวน์โหลด [`storyteller_skill.md`](./storyteller_skill.md) แล้วบันทึกเป็น `SKILL.md` ในโฟลเดอร์ `master-storyteller` ภายในโฟลเดอร์ skills ของ Codex เช่น `%USERPROFILE%\.codex\skills\master-storyteller\SKILL.md` บน Windows

อนุญาตให้แชร์และดัดแปลงได้ภายใต้ CC BY 4.0 โดยให้เครดิต ลิงก์ใบอนุญาต และระบุการเปลี่ยนแปลง
