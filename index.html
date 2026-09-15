<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AL NASRU Agency Tracking System</title> 

<!-- Web App Manifest (PWA Setup) -->
<link rel="manifest" href="data:application/manifest+json;charset=utf-8,%7B%22name%22%3A%22AL%20NASRU%20Tracking%22%2C%22short_name%22%3A%22AL%20NASRU%22%2C%22start_url%22%3A%22.%2Findex.html%22%2C%22display%22%3A%22standalone%22%2C%22background_color%22%3A%22%2312181f%22%2C%22theme_color%22%3A%22%231a2b4c%22%7D"> 

<!-- QR Code Library -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script> 

<!-- SUPABASE JS SDK -->
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script> 

<script>
// SUPABASE CONFIGURATION
const SUPABASE_URL = "https://ftznjzrecydffkjoizza.supabase.co";
const SUPABASE_KEY = "sb_publishable_fs2PHpfFr8rP3abac8Vrmw_XR0OEWQI"; 

const _supabase = supabase.createClient(SUPABASE_URL, SUPABASE_KEY);
</script> 

<style>
* {
box-sizing: border-box;
margin: 0;
padding: 0;
font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
Roboto, Helvetica, Arial, sans-serif;
} 

body {
background-color: #f2f5f9;
color: #333;
min-height: 100vh;
display: flex;
justify-content: center;
align-items: center;
padding: 15px;
} 

.page {
display: none;
width: 100%;
max-width: 420px;
} 

.page.active {
display: block !important;
} 

/* HOME */
.home-card {
background-color: #ffffff;
border-radius: 24px;
box-shadow: 0 10px 25px rgba(0,0,0,0.05);
overflow: hidden;
margin-bottom: 20px;
} 

.home-header {
background-color: #1a2b4c;
color: #ffffff;
padding: 32px 24px;
} 

.agency-tag {
font-size: 14px;
font-weight: 700;
letter-spacing: 2px;
margin-bottom: 12px;
text-transform: uppercase;
color: #e2e8f0;
} 

.home-title {
font-size: 32px;
font-weight: 800;
line-height: 1.15;
margin-bottom: 16px;
} 

.home-subtitle {
font-size: 15px;
color: #cbd5e1;
line-height: 1.4;
} 

.home-body {
padding: 28px 24px 32px;
} 

.form-label {
display: block;
font-size: 15px;
font-weight: 700;
color: #1e293b;
margin-bottom: 10px;
} 

.form-input,
.form-select {
width: 100%;
padding: 14px 16px;
font-size: 15px;
border: 1px solid #cbd5e1;
border-radius: 12px;
outline: none;
color: #334155;
margin-bottom: 20px;
background: #fff;
} 

.btn {
width: 100%;
padding: 14px;
border: none;
border-radius: 12px;
font-size: 16px;
font-weight: 600;
cursor: pointer;
margin-bottom: 12px;
} 

.btn-track {
background-color: #0b8443;
color: white;
} 

.btn-admin {
background-color: #2c3e55;
color: white;
} 

.btn-back {
background-color: #475569;
color: white;
margin-top: 10px;
} 

.footer-text {
color: #64748b;
font-size: 13px;
text-align: center;
} 

/* TRACKING */
.tracking-card {
background-color: #1a222d;
width: 100%;
border-radius: 20px;
border: 1px solid #2a3546;
overflow: hidden;
color: white;
box-shadow: 0 10px 30px rgba(0,0,0,0.5);
} 

.card-header-dark {
background-color: #0d1527;
padding: 24px 20px;
border-bottom: 1px solid #2a3546;
} 

.header-tag-dark {
font-size: 11px;
font-weight: 700;
letter-spacing: 1.5px;
color: #8b9bb4;
text-transform: uppercase;
margin-bottom: 6px;
} 

.main-status-dark {
font-size: 26px;
font-weight: 800;
color: white;
margin-bottom: 12px;
} 

.meta-info-dark {
font-size: 13px;
color: #94a3b8;
margin-bottom: 4px;
} 

.meta-info-dark span {
color: white;
font-weight: 600;
font-family: monospace;
} 

.last-updated-dark {
font-size: 11px;
color: #eab308;
margin-top: 10px;
font-weight: 500;
} 

.card-body-dark {
padding: 20px;
} 

.customer-name-dark {
font-size: 14px;
color: #94a3b8;
margin-bottom: 16px;
} 

.customer-name-dark strong {
color: white;
font-size: 15px;
} 

