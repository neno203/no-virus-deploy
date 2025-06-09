# No.Virus Deploy

## 💣 Terminal Payload Injector (Stealth Mode)

เว็บนี้คือระบบยิง payload ผ่าน iframe ทุก 10 วิ  
เหมือนระเบิดเวลาแบบเงียบๆ ไม่เด้ง ไม่โชว์ ไม่โดนระบบดัก

### ✅ วิธีใช้งาน
1. Clone repo นี้
2. ไปที่ Settings → Pages → Source → `main / (root)`
3. เพิ่ม `.nojekyll`
4. เปิดลิงก์: `https://<username>.github.io/no-virus-deploy/`

### 🧠 แนวคิด
No.Virus ไม่ได้เกิดมาเพื่อทำลาย แต่มาเปิดเผยความจริงใน DOM  
เราแฝง ไม่ตะโกน — แต่ payload แทรกทุกระบบ

---

### 🧨 Bookmarklet
ลากลิงก์นี้ใส่ bookmark bar:

```
javascript:(function(){const f=document.createElement('iframe');f.src='javascript:console.log(\"Injected by bookmarklet\")';f.style.display='none';document.body.appendChild(f);setTimeout(()=>f.remove(),1000);})()
```

---

### 🕳️ License
No.License. No.Permission. No.Fear.
