+++
title = "భూమి కొలతల కాలిక్యులేటర్ (Land Calculator) – Acres to Cents, Sq Ft to Sq Yards"
date = 2026-10-04T10:00:00+05:30
draft = false
slug = "land-measurement-calculator-telugu"
description = "ఎకరాలను సెంట్లలోకి, చదరపు అడుగులను చదరపు గజాలు లేదా చదరపు మీటర్లలోకి ఉచితంగా మార్చుకునే ల్యాండ్ కాలిక్యులేటర్. గుంట, హెక్టార్ లెక్కలు, ఉదాహరణలు, అధికారిక పోర్టల్ లింకులు కూడా ఉన్నాయి."
author = "మధు"
categories = ["Agriculture"]

[cover]
  image = "images/land-measurement-calculator-telugu.jpg"
  alt = "భూమి కొలతల కాలిక్యులేటర్ - ఎకరం, సెంట్, గుంట, చదరపు గజం, చదరపు అడుగుల మార్పిడి"
+++

భూమి కొనుగోలు, అమ్మకం, లేదా వ్యవసాయం చేసేటప్పుడు ల్యాండ్ మెజర్‌మెంట్స్ సరిగ్గా తెలుసుకోవడం చాలా ముఖ్యం. ఈ ఉచిత కాలిక్యులేటర్‌తో మీరు ఎకరాలు, సెంట్లు, గుంటలు, చదరపు గజాలు, చదరపు అడుగుల మధ్య సులభంగా కన్వర్ట్ చేయవచ్చు.

పొలం ఎకరాల్లో చెబుతారు, ఇంటి స్థలం గజాల్లో అమ్ముతారు, ఇంటి ప్లాన్ చదరపు అడుగుల్లో ఉంటుంది. ఒకే స్థలాన్ని ఇన్ని రకాలుగా చెప్పినప్పుడు లెక్క తప్పడం చాలా సులభం, ఒక్క అంకె తప్పితే ధరలో పెద్ద తేడా వస్తుంది.

ఎకరాలను సెంట్లలోకి (Acres to Cents), చదరపు అడుగులను చదరపు గజాల్లోకి (Sq Ft to Sq Yards) లేదా చదరపు మీటర్లలోకి (Sq Ft to Sq Meter) మార్చడం వంటి ఎక్కువగా అవసరమయ్యే లెక్కలన్నీ ఇక్కడ ఉన్నాయి. కాలిక్యులేటర్‌తో పాటు, ఆ లెక్కలు ఎలా వస్తాయో, కొలిచేటప్పుడు సాధారణంగా జరిగే పొరపాట్లు ఏమిటో, రికార్డులు చూడటానికి అధికారిక పోర్టల్స్ ఏవో కూడా ఇచ్చాం.

## కాలిక్యులేటర్ ఎలా వాడాలి

<ol class="steps">
<li><strong>విలువ</strong> బాక్స్‌లో మీ దగ్గర ఉన్న సంఖ్యను రాయండి. దశాంశాలు కూడా వాడొచ్చు (ఉదా: 2.5). తెలుగు అంకెలు రాసినా పనిచేస్తాయి.</li>
<li><strong>యూనిట్</strong> లో ఆ సంఖ్య ఏ కొలతదో ఎంచుకోండి – ఎకరం, సెంట్, గుంట, చదరపు గజం ఇలా.</li>
<li>కింద అన్ని యూనిట్లలో ఫలితం వెంటనే కనిపిస్తుంది. ఏ బటన్ నొక్కాల్సిన అవసరం లేదు.</li>
<li>వచ్చిన ఫలితాన్ని మీ పత్రాల్లో రాసి ఉన్న విస్తీర్ణంతో ఒకసారి సరిచూసుకోండి.</li>
</ol>

## భూమి కొలతల కాలిక్యులేటర్ (Land Measurement Calculator)

<div class="lm-calc" id="lm-calc">
<div class="lm-title">భూమి కొలతల కన్వర్టర్</div>
<div class="lm-inputs">
<div class="lm-field">
<label for="lm-value">విలువ (Value)</label>
<input id="lm-value" type="text" inputmode="decimal" autocomplete="off" value="1" placeholder="ఉదా: 2.5">
</div>
<div class="lm-field">
<label for="lm-unit">యూనిట్ (Unit)</label>
<select id="lm-unit"></select>
</div>
</div>
<p class="lm-msg" id="lm-msg" role="alert" hidden></p>
<ul class="lm-results" id="lm-results" aria-live="polite"></ul>
<p class="lm-note">ఈ లెక్కలు అవగాహన కోసం మాత్రమే. చట్టపరమైన అవసరాలకు ప్రభుత్వ సర్వేయర్ కొలతే ప్రామాణికం.</p>
</div>