.status-alert-dark {
background-color: #062c19;
border: 1px solid #0e5a32;
color: #4ade80;
padding: 14px 16px;
border-radius: 12px;
font-size: 13px;
line-height: 1.4;
margin-bottom: 8px;
} 

.amharic-text-dark {
color: #cbd5e1;
font-size: 13px;
margin-bottom: 20px;
} 

.status-list-dark {
display: flex;
flex-direction: column;
gap: 10px;
margin-bottom: 25px;
} 

.status-item-dark {
display: flex;
align-items: center;
gap: 12px;
padding: 12px 16px;
background-color: #121824;
border: 1px solid #232d3d;
border-radius: 12px;
color: #64748b;
font-size: 14px;
font-weight: 600;
} 

.status-item-dark.completed {
color: #94a3b8;
background-color: #16202c;
} 

.status-item-dark.active {
border-color: #16a34a;
background-color: #0b1f17;
color: white;
} 

.status-dot-dark {
width: 14px;
height: 14px;
border-radius: 50%;
background-color: #475569;
} 

.status-item-dark.completed .status-dot-dark {
background-color: #f59e0b;
} 

.status-item-dark.active .status-dot-dark {
background-color: #22c55e;
box-shadow: 0 0 10px #22c55e;
} 

.qr-section-dark {
display: flex;
flex-direction: column;
align-items: center;
padding-top: 15px;
border-top: 1px solid #2a3546;
} 

.qr-box-dark {
background-color: white;
padding: 12px;
border-radius: 12px;
margin-bottom: 15px;
} 

.qr-ref-text-dark {
font-size: 14px;
font-weight: 700;
color: white;
margin-bottom: 15px;
text-align: center;
} 

.btn-whatsapp-dark {
width: 100%;
background-color: #16a34a;
color: white;
border: none;
padding: 14px;
border-radius: 30px;
font-size: 15px;
font-weight: 700;
display: flex;
align-items: center;
justify-content: center;
cursor: pointer;
margin-bottom: 15px;
text-decoration: none;
} 

.info-note-dark {
font-size: 11px;
color: #64748b;
text-align: center;
line-height: 1.4;
margin-bottom: 12px;
} 

.btn-copy-dark {
background-color: #232d3d;
color: #94a3b8;
border: none;
padding: 10px 16px;
border-radius: 8px;
font-size: 12px;
font-weight: 600;
cursor: pointer;
margin-bottom: 15px;
} 

/* ADMIN */
.admin-card {
background: white;
padding: 24px;
border-radius: 20px;
box-shadow: 0 10px 25px rgba(0,0,0,0.05);
} 

.admin-title {
font-size: 20px;
font-weight: 700;
color: #1a2b4c;
margin-bottom: 20px;
text-align: center;
}
</style>
</head> 

<body> 

<!-- HOME -->
<div id="homePage" class="page active">
<div class="home-card">
<div class="home-header">
<div class="agency-tag">AL NASRU</div>
<h1 class="home-title">Agency Tracking<br>System</h1>
<p class="home-subtitle">Foreign Employment & Worker<br>Recruitment Agency</p>
</div> 

<div class="home-body">
<label class="form-label">Reference Number</label>
<input type="text" id="searchInput" class="form-input" placeholder="Example: ALN-2026-0001" value="ALN-2026-0001"> 

<button class="btn btn-track" onclick="trackApplication()">Track Application</button>
<button class="btn btn-admin" onclick="showPage('adminPage')">Admin</button>
</div>
</div>
<div class="footer-text">AL NASRU Agency Tracking System</div>
</div>


<!-- ADMIN -->
<div id="adminPage" class="page">
<div class="admin-card">
<h2 class="admin-title">AL NASRU Admin Panel</h2> 

<label class="form-label">Customer Name (የደንበኛ ስም):</label>
<input type="text" id="adminName" class="form-input" value="AMEDIN KEDIR MAMUD"> 

<label class="form-label">Reference Number (file_code):</label>
<input type="text" id="adminRef" class="form-input" value="ALN-2026-0001"> 

<label class="form-label">MOFA Reference (title):</label>
<input type="text" id="adminMofa" class="form-input" value="ATS-20260903150227536"> 

<label class="form-label">Application Status (ደረጃ):</label>
<select id="adminStatus" class="form-select">
<option value="Received">Received</option>
<option value="At embassy" selected>At embassy</option>
<option value="Embassy done">Embassy done</option>
<option value="Ready to collect">Ready to collect</option>
<option value="Collected">Collected</option>
</select> 

