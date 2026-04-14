---
marp: true
paginate: true
theme: aqua
---

<script src="https://cdn.jsdelivr.net/npm/chart.js@4.5.1"></script>
<script src="https://cdn.amcharts.com/lib/5/index.js"></script>
<script src="https://cdn.amcharts.com/lib/5/wc.js"></script>
<script src="https://cdn.amcharts.com/lib/5/themes/Animated.js"></script>

<!--
_class: lead blue
_paginate: false
_footer: "`2026.04.17`"
-->

<style scoped>
ul {
  list-style-type: none;
}
</style>

# 法律工作者群像速寫

* :door: 角色 :bar_chart: 統計

人權法治與司法實務

---

<!--
_footer: "[Google](https://blog.google/intl/zh-tw/company-news/outreach-initiatives/be-scam-ready/) 2025.10"
-->

![bg right](https://storage.googleapis.com/gweb-uniblog-publish-prod/images/Be_Scam_Ready.width-1200.format-webp.webp)

### Google在台推全新遊戲，提升全民詐騙防禦力 :brain:

> Google在台灣推出全新互動遊戲「[防詐大作戰](https://bescamready.withgoogle.com/intl/zh_tw/play)」，帶領使用者透過遊戲式學習，認識常見詐騙手法，輕鬆建立數位防禦力，有效防範網路詐騙。 

---

<!--
_footer: "[劇夠](https://dramago.ptsplus.tv/articles/17984/) 2024.08"
-->

### <!--fit-->《地面師》呈現不動產交易體系的疏漏與盲點，日本受害者實際被詐騙的55億日圓至今仍未討回

> 《地面師》劇情以「地面師」為主軸。「地面」指的是土地，「師」則為專家，這群人自視為土地交易的專家，但實則為進行土地相關詐欺的犯罪分子，利用複雜的土地所有權關係鑽法律漏洞，透過偽造證件、文件，以假冒土地所有人或其代理人，再出售給不知情的買家，因為涉及土地交易，一次騙局往往牽扯到動輒千百萬的金錢交易。<mark>地面師往往是一個集團，包括</mark>負責主導的「領袖」、安排計畫的「交涉人」、消息靈通的「情報員」、<mark>精通法律的「法律專家」</mark>、有偽造技術的「文件偽造師」，以及尋找合適冒充者的「選角人」等成員，分工精細以確保計畫順利實施。
>
> 而這些地面師不是劇情設定，而是真實存在的。1980年代末到1990年代初，日本正值泡沫經濟時期，當時不動產價格高漲，地面師曾活躍一時，爾後在不動產交易文件數位化後，詐騙難度提升，讓地面師詐欺事件看似趨緩。

---

<!--
_footer: "[樂居](https://www.leju.com.tw/page_blog/view/2654) 2025.10"
-->

### 律師、里長、專業人士也涉案！揭密台灣「地面師」的駭人繼承詐術

>整個詐欺流程可能包含以下步驟與關鍵角色：
> 1. 資料收集：鎖定獨居老人或子女長期在國外的對象。
>  :bust_in_silhouette: 里長：最可能知道誰獨居或誰的小孩不在台灣。
>  :bust_in_silhouette: 戶政機關相關人員：掌握戶籍謄本等資訊，確認是否無人繼承。
> 2. 偽造假遺囑：讓遺產繼承看起來合法。
>  :bust_in_silhouette: <mark>律師</mark>：協助代立遺囑。
>  :bust_in_silhouette: 見證人：一共三位，作為代立遺囑的見證。
>  :bust_in_silhouette: <mark>公證人</mark>：為遺囑進行公證，使其具有法律效力。這個步驟結合了三位見證人、律師和公證人，共五個角色來執行，偽造的遺囑看起來非常逼真。
> 3. 假繼承人：尋找一個假裝要繼承遺產的人，進行現場勘查等確認動作。
> 4. 跑完流程：利用假的遺囑和假的繼承人身份，向法院和地政機關跑完過戶流程。

---

<!--
_class: blue
-->

## 角色

## :door:

法律系
常見職業選擇

---

<!--
_footer: "[國立臺灣大學法律學院](https://www.law.ntu.edu.tw/index.php/%E4%BF%AE%E6%A5%AD%E8%A6%8F%E5%AE%9A) 2026.04"
-->

### 法律系必修課

大一
- 憲法:four:、民法總則:three:、刑法總則一:three:、刑法總則二:three:、民法債編總論一:three:

大二
- 行政法:four:、民法債編總論二:three:、民法債編各論:three:、民法身分法:three:、刑法分則:four:、國際公法:two:、法理學:two:、行政救濟法:two:、民法物權:three:、法律史:two:、票據及支付工具法:two::spades:

大三
- 商事法總論及公司法:three:、保險法:two:、民事訴訟法甲上:three:、民事訴訟法甲下:three:、刑事訴訟法:four:、勞動法:two::hearts:、公平交易法:two::clubs:、證券交易法:two::diamonds:

（:spades::hearts::clubs::diamonds:：商事法群組4選2）

---

### 職業選擇：公部門？私部門？

<!-- Styles -->
<style>
#tagCloudDiv {
  width: 85%;
  height: 80%;
}
</style>

<!-- HTML -->
<div style="height:75vh;">
  <div id="tagCloudDiv"></div>
</div>

<!-- Chart code -->
<script>
am5.ready(function() {

// Create root element
// https://www.amcharts.com/docs/v5/getting-started/#Root_element
var root = am5.Root.new("tagCloudDiv");

// Set themes
// https://www.amcharts.com/docs/v5/concepts/themes/
root.setThemes([
  am5themes_Animated.new(root)
]);

// Add wrapper container
var container = root.container.children.push(am5.Container.new(root, {
  width: am5.percent(100),
  height: am5.percent(100),
  layout: root.verticalLayout
}));

// Add series
// https://www.amcharts.com/docs/v5/charts/word-cloud/
var series = container.children.push(am5wc.WordCloud.new(root, {
  categoryField: "tag",
  valueField: "weight",
  minFontSize: am5.percent(10),
  maxFontSize: am5.percent(30),
  calculateAggregates: true // this is needed for heat rules to work
}));

// Set up heat rules
// https://www.amcharts.com/docs/v5/charts/word-cloud/#Via_heat_rules
series.set("heatRules", [{
  target: series.labels.template,
  dataField: "value",
  min: am5.color(0x95d5b2),
  max: am5.color(0x2d6a4f),
  key: "fill"
}]);

// Configure labels
series.labels.template.setAll({
  paddingTop: 5,
  paddingBottom: 5,
  paddingLeft: 5,
  paddingRight: 5,
  fontFamily: "GenSekiGothicTW",
  cursorOverStyle: "pointer"
});

// Data from:
// https://www.sir.tw/Article/Detail/96627
series.data.setAll([
  { tag: "法官", weight: 50 },
  { tag: "檢察官", weight: 45 },
  { tag: "書記官", weight: 20 },
  { tag: "公證人", weight: 30 },
  { tag: "專利師", weight: 30 },
  { tag: "律師", weight: 40 },
  { tag: "法制人員", weight: 30 },
  { tag: "法律廉政人員", weight: 30 },
  { tag: "法務", weight: 20 },
  { tag: "家族信託規劃師", weight: 20 },
  { tag: "法律顧問", weight: 25 },
  { tag: "政治工作", weight: 15 },
  { tag: "學術研究", weight: 15 },
  { tag: "檢察事務官", weight: 10 },
  { tag: "司法事務官", weight: 10 },
  { tag: "監所管理員", weight: 10 },
  { tag: "調查局", weight: 25 },
  { tag: "國家安全情報人員", weight: 25 },
  { tag: "犯罪防治人員", weight: 20 },
  { tag: "政治工作", weight: 15 },
  { tag: "學術研究", weight: 15 },
  { tag: "倡議組織", weight: 15 },
]);

}); // end am5.ready()
</script>

---

<!--
_footer: "[臺灣高等檢察署](https://www.tph.moj.gov.tw/4421/4475/4489/25479/) 2024.04"
-->

### 不同的法袍顏色代表什麼職務？

| | | |
| :---: | :---: | :---: |
| 檢察官<br>![w:200px 檢察官法袍](https://www.tph.moj.gov.tw/media/355662/%E6%AA%A2%E5%AF%9F%E5%AE%98%E6%B3%95%E8%A2%8D.png) | 法官<br>![w:200px 法官法袍](https://www.tph.moj.gov.tw/media/355665/%E6%B3%95%E5%AE%98%E6%B3%95%E8%A2%8D.png) | 書記官<br>![w:200px 書記官法袍](https://www.tph.moj.gov.tw/media/355667/%E6%9B%B8%E8%A8%98%E5%AE%98%E6%B3%95%E8%A2%8D.png) | 
| 公證人<br>![w:200px 公證人法袍](https://www.tph.moj.gov.tw/media/355664/%E5%85%AC%E8%AD%89%E4%BA%BA%E6%B3%95%E8%A2%8D.png) | 公設辯護人<br>![w:200px 公設辯護人法袍](https://www.tph.moj.gov.tw/media/355663/%E5%85%AC%E8%A8%AD%E8%BE%AF%E8%AD%B7%E4%BA%BA%E6%B3%95%E8%A2%8D.png) | 律師<br>![w:200px 律師法袍](https://www.tph.moj.gov.tw/media/355666/%E5%BE%8B%E5%B8%AB%E6%B3%95%E8%A2%8D.png) |

---

### 司法官 :heavy_equals_sign: 法官 :heavy_plus_sign: 檢察官

法官法13
> 1. <mark>法官</mark>應依據憲法及法律，本於良心，超然、獨立、公正審判，不受任何干涉。
> 2. <mark>法官</mark>應遵守法官倫理規範，其內容由司法院徵詢全國法官代表意見定之。

法官法86
> 1. <mark>檢察官</mark>代表國家依法追訴處罰犯罪，為維護社會秩序之公益代表人。檢察官須超出黨派以外，維護憲法及法律保護之公共利益，公正超然、勤慎執行檢察職務。

---

<!--
_footer: "[臺灣高等檢察署](https://www.tph.moj.gov.tw/4421/4475/4489/25477/) 2024.04"
-->

### 檢察官與法官有何不同？

| | 檢察官 | 法官 |
| --: | :---: | :---: |
| 主要業務 | 偵查刑事案件 | 審理案件<br>（含刑事、民事、行政、非訟等） |
| 工作內容 | 指揮偵查刑案，<br>決定對被告起訴/不起訴/緩起訴處分。 | 審理訴訟，<br>決定被告有罪與否。 |
| 案件可否公開 | 偵查案件不公開，不允許旁聽。 | 原則公開，可以旁聽；<br>例外不公開，不能旁聽。 |
| 管轄機關 | 行政院法務部 | 司法院 |

---

### 律師

律師法1
> 1. 律師以保障人權、實現社會正義及促進民主法治為使命。
> 2. 律師應基於前項使命，本於自律自治之精神，誠正信實執行職務，維護社會公義及改善法律制度。

律師倫理規範7
> 律師應體認律師職務為公共職務，於執行職務時，應兼顧當事人合法權益及公共利益。

律師倫理規範11
> 律師不應拘泥於訴訟勝敗而忽略真實之發現。

律師倫理規範13
> 律師不得以違反公共秩序善良風俗或有損律師尊嚴與信譽之方法受理業務。

---

### 鄉野傳說

![](https://mermaid.ink/svg/pako:eNo9kNtKw0AQhl8lzHUsOTSH7q3e-gKSm8Vs20A3W7YbsJZeFFREUUHRoqg9CGIQL0RBLNanadLtW5gmrTAX8_3_zD8wHdhlPgEENAh9iptemBwey594fncg43f53JO9qRcqirI4epVvX7PJJLka5YKizM9P0_HLCuTJZfp4n0P6cS3HZys9_ezL0VMaDworHiS365XZ901WK1g8DJPf_mx6ASrUeOADEjwiKlDCKV4idJaTHog6ocQDlLVVxklLeKAWTgO3WSQKSwR-e0Nwkk16YTfLbOJwhzG6juUsqtUBVXGjlVHU9LEgWwGucUz_VU5Cn_BNFoUCkKE5eQigDuwBKpt2yS5rtmGp0Aaku3pJ1w3b0dyKWzYdq6vCfn5OKzmmZWqm5eqaVbF021CB-IFgfLt4fP7_7h_NrZPn)

<!-- https://mermaid.ai/live/edit#pako:eNo9kNtKw0AQhl8lzHUsOTSH7q3e-gKSm8Vs20A3W7YbsJZeFFREUUHRoqg9CGIQL0RBLNanadLtW5gmrTAX8_3_zD8wHdhlPgEENAh9iptemBwey594fncg43f53JO9qRcqirI4epVvX7PJJLka5YKizM9P0_HLCuTJZfp4n0P6cS3HZys9_ezL0VMaDworHiS365XZ901WK1g8DJPf_mx6ASrUeOADEjwiKlDCKV4idJaTHog6ocQDlLVVxklLeKAWTgO3WSQKSwR-e0Nwkk16YTfLbOJwhzG6juUsqtUBVXGjlVHU9LEgWwGucUz_VU5Cn_BNFoUCkKE5eQigDuwBKpt2yS5rtmGp0Aaku3pJ1w3b0dyKWzYdq6vCfn5OKzmmZWqm5eqaVbF021CB-IFgfLt4fP7_7h_NrZPn -->

<!-- ```mermaid
{
  "theme": "forest",
  "layout": "tidy-tree"
}

mindmap
先輩的話要聽
   醫護人員
     王梨
     芒果
   法袍
     洗衣機
   機器
     乖乖
     靠得住
``` -->

---

<!--
_footer: "[法律百科](https://www.legis-pedia.com/QA/question/1306) 2021.04"
-->

### 請問臺灣司法人員除了法袍以外，還需要穿戴什麼東西嗎？法袍可以洗嗎？

> 法袍能不能洗這件事，主要是流傳在律師界的習俗。<mark>有認為法袍是累積運氣跟道行的服裝，所以洗法袍會導致功力大減。</mark>不過，也有律師認為基於尊重所有法庭參與者的原因，服儀整齊、法袍清潔才是比較適當的做法。而不論是基於習俗或因為想避免弄髒法袍，律師如廁的時候是不會穿著法袍的。

---

<!--
_footer: "[今日新聞](https://www.nownews.com/news/6782749) 2026.02"
-->

### 揭秘法界5大生存守則！法官律師「芒旺」兩樣情　洗法袍也藏學問

> 行銷逾半世紀的「乖乖」不僅是國民零食，更是台灣法官祈求案件順遂的吉祥物。法官常將其供奉於辦公桌或卷證櫃，期盼案情不節外生枝、順利結案。不過，挑選乖乖有其禁忌：法官僅擺放綠色包裝的椰子口味，象徵「綠燈」一路通關；至於黃色的五香口味則是辦公室大忌，因「五香」音同「五箱」，對法官而言，這代表卷宗數量驚人，絕對不能亂放。...
>
> 法學界對法袍洗滌極其講究。<mark>律師深信白邊袍象徵黑白分明，洗了會洩掉「浩然正氣」與勝訴好運，因此袍子愈灰黃，往往代表資歷與功力愈深</mark>；法官與檢察官則視運勢而定：若審案不順，會洗袍祈求「洗去霉運」；反之若歲月靜好，則絕對不洗，以免驚動現有的順遂氣場。

---

<!--
_class: blue
-->

## 統計

## :bar_chart:

狀態
競爭
未來

---

<!--
_footer: "[天下雜誌](https://www.cw.com.tw/article/5140131) 2026.03"
-->

### 書記官消失中》新北地檢十年補不滿40個缺、台中詐欺犯5年後才通知入獄

> 新北地檢署的一間辦公室，桌上堆滿如山高的卷宗。電話聲此起彼落，可能是民眾追問不起訴理由，也可能是被告律師急著改開庭日期，但電話始終無人接聽。檢察官也探頭找座位的主人JJ（化名），只見桌上留下「有事留言」的便條。當了12年書記官的她手腳利索，但仍需沒日沒夜地加班，因為書記官都跑光了。
>
> 「我們書記官缺額40個，已經缺了10年，」一名知情的資深檢察官表示。
>
> JJ的工作不只<mark>開庭打筆錄</mark>，還要<mark>接電話</mark>、<mark>寄送書類</mark>和<mark>歸檔</mark>。一位檢察官每月幾百件案子，被告與律師的壓力全倒在書記官一人身上。且因為書記官流動率太大，她還要花時間陪「新人」開庭，傳授筆錄系統快捷鍵與檢察官習慣。
>
> JJ從「比慘」裡得到安慰，因為隔壁新北地方法院更慘，去年缺額71人，結果只報到2人。法官得共用書記官，開庭次數被迫縮減，民眾的案子愈拖愈久。

---

<!--
_footer: "[報導者](https://www.twreporter.org/a/massive-fraud-cases-overwhelm-judicial-system-prosecutor) 2025.12"
-->

### 從熱血檢察官到僵化結案機器──巨量詐騙案衝擊，新北地檢署爆發離職潮

> 2025年以來，新北地方檢察署有10名檢察官離職出走，創下該署最高紀錄。位於新北市土城區的新北檢，向來是全台業務最為繁重的地檢署，根據法務部統計，2024年新收檢察案件就高達32萬件，數量高居全台22個地檢署之冠。
> 
> 此外，檢閱近5年數字更可以發現，<mark>大量激增的案件中，詐欺已成為主流</mark>。這類以掠奪金錢為主要目標的犯罪，就像是夾雜著砂礫和巨石的泥流，一次又一次地衝擊著司法防線。身處一線的司法官們如何自處？其中不少人為何選擇拋下鐵飯碗？詐欺暴增帶來的大量副作用又怎麼影響台灣司法體系？這些棘手的問題正一步步發酵。...
>
> 今年9月，連二審高等法院都決議暫時停分詐欺案4個月，另創刑事「審查中心」，<mark>對詐欺案件進行預先程序審查，以嚴格控管案量</mark>，提升處理效率。11月，彰化地檢署更對一名提款逾200次的詐欺車手求處高達30年刑度，並強調此舉是基於一罪一罰及罪刑相當原則，每個行為都應被完整評價及定刑，創下國內少見紀錄。

---

<!--
_footer: "[獨立評論＠天下](https://opinion.cw.com.tw/blog/profile/566/article/15477) 2024.11"
-->

### 血汗司法進行式：書記官大逃亡

> 無論在法院或檢察機關，書記官的重要性，並不亞於大眾更常聽到的法官或檢察官。...書記官的工作在開庭之外琳瑯滿目，例如當事人聲請法院送鑑定，法官也認為有必要性，但這些司法機關的函文、鑑定許可等文書，不是如同AI可以自動生成，就需要書記官在開庭後去處理。
>
> 還有其他林林總總的工作，如被告傳喚後沒有到庭，要製作拘票；又或者這幾年大幅增加的刑事訴訟科技監控等強制處分，書記官在法官決定後，要製作相關函文跟聯繫工作，可說是司法過勞下首當其衝者。
>
> 這裡還沒提到這幾年台灣<mark>詐騙案件</mark>激增，<mark>一個案件的被害人往往多達數十位甚至上百位</mark>，光是通知一件詐騙案件的被害人到庭，就佔據了快一整天時間。這些被佔據的日常工時，只能在下班後加班補回，當然不用說公務機關那微薄的加班費，註定只能做功德。這是血汗司法的縮影，也是基層司法過勞的日常。

---

<!--
_footer: "[鏡週刊](https://www.mirrormedia.mg/story/20240122pol001) 2024.01"
-->

### 正義的成本　當檢察官與法官陸續昏倒

> 案件太多了。吳承學提供我們一份統計，以台北地方法院近10年為例，2013年總案件量為2.7萬多件，2023年增至3.5萬多件，10年增加3成，讓本就過勞的他們，精疲力竭到幾乎難以負荷。其中，詐騙案件增加最多，10年前一年僅800多件，2023年已暴增至一年3千多件。法官鮑慧忠就說：「我們快要被詐欺案件淹沒了！」
>
> <mark>法官是後端，司法流程的前端是檢察官，檢察官偵查後決定起訴的案子，才會送到法院。法院案件量驟增，必定代表前端地檢署的案件量更加驚人。</mark>
>
> 以近5年的案件量來看，統計資料顯示，2019年時，全台地檢署一整年的新收案件量約56萬多件，到2023年，已暴增至一年83萬多件，短短5年，案件量增加了47％。

---

<!--
_footer: "[司法院](https://www.judicial.gov.tw/tw/cp-1789-90906-ae4c1-1.html) 2026.02"
-->

### 法院統計：司法院及所屬各機關收結件數

<div style="height:75vh;">
  <canvas id="barChartCourt"></canvas>
</div>

<script>
  const ctxCourt = document.getElementById('barChartCourt');

  new Chart(ctxCourt, {
    type: 'bar',
    data: {
      labels: ['2015', '2016', '2017', '2018', '2019', '2020', '2021', '2022', '2023', '2024', '2025'],
      datasets: [{
        label: '新收件數',
        data: [3036007, 3134394, 3120818, 3141528, 3272998, 3375910, 3247571, 3579411, 3876061, 4177668, 4214912],
        borderWidth: 1
      },
      {
        label: '終結件數',
        data: [3027555, 3118330, 3106737, 3132630, 3258677, 3381191, 3226216, 3549731, 3792844, 4033149, 4247229],
        borderWidth: 1
      }]
    },
    options: {
    	responsive: true,
	    plugins: {
	      legend: {
	        position: 'top',
	      }
	    }
    }
  });
</script>

---

<!--
_footer: "[法務部](https://www.rjsd.moj.gov.tw/RJSDWeb/visualize/Visualization.aspx?kind=PC&d=12) 2026.04"
-->

### 地檢署統計：地方檢察署偵查新收件數

<div style="height:75vh;">
  <canvas id="barChartProsecute"></canvas>
</div>

<script>
  const ctxProsecute = document.getElementById('barChartProsecute');

  new Chart(ctxProsecute, {
    type: 'bar',
    data: {
      labels: ['2022', '2023', '2024', '2025'],
      datasets: [{
        label: '非電信網路詐欺新收件數',
        data: [(639301-160803), (733505-229711), (670574-167931), (694824-165834)],
        borderWidth: 1,
        order: 2,
        yAxisID: 'yCount',
      },
      {
        label: '電信網路詐欺新收件數',
        data: [160803, 229711, 167931, 165834],
        borderWidth: 1,
        order: 1,
        yAxisID: 'yCount',
      },
      {
        label: '電信網路詐欺占全部偵查新收件數比率',
        data: [25.2, 31.3, 25.0, 23.9],
        borderWidth: 2,
        type: 'line',
        order: 0,
      }]
    },
    options: {
      scales: {
        x: {
          stacked: true,
        },
        y: {
          beginAtZero: true,
          position: 'right',
          title: {
            display: true,
            text: '%',
          }
        },
        yCount: {
          stacked: true,
          beginAtZero: true,
          title: {
            display: true,
            text: '件',
          }
        },
      }
    }
  });
</script>

---

<!--
_footer: "[民視新聞網](https://www.ftvnews.com.tw/news/detail/2025B21W0049) 2025.11"
-->

### 勞動部公文讓法官、檢察官哭笑不得　竟要求開庭別太密集以免律師過勞

> <mark>勞動部</mark>日前發文<mark>司法院</mark>和<mark>法務部</mark>，希望要求所屬法官和檢察官安排庭期時，不要過度密集以免律師過勞。上述公文在法官和檢察官群組瘋傳，讓司法官們覺得不可思議。
>
> 有法官表示，司法院和法務部並非律師的雇主，法官和檢察官為保障民眾訴訟權益，安排適當庭期讓案子順利進行，至於律師們合理的工作量應該是律師事務所老闆和法扶基金會負責人的責任。
>
> 有檢察官指出，從勞動部公文內容來看，應該是<mark>法律扶助基金會</mark>發函要求勞動部幫忙發文，而勞動部也照辦，希望司法院和法務部要求法官和檢察官安排庭期時，要能顧及律師身心健康及合理工時。這位檢察官表示，現在詐欺案件這麼多，檢警都忙得人仰馬翻，勞動部怎麼不發文給法務部，要求檢警不要一直抓壞人，以免支援檢警辦案的檢察署和法院職員嚴重過勞？


---

<!--
_footer: "[法務部](https://www.rjsd.moj.gov.tw/RJSDWeb/common/WebList3.aspx?menu=INF_COMMON_LAWYER) 2026.04"
-->

### 律師統計：本國律師人數（人）

<div style="height:75vh;">
  <canvas id="barChartAttorney"></canvas>
</div>

<script>
  const ctxAttorney = document.getElementById('barChartAttorney');

  new Chart(ctxAttorney, {
    type: 'line',
    data: {
      labels: ['2020', '2021', '2022', '2023', '2024'],
      datasets: [{
        label: '累計已領證',
        data: [18484, 18928, 19448, 20171, 20902],
        fill: 1,
        order: 1,
      },
      {
        label: '年底累計加入公會',
        data: [9569, 11123, 11454, 11998, 12562],
        fill: true,
        order: 0,
      }]
    },
    options: {
      scales: {
        y: {
          beginAtZero: true,
          title: {
            display: true,
            text: '人',
          }
        }
      }
    }
  });
</script>

---

<!--
_footer: "[法務部](https://www.rjsd.moj.gov.tw/RJSDWeb/common/WebList3.aspx?menu=INF_COMMON_LAWYER) 2026.04"
-->

### 律師統計：律師服務單位規模（家）

| 年 | 總計 | 1人 | 2人 | 3-5人 | 6-10人 |	11-20人 | 21-50人 | 51人+ |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 2017 | 5,894 | 4,267 | 782 | 648 | 150 | 34 | 10 | 3 |
| 2018 | 5,917 | 4,237 | 762 | 702 | 159 | 41 | 13 | 3 |

<div style="height:55vh;">
  <canvas id="bubbleChartAttorney"></canvas>
</div>

<script>
  const ctxAttorneyCount = document.getElementById('bubbleChartAttorney');

  new Chart(ctxAttorneyCount, {
    type: 'bubble',
    data: {
        datasets: [{
            label: '2018',
            data: [{
              x: 1,
              y: 4237,
              r: 42.37 // x*y*0.01
            }, {
              x: 2,
              y: 762,
              r: 15.24
            }, {
              x: 4, // (3+5)*0.5
              y: 702,
              r: 28.08
            }, {
              x: 8,
              y: 159,
              r: 12.72
            }, {
              x: 15,
              y: 41,
              r: 6.15
            }, {
              x: 35,
              y: 13,
              r: 4.55
            }, {
              x: 51,
              y: 3,
              r: 1.53
            }]
          }
      ]
    },
    options: {
      scales: {
        x: {
          title: {
            display: true,
            text: '律師服務單位規模（人）',
          }
        },
        y: {
          beginAtZero: true,
          title: {
            display: true,
            text: '家',
          }
        }
      }
    }
  });
</script>

---

<!--
_footer: "[聯合晚報](https://www.ptt.cc/bbs/TMU911/M.1190100191.A.192.html) 2007.09"
-->

### 律師20年內人多6倍 菜鳥慘

> 律師人數近10年來成長速度驚人。根據律師公會全國聯合會的統計，目前國內律師有9,922人，領照的約5,522人。資深法界人士表示，<mark>在2、30年前，律師的錄取人數，每年頂多2位數，最好的情況也只錄取5、60人</mark>。但自1991年起，律師錄取人數開始大幅躍進。
>
> 1994年的律師高考錄取率達15.22％，錄取了563人；1999年，錄取率也有13.88％，錄取564人，近年雖然錄取人數超過500人的情況已經不再，但錄取3、400人卻是常態，<mark>2005年、2006年，錄取人數分別是427和448人</mark>。律師錄取人數大幅成長後，直接造成律師業競爭激烈。

---

<!--
_footer: "[天下雜誌](https://www.cw.com.tw/article/5068064) 2015.06"
-->

### 律師，你可以不必流浪

> 根據律師公會全聯會提供資料，20年前，每年通過律師考試的人數僅約兩位數，如今已將近4位數，但是司法院統計，訴訟案量卻幾乎沒有增加。
>
> 全聯會認為，律師實習與就職困難，問題出在前端沒控管。
>
> 過去十年來大學紛紛改制，許多技術學院增設法律科系，目前全國已經有將近40個學校有法律相關系所，每年畢業生高達5,000人。
>
> 考選部更在2011年，改變律師高考錄取制度，第一試錄取三分之一，第二試再錄取三分之一，換算下來，總錄取率是到考人數的10%以上。過去4年，平均每年錄取超過900人，是10年前的將近3倍。
>
> 「為什麼我們很少聽到流浪醫師？因為醫學院有入學名額總量管制，但法律界卻沒有，」李家慶以醫學院的例子，建議法學院或可比照辦理。

---

<!--
_footer: "[全國律師聯合會](https://www.twba.org.tw/news/9a5e368d-62f9-47eb-aa93-f68fca57b109) 2025.11"
-->

### 律師錄取人數創新高，本會嚴正抗議考訓失衡並籲請推動修法

> 我國執業律師人數於2013年僅6,853人，截至2025年底已攀升至13,016人，短短12年間成長近倍。法務部早於2017年之研究報告即指出，我國合理執業律師人數約為1萬人；然<mark>自2011年律師考試改制放寬門檻以來，14年間累計錄取人數已逾1.3萬人</mark>，顯見政策與實務需求嚴重背離。
>
> 律師專業非一般商品而具有高度公共性，其服務品質與專業倫理難以透過純粹優勝劣敗市場競爭來確保，長期以追求錄取數量為導向、未同步檢視社會實務需求與市場容納量的錄取政策，無助於提升法律服務品質，反將導致惡性競爭，所帶來的負面影響不僅衝擊律師業，更將對整個司法品質造成影響，最終將損及社會大眾權益。...
>
> 專門職業及技術人員考試法立法精神，在於透過國家考試選拔具備執業能力之專業人才，而非單純追求錄取數字。尤有甚者，現行制度允許非法律科系畢業者，僅需修習20個法律學分即可報考。此舉不僅無視法律專業養成的嚴謹性，更使正規法學教育功能大幅弱化。

---

<!--
_footer: "[報導者](https://www.twreporter.org/a/massive-fraud-cases-overwhelm-judicial-system-lawyers) 2025.12"
-->

### 當法律守門人墮入共犯結構──不肖律師如何遊走灰色地帶，成詐團廉價工具

> 曾幾何時，律師捍衛人權、為民眾法律權益奔走、在法庭上抗衡國家權力的公益形象，已然蒙塵。近來不斷有律師因涉及替犯罪集團洩密被檢方起訴，他們<mark>以手機拍下卷證資料、筆錄，以及在押被告的供述內容，再回傳給詐團上游以牟利</mark>，甚至從個案如蛛網般不斷擴張，成立專門替詐騙集團服務的集團。
>
> 根據統計與檢方實務經驗，律師在「偵查中洩密」大量發生在2017年以後──該年恰好修正《刑事訴訟法》第33-1條，允許辯護人在被告羈押審查程序進行時得以檢閱卷宗及證物等偵查資料。這項本是為了保障偵查中辯護權的舉措，卻意外打開犯罪集團滲透司法制度的破口，加上整體律師生態發生變化、職業倫理與懲戒制度的不足，都使「<mark>詐團結合律師</mark>」的現象如星星之火，難以遏止。

---

<!--
_footer: "[月旦法學教室](https://www.law.nccu.edu.tw/zh_tw/Faculty/JournalPapers/%E5%BE%8B%E5%B8%AB%E6%88%91%E8%A6%81%E6%80%8E%E9%BA%BC%E4%BB%98%E4%BD%A0%E9%8C%A2-%E5%BE%8B%E5%B8%AB%E9%85%AC%E9%87%91%E7%9A%84%E5%80%AB%E7%90%86%E8%A6%8F%E7%AF%84-42004041) 2014.10"
-->

### 律師我要怎麼付你錢？律師酬金的倫理規範

> 我國法律實務上，律師酬金的主要收取方式有四種：
> 1. <mark>按項目或按件計酬</mark>：例如律師函或存證信函每件若干元、訴訟書狀每件若干元、出庭費每次若干元；
> 2. <mark>按時計酬</mark>：依工作時數計算，例如每小時若干元；
> 3. <mark>按審級計酬（包審制）</mark>：以一個審級的完成作為收費的單位，例如一審從起訴到訴訟終結為止，無論開庭幾次、書狀撰寫了幾份、與當事人會談幾次，在這個審級都是收取一筆固定費用；
> 4. <mark>後酬方式</mark>：依據訴訟結果的勝敗或勝訴金額來計算酬金，例如約定若勝訴則給付酬金若干元，否則僅給付一半，或是約定依照勝訴金額的一定比例來給付律師費用。

:warning: 家事、刑事案件或少年事件：原則上不得約定後酬

---

<!--
_footer: "[在野法潮](https://dissent.tba.org.tw/special/4784) 2025.06"
-->

### 法律服務的下一場革命  AI重塑事務所的專業價值

> AI在法律產業的應用正快速擴展，不僅成為律所提升效率的利器、廣泛應用於日常業務，甚至已進一步成為客戶所要求的作業條件。林香君律師分享，歐洲客戶曾委託英國律所處理大規模債務合約清理，並明確要求必須使用AI進行條款摘要。過去需仰賴多位律師投入數百工時的任務，現在AI幾分鐘即可完成初稿，再由資深律師快速確認，大幅縮短處理時間、提升整體效率，但這也挑戰律師傳統收費模式。
>
> 律所長期以「按時計費」為主，但當AI工具顯著壓縮工時後，現行計費方式便顯得不合時宜。林香君律師坦言，現在已有許多歐美律所正積極討論如何合理地將AI成本納入收費標準，例如透過訂閱費用攤提，或轉向「按價值計費（Charge by Value）」的模式，「<mark>律師不再只販售時間，而是提供具洞察力的結果與決策價值</mark>，這已經是歐美市場進行式，而台灣也將在不久的未來發生。」

---

<!--
_footer: "[Lawsnote](https://blog.lawsnote.com/2026/01/lawsnote-ai-legal-3/) 2026.01"
-->

### 從人工智慧的長處與短處看未來的律師產業變化

> 當我們談論AI對法律實務的衝擊時，最直觀的震撼往往來自它那<mark>永不疲倦的「數位勞工」</mark>。如果一個律師團隊需要耗費三天三夜，才能勉強翻完上萬頁的實地查核（Due Diligence）文件，現在的智慧系統只要幾分鐘就能精準鎖定風險。這種對非結構化資料的處理速度，簡直像是給律師裝上了一對能透視資訊迷霧的鷹眼，讓原本繁瑣的資訊勞動轉化為高價值的策略分析。...
>
> 這種技術不只能處理靜態的文字檢索，它更擅長從海量的判決書中，勾勒出法官的裁量傾向， 甚至能透過過去的資料精準預測對造律師在類似案件中的辯論慣性，讓訴訟上的攻防發生在法庭活動之前，猶如現代球賽的起賽點始於情蒐一般，AI 將在開戰前點燃訴訟硝煙，<mark>資訊的搜集和訴訟策略的制定將比以往任何時候都來得更重要</mark>。

---

<!--
_footer: "[Jason's數位行銷筆記](https://jasondiginote.com/ai-fomo/) 2026.02"
-->

### 追新會累，不追會慌，走出AI FOMO追與不追的兩難

FOMO（Fear Of Missing Out）

> AI FOMO表面看起來是工具焦慮，但仔細思考後應該改成以下這三種：
>
> 1. 能力焦慮：別人會了，我還不會，代表我落後人家一步？
> 2. 價值焦慮：同上題，如果我還不會，那我還有價值嗎？
> 3. 機會焦慮：如果我現在不進場，會不會下一波紅利就沒了？

---

<style scoped>
ul {
  list-style-type: none;
}
</style>

## 未來是？

![](https://mermaid.ink/svg/pako:eNpVUMtqxDAM_JWgsxOcbB6ur-2lhUKh0EPxxWy0jtmNHByb7Tbk3-smtKUCgUaa0QgtcHQ9goQ8zxUdHZ2skYqybNZ0xttWJjC465u-RJxldtKXGff2gNYMQWYV54q2BbtKkaLXOKHPXtwVPXuKvRmRAmv4_8HjqI0lHayjNAMGxtseZPARGYzoR_0NYdntFPzdoUAmvN8CitaknTS9Ozf-yL2LZgC5URjEqdcBH6w2Xo-_XY_Uo793kQLIshFi2wJygQ-QLS-atqrbu1pUdVWKrmFwAylEwUUneNvxsm1Trgw-N19eJA5PUYq6OdQNPzDA3gbnn_cfb69evwC7s3Si)

<!-- https://mermaid.ai/live/edit#pako:eNpVUMtqxDAM_JWgsxOcbB6ur-2lhUKh0EPxxWy0jtmNHByb7Tbk3-smtKUCgUaa0QgtcHQ9goQ8zxUdHZ2skYqybNZ0xttWJjC465u-RJxldtKXGff2gNYMQWYV54q2BbtKkaLXOKHPXtwVPXuKvRmRAmv4_8HjqI0lHayjNAMGxtseZPARGYzoR_0NYdntFPzdoUAmvN8CitaknTS9Ozf-yL2LZgC5URjEqdcBH6w2Xo-_XY_Uo793kQLIshFi2wJygQ-QLS-atqrbu1pUdVWKrmFwAylEwUUneNvxsm1Trgw-N19eJA5PUYq6OdQNPzDA3gbnn_cfb69evwC7s3Si -->

* 判斷力：懂，才有辦法用
* 想像力：想得到，才可能做得到

<!-- ```mermaid
---
config:
  sankey:
    showValues: false
    height: 200
---
sankey

Super Power,Judgment,50
Super Power,Imagination,50
``` -->

---

<style scoped>
ul {
  list-style-type: none;
}
</style>

<!--
_footer: "[Wikipedia](https://en.wikipedia.org/wiki/Letter_and_spirit_of_the_law) 2026.04"
-->

### 法律文字 :vs: 精神

> The <mark>letter of the law</mark> and the <mark>spirit of the law</mark> are two possible ways to regard rules, or laws. To obey the letter of the law is to follow the literal reading of the words of the law, whereas following the spirit of the law means enacting the intent behind the law. Although it is usual to follow both the letter and the spirit, the two are commonly referenced when they are in opposition.

* 誹謗：名譽值多少？
* 邏輯推理 :left_right_arrow: 價值選擇

---

<style scoped>
ul {
  list-style-type: none;
}
</style>

<!--
_footer: "[The Good Wife (S6 E18)](https://m.imdb.com/title/tt4529816/quotes/) 2015.04"
-->

### 客觀 :vs: 公平

* > :mountain:: Diane, can I ask you something? What do you think would happen if every case were adjudicated by someone with a family member or loved one who'd be affected by the decision?
* > :ocean:: Ultimately, perhaps, every case is.
* > :mountain:: But isn't the law supposed to be impersonal? In the sense that it should be the same for everyone? Y'know, otherwise we're in China, right? Everything's determined by who you know.
* > :ocean:: The law's supposed to be <mark>fair</mark>, not <mark>impersonal</mark>. In fact, I would argue that the law's always personal; it has to see the human side, too. Or else it's meaningless.

---

<!--
_class: blue
_paginate: false
-->

# Powered By 以上

Github [iunn-sh/legal-profession-sketch](https://github.com/iunn-sh/legal-profession-sketch) ![GitHub License](https://img.shields.io/github/license/iunn-sh/legal-profession-sketch?style=flat-square)

- Framework [marp-team/marp-cli](https://github.com/marp-team/marp-cli)
- Theme [sano-jin/marp-theme-aqua](https://github.com/sano-jin/marp-theme-aqua)
- Color [Ocean Blue Serenity](https://coolors.co/palette/03045e-023e8a-0077b6-0096c7-00b4d8-48cae4-90e0ef-ade8f4-caf0f8) & [Fresh Greens](https://coolors.co/palette/d8f3dc-b7e4c7-95d5b2-74c69d-52b788-40916c-2d6a4f-1b4332-081c15)
- Font [源石黑體 TW](https://font.emtech.cc/fonts/GenSekiGothicTW)
- Chart [chartjs/Chart.js](https://github.com/chartjs/Chart.js) & [amCharts](https://www.amcharts.com/)