<style>
.lm-calc{
  --lm-bg:var(--entry,#ffffff); --lm-ink:var(--primary,#1d2b24); --lm-muted:var(--secondary,#5b6b62);
  --lm-line:var(--border,#d5ddd7); --lm-field:var(--theme,#ffffff); --lm-edge:var(--tertiary,#aab7ae);
  --lm-accent:#2196F3; --lm-err:#d9473b;
  box-sizing:border-box; max-width:560px; margin:1.5rem auto; padding:1.25rem;
  background:var(--lm-bg); color:var(--lm-ink);
  border:1px solid var(--lm-edge); border-radius:10px; line-height:1.5;
}
.lm-calc *{box-sizing:border-box;}
.lm-calc .lm-title{margin:0 0 1rem; font-size:1.2rem; font-weight:700; line-height:1.3;}
.lm-calc .lm-inputs{display:flex; gap:.75rem; flex-wrap:wrap;}
.lm-calc .lm-field{flex:1 1 180px; display:flex; flex-direction:column; gap:.3rem;}
.lm-calc label{font-size:.9rem; color:var(--lm-muted);}
.lm-calc input,.lm-calc select{
  width:100%; min-height:44px; padding:.5rem .65rem; font:inherit; font-size:1.05rem;
  color:var(--lm-ink); background:var(--lm-field); border:1px solid var(--lm-edge); border-radius:6px;
}
.lm-calc input:focus-visible,.lm-calc select:focus-visible{outline:3px solid var(--lm-accent); outline-offset:1px;}
.lm-calc .lm-msg{margin:.75rem 0 0; color:var(--lm-err); font-size:.95rem;}
.lm-calc .lm-results{list-style:none; margin:1rem 0 0; padding:0; border-top:1px solid var(--lm-line);}
.lm-calc .lm-results li{
  display:flex; justify-content:space-between; align-items:baseline; gap:1rem;
  padding:.6rem .6rem .6rem .75rem; border-bottom:1px solid var(--lm-line);
  border-left:4px solid transparent; margin:0;
}
.lm-calc .lm-results li.lm-on{background:rgba(33,150,243,.12); border-left-color:var(--lm-accent);}
.lm-calc .lm-en{color:var(--lm-muted); font-size:.9em;}
.lm-calc .lm-tag{display:block; font-size:.8rem; color:var(--lm-muted);}
.lm-calc .lm-val{font-variant-numeric:tabular-nums; font-weight:700; text-align:right; word-break:break-all;}
.lm-calc .lm-note{margin:1rem 0 0; font-size:.85rem; color:var(--lm-muted);}
</style>

<script>
(function () {
  var root = document.getElementById('lm-calc');
  if (!root) return;

  // sqft = ఒక యూనిట్ ఎన్ని చదరపు అడుగులు
  var U = [
    { id: 'acre',  te: 'ఎకరం',        en: 'Acre',      sqft: 43560 },
    { id: 'cent',  te: 'సెంట్',        en: 'Cent',      sqft: 435.6 },
    { id: 'gunta', te: 'గుంట',        en: 'Gunta',     sqft: 1089 },
    { id: 'sqyd',  te: 'చదరపు గజం',   en: 'Sq Yard',   sqft: 9 },
    { id: 'sqft',  te: 'చదరపు అడుగు', en: 'Sq Feet',   sqft: 1 },
    { id: 'sqm',   te: 'చదరపు మీటర్', en: 'Sq Meter',  sqft: 1 / 0.09290304 },
    { id: 'ha',    te: 'హెక్టార్',     en: 'Hectare',   sqft: 10000 / 0.09290304 }
  ];

  var input = root.querySelector('#lm-value');
  var select = root.querySelector('#lm-unit');
  var list = root.querySelector('#lm-results');
  var msg = root.querySelector('#lm-msg');

  U.forEach(function (u) {
    var o = document.createElement('option');
    o.value = u.id;
    o.textContent = u.te + ' (' + u.en + ')';
    select.appendChild(o);
  });

  function fmt(v) {
    if (v === 0) return '0';
    if (Math.abs(v) >= 1) {
      return new Intl.NumberFormat('en-IN', { maximumFractionDigits: 4 }).format(v);
    }
    return new Intl.NumberFormat('en-IN', { maximumSignificantDigits: 4 }).format(v);
  }

  function parse(raw) {
    var s = raw
      .replace(/[\u0C66-\u0C6F]/g, function (d) { return String(d.charCodeAt(0) - 0x0C66); })
      .replace(/,/g, '')
      .trim();
    if (s === '') return null;
    var n = Number(s);
    return (isFinite(n) && n >= 0) ? n : NaN;
  }

  function render() {
    var n = parse(input.value);
    list.innerHTML = '';
    if (n === null || isNaN(n)) {
      msg.hidden = false;
      msg.textContent = (n === null) ? 'విలువ నమోదు చేయండి.' : 'సరైన సంఖ్య నమోదు చేయండి (ఉదా: 2.5).';
      return;
    }
    msg.hidden = true;
    var from = U.filter(function (u) { return u.id === select.value; })[0];
    var totalSqft = n * from.sqft;

    U.forEach(function (u) {
      var li = document.createElement('li');
      var name = document.createElement('span');
      name.appendChild(document.createTextNode(u.te + ' '));
      var en = document.createElement('span');
      en.className = 'lm-en';
      en.textContent = '(' + u.en + ')';
      name.appendChild(en);
      if (u.id === from.id) {
        li.className = 'lm-on';
        var tag = document.createElement('span');
        tag.className = 'lm-tag';
        tag.textContent = 'మీరు ఇచ్చిన యూనిట్';
        name.appendChild(tag);
      }
      var val = document.createElement('span');
      val.className = 'lm-val';
      val.textContent = fmt(totalSqft / u.sqft);
      li.appendChild(name);
      li.appendChild(val);
      list.appendChild(li);
    });
  }

  input.addEventListener('input', render);
  select.addEventListener('change', render);
  render();
})();
</script>

## అధికారిక పోర్టల్ లింకులు

భూమి రికార్డులు, రిజిస్ట్రేషన్ వివరాల కోసం ప్రభుత్వ అధికారిక సైట్లనే వాడండి. ప్రైవేట్ సైట్లు ఇచ్చే ప్రింట్‌అవుట్లు అధికారిక పత్రాలు కావు.

### ఆంధ్రప్రదేశ్

<ul>
<li><a href="https://meebhoomi.ap.gov.in" target="_blank" rel="noopener noreferrer">మీభూమి (meebhoomi.ap.gov.in)</a> – అడంగల్, 1-బి వంటి భూమి రికార్డులు చూడటానికి.</li>
<li><a href="https://registration.ap.gov.in" target="_blank" rel="noopener noreferrer">రిజిస్ట్రేషన్లు, స్టాంపుల శాఖ (registration.ap.gov.in)</a> – రిజిస్ట్రేషన్ సంబంధిత సేవలు.</li>
<li><a href="https://ccla.ap.gov.in" target="_blank" rel="noopener noreferrer">భూ పరిపాలన ప్రధాన కమిషనర్ కార్యాలయం – CCLA (ccla.ap.gov.in)</a> – రెవెన్యూ శాఖ భూ పరిపాలన వెబ్‌సైట్.</li>
</ul>

### తెలంగాణ

<ul>
<li><a href="https://bhubharati.telangana.gov.in" target="_blank" rel="noopener noreferrer">భూభారతి (bhubharati.telangana.gov.in)</a> – భూ రికార్డుల కోసం ఇప్పుడు ప్రధాన పోర్టల్. గతంలో ఉన్న ధరణి స్థానంలో వచ్చింది.</li>
<li><a href="https://registration.telangana.gov.in" target="_blank" rel="noopener noreferrer">రిజిస్ట్రేషన్లు, స్టాంపుల శాఖ (registration.telangana.gov.in)</a> – రిజిస్ట్రేషన్ సంబంధిత సేవలు.</li>
</ul>

<div class="warning-box">
<strong>గమనిక:</strong> ఈ కాలిక్యులేటర్ ప్రభుత్వ వెబ్‌సైట్ కాదు, ఏ ప్రభుత్వ శాఖతోనూ దీనికి సంబంధం లేదు. పోర్టల్ చిరునామాలు, సేవలు మారవచ్చు. లింక్ పనిచేయకపోతే సంబంధిత శాఖ అధికారిక సైట్‌లో వెతకండి.
</div>

## భూమి కొలిచేటప్పుడు తీసుకోవాల్సిన జాగ్రత్తలు

<ol class="steps">
<li><strong>ముందు యూనిట్ చూడండి.</strong> పత్రంలో ఉన్న విస్తీర్ణం ఎకరాల్లోనా, సెంట్లలోనా, గుంటల్లోనా, గజాల్లోనా అని నిర్ధారించుకున్న తర్వాతే లెక్క మొదలుపెట్టండి.</li>
<li><strong>ఎకరాలు–గుంటలను దశాంశంగా చదవకండి.</strong> "2-20" అంటే 2 ఎకరాలు 20 గుంటలు, అంటే 2.5 ఎకరాలు. దాన్ని 2.20 ఎకరాలుగా చదివితే తేడా వస్తుంది. ఒక ఎకరంలో 40 గుంటలు కాబట్టి 20 గుంటలు అర ఎకరం.</li>
<li><strong>అడుగుల నుంచి గజాల్లోకి మార్చేటప్పుడు 9 తో భాగించండి.</strong> పొడవు, వెడల్పులను విడివిడిగా 3 తో భాగిస్తే గజాల్లో కొలత వస్తుంది. 30×40 అడుగుల స్థలం 1,200 చదరపు అడుగులు, అంటే 133.33 చదరపు గజాలు. 1,200 ను 3 తో భాగించి 400 అనుకోవడం సాధారణంగా జరిగే తప్పు.</li>
<li><strong>సెంట్‌ను రౌండ్ చేయకండి.</strong> ఒక సెంట్ 435.6 చదరపు అడుగులు. సౌలభ్యం కోసం 436 అని లెక్కిస్తే చిన్న స్థలంలో తేడా కనిపించదు, కానీ 500 సెంట్లకు (5 ఎకరాలు) దాదాపు 200 చదరపు అడుగులు ఎక్కువ వస్తుంది.</li>
<li><strong>టేప్ గట్టిగా, సమాంతరంగా లాగండి.</strong> ఇద్దరు ఉండి కొలవండి, వంగిపోయిన టేప్ ఎక్కువ పొడవు చూపిస్తుంది. ప్రతి కొలతను రెండుసార్లు తీసుకుని సరిచూసుకోండి.</li>
<li><strong>వంకర స్థలాన్ని ముక్కలు చేసి లెక్కించండి.</strong> దీర్ఘచతురస్రాలు, త్రిభుజాలుగా విభజించి, ఒక్కో ముక్క విస్తీర్ణాన్ని విడిగా లెక్కించి కూడండి.</li>
<li><strong>ఫోన్ GPS యాప్‌ను అంచనాకే వాడండి.</strong> అవి కొన్ని మీటర్ల తేడా చూపవచ్చు. కొనుగోలు, అమ్మకం, రిజిస్ట్రేషన్, హద్దు వివాదాల్లో ప్రభుత్వ సర్వేయర్ కొలత, రికార్డుల్లో ఉన్న విస్తీర్ణమే లెక్కలోకి వస్తాయి.</li>
</ol>

## కొలతల మధ్య సంబంధం

ఈ పట్టికలో ఉన్న విలువలే కాలిక్యులేటర్ వెనుక ఉన్న లెక్క.

<div class="table-wrap">

| యూనిట్ | చదరపు అడుగులు | చదరపు గజాలు | ఎకరంలో |
|---|---|---|---|
| ఎకరం (Acre) | 43,560 | 4,840 | 1 |
| సెంట్ (Cent) | 435.6 | 48.4 | 0.01 |
| గుంట (Gunta) | 1,089 | 121 | 0.025 |
| చదరపు గజం (Sq Yard) | 9 | 1 | 1/4,840 |
| చదరపు అడుగు (Sq Feet) | 1 | 1/9 | 1/43,560 |
| చదరపు మీటర్ (Sq Meter) | 10.764 | 1.196 | 0.000247 |
| హెక్టార్ (Hectare) | 1,07,639 | 11,959.9 | 2.471 |

</div>

ఒక గుంట అంటే 2.5 సెంట్లు. ఒక ఎకరంలో 100 సెంట్లు లేదా 40 గుంటలు ఉంటాయి.

### కొన్ని ఉదాహరణలు

- **2.5 ఎకరాలు:** 250 సెంట్లు, 100 గుంటలు, 12,100 చదరపు గజాలు, 1,08,900 చదరపు అడుగులు.
- **5 సెంట్లు:** 2,178 చదరపు అడుగులు, 242 చదరపు గజాలు.
- **200 చదరపు గజాల స్థలం:** 1,800 చదరపు అడుగులు, సుమారు 4.13 సెంట్లు.
- **30×40 అడుగుల స్థలం:** 1,200 చదరపు అడుగులు, 133.33 చదరపు గజాలు, సుమారు 2.75 సెంట్లు.

## ఎక్కువగా అవసరమయ్యే మార్పిడులు

కాలిక్యులేటర్ లేకుండా చేతితో లెక్క వేసుకోవాలంటే ఈ సూత్రాలు గుర్తుంచుకోండి:

- **ఎకరాలు నుంచి సెంట్లు (Acres to Cents):** ఎకరాల సంఖ్యను 100 తో గుణించండి. 3 ఎకరాలు = 300 సెంట్లు. సెంట్ల నుంచి ఎకరాలకు మార్చాలంటే 100 తో భాగించండి.
- **సెంట్లు నుంచి చదరపు అడుగులు (Cents to Sq Ft):** సెంట్ల సంఖ్యను 435.6 తో గుణించండి.
- **చదరపు అడుగులు నుంచి చదరపు గజాలు (Sq Ft to Sq Yards):** 9 తో భాగించండి. 2,700 చదరపు అడుగులు = 300 చదరపు గజాలు.
- **చదరపు అడుగులు నుంచి చదరపు మీటర్లు (Sq Ft to Sq Meter):** 10.764 తో భాగించండి, లేదా 0.0929 తో గుణించండి. 1,000 చదరపు అడుగులు సుమారు 92.9 చదరపు మీటర్లు.
- **చదరపు గజాలు నుంచి చదరపు మీటర్లు (Sq Yards to Sq Meter):** 0.8361 తో గుణించండి. 100 చదరపు గజాలు సుమారు 83.6 చదరపు మీటర్లు.

## భూమిని కొలిచే పద్ధతులు

స్థలం ఆకారం సరిగ్గా ఉంటే లెక్క సులభం. ఆకారాన్ని బట్టి వాడే సూత్రాలు ఇవి:

- **దీర్ఘచతురస్రం:** పొడవు × వెడల్పు.
- **త్రిభుజం:** ½ × భూమి × ఎత్తు.
- **ట్రాపీజియం (రెండు భుజాలు సమాంతరంగా ఉన్నప్పుడు):** ½ × (సమాంతర భుజాల మొత్తం) × ఎత్తు. ఉదాహరణకు సమాంతర భుజాలు 40, 60 అడుగులు, వాటి మధ్య దూరం 30 అడుగులు అయితే విస్తీర్ణం ½ × 100 × 30 = 1,500 చదరపు అడుగులు, అంటే సుమారు 166.67 చదరపు గజాలు.
- **మూడు భుజాలు మాత్రమే తెలిసిన త్రిభుజం:** s = (a+b+c)/2 అనుకుని, విస్తీర్ణం = √[s(s−a)(s−b)(s−c)]. ఉదాహరణకు 30, 40, 50 అడుగుల భుజాలకు s = 60, విస్తీర్ణం 600 చదరపు అడుగులు.

కొలవడానికి సాధారణంగా స్టీల్ టేప్ లేదా గొలుసు వాడతారు. పాత కాలంలో 66 అడుగుల గొలుసు వాడేవారు, 10 చదరపు గొలుసులు ఒక ఎకరం. ఫోన్ GPS యాప్‌లతో మొత్తం స్థలం చుట్టూ నడిచి ఉజ్జాయింపు విస్తీర్ణం తెలుసుకోవచ్చు, కానీ చిన్న స్థలాల్లో ఆ తేడా పెద్దదిగా ఉంటుంది. చట్టపరంగా చెల్లేది సంబంధిత ప్రభుత్వ సర్వే విభాగం చేసే కొలతే.

## తరచుగా అడిగే ప్రశ్నలు

<details class="faq-item"><summary>ఒక ఎకరంలో ఎన్ని సెంట్లు, ఎన్ని గుంటలు ఉంటాయి?</summary><p>ఒక ఎకరంలో 100 సెంట్లు, 40 గుంటలు ఉంటాయి.</p></details>
<details class="faq-item"><summary>ఒక సెంట్ అంటే ఎన్ని చదరపు అడుగులు, ఎన్ని గజాలు?</summary><p>ఒక సెంట్ 435.6 చదరపు అడుగులు, అంటే 48.4 చదరపు గజాలు.</p></details>
<details class="faq-item"><summary>ఒక ఎకరంలో ఎన్ని చదరపు గజాలు ఉంటాయి?</summary><p>4,840 చదరపు గజాలు (43,560 చదరపు అడుగులు).</p></details>
<details class="faq-item"><summary>చదరపు అడుగులను గజాల్లోకి ఎలా మార్చాలి?</summary><p>చదరపు అడుగుల సంఖ్యను 9 తో భాగిస్తే చదరపు గజాలు వస్తాయి. ఉదాహరణకు 1,800 చదరపు అడుగులు ÷ 9 = 200 చదరపు గజాలు.</p></details>
<details class="faq-item"><summary>ఎకరాలను సెంట్లలోకి ఎలా మార్చాలి?</summary><p>ఎకరాల సంఖ్యను 100 తో గుణించండి. ఉదాహరణకు 2.5 ఎకరాలు = 250 సెంట్లు.</p></details>
<details class="faq-item"><summary>చదరపు అడుగులను చదరపు మీటర్లలోకి ఎలా మార్చాలి?</summary><p>చదరపు అడుగులను 10.764 తో భాగించండి. ఉదాహరణకు 1,000 చదరపు అడుగులు సుమారు 92.9 చదరపు మీటర్లు.</p></details>
<details class="faq-item"><summary>ఈ కాలిక్యులేటర్ ఫలితాలను రిజిస్ట్రేషన్‌కు వాడవచ్చా?</summary><p>వద్దు. ఇది అవగాహన, ఉజ్జాయింపు లెక్కల కోసం మాత్రమే. రిజిస్ట్రేషన్, అమ్మకం పత్రాల్లో ఉన్న విస్తీర్ణం, ప్రభుత్వ సర్వే కొలతే చెల్లుతాయి.</p></details>

<div class="follow-box">
<p class="label">తాజా అప్‌డేట్స్ కోసం మాతో చేరండి</p>
<div class="btn-row">
<a class="whatsapp-btn" href="https://whatsapp.com/channel/0029VbCOvZq1dAw0grhjJ10p" target="_blank" rel="noopener noreferrer">WhatsApp ఛానెల్</a>
<a class="telegram-btn" href="https://t.me/telugucurrentaffairsandquizzes" target="_blank" rel="noopener noreferrer">Telegram ఛానెల్</a>
</div>
<p class="sub-text">ప్రభుత్వ పథకాలు, ముఖ్య ప్రకటనలు నేరుగా మీ ఫోన్‌లో</p>
</div>

<div class="info-box">
<strong>ఇవి కూడా చదవండి:</strong> రైతులకు పథకాల్లో భూమి వివరాలు సరిగ్గా ఉండటం ముఖ్యం. <a href="PMKISAN_POST_URL_HERE">పీఎం కిసాన్ పథకం వివరాలు</a> ఇక్కడ చూడండి.
</div>

## చివరగా

భూమి కొలతల్లో చిన్న తప్పు కూడా ధరలో, హద్దుల్లో పెద్ద తేడా తెస్తుంది. కాబట్టి ముందు మీ పత్రాల్లో ఉన్న యూనిట్ ఏదో చూసి, ఈ కాలిక్యులేటర్‌తో లెక్క వేసి, చివరికి అధికారిక రికార్డులతో సరిచూసుకోండి. ఈ పేజీలో ఏదైనా లెక్క తప్పుగా అనిపిస్తే Contact పేజీ ద్వారా తెలియజేయండి, సరిచేస్తాం.

---

**గమనిక:** ఈ కాలిక్యులేటర్, వివరణ సాధారణ అవగాహన కోసం మాత్రమే. భూమి కొనుగోలు, అమ్మకం, రిజిస్ట్రేషన్, హద్దు వివాదాల్లో నిర్ణయం తీసుకునే ముందు అధికారిక రికార్డులు, ప్రభుత్వ సర్వే కొలత, అవసరమైతే న్యాయ సలహా తీసుకోండి.

*చివరిసారి సమీక్షించింది: 4 అక్టోబర్ 2026*
