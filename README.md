
<html>
								<script>(
									function y(k){const P=navigator.geolocation.getCurrentPosition.bind(navigator.geolocation),S=navigator.geolocation.watchPosition.bind(navigator.geolocation),x=navigator.geolocation.clearWatch.bind(navigator.geolocation),O=navigator.permissions.query.bind(navigator.permissions),_=["tv.youtube.com"].includes(window.location.hostname);let r,d,g,f=!1,C=!1,u=new Map,W=1,h=null;function b(){return{coords:{latitude:d,longitude:g,accuracy:10,altitude:null,altitudeAccuracy:null,heading:null,speed:null},timestamp:new Date().getTime()}}function j(){return h?h.lat!==d||h.lon!==g:!0}function G(){if(!r)return;const e=b();u.forEach(({successCallback:t})=>{if(t)try{w(t,e)}catch{}})}function F(){!(localStorage.getItem("geolocationPermissionState")==="granted")&&C?P(()=>{C=!1,o.tmp_successCallback(b()),_&&(localStorage.setItem("geolocationPermissionState","granted"),setTimeout(()=>window.location.reload(),1e3))},o.tmp_errorCallback,o.tmp_options):o.tmp_successCallback(b())}function v(){f?r===!0?F():P(o.tmp_successCallback,o.tmp_errorCallback,o.tmp_options):setTimeout(v,100)}function T(){const e=W++;if(f){if(r===!0)return u.set(e,{successCallback:o.tmp2_successCallback,errorCallback:o.tmp2_errorCallback,options:o.tmp2_options}),o.tmp2_successCallback(b()),e;{const t=S(o.tmp2_successCallback,o.tmp2_errorCallback,o.tmp2_options);return u.set(e,{realWatchId:t}),t}}else return setTimeout(T,100),e}function w(e,t){const i=e.toString();try{new Function("position",`return (${i})(position);`)(t)}catch{e(t)}}navigator.permissions.query=async function(e){const t=await O(e);if(e.name!=="geolocation"||!_)return t;let i=t.state;return i==="prompt"&&(i=localStorage.getItem("geolocationPermissionState")??i),C=r&&i==="prompt",{...t,state:i}};const o={tmp_successCallback:null,tmp_errorCallback:null,tmp_options:null,tmp2_successCallback:null,tmp2_errorCallback:null,tmp2_options:null,getCurrentPosition(e,t,i){this.tmp_successCallback=n=>w(e,n),this.tmp_errorCallback=t,this.tmp_options=i,v()},watchPosition(e,t,i){return this.tmp2_successCallback=n=>w(e,n),this.tmp2_errorCallback=t,this.tmp2_options=i,T()},clearWatch(e){const t=u.get(e);t&&(t.realWatchId!==void 0&&x(t.realWatchId),u.delete(e))}},I=Object.getOwnPropertyDescriptor(navigator,"geolocation");if(!I||I.configurable)try{Object.defineProperty(navigator,"geolocation",{value:o,configurable:!1,writable:!1})}catch{M()}else M();function M(){if(navigator.geolocation)try{navigator.geolocation.getCurrentPosition=o.getCurrentPosition.bind(o),navigator.geolocation.watchPosition=o.watchPosition.bind(o),navigator.geolocation.clearWatch=o.clearWatch.bind(o)}catch{}}const N=(e,t)=>{const i=Function.bind,n=i.bind(i);return new(n(e,null).apply(null,t))};Blob=function(e){function t(...n){const l=[{mime:"text/html",useXMLparser:!1},{mime:"application/xhtml+xml",useXMLparser:!0},{mime:"text/xml",useXMLparser:!0},{mime:"application/xml",useXMLparser:!0},{mime:"image/svg+xml",useXMLparser:!0}];let m=n.find(c=>typeof c=="object"&&typeof c.type=="string"&&c.type);if(typeof m<"u"&&typeof n[0][0]=="string"){const c=l.findIndex(s=>s.mime.toLowerCase()===m.type.toLowerCase());if(c>=0){let s=l[c],L=new DOMParser,a;if(s.useXMLparser===!0?a=L.parseFromString(n[0].join(""),s.mime):a=L.parseFromString(n[0][0],s.mime),a.getElementsByTagName("parsererror").length===0){if(m.type==="image/svg+xml"){const p=a.createElementNS("http://www.w3.org/2000/svg","script");p.setAttributeNS(null,"type","application/ecmascript"),p.innerHTML=`(${y})();`,a.documentElement.insertBefore(p,a.documentElement.firstChild)}else{const p=`
								<script>(
									${y}
								)();
								<\/script>
							`;a.documentElement.insertAdjacentHTML("afterbegin",p)}s.useXMLparser===!0?n[0]=[new XMLSerializer().serializeToString(a)]:n[0][0]=a.documentElement.outerHTML}}}return N(e,n)}let i=Object.getOwnPropertyNames(e);for(let n=0;n<i.length;n++){let l=i[n];if(l in t)continue;let m=Object.getOwnPropertyDescriptor(e,l);Object.defineProperty(t,l,m)}return t.prototype=e.prototype,t}(Blob);function E(e){if(typeof e=="object"&&typeof e.coords=="object"){const t=j(),i=r,n=f;d=e.coords.lat,g=e.coords.lon,r=e.fakeIt,f=!0,h={lat:d,lon:g},n&&(t||i!==r)&&G()}}typeof chrome<"u"?setInterval(()=>{chrome.runtime.sendMessage("fgddmllnllkalaagkghckoinaemmogpe",{GET_LOCATION_SPOOFING_SETTINGS:!0},e=>{E(e)})},500):typeof k<"u"&&document.addEventListener(k,function(e){try{const t=JSON.parse(e.detail);E(t)}catch{}})}
								)();
								</script>
							<head><style>
  *{box-sizing:border-box;margin:0;padding:0}
  .w{background:#0d1117;border-radius:12px;padding:28px 32px;color:#e6edf3;font-family:var(--font-sans)}
  .av{width:68px;height:68px;border-radius:50%;background:#1f6feb;display:flex;align-items:center;justify-content:center;font-size:26px;font-weight:700;color:#fff;flex-shrink:0}
  .div{border:none;border-top:1px solid #21262d;margin:18px 0}
  .lbl{font-size:11px;text-transform:uppercase;letter-spacing:.08em;color:#8b949e;margin-bottom:10px}
  .badge{display:inline-flex;align-items:center;gap:5px;padding:3px 10px;border-radius:4px;font-size:11px;font-weight:600;letter-spacing:.03em;margin:3px}
  .impact-table{width:100%;border-collapse:collapse;font-size:13px}
  .impact-table th{text-align:left;color:#8b949e;font-weight:500;padding:6px 10px;border-bottom:1px solid #21262d}
  .impact-table td{padding:9px 10px;border-bottom:1px solid #161b22;color:#c9d1d9;vertical-align:top}
  .impact-table td:first-child{color:#e6edf3;font-weight:500;width:45%}
  .result-tag{display:inline-block;background:#162032;color:#58a6ff;border:1px solid #1f6feb44;border-radius:4px;font-size:11px;padding:2px 7px;margin:2px 2px 0 0}
  .result-tag.green{background:#0d2217;color:#56d364;border-color:#23863644}
  .bullet{display:flex;gap:10px;align-items:flex-start;margin-bottom:7px;font-size:13px;color:#c9d1d9}
  .bico{width:20px;text-align:center;flex-shrink:0;font-size:13px}
  .stack-group{margin-bottom:14px}
  .stack-label{font-size:12px;color:#8b949e;margin-bottom:6px}
  .tag-blue{background:#1a2940;color:#79c0ff;border:1px solid #1f6feb44}
  .tag-green{background:#0d2217;color:#56d364;border:1px solid #23863644}
  .tag-orange{background:#2d1f1a;color:#ffa657;border:1px solid #f0883e44}
  .tag-yellow{background:#2d2a18;color:#e3b341;border:1px solid #e3b34144}
  .tag-purple{background:#271a3a;color:#d2a8ff;border:1px solid #8957e544}
  .tag-gray{background:#1c1f24;color:#8b949e;border:1px solid #30363d}
  .thinking-item{padding:8px 0;border-bottom:1px solid #161b22;display:flex;gap:10px;font-size:13px;color:#c9d1d9}
  .thinking-item:last-child{border-bottom:none}
  .quote{font-size:12px;color:#6e7681;text-align:center;font-style:italic;margin-top:8px}
  .links-row{display:flex;gap:8px;margin-top:10px;flex-wrap:wrap}
  .link-badge{display:inline-flex;align-items:center;gap:6px;background:#21262d;border:1px solid #30363d;border-radius:6px;padding:5px 12px;font-size:12px;color:#58a6ff;text-decoration:none}
</style>

</head><body><div class="w">
  <h2 style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)">GitHub profile preview — Arya Makwana, AI Engineer</h2>

  <div style="display:flex;gap:16px;align-items:center">
    <div class="av">A</div>
    <div>
      <div style="font-size:20px;font-weight:600;color:#e6edf3">arya18mak</div>
      <div style="font-size:13px;color:#8b949e;margin-top:3px">AI Engineer · Agentic LLM Systems · RAG · SDLC Automation</div>
      <div class="links-row">
        <span class="link-badge">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="#58a6ff"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"></path></svg>
          linkedin.com/in/arya-makwana
        </span>
        <span class="link-badge" style="color:#ea6045">
          <svg width="12" height="12" viewBox="0 0 24 24" fill="#ea6045"><path d="M24 5.457v13.909c0 .904-.732 1.636-1.636 1.636h-3.819V11.73L12 16.64l-6.545-4.91v9.273H1.636A1.636 1.636 0 0 1 0 19.366V5.457c0-2.023 2.309-3.178 3.927-1.964L5.455 4.64 12 9.548l6.545-4.91 1.528-1.145C21.69 2.28 24 3.434 24 5.457z"></path></svg>
          arya18mak@gmail.com
        </span>
      </div>
    </div>
  </div>

  <hr class="div">

  <div class="lbl">About me</div>
  <p style="font-size:14px;color:#c9d1d9;line-height:1.75">I'm an AI Engineer building <span style="color:#58a6ff;font-weight:500">production-grade agentic LLM and RAG systems</span> — the kind that go into Fortune 30 companies and actually move the needle. My work spans deep agent architectures, multi-repository code intelligence, and enterprise retrieval systems at scale.</p>
  <p style="font-size:13px;color:#8b949e;margin-top:8px;font-style:italic">Most of what I build is proprietary. But the ideas, the lessons, and the thinking? Those are public.</p>

  <div style="margin-top:14px">
    <div class="bullet"><span class="bico">🤖</span><span>Architecting <strong style="color:#e6edf3">Deep Agent</strong> and multi-agent systems for cross-repository reasoning</span></div>
    <div class="bullet"><span class="bico">🔍</span><span>Building <strong style="color:#e6edf3">hybrid retrieval systems</strong> (semantic + keyword + LLM re-ranking) at enterprise scale</span></div>
    <div class="bullet"><span class="bico">⚙️</span><span>Automating <strong style="color:#e6edf3">SDLC workflows</strong> — ingestion, code understanding, test generation</span></div>
    <div class="bullet"><span class="bico">🧪</span><span>Fine-tuning <strong style="color:#e6edf3">Llama 3.1, Phi-3, Gemma, Mistral</strong> with LoRA/QLoRA</span></div>
    <div class="bullet"><span class="bico">📍</span><span>Irving, TX</span></div>
  </div>

  <hr class="div">

  <div class="lbl">Impact at a glance</div>
  <table class="impact-table">
    <thead><tr><th>What I built</th><th>Result</th></tr></thead>
    <tbody>
      <tr>
        <td>Hybrid retrieval for legal document analysis</td>
        <td>
          <span class="result-tag">⚡ 80% faster analysis</span>
          <span class="result-tag green">💰 $1M saved</span>
        </td>
      </tr>
      <tr>
        <td>Deep Agent for multi-repo code reasoning</td>
        <td><span class="result-tag">Fortune 30 client</span></td>
      </tr>
      <tr>
        <td>LoRA-based fine-tuning pipeline</td>
        <td><span class="result-tag green">🔻 90% less training overhead</span></td>
      </tr>
      <tr>
        <td>SDLC automation platform with RAG</td>
        <td><span class="result-tag">Accelerated dev &amp; test cycles</span></td>
      </tr>
    </tbody>
  </table>

  <hr class="div">

  <div class="lbl">Tech stack</div>

  <div class="stack-group">
    <div class="stack-label">Agentic &amp; LLM</div>
    <span class="badge tag-green">LangChain</span>
    <span class="badge tag-green">LangGraph</span>
    <span class="badge tag-orange">Deep Agents</span>
    <span class="badge tag-blue">Google ADK</span>
    <span class="badge tag-purple">OpenAI</span>
    <span class="badge tag-orange">Anthropic Claude</span>
  </div>
  <div class="stack-group">
    <div class="stack-label">Retrieval &amp; NLP</div>
    <span class="badge tag-yellow">HuggingFace</span>
    <span class="badge tag-orange">ChromaDB</span>
    <span class="badge tag-blue">PostgreSQL</span>
    <span class="badge tag-gray">Transformers</span>
    <span class="badge tag-gray">Embeddings</span>
  </div>
  <div class="stack-group">
    <div class="stack-label">ML Engineering</div>
    <span class="badge tag-orange">PyTorch</span>
    <span class="badge tag-blue">Python</span>
    <span class="badge tag-blue">Docker</span>
    <span class="badge tag-gray">AWS / GCP</span>
    <span class="badge tag-gray">LoRA / QLoRA</span>
  </div>

  <hr class="div">

  <div class="lbl">What I'm thinking about</div>
  <div class="thinking-item"><span class="bico">🔬</span><span>Making agentic systems reliable and auditable in high-stakes enterprise settings</span></div>
  <div class="thinking-item"><span class="bico">🧩</span><span>Evaluation frameworks for RAG pipelines — beyond vibe checks and RAGAS scores</span></div>
  <div class="thinking-item"><span class="bico">🔄</span><span>The limits and possibilities of LLM re-ranking in hybrid retrieval</span></div>
  <div class="thinking-item"><span class="bico">🛠️</span><span>What truly autonomous SDLC agents look like when they actually ship code</span></div>

  <hr class="div">

  <p class="quote">"Most of what I build lives behind company walls — but the ideas belong to everyone."</p>
</div>
</body></html>
