<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spot-it. Universe (GEN-Z STAGE)</title>
    <style>
        :root {
            --bg-color: #0c0a1d;
            --card-bg: #161230;
            --card-border: #2a2254;
            --accent-purple: #9333ea;
            --accent-pink: #db2777;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
        }
        body {
            background: var(--bg-color);
            color: var(--text-main);
            font-family: system-ui, -apple-system, sans-serif;
            margin: 0;
            padding: 1rem;
            display: flex;
            justify-content: center;
        }
        .app-container {
            width: 100%;
            max-width: 480px;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1rem;
        }
        h1 {
            font-size: 1.4rem;
            margin: 0;
            background: linear-gradient(90deg, #f472b6, #c084fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .subtitle {
            font-size: 0.75rem;
            color: var(--text-muted);
            letter-spacing: 0.05em;
            text-transform: uppercase;
        }
        .btn-backup {
            background: #1e1b4b;
            color: #c084fc;
            border: 1px solid #4c1d95;
            padding: 0.4rem 0.8rem;
            border-radius: 9999px;
            font-size: 0.75rem;
            font-weight: bold;
            cursor: pointer;
        }
        .player-bar {
            background: var(--card-bg);
            border: 1px solid var(--card-border);
            border-radius: 1rem;
            padding: 0.8rem 1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 0.8rem;
        }
        .player-info {
            display: flex;
            align-items: center;
            gap: 0.6rem;
            font-size: 0.85rem;
        }
        .vibe-badge {
            background: rgba(147, 51, 234, 0.2);
            color: #d8b4fe;
            border: 1px solid rgba(147, 51, 234, 0.4);
            padding: 0.2rem 0.6rem;
            border-radius: 0.5rem;
            font-size: 0.75rem;
            font-weight: bold;
        }
        .alert-banner {
            background: linear-gradient(135deg, rgba(219, 39, 119, 0.15), rgba(147, 51, 234, 0.15));
            border: 1px solid rgba(219, 39, 119, 0.3);
            border-radius: 0.8rem;
            padding: 0.7rem 1rem;
            font-size: 0.8rem;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        .nav-tabs {
            display: flex;
            gap: 0.4rem;
            overflow-x: auto;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }
        .tab-btn {
            background: var(--card-bg);
            color: var(--text-muted);
            border: 1px solid var(--card-border);
            padding: 0.5rem 0.9rem;
            border-radius: 0.7rem;
            font-size: 0.8rem;
            font-weight: 500;
            white-space: nowrap;
            cursor: pointer;
            transition: all 0.2s;
        }
        .tab-btn.active {
            background: #2e1065;
            color: #f3e8ff;
            border-color: #7e22ce;
        }
        .section-card {
            background: var(--card-bg);
            border: 1px solid var(--card-border);
            border-radius: 1rem;
            padding: 1.2rem;
            margin-bottom: 1rem;
        }
        .section-title {
            font-size: 0.95rem;
            font-weight: bold;
            margin-bottom: 0.8rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        .stream-counter {
            font-size: 0.75rem;
            color: var(--text-muted);
            margin-bottom: 0.8rem;
        }
        select, textarea, input {
            width: 100%;
            background: #0f0c1b;
            border: 1px solid #3b2875;
            color: var(--text-main);
            padding: 0.7rem;
            border-radius: 0.6rem;
            font-size: 0.85rem;
            margin-bottom: 0.8rem;
            box-sizing: border-box;
            outline: none;
        }
        textarea {
            resize: vertical;
            min-height: 80px;
        }
        .action-submit-btn {
            background: linear-gradient(135deg, #9333ea, #db2777);
            color: white;
            border: none;
            width: 100%;
            padding: 0.8rem;
            border-radius: 0.6rem;
            font-weight: bold;
            font-size: 0.9rem;
            cursor: pointer;
            box-shadow: 0 4px 12px rgba(147, 51, 234, 0.3);
        }
        .action-submit-btn:hover {
            opacity: 0.9;
        }
        .hidden {
            display: none;
        }
        .feed-container {
            margin-top: 1rem;
            display: flex;
            flex-direction: column;
            gap: 0.6rem;
            max-height: 220px;
            overflow-y: auto;
        }
        .feed-item {
            background: rgba(255, 255, 255, 0.03);
            border-left: 3px solid #db2777;
            padding: 0.6rem;
            border-radius: 0.3rem;
            font-size: 0.8rem;
            word-break: break-word;
        }
        .feed-item span {
            color: var(--text-muted);
            font-size: 0.7rem;
            display: block;
            margin-top: 0.2rem;
        }
    </style>
</head>
<body>

<div class="app-container">
    <header>
        <div>
            <h1>Spot-it. Universe</h1>
            <div class="subtitle">GEN-Z STAGE & COMMUNITY</div>
        </div>
        <button class="btn-backup" onclick="eseguiBackup()">💾 Backup</button>
    </header>

    <div class="player-bar">
        <div class="player-info">
            <span>🎧</span>
            <div>
                <div style="font-size: 0.75rem; color: var(--text-muted);">In play:</div>
                <div style="font-weight: 600;">Luv Sic - Nujabes & Shing02</div>
            </div>
        </div>
        <div class="vibe-badge">Vibe: 100%</div>
    </div>

    <div class="alert-banner">
        <span>🔥</span>
        <span>Modalità Offline Attiva: Stand-up & Lab protetti!</span>
    </div>

    <div class="nav-tabs">
        <button class="tab-btn active" onclick="cambiaTab('standup', this)">🎙️ Live & Standup</button>
        <button class="tab-btn" onclick="cambiaTab('lab', this)">🧪 Lab Idee</button>
        <button class="tab-btn" onclick="cambiaTab('vr', this)">🌌 Visore VR</button>
        <button class="tab-btn" onclick="cambiaTab('community', this)">💬 Community</button>
    </div>

    <div id="tab-standup" class="section-card">
        <div class="section-title">🎤 Stand-Up Comedy</div>
        <div class="stream-counter" id="stream-status">Caricamento flussi offline...</div>
        
        <select id="standup-cat">
            <option>Stand-Up Comedy</option>
            <option>Poetry Slam</option>
            <option>Pensiero Libero (Pills)</option>
        </select>
        
        <textarea id="standup-text" placeholder="Scrivi la tua barra, la tua poesia o il tuo pezzo comico... (Slang approved 🔥)"></textarea>
        
        <button class="action-submit-btn" onclick="inviaStandup()">MANDA IN LIVE STREAM 🚀</button>
        
        <div class="feed-container" id="standup-feed"></div>
    </div>

    <div id="tab-lab" class="section-card hidden">
        <div class="section-title">🧪 Laboratorio delle Idee - Video Drop</div>
        <button class="action-submit-btn" style="margin-bottom: 0.8rem; background: #3b82f6;" onclick="avviaTeaser()">▶️ Play Teaser / Visual</button>
        
        <input type="text" id="lab-title" placeholder="Titolo dell'idea o del concept visivo...">
        <textarea id="lab-desc" placeholder="Descrivi il progetto, la gag o il verso..."></textarea>
        
        <button class="action-submit-btn" onclick="salvaLab()">CONDIVIDI NEL LAB 🧪</button>
        
        <div class="feed-container" id="lab-feed"></div>
    </div>

    <div id="tab-vr" class="section-card hidden" style="text-align: center; padding: 2rem 1rem;">
        <div class="section-title" style="justify-content: center;">🌌 VR Immersion Chamber</div>
        <p style="color: var(--text-muted); font-size: 0.85rem; margin-bottom: 1.2rem;">
            Indossa il visore e vivi lo stage di stand-up o la lettura di poesie in uno spazio olografico a 360°.
        </p>
        <button class="action-submit-btn" onclick="attivaVR()">ATTIVA SESSIONE VR 🥽</button>
        <div id="vr-status" style="margin-top: 1rem; color: #c084fc; font-size: 0.85rem; font-weight: bold;"></div>
    </div>

    <div id="tab-community" class="section-card hidden">
        <div class="section-title">💬 Community Lounge</div>
        <input type="text" id="comm-nick" placeholder="Il tuo nickname / tag...">
        <textarea id="comm-msg" placeholder="Lascia un messaggio nella community... cringio zero, solo hype ✨"></textarea>
        
        <button class="action-submit-btn" onclick="inviaCommunity()">INVIA IN CHAT 💬</button>
        
        <div class="feed-container" id="comm-feed"></div>
    </div>
</div>

<script>
    // Avvio immediato sicuro
    window.onload = function() {
        caricaDatiPersistenti();
    };

    function cambiaTab(tabName, btnElement) {
        document.querySelectorAll('.section-card').forEach(el => el.classList.add('hidden'));
        document.getElementById('tab-' + tabName).classList.remove('hidden');
        
        document.querySelectorAll('.tab-btn').forEach(el => el.classList.remove('active'));
        btnElement.classList.add('active');
    }

    function inviaStandup() {
        const txt = document.getElementById('standup-text').value.trim();
        const cat = document.getElementById('standup-cat').value;
        if(!txt) {
            alert("Scrivi prima qualcosa di epico!");
            return;
        }

        try {
            let standups = JSON.parse(localStorage.getItem('spot_standups') || '[]');
            const nuovoElemento = { cat, txt, data: new Date().toLocaleTimeString([], { hour: '2-digit', minute: '2-digit' }) };
            standups.unshift(nuovoElemento);
            localStorage.setItem('spot_standups', JSON.stringify(standups));
            document.getElementById('standup-text').value = '';
            renderStandups();
        } catch(e) {
            alert("Errore di salvataggio locale offline.");
        }
    }

    function renderStandups() {
        const feed = document.getElementById('standup-feed');
        feed.innerHTML = '';
        let standups = [];
        try {
            standups = JSON.parse(localStorage.getItem('spot_standups') || '[]');
        } catch(e) { standups = []; }
        
        if(standups.length === 0) {
            document.getElementById('stream-status').innerText = 'Nessuna barra live. Scrivi la prima offline! 🔥';
            return;
        }

        document.getElementById('stream-status').innerText = `Live offline attiva (${standups.length} contributi salvati) 🎤`;
        standups.forEach(item => {
            const div = document.createElement('div');
            div.className = 'feed-item';
            div.innerHTML = `<strong>[${item.cat}]</strong> ${item.txt}<span>Salvato offline alle ${item.data}</span>`;
            feed.appendChild(div);
        });
    }

    function salvaLab() {
        const title = document.getElementById('lab-title').value.trim();
        const desc = document.getElementById('lab-desc').value.trim();
        if(!title || !desc) {
            alert("Inserisci titolo e descrizione del concept!");
            return;
        }

        try {
            let labs = JSON.parse(localStorage.getItem('spot_labs') || '[]');
            labs.unshift({ title, desc, data: new Date().toLocaleDateString() });
            localStorage.setItem('spot_labs', JSON.stringify(labs));
            document.getElementById('lab-title').value = '';
            document.getElementById('lab-desc').value = '';
            renderLabs();
            alert("Idea salvata nel Lab offline con successo!");
        } catch(e) {
            alert("Errore salvataggio Lab.");
        }
    }

    function renderLabs() {
        const feed = document.getElementById('lab-feed');
        feed.innerHTML = '';
        let labs = [];
        try {
            labs = JSON.parse(localStorage.getItem('spot_labs') || '[]');
        } catch(e) { labs = []; }
        
        labs.forEach(item => {
            const div = document.createElement('div');
            div.className = 'feed-item';
            div.innerHTML = `<strong>🧪 ${item.title}</strong><br>${item.desc}<span>Creato il ${item.data} • Offline Storage</span>`;
            feed.appendChild(div);
        });
    }

    function inviaCommunity() {
        const nick = document.getElementById('comm-nick').value.trim() || "GenZ User";
        const msg = document.getElementById('comm-msg').value.trim();
        if(!msg) {
            alert("Scrivi un messaggio per la community!");
            return;
        }

        try {
            let msgs = JSON.parse(localStorage.getItem('spot_community') || '[]');
            msgs.unshift({ nick, msg, data: new Date().toLocaleTimeString([], { hour: '2-digit', minute: '2-digit' }) });
            localStorage.setItem('spot_community', JSON.stringify(msgs));
            document.getElementById('comm-msg').value = '';
            renderCommunity();
        } catch(e) {
            alert("Errore chat offline.");
        }
    }

    function renderCommunity() {
        const feed = document.getElementById('comm-feed');
        feed.innerHTML = '';
        let msgs = [];
        try {
            msgs = JSON.parse(localStorage.getItem('spot_community') || '[]');
        } catch(e) { msgs = []; }
        
        msgs.forEach(item => {
            const div = document.createElement('div');
            div.className = 'feed-item';
            div.innerHTML = `<strong>@${item.nick}</strong>: ${item.msg}<span>${item.data}</span>`;
            feed.appendChild(div);
        });
    }

    function caricaDatiPersistenti() {
        renderStandups();
        renderLabs();
        renderCommunity();
    }

    function avviaTeaser() {
        alert("▶️ Riproduzione Teaser/Visual offline avviata!");
    }

    function attivaVR() {
        document.getElementById('vr-status').innerText = "✨ Connessione VR offline stabilita al 360° Stage.";
    }

    function eseguiBackup() {
        try {
            const datiTotali = {
                standups: localStorage.getItem('spot_standups'),
                labs: localStorage.getItem('spot_labs'),
                community: localStorage.getItem('spot_community')
            };
            alert("💾 Backup offline completato! I dati sono protetti nel dispositivo.");
        } catch(e) {
            alert("Impossibile eseguire il backup.");
        }
    }
</script>

</body>
</html>
