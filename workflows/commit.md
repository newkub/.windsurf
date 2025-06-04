---
description: commit
---

- ทำการ git commit แบบทีละรายการ (atomic commits) เพื่อให้ commit history มีความชัดเจนและติดตามได้ง่าย
- จัดกลุ่มไฟล์ที่เกี่ยวข้องกันด้วย `git add <directory>` หรือใช้ `git add -p` เพื่อเลือก stage เฉพาะส่วนที่ต้องการ
- ตรวจสอบการเปลี่ยนแปลงด้วย `git status` และ `git diff --staged` ก่อนทำการ commit
- เขียน commit message ตาม conventional commits format:
  - รูปแบบ: `type(scope): description`
  - ตัวอย่าง: `feat(auth): implement OAuth login flow`, `fix(api): handle null response`, `refactor(utils): simplify date formatting`
- ใช้ type ที่เหมาะสม: feat, fix, docs, style, refactor, perf, test, chore