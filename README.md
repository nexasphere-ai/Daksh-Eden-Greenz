<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Daksh Eden Greenz · Menu</title>
<style>
:root{--bg:#f6f4ec;--card:#fff;--ink:#1f2a22;--mute:#6b756d;--g:#1f4d36;--a:#d9902f;--line:#e4e0d2}
@media(prefers-color-scheme:dark){:root{--bg:#121a15;--card:#1a251e;--ink:#eef0e8;--mute:#9aa69d;--g:#7fcf9f;--a:#e8a94d;--line:#2a382f}}
*{box-sizing:border-box}body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.45 system-ui,sans-serif;padding-bottom:90px}
header{background:#1f4d36;color:#fff;padding:36px 20px 28px;text-align:center}
h1{font:600 30px/1.15 Georgia,serif;margin:0 0 6px}header p{margin:2px 0;opacity:.85;font-size:14px}
.wrap{max-width:720px;margin:0 auto;padding:0 16px}
.bar{position:sticky;top:0;z-index:5;background:var(--bg);padding:12px 0 8px;border-bottom:1px solid var(--line)}
input{width:100%;padding:12px 14px;border:1px solid var(--line);border-radius:10px;background:var(--card);color:var(--ink);font-size:16px}
.chips{display:flex;gap:8px;overflow-x:auto;padding:10px 0 2px;scrollbar-width:none}
.chips button{flex:none;border:1px solid var(--line);background:var(--card);color:var(--ink);padding:6px 13px;border-radius:99px;font-size:14px;cursor:pointer}
.chips button.on{background:var(--g);color:#fff;border-color:var(--g)}
h2{font:600 22px Georgia,serif;margin:28px 0 8px;color:var(--g)}
.it{display:flex;justify-content:space-between;align-items:center;gap:12px;padding:12px 0;border-bottom:1px solid var(--line)}
.it b{font-weight:600}.it small{display:block;color:var(--mute)}.it.off{opacity:.5}
.pr{font-weight:600;white-space:nowrap}
.q{display:flex;align-items:center;gap:6px;margin-top:6px;justify-content:flex-end}
.q button,.add{border:1px solid var(--g);background:none;color:var(--g);border-radius:8px;min-width:32px;height:32px;font-size:16px;cursor:pointer;padding:0 12px}
.add{font-size:14px;font-weight:600}.q span{min-width:18px;text-align:center}
.nf{text-align:center;color:var(--mute);padding:30px 0}
.rv{margin:34px 0;padding:20px;border-radius:14px;background:var(--card);border:1px solid var(--line);text-align:center}
.rv h3{margin:0 0 4px;font:600 18px Georgia,serif}.rv p{margin:0 0 12px;color:var(--mute);font-size:14px}
.btn{display:inline-block;background:var(--a);color:#1f1a10;padding:11px 18px;border-radius:10px;font-weight:600;text-decoration:none;border:0;font-size:15px;cursor:pointer}
footer{text-align:center;color:var(--mute);font-size:13px;padding:10px 0 20px}footer a{color:var(--g)}
#cb{position:fixed;left:0;right:0;bottom:0;background:var(--g);color:#fff;padding:14px 20px;display:none;justify-content:space-between;align-items:center;cursor:pointer}
#sh{position:fixed;inset:0;background:#0008;display:none;align-items:flex-end;z-index:9}
#sh .p{background:var(--card);width:100%;max-width:720px;margin:0 auto;border-radius:18px 18px 0 0;padding:20px;max-height:85vh;overflow:auto}
.tot{display:flex;justify-content:space-between;font-weight:700;font-size:18px;padding:14px 0}
.rv input,.rv textarea{margin-bottom:10px;text-align:left}.rv .btn{width:100%}
.st{display:flex;justify-content:center;gap:4px;margin-bottom:14px}
.st button{background:none;border:0;font-size:34px;line-height:1;color:var(--line);cursor:pointer;padding:2px 4px}.st button.on{color:var(--a)}
.rv .btn.g{background:var(--g);color:#fff;margin-top:10px;text-align:center}
.sn{margin-top:14px}.sn label{display:block;font-weight:600;font-size:14px;margin-bottom:6px}
textarea{width:100%;min-height:72px;resize:vertical;padding:11px 14px;border:1px solid var(--line);border-radius:10px;background:var(--bg);color:var(--ink);font:inherit;font-size:15px}
.note{font-size:13px;color:var(--mute);margin-top:10px}
</style></head><body>
<header><h1>Daksh Eden Greenz</h1><p>A luxury resort in Sasan Gir · Pure veg · Open 24×7</p><p>Taxes as applicable extra</p></header>
<div class="wrap">
<div class="bar"><input id="s" placeholder="Search the menu" type="search"><div class="chips" id="ch"></div></div>
<div id="m"></div><div class="nf" id="nf" hidden>Nothing matches that search. Try another word.</div>
<div class="rv"><h3>How was your experience?</h3><p>Tell us how we did. It takes a few seconds.</p>
<div class="st" id="st" role="radiogroup" aria-label="Rating"></div>
<input id="rn" placeholder="Your name (optional)" maxlength="60"><textarea id="rt" maxlength="500" placeholder="What did you like, or what can we improve?"></textarea>
<button class="btn" id="rs" type="button">Send feedback</button><div class="note" id="rm" aria-live="polite"></div></div>
<footer>Menu made by <a href="https://nexasphere-digital-craft.lovable.app/" target="_blank" rel="noopener">Nexa Sphere</a><br>Kindly allow 20–25 minutes to serve you. Outside food not allowed. Images and items subject to availability.</footer>
</div>
<div id="cb"><span id="cn"></span><b>View order</b></div>
<div id="sh"><div class="p"><h2 style="margin-top:0">Your order</h2><div id="ol"></div><div class="sn"><label for="sn">Special note (optional)</label><textarea id="sn" maxlength="300" placeholder="Less spicy, no onion or garlic, Jain, room number, table number…"></textarea></div><div class="tot"><span>Total</span><span id="tt"></span></div><a class="btn" id="wa" href="#" target="_blank" rel="noopener">Send order on WhatsApp</a><div class="note">Opens WhatsApp with your order ready to send. Taxes extra. Tap outside to close.</div></div></div>
<script>
// Format: Name|portion|price|x (x = currently unavailable)
const D={
"Round O Clock":`Tea|80ml|40
Black Tea|80ml|25
Masala Tea|80ml|40
Coffee|80ml|55
Black Coffee|80ml|35
French Fried|200gm|120
Bread Butter||50
Bread Butter Jam||70
Toast Butter||70
Toast Butter Jam||70
Veg Sandwich||70
Veg Grill Sandwich||140
Cheese Sandwich||90
Veg Cheese Sandwich||100
Cheese Grill Sandwich||110
Veg Cheese Grill Sandwich||120
Club Sandwich||140|x
Aloo Poha|180gm|90
Aloo Paratha With Curd||110
Gobi Paratha With Curd||120
Paneer Paratha With Curd||150
Thepla With Curd|2 pcs|110
Poori Bhaji|4 pcs|120
Chole Bhature|2 pcs|150`,
"Beverages":`Cold Milk|200ml|59
Hot Milk|200ml|50
Cold Coffee|250ml|85
Cold Coffee With Ice Cream|250ml|140
Bournvita|200ml|85
Fresh Lemon Water|200ml|40
Fresh Lemon Soda|200ml|60
Plain Soda|740ml|30
Milkshake|250ml|110
Milkshake With Ice Cream|250ml|130
Salted Lassi|200ml|85
Sweet Lassi|200ml|85
Mango Lassi|200ml|95
Pineapple Lassi|200ml|95
Dry Fruit Lassi|200ml|110
Butter Milk|200ml|50
Masala Butter Milk|200ml|35
Water|1 ltr|20
Cold Drinks|250ml btl|30
Red Bull||75|x`,
"Accompaniments":`Fried Papad||40|x
Roasted Papad||30
Masala Papad||50
Cheese Masala Papad||65|x
Veg Raita|100gm|60
Boondi Raita|100gm|70|x
Pineapple Raita|100gm|75|x
Plain Curd|120gm|40
Green Salad|150gm|80
Cucumber Salad|150gm|65|x
Kuchumber Salad|150gm|60
Tomato Salad|150gm|70|x`,
"Khathiyawadi":`Sev Tomato|250gm|190
Aloo Rasawala|250gm|190
Sukhi Bhaji|250gm|120
Lasuniya Batata|250gm|190
Bhindi Masala|250gm|180
Dahi Tikhari|250gm|150
Aloo Baigan|250gm|190
Jeera Aloo|250gm|120
Bharela Baigan|250gm|220`,
"Rice And Noodles":`Veg Hakka Noodles|300gm|220
Singapuri Noodles|300gm|175
Schezwan Noodles|300gm|180
Manchurian Noodles|300gm|220
Veg Fried Rice|300gm|210
Schezwan Fried Rice|300gm|240
Triple Fried Rice|400gm|240`,
"South Indian N Snacks":`Mix Uttapam|regular|170|x
Upma|200gm|140
Idli With Sambhar|3 pcs|120|x
Medu Vada|2 pcs|120|x
Plain Dosa|regular|140|x
Masala Dosa|regular|180|x
Cheese Masala Dosa|regular|220|x
Veg Pakoda|250gm|120
Paneer Pakoda|250gm|220`,
"Soups":`Manchow Soup|150ml|120
Manchurian Soup|150ml|150
Cream Of Tomato Soup|150ml|135
Hot N Sour Soup|150ml|110
Veg Clear Soup|150ml|110
Sweet Corn Soup|150ml|120`,
"Chinese Starters":`Manchurian Dry|225gm|160
Manchurian Gravy|275gm|210
Paneer Chilli Dry|250gm|240
Paneer Chilli Gravy|275gm|220
Mushroom Chilli|225gm|270
Chilli Garlic Potato|250gm|180
Cheese Ball|8 pcs|200
Dragon Potato|250gm|180
Dragon Paneer|250gm|220
Veg Lollipop|6 pcs|270
Veg Crispy|250gm|230
Honey Chilli Potato|250gm|160`,
"Roti":`Plain Roti||30|x
Butter Roti||35|x
Plain Tawa Roti||20
Butter Tawa Roti||25
Plain Naan||45|x
Butter Naan||50|x
Tawa Paratha||50
Lachcha Paratha||55`,
"Dal":`Dal Fried|200gm|180
Dal Tadka|200gm|200
Dal Makhni|200ml|250
Dal Palak|200ml|220
Dal Methi|200ml|220
Gujarati Kadhi|250gm|180`,
"Desserts":`Gulab Jamun|2 pcs|90
Regular Ice Cream||90`,
"Tandoori Starters":`Paneer Tikka Dry|8 pcs|260|x
Paneer Pahadi Tikka|8 pcs|290|x
Paneer Achari Tikka|8 pcs|270|x
Hara Bhara Kabab|8 pcs|180
Paneer Hariyali Tikka|8 pcs|280|x
Mushroom Ka Moti|8 pcs|310
Corn Tikki|8 pcs|180`,
"Pizza N Pasta":`Margarita Pizza|regular|170|x
Italian Pizza|regular|190|x
Veg Pizza|regular|170|x
Tandoori Paneer Pizza|regular|220|x
Peri Peri Paneer Pizza|regular|240|x
White Sauce Pasta|300gm|220|x
Red Sauce Pasta|300gm|220|x`,
"Paneer Main Course":`Paneer Butter Masala|300gm|240
Paneer Lababdar|300gm|250
Paneer Bhurji|300gm|220
Paneer Kadhai|300gm|240
Paneer Handi|300gm|240
Paneer Angara|300gm|290
Paneer Kolhapuri|300gm|240
Kaju Paneer Masala|300gm|280
Mattar Paneer|300gm|220
Palak Paneer|300gm|240
Kaju Butter Masala|300gm|240
Khoya Kaju Sweet|300gm|280
Cheese Butter Masala|300gm|310
Paneer Toofani|300gm|240
Paneer Tawa|300gm|250
Sahi Paneer|300gm|240`,
"Veg Main Course":`Mix Veg|300gm|220
Veg Toofani|300gm|240
Veg Kolhapori||220
Veg Handi||220
Veg Kadhai||220
Veg Jalfrazi||230
Veg Jaipuri||240
Veg Makhanwala||240
Veg Angara||220
Chana Masala||180
Aloo Palak||180
Corn Palak||230
Aloo Methi||210
Chef Special Veg||310|x`,
"Rice":`Jeera Rice|250gm|140
Steam Rice|250gm|120
Peas Pulao|300gm|180
Veg Pulao|300gm|180
Dum Biryani|350gm|260
Hyderabadi Biryani|350gm|240
Dal Masala Khichdi|300gm|140`,
"Mid-Night (11 pm to 7 am)":`Tea|80ml|40
Black Tea|80ml|25
Masala Tea|80ml|40
Coffee|80ml|55
Black Coffee|80ml|35
Milkshake|250ml|110
Milkshake With Ice Cream|250ml|130
Veg Pakoda|250gm|120
Paneer Pakoda|250gm|220
Veg Sandwich||70
Veg Grill Sandwich||140
Cheese Sandwich||90
Veg Cheese Sandwich||100
Cheese Grill Sandwich||110
Veg Cheese Grill Sandwich||120
Club Sandwich||140
Maggi Plain||70
Maggi Masala||90
Cheese Maggi||110
Veg Cheese Maggi||130`};
const WA="919978952953",cart={},items={};let cat="All";
const $=id=>document.getElementById(id),inr=n=>"₹"+n.toLocaleString("en-IN");
const esc=t=>t.replace(/[&<>"]/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[c]));
Object.keys(D).forEach((c,ci)=>D[c]=D[c].split("\n").map((l,i)=>{const[n,p,pr,x]=l.split("|");const o={id:ci+"_"+i,n,p,pr:+pr,off:!!x};items[o.id]=o;return o}));
function render(){
 const q=$("s").value.trim().toLowerCase();let h="",any=0;
 for(const c in D){if(cat!="All"&&cat!=c)continue;
  const L=D[c].filter(o=>!q||o.n.toLowerCase().includes(q)||c.toLowerCase().includes(q));if(!L.length)continue;any=1;
  h+=`<h2>${esc(c)}</h2>`+L.map(o=>`<div class="it${o.off?" off":""}"><div><b>${esc(o.n)}</b>${o.p?`<small>${esc(o.p)}</small>`:""}</div><div style="text-align:right"><div class="pr">${inr(o.pr)}</div>${o.off?`<small>Not available</small>`:cart[o.id]?`<div class="q"><button onclick="ch('${o.id}',-1)">−</button><span>${cart[o.id]}</span><button onclick="ch('${o.id}',1)">+</button></div>`:`<div class="q"><button class="add" onclick="ch('${o.id}',1)">Add</button></div>`}</div></div>`).join("")}
 $("m").innerHTML=h;$("nf").hidden=!!any}
function chips(){$("ch").innerHTML=["All",...Object.keys(D)].map(c=>`<button class="${c==cat?"on":""}" data-c="${esc(c)}">${esc(c)}</button>`).join("")}
$("ch").onclick=e=>{if(e.target.dataset.c){cat=e.target.dataset.c;chips();render();scrollTo(0,0)}};
$("s").oninput=render;
function ch(id,d){cart[id]=(cart[id]||0)+d;if(cart[id]<=0)delete cart[id];render();bar()}
function bar(){let n=0,t=0;for(const id in cart){n+=cart[id];t+=cart[id]*items[id].pr}
 $("cb").style.display=n?"flex":"none";$("cn").textContent=n+(n>1?" items · ":" item · ")+inr(t);
 $("ol").innerHTML=Object.keys(cart).map(id=>`<div class="it"><div><b>${esc(items[id].n)}</b><small>${inr(items[id].pr)} each</small></div><div class="q"><button onclick="ch('${id}',-1)">−</button><span>${cart[id]}</span><button onclick="ch('${id}',1)">+</button></div></div>`).join("");
 $("tt").textContent=inr(t);
 const msg="Hello Daksh Eden Greenz, I'd like to order:\n"+Object.keys(cart).map(id=>`${cart[id]} x ${items[id].n} - ${inr(cart[id]*items[id].pr)}`).join("\n")+`\nTotal: ${inr(t)} (taxes extra)`+($("sn").value.trim()?"\nSpecial note: "+$("sn").value.trim():"");
 $("wa").href="https://wa.me/"+WA+"?text="+encodeURIComponent(msg);if(!n)$("sh").style.display="none"}
$("sn").oninput=bar;
$("cb").onclick=()=>$("sh").style.display="flex";
$("sh").onclick=e=>{if(e.target.id=="sh")$("sh").style.display="none"};
let rate=0;const GR="https://g.co/kgs/e4c2mEu";
function stars(){$("st").innerHTML=[1,2,3,4,5].map(i=>`<button type="button" role="radio" aria-checked="${i==rate}" aria-label="${i} star${i>1?"s":""}" class="${i<=rate?"on":""}" data-r="${i}">★</button>`).join("")}
$("st").onclick=e=>{if(e.target.dataset.r){rate=+e.target.dataset.r;stars()}};
$("rs").onclick=()=>{
 if(!rate){$("rm").textContent="Please tap a star rating first.";return}
 const nm=$("rn").value.trim(),tx=$("rt").value.trim();
 const msg="Feedback for Daksh Eden Greenz\nRating: "+rate+"/5"+(nm?"\nName: "+nm:"")+(tx?"\nComment: "+tx:"");
 window.open("https://wa.me/"+WA+"?text="+encodeURIComponent(msg),"_blank");
 $("rm").innerHTML="Thank you for your feedback."+(rate>=4?`<br><a class="btn g" href="${GR}" target="_blank" rel="noopener">Share it on Google too</a>`:"")};
stars();chips();render();
</script></body></html>
