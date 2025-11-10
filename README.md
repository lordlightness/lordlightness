<p align="center">
  <!-- Animated SVG typing banner (Matrix green) -->
  <img src="https://readme-typing-svg.demolab.com?font=VT323&size=40&pause=1500&color=00FF00&center=true&vCenter=true&width=900&lines=ShyChimera.lmao;System+crashed+due+to+love%28%29+%26+life.exe" alt="ShyChimera Banner" />
</p>

<p align="center">
  <!-- SVG badge-style message: boys == girls == same bugs -->
  <img src="https://img.shields.io/static/v1?label=Reality&message=boys%20%3D%3D%20girls%20%3D%3D%20same%20bugs&color=00ff00&style=for-the-badge" alt="reality-badge" />
</p>

<hr/>

<h2 align="center">🧠 Love Detector v0.3 — (sarcasm: boys, girls, same bugs)</h2>

<pre><code class="language-js">// LoveDetector.js — sarcasm-enabled, gender-agnostic truth machine

const claims = [
  "I'm loyal",
  "I love you so much",
  "You’re the only one",
  "Trust me, I won’t leave"
];

function analyzeClaim(claim) {
  const triggers = ["forever","trust me","always","promise","bngt","selamanya"];
  const drama = (claim.match(/so+|very+|really+/gi) || []).length;
  const dots = (claim.match(/\.\.\./g) || []).length;

  let score = 0;
  if (triggers.some(t => claim.toLowerCase().includes(t))) score += 35;
  if (drama > 1) score += 30;
  if (dots > 0) score += 20;
  if (claim.length < 12) score += 15;

  return {
    claim,
    fake: score >= 50,
    score
  };
}

console.log("🕵️ Running Love Detector (gender-agnostic)...");
claims.forEach(c => {
  const r = analyzeClaim(c);
  console.log(`> "${r.claim}" -> ${r.fake ? "FAKE 💔" : "maybe real (??)"} [score:${r.score}]`);
});

/*
Output:
> "I'm loyal" -> FAKE 💔 [score:65]
> "I love you so much" -> FAKE 💔 [score:80]
...
*/
</code></pre>

<p><em>Quick note:</em> This is satire. If you still believe every dramatic line, run:</p>

<pre><code class="language-bash">npm uninstall hope && npm i --save self_respect
</code></pre>

<hr/>

<h2>🚀 Install</h2>

<pre><code># macOS / Linux
npm install shychimera.lmao --save

# Windows (backup feelings recommended)
echo "reinstall feelings" &gt; autoexec.bat
</code></pre>

<hr/>

<h2>⚙️ Usage</h2>

<pre><code class="language-js">import Chimera from "shychimera.lmao";

const app = new Chimera({ mode: "matrix", sarcasm: true, empathy: 0 });

app.boot();
app.run(() =&gt; console.log("✅ Logic online. Emotions offline."));</code></pre>

<hr/>

<h2>📟 System Log (sample)</h2>

<pre>
[BOOT] System online
[INFO] Scanning texts... 72% suspicious
[WARN] Detected repeated "forever" statements
[FAIL] LoveDetector -> FAKE (gender-agnostic)
</pre>

<hr/>

<h2>📜 Release Notes</h2>
<ul>
<li><strong>v0.3.0</strong> — Improved detector, added gender-agnostic sarcasm</li>
<li><strong>v0.2.0</strong> — More accurate drama scoring</li>
<li><strong>v0.1.0</strong> — Initial chaotic release</li>
</ul>

<hr/>

<h2>👤 Author</h2>

<pre><code>const author = {
  handle: "ShyChimera.lmao",
  origin: "0xDEADFACE",
  fuels: ["coffee", "dark humor", "late-night code"]
};
</code></pre>

<p align="center">
  <a href="https://github.com/lordlightness"><img src="https://img.shields.io/badge/GitHub-lordlightness-181717?style=for-the-badge&logo=github" alt="github" /></a>
  <a href="https://wa.me/6287861848232"><img src="https://img.shields.io/badge/WhatsApp-Chat%20Now-25D366?style=for-the-badge&logo=whatsapp" alt="whatsapp" /></a>
</p>

<hr/>

<p align="center"><em>Headings use HTML to avoid anchor link icons. Matrix-style green is simulated via SVG elements above.</em></p>

<p align="center">💀 “Love.js returned NULL — reboot your priorities.”</p>
