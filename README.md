<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Day 1</title><style>
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
margin: 0;
padding: 0;
}
@media only screen {
body {
margin: 2em auto;
max-width: 900px;
color: rgb(55, 53, 47);
}
}

body {
line-height: 1.5;
white-space: pre-wrap;
}

a,
a.visited {
color: inherit;
text-decoration: underline;
}

.pdf-relative-link-path {
font-size: 80%;
color: #444;
}

h1,
h2,
h3 {
letter-spacing: -0.01em;
line-height: 1.2;
font-weight: 600;
margin-bottom: 0;
}

.page-title {
font-size: 2.5rem;
font-weight: 700;
margin-top: 0;
margin-bottom: 0.75em;
}

h1 {
font-size: 1.875rem;
margin-top: 1.875rem;
}

h2 {
font-size: 1.5rem;
margin-top: 1.5rem;
}

h3 {
font-size: 1.25rem;
margin-top: 1.25rem;
}

.source {
border: 1px solid #ddd;
border-radius: 3px;
padding: 1.5em;
word-break: break-all;
}

.callout {
border-radius: 3px;
padding: 1rem;
}

figure {
margin: 1.25em 0;
page-break-inside: avoid;
}

figcaption {
opacity: 0.5;
font-size: 85%;
margin-top: 0.5em;
}

mark {
background-color: transparent;
}

.indented {
padding-left: 1.5em;
}

hr {
background: transparent;
display: block;
width: 100%;
height: 1px;
visibility: visible;
border: none;
border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
max-width: 100%;
}

@media only print {
img {
max-height: 100vh;
object-fit: contain;
}
}

@page {
margin: 1in;
}

.collection-content {
font-size: 0.875rem;
}

.column-list {
display: flex;
justify-content: space-between;
}

.column {
padding: 0 1em;
}

.column:first-child {
padding-left: 0;
}

.column:last-child {
padding-right: 0;
}

.table_of_contents-item {
display: block;
font-size: 0.875rem;
line-height: 1.3;
padding: 0.125rem;
}

.table_of_contents-indent-1 {
margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
margin-left: 3rem;
}

.table_of_contents-indent-3 {
margin-left: 4.5rem;
}

.table_of_contents-link {
text-decoration: none;
opacity: 0.7;
border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
border: 1px solid rgba(55, 53, 47, 0.09);
border-collapse: collapse;
}

table {
border-left: none;
border-right: none;
}

th,
td {
font-weight: normal;
padding: 0.25em 0.5em;
line-height: 1.5;
min-height: 1.5em;
text-align: left;
}

th {
color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
margin: 0;
margin-block-start: 0.6em;
margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
margin-block-start: 0.6em;
}

ul > li {
list-style: disc;
}

ul.to-do-list {
text-indent: -1.7em;
}

ul.to-do-list > li {
list-style: none;
}

.to-do-children-checked {
text-decoration: line-through;
opacity: 0.375;
}

ul.toggle > li {
list-style: none;
}

ul {
padding-inline-start: 1.7em;
}

ul > li {
padding-left: 0.1em;
}

ol {
padding-inline-start: 1.6em;
}

ol > li {
padding-left: 0.2em;
}

.mono ol {
padding-inline-start: 2em;
}

.mono ol > li {
text-indent: -0.4em;
}

.toggle {
padding-inline-start: 0em;
list-style-type: none;
}

/_ Indent toggle children _/
.toggle > li > details {
padding-left: 1.7em;
}

.toggle > li > details > summary {
margin-left: -1.1em;
}

.selected-value {
display: inline-block;
padding: 0 0.5em;
background: rgba(206, 205, 202, 0.5);
border-radius: 3px;
margin-right: 0.5em;
margin-top: 0.3em;
margin-bottom: 0.3em;
white-space: nowrap;
}

.collection-title {
display: inline-block;
margin-right: 1em;
}

time {
opacity: 0.5;
}

.icon {
display: inline-block;
max-width: 1.2em;
max-height: 1.2em;
text-decoration: none;
vertical-align: text-bottom;
margin-right: 0.5em;
}

