<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>GitHub profile README generator</title>
<style>
:root{--bg:#f6f7f4;--surface:#fff;--ink:#1d2421;--mute:#5d6a64;--line:#d9ded9;--accent:#1f6f54;--accent-ink:#fff;--chip:#e6efe9;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#141a17;--surface:#1b2420;--ink:#e8eeea;--mute:#9aa8a1;--line:#2c3832;--accent:#4fc196;--accent-ink:#0c1a14;--chip:#24332b}}
:root[data-theme="dark"]{--bg:#141a17;--surface:#1b2420;--ink:#e8eeea;--mute:#9aa8a1;--line:#2c3832;--accent:#4fc196;--accent-ink:#0c1a14;--chip:#24332b}
*,*::before,*::after{box-sizing:inherit}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--ink);font:15px/1.55 "Source Sans 3","Segoe UI",system-ui,sans-serif}
header{padding:28px 20px 8px;max-width:1200px;margin:0 auto}
h1{font:600 28px/1.2 Georgia,"Times New Roman",serif;margin:0 0 6px}
header p{margin:0;color:var(--mute);max-width:60ch}
main{display:grid;grid-template-columns:minmax(0,1fr) minmax(0,1fr);gap:20px;max-width:1200px;margin:0 auto;padding:16px 20px 40px}
@media (max-width:860px){main{grid-template-columns:minmax(0,1fr)}}
section{background:var(--surface);border:1px solid var(--line);border-radius:10px;padding:18px}
h2{font:600 16px/1.3 Georgia,serif;margin:20px 0 8px}
h2:first-child{margin-top:0}
label{display:block;font-weight:600;margin:10px 0 4px}
input[type=text],textarea{width:100%;font:inherit;color:var(--ink);background:var(--bg);border:1px solid var(--line);border-radius:6px;padding:8px 10px}
textarea{resize:vertical;min-height:64px}
input:focus-visible,textarea:focus-visible,button:focus-visible,.chip:focus-visible{outline:2px solid var(--accent);outline-offset:2px}
.row{display:grid;grid-template-columns:1fr 1fr;gap:10px}
@media (max-width:520px){.row{grid-template-columns:1fr}}
.chips{display:flex;flex-wrap:wrap;gap:6px}
.chip{font:inherit;font-size:13px;border:1px solid var(--line);background:var(--bg);color:var(--ink);border-radius:999px;padding:3px 11px;cursor:pointer}
.chip[aria-pressed=true]{background:var(--accent);border-color:var(--accent);color:var(--accent-ink)}
.check{display:flex;gap:8px;align-items:center;font-weight:400;margin:6px 0}
.tabs{display:flex;gap:6px;margin-bottom:10px;flex-wrap:wrap}
.tabs button,.act{font:inherit;border:1px solid var(--line);background:var(--bg);color:var(--ink);border-radius:6px;padding:6px 12px;cursor:pointer}
.tabs button[aria-selected=true]{border-color:var(--accent);box-shadow:inset 0 -2px 0 var(--accent)}
.act.primary{background:var(--accent);border-color:var(--accent);color:var(--accent-ink);font-weight:600}
.spacer{flex:1}
pre{margin:0;white-space:pre-wrap;word-break:break-word;font:13px/1.5 ui-monospace,Menlo,Consolas,monospace;max-height:70vh;overflow:auto}
#preview{max-height:70vh;overflow:auto;padding:4px 2px}
#preview h1{font:600 24px/1.25 system-ui,sans-serif;border-bottom:1px solid var(--line);padding-bottom:6px}
#preview h2{font:600 19px/1.3 system-ui,sans-serif;border-bottom:1px solid var(--line);padding-bottom:5px;margin-top:20px}
#preview ul{padding-left:22px;margin:6px 0}
#preview .badge{display:inline-block;background:var(--chip);border-radius:4px;padding:1px 8px;margin:2px 3px 2px 0;font-size:12px}
#preview .img{display:inline-block;border:1px dashed var(--line);border-radius:4px;padding:6px 10px;margin:2px;color:var(--mute);font-size:12px}
#preview a{color:var(--accent)}
.note{color:var(--mute);font-size:13px;margin:8px 0 0}
#status{color:var(--mute);font-size:13px;min-height:20px;margin-top:8px}
.type{display:block;font:600 16px ui-monospace,Menlo,Consolas,monospace;color:var(--accent);min-height:26px;margin:6px 0}
@keyframes blink{50%{opacity:0}}
h1::after{content:"\258C";color:var(--accent);margin-left:4px;animation:blink 1s steps(1) infinite}
@media (prefers-reduced-motion:reduce){h1::after{animation:none}}
</style>
</head>
<body>
<header>
<h1>GitHub profile README generator</h1>
<p>Fill in the form, check the preview, then copy the Markdown into a repository named after your username.</p>
</header>
<main>
<section aria-label="Profile details">
<h2>Basics</h2>
<div class="row">
<div><label for="user">GitHub username</label><input id="user" type="text" value="Bharathraj282002" autocomplete="off"></div>
<div><label for="name">Display name</label><input id="name" type="text" placeholder="Your name"></div>
</div>
<label for="tag">Tagline</label>
<input id="tag" type="text" value="Postgraduate data science student exploring machine learning">
<h2>About me</h2>
<label for="work">Currently working on</label>
<input id="work" type="text" placeholder="e.g. a fraud detection classifier">
<label for="learn">Currently learning</label>
<input id="learn" type="text" value="Advanced machine learning">
<label for="ask">Ask me about</label>
<input id="ask" type="text" value="Python, pandas, scikit-learn, exploratory data analysis">
<label for="fun">Interests</label>
<input id="fun" type="text" value="Fraud detection, transaction risk analysis, security analytics">
<h2>Skills</h2>
<div class="chips" id="skills" role="group" aria-label="Skills"></div>
<h2>Links</h2>
<div class="row">
<div><label for="li">LinkedIn username</label><input id="li" type="text" placeholder="your-handle"></div>
<div><label for="kg">Kaggle username</label><input id="kg" type="text" placeholder="your-handle"></div>
<div><label for="tw">X / Twitter username</label><input id="tw" type="text" placeholder="your-handle"></div>
<div><label for="em">Email</label><input id="em" type="text" placeholder="you@example.com"></div>
</div>
<label for="site">Portfolio or website URL</label>
<input id="site" type="text" placeholder="https://">
<h2>Extras</h2>
<label class="check"><input type="checkbox" id="stats" checked> GitHub stats card</label>
<label class="check"><input type="checkbox" id="langs" checked> Top languages card</label>
<label class="check"><input type="checkbox" id="views" checked> Profile view counter</label>
<label class="check"><input type="checkbox" id="anim" checked> Animated typing line</label>
<label for="lines">Typing lines (separate with semicolons)</label>
<input id="lines" type="text" value="Data science student;Machine learning enthusiast;Python and pandas lover">
<label class="check"><input type="checkbox" id="banner" checked> Animated wave banner (header and footer)</label>
<label for="quote">Closing line</label>
<input id="quote" type="text" value="Always happy to collaborate on data projects.">
</section>
<section aria-label="Output">
<div class="tabs" role="tablist">
<button role="tab" id="t-prev" aria-selected="true">Preview</button>
<button role="tab" id="t-md" aria-selected="false">Markdown</button>
<span class="spacer"></span>
<button class="act primary" id="copy">Copy Markdown</button>
<button class="act" id="dl">Download README.md</button>
</div>
<div id="preview"></div>
<pre id="md" hidden></pre>
<p id="status" role="status"></p>
<p class="note">Badges and stats cards load from shields.io and github-readme-stats once the README is on GitHub. This preview shows them as labelled placeholders.</p>
</section>
</main>
<script>
(function(){
var SK=[["Python","python","3776AB"],["NumPy","numpy","013243"],["pandas","pandas","150458"],["Matplotlib","plotly","11557c"],["scikit-learn","scikitlearn","F7931E"],["Jupyter","jupyter","F37626"],["SQL","postgresql","336791"],["TensorFlow","tensorflow","FF6F00"],["PyTorch","pytorch","EE4C2C"],["Seaborn","python","4c72b0"],["Git","git","F05032"],["Docker","docker","2496ED"],["Streamlit","streamlit","FF4B4B"],["R","r","276DC3"],["Tableau","tableau","E97627"],["Power BI","powerbi","F2C811"]];
var on={"Python":1,"NumPy":1,"pandas":1,"Matplotlib":1,"scikit-learn":1,"Jupyter":1,"Git":1};
var $=function(i){return document.getElementById(i)};
var ids=["user","name","tag","work","learn","ask","fun","li","kg","tw","em","site","quote","stats","langs","views","anim","lines","banner"];
function v(i){var e=$(i);return e.type==="checkbox"?e.checked:e.value.trim()}
function enc(s){return encodeURIComponent(s).replace(/-/g,"--")}
function badge(label,slug,color,link){
var u="https://img.shields.io/badge/"+enc(label)+"-"+color+"?style=for-the-badge&logo="+slug+"&logoColor=white";
var b="!["+label+"]("+u+")";return link?"["+b+"]("+link+")":b}
function gen(){
var u=v("user")||"username",n=v("name")||u,o=[];
if(v("banner"))o.push("![Banner](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=160&section=header&text="+encodeURIComponent(n)+"&fontSize=48)\n");
o.push("# Hi \uD83D\uDC4B, I\u2019m "+n);
if(v("tag"))o.push("\n### "+v("tag"));
var L=v("lines").split(";").map(function(x){return x.trim()}).filter(Boolean);
if(v("anim")&&L.length)o.push("\n![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=1F6F54&width=500&lines="+L.map(function(x){return encodeURIComponent(x).replace(/%20/g,"+")}).join(";")+")");
var a=[];
if(v("work"))a.push("- \uD83D\uDD2D I\u2019m currently working on **"+v("work")+"**");
if(v("learn"))a.push("- \uD83C\uDF31 I\u2019m currently learning **"+v("learn")+"**");
if(v("ask"))a.push("- \uD83D\uDCAC Ask me about **"+v("ask")+"**");
if(v("fun"))a.push("- \u26A1 I\u2019m interested in **"+v("fun")+"**");
if(a.length)o.push("\n## About me\n\n"+a.join("\n"));
var s=SK.filter(function(k){return on[k[0]]}).map(function(k){return badge(k[0],k[1],k[2])});
if(s.length)o.push("\n## Skills\n\n"+s.join("\n"));
var l=[];
if(v("li"))l.push(badge("LinkedIn","linkedin","0A66C2","https://www.linkedin.com/in/"+v("li")));
if(v("kg"))l.push(badge("Kaggle","kaggle","20BEFF","https://www.kaggle.com/"+v("kg")));
if(v("tw"))l.push(badge("X","x","000000","https://x.com/"+v("tw")));
if(v("em"))l.push(badge("Email","gmail","D14836","mailto:"+v("em")));
if(v("site"))l.push(badge("Portfolio","googlechrome","4285F4",v("site")));
if(l.length)o.push("\n## Connect with me\n\n"+l.join("\n"));
var st=[];
if(v("stats"))st.push("![GitHub stats](https://github-readme-stats.vercel.app/api?username="+u+"&show_icons=true&theme=default)");
if(v("langs"))st.push("![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username="+u+"&layout=compact)");
if(st.length)o.push("\n## GitHub stats\n\n"+st.join("\n"));
if(v("views"))o.push("\n![Profile views](https://komarev.com/ghpvc/?username="+u+"&label=Profile%20views&style=flat)");
if(v("quote"))o.push("\n---\n\n_"+v("quote")+"_");
if(v("banner"))o.push("\n![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer)");
return o.join("\n")+"\n"}
function esc(s){return s.replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/>/g,"&gt;")}
function inl(s){
s=esc(s);
s=s.replace(/\[!\[([^\]]*)\]\([^)]*\)\]\([^)]*\)/g,'<span class="badge">$1</span>');
s=s.replace(/!\[([^\]]*)\]\([^)]*\)/g,function(m,a){if(a==="Typing SVG")return '<span class="type"></span>';return /stats|languages|views|banner|footer/i.test(a)?'<span class="img">'+a+' (image)</span>':'<span class="badge">'+a+'</span>'});
s=s.replace(/\*\*([^*]+)\*\*/g,"<strong>$1</strong>").replace(/(^|\s)_([^_]+)_/g,"$1<em>$2</em>");
return s}
function render(md){
var h="",inl2=false;
md.split("\n").forEach(function(r){
if(/^- /.test(r)){if(!inl2){h+="<ul>";inl2=true}h+="<li>"+inl(r.slice(2))+"</li>";return}
if(inl2){h+="</ul>";inl2=false}
if(/^# /.test(r))h+="<h1>"+inl(r.slice(2))+"</h1>";
else if(/^## /.test(r))h+="<h2>"+inl(r.slice(3))+"</h2>";
else if(/^### /.test(r))h+="<h3>"+inl(r.slice(4))+"</h3>";
else if(r==="---")h+="<hr>";
else if(r.trim())h+="<p>"+inl(r)+"</p>"});
if(inl2)h+="</ul>";return h}
var tt;
function startType(){
clearTimeout(tt);var el=document.querySelector("#preview .type");if(!el)return;
var L=v("lines").split(";").map(function(x){return x.trim()}).filter(Boolean);if(!L.length)return;
if(matchMedia("(prefers-reduced-motion: reduce)").matches){el.textContent=L[0];return}
var i=0,c=0,d=1;
(function s(){var t=L[i%L.length];c+=d;el.textContent=t.slice(0,c)+"\u258C";var w=60;
if(d>0&&c>=t.length){d=-1;w=1100}else if(d<0&&c<=0){d=1;i++;w=300}
tt=setTimeout(s,w)})()}
function update(){var m=gen();$("md").textContent=m;$("preview").innerHTML=render(m);startType()}
function tab(p){
$("t-prev").setAttribute("aria-selected",p);$("t-md").setAttribute("aria-selected",!p);
$("preview").hidden=!p;$("md").hidden=p}
function say(t){$("status").textContent=t;setTimeout(function(){$("status").textContent=""},2500)}
var box=$("skills");
SK.forEach(function(k){
var b=document.createElement("button");b.type="button";b.className="chip";b.textContent=k[0];
b.setAttribute("aria-pressed",!!on[k[0]]);
b.onclick=function(){on[k[0]]=on[k[0]]?0:1;b.setAttribute("aria-pressed",!!on[k[0]]);update()};
box.appendChild(b)});
ids.forEach(function(i){$(i).addEventListener($(i).type==="checkbox"?"change":"input",update)});
$("t-prev").onclick=function(){tab(true)};
$("t-md").onclick=function(){tab(false)};
$("copy").onclick=function(){
var t=gen();
function ok(){say("Copied. Paste it into README.md in your "+(v("user")||"username")+" repository.")}
function fb(){tab(false);var r=document.createRange();r.selectNodeContents($("md"));var s=getSelection();s.removeAllRanges();s.addRange(r);say("Press Ctrl+C or Cmd+C to copy the selected text.")}
try{navigator.clipboard.writeText(t).then(ok,fb)}catch(e){fb()}};
$("dl").onclick=function(){
try{var a=document.createElement("a");a.href=URL.createObjectURL(new Blob([gen()],{type:"text/markdown"}));a.download="README.md";a.click()}
catch(e){}
say("If the download did not start, use Copy Markdown instead.")};
update();
})();
</script>
</body>
</html>

