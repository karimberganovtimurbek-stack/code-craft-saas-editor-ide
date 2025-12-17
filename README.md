<h1 align="center">✨ SaaS Code Editor - Next.js 15 ✨</h1>

![Demo App](/public/screenshot-for-readme.png)

[Youtubeda to'liq video joylashtirilgan](https://youtu.be/fGkRQgf6Scw)

# 🧩 CodeCraft – SaaS Code Editor (IDE)  
Ushbu loyiha — foydalanuvchilarga onlayn tarzda kod yozish, saqlash, tahrirlash va o‘z loyihalarini boshqarish imkonini beruvchi zamonaviy SaaS (Software as a Service) platforma hisoblanadi. Loyiha Next.js asosida qurilgan bo‘lib, real vaqtli kod muharriri, foydalanuvchi autentifikatsiyasi, ma’lumotlar bazasi, shuningdek zamonaviy UI komponentlariga ega.

## 🚀 Loyihaning maqsadi
CodeCraft — dasturchilar uchun sodda, qulay va funksional onlayn muharrir yaratish.  
Platforma orqali foydalanuvchilar:
- Kod yozishi  
- Loyihalarni saqlashi  
- Real vaqt rejimida o‘zgarishlarni ko‘rishi  
- Avtorizatsiya orqali o‘z profilinga kirishi  
- Bulutda saqlangan kodlar bilan ishlashi  

## 🛠 Ishlatilgan texnologiyalar

### **Frontend**
- **Next.js 15**
- **React**
- **TypeScript**
- **TailwindCSS**
- **ShadCN/UI**

### **Backend & Servislar**
- **Convex** – real-time database
- **Clerk** – autentifikatsiya (login/register)
- **CodeMirror** – kod muharriri
- **Vercel** – deploy (ixtiyoriy)

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

### Add these env to Convex Dashboard

```js
CLERK_WEBHOOK_SECRET=
LEMON_SQUEEZY_WEBHOOK_SECRET=
```

### Run the app

```shell
npm run dev
```
# code-craft-saas-editor
