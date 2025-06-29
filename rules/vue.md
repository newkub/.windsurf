---
trigger: always_on
---

- เขียนแบบ vue3 sfc และใช้ lang="ts"
- style ใช้ unocss ทั้งหมด ไม่ใช้ style ใช้จาก uno.config.ts และไม่ต้องมี dark:
- ให้ script อยู่ด้านบน template
- แยก logic ออกจาก template
- ถ้าควรมี interface ให้มี
- ถ้าใช้ icon => ใช้จาก iconify json mdi จาก unocss
- ไม่ใช่ svg
- ดูใน uno.config.ts ก่อนว่ามีอะไรให้ใช้ไหม ถ้ามีให้ใช้จาก uno.config.ts ก่อน
- ไม่ต้องมี dark: