# Master Storyteller

A focused Codex skill for writing original fiction and developing narrative ideas into vivid, coherent stories.

## Download

- [Download the skill as a ZIP](https://github.com/narawitsuraphan/ai-storyteller-skill/archive/refs/heads/codex/separate-master-storyteller.zip)
- [Browse the skill folder](https://github.com/narawitsuraphan/ai-storyteller-skill/tree/codex/separate-master-storyteller/skills/master-storyteller)
- [Open SKILL.md](https://raw.githubusercontent.com/narawitsuraphan/ai-storyteller-skill/codex/separate-master-storyteller/skills/master-storyteller/SKILL.md)

This repository contains the Master Storyteller skill by itself.

## What it can do

- Draft original stories, fairy tales, fables, scenes, and chapters.
- Develop characters, settings, conflicts, plots, and outlines.
- Revise a draft for character voice, detail, pacing, and continuity while preserving the writer's intent.
- Use a quick mode for shorter requests or a staged blueprint, outline, draft, and polish process for longer projects.

It is designed for fiction and narrative writing. It is not intended for essays, summaries, marketing copy, or factual writing.

## Install in Codex

Download and extract the ZIP. From the extracted repository folder, copy the complete skill folder into your Codex skills directory.

PowerShell:

    $codexHome = if ($env:CODEX_HOME) { $env:CODEX_HOME } else { Join-Path $HOME ".codex" }
    $skillsPath = Join-Path $codexHome "skills"
    New-Item -ItemType Directory -Force -Path $skillsPath | Out-Null
    Copy-Item -Recurse -Force ".\skills\master-storyteller" $skillsPath

macOS or Linux:

    if [ -n "$CODEX_HOME" ]; then
      CODEX_DIR="$CODEX_HOME"
    else
      CODEX_DIR="$HOME/.codex"
    fi
    mkdir -p "$CODEX_DIR/skills"
    cp -R skills/master-storyteller "$CODEX_DIR/skills/"

Restart Codex if the skill does not appear. You can invoke it with **$master-storyteller**, or Codex may select it automatically when a request matches.

## License

The skill is shared under [Creative Commons Attribution 4.0 International (CC BY 4.0)](./LICENSE). You may share and adapt it, including commercially. Credit **narawitsuraphan**, link to this repository and the license, and indicate whether you made changes.

## ภาษาไทย

Master Storyteller เป็น Codex skill สำหรับแต่งเรื่องเล่าและพัฒนาไอเดียให้เป็นเรื่องที่มีรายละเอียดและดำเนินเรื่องต่อเนื่อง

### ทำอะไรได้บ้าง

- แต่งนิทาน เรื่องสั้น ฉาก และบทต่าง ๆ
- ช่วยพัฒนาตัวละคร ฉากหลัง ความขัดแย้ง พล็อต และโครงเรื่อง
- ปรับร่างงานเขียนให้เสียงตัวละครชัด รายละเอียดเฉพาะตัว จังหวะดี และเรื่องราวต่อเนื่อง โดยรักษาเจตนาของผู้เขียน
- ใช้โหมดด่วนกับคำขอสั้น หรือวาง blueprint และโครงเรื่องก่อนเขียนและเกลาฉบับยาว

เหมาะกับงานนิยายและเรื่องเล่า ไม่ได้ออกแบบมาสำหรับเรียงความ สรุป โฆษณา หรือการเขียนข้อเท็จจริง

### ดาวน์โหลดและติดตั้ง

- [ดาวน์โหลด skill เป็น ZIP](https://github.com/narawitsuraphan/ai-storyteller-skill/archive/refs/heads/codex/separate-master-storyteller.zip)
- [ดูโฟลเดอร์ skill](https://github.com/narawitsuraphan/ai-storyteller-skill/tree/codex/separate-master-storyteller/skills/master-storyteller)

แตก ZIP แล้วคัดลอกโฟลเดอร์ **skills/master-storyteller** ทั้งโฟลเดอร์ไปไว้ที่ **CODEX_HOME/skills/** หากไม่ได้ตั้งค่า CODEX_HOME ตำแหน่งทั่วไปคือโฟลเดอร์ .codex/skills ภายใต้ %USERPROFILE% บน Windows และ **~/.codex/skills/** บน macOS/Linux จากนั้นเริ่ม Codex ใหม่หากยังไม่เห็น skill เรียกใช้ด้วย **$master-storyteller** ได้ หรือ Codex อาจเลือกให้อัตโนมัติเมื่อคำขอตรงกับงานของ skill

### ใบอนุญาต

เผยแพร่ภายใต้ CC BY 4.0 สามารถแชร์และดัดแปลงได้ รวมถึงใช้เชิงพาณิชย์ โดยให้เครดิต **narawitsuraphan** ลิงก์ repository และใบอนุญาต พร้อมระบุการเปลี่ยนแปลง ดูรายละเอียดใน [LICENSE](./LICENSE)
