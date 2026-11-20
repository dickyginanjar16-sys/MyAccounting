<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>ABL Accounting</title>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
<style>
:root{--bg:#f4f6f9;--card:#fff;--ink:#1c2430;--mut:#6b7686;--line:#e3e7ee;--pri:#0f5ea8;--pri2:#e8f1fb;--ok:#18794e;--okbg:#e6f6ee;--warn:#9a5b00;--warnbg:#fff4e0;--bad:#b42318;--badbg:#fdecea}
*{box-sizing:border-box}
body{margin:0;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;background:var(--bg);color:var(--ink);font-size:14px}
button,input,select,textarea{font:inherit}
.hidden{display:none!important}
header.top{display:flex;align-items:center;gap:12px;padding:10px 16px;background:#0b2f55;color:#fff;position:sticky;top:0;z-index:20}
header.top .brand{font-weight:700;letter-spacing:.3px}
header.top .who{margin-left:auto;font-size:12px;opacity:.85;text-align:right}
header.top button{background:transparent;border:1px solid rgba(255,255,255,.4);color:#fff;border-radius:6px;padding:4px 10px;cursor:pointer}
nav.tabs{display:flex;gap:4px;overflow-x:auto;padding:8px 12px;background:#fff;border-bottom:1px solid var(--line);position:sticky;top:46px;z-index:15}
nav.tabs a{white-space:nowrap;padding:7px 12px;border-radius:999px;color:var(--mut);text-decoration:none;font-weight:500}
nav.tabs a.on{background:var(--pri2);color:var(--pri)}
main{padding:16px;max-width:1200px;margin:0 auto}
h2{font-size:18px;margin:4px 0 12px}
h3{font-size:15px;margin:18px 0 8px}
.card{background:var(--card);border:1px solid var(--line);border-radius:10px;padding:14px;margin-bottom:14px}
.grid{display:grid;gap:12px}
.kpis{grid-template-columns:repeat(auto-fill,minmax(170px,1fr))}
.kpi .l{font-size:12px;color:var(--mut)}
.kpi .v{font-size:19px;font-weight:700;margin-top:4px;font-variant-numeric:tabular-nums}
.bar{display:flex;flex-wrap:wrap;gap:8px;align-items:center;margin-bottom:12px}
.bar .sp{flex:1}
.btn{border:1px solid var(--line);background:#fff;border-radius:7px;padding:7px 12px;cursor:pointer;color:var(--ink)}
.btn:hover{border-color:#c5ccd8}
.btn.p{background:var(--pri);border-color:var(--pri);color:#fff}
.btn.d{color:var(--bad);border-color:#f3c4bf}
.btn.s{padding:4px 9px;font-size:12px}
.btn:disabled{opacity:.5;cursor:default}
input,select,textarea{border:1px solid var(--line);border-radius:7px;padding:7px 9px;background:#fff;width:100%}
input[type=checkbox]{width:auto}
label.f{display:block;font-size:12px;color:var(--mut);margin-bottom:10px}
label.f>input,label.f>select,label.f>textarea{margin-top:4px;color:var(--ink);font-size:14px}
.cols2{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:0 12px}
.tw{overflow-x:auto}
table{width:100%;border-collapse:collapse;font-size:13px}
th,td{padding:7px 8px;border-bottom:1px solid var(--line);text-align:left;vertical-align:top}
th{font-size:11px;text-transform:uppercase;letter-spacing:.4px;color:var(--mut);font-weight:600;background:#fafbfc}
td.n,th.n{text-align:right;font-variant-numeric:tabular-nums;white-space:nowrap}
tr.tot td{font-weight:700;border-top:2px solid var(--ink)}
tr.click{cursor:pointer}tr.click:hover td{background:#f7f9fc}
.tag{display:inline-block;padding:2px 8px;border-radius:999px;font-size:11px;font-weight:600}
.t-draft{background:#eef0f3;color:#4a5462}.t-posted{background:var(--pri2);color:var(--pri)}
.t-lunas{background:var(--okbg);color:var(--ok)}.t-batal{background:var(--badbg);color:var(--bad)}
.note{font-size:12px;color:var(--mut);line-height:1.5}
.alert{padding:10px 12px;border-radius:8px;background:var(--warnbg);color:var(--warn);font-size:13px;margin-bottom:12px;line-height:1.5}
.sum{margin-left:auto;max-width:360px}
.sum div{display:flex;justify-content:space-between;padding:4px 0;font-variant-numeric:tabular-nums}
.sum div.b{font-weight:700;border-top:1px solid var(--line);padding-top:7px}
.modal{position:fixed;inset:0;background:rgba(15,25,40,.45);z-index:50;display:flex;align-items:flex-start;justify-content:center;overflow-y:auto;padding:24px 10px}
.modal-box{background:#fff;border-radius:12px;width:100%;max-width:860px;padding:18px;position:relative}
.modal-box .x{position:absolute;right:12px;top:10px;border:0;background:none;font-size:22px;cursor:pointer;color:var(--mut)}
#toast{position:fixed;bottom:18px;left:50%;transform:translateX(-50%);z-index:99}
#toast div{background:#1c2430;color:#fff;padding:10px 16px;border-radius:8px;margin-top:6px;max-width:90vw;font-size:13px}
#toast div.e{background:var(--bad)}
.login{max-width:380px;margin:8vh auto}
.lines td input{padding:5px 6px;font-size:13px}
.seg{display:flex;gap:4px;flex-wrap:wrap;margin-bottom:12px}
.seg button{border:1px solid var(--line);background:#fff;border-radius:7px;padding:6px 12px;cursor:pointer}
.seg button.on{background:var(--pri);color:#fff;border-color:var(--pri)}
@media(max-width:640px){main{padding:10px}.card{padding:11px}.kpi .v{font-size:16px}}
@media print{header,nav,.bar,.noprint{display:none!important}}
</style>
</head>
<body>
<div id="app"></div>
<div id="modal" class="modal hidden"><div class="modal-box"><button class="x" onclick="closeModal()">×</button><div id="modal-body"></div></div></div>
<div id="toast"></div>

<script>
// ================== KONFIGURASI ==================
const SUPABASE_URL = 'https://jobvnjhokrqbpfxaiajb.supabase.co';
const SUPABASE_KEY = 'sb_publishable_gR3JiGtL0CVUWv50ZvM8qQ_lpmv779Z';
const sb = supabase.createClient(SUPABASE_URL, SUPABASE_KEY);

const S = { user:null, role:null, settings:{}, accounts:[], contacts:[] };
const canWrite = () => ['admin','finance'].includes(S.role);
const isAdmin = () => S.role === 'admin';

const PPN_JENIS = {
  BESARAN_TERTENTU: 'PPN 1,1% besaran tertentu (paket / freight forwarding) – kode 05',
  UMUM: 'PPN umum 11% (12% × DPP 11/12) – kode 04',
  DIBEBASKAN: 'PPN dibebaskan (angkutan umum darat/air) – kode 08',
  PENUH: 'PPN 12% penuh – kode 01',
  NON_PPN: 'Tanpa PPN (lawan transaksi non-PKP)'
};
const PPN_SHORT = { BESARAN_TERTENTU:'1,1%', UMUM:'11%', DIBEBASKAN:'Bebas', PENUH:'12%', NON_PPN:'-' };
const PPH_JENIS = {
  PPH23: 'PPh 23 – 2% (4% tanpa NPWP)',
  PPH15_LAUT: 'PPh 15 pelayaran dalam negeri – 1,2% final',
  NONE: 'Tanpa PPh'
};
const PPH_SHORT = { PPH23:'PPh 23', PPH15_LAUT:'PPh 15', NONE:'-' };
const PTKP = ['TK/0','TK/1','TK/2','TK/3','K/0','K/1','K/2','K/3'];

// ================== UTIL ==================
const $ = (s, r=document) => r.querySelector(s);
const $$ = (s, r=document) => [...r.querySelectorAll(s)];
const esc = s => String(s ?? '').replace(/[&<>"']/g, c => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const num = n => Number(n || 0).toLocaleString('id-ID', { maximumFractionDigits: 2 });
const rp = n => 'Rp ' + num(n);
const r2 = x => Math.round((Number(x) + Number.EPSILON) * 100) / 100;
const sum = (arr, k) => arr.reduce((a, r) => a + Number(typeof k === 'function' ? k(r) : r[k] || 0), 0);
const pad = n => String(n).padStart(2, '0');
const today = () => { const d = new Date(); return `${d.getFullYear()}-${pad(d.getMonth()+1)}-${pad(d.getDate())}`; };
const thisMonth = () => today().slice(0, 7);
const fmtDate = s => s ? new Date(s + 'T00:00:00').toLocaleDateString('id-ID', { day:'2-digit', month:'short', year:'numeric' }) : '';
const fmtTs = s => s ? new Date(s).toLocaleString('id-ID', { dateStyle:'short', timeStyle:'short' }) : '';
function monthRange(ym) { const [y, m] = ym.split('-').map(Number); return [`${ym}-01`, `${ym}-${pad(new Date(y, m, 0).getDate())}`]; }
function monthName(ym) { const [y, m] = ym.split('-').map(Number); return new Date(y, m-1, 1).toLocaleDateString('id-ID', { month:'long', year:'numeric' }); }
function nextMonth(ym) { const [y, m] = ym.split('-').map(Number); const d = new Date(y, m, 1); return `${d.getFullYear()}-${pad(d.getMonth()+1)}`; }
const acctName = k => (S.accounts.find(a => a.kode === k) || {}).nama || k;
const tag = st => `<span class="tag t-${esc(st)}">${esc(st)}</span>`;

function toast(msg, err) {
  const d = document.createElement('div'); d.textContent = msg; if (err) d.className = 'e';
  $('#toast').appendChild(d); setTimeout(() => d.remove(), err ? 6000 : 3000);
}
async function q(p) {
  const { data, error } = await p;
  if (error) { toast(error.message, true); throw error; }
  return data;
}
function openModal(html) { $('#modal-body').innerHTML = html; $('#modal').classList.remove('hidden'); window.scrollTo(0, 0); }
function closeModal() { $('#modal').classList.add('hidden'); $('#modal-body').innerHTML = ''; }
function csvDownload(name, rows, cols) {
  const e = v => { const s = String(v ?? ''); return /[",;\n]/.test(s) ? '"' + s.replace(/"/g, '""') + '"' : s; };
  const out = [cols.map(c => e(c[1])).join(',')].concat(rows.map(r => cols.map(c => e(typeof c[0] === 'function' ? c[0](r) : r[c[0]])).join(','))).join('\n');
  const a = document.createElement('a');
  a.href = URL.createObjectURL(new Blob(['﻿' + out], { type:'text/csv;charset=utf-8' }));
  a.download = name + '.csv'; a.click();
}
function acctOptions(filter, sel) {
  return S.accounts.filter(a => a.aktif && (!filter || filter(a)))
    .map(a => `<option value="${a.kode}" ${a.kode === sel ? 'selected' : ''}>${a.kode} · ${esc(a.nama)}</option>`).join('');
}
function optMap(map, sel) { return Object.entries(map).map(([k, v]) => `<option value="${k}" ${k === sel ? 'selected' : ''}>${esc(v)}</option>`).join(''); }

// Perhitungan pajak (sama dengan fungsi di database; angka final dihitung server)
function calcPPN(jenis, dpp) {
  dpp = Number(dpp) || 0; let dnl = dpp, ppn = 0;
  if (jenis === 'UMUM') { dnl = r2(dpp * 11 / 12); ppn = Math.floor(r2(dnl * 0.12)); }
  else if (jenis === 'BESARAN_TERTENTU') ppn = Math.floor(r2(dpp * 0.011));
  else if (jenis === 'PENUH') ppn = Math.floor(r2(dpp * 0.12));
  return { dnl, ppn };
}
const defTarif = (jenis, punyaNpwp) => jenis === 'PPH23' ? (punyaNpwp ? 0.02 : 0.04) : jenis === 'PPH15_LAUT' ? 0.012 : 0;

// ================== AUTH ==================
async function init() {
  const { data: { session } } = await sb.auth.getSession();
  if (!session) return renderLogin();
  S.user = session.user;
  S.role = await q(sb.rpc('my_role'));
  if (!['admin','finance','viewer'].includes(S.role)) return renderPending();
  await loadMaster();
  renderShell();
  window.addEventListener('hashchange', () => go(location.hash.slice(1)));
  go(location.hash.slice(1) || 'dashboard');
}
sb.auth.onAuthStateChange(ev => { if (ev === 'SIGNED_OUT') location.reload(); });

function renderLogin() {
  $('#app').innerHTML = `
  <div class="login card">
    <h2>ABL Accounting</h2>
    <p class="note">Pembukuan & pajak ABL Logistics</p>
    <label class="f">Email<input id="lg-email" type="email" autocomplete="username"></label>
    <label class="f">Password<input id="lg-pass" type="password" autocomplete="current-password"></label>
    <label class="f hidden" id="lg-nama-w">Nama<input id="lg-nama"></label>
    <div class="bar"><button class="btn p" id="lg-go">Masuk</button><span class="sp"></span>
      <a href="#" id="lg-toggle" class="note">Belum punya akun? Daftar</a></div>
  </div>`;
  let daftar = false;
  $('#lg-toggle').onclick = e => { e.preventDefault(); daftar = !daftar;
    $('#lg-nama-w').classList.toggle('hidden', !daftar);
    $('#lg-go').textContent = daftar ? 'Daftar' : 'Masuk';
    e.target.textContent = daftar ? 'Sudah punya akun? Masuk' : 'Belum punya akun? Daftar'; };
  $('#lg-go').onclick = async () => {
    const email = $('#lg-email').value.trim(), password = $('#lg-pass').value;
    if (!email || !password) return toast('Isi email dan password', true);
    if (daftar) {
      const { error } = await sb.auth.signUp({ email, password,
        options: { data: { nama: $('#lg-nama').value.trim() }, emailRedirectTo: location.href.split('#')[0] } });
      if (error) return toast(error.message, true);
      toast('Pendaftaran terkirim. Cek email untuk konfirmasi, lalu tunggu persetujuan admin.');
    } else {
      const { error } = await sb.auth.signInWithPassword({ email, password });
      if (error) return toast(error.message === 'Invalid login credentials' ? 'Email atau password salah' : error.message, true);
      location.reload();
    }
  };
}
function renderPending() {
  $('#app').innerHTML = `<div class="login card"><h2>Menunggu persetujuan</h2>
    <p class="note">Akun <b>${esc(S.user.email)}</b> sudah terdaftar tapi belum diberi akses. Minta admin mengaktifkan akunmu di menu Pengaturan → Pengguna.</p>
    <button class="btn" onclick="sb.auth.signOut()">Keluar</button></div>`;
}
async function loadMaster() {
  const [st, ac, ct] = await Promise.all([
    q(sb.from('settings').select('*').eq('id', 1).single()),
    q(sb.from('accounts').select('*').order('kode')),
    q(sb.from('contacts').select('*').order('nama'))
  ]);
  S.settings = st; S.accounts = ac; S.contacts = ct;
}

// ================== SHELL ==================
const PAGES = {
  dashboard: ['Dashboard', pgDashboard], penjualan: ['Penjualan', p => pgDocs(p, 'sales')],
  pembelian: ['Pembelian', p => pgDocs(p, 'purchase')], kas: ['Kas & Bank', pgKas], gaji: ['Gaji & PPh 21', pgGaji],
  pajak: ['Pajak', pgPajak], laporan: ['Laporan', pgLaporan], jurnal: ['Jurnal', pgJurnal], pengaturan: ['Pengaturan', pgPengaturan]
};
function renderShell() {
  $('#app').innerHTML = `
  <header class="top"><span class="brand">${esc(S.settings.nama_perusahaan)} · Accounting</span>
    <span class="who">${esc(S.user.email)}<br>${esc(S.role)}</span>
    <button onclick="sb.auth.signOut()">Keluar</button></header>
  <nav class="tabs">${Object.entries(PAGES).map(([k, v]) => `<a href="#${k}" data-p="${k}">${v[0]}</a>`).join('')}</nav>
  <main id="main"></main>`;
}
async function go(p) {
  if (!PAGES[p]) p = 'dashboard';
  $$('nav.tabs a').forEach(a => a.classList.toggle('on', a.dataset.p === p));
  const el = $('#main'); el.innerHTML = '<p class="note">Memuat…</p>';
  try { await PAGES[p][1](el); } catch (e) { console.error(e); el.innerHTML = `<div class="alert">Gagal memuat: ${esc(e.message)}</div>`; }
}
const monthPicker = (id, v) => `<input type="month" id="${id}" value="${v || thisMonth()}" style="width:auto">`;

// ================== DASHBOARD ==================
async function pgDashboard(el) {
  const ym = thisMonth(), [d1, d2] = monthRange(ym);
  const [tb, piu, ut, pk, pm, pd, p21] = await Promise.all([
    q(sb.rpc('neraca_saldo', { p_dari: d1, p_sampai: d2 })),
    q(sb.from('v_piutang').select('sisa,jatuh_tempo').gt('sisa', 0)),
    q(sb.from('v_utang').select('sisa').gt('sisa', 0)),
    q(sb.from('v_ppn_keluaran').select('ppn').gte('tanggal', d1).lte('tanggal', d2)),
    q(sb.from('v_ppn_masukan').select('ppn,ppn_dikreditkan').gte('tanggal', d1).lte('tanggal', d2)),
    q(sb.from('v_pph_dipotong_abl').select('pph,pph_jenis').gte('tanggal', d1).lte('tanggal', d2)),
    q(sb.from('v_pph21').select('pph21').eq('periode', d1))
  ]);
  const pend = sum(tb.filter(r => r.tipe === 'PENDAPATAN'), r => r.kredit - r.debit);
  const beb = sum(tb.filter(r => r.tipe === 'BEBAN'), r => r.debit - r.kredit);
  const kasK = S.accounts.filter(a => a.is_kas).map(a => a.kode);
  const kas = sum(tb.filter(r => kasK.includes(r.kode)), 'saldo_akhir');
  const telat = piu.filter(r => r.jatuh_tempo && r.jatuh_tempo < today());
  const ppnK = sum(pk, 'ppn'), ppnM = sum(pm.filter(r => r.ppn_dikreditkan), 'ppn');
  const nm = nextMonth(ym);
  el.innerHTML = `
  <h2>Ringkasan ${monthName(ym)}</h2>
  <div class="grid kpis">
    ${kpi('Pendapatan bulan ini', rp(pend))}${kpi('Beban bulan ini', rp(beb))}
    ${kpi('Laba bulan ini', rp(pend - beb))}${kpi('Saldo kas & bank', rp(kas))}
    ${kpi(`Piutang belum dibayar (${piu.length})`, rp(sum(piu, 'sisa')))}${kpi(`Utang ke vendor`, rp(sum(ut, 'sisa')))}
  </div>
  ${telat.length ? `<div class="alert">${telat.length} invoice sudah lewat jatuh tempo (${rp(sum(telat, 'sisa'))}).</div>` : ''}
  <h3>Pajak masa ${monthName(ym)} (sementara)</h3>
  <div class="grid kpis">
    ${kpi('PPN keluaran', rp(ppnK))}${kpi('PPN masukan dikreditkan', rp(ppnM))}
    ${kpi(ppnK - ppnM >= 0 ? 'PPN kurang bayar' : 'PPN lebih bayar', rp(Math.abs(ppnK - ppnM)))}
    ${kpi('PPh 23 dipotong ABL', rp(sum(pd.filter(r => r.pph_jenis === 'PPH23'), 'pph')))}
    ${kpi('PPh 15 dipotong ABL', rp(sum(pd.filter(r => r.pph_jenis === 'PPH15_LAUT'), 'pph')))}
    ${kpi('PPh 21 karyawan', rp(sum(p21, 'pph21')))}
  </div>
  <div class="card note" style="margin-top:12px">
    <b>Tenggat masa ${monthName(ym)}:</b> setor PPh 21/23/15 paling lambat 15 ${monthName(nm)}, lapor SPT Masa PPh paling lambat 20 ${monthName(nm)};
    setor & lapor SPT Masa PPN paling lambat akhir ${monthName(nm)}. Semua lewat Coretax. Cek ulang kalau ada perubahan aturan.
  </div>`;
}
const kpi = (l, v) => `<div class="card kpi"><div class="l">${l}</div><div class="v">${v}</div></div>`;

// ================== PENJUALAN / PEMBELIAN ==================
const DOC = {
  sales: { table:'sales_invoices', lines:'sales_invoice_lines', fk:'invoice_id', party:'customer_id', partyLabel:'Customer',
    partyTipe:['customer','keduanya'], acct:'akun_pendapatan', acctTipe:'PENDAPATAN', post:'post_sales_invoice', batal:'penjualan',
    title:'Invoice Penjualan', newLabel:'＋ Invoice Baru', defPPN:'BESARAN_TERTENTU', defAcct:'4-1000', view:'v_piutang' },
  purchase: { table:'purchase_bills', lines:'purchase_bill_lines', fk:'bill_id', party:'vendor_id', partyLabel:'Vendor',
    partyTipe:['vendor','keduanya'], acct:'akun_beban', acctTipe:'BEBAN', post:'post_purchase_bill', batal:'pembelian',
    title:'Tagihan Pembelian', newLabel:'＋ Tagihan Baru', defPPN:'NON_PPN', defAcct:'5-1000', view:'v_utang' }
};
let docState = {};
async function pgDocs(el, kind) {
  const c = DOC[kind];
  el.innerHTML = `<h2>${kind === 'sales' ? 'Penjualan (Invoice)' : 'Pembelian (Tagihan Vendor)'}</h2>
  <div class="bar">${monthPicker('d-m')}
    <select id="d-st" style="width:auto"><option value="">Semua status</option><option>draft</option><option>posted</option><option>lunas</option><option>batal</option></select>
    <span class="sp"></span>${canWrite() ? `<button class="btn p" id="d-new">${c.newLabel}</button>` : ''}</div>
  <div class="card tw" id="d-list"></div>`;
  const load = async () => {
    const [d1, d2] = monthRange($('#d-m').value);
    let qq = sb.from(c.table).select('*, contacts(nama)').gte('tanggal', d1).lte('tanggal', d2).order('tanggal', { ascending:false }).order('created_at', { ascending:false });
    if ($('#d-st').value) qq = qq.eq('status', $('#d-st').value);
    const rows = await q(qq);
    $('#d-list').innerHTML = rows.length ? `<table><thead><tr><th>No</th><th>Tanggal</th><th>${c.partyLabel}</th><th>PPN</th><th>PPh</th>
      <th class="n">DPP</th><th class="n">PPN</th><th class="n">PPh</th><th class="n">Total</th><th>Status</th></tr></thead><tbody>
      ${rows.map(r => `<tr class="click" data-id="${r.id}"><td>${esc(r.no || '(draft)')}</td><td>${fmtDate(r.tanggal)}</td><td>${esc(r.contacts?.nama)}</td>
        <td>${PPN_SHORT[r.ppn_jenis]}</td><td>${PPH_SHORT[r.pph_jenis]}</td><td class="n">${num(r.dpp)}</td><td class="n">${num(r.ppn)}</td>
        <td class="n">${num(r.pph)}</td><td class="n">${num(r.total)}</td><td>${tag(r.status)}</td></tr>`).join('')}
      <tr class="tot"><td colspan="5">Total (tanpa batal)</td>${['dpp','ppn','pph','total'].map(k => `<td class="n">${num(sum(rows.filter(r => r.status !== 'batal'), k))}</td>`).join('')}<td></td></tr>
      </tbody></table>` : '<p class="note">Belum ada data di bulan ini.</p>';
    $$('#d-list tr.click').forEach(tr => tr.onclick = () => openDoc(kind, tr.dataset.id, load));
  };
  $('#d-m').onchange = load; $('#d-st').onchange = load;
  if ($('#d-new')) $('#d-new').onclick = () => openDoc(kind, null, load);
  await load();
}

async function openDoc(kind, id, reload) {
  const c = DOC[kind];
  let h = { tanggal: today(), ppn_jenis: c.defPPN, pph_jenis: 'PPH23', [c.acct]: c.defAcct, status: 'draft', ppn_dikreditkan: true }, lines = [];
  if (id) {
    h = await q(sb.from(c.table).select('*, contacts(nama,npwp,alamat)').eq('id', id).single());
    lines = await q(sb.from(c.lines).select('*').eq(c.fk, id).order('id'));
  }
  docState = { kind, id, h, lines, reload };
  if (h.status === 'draft' && canWrite()) renderDocForm(); else renderDocView();
}

function renderDocForm() {
  const { kind, h, lines } = docState, c = DOC[kind], sales = kind === 'sales';
  const parties = S.contacts.filter(x => c.partyTipe.includes(x.tipe));
  const tarifPct = h.pph_tarif != null ? r2(h.pph_tarif * 100) : '';
  openModal(`<h2>${docState.id ? 'Ubah' : 'Buat'} ${c.title} <span class="note">(draft)</span></h2>
  <div class="cols2">
    <label class="f">${c.partyLabel}<select id="f-party"><option value="">— pilih —</option>${parties.map(p => `<option value="${p.id}" ${p.id === h[c.party] ? 'selected' : ''}>${esc(p.nama)}${p.npwp ? '' : ' (tanpa NPWP)'}</option>`).join('')}</select>
      <a href="#" class="note" id="f-newparty">＋ ${c.partyLabel.toLowerCase()} baru</a></label>
    <label class="f">Tanggal<input type="date" id="f-tgl" value="${h.tanggal || ''}"></label>
    <label class="f">Jatuh tempo<input type="date" id="f-jt" value="${h.jatuh_tempo || ''}"></label>
    ${sales ? '' : `<label class="f">No. tagihan vendor<input id="f-novendor" value="${esc(h.no_tagihan_vendor)}"></label>`}
    <label class="f">${sales ? 'Akun pendapatan' : 'Akun beban'}<select id="f-acct">${acctOptions(a => a.tipe === c.acctTipe, h[c.acct])}</select></label>
    <label class="f">Jenis PPN<select id="f-ppn">${optMap(PPN_JENIS, h.ppn_jenis)}</select></label>
    ${sales ? '' : `<label class="f" style="padding-top:22px"><input type="checkbox" id="f-kredit" ${h.ppn_dikreditkan ? 'checked' : ''}> PPN masukan dapat dikreditkan</label>`}
    <label class="f">Jenis PPh<select id="f-pph">${optMap(PPH_JENIS, h.pph_jenis)}</select></label>
    <label class="f">Tarif PPh (%)<input type="number" step="0.01" id="f-tarif" value="${tarifPct}"></label>
    <label class="f">No. faktur pajak${sales ? ' (dari Coretax)' : ' vendor'}<input id="f-faktur" value="${esc(h.no_faktur)}"></label>
  </div>
  <label class="f">Keterangan<input id="f-ket" value="${esc(h.keterangan)}"></label>
  <h3>Item</h3>
  <div class="tw"><table class="lines"><thead><tr><th>Deskripsi</th><th>No LT / Ref</th><th class="n">Qty</th><th>Satuan</th><th class="n">Harga</th><th class="n">Jumlah</th><th></th></tr></thead>
  <tbody id="f-lines"></tbody></table></div>
  <button class="btn s" id="f-addline">＋ Tambah baris</button>
  <div class="sum" id="f-sum"></div>
  <p class="note">${sales ? 'PPh tidak mengurangi invoice: PPh dipotong customer saat membayar (dicatat di Terima Pembayaran).'
    : 'PPh dipotong ABL dari pembayaran ke vendor, jadi ABL wajib setor & membuat bukti potong.'} Angka final dihitung server saat disimpan.</p>
  <div class="bar" style="margin-top:14px"><button class="btn p" id="f-save">Simpan draft</button><button class="btn p" id="f-savepost">Simpan & Posting</button>
    <span class="sp"></span>${docState.id ? '<button class="btn d" id="f-del">Hapus draft</button>' : ''}</div>`);

  const tbody = $('#f-lines');
  const addRow = (l = {}) => {
    const tr = document.createElement('tr');
    tr.innerHTML = `<td><input class="l-desk" value="${esc(l.deskripsi)}" placeholder="Jasa pengiriman…"></td>
      <td><input class="l-ref" value="${esc(l.ref_lt)}" style="width:110px"></td>
      <td><input class="l-qty" type="number" step="any" value="${l.qty ?? 1}" style="width:80px;text-align:right"></td>
      <td><input class="l-sat" value="${esc(l.satuan || '')}" placeholder="kg" style="width:70px"></td>
      <td><input class="l-harga" type="number" step="any" value="${l.harga ?? ''}" style="width:120px;text-align:right"></td>
      <td class="n l-jml"></td><td><button class="btn s d l-rm">×</button></td>`;
    tbody.appendChild(tr);
    tr.querySelector('.l-rm').onclick = () => { tr.remove(); recalc(); };
    $$('input', tr).forEach(i => i.oninput = recalc);
  };
  (lines.length ? lines : [{}]).forEach(addRow);
  $('#f-addline').onclick = () => { addRow(); recalc(); };

  const party = () => S.contacts.find(x => x.id === $('#f-party').value);
  const setDefTarif = () => { $('#f-tarif').value = r2(defTarif($('#f-pph').value, !!party()?.npwp) * 100); recalc(); };
  $('#f-pph').onchange = setDefTarif;
  $('#f-party').onchange = setDefTarif;
  $('#f-ppn').onchange = recalc; $('#f-tarif').oninput = recalc;
  if ($('#f-kredit')) $('#f-kredit').onchange = recalc;
  if ($('#f-tarif').value === '') $('#f-tarif').value = r2(defTarif(h.pph_jenis, !!party()?.npwp) * 100);

  function recalc() {
    let dpp = 0;
    $$('#f-lines tr').forEach(tr => { const j = r2((+tr.querySelector('.l-qty').value || 0) * (+tr.querySelector('.l-harga').value || 0)); tr.querySelector('.l-jml').textContent = num(j); dpp += j; });
    dpp = r2(dpp);
    const { dnl, ppn } = calcPPN($('#f-ppn').value, dpp);
    const pph = Math.floor(r2(dpp * (+$('#f-tarif').value || 0) / 100));
    $('#f-sum').innerHTML = `<div><span>DPP</span><span>${rp(dpp)}</span></div>
      ${$('#f-ppn').value === 'UMUM' ? `<div><span>DPP nilai lain (11/12)</span><span>${rp(dnl)}</span></div>` : ''}
      <div><span>PPN</span><span>${rp(ppn)}</span></div><div class="b"><span>Total ${sales ? 'invoice' : 'tagihan'}</span><span>${rp(dpp + ppn)}</span></div>
      <div><span>${PPH_SHORT[$('#f-pph').value]} ${sales ? 'dipotong customer' : 'dipotong ABL'}</span><span>${rp(pph)}</span></div>
      <div class="b"><span>${sales ? 'Uang yang diterima' : 'Yang dibayar ke vendor'}</span><span>${rp(dpp + ppn - pph)}</span></div>`;
  }
  recalc();

  $('#f-newparty').onclick = e => {
    e.preventDefault();
    const keep = { ...docState.h, ...readHeader() }, keepLines = readLines();
    contactForm(null, c.partyTipe[0], () => {
      const newest = S.contacts.filter(x => c.partyTipe.includes(x.tipe)).sort((a, b) => b.created_at.localeCompare(a.created_at))[0];
      if (newest) keep[c.party] = newest.id;
      docState.h = keep; docState.lines = keepLines; renderDocForm();
    });
  };
  function readHeader() {
    const o = { [c.party]: $('#f-party').value || null, tanggal: $('#f-tgl').value, jatuh_tempo: $('#f-jt').value || null,
      [c.acct]: $('#f-acct').value, ppn_jenis: $('#f-ppn').value, pph_jenis: $('#f-pph').value,
      pph_tarif: r2((+$('#f-tarif').value || 0) / 100 * 10000) / 10000, no_faktur: $('#f-faktur').value.trim() || null,
      keterangan: $('#f-ket').value.trim() || null };
    if (!sales) { o.no_tagihan_vendor = $('#f-novendor').value.trim() || null; o.ppn_dikreditkan = $('#f-kredit').checked; }
    return o;
  }
  function readLines() {
    return $$('#f-lines tr').map(tr => ({ deskripsi: tr.querySelector('.l-desk').value.trim(), ref_lt: tr.querySelector('.l-ref').value.trim() || null,
      qty: +tr.querySelector('.l-qty').value || 0, satuan: tr.querySelector('.l-sat').value.trim() || null, harga: +tr.querySelector('.l-harga').value || 0 }))
      .filter(l => l.deskripsi && l.qty && l.harga);
  }
  async function save(post) {
    const hd = readHeader(), ls = readLines();
    if (!hd[c.party]) return toast(`Pilih ${c.partyLabel.toLowerCase()}`, true);
    if (!hd.tanggal) return toast('Isi tanggal', true);
    if (!ls.length) return toast('Isi minimal 1 item (deskripsi, qty, harga)', true);
    $('#f-save').disabled = $('#f-savepost').disabled = true;
    try {
      let id = docState.id;
      if (!id) id = (await q(sb.from(c.table).insert(hd).select('id').single())).id;
      else { await q(sb.from(c.table).update(hd).eq('id', id)); await q(sb.from(c.lines).delete().eq(c.fk, id)); }
      await q(sb.from(c.lines).insert(ls.map(l => ({ ...l, [c.fk]: id }))));
      docState.id = id;
      if (post) { const no = await q(sb.rpc(c.post, { p_id: id })); toast(`Diposting: ${no}`); }
      else toast('Draft tersimpan');
      closeModal(); docState.reload && docState.reload();
    } catch (e) { $('#f-save').disabled = $('#f-savepost').disabled = false; }
  }
  $('#f-save').onclick = () => save(false);
  $('#f-savepost').onclick = () => { if (confirm('Posting akan mengunci dokumen dan membuat jurnal. Lanjut?')) save(true); };
  if ($('#f-del')) $('#f-del').onclick = async () => {
    if (!confirm('Hapus draft ini?')) return;
    await q(sb.from(c.table).delete().eq('id', docState.id)); toast('Draft dihapus'); closeModal(); docState.reload();
  };
}

async function renderDocView() {
  const { kind, id, h, lines } = docState, c = DOC[kind], sales = kind === 'sales';
  const pays = await q(sb.from('payments').select('*').eq(sales ? 'invoice_id' : 'bill_id', id).order('tanggal'));
  const live = pays.filter(p => !p.dibatalkan);
  const sisa = sales ? h.total - sum(live, p => +p.jumlah + +p.pph_dipotong) : h.total - h.pph - sum(live, 'jumlah');
  openModal(`<h2>${c.title} ${esc(h.no || '(draft)')} ${tag(h.status)}</h2>
  <div class="cols2 note" style="color:var(--ink)">
    <div><b>${c.partyLabel}:</b> ${esc(h.contacts?.nama)}<br>NPWP: ${esc(h.contacts?.npwp || '-')}</div>
    <div><b>Tanggal:</b> ${fmtDate(h.tanggal)}<br><b>Jatuh tempo:</b> ${fmtDate(h.jatuh_tempo) || '-'}</div>
    <div><b>PPN:</b> ${esc(PPN_JENIS[h.ppn_jenis])}${sales ? '' : (h.ppn_dikreditkan ? '' : ' (tidak dikreditkan)')}<br><b>PPh:</b> ${esc(PPH_SHORT[h.pph_jenis])} ${r2(h.pph_tarif * 100)}%</div>
    <div><b>Akun:</b> ${esc(acctName(h[c.acct]))}<br><b>No faktur:</b> ${esc(h.no_faktur || '-')}${sales ? '' : `<br><b>No tagihan vendor:</b> ${esc(h.no_tagihan_vendor || '-')}`}</div>
  </div>
  ${h.keterangan ? `<p class="note">${esc(h.keterangan)}</p>` : ''}
  <div class="tw"><table><thead><tr><th>Deskripsi</th><th>Ref</th><th class="n">Qty</th><th class="n">Harga</th><th class="n">Jumlah</th></tr></thead><tbody>
  ${lines.map(l => `<tr><td>${esc(l.deskripsi)}</td><td>${esc(l.ref_lt || '')}</td><td class="n">${num(l.qty)} ${esc(l.satuan || '')}</td><td class="n">${num(l.harga)}</td><td class="n">${num(l.jumlah)}</td></tr>`).join('')}
  </tbody></table></div>
  <div class="sum"><div><span>DPP</span><span>${rp(h.dpp)}</span></div>
    ${h.ppn_jenis === 'UMUM' ? `<div><span>DPP nilai lain</span><span>${rp(h.dpp_nilai_lain)}</span></div>` : ''}
    <div><span>PPN</span><span>${rp(h.ppn)}</span></div><div class="b"><span>Total</span><span>${rp(h.total)}</span></div>
    <div><span>${PPH_SHORT[h.pph_jenis]}</span><span>${rp(h.pph)}</span></div>
    ${h.status === 'posted' || h.status === 'lunas' ? `<div class="b"><span>Sisa ${sales ? 'piutang' : 'utang'}</span><span>${rp(sisa)}</span></div>` : ''}</div>
  ${pays.length ? `<h3>${sales ? 'Penerimaan' : 'Pembayaran'}</h3><div class="tw"><table><thead><tr><th>No</th><th>Tanggal</th><th>Akun</th><th class="n">Uang</th>${sales ? '<th class="n">PPh dipotong</th><th>Bukti potong</th>' : ''}<th></th></tr></thead><tbody>
    ${pays.map(p => `<tr><td>${esc(p.no)}${p.dibatalkan ? ' ' + tag('batal') : ''}</td><td>${fmtDate(p.tanggal)}</td><td>${esc(acctName(p.akun_kas))}</td><td class="n">${num(p.jumlah)}</td>
      ${sales ? `<td class="n">${num(p.pph_dipotong)}</td><td>${esc(p.no_bukti_potong || '')}</td>` : ''}
      <td>${!p.dibatalkan && canWrite() ? `<button class="btn s d" data-batalpay="${p.id}">Batal</button>` : ''}</td></tr>`).join('')}</tbody></table></div>` : ''}
  <div class="bar" style="margin-top:14px">
    ${h.status === 'posted' && canWrite() ? `<button class="btn p" id="v-pay">${sales ? 'Terima pembayaran' : 'Bayar'}</button>` : ''}
    ${sales && h.status !== 'draft' ? '<button class="btn" id="v-print">Cetak invoice</button>' : ''}
    <span class="sp"></span>
    ${['posted','lunas'].includes(h.status) && canWrite() ? '<button class="btn d" id="v-batal">Batalkan dokumen</button>' : ''}
  </div>`);
  $$('[data-batalpay]').forEach(b => b.onclick = async () => {
    if (!confirm('Batalkan transaksi ini? Jurnal pembalik akan dibuat.')) return;
    await q(sb.rpc('batal_dokumen', { p_tipe: 'kas', p_id: b.dataset.batalpay, p_tgl: today() }));
    toast('Dibatalkan'); reopen();
  });
  const reopen = async () => { docState.reload && docState.reload(); await openDoc(kind, id, docState.reload); };
  if ($('#v-batal')) $('#v-batal').onclick = async () => {
    if (!confirm('Batalkan dokumen ini? Jurnal pembalik dibuat dengan tanggal hari ini.')) return;
    await q(sb.rpc('batal_dokumen', { p_tipe: c.batal, p_id: id, p_tgl: today() })); toast('Dokumen dibatalkan'); reopen();
  };
  if ($('#v-print')) $('#v-print').onclick = () => printInvoice(h, lines);
  if ($('#v-pay')) $('#v-pay').onclick = () => {
    const firstPay = live.length === 0;
    const defPph = sales && firstPay ? h.pph : 0;
    const defUang = sales ? r2(sisa - defPph) : r2(sisa);
    const box = document.createElement('div'); box.className = 'card'; box.style.marginTop = '12px';
    box.innerHTML = `<h3 style="margin-top:0">${sales ? 'Terima pembayaran' : 'Bayar vendor'}</h3><div class="cols2">
      <label class="f">Tanggal<input type="date" id="p-tgl" value="${today()}"></label>
      <label class="f">Masuk ke / keluar dari<select id="p-kas">${acctOptions(a => a.is_kas, '1-1200')}</select></label>
      <label class="f">Jumlah uang<input type="number" step="any" id="p-jml" value="${defUang}"></label>
      ${sales && h.pph_jenis !== 'NONE' ? `<label class="f">PPh dipotong customer<input type="number" step="any" id="p-pph" value="${defPph}"></label>
      <label class="f">No. bukti potong<input id="p-bp"></label>` : ''}
      <label class="f">Keterangan<input id="p-ket"></label></div>
      <button class="btn p" id="p-go">Simpan</button>`;
    $('#modal-body').appendChild(box); $('#v-pay').disabled = true;
    $('#p-go').onclick = async () => {
      $('#p-go').disabled = true;
      try {
        const no = sales
          ? await q(sb.rpc('record_receipt', { p_invoice: id, p_tgl: $('#p-tgl').value, p_akun_kas: $('#p-kas').value, p_jumlah: +$('#p-jml').value || 0,
              p_pph: $('#p-pph') ? +$('#p-pph').value || 0 : 0, p_bukti: $('#p-bp')?.value.trim() || null, p_ket: $('#p-ket').value.trim() || null }))
          : await q(sb.rpc('record_bill_payment', { p_bill: id, p_tgl: $('#p-tgl').value, p_akun_kas: $('#p-kas').value, p_jumlah: +$('#p-jml').value || 0, p_ket: $('#p-ket').value.trim() || null }));
        toast(`Tersimpan: ${no}`); reopen();
      } catch (e) { $('#p-go').disabled = false; }
    };
  };
}

function printInvoice(h, lines) {
  const s = S.settings, w = window.open('', '_blank');
  w.document.write(`<!DOCTYPE html><html><head><meta charset="utf-8"><title>${esc(h.no)}</title><style>
    body{font-family:system-ui,sans-serif;padding:32px;color:#111;font-size:13px}h1{margin:0;font-size:22px}table{width:100%;border-collapse:collapse;margin-top:16px}
    th,td{border-bottom:1px solid #ddd;padding:7px;text-align:left}td.n,th.n{text-align:right}.top{display:flex;justify-content:space-between;gap:20px}
    .sum{margin-left:auto;width:320px;margin-top:12px}.sum div{display:flex;justify-content:space-between;padding:3px 0}.b{font-weight:700;border-top:1px solid #333;padding-top:6px!important}
    .muted{color:#666;font-size:12px}</style></head><body>
    <div class="top"><div><h1>${esc(s.nama_perusahaan)}</h1><div class="muted">${esc(s.alamat || '')}<br>NPWP: ${esc(s.npwp || '-')}</div></div>
    <div style="text-align:right"><h1>INVOICE</h1><div>${esc(h.no)}</div><div class="muted">Tanggal: ${fmtDate(h.tanggal)}${h.jatuh_tempo ? '<br>Jatuh tempo: ' + fmtDate(h.jatuh_tempo) : ''}</div></div></div>
    <p><b>Kepada:</b><br>${esc(h.contacts?.nama)}<br><span class="muted">${esc(h.contacts?.alamat || '')}<br>NPWP: ${esc(h.contacts?.npwp || '-')}</span></p>
    <table><thead><tr><th>Deskripsi</th><th>Ref</th><th class="n">Qty</th><th class="n">Harga</th><th class="n">Jumlah</th></tr></thead><tbody>
    ${lines.map(l => `<tr><td>${esc(l.deskripsi)}</td><td>${esc(l.ref_lt || '')}</td><td class="n">${num(l.qty)} ${esc(l.satuan || '')}</td><td class="n">${num(l.harga)}</td><td class="n">${num(l.jumlah)}</td></tr>`).join('')}
    </tbody></table>
    <div class="sum"><div><span>DPP</span><span>${rp(h.dpp)}</span></div>
    <div><span>PPN (${PPN_SHORT[h.ppn_jenis]})</span><span>${rp(h.ppn)}</span></div><div class="b"><span>Total</span><span>${rp(h.total)}</span></div>
    ${h.pph > 0 ? `<div><span>${PPH_SHORT[h.pph_jenis]} dipotong pemberi kerja</span><span>(${rp(h.pph)})</span></div><div class="b"><span>Jumlah ditransfer</span><span>${rp(h.total - h.pph)}</span></div>` : ''}</div>
    ${h.ppn_jenis === 'DIBEBASKAN' ? '<p class="muted">PPN dibebaskan sesuai PP 49/2022.</p>' : ''}
    ${h.keterangan ? `<p class="muted">${esc(h.keterangan)}</p>` : ''}
    <script>window.print()<\/script></body></html>`);
  w.document.close();
}

// ================== KONTAK ==================
function contactForm(ct, defTipe, after) {
  ct = ct || { tipe: defTipe || 'customer' };
  const prevHtml = $('#modal').classList.contains('hidden') ? null : $('#modal-body').innerHTML;
  openModal(`<h2>${ct.id ? 'Ubah' : 'Tambah'} kontak</h2><div class="cols2">
    <label class="f">Tipe<select id="c-tipe">${['customer','vendor','keduanya'].map(t => `<option ${t === ct.tipe ? 'selected' : ''}>${t}</option>`).join('')}</select></label>
    <label class="f">Nama<input id="c-nama" value="${esc(ct.nama)}"></label>
    <label class="f">NPWP / NIK (16 digit)<input id="c-npwp" value="${esc(ct.npwp)}"></label>
    <label class="f">Email<input id="c-email" value="${esc(ct.email)}"></label>
    <label class="f">Telepon<input id="c-telp" value="${esc(ct.telp)}"></label></div>
    <label class="f">Alamat<textarea id="c-alamat" rows="2">${esc(ct.alamat)}</textarea></label>
    <p class="note">Kosongkan NPWP kalau lawan transaksi tidak punya; tarif PPh 23 otomatis jadi 4%.</p>
    <button class="btn p" id="c-save">Simpan</button>`);
  $('#c-save').onclick = async () => {
    const o = { tipe: $('#c-tipe').value, nama: $('#c-nama').value.trim(), npwp: $('#c-npwp').value.replace(/\D/g, '') || null,
      email: $('#c-email').value.trim() || null, telp: $('#c-telp').value.trim() || null, alamat: $('#c-alamat').value.trim() || null };
    if (!o.nama) return toast('Isi nama', true);
    if (ct.id) await q(sb.from('contacts').update(o).eq('id', ct.id)); else await q(sb.from('contacts').insert(o));
    S.contacts = await q(sb.from('contacts').select('*').order('nama'));
    toast('Kontak tersimpan'); if (after) after(); else closeModal();
  };
}

// ================== KAS & BANK ==================
async function pgKas(el) {
  el.innerHTML = `<h2>Kas & Bank</h2>
  <div class="bar">${monthPicker('k-m')}<span class="sp"></span>
    ${canWrite() ? '<button class="btn p" id="k-in">＋ Kas masuk</button><button class="btn p" id="k-out">＋ Kas keluar</button>' : ''}</div>
  <div class="grid kpis" id="k-saldo"></div><div class="card tw" id="k-list"></div>`;
  const load = async () => {
    const [d1, d2] = monthRange($('#k-m').value);
    const [rows, tb] = await Promise.all([
      q(sb.from('payments').select('*').gte('tanggal', d1).lte('tanggal', d2).order('tanggal', { ascending:false }).order('created_at', { ascending:false })),
      q(sb.rpc('neraca_saldo', { p_dari: d1, p_sampai: d2 }))
    ]);
    $('#k-saldo').innerHTML = S.accounts.filter(a => a.is_kas).map(a => { const r = tb.find(x => x.kode === a.kode) || {}; return kpi(`${esc(a.nama)} (akhir bulan)`, rp(r.saldo_akhir)); }).join('');
    $('#k-list').innerHTML = rows.length ? `<table><thead><tr><th>No</th><th>Tanggal</th><th>Akun kas</th><th>Lawan</th><th>Keterangan</th><th class="n">Masuk</th><th class="n">Keluar</th><th></th></tr></thead><tbody>
      ${rows.map(p => `<tr><td>${esc(p.no)}${p.dibatalkan ? ' ' + tag('batal') : ''}</td><td>${fmtDate(p.tanggal)}</td><td>${esc(acctName(p.akun_kas))}</td><td>${esc(acctName(p.akun_lawan))}</td>
        <td>${esc(p.keterangan || '')}</td><td class="n">${p.arah === 'masuk' ? num(p.jumlah) : ''}</td><td class="n">${p.arah === 'keluar' ? num(p.jumlah) : ''}</td>
        <td>${!p.dibatalkan && canWrite() && !p.invoice_id && !p.bill_id ? `<button class="btn s d" data-b="${p.id}">Batal</button>` : ''}</td></tr>`).join('')}
      </tbody></table>` : '<p class="note">Belum ada transaksi kas di bulan ini.</p>';
    $$('[data-b]').forEach(b => b.onclick = async () => {
      if (!confirm('Batalkan transaksi ini?')) return;
      await q(sb.rpc('batal_dokumen', { p_tipe: 'kas', p_id: b.dataset.b, p_tgl: today() })); toast('Dibatalkan'); load();
    });
  };
  $('#k-m').onchange = load;
  if ($('#k-in')) { $('#k-in').onclick = () => kasForm('masuk', load); $('#k-out').onclick = () => kasForm('keluar', load); }
  await load();
}
function kasForm(arah, after) {
  const presets = arah === 'keluar'
    ? [['2-1200','Bayar gaji'],['2-1400','Setor PPh 21'],['2-1500','Setor PPh 23'],['2-1600','Setor PPh 15'],['2-1700','Setor PPN'],['2-1800','Bayar BPJS'],['6-1300','Biaya kantor']]
    : [['3-1000','Setoran modal'],['4-1200','Pendapatan lain']];
  openModal(`<h2>Kas ${arah}</h2>
  <div class="bar">${presets.map(p => `<button class="btn s" data-pre="${p[0]}" data-ket="${p[1]}">${p[1]}</button>`).join('')}</div>
  <div class="cols2"><label class="f">Tanggal<input type="date" id="x-tgl" value="${today()}"></label>
    <label class="f">Akun kas/bank<select id="x-kas">${acctOptions(a => a.is_kas, '1-1200')}</select></label>
    <label class="f">${arah === 'masuk' ? 'Sumber (akun lawan)' : 'Untuk (akun lawan)'}<select id="x-lawan">${acctOptions(a => !a.is_kas)}</select></label>
    <label class="f">Jumlah<input type="number" step="any" id="x-jml"></label></div>
  <label class="f">Keterangan<input id="x-ket"></label>
  <p class="note">Untuk pembayaran invoice/tagihan, pakai tombol di dokumennya supaya status lunas ikut terupdate.</p>
  <button class="btn p" id="x-go">Simpan</button>`);
  $$('[data-pre]').forEach(b => b.onclick = () => { $('#x-lawan').value = b.dataset.pre; $('#x-ket').value = b.dataset.ket; });
  $('#x-go').onclick = async () => {
    const no = await q(sb.rpc('kas_transaksi', { p_tgl: $('#x-tgl').value, p_arah: arah, p_akun_kas: $('#x-kas').value,
      p_akun_lawan: $('#x-lawan').value, p_jumlah: +$('#x-jml').value || 0, p_ket: $('#x-ket').value.trim() || null }));
    toast(`Tersimpan: ${no}`); closeModal(); after();
  };
}

// ================== GAJI & PPh 21 ==================
async function pgGaji(el) {
  el.innerHTML = `<h2>Gaji & PPh 21</h2>
  <div class="seg"><button data-t="run" class="on">Payroll bulanan</button><button data-t="emp">Karyawan</button></div><div id="g-body"></div>`;
  const tabs = { run: gajiRuns, emp: gajiEmp };
  $$('.seg button', el).forEach(b => b.onclick = () => { $$('.seg button', el).forEach(x => x.classList.toggle('on', x === b)); tabs[b.dataset.t]($('#g-body')); });
  await gajiRuns($('#g-body'));
}
async function gajiEmp(box) {
  const rows = await q(sb.from('employees').select('*').order('nama'));
  box.innerHTML = `<div class="bar"><span class="sp"></span>${canWrite() ? '<button class="btn p" id="e-new">＋ Karyawan</button>' : ''}</div>
  <div class="card tw">${rows.length ? `<table><thead><tr><th>Nama</th><th>Jabatan</th><th>PTKP</th><th class="n">Gaji pokok</th><th class="n">Tunjangan</th><th class="n">Premi perusahaan</th><th class="n">Iuran pegawai</th><th>Status</th></tr></thead><tbody>
  ${rows.map(r => `<tr class="click" data-id="${r.id}"><td>${esc(r.nama)}</td><td>${esc(r.jabatan || '')}</td><td>${r.ptkp}</td><td class="n">${num(r.gaji_pokok)}</td><td class="n">${num(r.tunjangan_tetap)}</td>
    <td class="n">${num(r.premi_perusahaan)}</td><td class="n">${num(r.iuran_pegawai)}</td><td>${r.aktif ? 'aktif' : 'nonaktif'}</td></tr>`).join('')}</tbody></table>` : '<p class="note">Belum ada karyawan.</p>'}</div>
  <p class="note">Premi perusahaan = JKK, JKM, BPJS Kesehatan yang ditanggung perusahaan (menambah penghasilan bruto untuk PPh 21). Iuran pegawai = JHT 2% + JP 1% bagian karyawan (pengurang di hitungan Desember).</p>`;
  const form = r => {
    if (!canWrite()) return;
    r = r || { ptkp: 'TK/0', aktif: true };
    openModal(`<h2>${r.id ? 'Ubah' : 'Tambah'} karyawan</h2><div class="cols2">
      <label class="f">Nama<input id="e-nama" value="${esc(r.nama)}"></label><label class="f">Jabatan<input id="e-jab" value="${esc(r.jabatan)}"></label>
      <label class="f">NIK<input id="e-nik" value="${esc(r.nik)}"></label><label class="f">NPWP<input id="e-npwp" value="${esc(r.npwp)}"></label>
      <label class="f">Status PTKP (awal tahun)<select id="e-ptkp">${PTKP.map(p => `<option ${p === r.ptkp ? 'selected' : ''}>${p}</option>`).join('')}</select></label>
      <label class="f">Gaji pokok / bulan<input type="number" id="e-gp" value="${r.gaji_pokok ?? 0}"></label>
      <label class="f">Tunjangan tetap / bulan<input type="number" id="e-tj" value="${r.tunjangan_tetap ?? 0}"></label>
      <label class="f">Premi ditanggung perusahaan<input type="number" id="e-pr" value="${r.premi_perusahaan ?? 0}"></label>
      <label class="f">Iuran pegawai (JHT+JP)<input type="number" id="e-iu" value="${r.iuran_pegawai ?? 0}"></label>
      <label class="f" style="padding-top:22px"><input type="checkbox" id="e-aktif" ${r.aktif ? 'checked' : ''}> Aktif</label></div>
      <button class="btn p" id="e-save">Simpan</button>`);
    $('#e-save').onclick = async () => {
      const o = { nama: $('#e-nama').value.trim(), jabatan: $('#e-jab').value.trim() || null, nik: $('#e-nik').value.trim() || null, npwp: $('#e-npwp').value.trim() || null,
        ptkp: $('#e-ptkp').value, gaji_pokok: +$('#e-gp').value || 0, tunjangan_tetap: +$('#e-tj').value || 0, premi_perusahaan: +$('#e-pr').value || 0,
        iuran_pegawai: +$('#e-iu').value || 0, aktif: $('#e-aktif').checked };
      if (!o.nama) return toast('Isi nama', true);
      if (r.id) await q(sb.from('employees').update(o).eq('id', r.id)); else await q(sb.from('employees').insert(o));
      toast('Tersimpan'); closeModal(); gajiEmp(box);
    };
  };
  if ($('#e-new')) $('#e-new').onclick = () => form();
  $$('tr.click', box).forEach(tr => tr.onclick = () => form(rows.find(r => r.id === tr.dataset.id)));
}
async function gajiRuns(box) {
  const runs = await q(sb.from('payroll_runs').select('*, payroll_lines(pph21,take_home,bruto)').order('periode', { ascending:false }));
  box.innerHTML = `<div class="bar">${canWrite() ? `${monthPicker('r-m')}<button class="btn p" id="r-new">Buat payroll</button>` : ''}</div>
  <div class="card tw">${runs.length ? `<table><thead><tr><th>Periode</th><th>Status</th><th class="n">Karyawan</th><th class="n">Bruto</th><th class="n">PPh 21</th><th class="n">Take home</th></tr></thead><tbody>
  ${runs.map(r => `<tr class="click" data-id="${r.id}"><td>${monthName(r.periode.slice(0, 7))}</td><td>${tag(r.status)}</td><td class="n">${r.payroll_lines.length}</td>
    <td class="n">${num(sum(r.payroll_lines, 'bruto'))}</td><td class="n">${num(sum(r.payroll_lines, 'pph21'))}</td><td class="n">${num(sum(r.payroll_lines, 'take_home'))}</td></tr>`).join('')}</tbody></table>` : '<p class="note">Belum ada payroll.</p>'}</div>
  <p class="note">Januari–November dipotong pakai TER bulanan (PP 58/2023). Desember dihitung ulang dengan tarif Pasal 17 setahun dikurangi PPh Jan–Nov, jadi posting Januari–November dulu sebelum membuat Desember.</p>`;
  if ($('#r-new')) $('#r-new').onclick = async () => {
    const id = await q(sb.rpc('generate_payroll', { p_periode: $('#r-m').value + '-01' })); toast('Payroll dibuat'); openRun(id, () => gajiRuns(box));
  };
  $$('tr.click', box).forEach(tr => tr.onclick = () => openRun(tr.dataset.id, () => gajiRuns(box)));
}
async function openRun(id, after) {
  const r = await q(sb.from('payroll_runs').select('*').eq('id', id).single());
  const ls = await q(sb.from('payroll_lines').select('*, employees(nama,nik,npwp)').eq('run_id', id).order('id'));
  const edit = r.status === 'draft' && canWrite();
  const inp = (l, k) => edit ? `<input type="number" data-l="${l.id}" data-k="${k}" value="${l[k]}" style="width:110px;text-align:right">` : num(l[k]);
  openModal(`<h2>Payroll ${monthName(r.periode.slice(0, 7))} ${tag(r.status)}</h2>
  <div class="tw"><table><thead><tr><th>Nama</th><th>PTKP</th><th class="n">Gaji</th><th class="n">Tunjangan</th><th class="n">Bonus/THR/Lembur</th><th class="n">Premi prsh</th>
    <th class="n">Iuran pegawai</th><th class="n">Bruto</th><th>Tarif</th><th class="n">PPh 21</th><th class="n">Take home</th></tr></thead><tbody>
  ${ls.map(l => `<tr><td>${esc(l.employees?.nama)}</td><td>${l.ptkp}</td><td class="n">${inp(l, 'gaji')}</td><td class="n">${inp(l, 'tunjangan')}</td><td class="n">${inp(l, 'lain')}</td>
    <td class="n">${inp(l, 'premi_perusahaan')}</td><td class="n">${inp(l, 'iuran_pegawai')}</td><td class="n">${num(l.bruto)}</td>
    <td>${l.metode === 'TER' ? `TER ${l.ter_kategori} ${r2(l.ter_tarif * 100)}%` : 'Pasal 17 (Des)'}</td><td class="n">${num(l.pph21)}</td><td class="n">${num(l.take_home)}</td></tr>`).join('')}
  <tr class="tot"><td colspan="7">Total</td><td class="n">${num(sum(ls, 'bruto'))}</td><td></td><td class="n">${num(sum(ls, 'pph21'))}</td><td class="n">${num(sum(ls, 'take_home'))}</td></tr></tbody></table></div>
  ${ls.some(l => l.pph21 < 0) ? '<div class="alert">Ada PPh 21 negatif (lebih potong) di Desember: kelebihannya dikembalikan ke karyawan.</div>' : ''}
  <div class="bar" style="margin-top:12px">${edit ? '<button class="btn p" id="r-post">Posting payroll</button>' : ''}
    <button class="btn" id="r-csv">Export CSV</button><span class="sp"></span>
    ${canWrite() && r.status !== 'batal' ? '<button class="btn d" id="r-batal">Batalkan</button>' : ''}</div>
  <p class="note">Setelah posting, bayar gaji lewat Kas keluar → "Bayar gaji", setor PPh 21 lewat Kas keluar → "Setor PPh 21".</p>`);
  $$('input[data-l]').forEach(i => i.onchange = async () => {
    await q(sb.from('payroll_lines').update({ [i.dataset.k]: +i.value || 0 }).eq('id', i.dataset.l)); openRun(id, after);
  });
  if ($('#r-post')) $('#r-post').onclick = async () => {
    if (!confirm('Posting payroll? Data terkunci dan jurnal gaji dibuat.')) return;
    await q(sb.rpc('post_payroll', { p_run: id })); toast('Payroll diposting'); closeModal(); after();
  };
  if ($('#r-batal')) $('#r-batal').onclick = async () => {
    if (!confirm('Batalkan payroll ini?')) return;
    await q(sb.rpc('batal_payroll', { p_run: id })); toast('Dibatalkan'); closeModal(); after();
  };
  $('#r-csv').onclick = () => csvDownload('payroll_' + r.periode.slice(0, 7), ls, [[l => l.employees?.nama, 'Nama'], [l => l.employees?.nik, 'NIK'], [l => l.employees?.npwp, 'NPWP'],
    ['ptkp', 'PTKP'], ['gaji', 'Gaji'], ['tunjangan', 'Tunjangan'], ['lain', 'Lain'], ['premi_perusahaan', 'Premi perusahaan'], ['iuran_pegawai', 'Iuran pegawai'],
    ['bruto', 'Bruto'], ['ter_kategori', 'Kategori TER'], [l => l.ter_tarif != null ? r2(l.ter_tarif * 100) : '', 'Tarif %'], ['pph21', 'PPh 21'], ['take_home', 'Take home']]);
}

// ================== PAJAK ==================
async function pgPajak(el) {
  el.innerHTML = `<h2>Pajak</h2><div class="bar">Masa pajak ${monthPicker('t-m')}</div>
  <div class="seg"><button data-t="ppn" class="on">PPN</button><button data-t="pph">PPh 23 / 15 (ABL potong)</button><button data-t="kredit">PPh dipotong customer</button><button data-t="p21">PPh 21</button></div>
  <div id="t-body"></div>`;
  let tab = 'ppn';
  const render = async () => {
    const ym = $('#t-m').value, [d1, d2] = monthRange(ym), b = $('#t-body');
    const tbl = (rows, cols, totals) => rows.length ? `<div class="tw"><table><thead><tr>${cols.map(c => `<th class="${c[2] ? 'n' : ''}">${c[1]}</th>`).join('')}</tr></thead><tbody>
      ${rows.map(r => `<tr>${cols.map(c => `<td class="${c[2] ? 'n' : ''}">${c[2] ? num(typeof c[0] === 'function' ? c[0](r) : r[c[0]]) : esc(typeof c[0] === 'function' ? c[0](r) : r[c[0]])}</td>`).join('')}</tr>`).join('')}
      ${totals ? `<tr class="tot">${cols.map((c, i) => `<td class="${c[2] ? 'n' : ''}">${i === 0 ? 'Total' : c[2] ? num(sum(rows, c[0])) : ''}</td>`).join('')}</tr>` : ''}
      </tbody></table></div>` : '<p class="note">Tidak ada data.</p>';
    if (tab === 'ppn') {
      const [k, m] = await Promise.all([
        q(sb.from('v_ppn_keluaran').select('*').gte('tanggal', d1).lte('tanggal', d2).order('tanggal')),
        q(sb.from('v_ppn_masukan').select('*').gte('tanggal', d1).lte('tanggal', d2).order('tanggal'))]);
      const K = sum(k, 'ppn'), mk = m.filter(r => r.ppn_dikreditkan), M = sum(mk, 'ppn');
      const colsK = [['tanggal','Tanggal'],['no','Invoice'],['kode_faktur','Kode'],['no_faktur','No faktur'],['customer','Customer'],['npwp','NPWP'],['dpp','DPP',1],['dpp_nilai_lain','DPP nilai lain',1],['ppn','PPN',1]];
      const colsM = [['tanggal','Tanggal'],['no','Tagihan'],['kode_faktur','Kode'],['no_faktur','No faktur'],['vendor','Vendor'],['npwp','NPWP'],['dpp','DPP',1],['ppn','PPN',1],[r => r.ppn_dikreditkan ? 'ya' : 'tidak','Dikreditkan']];
      b.innerHTML = `<div class="grid kpis">${kpi('PPN keluaran', rp(K))}${kpi('PPN masukan dikreditkan', rp(M))}${kpi(K >= M ? 'Kurang bayar (setor)' : 'Lebih bayar (kompensasi)', rp(Math.abs(K - M)))}</div>
        <div class="card"><div class="bar"><b>PPN Keluaran</b><span class="sp"></span><button class="btn s" id="t-ck">CSV</button></div>${tbl(k, colsK, true)}
        <p class="note">Faktur kode 08 (dibebaskan) tetap wajib dibuat & dilaporkan walaupun PPN-nya 0.</p></div>
        <div class="card"><div class="bar"><b>PPN Masukan</b><span class="sp"></span><button class="btn s" id="t-cm">CSV</button></div>${tbl(m, colsM, true)}</div>
        ${canWrite() ? `<div class="card"><b>Jurnal kompensasi PPN</b><p class="note">Memindahkan PPN keluaran & masukan masa ini ke akun Utang PPN (kalau kurang bayar). Jalankan sekali per masa, setelah semua faktur masuk.</p>
          <button class="btn" id="t-komp">Buat jurnal kompensasi ${monthName(ym)}</button></div>` : ''}`;
      $('#t-ck').onclick = () => csvDownload('ppn_keluaran_' + ym, k, colsK.map(c => [c[0], c[1]]));
      $('#t-cm').onclick = () => csvDownload('ppn_masukan_' + ym, m, colsM.map(c => [c[0], c[1]]));
      if ($('#t-komp')) $('#t-komp').onclick = async () => {
        if (K === 0 && M === 0) return toast('Tidak ada PPN di masa ini', true);
        const lines = [{ akun: '2-1300', debit: K, kredit: 0, memo: 'PPN keluaran ' + ym }];
        if (K >= M) { lines.push({ akun: '1-1400', debit: 0, kredit: M, memo: 'PPN masukan ' + ym }); if (K - M > 0) lines.push({ akun: '2-1700', debit: 0, kredit: K - M, memo: 'PPN kurang bayar ' + ym }); }
        else lines.push({ akun: '1-1400', debit: 0, kredit: K, memo: 'Kompensasi sebagian, sisa masukan dibawa ke masa berikut' });
        if (lines.filter(l => l.debit || l.kredit).length < 2) return toast('Tidak ada yang perlu dikompensasi', true);
        if (!confirm(`Buat jurnal kompensasi PPN ${monthName(ym)}?`)) return;
        const no = await q(sb.rpc('create_manual_journal', { p_tgl: d2, p_ket: 'Kompensasi PPN masa ' + ym, p_lines: lines.filter(l => l.debit || l.kredit) }));
        toast('Jurnal dibuat: ' + no);
      };
    } else if (tab === 'pph') {
      const rows = await q(sb.from('v_pph_dipotong_abl').select('*').gte('tanggal', d1).lte('tanggal', d2).order('tanggal'));
      const cols = [['tanggal','Tanggal'],['no','Tagihan'],[r => PPH_SHORT[r.pph_jenis],'Jenis'],['vendor','Vendor'],['npwp','NPWP'],['dpp','DPP (bruto)',1],[r => r2(r.pph_tarif * 100) + '%','Tarif'],['pph','PPh',1],['no_bukti_potong','No bukti potong']];
      b.innerHTML = `<div class="grid kpis">${kpi('PPh 23 harus disetor', rp(sum(rows.filter(r => r.pph_jenis === 'PPH23'), 'pph')))}${kpi('PPh 15 harus disetor', rp(sum(rows.filter(r => r.pph_jenis === 'PPH15_LAUT'), 'pph')))}</div>
        <div class="card"><div class="bar"><b>PPh yang dipotong ABL dari vendor</b><span class="sp"></span><button class="btn s" id="t-c">CSV</button></div>${tbl(rows, cols, true)}
        <p class="note">Buat bukti potong (e-Bupot Unifikasi) di Coretax per vendor, setor paling lambat tanggal 15 bulan berikutnya.</p></div>`;
      $('#t-c').onclick = () => csvDownload('pph_dipotong_abl_' + ym, rows, cols.map(c => [c[0], c[1]]));
    } else if (tab === 'kredit') {
      const rows = await q(sb.from('v_pph_dipotong_customer').select('*').gte('tanggal', d1).lte('tanggal', d2).order('tanggal'));
      const cols = [['tanggal','Tgl bayar'],['invoice_no','Invoice'],[r => PPH_SHORT[r.pph_jenis],'Jenis'],['customer','Customer'],['npwp','NPWP'],['dpp','DPP',1],['pph','PPh dipotong',1],['no_bukti_potong','No bukti potong']];
      b.innerHTML = `<div class="grid kpis">${kpi('PPh 23 (kredit pajak)', rp(sum(rows.filter(r => r.pph_jenis === 'PPH23'), 'pph')))}${kpi('PPh final', rp(sum(rows.filter(r => r.pph_jenis !== 'PPH23'), 'pph')))}</div>
        <div class="card"><div class="bar"><b>PPh yang dipotong customer dari pendapatan ABL</b><span class="sp"></span><button class="btn s" id="t-c">CSV</button></div>${tbl(rows, cols, true)}
        <p class="note">PPh 23 ini jadi kredit pajak di SPT Tahunan Badan. Pastikan bukti potong dari customer sudah diterima.</p></div>`;
      $('#t-c').onclick = () => csvDownload('pph_dipotong_customer_' + ym, rows, cols.map(c => [c[0], c[1]]));
    } else {
      const rows = await q(sb.from('v_pph21').select('*').eq('periode', d1).order('nama'));
      const cols = [['nama','Nama'],['nik','NIK'],['npwp','NPWP'],['ptkp','PTKP'],['bruto','Bruto',1],[r => r.metode === 'TER' ? `TER ${r.ter_kategori} ${r2(r.ter_tarif * 100)}%` : 'Pasal 17','Tarif'],['pph21','PPh 21',1]];
      b.innerHTML = `<div class="grid kpis">${kpi('PPh 21 harus disetor', rp(sum(rows, 'pph21')))}</div>
        <div class="card"><div class="bar"><b>PPh 21 (payroll yang sudah diposting)</b><span class="sp"></span><button class="btn s" id="t-c">CSV</button></div>${tbl(rows, cols, true)}</div>`;
      $('#t-c').onclick = () => csvDownload('pph21_' + ym, rows, cols.map(c => [c[0], c[1]]));
    }
  };
  $$('.seg button', el).forEach(bt => bt.onclick = () => { tab = bt.dataset.t; $$('.seg button', el).forEach(x => x.classList.toggle('on', x === bt)); render(); });
  $('#t-m').onchange = render;
  await render();
}

// ================== LAPORAN ==================
async function pgLaporan(el) {
  const y = today().slice(0, 4);
  el.innerHTML = `<h2>Laporan Keuangan</h2>
  <div class="bar"><input type="date" id="l-d1" value="${y}-01-01" style="width:auto"> s/d <input type="date" id="l-d2" value="${today()}" style="width:auto"></div>
  <div class="seg"><button data-t="lr" class="on">Laba Rugi</button><button data-t="nr">Neraca</button><button data-t="ns">Neraca Saldo</button><button data-t="bb">Buku Besar</button></div>
  <div class="card" id="l-body"></div>`;
  let tab = 'lr';
  const render = async () => {
    const d1 = $('#l-d1').value, d2 = $('#l-d2').value, b = $('#l-body');
    const tb = await q(sb.rpc('neraca_saldo', { p_dari: d1, p_sampai: d2 }));
    const row = (l, v, cls) => `<tr class="${cls || ''}"><td>${l}</td><td class="n">${num(v)}</td></tr>`;
    if (tab === 'lr') {
      const P = tb.filter(r => r.tipe === 'PENDAPATAN').map(r => ({ ...r, v: r.kredit - r.debit })).filter(r => r.v);
      const B = tb.filter(r => r.tipe === 'BEBAN').map(r => ({ ...r, v: r.debit - r.kredit })).filter(r => r.v);
      const tp = sum(P, 'v'), tbb = sum(B, 'v');
      b.innerHTML = `<h3 style="margin-top:0">Laba Rugi ${fmtDate(d1)} – ${fmtDate(d2)}</h3><table>
        <tr><th colspan="2">Pendapatan</th></tr>${P.map(r => row(`${r.kode} ${esc(r.nama)}`, r.v)).join('')}${row('Total pendapatan', tp, 'tot')}
        <tr><th colspan="2">Beban</th></tr>${B.map(r => row(`${r.kode} ${esc(r.nama)}`, r.v)).join('')}${row('Total beban', tbb, 'tot')}
        ${row(tp - tbb >= 0 ? 'LABA BERSIH' : 'RUGI BERSIH', tp - tbb, 'tot')}</table>
        <p class="note">Laba sebelum PPh Badan. Pendapatan yang kena PPh final (mis. PPh 15) perlu dipisah saat SPT Tahunan.</p>`;
    } else if (tab === 'nr') {
      const g = t => tb.filter(r => r.tipe === t && r.saldo_akhir);
      const laba = sum(tb.filter(r => r.tipe === 'PENDAPATAN'), 'saldo_akhir') - sum(tb.filter(r => r.tipe === 'BEBAN'), 'saldo_akhir');
      const A = g('ASET'), K = g('KEWAJIBAN'), E = g('EKUITAS');
      const ta = sum(A, r => r.normal === 'D' ? r.saldo_akhir : -r.saldo_akhir), tk = sum(K, 'saldo_akhir'), te = sum(E, 'saldo_akhir') + laba;
      b.innerHTML = `<h3 style="margin-top:0">Neraca per ${fmtDate(d2)}</h3><table>
        <tr><th colspan="2">Aset</th></tr>${A.map(r => row(`${r.kode} ${esc(r.nama)}`, r.normal === 'D' ? r.saldo_akhir : -r.saldo_akhir)).join('')}${row('Total aset', ta, 'tot')}
        <tr><th colspan="2">Kewajiban</th></tr>${K.map(r => row(`${r.kode} ${esc(r.nama)}`, r.saldo_akhir)).join('')}${row('Total kewajiban', tk, 'tot')}
        <tr><th colspan="2">Ekuitas</th></tr>${E.map(r => row(`${r.kode} ${esc(r.nama)}`, r.saldo_akhir)).join('')}${row('Laba (rugi) belum ditutup', laba)}${row('Total ekuitas', te, 'tot')}
        ${row('Total kewajiban + ekuitas', tk + te, 'tot')}</table>
        ${Math.abs(ta - tk - te) > 1 ? '<div class="alert">Neraca tidak seimbang, cek jurnal.</div>' : '<p class="note">Seimbang ✓</p>'}`;
    } else if (tab === 'ns') {
      const rows = tb.filter(r => r.saldo_awal || r.debit || r.kredit || r.saldo_akhir);
      b.innerHTML = `<div class="bar"><b>Neraca Saldo</b><span class="sp"></span><button class="btn s" id="l-csv">CSV</button></div><div class="tw"><table>
        <thead><tr><th>Akun</th><th class="n">Saldo awal</th><th class="n">Debit</th><th class="n">Kredit</th><th class="n">Saldo akhir</th></tr></thead><tbody>
        ${rows.map(r => `<tr><td>${r.kode} ${esc(r.nama)}</td><td class="n">${num(r.saldo_awal)}</td><td class="n">${num(r.debit)}</td><td class="n">${num(r.kredit)}</td><td class="n">${num(r.saldo_akhir)}</td></tr>`).join('')}
        <tr class="tot"><td>Total</td><td></td><td class="n">${num(sum(rows, 'debit'))}</td><td class="n">${num(sum(rows, 'kredit'))}</td><td></td></tr></tbody></table></div>`;
      $('#l-csv').onclick = () => csvDownload(`neraca_saldo_${d1}_${d2}`, rows, [['kode','Kode'],['nama','Akun'],['saldo_awal','Saldo awal'],['debit','Debit'],['kredit','Kredit'],['saldo_akhir','Saldo akhir']]);
    } else {
      b.innerHTML = `<div class="bar"><select id="l-akun" style="width:auto">${acctOptions(null, '1-1200')}</select><span class="sp"></span><button class="btn s" id="l-csv">CSV</button></div><div id="l-bb"></div>`;
      const show = async () => {
        const k = $('#l-akun').value, a = S.accounts.find(x => x.kode === k), sg = a.normal === 'D' ? 1 : -1;
        const awal = (tb.find(r => r.kode === k) || {}).saldo_awal || 0;
        const rows = await q(sb.rpc('buku_besar', { p_akun: k, p_dari: d1, p_sampai: d2 }));
        let s = +awal; rows.forEach(r => { s += sg * (r.debit - r.kredit); r.saldo = s; });
        $('#l-bb').innerHTML = `<div class="tw"><table><thead><tr><th>Tanggal</th><th>No</th><th>Keterangan</th><th class="n">Debit</th><th class="n">Kredit</th><th class="n">Saldo</th></tr></thead><tbody>
          <tr><td colspan="5">Saldo awal</td><td class="n">${num(awal)}</td></tr>
          ${rows.map(r => `<tr><td>${fmtDate(r.tanggal)}</td><td>${esc(r.no)}</td><td>${esc(r.keterangan || '')}</td><td class="n">${num(r.debit)}</td><td class="n">${num(r.kredit)}</td><td class="n">${num(r.saldo)}</td></tr>`).join('')}
          </tbody></table></div>`;
        $('#l-csv').onclick = () => csvDownload(`buku_besar_${k}`, rows, [['tanggal','Tanggal'],['no','No'],['keterangan','Keterangan'],['debit','Debit'],['kredit','Kredit'],['saldo','Saldo']]);
      };
      $('#l-akun').onchange = show; await show();
    }
  };
  $$('.seg button', el).forEach(bt => bt.onclick = () => { tab = bt.dataset.t; $$('.seg button', el).forEach(x => x.classList.toggle('on', x === bt)); render(); });
  $('#l-d1').onchange = render; $('#l-d2').onchange = render;
  await render();
}

// ================== JURNAL ==================
async function pgJurnal(el) {
  el.innerHTML = `<h2>Jurnal</h2><div class="bar">${monthPicker('j-m')}<span class="sp"></span>${canWrite() ? '<button class="btn p" id="j-new">＋ Jurnal manual</button>' : ''}</div><div class="card tw" id="j-list"></div>`;
  const load = async () => {
    const [d1, d2] = monthRange($('#j-m').value);
    const rows = await q(sb.from('journals').select('*, journal_lines(akun,debit,kredit,memo)').gte('tanggal', d1).lte('tanggal', d2).order('tanggal', { ascending:false }).order('created_at', { ascending:false }));
    $('#j-list').innerHTML = rows.length ? `<table><thead><tr><th>Tanggal</th><th>No / Keterangan</th><th>Akun</th><th class="n">Debit</th><th class="n">Kredit</th></tr></thead><tbody>
      ${rows.map(j => j.journal_lines.map((l, i) => `<tr>${i === 0 ? `<td rowspan="${j.journal_lines.length}">${fmtDate(j.tanggal)}</td>
        <td rowspan="${j.journal_lines.length}"><b>${esc(j.no)}</b> <span class="note">${esc(j.sumber)}</span>${j.dibatalkan ? ' ' + tag('batal') : ''}<br>${esc(j.keterangan || '')}
        ${j.sumber === 'manual' && !j.dibatalkan && canWrite() ? `<br><button class="btn s d" data-b="${j.id}">Batal</button>` : ''}</td>` : ''}
        <td>${l.akun} ${esc(acctName(l.akun))}</td><td class="n">${l.debit ? num(l.debit) : ''}</td><td class="n">${l.kredit ? num(l.kredit) : ''}</td></tr>`).join('')).join('')}
      </tbody></table>` : '<p class="note">Belum ada jurnal di bulan ini.</p>';
    $$('[data-b]').forEach(b => b.onclick = async () => {
      if (!confirm('Batalkan jurnal ini (dibuat jurnal pembalik)?')) return;
      await q(sb.rpc('batal_dokumen', { p_tipe: 'jurnal', p_id: b.dataset.b, p_tgl: today() })); toast('Dibatalkan'); load();
    });
  };
  $('#j-m').onchange = load;
  if ($('#j-new')) $('#j-new').onclick = () => {
    openModal(`<h2>Jurnal manual</h2><div class="cols2"><label class="f">Tanggal<input type="date" id="jm-tgl" value="${today()}"></label>
      <label class="f">Keterangan<input id="jm-ket" placeholder="Saldo awal, penyusutan, koreksi, …"></label></div>
      <div class="tw"><table class="lines"><thead><tr><th>Akun</th><th class="n">Debit</th><th class="n">Kredit</th><th>Memo</th><th></th></tr></thead><tbody id="jm-lines"></tbody></table></div>
      <button class="btn s" id="jm-add">＋ Baris</button><div class="sum" id="jm-sum"></div><button class="btn p" id="jm-save">Simpan</button>`);
    const add = () => { const tr = document.createElement('tr');
      tr.innerHTML = `<td><select class="a">${acctOptions()}</select></td><td><input class="d" type="number" step="any" style="width:120px;text-align:right"></td>
        <td><input class="k" type="number" step="any" style="width:120px;text-align:right"></td><td><input class="m"></td><td><button class="btn s d">×</button></td>`;
      $('#jm-lines').appendChild(tr); tr.querySelector('button').onclick = () => { tr.remove(); bal(); }; $$('input', tr).forEach(i => i.oninput = bal); };
    const read = () => $$('#jm-lines tr').map(tr => ({ akun: tr.querySelector('.a').value, debit: +tr.querySelector('.d').value || 0, kredit: +tr.querySelector('.k').value || 0, memo: tr.querySelector('.m').value || null })).filter(l => l.debit || l.kredit);
    const bal = () => { const l = read(), d = r2(sum(l, 'debit')), k = r2(sum(l, 'kredit'));
      $('#jm-sum').innerHTML = `<div><span>Debit</span><span>${rp(d)}</span></div><div><span>Kredit</span><span>${rp(k)}</span></div><div class="b"><span>${d === k ? 'Seimbang ✓' : 'Selisih'}</span><span>${rp(d - k)}</span></div>`; };
    add(); add(); bal(); $('#jm-add').onclick = add;
    $('#jm-save').onclick = async () => {
      const l = read(); if (r2(sum(l, 'debit')) !== r2(sum(l, 'kredit'))) return toast('Debit dan kredit harus sama', true);
      const no = await q(sb.rpc('create_manual_journal', { p_tgl: $('#jm-tgl').value, p_ket: $('#jm-ket').value.trim() || null, p_lines: l }));
      toast('Tersimpan: ' + no); closeModal(); load();
    };
  };
  await load();
}

// ================== PENGATURAN ==================
async function pgPengaturan(el) {
  const tabs = [['co','Perusahaan'],['kontak','Kontak'],['akun','Akun (COA)']].concat(isAdmin() ? [['user','Pengguna'],['audit','Log perubahan']] : []);
  el.innerHTML = `<h2>Pengaturan</h2><div class="seg">${tabs.map((t, i) => `<button data-t="${t[0]}" class="${i ? '' : 'on'}">${t[1]}</button>`).join('')}</div><div id="s-body"></div>`;
  const R = {
    async co(b) {
      const s = S.settings, ro = canWrite() ? '' : 'disabled';
      b.innerHTML = `<div class="card"><div class="cols2">
        <label class="f">Nama perusahaan<input id="s-nama" value="${esc(s.nama_perusahaan)}" ${ro}></label><label class="f">NPWP<input id="s-npwp" value="${esc(s.npwp)}" ${ro}></label>
        <label class="f">NITKU<input id="s-nitku" value="${esc(s.nitku)}" ${ro}></label><label class="f">Kota<input id="s-kota" value="${esc(s.kota)}" ${ro}></label></div>
        <label class="f">Alamat<textarea id="s-alamat" rows="2" ${ro}>${esc(s.alamat)}</textarea></label>
        <label class="f"><input type="checkbox" id="s-pkp" ${s.is_pkp ? 'checked' : ''} ${ro}> Sudah dikukuhkan sebagai PKP</label>
        ${canWrite() ? '<button class="btn p" id="s-save">Simpan</button>' : ''}</div>`;
      if ($('#s-save')) $('#s-save').onclick = async () => {
        await q(sb.from('settings').update({ nama_perusahaan: $('#s-nama').value.trim(), npwp: $('#s-npwp').value.trim() || null, nitku: $('#s-nitku').value.trim() || null,
          kota: $('#s-kota').value.trim() || null, alamat: $('#s-alamat').value.trim() || null, is_pkp: $('#s-pkp').checked, updated_at: new Date().toISOString() }).eq('id', 1));
        await loadMaster(); toast('Tersimpan'); renderShell(); go('pengaturan');
      };
    },
    async kontak(b) {
      S.contacts = await q(sb.from('contacts').select('*').order('nama'));
      b.innerHTML = `<div class="bar"><span class="sp"></span>${canWrite() ? '<button class="btn p" id="ct-new">＋ Kontak</button>' : ''}</div>
        <div class="card tw">${S.contacts.length ? `<table><thead><tr><th>Nama</th><th>Tipe</th><th>NPWP</th><th>Telp</th></tr></thead><tbody>
        ${S.contacts.map(c => `<tr class="click" data-id="${c.id}"><td>${esc(c.nama)}</td><td>${c.tipe}</td><td>${esc(c.npwp || '— (PPh 23 jadi 4%)')}</td><td>${esc(c.telp || '')}</td></tr>`).join('')}</tbody></table>` : '<p class="note">Belum ada kontak.</p>'}</div>`;
      if ($('#ct-new')) $('#ct-new').onclick = () => contactForm(null, 'customer', () => { closeModal(); R.kontak(b); });
      if (canWrite()) $$('tr.click', b).forEach(tr => tr.onclick = () => contactForm(S.contacts.find(c => c.id === tr.dataset.id), null, () => { closeModal(); R.kontak(b); }));
    },
    async akun(b) {
      b.innerHTML = `<div class="card tw"><table><thead><tr><th>Kode</th><th>Nama</th><th>Tipe</th><th>Normal</th><th>Kas/Bank</th></tr></thead><tbody>
        ${S.accounts.map(a => `<tr><td>${a.kode}</td><td>${esc(a.nama)}${a.sistem ? ' <span class="note">(sistem)</span>' : ''}</td><td>${a.tipe}</td><td>${a.normal}</td><td>${a.is_kas ? '✓' : ''}</td></tr>`).join('')}</tbody></table></div>
        ${canWrite() ? `<div class="card"><b>Tambah akun</b><div class="cols2" style="margin-top:8px">
          <label class="f">Kode<input id="a-kode" placeholder="1-1210"></label><label class="f">Nama<input id="a-nama" placeholder="Bank BCA"></label>
          <label class="f">Tipe<select id="a-tipe">${['ASET','KEWAJIBAN','EKUITAS','PENDAPATAN','BEBAN'].map(t => `<option>${t}</option>`).join('')}</select></label>
          <label class="f" style="padding-top:22px"><input type="checkbox" id="a-kas"> Akun kas/bank</label></div><button class="btn p" id="a-save">Tambah</button></div>` : ''}`;
      if ($('#a-save')) $('#a-save').onclick = async () => {
        const t = $('#a-tipe').value;
        await q(sb.from('accounts').insert({ kode: $('#a-kode').value.trim(), nama: $('#a-nama').value.trim(), tipe: t, normal: ['ASET','BEBAN'].includes(t) ? 'D' : 'K', is_kas: $('#a-kas').checked }));
        await loadMaster(); toast('Akun ditambah'); R.akun(b);
      };
    },
    async user(b) {
      const us = await q(sb.from('app_users').select('*').order('created_at'));
      b.innerHTML = `<div class="card tw"><table><thead><tr><th>Email</th><th>Nama</th><th>Role</th><th>Terdaftar</th></tr></thead><tbody>
        ${us.map(u => `<tr><td>${esc(u.email)}</td><td>${esc(u.nama || '')}</td><td><select data-u="${u.user_id}" style="width:auto" ${u.user_id === S.user.id ? 'disabled' : ''}>
          ${['pending','viewer','finance','admin'].map(r => `<option ${r === u.role ? 'selected' : ''}>${r}</option>`).join('')}</select></td><td>${fmtTs(u.created_at)}</td></tr>`).join('')}</tbody></table>
        <p class="note">admin = semua + kelola pengguna · finance = input & posting · viewer = lihat saja · pending = belum ada akses.</p></div>`;
      $$('[data-u]', b).forEach(s => s.onchange = async () => { await q(sb.from('app_users').update({ role: s.value }).eq('user_id', s.dataset.u)); toast('Role diubah'); });
    },
    async audit(b) {
      const rows = await q(sb.from('audit_log').select('id,waktu,email,tabel,aksi,row_id').order('id', { ascending:false }).limit(300));
      b.innerHTML = `<div class="card tw"><table><thead><tr><th>Waktu</th><th>User</th><th>Tabel</th><th>Aksi</th><th>ID</th></tr></thead><tbody>
        ${rows.map(r => `<tr><td>${fmtTs(r.waktu)}</td><td>${esc(r.email || 'sistem')}</td><td>${esc(r.tabel)}</td><td>${esc(r.aksi)}</td><td class="note">${esc((r.row_id || '').slice(0, 8))}</td></tr>`).join('')}</tbody></table></div>`;
    }
  };
  $$('.seg button', el).forEach(bt => bt.onclick = () => { $$('.seg button', el).forEach(x => x.classList.toggle('on', x === bt)); R[bt.dataset.t]($('#s-body')); });
  await R.co($('#s-body'));
}

init();
</script>
</body>
</html>

