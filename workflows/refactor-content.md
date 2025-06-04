---
description: refactor content
---

refactor เนื้อหาให้ตรงตามรูปแบบตามล่าง อ่านหมายเหตุด้วย 


----- content ----

## title

คำอธิบาย

``` ts [vite.config.ts] 
import { defineConfig } from 'vite'
import vue from '@vitejs/plugin-vue' // 

export default defineConfig({
  // การตั้งค่า Plugins
  plugins: [
    vue(),   // ใช้ Vue.js
  ],

})
```

----- หมายเหตุ -----

ผมเขียน markdown ใน vitepress นะ

1. ที่ code จะมี [file] ด้วย
2. อะไรที่ควรใช้ ::: code-group ใช้ด้วย
3. อะไรทีควรเขียนในรูปแบบ table ทำด้วย
4. อะไรที่ควรวาด mermaid chat ทำด้วย (วาดในรูปแบบที่เหมาะสมตามเนื้อหานั้นๆ)
5. อะไรที่ควรมี ::: tip ::: warning ::: danger ทำด้วย
6. เนื้อหาใน con