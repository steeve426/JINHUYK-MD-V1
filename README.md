<p align="center">
𝐉𝐈𝐍𝐇𝐘𝐔𝐊-𝐌𝐃
</p>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=50&pause=1000&color=DAA520&center=true&width=910&height=100&lines=THANKS FOR CHOOSING +JINHUYK-MD;MULTI+DEVICE+WHATSAPP+BOT" alt="Typing SVG" /></a>
  </p>

<p align="center">
  <a href="https://github.com/ChanJinhuyk">
    <img alt="Jinhuyk bot logo" height="230" src="https://i.postimg.cc/sx2KY0mS/JINHUYK-MD-V1.jpg">
  </a>
</p>

<p align="center">
  <a href="https://github.com/ChanJinhuyk?tab=followers"><img title="Followers" src="https://img.shields.io/github/followers/KangJinhuyk?label=Followers&style=social"></a>
  <a href="https://github.com/ChanJinhuyk/JINHUYK-MD-V1/stargazers/"><img title="STARS" src="https://img.shields.io/github/stars/ChanJinhuyk/JINHUYK-MD-V1?&style=social"></a>
  <a href="https://github.com/ChanJinhuyk/JINHUYK-MD-V1/network/members"><img title="Forks" src="https://img.shields.io/github/forks/ChanJinhuyk/JINHUYK-MD-V1?style=social"></a>
  <a href="https://github.com/ChanJinhuyk/JINHUYK-MD-V1/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/ChanJinhuyk/JINHUYK-MD-V1?label=Watching&style=social"></a>
</p>

 **JINHUYK-MD-V1 Deployment Methods**

•FORK THIS REPO
 <br>
 <a href='https://github.com/ChanJinhuyk/JINHUYK-MD-V1/fork' target="_blank"><img alt='Fork repo' src='https://img.shields.io/badge/Fork-black?style=for-the-badge&logo=git&logoColor=white'/></a>

 GET SESSION ID HERE
 <br>
 <a href='https://unknown-md-sessions-generator-1.onrender.com' target="_blank"><img alt='Get Session ID' src='https://img.shields.io/badge/Get session id-blue?style=for-the-badge&logo=opencv&logoColor=white'/></a> 


**PANEL.HUGUITISNODES**
*Créer un Compte sur HuguitisNodes*
:
   - vas sur  [HuguitisNodes](https://panel.huguitisnodes.host) et crée un compte si tu n'en as pas déjà un.

 **Lien de Déploiement**
<a href='https://panel.huguitisnodes.host/server/623d1dcf/' target="_blank"><img alt='Deploy on HuguitisNodes' src='https://img.shields.io/badge/-DEPLOY-blue?style=for-the-badge&logo=panel&logoColor=white'/></a>

**DEPLOY ON HEROKU**

•If you don't have an account in Heroku, create one.
   <br>
    <a href='https://signup.heroku.com/' target="_blank"><img alt='Heroku' src='https://img.shields.io/badge/-Create-purple?style=for-the-badge&logo=heroku&logoColor=white'/></a>

•Now deploy.
    <br>
    <a href='https://dashboard.heroku.com/new?template=https://github.com/ChanJinhuyk/JINHUYK-MD-V1' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-DEPLOY-purple?style=for-the-badge&logo=heroku&logoColor=white'/></a>

**DEPLOY ON RENDER**

•If you don't have an account in RENDER, create one and deploy.
    <br>
    <a href='https://dashboard.render.com/select-repo?type=web' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-DEPLOY-black?style=for-the-badge&logo=render&logoColor=white'/></a>

**env for render**

_key_

```
DATABASE_URL
```
_value_

```
postgresql://tkm:Aqi6tqwyv5IwDHncTtVi5XtMGZvfndDJ@dpg-cqahogtds78s739sl81g-a.oregon-postgres.render.com/takudzwa
```
* [⭐️How to deploy on render⭐️](https://youtu.be/FiRpFMZZrMU?si=tyLUSRBqLt4wyfK-)


**DEPLOY ON REPLIT**

[not RECOMMENDED for now,don't even try it]

•Deploy.
    <br>
    <a href='https://github.com/ChanJinhuyk/JINHUYK-MD-V1' target="_blank"><img alt='Replit' src='https://img.shields.io/badge/-Deploy-red?style=for-the-badge&logo=replit&logoColor=white'/></a>

**•Koyeb and Render Deploy now available**

_Termux Setup not recommended_

**DEVELOPERS**

<table>
  <tr>
    <td>•EMMANUEL SASAKI•</td>
  </tr>
  <tr>
    <td><a href="https://github.com/ChanJinhuyk"><img src="https://i.imgur.com/1YWlaIx.jpeg" width="150"</td>
  </tr>
</table>

**Deployer via github lui même `.github/workflows/deploye.yml`

```bash
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  schedule:
    - cron: '0 */6 * * *'  # Relance toutes les 6 heures

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Install FFmpeg
      run: sudo apt-get install -y ffmpeg

    - name: Start application with timeout
      run: |
        timeout 21590s npm start  # Limite l'exécution à 5h 59m 50s

    - name: Save state (Optional)
      run: |
        ./save_state.sh
```

**contributors**

[Sasaki  whatsapp Channel🧑‍💻](https://whatsapp.com/channel/0029Vajrhmz96H4IsEjh4a41)