<button class="btn btn-track" onclick="saveData()">Save to Supabase</button>
<button class="btn btn-back" onclick="showPage('homePage')">Back to Home</button>
</div>
</div>


<!-- TRACKING -->
<div id="trackingPage" class="page">
<div class="tracking-card">
<div class="card-header-dark">
<div class="header-tag-dark">MOFA ATTESTATION</div>
<div class="main-status-dark" id="displayStatusTitle">At embassy</div>
<div class="meta-info-dark">Receipt: <span id="displayRef">ALN-2026-0001</span></div>
<div class="meta-info-dark">MOFA REF: <span id="displayMofa">ATS-20260903150227536</span></div>
<div class="last-updated-dark" id="displayLastUpdated">Last updated</div>
</div> 

<div class="card-body-dark">
<div class="customer-name-dark">Customer: <strong id="displayName">AMEDIN KEDIR MAMUD</strong></div> 

<div class="status-alert-dark" id="displayAlertEn">Your file has been submitted to the embassy for attestation.</div>
<div class="amharic-text-dark" id="displayAlertAm">ፋይልዎ ወደ ኤምባሲ ለማረጋገጥ ቀርቧል።</div> 

<div class="status-list-dark">
<div class="status-item-dark" id="step-Received">
<div class="status-dot-dark"></div>
<span>Received</span>
</div>
<div class="status-item-dark" id="step-At-embassy">
<div class="status-dot-dark"></div>
<span>At embassy</span>
</div>
<div class="status-item-dark" id="step-Embassy-done">
<div class="status-dot-dark"></div>
<span>Embassy done</span>
</div>
<div class="status-item-dark" id="step-Ready-to-collect">
<div class="status-dot-dark"></div>
<span>Ready to collect</span>
</div>
<div class="status-item-dark" id="step-Collected">
<div class="status-dot-dark"></div>
<span>Collected</span>
</div>
</div> 

<div class="qr-section-dark">
<div class="qr-box-dark" id="qrcode"></div>
<div class="qr-ref-text-dark" id="displayQrText">AMEDIN KEDIR MAMUD<br>Ref ALN-2026-0001</div> 

<a href="#" id="whatsappBtn" class="btn-whatsapp-dark" target="_blank">📱 Share on WhatsApp</a>
<div class="info-note-dark">Share this tracking link with family or save the QR. Status updates when staff change the file.</div> 

<button class="btn-copy-dark" onclick="copyLink()">Copy tracking link</button>
<button class="btn btn-back" onclick="showPage('homePage')">Back to Search</button>
</div>
</div>
</div>
</div> 

<script>
const statusMessages = {
"Received": {
en: "Your application has been received and is being processed.",
am: "ማመልከቻዎ ደርሶናል፤ በሂደት ላይ ይገኛል።"
},
"At embassy": {
en: "Your file has been submitted to the embassy for attestation.",
am: "ፋይልዎ ወደ ኤምባሲ ለማረጋገጥ ቀርቧል።"
},
"Embassy done": {
en: "Embassy attestation is complete. Document is returning to agency.",
am: "የኤምባሲ ማረጋገጫ ተጠናቋል። ሰነዱ ወደ ኤጀንሲው በመመለስ ላይ ነው።"
},
"Ready to collect": {
en: "Your documents are ready for pickup at our office.",
am: "ሰነዶችዎ ከቢሮአችን ለመውሰድ ዝግጁ ናቸው።"
},
"Collected": {
en: "Documents have been successfully collected.",
am: "ሰነዶች በተሳካ ሁኔታ ተወስደዋል።"
}
}; 

function showPage(pageId) {
document.querySelectorAll(".page").forEach(page => page.classList.remove("active"));
const target = document.getElementById(pageId);
if(target) target.classList.add("active"); 

if (pageId === "trackingPage") {
document.body.style.backgroundColor = "#12181f";
} else {
document.body.style.backgroundColor = "#f2f5f9";
}
} 

