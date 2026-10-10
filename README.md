# AI Storyteller Skill

`master-storyteller` is a reusable Codex skill for writing fiction from an initial idea to a polished story. It helps keep the prose specific, character-driven, and natural.

## What is an AI skill?

An AI skill is a folder of reusable instructions that helps an assistant recognize when a workflow applies and how to carry it out. Codex can load a skill when a request matches its description. A skill guides the assistant; it is not a separate model or application.

## What this skill helps with

- Writing stories, fairy tales, fables, chapters, and scenes.
- Developing characters, plots, and narrative outlines.
- Revising a draft while preserving the writer’s voice and intent.
- Improving specificity, character voice, subtext, pacing, continuity, and polish.

For short or clear requests, **Quick mode** drafts the story directly. For longer work, **Full mode** develops a blueprint and outline first, then drafts in stages with checkpoints.

This skill is designed for fiction and narrative work. It is not intended for essays, summaries, marketing copy, or factual writing.

## Download and install in Codex

1. [Download the repository ZIP](https://github.com/narawitsuraphan/ai-storyteller-skill/archive/refs/heads/main.zip) and extract it, or [download `SKILL.md` directly](https://raw.githubusercontent.com/narawitsuraphan/ai-storyteller-skill/main/skills/master-storyteller/SKILL.md).
2. Copy the `skills/master-storyteller` folder into your Codex skills directory. If you downloaded only `SKILL.md`, create a `master-storyteller` folder and put the file inside it.

Codex expects the file at one of these locations:

- Windows: `%USERPROFILE%\.codex\skills\master-storyteller\SKILL.md`
- macOS and Linux: `~/.codex/skills/master-storyteller/SKILL.md`
- If `CODEX_HOME` is set: `$CODEX_HOME/skills/master-storyteller/SKILL.md`

Restart Codex if the skill does not appear. You can invoke it with `$master-storyteller`; Codex may also select it automatically when a request matches its description.

## License

Copyright 2026 narawitsuraphan.

The skill is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](./LICENSE). You may share and adapt it, including commercially. When you do, credit `narawitsuraphan`, link to [this repository](https://github.com/narawitsuraphan/ai-storyteller-skill) and the license, and indicate if you made changes. See the license for the full terms.

## ภาษาไทย

### Skill คืออะไร

Skill คือโฟลเดอร์ที่มีไฟล์คำแนะนำ `SKILL.md` ซึ่งช่วยให้ Codex รู้ว่าควรใช้แนวทางใดเมื่อได้รับงานที่ตรงกัน และควรทำงานนั้นอย่างไร เป็นคำแนะนำที่นำกลับมาใช้ซ้ำได้ ไม่ใช่โมเดลหรือแอปพลิเคชันแยกต่างหาก

`master-storyteller` ช่วยเขียนนิทาน เรื่องสั้น ฉาก ตัวละคร และโครงเรื่อง รวมถึงปรับแก้ร่างงานเขียน โดยเน้นรายละเอียดเฉพาะตัว น้ำเสียงตัวละคร นัยระหว่างบทสนทนา จังหวะ และความต่อเนื่อง

### ดาวน์โหลดและติดตั้งใน Codex

1. [ดาวน์โหลด ZIP ของ repository](https://github.com/narawitsuraphan/ai-storyteller-skill/archive/refs/heads/main.zip) แล้วแตกไฟล์ หรือ [ดาวน์โหลด `SKILL.md` โดยตรง](https://raw.githubusercontent.com/narawitsuraphan/ai-storyteller-skill/main/skills/master-storyteller/SKILL.md)
2. คัดลอกโฟลเดอร์ `skills/master-storyteller` ไปไว้ในโฟลเดอร์ skills ของ Codex หากดาวน์โหลดเฉพาะ `SKILL.md` ให้สร้างโฟลเดอร์ `master-storyteller` แล้วนำไฟล์ไปไว้ข้างใน

ตำแหน่งไฟล์ที่ Codex ใช้:

- Windows: `%USERPROFILE%\.codex\skills\master-storyteller\SKILL.md`
- macOS และ Linux: `~/.codex/skills/master-storyteller/SKILL.md`
- หากตั้งค่า `CODEX_HOME`: `$CODEX_HOME/skills/master-storyteller/SKILL.md`

หากยังไม่เห็น skill ให้เริ่ม Codex ใหม่ เรียกใช้โดยพิมพ์ `$master-storyteller` หรือ Codex อาจเลือกใช้ให้อัตโนมัติเมื่อคำขอตรงกับคำอธิบายของ skill

อนุญาตให้แชร์และดัดแปลงได้ภายใต้ CC BY 4.0 โดยให้เครดิต `narawitsuraphan` ลิงก์ repository และใบอนุญาต พร้อมระบุว่าแก้ไขอะไร ดูเงื่อนไขทั้งหมดได้ใน [LICENSE](./LICENSE).
