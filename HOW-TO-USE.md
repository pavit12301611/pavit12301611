# 🧰 HOW TO USE — GitHub Profile Kit (Hinglish)

Ye repo `pavit12301611/pavit12301611` hai — GitHub ka **special profile repo**.
Iska `README.md` seedha tere GitHub profile page par dikhta hai:
👉 https://github.com/pavit12301611

---

## 📁 Is repo mein kya hai

| File | Kaam |
| :-- | :-- |
| `README.md` | Profile README — banner, badges, about, stack, projects, journey, stats, contact. Yahi profile par render hota hai. |
| `assets/banner.png` | 1500×500 profile banner (dark #0d1116 + green #00df8f circuit theme, PS logo card). README ke top par use hua hai. |
| `assets/avatar.png` | 512×512 PS monogram avatar (gradient cyan→violet→amber). GitHub profile photo ke liye upload kar. |
| `assets/typing.svg` | Animated gradient tagline ("Built by hand, measured by numbers") — self-hosted, koi external service nahi. |
| `assets/divider.svg` | Gradient section divider line — README ke har section ke beech. |
| `setup/snake-workflow.yml` | Ready-made GitHub Action — contribution-snake animation banata hai. Isko `.github/workflows/snake.yml` par copy karna hai (steps neeche). |
| `MASTER_PROMPT.md` | Tera master context prompt — kisi bhi AI agent ko dena hai to yahi paste kar. |
| `HOW-TO-USE.md` | Yehi file — steps aur maintenance guide. |

---

## ✅ Manual steps (ye mujhse nahi hote, tereko karne hain)

1. **Avatar set karo**
   GitHub → top-right photo → *Settings* → *Public profile* → **Edit** picture →
   `assets/avatar.png` upload karo → *Set new profile picture*.

2. **Profile bio bhar do**
   Same Settings page par:
   - **Bio:** `Frontend Developer & UX/UI Designer · Automation Builder · Built by hand, measured by numbers.`
   - **Location:** `Saharanpur, Uttar Pradesh, India`
   - **Website:** `https://psdfolio1611.vercel.app/`
   - **Social links:** Instagram `https://instagram.com/pavitsingh1611`, Card `https://psdbcard.vercel.app/`
   - ✔️ *Display current local time* on kar de.

3. **Repos pin karo** (profile par *Customize your pins*):
   `psdfolio1611` → `webmers` → `theyarntales` → (baaki koi bhi active repo)

4. **Har pinned repo ki description + topics set karo** — neeche wale table se copy-paste:

| Repo | Description | Topics |
| :-- | :-- | :-- |
| `psdfolio1611` | Audit-led personal portfolio OS — React + Vite + Tailwind, design tokens, WebP art direction, accessibility-first. | `portfolio` `react` `vite` `tailwindcss` `framer-motion` `accessibility` `web-performance` `design-system` |
| `webmers` | Marketplace prototype — listings, checkout flow and an in-browser visual editor. | `marketplace` `react` `ecommerce` `frontend` `prototype` |
| `theyarntales` | Handmade crochet e-commerce — teddy bears, accessories, WhatsApp ordering. | `ecommerce` `small-business` `frontend` `netlify` `whatsapp` |
| `pavit12301611` | ✨ My GitHub profile README, banner and brand kit. | `github-profile` `readme` `personal-branding` |

---

## 🔄 Update kaise kare

- **Content badalna hai?** Sirf `README.md` edit karo → commit → push. Profile turant update ho jata hai.
- **Naya project add karna hai?** `## 🚀 Featured projects` table mein ek row add kar do (live link + code link dono).
- **Banner dobara banwana hai?** AI agent ko bolo: `@MASTER_PROMPT.md — TASK 1 execute karo, banner regenerate kar` — brand tokens (#0d1116 bg, #00df8f accent, Space Grotesk vibe) same rakhna.

---

## 🐍 Snake animation on karna (ek baar ka kaam)

README ke bottom wala contribution-snake tabhi dikhega jab workflow ek baar chal jaye:

1. `setup/snake-workflow.yml` ka content copy karke repo mein naya file bana: **`.github/workflows/snake.yml`**
   (GitHub web par: *Add file → Create new file* → path mein `.github/workflows/snake.yml` type kar → paste → commit).
   *(Ye step manually isliye hai kyunki agent ke paas workflow-write permission nahi hai.)*
2. Repo → **Settings** → **Actions** → **General** → *Workflow permissions* → **Read and write permissions** → Save.
3. Repo → **Actions** tab → **"Generate contribution snake"** → **Run workflow** → Run.
4. 1–2 minute baad `output` branch ban jayega aur README mein snake live ho jayega. Uske baad har 12 ghante auto-update hoga.

---

## ⚠️ Dhyan rakhne wali baatein

- Stats cards (`github-readme-stats`, streak) external services hain — kabhi-kabhi slow/down ho sakte hain. Image na dikhe to service ka issue hai, tera README theek hai.
- Repo **public** rehna chahiye, warna profile par README show nahi hoga.
- Koi fake number / fake stat mat add karna — `~82% payload reduction` jaise sirf real, measured numbers.
- Banner ka aspect ratio **3:1** rakho (1500×500) taaki mobile par crop na ho.

---

*© 2026 Pavit Singh · PSDFOLIO · Craft over noise.*
