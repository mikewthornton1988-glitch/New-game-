COLLECTOR PRO v2.0 — $197 GUMROAD + NEW GITHUB DEPLOY

📁 CURRENT TERMUX FILES (DO NOT DELETE):
~/downloads/collector-game/index.html (v1.0 LIVE)

🎯 COPILOT MISSION: UPGRADE TO v2.0 + NEW GITHUB

**STEP 1: UPGRADE FEATURES (add to existing index.html):**
1. HIGH SCORE LEADERBOARD (localStorage top 10)
2. DAILY STREAK BONUS (day 1-7 multipliers)  
3. 3 POWERUPS (speed/score/invincible - 15sec each)
4. KEEP mobile touch controls + single file

**STEP 2: EXACT CODE BLOCKS TO ADD:**

BEFORE </body> tag:
<div id="leaderboard" style="position:fixed;top:10px;right:10px;background:rgba(0,0,0,0.8);padding:15px;border-radius:10px;max-width:200px">
<h3>Leaderboard</h3><div id="topScores"></div><button onclick="submitScore()" style="background:#4a90e2;color:white;border:none;padding:8px;border-radius:5px;cursor:pointer;width:100%">Submit</button></div>

In gameState object, add:
powerups:[],powerupActive:{speed:0,score:1,invincible:0},dailyStreak:1,lastPlayDate:0

**STEP 3: NEW GITHUB REPO (Termux commands):**
cd ~/downloads/collector-game-v2
git init
git config --global user.name "mikewthornton1988-glitch"
git config --global user.email "mike@gigbeast.com" 
git add .
git commit -m "Collector PRO v2.0"
git branch -M main
git remote add origin https://github.com/mikewthornton1988-glitch/collector-pro.git
git push -u origin main

**STEP 4: ENABLE PAGES:**
Repo Settings → Pages → Source: Deploy from branch "main" / folder "/" → Save

**LIVE URL:** https://mikewthornton1988-glitch.github.io/collector-pro

**GUMROAD PRODUCT:**
"Mobile HTML5 Collector PRO - Leaderboard + Powerups + Streak - $197"
Includes: source code + Termux setup + mobile optimization + GitHub Pages deploy

📱 MOBILE READY: Touch controls + responsive canvas
✅ SINGLE FILE: index.html only (Freedom Method safe)
✅ NO SERVER: Pure static HTML5 + localStorage

DO NOT ADD: Python files, Flask, server.js, requirements.txt
KEEP SINGLE: index.html (self-contained game)

TEST LOCAL: python3 -m http.server 8080 → http://127.0.0.1:8080
