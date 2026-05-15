<div align="center">
  <h1> B0T PR0J3T ✨ </h1>
  <p><b> THE BOT PROJECT FULLY MODIFIED BY UNKNOWN 🔺 </b></p>
  <img src="https://files.catbox.moe/yywvtl.jpg" alt="SAGOR BOT" width="400"/>
</div>

---

## 📊 STATS

<p align="center">
<img src="https://img.shields.io/badge/Commands-92-00d9ff?style=for-the-badge" />
<img src="https://img.shields.io/badge/Events-8-ff2d55?style=for-the-badge" />
<img src="https://img.shields.io/badge/Node.js-20.x-339933?style=for-the-badge&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge" />
</p>

---

### Local
```bash
npm install
node index.js
```

---
## Workflow
```
name: Node.js CI

on:
  workflow_dispatch:
  

jobs:
  build:


    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [16.x]
        # See supported Node.js release schedule at https://nodejs.org/en/about/releases/

    steps:
    - uses: actions/checkout@v2
    - name: Use Node.js ${{ matrix.node-version }}
      uses: actions/setup-node@v2
      with:
        node-version: ${{ matrix.node-version }}
        cache: 'npm'
    - run: npm install
    - run: npm start
```

---

## 🔗 SOCIAL

<p align="center">
<a href="https://facebook.com/SAGOR.69x"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" /></a>
<a href="https://github.com/SAGOR-KINGx"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://wa.me/+8801611079915"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" /></a>
<a href="https://t.me/xxSaGorxx"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" /></a>
</p>

---

## LICENSE 🪧

GPL-3.0 — © **LIKHON AHMED 💠**

<div align="center">
  <sub> MODIFIED V2 BY UNKNOWN </sub>
</div>