img.icon {
border-radius: 3px;
}

.user-icon {
width: 1.5em;
height: 1.5em;
border-radius: 100%;
margin-right: 0.5rem;
}

.user-icon-inner {
font-size: 0.8em;
}

.text-icon {
border: 1px solid #000;
text-align: center;
}

.page-cover-image {
display: block;
object-fit: cover;
width: 100%;
height: 30vh;
}

.page-header-icon {
font-size: 3rem;
margin-bottom: 1rem;
}

.page-header-icon-with-cover {
margin-top: -0.72em;
margin-left: 0.07em;
}

.page-header-icon img {
border-radius: 3px;
}

.link-to-page {
margin: 1em 0;
padding: 0;
border: none;
font-weight: 500;
}

p > .user {
opacity: 0.5;
}

td > .user,
td > time {
white-space: nowrap;
}

input[type="checkbox"] {
transform: scale(1.5);
margin-right: 0.6em;
vertical-align: middle;
}

p {
margin-top: 0.5em;
margin-bottom: 0.5em;
}

.image {
border: none;
margin: 1.5em 0;
padding: 0;
border-radius: 0;
text-align: center;
}

.code,
code {
background: rgba(135, 131, 120, 0.15);
border-radius: 3px;
padding: 0.2em 0.4em;
border-radius: 3px;
font-size: 85%;
tab-size: 2;
}

code {
color: #eb5757;
}

.code {
padding: 1.5em 1em;
}

.code-wrap {
white-space: pre-wrap;
word-break: break-all;
}

.code > code {
background: none;
padding: 0;
font-size: 100%;
color: inherit;
}

blockquote {
font-size: 1.25em;
margin: 1em 0;
padding-left: 1em;
border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
text-decoration: none;
max-height: 8em;
padding: 0;
display: flex;
width: 100%;
align-items: stretch;
}

.bookmark-title {
font-size: 0.85em;
overflow: hidden;
text-overflow: ellipsis;
height: 1.75em;
white-space: nowrap;
}

.bookmark-text {
display: flex;
flex-direction: column;
}

.bookmark-info {
flex: 4 1 180px;
padding: 12px 14px 14px;
display: flex;
flex-direction: column;
justify-content: space-between;
}

.bookmark-image {
width: 33%;
flex: 1 1 180px;
display: block;
position: relative;
object-fit: cover;
border-radius: 1px;
}

.bookmark-description {
color: rgba(55, 53, 47, 0.6);
font-size: 0.75em;
overflow: hidden;
max-height: 4.5em;
word-break: break-word;
}

.bookmark-href {
font-size: 0.75em;
margin-top: 0.25em;
}

