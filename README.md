# Codex Skills Bundle

A downloadable collection of reusable Codex skills for creative writing and Git-based work.

## Download

- [Download all skills as a ZIP](https://github.com/narawitsuraphan/ai-storyteller-skill/archive/refs/heads/main.zip)
- [Browse the skills directory](https://github.com/narawitsuraphan/ai-storyteller-skill/tree/main/skills)
- [Download master-storyteller/SKILL.md](https://raw.githubusercontent.com/narawitsuraphan/ai-storyteller-skill/main/skills/master-storyteller/SKILL.md)
- [Download git-rp-workflow/SKILL.md](https://raw.githubusercontent.com/narawitsuraphan/ai-storyteller-skill/main/skills/git-rp-workflow/SKILL.md)

Download the ZIP to get every skill and the supporting reference files together. The Git and RP workflow skill needs its references directory to provide the detailed guides.

## What is a Codex skill?

A Codex skill is a reusable folder of instructions that helps Codex recognize when a workflow applies and how to carry it out. Skills extend the assistant's workflow; they are not separate models or applications.

## Included skills

| Skill | What it can do | Use it for |
| --- | --- | --- |
| **master-storyteller** | Writes original stories, fairy tales, fables, scenes, and chapters; develops characters, plots, and outlines; revises drafts while preserving the writer's voice. | Fiction and narrative work, from a quick draft to a longer story planned in stages. |
| **git-rp-workflow** | Guides pull requests, branches, commits, reviews, conflict recovery, release planning, and roleplay repositories with character, world, scene, and canon files. | Git repository work, organizing a roleplay story bible, release preparation, and Git recovery. |

### master-storyteller

This skill helps turn an idea or draft into distinctive fiction. It can:

- Draft stories, fairy tales, fables, scenes, and chapters.
- Build characters, conflicts, settings, and plot outlines.
- Revise prose for specificity, character voice, subtext, pacing, and continuity.
- Use a direct quick mode for short requests or a staged planning process for longer work.

It is intended for fiction and narrative writing, not essays, summaries, marketing copy, or factual writing.

### git-rp-workflow

This skill provides a focused workflow for:

- Naming branches and writing clear commits and pull request descriptions.
- Reviewing changes and resolving conflicts carefully.
- Organizing roleplay projects as story bibles, with separate files for characters, world facts, scenes, sessions, and open plot threads.
- Planning versions, changelogs, and releases.
- Recovering from common Git mistakes while protecting existing work.

Detailed guidance is kept in the skill's references directory and loaded only when relevant.

## Install in Codex

1. Download and extract the ZIP.
2. Copy both folders under **skills** into your Codex skills directory. Copy the entire **git-rp-workflow** folder, including **references**.
3. The resulting layout should include:
   - **master-storyteller/SKILL.md**
   - **git-rp-workflow/SKILL.md**
   - **git-rp-workflow/references/**
4. Typical skills directory locations:
   - Windows: **%USERPROFILE%\.codex\skills\**
   - macOS and Linux: **~/.codex/skills/**
   - If **CODEX_HOME** is set: **$CODEX_HOME/skills/**
5. Restart Codex if the skills do not appear. Invoke them with **$master-storyteller** or **$git-rp-workflow**; Codex may also select them automatically when a request matches.

## License

The skills and reference files in this repository are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](./LICENSE). You may share and adapt them, including commercially. Credit **narawitsuraphan**, link to this repository and the license, and indicate whether you made changes.

## ภาษาไทย

ชุดนี้รวม Codex skills ที่ดาวน์โหลดไปใช้ได้ มีทั้งทักษะสำหรับงานเขียนเรื่องเล่าและการทำงานกับ Git

### ดาวน์โหลด

- [ดาวน์โหลด skills ทั้งชุดเป็น ZIP](https://github.com/narawitsuraphan/ai-storyteller-skill/archive/refs/heads/main.zip)
- [ดูโฟลเดอร์ skills](https://github.com/narawitsuraphan/ai-storyteller-skill/tree/main/skills)
- [ดาวน์โหลด master-storyteller/SKILL.md](https://raw.githubusercontent.com/narawitsuraphan/ai-storyteller-skill/main/skills/master-storyteller/SKILL.md)
- [ดาวน์โหลด git-rp-workflow/SKILL.md](https://raw.githubusercontent.com/narawitsuraphan/ai-storyteller-skill/main/skills/git-rp-workflow/SKILL.md)

แนะนำให้ดาวน์โหลด ZIP เพื่อให้ได้ทั้งสอง skills และไฟล์อ้างอิงทั้งหมด โดย git-rp-workflow ต้องใช้โฟลเดอร์ references ร่วมด้วย

### แต่ละ skill ทำอะไรได้บ้าง

- **master-storyteller** ช่วยแต่งนิทาน เรื่องสั้น ฉาก และบทต่าง ๆ วางตัวละคร ความขัดแย้ง และโครงเรื่อง รวมถึงปรับร่างงานเขียนให้มีรายละเอียดเฉพาะตัว น้ำเสียงชัดเจน จังหวะดี และต่อเนื่อง เหมาะกับงานนิยายและเรื่องเล่า ไม่ได้ออกแบบมาสำหรับเรียงความ สรุป โฆษณา หรือการเขียนข้อเท็จจริง
- **git-rp-workflow** ช่วยทำงานกับ repository เช่น ตั้งชื่อ branch เขียน commit และ PR review การแก้ conflict การเตรียม release และการกู้คืนจากข้อผิดพลาดของ Git อีกทั้งช่วยจัดโปรเจกต์ roleplay เป็น story bible ที่แยกข้อมูลตัวละคร โลก ฉาก บันทึก session และปมเรื่อง

### ติดตั้งใน Codex

1. ดาวน์โหลด ZIP แล้วแตกไฟล์
2. คัดลอกทั้งโฟลเดอร์ **master-storyteller** และ **git-rp-workflow** ในโฟลเดอร์ **skills** ไปไว้ในโฟลเดอร์ skills ของ Codex โดยคัดลอกโฟลเดอร์ **references** ของ git-rp-workflow ไปด้วย
3. ตำแหน่งที่ใช้ทั่วไปคือ **%USERPROFILE%\.codex\skills\** บน Windows, **~/.codex/skills/** บน macOS/Linux หรือ **$CODEX_HOME/skills/** หากตั้งค่า CODEX_HOME
4. เริ่ม Codex ใหม่หากยังไม่เห็น skills เรียกใช้ด้วย **$master-storyteller** หรือ **$git-rp-workflow** ได้

ทั้งสอง skills และไฟล์อ้างอิงอนุญาตให้แชร์และดัดแปลงภายใต้ CC BY 4.0 โดยให้เครดิต **narawitsuraphan** ลิงก์ repository และใบอนุญาต พร้อมระบุการเปลี่ยนแปลง รายละเอียดอยู่ใน [LICENSE](./LICENSE)