// SUPABASE SAVE
async function saveData() {
const name = document.getElementById("adminName").value.trim();
const ref = document.getElementById("adminRef").value.trim();
const mofa = document.getElementById("adminMofa").value.trim();
const status = document.getElementById("adminStatus").value; 

if (!name || !ref || !mofa) {
alert("እባክዎ ሁሉንም መረጃ ይሙሉ።");
return;
} 

try {
const { data, error } = await _supabase
.from('files')
.upsert(
{
file_code: ref,
title: mofa,
status: status
},
{ onConflict: 'file_code' }
); 

if (error) {
alert("ስህተት ተፈጥሯል (Supabase Error)፦ " + error.message);
} else {
alert("መረጃው በ Supabase ላይ በትክክል ተመዝግቧል!");
}
} catch(e) {
alert("መረጃ ማስገባት አልተቻለም፦ " + e.message);
} 

loadTrackingView({ name, ref, mofa, status });
} 

// SUPABASE FETCH
async function trackApplication(refQuery) {
const ref = refQuery || document.getElementById("searchInput").value.trim(); 

if (!ref) {
alert("Reference Number ያስገቡ።");
return;
} 

let searchData = null; 

try {
const { data, error } = await _supabase
.from('files')
.select('*')
.eq('file_code', ref); 

if (data && data.length > 0) {
searchData = data[0];
}
} catch (e) {
console.error("Supabase fetch error:", e);
} 

if (searchData) {
loadTrackingView({
name: document.getElementById("adminName").value || "AMEDIN KEDIR MAMUD",
ref: searchData.file_code,
mofa: searchData.title,
status: searchData.status
});
} else {
alert("ማሳሰቢያ፦ ይህ Reference Number በ Supabase ላይ አልተገኘም። የሙከራ (Demo) ገጽ በመክፈት ላይ ይገኛል...");
loadTrackingView({
name: document.getElementById("adminName").value || "AMEDIN KEDIR MAMUD",
ref: ref,
mofa: "ATS-20260903150227536",
status: "At embassy"
});
}
} 

function loadTrackingView(data) {
document.getElementById("displayStatusTitle").innerText = data.status;
document.getElementById("displayRef").innerText = data.ref;
document.getElementById("displayMofa").innerText = data.mofa;
document.getElementById("displayName").innerText = data.name;
document.getElementById("displayQrText").innerHTML = data.name + "<br>Ref " + data.ref; 

const messages = statusMessages[data.status] || statusMessages["Received"];
document.getElementById("displayAlertEn").innerText = messages.en;
document.getElementById("displayAlertAm").innerText = messages.am; 

const steps = ["Received", "At-embassy", "Embassy-done", "Ready-to-collect", "Collected"];
const currentStepKey = data.status.replace(/\s+/g, "-");
const currentIndex = steps.indexOf(currentStepKey); 

steps.forEach((step, index) => {
const el = document.getElementById("step-" + step);
if (!el) return; 

if (index < currentIndex) {
el.className = "status-item-dark completed";
} else if (index === currentIndex) {
el.className = "status-item-dark active";
} else {
el.className = "status-item-dark";
}
}); 

const now = new Date();
document.getElementById("displayLastUpdated").innerText = "Last updated " + now.toLocaleString(); 

const baseUrl = window.location.href.split("?")[0];
const shareUrl = baseUrl + "?ref=" + encodeURIComponent(data.ref); 

document.getElementById("qrcode").innerHTML = ""; 

if (typeof QRCode !== "undefined") {
new QRCode(document.getElementById("qrcode"), {
text: shareUrl,
width: 130,
height: 130
});
} 

const waMessageText = "🏢 AL NASRU Agency Tracking System\n" +
"👤 Customer: " + data.name + "\n" +
"📋 Status: " + data.status + "\n\n" +
"🔗 የፋይልዎን ሁኔታ ለመከታተል ይህን ሊንክ ይጫኑ፦\n" + shareUrl; 

document.getElementById("whatsappBtn").href = "https://api.whatsapp.com/send?text=" + encodeURIComponent(waMessageText); 

showPage("trackingPage");
} 

function copyLink() {
const ref = document.getElementById("displayRef").innerText;
const baseUrl = window.location.href.split("?")[0];
const shareUrl = baseUrl + "?ref=" + encodeURIComponent(ref); 

if (navigator.clipboard) {
navigator.clipboard.writeText(shareUrl).then(() => {
alert("የመከታተያ ሊንኩ ተኮፒ ተደርጓል!");
});
} else {
prompt("የመከታተያ ሊንኩን ይቅዱ:", shareUrl);
}
} 

window.addEventListener("DOMContentLoaded", () => {
const urlParams = new URLSearchParams(window.location.search);
const refParam = urlParams.get('ref');
if (refParam) {
trackApplication(refParam);
}
});
</script> 

</body>
</html>