.sans { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, YuMincho, "Yu Mincho", "Hiragino Mincho ProN", "Hiragino Mincho Pro", "Songti TC", "Songti SC", "SimSun", "Nanum Myeongjo", NanumMyeongjo, Batang, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC', 'Noto Sans CJK KR'; }

.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC', 'Noto Sans Mono CJK KR'; }

.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, YuMincho, "Yu Mincho", "Hiragino Mincho ProN", "Hiragino Mincho Pro", "Songti TC", "Songti SC", "SimSun", "Nanum Myeongjo", NanumMyeongjo, Batang, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC', 'Noto Sans CJK KR'; }

.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC', 'Noto Sans Mono CJK KR'; }

.highlight-default {
}
.highlight-gray {
color: rgb(155,154,151);
}
.highlight-brown {
color: rgb(100,71,58);
}
.highlight-orange {
color: rgb(217,115,13);
}
.highlight-yellow {
color: rgb(223,171,1);
}
.highlight-teal {
color: rgb(15,123,108);
}
.highlight-blue {
color: rgb(11,110,153);
}
.highlight-purple {
color: rgb(105,64,165);
}
.highlight-pink {
color: rgb(173,26,114);
}
.highlight-red {
color: rgb(224,62,62);
}
.highlight-gray_background {
background: rgb(235,236,237);
}
.highlight-brown_background {
background: rgb(233,229,227);
}
.highlight-orange_background {
background: rgb(250,235,221);
}
.highlight-yellow_background {
background: rgb(251,243,219);
}
.highlight-teal_background {
background: rgb(221,237,234);
}
.highlight-blue_background {
background: rgb(221,235,241);
}
.highlight-purple_background {
background: rgb(234,228,242);
}
.highlight-pink_background {
background: rgb(244,223,235);
}
.highlight-red_background {
background: rgb(251,228,228);
}
.block-color-default {
color: inherit;
fill: inherit;
}
.block-color-gray {
color: rgba(55, 53, 47, 0.6);
fill: rgba(55, 53, 47, 0.6);
}
.block-color-brown {
color: rgb(100,71,58);
fill: rgb(100,71,58);
}
.block-color-orange {
color: rgb(217,115,13);
fill: rgb(217,115,13);
}
.block-color-yellow {
color: rgb(223,171,1);
fill: rgb(223,171,1);
}
.block-color-teal {
color: rgb(15,123,108);
fill: rgb(15,123,108);
}
.block-color-blue {
color: rgb(11,110,153);
fill: rgb(11,110,153);
}
.block-color-purple {
color: rgb(105,64,165);
fill: rgb(105,64,165);
}
.block-color-pink {
color: rgb(173,26,114);
fill: rgb(173,26,114);
}
.block-color-red {
color: rgb(224,62,62);
fill: rgb(224,62,62);
}
.block-color-gray_background {
background: rgb(235,236,237);
}
.block-color-brown_background {
background: rgb(233,229,227);
}
.block-color-orange_background {
background: rgb(250,235,221);
}
.block-color-yellow_background {
background: rgb(251,243,219);
}
.block-color-teal_background {
background: rgb(221,237,234);
}
.block-color-blue_background {
background: rgb(221,235,241);
}
.block-color-purple_background {
background: rgb(234,228,242);
}
.block-color-pink_background {
background: rgb(244,223,235);
}
.block-color-red_background {
background: rgb(251,228,228);
}
.select-value-color-default { background-color: rgba(206,205,202,0.5); }
.select-value-color-gray { background-color: rgba(155,154,151, 0.4); }
.select-value-color-brown { background-color: rgba(140,46,0,0.2); }
.select-value-color-orange { background-color: rgba(245,93,0,0.2); }
.select-value-color-yellow { background-color: rgba(233,168,0,0.2); }
.select-value-color-green { background-color: rgba(0,135,107,0.2); }
.select-value-color-blue { background-color: rgba(0,120,223,0.2); }
.select-value-color-purple { background-color: rgba(103,36,222,0.2); }
.select-value-color-pink { background-color: rgba(221,0,129,0.2); }
.select-value-color-red { background-color: rgba(255,0,26,0.2); }

.checkbox {
display: inline-flex;
vertical-align: text-bottom;
width: 16;
height: 16;
background-size: 16px;
margin-left: 2px;
margin-right: 5px;
}

.checkbox-on {
background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
</style></head><body><article id="e03d11c1-e2e9-4dbb-a65c-a4bd8741c32a" class="page sans"><header><h1 class="page-title">Day 1</h1></header><div class="page-body"><h2 id="54cfc1b0-71d3-4e2a-a213-b8013cfc7ccd" class=""><strong>Modül-1: Data Collection</strong></h2><p id="ebdac120-c2d4-4b99-a735-29872ef70d15" class=""><strong>İçerik: </strong>API&#x27;lar, loglama, sensory data, web scraping. </p><p id="a32e414b-d093-4b63-b657-367b34bc3ee4" class=""><strong>Anahtar sözcükler: </strong>JSON, XML, HTTP, HTML, DOM, grep, RegExp. </p><p id="c57d54ed-25c8-4ece-be73-1ca85d197415" class=""><strong>Araçlar: </strong>Postman, log4j, python-logging, BeautifulSoup, Jsoup, Selenium</p><h1 id="0b099f06-bad5-4891-a7d8-f3ec03bccb02" class="">Data Toplama</h1><p id="dd3387a4-afb0-4e0f-a1b9-44f2274c870a" class="">Information retreival, webscraping, alınan API dataları bunlara örnektir.</p><hr id="0593ad02-e28e-4506-ad4b-336280292087"/><h2 id="81771825-e159-40f8-a8c0-35c06758eee6" class=""><strong>API</strong> </h2><p id="9063726c-c1ee-4ccb-9358-471f5f8ed0cf" class="">İki sistemin arasında nasıl konusacağını belirleyen bir yapıdır. Belirli spesifik tipte akış ve veri sunar. Belirli bir rate içerisinde olmaktadır. Belirli sorgulara karşı belirli bir data parçası geçmektedir, tüm sistemin veri akışını sağlamak için değildir.</p><figure class="block-color-blue_background callout" style="white-space:pre-wrap;display:flex" id="cb583814-f15e-430e-a304-1109671edbbd"><div style="font-size:1.5em"><span class="icon">💡</span></div><div style="width:100%">Farklı formatlarda dönüşü olabilir. <strong>.xml</strong> veya <strong>json</strong> olabilir. JSON oldukça popüler, şu an genel akım json üzerinden çalışıyor.</div></figure><p id="65438944-0574-4531-a770-9a728b100eee" class="">Sensörler ufak bilgisayarlar denilebilir, genellikle amaca yönelik sadece görevini yapan pil ömrü yüksek olan mini cihazlardır. Üzerindeki datayı merkeze alınarak kullanılabilir. <em>Aslında </em><strong><em>edgedeki</em></strong><em> cihazlardan bahsediliyor.</em></p><hr id="509d110d-3af0-4901-8c3b-823d73d0574b"/><h2 id="28505a11-1ad4-48ea-9e4f-bbbe70c87b60" class=""><strong>Web Scraping</strong></h2><p id="e27fc2ae-62dc-4971-bb9a-7e17d1fd4f97" class="">Görece API&#x27;ye göre verinin elde edilmesi daha zor. Veri genellikle dağınık biçimde web&#x27;de bulunur, veri toplama prosesi kullanıcının bu rotaları tanımlayarak gerçekleştirmesiyle sağlanır. Dezavantajı ise belirli bir protokolun olmaması, <strong><em>challenging but fun!</em></strong></p><figure class="block-color-yellow_background callout" style="white-space:pre-wrap;display:flex" id="fc4fb940-6bd1-49ad-8d05-a77f6105c578"><div style="font-size:1.5em"><span class="icon">💡</span></div><div style="width:100%">Değişikliklerde call denilen bir sistem kullanılabilir. İki taraf için yüklü bir sistem olduğundan dolayı istenilen bir yöntem değildir. Bir websitesi için yazılan scraping scriptleri her gün değişmez bu yüzden büyük bir problem yaratmayacaktır. Subscribe yönteminde webhook gibi yöntemler kullanılabilir fakat karşı tarafın da sizi tanıyor olması gerek.</div></figure><hr id="d0e20ceb-49c9-4cc2-8d36-a8c8add05ddf"/><h2 id="e132972c-260f-4d91-8041-e7022ebbb9c7" class="">Loglama</h2><p id="82a86268-200a-4c73-9d05-a009d0026ddf" class="">Genellikle problemler belirli bir zaman diliminden itibaren veya geçmişten gelir. Anlık sorunları ve sistemin ne yaptığını en ince detayın kadar görmek için <strong>loglama</strong> kullanılır.</p><figure class="block-color-purple_background callout" style="white-space:pre-wrap;display:flex" id="0da9e4b1-18ba-4ecd-8abf-935eb2a5f9e0"><div style="font-size:1.5em"><span class="icon">🔥</span></div><div style="width:100%"><strong>Pro Tip:</strong> Her satırın loglanmasının anlamı yoktur. Oldukça dikkat dağıtıcı ve kullanışsız olmaya başlamaktadır. Bunun için loglamanın seviyeleri vardır.</div></figure><h3 id="3c2af95e-b08c-4351-b98f-951b2ab7c507" class="">Loglamanın seviyeleri</h3><p id="ffcd3ed7-a2fc-451b-b580-a99e1d5223a9" class="">Low level, critical, warning, info gibi seviyeler vardır.</p><ul id="da652a23-a3bf-42cd-986d-505523773702" class="bulleted-list"><li><strong>Debug: </strong>Sorunların teşhisi için debugging gibi düşünebiliriz. Ayrıntılı bilgilere ihtiyacımız vardır.</li></ul><ul id="a2cc9456-b558-4fbf-9cfa-f6263097d4e2" class="bulleted-list"><li><strong>Info: </strong>Beklenen çıktılarımızdır.</li></ul><ul id="5b8bfcb6-e7ac-4b0c-affa-d018e785550e" class="bulleted-list"><li><strong>Warning: </strong>Yazılım hala çalışıyordur ama uyarı çanları çalmaktadır.</li></ul><ul id="2dba6dc6-0bae-4095-863f-9fe16dea5e8b" class="bulleted-list"><li><strong>Error:</strong> Yazılım ciddi bir sorunla karşılaştı ve görevini yerine getiremedi.</li></ul><ul id="995d36fe-7e97-4715-89ad-175cacbd935d" class="bulleted-list"><li><strong>Critical</strong>: Programın işlevini yerine getiremeyecek bir sorunla karşılaşmasıdır.</li></ul><figure class="block-color-purple_background callout" style="white-space:pre-wrap;display:flex" id="343d472c-71e4-4ee9-b7f9-bda4b93d6003"><div style="font-size:1.5em"><span class="icon">🔥</span></div><div style="width:100%"><strong>Pro Tip:</strong> <em>grep</em> komutuyla dosyaların içerisindeki belirli kelimeyi arar.<em> (e.g. 2 şubat tarihinde bir problem oldu ve onun bulunması için kullanılabilir.)</em></div></figure><h3 id="fd8a6d11-38b5-4eb8-944a-84eaee425711" class="">Loglama yaparken:</h3><ul id="658b533a-25ef-477b-8095-5faa6dcee3d0" class="bulleted-list"><li><strong>Timestamp:</strong> Tarih, zaman damgası bulunması ve ne zaman olduğuna dair bilgi vermesi açısından önemlidir.</li></ul><ul id="31993185-3854-4b8a-8376-3c93de97b9d2" class="bulleted-list"><li><strong>Logging Level:</strong> Hatanın derecesi, nedeni veya olayın ne olduğuna dair seviyenin belirtilmesi gerekmektedir.</li></ul><ul id="9ec69e3f-8830-4d4e-b045-d3d46919e63b" class="bulleted-list"><li><strong>API Bilgisi:</strong> Sensor ID, hangi fonksiyon, genel bilgiler</li></ul><ul id="4673de08-2fc2-4290-aec6-3fe84722bb59" class="bulleted-list"><li><strong>Logun içeriği: </strong>value, logun içeriği json, plain text, xml olabilir.</li></ul><p id="823ad084-6cbb-4343-836d-137b14750cb8" class="">Logların tek büyük bir dosyada açmak giderek büyüyen dosyadan dolayı mantıklı değildir. Databasede tablo olarak saklanabilir böyle bir durumda select süresi uzamaktadır. Sistemi optimize edebilmek için aktif olanlar veya olmayanlar yahut arşivlenmiş gibi farklı parçalara bölmek zaman açısından yararlı olacaktır. </p><p id="cfcc0b22-7de8-4b2c-b17a-621a9cd37df2" class="">Güncel datayı optimize tutmak için düşünülmesi gerekmektedir. Bunun için <strong>Hadoop</strong> gibi özelleşmiş sistemler bulunmaktadır. Temelde depolanan ve güncel olarak kullanılan iki parçaya bölmek mantıklı olacaktır. </p><p id="f08d9c68-c5eb-46a7-b7d3-cd452497fc65" class="">

</p></div></article></body></html>
