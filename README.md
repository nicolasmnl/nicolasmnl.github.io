<!DOCTYPE html>
<html>

<head>
  <meta charset="utf8" />
  <title>Nutbox</title>
  <!-- needed for adaptive design -->
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      padding: 0;
      margin: 0;
    }
  </style>
  <script src="https://cdn.redoc.ly/redoc/v2.0.0/bundles/redoc.standalone.js"></script><style data-styled="true" data-styled-version="5.3.3">.fcjMZs{width:calc(100% - 40%);padding:0 40px;}/*!sc*/
@media print,screen and (max-width:75rem){.fcjMZs{width:100%;padding:40px 40px;}}/*!sc*/
.frutYI{width:calc(100% - 40%);padding:0 40px;}/*!sc*/
@media print,screen and (max-width:75rem){.frutYI{width:100%;padding:0px 40px;}}/*!sc*/
data-styled.g4[id="sc-hKwDye"]{content:"fcjMZs,frutYI,"}/*!sc*/
.kKqedw{padding:40px 0;}/*!sc*/
.kKqedw:last-child{min-height:calc(100vh + 1px);}/*!sc*/
.sc-eCImPb > .sc-eCImPb:last-child{min-height:initial;}/*!sc*/
@media print,screen and (max-width:75rem){.kKqedw{padding:0;}}/*!sc*/
.hexvPn{padding:40px 0;position:relative;}/*!sc*/
.hexvPn:last-child{min-height:calc(100vh + 1px);}/*!sc*/
.sc-eCImPb > .sc-eCImPb:last-child{min-height:initial;}/*!sc*/
@media print,screen and (max-width:75rem){.hexvPn{padding:0;}}/*!sc*/
.hexvPn:not(:last-of-type):after{position:absolute;bottom:0;width:100%;display:block;content:'';border-bottom:1px solid rgba(0,0,0,0.2);}/*!sc*/
data-styled.g5[id="sc-eCImPb"]{content:"kKqedw,hexvPn,"}/*!sc*/
.vSqXI{width:40%;color:#ffffff;background-color:#263238;padding:0 40px;}/*!sc*/
@media print,screen and (max-width:75rem){.vSqXI{width:100%;padding:40px 40px;}}/*!sc*/
data-styled.g6[id="sc-jRQBWg"]{content:"vSqXI,"}/*!sc*/
.dKDnzb{background-color:#263238;}/*!sc*/
data-styled.g7[id="sc-gKclnd"]{content:"dKDnzb,"}/*!sc*/
.jTXZbd{display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;width:100%;padding:0;}/*!sc*/
@media print,screen and (max-width:75rem){.jTXZbd{-webkit-flex-direction:column;-ms-flex-direction:column;flex-direction:column;}}/*!sc*/
data-styled.g8[id="sc-iCfMLu"]{content:"jTXZbd,"}/*!sc*/
.kwcwWd{font-family:Montserrat,sans-serif;font-weight:400;font-size:1.85714em;line-height:1.6em;color:#333333;}/*!sc*/
data-styled.g9[id="sc-furwcr"]{content:"kwcwWd,"}/*!sc*/
.QwiBS{font-family:Montserrat,sans-serif;font-weight:400;font-size:1.57143em;line-height:1.6em;color:#333333;margin:0 0 20px;}/*!sc*/
data-styled.g10[id="sc-pVTFL"]{content:"QwiBS,"}/*!sc*/
.hwMGJl{color:#ffffff;}/*!sc*/
data-styled.g12[id="sc-kDTinF"]{content:"hwMGJl,"}/*!sc*/
.kyZwVG{border-bottom:1px solid rgba(38,50,56,0.3);margin:1em 0 1em 0;color:rgba(38,50,56,0.5);font-weight:normal;text-transform:uppercase;font-size:0.929em;line-height:20px;}/*!sc*/
data-styled.g13[id="sc-iqseJM"]{content:"kyZwVG,"}/*!sc*/
.bNUQy{cursor:pointer;margin-left:-20px;padding:0;line-height:1;width:20px;display:inline-block;outline:0;}/*!sc*/
.bNUQy:before{content:'';width:15px;height:15px;background-size:contain;background-image:url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeD0iMCIgeT0iMCIgd2lkdGg9IjUxMiIgaGVpZ2h0PSI1MTIiIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiBlbmFibGUtYmFja2dyb3VuZD0ibmV3IDAgMCA1MTIgNTEyIiB4bWw6c3BhY2U9InByZXNlcnZlIj48cGF0aCBmaWxsPSIjMDEwMTAxIiBkPSJNNDU5LjcgMjMzLjRsLTkwLjUgOTAuNWMtNTAgNTAtMTMxIDUwLTE4MSAwIC03LjktNy44LTE0LTE2LjctMTkuNC0yNS44bDQyLjEtNDIuMWMyLTIgNC41LTMuMiA2LjgtNC41IDIuOSA5LjkgOCAxOS4zIDE1LjggMjcuMiAyNSAyNSA2NS42IDI0LjkgOTAuNSAwbDkwLjUtOTAuNWMyNS0yNSAyNS02NS42IDAtOTAuNSAtMjQuOS0yNS02NS41LTI1LTkwLjUgMGwtMzIuMiAzMi4yYy0yNi4xLTEwLjItNTQuMi0xMi45LTgxLjYtOC45bDY4LjYtNjguNmM1MC01MCAxMzEtNTAgMTgxIDBDNTA5LjYgMTAyLjMgNTA5LjYgMTgzLjQgNDU5LjcgMjMzLjR6TTIyMC4zIDM4Mi4ybC0zMi4yIDMyLjJjLTI1IDI0LjktNjUuNiAyNC45LTkwLjUgMCAtMjUtMjUtMjUtNjUuNiAwLTkwLjVsOTAuNS05MC41YzI1LTI1IDY1LjUtMjUgOTAuNSAwIDcuOCA3LjggMTIuOSAxNy4yIDE1LjggMjcuMSAyLjQtMS40IDQuOC0yLjUgNi44LTQuNWw0Mi4xLTQyYy01LjQtOS4yLTExLjYtMTgtMTkuNC0yNS44IC01MC01MC0xMzEtNTAtMTgxIDBsLTkwLjUgOTAuNWMtNTAgNTAtNTAgMTMxIDAgMTgxIDUwIDUwIDEzMSA1MCAxODEgMGw2OC42LTY4LjZDMjc0LjYgMzk1LjEgMjQ2LjQgMzkyLjMgMjIwLjMgMzgyLjJ6Ii8+PC9zdmc+Cg==');opacity:0.5;visibility:hidden;display:inline-block;vertical-align:middle;}/*!sc*/
h1:hover > .sc-crHmcD::before,h2:hover > .bNUQy::before,.bNUQy:hover::before{visibility:visible;}/*!sc*/
data-styled.g14[id="sc-crHmcD"]{content:"bNUQy,"}/*!sc*/
.jLPfXH{height:18px;width:18px;min-width:18px;vertical-align:middle;float:right;-webkit-transition:-webkit-transform 0.2s ease-out;-webkit-transition:transform 0.2s ease-out;transition:transform 0.2s ease-out;-webkit-transform:rotateZ(-90deg);-ms-transform:rotateZ(-90deg);transform:rotateZ(-90deg);}/*!sc*/
.laPRNF{height:20px;width:20px;min-width:20px;vertical-align:middle;float:right;-webkit-transition:-webkit-transform 0.2s ease-out;-webkit-transition:transform 0.2s ease-out;transition:transform 0.2s ease-out;-webkit-transform:rotateZ(0);-ms-transform:rotateZ(0);transform:rotateZ(0);}/*!sc*/
.laPRNF polygon{fill:white;}/*!sc*/
.bPEzCN{height:1.5em;width:1.5em;min-width:1.5em;vertical-align:middle;float:left;-webkit-transition:-webkit-transform 0.2s ease-out;-webkit-transition:transform 0.2s ease-out;transition:transform 0.2s ease-out;-webkit-transform:rotateZ(-90deg);-ms-transform:rotateZ(-90deg);transform:rotateZ(-90deg);}/*!sc*/
.bPEzCN polygon{fill:#1d8127;}/*!sc*/
.FBjwd{height:1.5em;width:1.5em;min-width:1.5em;vertical-align:middle;float:left;-webkit-transition:-webkit-transform 0.2s ease-out;-webkit-transition:transform 0.2s ease-out;transition:transform 0.2s ease-out;-webkit-transform:rotateZ(-90deg);-ms-transform:rotateZ(-90deg);transform:rotateZ(-90deg);}/*!sc*/
.FBjwd polygon{fill:#d41f1c;}/*!sc*/
data-styled.g15[id="sc-egiyK"]{content:"jLPfXH,laPRNF,bPEzCN,FBjwd,"}/*!sc*/
.kCCtqV{border-left:1px solid #7c7cbb;box-sizing:border-box;position:relative;padding:10px 10px 10px 0;}/*!sc*/
@media screen and (max-width:50rem){.kCCtqV{display:block;overflow:hidden;}}/*!sc*/
tr:first-of-type > .sc-hBUSln,tr.last > .kCCtqV{border-left-width:0;background-position:top left;background-repeat:no-repeat;background-size:1px 100%;}/*!sc*/
tr:first-of-type > .sc-hBUSln{background-image:linear-gradient( to bottom, transparent 0%, transparent 22px, #7c7cbb 22px, #7c7cbb 100% );}/*!sc*/
tr.last > .sc-hBUSln{background-image:linear-gradient( to bottom, #7c7cbb 0%, #7c7cbb 22px, transparent 22px, transparent 100% );}/*!sc*/
tr.last + tr > .sc-hBUSln{border-left-color:transparent;}/*!sc*/
tr.last:first-child > .sc-hBUSln{background:none;border-left-color:transparent;}/*!sc*/
data-styled.g18[id="sc-hBUSln"]{content:"kCCtqV,"}/*!sc*/
.fwnkRw{vertical-align:top;line-height:20px;white-space:nowrap;font-size:13px;font-family:Courier,monospace;}/*!sc*/
.fwnkRw.deprecated{-webkit-text-decoration:line-through;text-decoration:line-through;color:#707070;}/*!sc*/
data-styled.g20[id="sc-fFeiMQ"]{content:"fwnkRw,"}/*!sc*/
.fOwWgB{border-bottom:1px solid #9fb4be;padding:10px 0;width:75%;box-sizing:border-box;}/*!sc*/
tr.expanded .sc-bkkeKt{border-bottom:none;}/*!sc*/
@media screen and (max-width:50rem){.fOwWgB{padding:0 20px;border-bottom:none;border-left:1px solid #7c7cbb;}tr.last > .sc-bkkeKt{border-left:none;}}/*!sc*/
data-styled.g21[id="sc-bkkeKt"]{content:"fOwWgB,"}/*!sc*/
.fMdASL{color:#7c7cbb;font-family:Courier,monospace;margin-right:10px;}/*!sc*/
.fMdASL::before{content:'';display:inline-block;vertical-align:middle;width:10px;height:1px;background:#7c7cbb;}/*!sc*/
.fMdASL::after{content:'';display:inline-block;vertical-align:middle;width:1px;background:#7c7cbb;height:7px;}/*!sc*/
data-styled.g22[id="sc-ieecCq"]{content:"fMdASL,"}/*!sc*/
.wbnF{border-collapse:separate;border-radius:3px;font-size:14px;border-spacing:0;width:100%;}/*!sc*/
.wbnF > tr{vertical-align:middle;}/*!sc*/
@media screen and (max-width:50rem){.wbnF{display:block;}.wbnF > tr,.wbnF > tbody > tr{display:block;}}/*!sc*/
@media screen and (max-width:50rem) and (-ms-high-contrast:none){.wbnF td{float:left;width:100%;}}/*!sc*/
.wbnF .sc-dJjYzT,.wbnF .sc-dJjYzT .sc-dJjYzT .sc-dJjYzT,.wbnF .sc-dJjYzT .sc-dJjYzT .sc-dJjYzT .sc-dJjYzT .sc-dJjYzT{margin:1em;margin-right:0;background:#fafafa;}/*!sc*/
.wbnF .sc-dJjYzT .sc-dJjYzT,.wbnF .sc-dJjYzT .sc-dJjYzT .sc-dJjYzT .sc-dJjYzT,.wbnF .sc-dJjYzT .sc-dJjYzT .sc-dJjYzT .sc-dJjYzT .sc-dJjYzT .sc-dJjYzT{background:#ffffff;}/*!sc*/
data-styled.g24[id="sc-hGPBjI"]{content:"wbnF,"}/*!sc*/
.eCLDJY > ul{list-style:none;padding:0;margin:0;margin:0 -5px;}/*!sc*/
.eCLDJY > ul > li{padding:5px 10px;display:inline-block;background-color:#11171a;border-bottom:1px solid rgba(0,0,0,0.5);cursor:pointer;text-align:center;outline:none;color:#ccc;margin:0 5px 5px 5px;border:1px solid #07090b;border-radius:5px;min-width:60px;font-size:0.9em;font-weight:bold;}/*!sc*/
.eCLDJY > ul > li.react-tabs__tab--selected{color:#333333;background:#ffffff;}/*!sc*/
.eCLDJY > ul > li.react-tabs__tab--selected:focus{outline:auto;}/*!sc*/
.eCLDJY > ul > li:only-child{-webkit-flex:none;-ms-flex:none;flex:none;min-width:100px;}/*!sc*/
.eCLDJY > ul > li.tab-success{color:#1d8127;}/*!sc*/
.eCLDJY > ul > li.tab-redirect{color:#ffa500;}/*!sc*/
.eCLDJY > ul > li.tab-info{color:#87ceeb;}/*!sc*/
.eCLDJY > ul > li.tab-error{color:#d41f1c;}/*!sc*/
.eCLDJY > .react-tabs__tab-panel{background:#11171a;}/*!sc*/
.eCLDJY > .react-tabs__tab-panel > div,.eCLDJY > .react-tabs__tab-panel > pre{padding:20px;margin:0;}/*!sc*/
.eCLDJY > .react-tabs__tab-panel > div > pre{padding:0;}/*!sc*/
data-styled.g30[id="sc-cxpSdN"]{content:"eCLDJY,"}/*!sc*/
.hGZPxu code[class*='language-'],.hGZPxu pre[class*='language-']{text-shadow:0 -0.1em 0.2em black;text-align:left;white-space:pre;word-spacing:normal;word-break:normal;word-wrap:normal;line-height:1.5;-moz-tab-size:4;-o-tab-size:4;tab-size:4;-webkit-hyphens:none;-moz-hyphens:none;-ms-hyphens:none;-webkit-hyphens:none;-moz-hyphens:none;-ms-hyphens:none;hyphens:none;}/*!sc*/
@media print{.hGZPxu code[class*='language-'],.hGZPxu pre[class*='language-']{text-shadow:none;}}/*!sc*/
.hGZPxu pre[class*='language-']{padding:1em;margin:0.5em 0;overflow:auto;}/*!sc*/
.hGZPxu .token.comment,.hGZPxu .token.prolog,.hGZPxu .token.doctype,.hGZPxu .token.cdata{color:hsl(30,20%,50%);}/*!sc*/
.hGZPxu .token.punctuation{opacity:0.7;}/*!sc*/
.hGZPxu .namespace{opacity:0.7;}/*!sc*/
.hGZPxu .token.property,.hGZPxu .token.tag,.hGZPxu .token.number,.hGZPxu .token.constant,.hGZPxu .token.symbol{color:#4a8bb3;}/*!sc*/
.hGZPxu .token.boolean{color:#e64441;}/*!sc*/
.hGZPxu .token.selector,.hGZPxu .token.attr-name,.hGZPxu .token.string,.hGZPxu .token.char,.hGZPxu .token.builtin,.hGZPxu .token.inserted{color:#a0fbaa;}/*!sc*/
.hGZPxu .token.selector + a,.hGZPxu .token.attr-name + a,.hGZPxu .token.string + a,.hGZPxu .token.char + a,.hGZPxu .token.builtin + a,.hGZPxu .token.inserted + a,.hGZPxu .token.selector + a:visited,.hGZPxu .token.attr-name + a:visited,.hGZPxu .token.string + a:visited,.hGZPxu .token.char + a:visited,.hGZPxu .token.builtin + a:visited,.hGZPxu .token.inserted + a:visited{color:#4ed2ba;-webkit-text-decoration:underline;text-decoration:underline;}/*!sc*/
.hGZPxu .token.property.string{color:white;}/*!sc*/
.hGZPxu .token.operator,.hGZPxu .token.entity,.hGZPxu .token.url,.hGZPxu .token.variable{color:hsl(40,90%,60%);}/*!sc*/
.hGZPxu .token.atrule,.hGZPxu .token.attr-value,.hGZPxu .token.keyword{color:hsl(350,40%,70%);}/*!sc*/
.hGZPxu .token.regex,.hGZPxu .token.important{color:#e90;}/*!sc*/
.hGZPxu .token.important,.hGZPxu .token.bold{font-weight:bold;}/*!sc*/
.hGZPxu .token.italic{font-style:italic;}/*!sc*/
.hGZPxu .token.entity{cursor:help;}/*!sc*/
.hGZPxu .token.deleted{color:red;}/*!sc*/
data-styled.g32[id="sc-iJKOTD"]{content:"hGZPxu,"}/*!sc*/
.gjxyHD{opacity:0.7;-webkit-transition:opacity 0.3s ease;transition:opacity 0.3s ease;text-align:right;}/*!sc*/
.gjxyHD:focus-within{opacity:1;}/*!sc*/
.gjxyHD > button{background-color:transparent;border:0;color:inherit;padding:2px 10px;font-family:Roboto,sans-serif;font-size:14px;line-height:1.5em;cursor:pointer;outline:0;}/*!sc*/
.gjxyHD > button:hover,.gjxyHD > button:focus{background:rgba(255,255,255,0.1);}/*!sc*/
data-styled.g33[id="sc-giYglK"]{content:"gjxyHD,"}/*!sc*/
.flfPA:hover .sc-giYglK{opacity:1;}/*!sc*/
data-styled.g34[id="sc-ezbkAF"]{content:"flfPA,"}/*!sc*/
.kQTUkh code[class*='language-'],.kQTUkh pre[class*='language-']{text-shadow:0 -0.1em 0.2em black;text-align:left;white-space:pre;word-spacing:normal;word-break:normal;word-wrap:normal;line-height:1.5;-moz-tab-size:4;-o-tab-size:4;tab-size:4;-webkit-hyphens:none;-moz-hyphens:none;-ms-hyphens:none;-webkit-hyphens:none;-moz-hyphens:none;-ms-hyphens:none;hyphens:none;}/*!sc*/
@media print{.kQTUkh code[class*='language-'],.kQTUkh pre[class*='language-']{text-shadow:none;}}/*!sc*/
.kQTUkh pre[class*='language-']{padding:1em;margin:0.5em 0;overflow:auto;}/*!sc*/
.kQTUkh .token.comment,.kQTUkh .token.prolog,.kQTUkh .token.doctype,.kQTUkh .token.cdata{color:hsl(30,20%,50%);}/*!sc*/
.kQTUkh .token.punctuation{opacity:0.7;}/*!sc*/
.kQTUkh .namespace{opacity:0.7;}/*!sc*/
.kQTUkh .token.property,.kQTUkh .token.tag,.kQTUkh .token.number,.kQTUkh .token.constant,.kQTUkh .token.symbol{color:#4a8bb3;}/*!sc*/
.kQTUkh .token.boolean{color:#e64441;}/*!sc*/
.kQTUkh .token.selector,.kQTUkh .token.attr-name,.kQTUkh .token.string,.kQTUkh .token.char,.kQTUkh .token.builtin,.kQTUkh .token.inserted{color:#a0fbaa;}/*!sc*/
.kQTUkh .token.selector + a,.kQTUkh .token.attr-name + a,.kQTUkh .token.string + a,.kQTUkh .token.char + a,.kQTUkh .token.builtin + a,.kQTUkh .token.inserted + a,.kQTUkh .token.selector + a:visited,.kQTUkh .token.attr-name + a:visited,.kQTUkh .token.string + a:visited,.kQTUkh .token.char + a:visited,.kQTUkh .token.builtin + a:visited,.kQTUkh .token.inserted + a:visited{color:#4ed2ba;-webkit-text-decoration:underline;text-decoration:underline;}/*!sc*/
.kQTUkh .token.property.string{color:white;}/*!sc*/
.kQTUkh .token.operator,.kQTUkh .token.entity,.kQTUkh .token.url,.kQTUkh .token.variable{color:hsl(40,90%,60%);}/*!sc*/
.kQTUkh .token.atrule,.kQTUkh .token.attr-value,.kQTUkh .token.keyword{color:hsl(350,40%,70%);}/*!sc*/
.kQTUkh .token.regex,.kQTUkh .token.important{color:#e90;}/*!sc*/
.kQTUkh .token.important,.kQTUkh .token.bold{font-weight:bold;}/*!sc*/
.kQTUkh .token.italic{font-style:italic;}/*!sc*/
.kQTUkh .token.entity{cursor:help;}/*!sc*/
.kQTUkh .token.deleted{color:red;}/*!sc*/
data-styled.g35[id="sc-bYoBSM"]{content:"kQTUkh,"}/*!sc*/
.fHMTIq{font-family:Courier,monospace;font-size:13px;overflow-x:auto;margin:0;white-space:pre;}/*!sc*/
data-styled.g36[id="sc-kLwhqv"]{content:"fHMTIq,"}/*!sc*/
.eqZXtE{position:relative;}/*!sc*/
data-styled.g38[id="sc-ikJyIC"]{content:"eqZXtE,"}/*!sc*/
.hgRRjA{margin-left:10px;text-transform:none;font-size:0.929em;color:black;}/*!sc*/
data-styled.g42[id="sc-cCcXHH"]{content:"hgRRjA,"}/*!sc*/
.fYaHea{font-family:Roboto,sans-serif;font-weight:400;line-height:1.5em;}/*!sc*/
.fYaHea p:last-child{margin-bottom:0;}/*!sc*/
.fYaHea h1{font-family:Montserrat,sans-serif;font-weight:400;font-size:1.85714em;line-height:1.6em;color:#32329f;margin-top:0;}/*!sc*/
.fYaHea h2{font-family:Montserrat,sans-serif;font-weight:400;font-size:1.57143em;line-height:1.6em;color:#333333;}/*!sc*/
.fYaHea code{color:#e53935;background-color:rgba(38,50,56,0.05);font-family:Courier,monospace;border-radius:2px;border:1px solid rgba(38,50,56,0.1);padding:0 5px;font-size:13px;font-weight:400;word-break:break-word;}/*!sc*/
.fYaHea pre{font-family:Courier,monospace;white-space:pre;background-color:#11171a;color:white;padding:20px;overflow-x:auto;line-height:normal;border-radius:0px;border:1px solid rgba(38,50,56,0.1);}/*!sc*/
.fYaHea pre code{background-color:transparent;color:white;padding:0;}/*!sc*/
.fYaHea pre code:before,.fYaHea pre code:after{content:none;}/*!sc*/
.fYaHea blockquote{margin:0;margin-bottom:1em;padding:0 15px;color:#777;border-left:4px solid #ddd;}/*!sc*/
.fYaHea img{max-width:100%;box-sizing:content-box;}/*!sc*/
.fYaHea ul,.fYaHea ol{padding-left:2em;margin:0;margin-bottom:1em;}/*!sc*/
.fYaHea ul ul,.fYaHea ol ul,.fYaHea ul ol,.fYaHea ol ol{margin-bottom:0;margin-top:0;}/*!sc*/
.fYaHea table{display:block;width:100%;overflow:auto;word-break:normal;word-break:keep-all;border-collapse:collapse;border-spacing:0;margin-top:1.5em;margin-bottom:1.5em;}/*!sc*/
.fYaHea table tr{background-color:#fff;border-top:1px solid #ccc;}/*!sc*/
.fYaHea table tr:nth-child(2n){background-color:#fafafa;}/*!sc*/
.fYaHea table th,.fYaHea table td{padding:6px 13px;border:1px solid #ddd;}/*!sc*/
.fYaHea table th{text-align:left;font-weight:bold;}/*!sc*/
.fYaHea .share-link{cursor:pointer;margin-left:-20px;padding:0;line-height:1;width:20px;display:inline-block;outline:0;}/*!sc*/
.fYaHea .share-link:before{content:'';width:15px;height:15px;background-size:contain;background-image:url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeD0iMCIgeT0iMCIgd2lkdGg9IjUxMiIgaGVpZ2h0PSI1MTIiIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiBlbmFibGUtYmFja2dyb3VuZD0ibmV3IDAgMCA1MTIgNTEyIiB4bWw6c3BhY2U9InByZXNlcnZlIj48cGF0aCBmaWxsPSIjMDEwMTAxIiBkPSJNNDU5LjcgMjMzLjRsLTkwLjUgOTAuNWMtNTAgNTAtMTMxIDUwLTE4MSAwIC03LjktNy44LTE0LTE2LjctMTkuNC0yNS44bDQyLjEtNDIuMWMyLTIgNC41LTMuMiA2LjgtNC41IDIuOSA5LjkgOCAxOS4zIDE1LjggMjcuMiAyNSAyNSA2NS42IDI0LjkgOTAuNSAwbDkwLjUtOTAuNWMyNS0yNSAyNS02NS42IDAtOTAuNSAtMjQuOS0yNS02NS41LTI1LTkwLjUgMGwtMzIuMiAzMi4yYy0yNi4xLTEwLjItNTQuMi0xMi45LTgxLjYtOC45bDY4LjYtNjguNmM1MC01MCAxMzEtNTAgMTgxIDBDNTA5LjYgMTAyLjMgNTA5LjYgMTgzLjQgNDU5LjcgMjMzLjR6TTIyMC4zIDM4Mi4ybC0zMi4yIDMyLjJjLTI1IDI0LjktNjUuNiAyNC45LTkwLjUgMCAtMjUtMjUtMjUtNjUuNiAwLTkwLjVsOTAuNS05MC41YzI1LTI1IDY1LjUtMjUgOTAuNSAwIDcuOCA3LjggMTIuOSAxNy4yIDE1LjggMjcuMSAyLjQtMS40IDQuOC0yLjUgNi44LTQuNWw0Mi4xLTQyYy01LjQtOS4yLTExLjYtMTgtMTkuNC0yNS44IC01MC01MC0xMzEtNTAtMTgxIDBsLTkwLjUgOTAuNWMtNTAgNTAtNTAgMTMxIDAgMTgxIDUwIDUwIDEzMSA1MCAxODEgMGw2OC42LTY4LjZDMjc0LjYgMzk1LjEgMjQ2LjQgMzkyLjMgMjIwLjMgMzgyLjJ6Ii8+PC9zdmc+Cg==');opacity:0.5;visibility:hidden;display:inline-block;vertical-align:middle;}/*!sc*/
.fYaHea h1:hover > .share-link::before,.fYaHea h2:hover > .share-link::before,.fYaHea .share-link:hover::before{visibility:visible;}/*!sc*/
.fYaHea a{-webkit-text-decoration:auto;text-decoration:auto;color:#32329f;}/*!sc*/
.fYaHea a:visited{color:#32329f;}/*!sc*/
.fYaHea a:hover{color:#6868cf;-webkit-text-decoration:auto;text-decoration:auto;}/*!sc*/
.fhPxtY{font-family:Roboto,sans-serif;font-weight:400;line-height:1.5em;}/*!sc*/
.fhPxtY p:last-child{margin-bottom:0;}/*!sc*/
.fhPxtY p:first-child{margin-top:0;}/*!sc*/
.fhPxtY p:last-child{margin-bottom:0;}/*!sc*/
.fhPxtY h1{font-family:Montserrat,sans-serif;font-weight:400;font-size:1.85714em;line-height:1.6em;color:#32329f;margin-top:0;}/*!sc*/
.fhPxtY h2{font-family:Montserrat,sans-serif;font-weight:400;font-size:1.57143em;line-height:1.6em;color:#333333;}/*!sc*/
.fhPxtY code{color:#e53935;background-color:rgba(38,50,56,0.05);font-family:Courier,monospace;border-radius:2px;border:1px solid rgba(38,50,56,0.1);padding:0 5px;font-size:13px;font-weight:400;word-break:break-word;}/*!sc*/
.fhPxtY pre{font-family:Courier,monospace;white-space:pre;background-color:#11171a;color:white;padding:20px;overflow-x:auto;line-height:normal;border-radius:0px;border:1px solid rgba(38,50,56,0.1);}/*!sc*/
.fhPxtY pre code{background-color:transparent;color:white;padding:0;}/*!sc*/
.fhPxtY pre code:before,.fhPxtY pre code:after{content:none;}/*!sc*/
.fhPxtY blockquote{margin:0;margin-bottom:1em;padding:0 15px;color:#777;border-left:4px solid #ddd;}/*!sc*/
.fhPxtY img{max-width:100%;box-sizing:content-box;}/*!sc*/
.fhPxtY ul,.fhPxtY ol{padding-left:2em;margin:0;margin-bottom:1em;}/*!sc*/
.fhPxtY ul ul,.fhPxtY ol ul,.fhPxtY ul ol,.fhPxtY ol ol{margin-bottom:0;margin-top:0;}/*!sc*/
.fhPxtY table{display:block;width:100%;overflow:auto;word-break:normal;word-break:keep-all;border-collapse:collapse;border-spacing:0;margin-top:1.5em;margin-bottom:1.5em;}/*!sc*/
.fhPxtY table tr{background-color:#fff;border-top:1px solid #ccc;}/*!sc*/
.fhPxtY table tr:nth-child(2n){background-color:#fafafa;}/*!sc*/
.fhPxtY table th,.fhPxtY table td{padding:6px 13px;border:1px solid #ddd;}/*!sc*/
.fhPxtY table th{text-align:left;font-weight:bold;}/*!sc*/
.fhPxtY .share-link{cursor:pointer;margin-left:-20px;padding:0;line-height:1;width:20px;display:inline-block;outline:0;}/*!sc*/
.fhPxtY .share-link:before{content:'';width:15px;height:15px;background-size:contain;background-image:url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeD0iMCIgeT0iMCIgd2lkdGg9IjUxMiIgaGVpZ2h0PSI1MTIiIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiBlbmFibGUtYmFja2dyb3VuZD0ibmV3IDAgMCA1MTIgNTEyIiB4bWw6c3BhY2U9InByZXNlcnZlIj48cGF0aCBmaWxsPSIjMDEwMTAxIiBkPSJNNDU5LjcgMjMzLjRsLTkwLjUgOTAuNWMtNTAgNTAtMTMxIDUwLTE4MSAwIC03LjktNy44LTE0LTE2LjctMTkuNC0yNS44bDQyLjEtNDIuMWMyLTIgNC41LTMuMiA2LjgtNC41IDIuOSA5LjkgOCAxOS4zIDE1LjggMjcuMiAyNSAyNSA2NS42IDI0LjkgOTAuNSAwbDkwLjUtOTAuNWMyNS0yNSAyNS02NS42IDAtOTAuNSAtMjQuOS0yNS02NS41LTI1LTkwLjUgMGwtMzIuMiAzMi4yYy0yNi4xLTEwLjItNTQuMi0xMi45LTgxLjYtOC45bDY4LjYtNjguNmM1MC01MCAxMzEtNTAgMTgxIDBDNTA5LjYgMTAyLjMgNTA5LjYgMTgzLjQgNDU5LjcgMjMzLjR6TTIyMC4zIDM4Mi4ybC0zMi4yIDMyLjJjLTI1IDI0LjktNjUuNiAyNC45LTkwLjUgMCAtMjUtMjUtMjUtNjUuNiAwLTkwLjVsOTAuNS05MC41YzI1LTI1IDY1LjUtMjUgOTAuNSAwIDcuOCA3LjggMTIuOSAxNy4yIDE1LjggMjcuMSAyLjQtMS40IDQuOC0yLjUgNi44LTQuNWw0Mi4xLTQyYy01LjQtOS4yLTExLjYtMTgtMTkuNC0yNS44IC01MC01MC0xMzEtNTAtMTgxIDBsLTkwLjUgOTAuNWMtNTAgNTAtNTAgMTMxIDAgMTgxIDUwIDUwIDEzMSA1MCAxODEgMGw2OC42LTY4LjZDMjc0LjYgMzk1LjEgMjQ2LjQgMzkyLjMgMjIwLjMgMzgyLjJ6Ii8+PC9zdmc+Cg==');opacity:0.5;visibility:hidden;display:inline-block;vertical-align:middle;}/*!sc*/
.fhPxtY h1:hover > .share-link::before,.fhPxtY h2:hover > .share-link::before,.fhPxtY .share-link:hover::before{visibility:visible;}/*!sc*/
.fhPxtY a{-webkit-text-decoration:auto;text-decoration:auto;color:#32329f;}/*!sc*/
.fhPxtY a:visited{color:#32329f;}/*!sc*/
.fhPxtY a:hover{color:#6868cf;-webkit-text-decoration:auto;text-decoration:auto;}/*!sc*/
data-styled.g43[id="sc-cidDSM"]{content:"fYaHea,fhPxtY,"}/*!sc*/
.eahewB{font-family:Roboto,sans-serif;font-weight:400;line-height:1.5em;}/*!sc*/
.eahewB p:last-child{margin-bottom:0;}/*!sc*/
.eahewB p:first-child{margin-top:0;}/*!sc*/
.eahewB p:last-child{margin-bottom:0;}/*!sc*/
.eahewB p{display:inline-block;}/*!sc*/
.eahewB h1{font-family:Montserrat,sans-serif;font-weight:400;font-size:1.85714em;line-height:1.6em;color:#32329f;margin-top:0;}/*!sc*/
.eahewB h2{font-family:Montserrat,sans-serif;font-weight:400;font-size:1.57143em;line-height:1.6em;color:#333333;}/*!sc*/
.eahewB code{color:#e53935;background-color:rgba(38,50,56,0.05);font-family:Courier,monospace;border-radius:2px;border:1px solid rgba(38,50,56,0.1);padding:0 5px;font-size:13px;font-weight:400;word-break:break-word;}/*!sc*/
.eahewB pre{font-family:Courier,monospace;white-space:pre;background-color:#11171a;color:white;padding:20px;overflow-x:auto;line-height:normal;border-radius:0px;border:1px solid rgba(38,50,56,0.1);}/*!sc*/
.eahewB pre code{background-color:transparent;color:white;padding:0;}/*!sc*/
.eahewB pre code:before,.eahewB pre code:after{content:none;}/*!sc*/
.eahewB blockquote{margin:0;margin-bottom:1em;padding:0 15px;color:#777;border-left:4px solid #ddd;}/*!sc*/
.eahewB img{max-width:100%;box-sizing:content-box;}/*!sc*/
.eahewB ul,.eahewB ol{padding-left:2em;margin:0;margin-bottom:1em;}/*!sc*/
.eahewB ul ul,.eahewB ol ul,.eahewB ul ol,.eahewB ol ol{margin-bottom:0;margin-top:0;}/*!sc*/
.eahewB table{display:block;width:100%;overflow:auto;word-break:normal;word-break:keep-all;border-collapse:collapse;border-spacing:0;margin-top:1.5em;margin-bottom:1.5em;}/*!sc*/
.eahewB table tr{background-color:#fff;border-top:1px solid #ccc;}/*!sc*/
.eahewB table tr:nth-child(2n){background-color:#fafafa;}/*!sc*/
.eahewB table th,.eahewB table td{padding:6px 13px;border:1px solid #ddd;}/*!sc*/
.eahewB table th{text-align:left;font-weight:bold;}/*!sc*/
.eahewB .share-link{cursor:pointer;margin-left:-20px;padding:0;line-height:1;width:20px;display:inline-block;outline:0;}/*!sc*/
.eahewB .share-link:before{content:'';width:15px;height:15px;background-size:contain;background-image:url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgeD0iMCIgeT0iMCIgd2lkdGg9IjUxMiIgaGVpZ2h0PSI1MTIiIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiBlbmFibGUtYmFja2dyb3VuZD0ibmV3IDAgMCA1MTIgNTEyIiB4bWw6c3BhY2U9InByZXNlcnZlIj48cGF0aCBmaWxsPSIjMDEwMTAxIiBkPSJNNDU5LjcgMjMzLjRsLTkwLjUgOTAuNWMtNTAgNTAtMTMxIDUwLTE4MSAwIC03LjktNy44LTE0LTE2LjctMTkuNC0yNS44bDQyLjEtNDIuMWMyLTIgNC41LTMuMiA2LjgtNC41IDIuOSA5LjkgOCAxOS4zIDE1LjggMjcuMiAyNSAyNSA2NS42IDI0LjkgOTAuNSAwbDkwLjUtOTAuNWMyNS0yNSAyNS02NS42IDAtOTAuNSAtMjQuOS0yNS02NS41LTI1LTkwLjUgMGwtMzIuMiAzMi4yYy0yNi4xLTEwLjItNTQuMi0xMi45LTgxLjYtOC45bDY4LjYtNjguNmM1MC01MCAxMzEtNTAgMTgxIDBDNTA5LjYgMTAyLjMgNTA5LjYgMTgzLjQgNDU5LjcgMjMzLjR6TTIyMC4zIDM4Mi4ybC0zMi4yIDMyLjJjLTI1IDI0LjktNjUuNiAyNC45LTkwLjUgMCAtMjUtMjUtMjUtNjUuNiAwLTkwLjVsOTAuNS05MC41YzI1LTI1IDY1LjUtMjUgOTAuNSAwIDcuOCA3LjggMTIuOSAxNy4yIDE1LjggMjcuMSAyLjQtMS40IDQuOC0yLjUgNi44LTQuNWw0Mi4xLTQyYy01LjQtOS4yLTExLjYtMTgtMTkuNC0yNS44IC01MC01MC0xMzEtNTAtMTgxIDBsLTkwLjUgOTAuNWMtNTAgNTAtNTAgMTMxIDAgMTgxIDUwIDUwIDEzMSA1MCAxODEgMGw2OC42LTY4LjZDMjc0LjYgMzk1LjEgMjQ2LjQgMzkyLjMgMjIwLjMgMzgyLjJ6Ii8+PC9zdmc+Cg==');opacity:0.5;visibility:hidden;display:inline-block;vertical-align:middle;}/*!sc*/
.eahewB h1:hover > .share-link::before,.eahewB h2:hover > .share-link::before,.eahewB .share-link:hover::before{visibility:visible;}/*!sc*/
.eahewB a{-webkit-text-decoration:auto;text-decoration:auto;color:#32329f;}/*!sc*/
.eahewB a:visited{color:#32329f;}/*!sc*/
.eahewB a:hover{color:#6868cf;-webkit-text-decoration:auto;text-decoration:auto;}/*!sc*/
data-styled.g44[id="sc-jcFjpl"]{content:"eahewB,"}/*!sc*/
.ddxnzs{position:relative;}/*!sc*/
data-styled.g45[id="sc-caiLqq"]{content:"ddxnzs,"}/*!sc*/
.jOBPNj:hover > .sc-giYglK{opacity:1;}/*!sc*/
data-styled.g50[id="sc-jObWnj"]{content:"jOBPNj,"}/*!sc*/
.sRoPx{font-family:Courier,monospace;font-size:13px;white-space:pre;contain:content;overflow-x:auto;}/*!sc*/
.sRoPx .redoc-json code > .collapser{display:none;pointer-events:none;}/*!sc*/
.sRoPx .callback-function{color:gray;}/*!sc*/
.sRoPx .collapser:after{content:'-';cursor:pointer;}/*!sc*/
.sRoPx .collapsed > .collapser:after{content:'+';cursor:pointer;}/*!sc*/
.sRoPx .ellipsis:after{content:' … ';}/*!sc*/
.sRoPx .collapsible{margin-left:2em;}/*!sc*/
.sRoPx .hoverable{padding-top:1px;padding-bottom:1px;padding-left:2px;padding-right:2px;border-radius:2px;}/*!sc*/
.sRoPx .hovered{background-color:rgba(235,238,249,1);}/*!sc*/
.sRoPx .collapser{background-color:transparent;border:0;color:#fff;font-family:Courier,monospace;font-size:13px;padding-right:6px;padding-left:6px;padding-top:0;padding-bottom:0;display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-align-items:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;-webkit-box-pack:center;-webkit-justify-content:center;-ms-flex-pack:center;justify-content:center;width:15px;height:15px;position:absolute;top:4px;left:-1.5em;cursor:default;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;-webkit-user-select:none;padding:2px;}/*!sc*/
.sRoPx .collapser:focus{outline-color:#fff;outline-style:dotted;outline-width:1px;}/*!sc*/
.sRoPx ul{list-style-type:none;padding:0px;margin:0px 0px 0px 26px;}/*!sc*/
.sRoPx li{position:relative;display:block;}/*!sc*/
.sRoPx .hoverable{display:inline-block;}/*!sc*/
.sRoPx .selected{outline-style:solid;outline-width:1px;outline-style:dotted;}/*!sc*/
.sRoPx .collapsed > .collapsible{display:none;}/*!sc*/
.sRoPx .ellipsis{display:none;}/*!sc*/
.sRoPx .collapsed > .ellipsis{display:inherit;}/*!sc*/
data-styled.g51[id="sc-dPiLbb"]{content:"sRoPx,"}/*!sc*/
.eidhyg{padding:0.9em;background-color:rgba(38,50,56,0.4);margin:0 0 10px 0;display:block;font-family:Montserrat,sans-serif;font-size:0.929em;line-height:1.5em;}/*!sc*/
data-styled.g52[id="sc-bBHHxi"]{content:"eidhyg,"}/*!sc*/
.iYcnri{font-family:Montserrat,sans-serif;font-size:12px;position:absolute;z-index:1;top:-11px;left:12px;font-weight:600;color:rgba(255,255,255,0.7);}/*!sc*/
data-styled.g53[id="sc-cNKqjZ"]{content:"iYcnri,"}/*!sc*/
.bcpfGN{position:relative;}/*!sc*/
data-styled.g54[id="sc-AjmGg"]{content:"bcpfGN,"}/*!sc*/
.iUheaL{margin-top:15px;}/*!sc*/
data-styled.g57[id="sc-jgrJph"]{content:"iUheaL,"}/*!sc*/
.gHbDui{vertical-align:middle;font-size:13px;line-height:20px;}/*!sc*/
data-styled.g59[id="sc-lbhJGD"]{content:"gHbDui,"}/*!sc*/
.eLMLxg{color:rgba(102,102,102,0.9);}/*!sc*/
data-styled.g60[id="sc-iNGGcK"]{content:"eLMLxg,"}/*!sc*/
.ifsMbX{color:#666;}/*!sc*/
data-styled.g61[id="sc-jeraig"]{content:"ifsMbX,"}/*!sc*/
.eyZzuM{vertical-align:middle;font-size:13px;line-height:20px;}/*!sc*/
data-styled.g63[id="sc-nVkyK"]{content:"eyZzuM,"}/*!sc*/
.eSyGZd{color:#d41f1c;font-size:0.9em;font-weight:normal;margin-left:20px;line-height:1;}/*!sc*/
data-styled.g64[id="sc-hiwPVj"]{content:"eSyGZd,"}/*!sc*/
.gGaqcD{margin:1em 0;}/*!sc*/
.gGaqcD a{-webkit-text-decoration:auto;text-decoration:auto;color:#32329f;}/*!sc*/
.gGaqcD a:visited{color:#32329f;}/*!sc*/
.gGaqcD a:hover{color:#6868cf;-webkit-text-decoration:auto;text-decoration:auto;}/*!sc*/
data-styled.g72[id="sc-dvQaRk"]{content:"gGaqcD,"}/*!sc*/
.dezuum{margin-top:0;margin-bottom:0.5em;}/*!sc*/
data-styled.g93[id="sc-dFtzxp"]{content:"dezuum,"}/*!sc*/
.cfBNBf{border:1px solid #32329f;color:#32329f;font-weight:normal;margin-left:0.5em;padding:4px 8px 4px;display:inline-block;-webkit-text-decoration:none;text-decoration:none;cursor:pointer;}/*!sc*/
data-styled.g94[id="sc-brSvTw"]{content:"cfBNBf,"}/*!sc*/
.dSDiln::before{content:'|';display:inline-block;opacity:0.5;width:15px;text-align:center;}/*!sc*/
.dSDiln:last-child::after{display:none;}/*!sc*/
data-styled.g95[id="sc-gIDmLj"]{content:"dSDiln,"}/*!sc*/
.jnWsnL{overflow:hidden;}/*!sc*/
data-styled.g96[id="sc-evcjhq"]{content:"jnWsnL,"}/*!sc*/
.clvmzv{display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-flex-wrap:wrap;-ms-flex-wrap:wrap;flex-wrap:wrap;margin-left:-15px;}/*!sc*/
data-styled.g97[id="sc-fHeRUh"]{content:"clvmzv,"}/*!sc*/
.eXEyiA{width:9ex;display:inline-block;height:13px;line-height:13px;background-color:#333;border-radius:3px;background-repeat:no-repeat;background-position:6px 4px;font-size:7px;font-family:Verdana,sans-serif;color:white;text-transform:uppercase;text-align:center;font-weight:bold;vertical-align:middle;margin-right:6px;margin-top:2px;}/*!sc*/
.eXEyiA.get{background-color:#2F8132;}/*!sc*/
.eXEyiA.post{background-color:#186FAF;}/*!sc*/
.eXEyiA.put{background-color:#95507c;}/*!sc*/
.eXEyiA.options{background-color:#947014;}/*!sc*/
.eXEyiA.patch{background-color:#bf581d;}/*!sc*/
.eXEyiA.delete{background-color:#cc3333;}/*!sc*/
.eXEyiA.basic{background-color:#707070;}/*!sc*/
.eXEyiA.link{background-color:#07818F;}/*!sc*/
.eXEyiA.head{background-color:#A23DAD;}/*!sc*/
.eXEyiA.hook{background-color:#32329f;}/*!sc*/
data-styled.g101[id="sc-ilfuhL"]{content:"eXEyiA,"}/*!sc*/
.cBjpjq{margin:0;padding:0;}/*!sc*/
.cBjpjq:first-child{padding-bottom:32px;}/*!sc*/
.sc-uojGG .sc-uojGG{font-size:0.929em;}/*!sc*/
.fZvBef{margin:0;padding:0;display:none;}/*!sc*/
.fZvBef:first-child{padding-bottom:32px;}/*!sc*/
.sc-uojGG .sc-uojGG{font-size:0.929em;}/*!sc*/
data-styled.g102[id="sc-uojGG"]{content:"cBjpjq,fZvBef,"}/*!sc*/
.iVJVQY{list-style:none inside none;overflow:hidden;text-overflow:ellipsis;padding:0;}/*!sc*/
data-styled.g103[id="sc-bilyIR"]{content:"iVJVQY,"}/*!sc*/
.cbGskd{cursor:pointer;color:#333333;margin:0;padding:12.5px 20px;display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-box-pack:justify;-webkit-justify-content:space-between;-ms-flex-pack:justify;justify-content:space-between;font-family:Montserrat,sans-serif;font-size:0.929em;text-transform:none;background-color:#fafafa;}/*!sc*/
.cbGskd:hover{color:#32329f;background-color:#e1e1e1;}/*!sc*/
.cbGskd .sc-egiyK{height:1.5em;width:1.5em;}/*!sc*/
.cbGskd .sc-egiyK polygon{fill:#333333;}/*!sc*/
.jDuioL{cursor:pointer;color:#333333;margin:0;padding:12.5px 20px;display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-box-pack:justify;-webkit-justify-content:space-between;-ms-flex-pack:justify;justify-content:space-between;font-family:Montserrat,sans-serif;background-color:#fafafa;}/*!sc*/
.jDuioL:hover{color:#32329f;background-color:#ededed;}/*!sc*/
.jDuioL .sc-egiyK{height:1.5em;width:1.5em;}/*!sc*/
.jDuioL .sc-egiyK polygon{fill:#333333;}/*!sc*/
data-styled.g104[id="sc-eGPXGI"]{content:"cbGskd,jDuioL,"}/*!sc*/
.hTIqli{display:inline-block;vertical-align:middle;width:auto;overflow:hidden;text-overflow:ellipsis;}/*!sc*/
.gPtqKT{display:inline-block;vertical-align:middle;width:calc(100% - 38px);overflow:hidden;text-overflow:ellipsis;}/*!sc*/
data-styled.g105[id="sc-hAcGzb"]{content:"hTIqli,gPtqKT,"}/*!sc*/
.hjTfvW{font-size:0.8em;margin-top:10px;text-align:center;position:fixed;width:260px;bottom:0;background:#fafafa;}/*!sc*/
.hjTfvW a,.hjTfvW a:visited,.hjTfvW a:hover{color:#333333 !important;padding:5px 0;border-top:1px solid #e1e1e1;-webkit-text-decoration:none;text-decoration:none;display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-align-items:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;-webkit-box-pack:center;-webkit-justify-content:center;-ms-flex-pack:center;justify-content:center;}/*!sc*/
.hjTfvW img{width:15px;margin-right:5px;}/*!sc*/
@media screen and (max-width:50rem){.hjTfvW{width:100%;}}/*!sc*/
data-styled.g106[id="sc-kYHfwS"]{content:"hjTfvW,"}/*!sc*/
.jYAhkx{cursor:pointer;position:relative;margin-bottom:5px;}/*!sc*/
data-styled.g112[id="sc-FNXRL"]{content:"jYAhkx,"}/*!sc*/
.hxZHzL{font-family:Courier,monospace;margin-left:10px;-webkit-flex:1;-ms-flex:1;flex:1;overflow-x:hidden;text-overflow:ellipsis;}/*!sc*/
data-styled.g113[id="sc-jWUzzU"]{content:"hxZHzL,"}/*!sc*/
.bxamQ{outline:0;color:inherit;width:100%;text-align:left;cursor:pointer;padding:10px 30px 10px 20px;border-radius:4px 4px 0 0;background-color:#11171a;display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;white-space:nowrap;-webkit-align-items:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;border:1px solid transparent;border-bottom:0;-webkit-transition:border-color 0.25s ease;transition:border-color 0.25s ease;}/*!sc*/
.bxamQ ..sc-jWUzzU{color:#ffffff;}/*!sc*/
.bxamQ:focus{box-shadow:inset 0 2px 2px rgba(0,0,0,0.45),0 2px 0 rgba(128,128,128,0.25);}/*!sc*/
data-styled.g114[id="sc-eFegNN"]{content:"bxamQ,"}/*!sc*/
.hYmQQT{font-size:0.929em;line-height:20px;background-color:#2F8132;color:#ffffff;padding:3px 10px;text-transform:uppercase;font-family:Montserrat,sans-serif;margin:0;}/*!sc*/
.huMmnt{font-size:0.929em;line-height:20px;background-color:#186FAF;color:#ffffff;padding:3px 10px;text-transform:uppercase;font-family:Montserrat,sans-serif;margin:0;}/*!sc*/
.iKSThS{font-size:0.929em;line-height:20px;background-color:#A23DAD;color:#ffffff;padding:3px 10px;text-transform:uppercase;font-family:Montserrat,sans-serif;margin:0;}/*!sc*/
data-styled.g115[id="sc-fmBCVi"]{content:"hYmQQT,huMmnt,iKSThS,"}/*!sc*/
.fuqHqW{position:absolute;width:100%;z-index:100;background:#fafafa;color:#263238;box-sizing:border-box;box-shadow:0px 0px 6px rgba(0,0,0,0.33);overflow:hidden;border-bottom-left-radius:4px;border-bottom-right-radius:4px;-webkit-transition:all 0.25s ease;transition:all 0.25s ease;visibility:hidden;-webkit-transform:translateY(-50%) scaleY(0);-ms-transform:translateY(-50%) scaleY(0);transform:translateY(-50%) scaleY(0);}/*!sc*/
data-styled.g116[id="sc-lkgTHX"]{content:"fuqHqW,"}/*!sc*/
.fUpXCf{padding:10px;}/*!sc*/
data-styled.g117[id="sc-jlRLRk"]{content:"fUpXCf,"}/*!sc*/
.ggmziU{padding:5px;border:1px solid #ccc;background:#fff;word-break:break-all;color:#32329f;}/*!sc*/
.ggmziU > span{color:#333333;}/*!sc*/
data-styled.g118[id="sc-dUbtfd"]{content:"ggmziU,"}/*!sc*/
.exjkhl{display:block;border:0;width:100%;text-align:left;padding:10px;border-radius:2px;margin-bottom:4px;line-height:1.5em;cursor:pointer;color:#1d8127;background-color:rgba(29,129,39,0.07);cursor:default;}/*!sc*/
.exjkhl:focus{outline:auto #1d8127;}/*!sc*/
.exjkhl::before{content:"—";font-weight:bold;width:1.5em;text-align:center;display:inline-block;vertical-align:top;}/*!sc*/
.exjkhl:focus{outline:0;}/*!sc*/
.hoRAnv{display:block;border:0;width:100%;text-align:left;padding:10px;border-radius:2px;margin-bottom:4px;line-height:1.5em;cursor:pointer;color:#1d8127;background-color:rgba(29,129,39,0.07);}/*!sc*/
.hoRAnv:focus{outline:auto #1d8127;}/*!sc*/
.gBqHPX{display:block;border:0;width:100%;text-align:left;padding:10px;border-radius:2px;margin-bottom:4px;line-height:1.5em;cursor:pointer;color:#d41f1c;background-color:rgba(212,31,28,0.07);cursor:default;}/*!sc*/
.gBqHPX:focus{outline:auto #d41f1c;}/*!sc*/
.gBqHPX::before{content:"—";font-weight:bold;width:1.5em;text-align:center;display:inline-block;vertical-align:top;}/*!sc*/
.gBqHPX:focus{outline:0;}/*!sc*/
.wltdp{display:block;border:0;width:100%;text-align:left;padding:10px;border-radius:2px;margin-bottom:4px;line-height:1.5em;cursor:pointer;color:#d41f1c;background-color:rgba(212,31,28,0.07);}/*!sc*/
.wltdp:focus{outline:auto #d41f1c;}/*!sc*/
data-styled.g119[id="sc-htJRVC"]{content:"exjkhl,hoRAnv,gBqHPX,wltdp,"}/*!sc*/
.jHtNTU{vertical-align:top;}/*!sc*/
data-styled.g123[id="sc-fXeWAj"]{content:"jHtNTU,"}/*!sc*/
.bTvSgn{font-size:1.3em;padding:0.2em 0;margin:3em 0 1.1em;color:#333333;font-weight:normal;}/*!sc*/
data-styled.g124[id="sc-fIosxK"]{content:"bTvSgn,"}/*!sc*/
.ilWCwE{margin-bottom:30px;}/*!sc*/
data-styled.g129[id="sc-iFMAIt"]{content:"ilWCwE,"}/*!sc*/
.lptroy{-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;width:20px;height:20px;-webkit-align-self:center;-ms-flex-item-align:center;align-self:center;display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-flex-direction:column;-ms-flex-direction:column;flex-direction:column;color:#32329f;}/*!sc*/
data-styled.g130[id="sc-iqVWFU"]{content:"lptroy,"}/*!sc*/
.iFeLMl{width:260px;background-color:#fafafa;overflow:hidden;display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;-webkit-flex-direction:column;-ms-flex-direction:column;flex-direction:column;-webkit-backface-visibility:hidden;backface-visibility:hidden;height:100vh;position:-webkit-sticky;position:sticky;position:-webkit-sticky;top:0;}/*!sc*/
@media screen and (max-width:50rem){.iFeLMl{position:fixed;z-index:20;width:100%;background:#fafafa;display:none;}}/*!sc*/
@media print{.iFeLMl{display:none;}}/*!sc*/
data-styled.g131[id="sc-eWfVMQ"]{content:"iFeLMl,"}/*!sc*/
.cxHKpm{outline:none;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;background-color:#f2f2f2;color:#32329f;display:none;cursor:pointer;position:fixed;right:20px;z-index:100;border-radius:50%;box-shadow:0 0 20px rgba(0,0,0,0.3);bottom:44px;width:60px;height:60px;padding:0 20px;}/*!sc*/
@media screen and (max-width:50rem){.cxHKpm{display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;}}/*!sc*/
.cxHKpm svg{color:#0065FB;}/*!sc*/
@media print{.cxHKpm{display:none;}}/*!sc*/
data-styled.g132[id="sc-kTLmzF"]{content:"cxHKpm,"}/*!sc*/
.cjkacg{font-family:Roboto,sans-serif;font-size:14px;font-weight:400;line-height:1.5em;color:#333333;display:-webkit-box;display:-webkit-flex;display:-ms-flexbox;display:flex;position:relative;text-align:left;-webkit-font-smoothing:antialiased;font-smoothing:antialiased;text-rendering:optimizeSpeed !important;tap-highlight-color:rgba(0,0,0,0);-webkit-text-size-adjust:100%;text-size-adjust:100%;}/*!sc*/
.cjkacg *{box-sizing:border-box;-webkit-tap-highlight-color:rgba(255,255,255,0);}/*!sc*/
data-styled.g133[id="sc-dwsnSq"]{content:"cjkacg,"}/*!sc*/
.jxeukX{z-index:1;position:relative;overflow:hidden;width:calc(100% - 260px);contain:layout;}/*!sc*/
@media print,screen and (max-width:50rem){.jxeukX{width:100%;}}/*!sc*/
data-styled.g134[id="sc-jtXEFf"]{content:"jxeukX,"}/*!sc*/
.bLydqy{background:#263238;position:absolute;top:0;bottom:0;right:0;width:calc((100% - 260px) * 0.4);}/*!sc*/
@media print,screen and (max-width:75rem){.bLydqy{display:none;}}/*!sc*/
data-styled.g135[id="sc-eldieg"]{content:"bLydqy,"}/*!sc*/
.qyDlP{padding:5px 0;}/*!sc*/
data-styled.g136[id="sc-kiIyQV"]{content:"qyDlP,"}/*!sc*/
.KrPzq{width:calc(100% - 40px);box-sizing:border-box;margin:0 20px;padding:5px 10px 5px 20px;border:0;border-bottom:1px solid #e1e1e1;font-family:Roboto,sans-serif;font-weight:bold;font-size:13px;color:#333333;background-color:transparent;outline:none;}/*!sc*/
data-styled.g137[id="sc-cLpAjG"]{content:"KrPzq,"}/*!sc*/
.liFvtQ{position:absolute;left:20px;height:1.8em;width:0.9em;}/*!sc*/
.liFvtQ path{fill:#333333;}/*!sc*/
data-styled.g138[id="sc-iIUQWv"]{content:"liFvtQ,"}/*!sc*/
</style>
  <link href="https://fonts.googleapis.com/css?family=Montserrat:300,400,700|Roboto:300,400,700" rel="stylesheet">
</head>

<body>
  
      <div id="redoc"><div class="sc-dwsnSq cjkacg redoc-wrap"><div class="sc-eWfVMQ iFeLMl menu-content" style="top:0px;height:calc(100vh - 0px)"><div role="search" class="sc-kiIyQV qyDlP"><svg class="sc-iIUQWv liFvtQ search-icon" version="1.1" viewBox="0 0 1000 1000" x="0px" xmlns="http://www.w3.org/2000/svg" y="0px"><path d="M968.2,849.4L667.3,549c83.9-136.5,66.7-317.4-51.7-435.6C477.1-25,252.5-25,113.9,113.4c-138.5,138.3-138.5,362.6,0,501C219.2,730.1,413.2,743,547.6,666.5l301.9,301.4c43.6,43.6,76.9,14.9,104.2-12.4C981,928.3,1011.8,893,968.2,849.4z M524.5,522c-88.9,88.7-233,88.7-321.8,0c-88.9-88.7-88.9-232.6,0-321.3c88.9-88.7,233-88.7,321.8,0C613.4,289.4,613.4,433.3,524.5,522z"></path></svg><input type="text" value="" placeholder="Search..." aria-label="Search" class="sc-cLpAjG KrPzq search-input"/></div><div class="sc-ikJyIC eqZXtE scrollbar-container undefined"><ul class="sc-uojGG cBjpjq" role="menu"><li data-item-id="tag/home-page" class="sc-bilyIR iVJVQY"><label type="tag" role="menuitem" class="sc-eGPXGI cbGskd -depth1"><span title="home-page" class="sc-hAcGzb hTIqli">home-page</span><svg class="sc-egiyK jLPfXH" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg></label><ul class="sc-uojGG fZvBef"><li data-item-id="tag/home-page/paths/~1/get" class="sc-bilyIR iVJVQY"><label role="menuitem" class="sc-eGPXGI jDuioL -depth2"><span type="get" class="sc-ilfuhL eXEyiA operation-type get">get</span><span width="calc(100% - 38px)" class="sc-hAcGzb gPtqKT">Hello World!</span></label></li></ul></li><li data-item-id="tag/about-page" class="sc-bilyIR iVJVQY"><label type="tag" role="menuitem" class="sc-eGPXGI cbGskd -depth1"><span title="about-page" class="sc-hAcGzb hTIqli">about-page</span><svg class="sc-egiyK jLPfXH" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg></label><ul class="sc-uojGG fZvBef"><li data-item-id="tag/about-page/paths/~1about/get" class="sc-bilyIR iVJVQY"><label role="menuitem" class="sc-eGPXGI jDuioL -depth2"><span type="get" class="sc-ilfuhL eXEyiA operation-type get">get</span><span width="calc(100% - 38px)" class="sc-hAcGzb gPtqKT">Clojure version</span></label></li></ul></li><li data-item-id="tag/upload" class="sc-bilyIR iVJVQY"><label type="tag" role="menuitem" class="sc-eGPXGI cbGskd -depth1"><span title="upload" class="sc-hAcGzb hTIqli">upload</span><svg class="sc-egiyK jLPfXH" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg></label><ul class="sc-uojGG fZvBef"><li data-item-id="tag/upload/paths/~1upload/post" class="sc-bilyIR iVJVQY"><label role="menuitem" class="sc-eGPXGI jDuioL -depth2"><span type="post" class="sc-ilfuhL eXEyiA operation-type post">post</span><span width="calc(100% - 38px)" class="sc-hAcGzb gPtqKT">Upload a file</span></label></li></ul></li><li data-item-id="tag/download" class="sc-bilyIR iVJVQY"><label type="tag" role="menuitem" class="sc-eGPXGI cbGskd -depth1"><span title="download" class="sc-hAcGzb hTIqli">download</span><svg class="sc-egiyK jLPfXH" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg></label><ul class="sc-uojGG fZvBef"><li data-item-id="tag/download/paths/~1download~1{file-id}/get" class="sc-bilyIR iVJVQY"><label role="menuitem" class="sc-eGPXGI jDuioL -depth2"><span type="get" class="sc-ilfuhL eXEyiA operation-type get">get</span><span width="calc(100% - 38px)" class="sc-hAcGzb gPtqKT">Download file by ID</span></label></li><li data-item-id="tag/download/paths/~1download~1{file-id}/head" class="sc-bilyIR iVJVQY"><label role="menuitem" class="sc-eGPXGI jDuioL -depth2"><span type="head" class="sc-ilfuhL eXEyiA operation-type head">head</span><span width="calc(100% - 38px)" class="sc-hAcGzb gPtqKT">Get file information by ID</span></label></li></ul></li></ul><div class="sc-kYHfwS hjTfvW"><a target="_blank" rel="noopener noreferrer" href="https://redocly.com/redoc/">API docs by Redocly</a></div></div></div><div class="sc-kTLmzF cxHKpm"><div class="sc-iqVWFU lptroy"><svg class="" style="transform:translate(2px, -4px) rotate(180deg);transition:transform 0.2s ease" viewBox="0 0 926.23699 573.74994" version="1.1" x="0px" y="0px" width="15" height="15"><g transform="translate(904.92214,-879.1482)"><path d="
          m -673.67664,1221.6502 -231.2455,-231.24803 55.6165,
          -55.627 c 30.5891,-30.59485 56.1806,-55.627 56.8701,-55.627 0.6894,
          0 79.8637,78.60862 175.9427,174.68583 l 174.6892,174.6858 174.6892,
          -174.6858 c 96.079,-96.07721 175.253196,-174.68583 175.942696,
          -174.68583 0.6895,0 26.281,25.03215 56.8701,
          55.627 l 55.6165,55.627 -231.245496,231.24803 c -127.185,127.1864
          -231.5279,231.248 -231.873,231.248 -0.3451,0 -104.688,
          -104.0616 -231.873,-231.248 z
        " fill="currentColor"></path></g></svg><svg class="" style="transform:translate(2px, 4px);transition:transform 0.2s ease" viewBox="0 0 926.23699 573.74994" version="1.1" x="0px" y="0px" width="15" height="15"><g transform="translate(904.92214,-879.1482)"><path d="
          m -673.67664,1221.6502 -231.2455,-231.24803 55.6165,
          -55.627 c 30.5891,-30.59485 56.1806,-55.627 56.8701,-55.627 0.6894,
          0 79.8637,78.60862 175.9427,174.68583 l 174.6892,174.6858 174.6892,
          -174.6858 c 96.079,-96.07721 175.253196,-174.68583 175.942696,
          -174.68583 0.6895,0 26.281,25.03215 56.8701,
          55.627 l 55.6165,55.627 -231.245496,231.24803 c -127.185,127.1864
          -231.5279,231.248 -231.873,231.248 -0.3451,0 -104.688,
          -104.0616 -231.873,-231.248 z
        " fill="currentColor"></path></g></svg></div></div><div class="sc-jtXEFf jxeukX api-content"><div class="sc-eCImPb kKqedw"><div class="sc-iCfMLu jTXZbd"><div class="sc-hKwDye fcjMZs api-info"><h1 class="sc-furwcr sc-dFtzxp kwcwWd dezuum">Nutbox<!-- --> <span>(<!-- -->1.0.0<!-- -->)</span></h1><p>Download OpenAPI specification<!-- -->:<a download="openapi.json" target="_blank" class="sc-brSvTw cfBNBf">Download</a></p><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea"><div class="sc-evcjhq jnWsnL"><div class="sc-fHeRUh clvmzv"><span class="sc-gIDmLj dSDiln">E-mail<!-- -->:<!-- --> <a href="mailto:nutbox@nutufuro.com">nutbox@nutufuro.com</a></span> <!-- --> <!-- --> </div></div></div><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea" data-role="redoc-summary"></div><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea" data-role="redoc-description"><p>This API provides a  solution for transferring files over the network. This API was build using clojure Pedestal API, which is a a set of libraries that we use to build services and applications.
Some useful links:</p>
<ul>
<li><a href="https://github.com/nufuturo-ufcg/nutbox-backend">NuTBox repository</a></li>
<li><a href="http://pedestal.io/">Pedestal API</a></li>
</ul>
</div><div class="sc-dvQaRk gGaqcD"><a href="http://swagger.io">Find out more about Swagger</a></div></div></div></div><div id="tag/home-page" data-section-id="tag/home-page" class="sc-eCImPb kKqedw"><div class="sc-iCfMLu jTXZbd"><div class="sc-hKwDye fcjMZs"><h1 class="sc-furwcr kwcwWd"><a class="sc-crHmcD bNUQy" href="#tag/home-page" aria-label="tag/home-page"></a>home-page</h1></div></div><div class="sc-hKwDye frutYI"><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea redoc-markdown "><p>Home Page</p>
</div></div></div><div id="tag/home-page/paths/~1/get" data-section-id="tag/home-page/paths/~1/get" class="sc-eCImPb hexvPn"><div class="sc-iCfMLu jTXZbd"><div class="sc-hKwDye fcjMZs"><h2 class="sc-pVTFL QwiBS"><a class="sc-crHmcD bNUQy" href="#tag/home-page/paths/~1/get" aria-label="tag/home-page/paths/~1/get"></a>Hello World!<!-- --> </h2><div class="sc-iFMAIt ilWCwE"><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea"><p>Returns the &quot;Hello World!&quot; message.</p>
</div></div><div><h3 class="sc-fIosxK bTvSgn">Responses</h3><div><button class="sc-htJRVC exjkhl" disabled=""><strong class="sc-fXeWAj jHtNTU">200<!-- --> </strong><span class="sc-jcFjpl eahewB"><p>Successful operation</p>
</span></button></div></div></div><div class="sc-jRQBWg sc-gKclnd vSqXI dKDnzb"><div class="sc-FNXRL jYAhkx"><button class="sc-eFegNN bxamQ"><span type="get" class="sc-fmBCVi hYmQQT http-verb get">get</span><span class="sc-jWUzzU hxZHzL">/</span><svg class="sc-egiyK laPRNF" style="margin-right:-25px" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg></button><div aria-hidden="true" class="sc-lkgTHX fuqHqW"><div class="sc-jlRLRk fUpXCf"><div class="sc-iJKOTD sc-cidDSM hGZPxu fhPxtY"></div><div tabindex="0" role="button"><div class="sc-dUbtfd ggmziU"><span>http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com</span>/</div></div></div></div></div><div><h3 class="sc-kDTinF hwMGJl"> <!-- -->Request samples<!-- --> </h3><div class="sc-cxpSdN eCLDJY" data-rttabs="true"><ul class="react-tabs__tab-list" role="tablist"><li class="react-tabs__tab react-tabs__tab--selected" role="tab" id="react-tabs-0" aria-selected="true" aria-disabled="false" aria-controls="react-tabs-1" tabindex="0" data-rttab="true">cURL</li><li class="react-tabs__tab" role="tab" id="react-tabs-2" aria-selected="false" aria-disabled="false" aria-controls="react-tabs-3" data-rttab="true">Python</li><li class="react-tabs__tab" role="tab" id="react-tabs-4" aria-selected="false" aria-disabled="false" aria-controls="react-tabs-5" data-rttab="true">Java</li></ul><div class="react-tabs__tab-panel react-tabs__tab-panel--selected" role="tabpanel" id="react-tabs-1" aria-labelledby="react-tabs-0"><div class="sc-ezbkAF flfPA"><div class="sc-giYglK gjxyHD"><button><div class="sc-caiLqq ddxnzs">Copy</div></button></div><pre class="sc-bYoBSM sc-kLwhqv kQTUkh fHMTIq">curl http<span class="token punctuation">:</span><span class="token operator">/</span><span class="token operator">/</span>ec2<span class="token operator">-</span><span class="token number">52</span><span class="token operator">-</span><span class="token number">67</span><span class="token operator">-</span><span class="token number">249</span><span class="token operator">-</span><span class="token number">109.</span>sa<span class="token operator">-</span>east<span class="token operator">-</span><span class="token number">1.</span>compute<span class="token punctuation">.</span>amazonaws<span class="token punctuation">.</span>com<span class="token operator">/</span></pre></div></div><div class="react-tabs__tab-panel" role="tabpanel" id="react-tabs-3" aria-labelledby="react-tabs-2"></div><div class="react-tabs__tab-panel" role="tabpanel" id="react-tabs-5" aria-labelledby="react-tabs-4"></div></div></div></div></div></div><div id="tag/about-page" data-section-id="tag/about-page" class="sc-eCImPb kKqedw"><div class="sc-iCfMLu jTXZbd"><div class="sc-hKwDye fcjMZs"><h1 class="sc-furwcr kwcwWd"><a class="sc-crHmcD bNUQy" href="#tag/about-page" aria-label="tag/about-page"></a>about-page</h1></div></div><div class="sc-hKwDye frutYI"><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea redoc-markdown "><p>About Page</p>
</div></div></div><div id="tag/about-page/paths/~1about/get" data-section-id="tag/about-page/paths/~1about/get" class="sc-eCImPb hexvPn"><div class="sc-iCfMLu jTXZbd"><div class="sc-hKwDye fcjMZs"><h2 class="sc-pVTFL QwiBS"><a class="sc-crHmcD bNUQy" href="#tag/about-page/paths/~1about/get" aria-label="tag/about-page/paths/~1about/get"></a>Clojure version<!-- --> </h2><div class="sc-iFMAIt ilWCwE"><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea"><p>Returns the current Clojure version.</p>
</div></div><div><h3 class="sc-fIosxK bTvSgn">Responses</h3><div><button class="sc-htJRVC exjkhl" disabled=""><strong class="sc-fXeWAj jHtNTU">200<!-- --> </strong><span class="sc-jcFjpl eahewB"><p>Successful operation</p>
</span></button></div></div></div><div class="sc-jRQBWg sc-gKclnd vSqXI dKDnzb"><div class="sc-FNXRL jYAhkx"><button class="sc-eFegNN bxamQ"><span type="get" class="sc-fmBCVi hYmQQT http-verb get">get</span><span class="sc-jWUzzU hxZHzL">/about</span><svg class="sc-egiyK laPRNF" style="margin-right:-25px" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg></button><div aria-hidden="true" class="sc-lkgTHX fuqHqW"><div class="sc-jlRLRk fUpXCf"><div class="sc-iJKOTD sc-cidDSM hGZPxu fhPxtY"></div><div tabindex="0" role="button"><div class="sc-dUbtfd ggmziU"><span>http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com</span>/about</div></div></div></div></div><div><h3 class="sc-kDTinF hwMGJl"> <!-- -->Request samples<!-- --> </h3><div class="sc-cxpSdN eCLDJY" data-rttabs="true"><ul class="react-tabs__tab-list" role="tablist"><li class="react-tabs__tab react-tabs__tab--selected" role="tab" id="react-tabs-6" aria-selected="true" aria-disabled="false" aria-controls="react-tabs-7" tabindex="0" data-rttab="true">cURL</li><li class="react-tabs__tab" role="tab" id="react-tabs-8" aria-selected="false" aria-disabled="false" aria-controls="react-tabs-9" data-rttab="true">Python</li><li class="react-tabs__tab" role="tab" id="react-tabs-10" aria-selected="false" aria-disabled="false" aria-controls="react-tabs-11" data-rttab="true">Java</li></ul><div class="react-tabs__tab-panel react-tabs__tab-panel--selected" role="tabpanel" id="react-tabs-7" aria-labelledby="react-tabs-6"><div class="sc-ezbkAF flfPA"><div class="sc-giYglK gjxyHD"><button><div class="sc-caiLqq ddxnzs">Copy</div></button></div><pre class="sc-bYoBSM sc-kLwhqv kQTUkh fHMTIq">curl http<span class="token punctuation">:</span><span class="token operator">/</span><span class="token operator">/</span>ec2<span class="token operator">-</span><span class="token number">52</span><span class="token operator">-</span><span class="token number">67</span><span class="token operator">-</span><span class="token number">249</span><span class="token operator">-</span><span class="token number">109.</span>sa<span class="token operator">-</span>east<span class="token operator">-</span><span class="token number">1.</span>compute<span class="token punctuation">.</span>amazonaws<span class="token punctuation">.</span>com<span class="token punctuation">:</span><span class="token number">8080</span><span class="token operator">/</span>about</pre></div></div><div class="react-tabs__tab-panel" role="tabpanel" id="react-tabs-9" aria-labelledby="react-tabs-8"></div><div class="react-tabs__tab-panel" role="tabpanel" id="react-tabs-11" aria-labelledby="react-tabs-10"></div></div></div></div></div></div><div id="tag/upload" data-section-id="tag/upload" class="sc-eCImPb kKqedw"><div class="sc-iCfMLu jTXZbd"><div class="sc-hKwDye fcjMZs"><h1 class="sc-furwcr kwcwWd"><a class="sc-crHmcD bNUQy" href="#tag/upload" aria-label="tag/upload"></a>upload</h1></div></div></div><div id="tag/upload/paths/~1upload/post" data-section-id="tag/upload/paths/~1upload/post" class="sc-eCImPb hexvPn"><div class="sc-iCfMLu jTXZbd"><div class="sc-hKwDye fcjMZs"><h2 class="sc-pVTFL QwiBS"><a class="sc-crHmcD bNUQy" href="#tag/upload/paths/~1upload/post" aria-label="tag/upload/paths/~1upload/post"></a>Upload a file<!-- --> </h2><div class="sc-iFMAIt ilWCwE"><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea"><p>Uploads a file using multipart form data.</p>
</div></div><h5 class="sc-iqseJM kyZwVG">Request Body schema: <span class="sc-cCcXHH hgRRjA">multipart/form-data</span></h5><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea"></div><table class="sc-hGPBjI wbnF"><tbody><tr class="last "><td class="sc-hBUSln sc-fFeiMQ kCCtqV fwnkRw" kind="field" title="file"><span class="sc-ieecCq fMdASL"></span><span class="property-name">file</span><div class="sc-nVkyK sc-hiwPVj eyZzuM eSyGZd">required</div></td><td class="sc-bkkeKt fOwWgB"><div><div><span class="sc-lbhJGD sc-iNGGcK gHbDui eLMLxg"></span><span class="sc-lbhJGD sc-jeraig gHbDui ifsMbX">string</span><span class="sc-lbhJGD sc-jeraig gHbDui ifsMbX"> <!-- -->&lt;<!-- -->binary<!-- -->&gt;<!-- --> </span></div> <div><div class="sc-iJKOTD sc-cidDSM hGZPxu fhPxtY"><p>The file to upload</p>
</div></div></div></td></tr></tbody></table><div><h3 class="sc-fIosxK bTvSgn">Responses</h3><div><button class="sc-htJRVC hoRAnv"><svg class="sc-egiyK bPEzCN" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg><strong class="sc-fXeWAj jHtNTU">200<!-- --> </strong><span class="sc-jcFjpl eahewB"><p>Successful operation</p>
</span></button></div><div><button class="sc-htJRVC gBqHPX" disabled=""><strong class="sc-fXeWAj jHtNTU">400<!-- --> </strong><span class="sc-jcFjpl eahewB"><p>File Not Uploaded</p>
</span></button></div></div></div><div class="sc-jRQBWg sc-gKclnd vSqXI dKDnzb"><div class="sc-FNXRL jYAhkx"><button class="sc-eFegNN bxamQ"><span type="post" class="sc-fmBCVi huMmnt http-verb post">post</span><span class="sc-jWUzzU hxZHzL">/upload</span><svg class="sc-egiyK laPRNF" style="margin-right:-25px" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg></button><div aria-hidden="true" class="sc-lkgTHX fuqHqW"><div class="sc-jlRLRk fUpXCf"><div class="sc-iJKOTD sc-cidDSM hGZPxu fhPxtY"></div><div tabindex="0" role="button"><div class="sc-dUbtfd ggmziU"><span>http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com</span>/upload</div></div></div></div></div><div><h3 class="sc-kDTinF hwMGJl"> <!-- -->Request samples<!-- --> </h3><div class="sc-cxpSdN eCLDJY" data-rttabs="true"><ul class="react-tabs__tab-list" role="tablist"><li class="react-tabs__tab react-tabs__tab--selected" role="tab" id="react-tabs-12" aria-selected="true" aria-disabled="false" aria-controls="react-tabs-13" tabindex="0" data-rttab="true">cURL</li><li class="react-tabs__tab" role="tab" id="react-tabs-14" aria-selected="false" aria-disabled="false" aria-controls="react-tabs-15" data-rttab="true">Python</li><li class="react-tabs__tab" role="tab" id="react-tabs-16" aria-selected="false" aria-disabled="false" aria-controls="react-tabs-17" data-rttab="true">Java</li></ul><div class="react-tabs__tab-panel react-tabs__tab-panel--selected" role="tabpanel" id="react-tabs-13" aria-labelledby="react-tabs-12"><div class="sc-ezbkAF flfPA"><div class="sc-giYglK gjxyHD"><button><div class="sc-caiLqq ddxnzs">Copy</div></button></div><pre class="sc-bYoBSM sc-kLwhqv kQTUkh fHMTIq">curl <span class="token operator">-</span>X POST <span class="token operator">-</span>H <span class="token string">'content-type: multipart/form-data'</span> <span class="token operator">-</span>F <span class="token string">'file=@&lt;path-to-your-file>'</span> http<span class="token punctuation">:</span><span class="token operator">/</span><span class="token operator">/</span>ec2<span class="token operator">-</span><span class="token number">52</span><span class="token operator">-</span><span class="token number">67</span><span class="token operator">-</span><span class="token number">249</span><span class="token operator">-</span><span class="token number">109.</span>sa<span class="token operator">-</span>east<span class="token operator">-</span><span class="token number">1.</span>compute<span class="token punctuation">.</span>amazonaws<span class="token punctuation">.</span>com<span class="token punctuation">:</span><span class="token number">8080</span><span class="token operator">/</span>upload</pre></div></div><div class="react-tabs__tab-panel" role="tabpanel" id="react-tabs-15" aria-labelledby="react-tabs-14"></div><div class="react-tabs__tab-panel" role="tabpanel" id="react-tabs-17" aria-labelledby="react-tabs-16"></div></div></div><div><h3 class="sc-kDTinF hwMGJl"> <!-- -->Response samples<!-- --> </h3><div class="sc-cxpSdN eCLDJY" data-rttabs="true"><ul class="react-tabs__tab-list" role="tablist"><li class="tab-success react-tabs__tab--selected" role="tab" id="react-tabs-18" aria-selected="true" aria-disabled="false" aria-controls="react-tabs-19" tabindex="0" data-rttab="true">200</li></ul><div class="react-tabs__tab-panel react-tabs__tab-panel--selected" role="tabpanel" id="react-tabs-19" aria-labelledby="react-tabs-18"><div><div class="sc-AjmGg bcpfGN"><span class="sc-cNKqjZ iYcnri">Content type</span><div class="sc-bBHHxi eidhyg">application/json</div></div><div class="sc-jgrJph iUheaL"><div class="sc-jObWnj jOBPNj"><div class="sc-giYglK gjxyHD"><button><div class="sc-caiLqq ddxnzs">Copy</div></button></div><div class="sc-iJKOTD hGZPxu sc-dPiLbb sRoPx"><div class="redoc-json"><code><button class="collapser" aria-label="collapse"></button><span class="token punctuation">{</span><span class="ellipsis"></span><ul class="obj collapsible"><li><div class="hoverable "><span class="property token string">"data"</span>: <span class="token string">&quot;string&quot;</span></div></li></ul><span class="token punctuation">}</span></code></div></div></div></div></div></div></div></div></div></div></div><div id="tag/download" data-section-id="tag/download" class="sc-eCImPb kKqedw"><div class="sc-iCfMLu jTXZbd"><div class="sc-hKwDye fcjMZs"><h1 class="sc-furwcr kwcwWd"><a class="sc-crHmcD bNUQy" href="#tag/download" aria-label="tag/download"></a>download</h1></div></div><div class="sc-hKwDye frutYI"><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea redoc-markdown "><p>File Download</p>
</div></div></div><div id="tag/download/paths/~1download~1{file-id}/get" data-section-id="tag/download/paths/~1download~1{file-id}/get" class="sc-eCImPb hexvPn"><div class="sc-iCfMLu jTXZbd"><div class="sc-hKwDye fcjMZs"><h2 class="sc-pVTFL QwiBS"><a class="sc-crHmcD bNUQy" href="#tag/download/paths/~1download~1{file-id}/get" aria-label="tag/download/paths/~1download~1{file-id}/get"></a>Download file by ID<!-- --> </h2><div class="sc-iFMAIt ilWCwE"><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea"><p>Downloads a file by its ID.</p>
</div></div><div><h5 class="sc-iqseJM kyZwVG">path<!-- --> Parameters</h5><table class="sc-hGPBjI wbnF"><tbody><tr class="last "><td class="sc-hBUSln sc-fFeiMQ kCCtqV fwnkRw" kind="field" title="file-id"><span class="sc-ieecCq fMdASL"></span><span class="property-name">file-id</span><div class="sc-nVkyK sc-hiwPVj eyZzuM eSyGZd">required</div></td><td class="sc-bkkeKt fOwWgB"><div><div><span class="sc-lbhJGD sc-iNGGcK gHbDui eLMLxg"></span><span class="sc-lbhJGD sc-jeraig gHbDui ifsMbX">string</span></div> <div><div class="sc-iJKOTD sc-cidDSM hGZPxu fhPxtY"><p>ID of the uploaded file</p>
</div></div></div></td></tr></tbody></table></div><div><h3 class="sc-fIosxK bTvSgn">Responses</h3><div><button class="sc-htJRVC hoRAnv"><svg class="sc-egiyK bPEzCN" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg><strong class="sc-fXeWAj jHtNTU">200<!-- --> </strong><span class="sc-jcFjpl eahewB"><p>File is downloaded successfully</p>
</span></button></div><div><button class="sc-htJRVC wltdp"><svg class="sc-egiyK FBjwd" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg><strong class="sc-fXeWAj jHtNTU">404<!-- --> </strong><span class="sc-jcFjpl eahewB"><p>File not found</p>
</span></button></div></div></div><div class="sc-jRQBWg sc-gKclnd vSqXI dKDnzb"><div class="sc-FNXRL jYAhkx"><button class="sc-eFegNN bxamQ"><span type="get" class="sc-fmBCVi hYmQQT http-verb get">get</span><span class="sc-jWUzzU hxZHzL">/download/{file-id}</span><svg class="sc-egiyK laPRNF" style="margin-right:-25px" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg></button><div aria-hidden="true" class="sc-lkgTHX fuqHqW"><div class="sc-jlRLRk fUpXCf"><div class="sc-iJKOTD sc-cidDSM hGZPxu fhPxtY"></div><div tabindex="0" role="button"><div class="sc-dUbtfd ggmziU"><span>http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com</span>/download/{file-id}</div></div></div></div></div><div><h3 class="sc-kDTinF hwMGJl"> <!-- -->Request samples<!-- --> </h3><div class="sc-cxpSdN eCLDJY" data-rttabs="true"><ul class="react-tabs__tab-list" role="tablist"><li class="react-tabs__tab react-tabs__tab--selected" role="tab" id="react-tabs-20" aria-selected="true" aria-disabled="false" aria-controls="react-tabs-21" tabindex="0" data-rttab="true">cURL</li><li class="react-tabs__tab" role="tab" id="react-tabs-22" aria-selected="false" aria-disabled="false" aria-controls="react-tabs-23" data-rttab="true">Python</li><li class="react-tabs__tab" role="tab" id="react-tabs-24" aria-selected="false" aria-disabled="false" aria-controls="react-tabs-25" data-rttab="true">Java</li></ul><div class="react-tabs__tab-panel react-tabs__tab-panel--selected" role="tabpanel" id="react-tabs-21" aria-labelledby="react-tabs-20"><div class="sc-ezbkAF flfPA"><div class="sc-giYglK gjxyHD"><button><div class="sc-caiLqq ddxnzs">Copy</div></button></div><pre class="sc-bYoBSM sc-kLwhqv kQTUkh fHMTIq">curl http<span class="token punctuation">:</span><span class="token operator">/</span><span class="token operator">/</span>ec2<span class="token operator">-</span><span class="token number">52</span><span class="token operator">-</span><span class="token number">67</span><span class="token operator">-</span><span class="token number">249</span><span class="token operator">-</span><span class="token number">109.</span>sa<span class="token operator">-</span>east<span class="token operator">-</span><span class="token number">1.</span>compute<span class="token punctuation">.</span>amazonaws<span class="token punctuation">.</span>com<span class="token punctuation">:</span><span class="token number">8080</span><span class="token operator">/</span>download<span class="token operator">/</span><span class="token punctuation">{</span>file<span class="token operator">-</span>id<span class="token punctuation">}</span></pre></div></div><div class="react-tabs__tab-panel" role="tabpanel" id="react-tabs-23" aria-labelledby="react-tabs-22"></div><div class="react-tabs__tab-panel" role="tabpanel" id="react-tabs-25" aria-labelledby="react-tabs-24"></div></div></div><div><h3 class="sc-kDTinF hwMGJl"> <!-- -->Response samples<!-- --> </h3><div class="sc-cxpSdN eCLDJY" data-rttabs="true"><ul class="react-tabs__tab-list" role="tablist"><li class="tab-error react-tabs__tab--selected" role="tab" id="react-tabs-26" aria-selected="true" aria-disabled="false" aria-controls="react-tabs-27" tabindex="0" data-rttab="true">404</li></ul><div class="react-tabs__tab-panel react-tabs__tab-panel--selected" role="tabpanel" id="react-tabs-27" aria-labelledby="react-tabs-26"><div><div class="sc-AjmGg bcpfGN"><span class="sc-cNKqjZ iYcnri">Content type</span><div class="sc-bBHHxi eidhyg">application/json</div></div><div class="sc-jgrJph iUheaL"><div class="sc-jObWnj jOBPNj"><div class="sc-giYglK gjxyHD"><button><div class="sc-caiLqq ddxnzs">Copy</div></button></div><div class="sc-iJKOTD hGZPxu sc-dPiLbb sRoPx"><div class="redoc-json"><code><button class="collapser" aria-label="collapse"></button><span class="token punctuation">{</span><span class="ellipsis"></span><ul class="obj collapsible"><li><div class="hoverable "><span class="property token string">"error"</span>: <span class="token string">&quot;File Not Found&quot;</span></div></li></ul><span class="token punctuation">}</span></code></div></div></div></div></div></div></div></div></div></div></div><div id="tag/download/paths/~1download~1{file-id}/head" data-section-id="tag/download/paths/~1download~1{file-id}/head" class="sc-eCImPb hexvPn"><div class="sc-iCfMLu jTXZbd"><div class="sc-hKwDye fcjMZs"><h2 class="sc-pVTFL QwiBS"><a class="sc-crHmcD bNUQy" href="#tag/download/paths/~1download~1{file-id}/head" aria-label="tag/download/paths/~1download~1{file-id}/head"></a>Get file information by ID<!-- --> </h2><div class="sc-iFMAIt ilWCwE"><div class="sc-iJKOTD sc-cidDSM hGZPxu fYaHea"><p>Retrieves file information by its ID.</p>
</div></div><div><h5 class="sc-iqseJM kyZwVG">path<!-- --> Parameters</h5><table class="sc-hGPBjI wbnF"><tbody><tr class="last "><td class="sc-hBUSln sc-fFeiMQ kCCtqV fwnkRw" kind="field" title="file-id"><span class="sc-ieecCq fMdASL"></span><span class="property-name">file-id</span><div class="sc-nVkyK sc-hiwPVj eyZzuM eSyGZd">required</div></td><td class="sc-bkkeKt fOwWgB"><div><div><span class="sc-lbhJGD sc-iNGGcK gHbDui eLMLxg"></span><span class="sc-lbhJGD sc-jeraig gHbDui ifsMbX">string</span></div> <div><div class="sc-iJKOTD sc-cidDSM hGZPxu fhPxtY"><p>ID of the uploaded file</p>
</div></div></div></td></tr></tbody></table></div><div><h3 class="sc-fIosxK bTvSgn">Responses</h3><div><button class="sc-htJRVC hoRAnv"><svg class="sc-egiyK bPEzCN" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg><strong class="sc-fXeWAj jHtNTU">200<!-- --> </strong><span class="sc-jcFjpl eahewB"><p>File information returned successfully</p>
</span></button></div><div><button class="sc-htJRVC wltdp"><svg class="sc-egiyK FBjwd" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg><strong class="sc-fXeWAj jHtNTU">404<!-- --> </strong><span class="sc-jcFjpl eahewB"><p>File not found</p>
</span></button></div></div></div><div class="sc-jRQBWg sc-gKclnd vSqXI dKDnzb"><div class="sc-FNXRL jYAhkx"><button class="sc-eFegNN bxamQ"><span type="head" class="sc-fmBCVi iKSThS http-verb head">head</span><span class="sc-jWUzzU hxZHzL">/download/{file-id}</span><svg class="sc-egiyK laPRNF" style="margin-right:-25px" version="1.1" viewBox="0 0 24 24" x="0" xmlns="http://www.w3.org/2000/svg" y="0" aria-hidden="true"><polygon points="17.3 8.3 12 13.6 6.7 8.3 5.3 9.7 12 16.4 18.7 9.7 "></polygon></svg></button><div aria-hidden="true" class="sc-lkgTHX fuqHqW"><div class="sc-jlRLRk fUpXCf"><div class="sc-iJKOTD sc-cidDSM hGZPxu fhPxtY"></div><div tabindex="0" role="button"><div class="sc-dUbtfd ggmziU"><span>http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com</span>/download/{file-id}</div></div></div></div></div><div><h3 class="sc-kDTinF hwMGJl"> <!-- -->Request samples<!-- --> </h3><div class="sc-cxpSdN eCLDJY" data-rttabs="true"><ul class="react-tabs__tab-list" role="tablist"><li class="react-tabs__tab react-tabs__tab--selected" role="tab" id="react-tabs-28" aria-selected="true" aria-disabled="false" aria-controls="react-tabs-29" tabindex="0" data-rttab="true">cURL</li><li class="react-tabs__tab" role="tab" id="react-tabs-30" aria-selected="false" aria-disabled="false" aria-controls="react-tabs-31" data-rttab="true">Python</li><li class="react-tabs__tab" role="tab" id="react-tabs-32" aria-selected="false" aria-disabled="false" aria-controls="react-tabs-33" data-rttab="true">Java</li></ul><div class="react-tabs__tab-panel react-tabs__tab-panel--selected" role="tabpanel" id="react-tabs-29" aria-labelledby="react-tabs-28"><div class="sc-ezbkAF flfPA"><div class="sc-giYglK gjxyHD"><button><div class="sc-caiLqq ddxnzs">Copy</div></button></div><pre class="sc-bYoBSM sc-kLwhqv kQTUkh fHMTIq">curl <span class="token operator">-</span>I http<span class="token punctuation">:</span><span class="token operator">/</span><span class="token operator">/</span>ec2<span class="token operator">-</span><span class="token number">52</span><span class="token operator">-</span><span class="token number">67</span><span class="token operator">-</span><span class="token number">249</span><span class="token operator">-</span><span class="token number">109.</span>sa<span class="token operator">-</span>east<span class="token operator">-</span><span class="token number">1.</span>compute<span class="token punctuation">.</span>amazonaws<span class="token punctuation">.</span>com<span class="token punctuation">:</span><span class="token number">8080</span><span class="token operator">/</span>download<span class="token operator">/</span><span class="token punctuation">{</span>file<span class="token operator">-</span>id<span class="token punctuation">}</span></pre></div></div><div class="react-tabs__tab-panel" role="tabpanel" id="react-tabs-31" aria-labelledby="react-tabs-30"></div><div class="react-tabs__tab-panel" role="tabpanel" id="react-tabs-33" aria-labelledby="react-tabs-32"></div></div></div><div><h3 class="sc-kDTinF hwMGJl"> <!-- -->Response samples<!-- --> </h3><div class="sc-cxpSdN eCLDJY" data-rttabs="true"><ul class="react-tabs__tab-list" role="tablist"><li class="tab-error react-tabs__tab--selected" role="tab" id="react-tabs-34" aria-selected="true" aria-disabled="false" aria-controls="react-tabs-35" tabindex="0" data-rttab="true">404</li></ul><div class="react-tabs__tab-panel react-tabs__tab-panel--selected" role="tabpanel" id="react-tabs-35" aria-labelledby="react-tabs-34"><div><div class="sc-AjmGg bcpfGN"><span class="sc-cNKqjZ iYcnri">Content type</span><div class="sc-bBHHxi eidhyg">application/json</div></div><div class="sc-jgrJph iUheaL"><div class="sc-jObWnj jOBPNj"><div class="sc-giYglK gjxyHD"><button><div class="sc-caiLqq ddxnzs">Copy</div></button></div><div class="sc-iJKOTD hGZPxu sc-dPiLbb sRoPx"><div class="redoc-json"><code><button class="collapser" aria-label="collapse"></button><span class="token punctuation">{</span><span class="ellipsis"></span><ul class="obj collapsible"><li><div class="hoverable "><span class="property token string">"error"</span>: <span class="token string">&quot;File Not Found&quot;</span></div></li></ul><span class="token punctuation">}</span></code></div></div></div></div></div></div></div></div></div></div></div></div><div class="sc-eldieg bLydqy"></div></div></div>
      <script>
      const __redoc_state = {"menu":{"activeItemIdx":-1},"spec":{"data":{"openapi":"3.0.0","info":{"description":"This API provides a  solution for transferring files over the network. This API was build using clojure Pedestal API, which is a a set of libraries that we use to build services and applications.\nSome useful links:\n- [NuTBox repository](https://github.com/nufuturo-ufcg/nutbox-backend)\n- [Pedestal API](http://pedestal.io/)\n","version":"1.0.0","title":"Nutbox","contact":{"email":"nutbox@nutufuro.com"}},"tags":[{"name":"home-page","description":"Home Page"},{"name":"about-page","description":"About Page"},{"name":"upload","description":""},{"name":"download","description":"File Download"}],"paths":{"/":{"get":{"tags":["home-page"],"summary":"Hello World!","description":"Returns the \"Hello World!\" message.","responses":{"200":{"description":"Successful operation"}},"x-code-samples":[{"lang":"cURL","source":"curl http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com/"},{"lang":"Python","source":"import requests\n\nresponse = requests.get('http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com/')\nprint(response.text)"},{"lang":"Java","source":"import java.io.IOException;\nimport java.io.InputStream;\nimport java.net.HttpURLConnection;\nimport java.net.URL;\nimport java.util.Scanner;\n\npublic class Main {\n\n    public static void main(String[] args) throws IOException {\n        URL url = new URL(\"http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com:8080/\");\n        HttpURLConnection httpConn = (HttpURLConnection) url.openConnection();\n        httpConn.setRequestMethod(\"GET\");\n\n        InputStream responseStream = httpConn.getResponseCode() / 100 == 2\n                ? httpConn.getInputStream()\n                : httpConn.getErrorStream();\n        Scanner s = new Scanner(responseStream).useDelimiter(\"\\\\A\");\n        String response = s.hasNext() ? s.next() : \"\";\n        System.out.println(response);\n    }\n}"}]}},"/about":{"get":{"tags":["about-page"],"summary":"Clojure version","description":"Returns the current Clojure version.","responses":{"200":{"description":"Successful operation"}},"x-code-samples":[{"lang":"cURL","source":"curl http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com:8080/about"},{"lang":"Python","source":"import requests\n\nresponse = requests.get('http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com/about')\nprint(response.text)"},{"lang":"Java","source":"import java.io.IOException;\nimport java.io.InputStream;\nimport java.net.HttpURLConnection;\nimport java.net.URL;\nimport java.util.Scanner;\n\npublic class Main {\n\n    public static void main(String[] args) throws IOException {\n        URL url = new URL(\"http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com:8080/about\");\n        HttpURLConnection httpConn = (HttpURLConnection) url.openConnection();\n        httpConn.setRequestMethod(\"GET\");\n\n        InputStream responseStream = httpConn.getResponseCode() / 100 == 2\n                ? httpConn.getInputStream()\n                : httpConn.getErrorStream();\n        Scanner s = new Scanner(responseStream).useDelimiter(\"\\\\A\");\n        String response = s.hasNext() ? s.next() : \"\";\n        System.out.println(response);\n    }\n}"}]}},"/upload":{"post":{"tags":["upload"],"summary":"Upload a file","description":"Uploads a file using multipart form data.","requestBody":{"content":{"multipart/form-data":{"schema":{"type":"object","properties":{"file":{"description":"The file to upload","type":"string","format":"binary"}},"required":["file"]}}},"required":true},"responses":{"200":{"description":"Successful operation","content":{"application/json":{"schema":{"$ref":"#/components/schemas/inline_response_200"}}}},"400":{"description":"File Not Uploaded"}},"x-code-samples":[{"lang":"cURL","source":"curl -X POST -H 'content-type: multipart/form-data' -F 'file=@<path-to-your-file>' http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com:8080/upload"},{"lang":"Python","source":"import requests\n\nurl = 'http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com/upload'\nfiles = {'file': open('/path/to/file', 'rb')}\nresponse = requests.post(url, files=files)\nprint(response.json())"},{"lang":"Java","source":"import java.io.IOException;\nimport java.io.InputStream;\nimport java.net.HttpURLConnection;\nimport java.net.URL;\nimport java.util.Scanner;\n\npublic class Main {\n\n    public static void main(String[] args) throws IOException {\n        URL url = new URL(\"http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com:8080/upload\");\n        HttpURLConnection httpConn = (HttpURLConnection) url.openConnection();\n        httpConn.setRequestMethod(\"POST\");\n\n        httpConn.setRequestProperty(\"content-type\", \"multipart/form-data\");\n\n        InputStream responseStream = httpConn.getResponseCode() / 100 == 2\n                ? httpConn.getInputStream()\n                : httpConn.getErrorStream();\n        Scanner s = new Scanner(responseStream).useDelimiter(\"\\\\A\");\n        String response = s.hasNext() ? s.next() : \"\";\n        System.out.println(response);\n    }\n}"}]}},"/download/{file-id}":{"get":{"tags":["download"],"summary":"Download file by ID","description":"Downloads a file by its ID.","parameters":[{"name":"file-id","in":"path","description":"ID of the uploaded file","required":true,"schema":{"type":"string"}}],"responses":{"200":{"description":"File is downloaded successfully","headers":{"Content-Type":{"description":"MIME type of the file","schema":{"type":"string"}},"Content-Disposition":{"description":"Name of the file to be downloaded","schema":{"type":"string"}}}},"404":{"description":"File not found","content":{"application/json":{"schema":{"$ref":"#/components/schemas/inline_response_404"}}}}},"x-code-samples":[{"lang":"cURL","source":"curl http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com:8080/download/{file-id}"},{"lang":"Python","source":"import requests\n\nfile_id = 'your_file_id'\nurl = f'http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com/download/{file_id}'\nresponse = requests.get(url)\n\nwith open('downloaded_file', 'wb') as f:\n    f.write(response.content)\nprint('File downloaded successfully')"},{"lang":"Java","source":"import java.io.IOException;\nimport java.io.InputStream;\nimport java.net.HttpURLConnection;\nimport java.net.URL;\nimport java.util.Scanner;\n\npublic class Main {\n\n    public static void main(String[] args) throws IOException {\n        URL url = new URL(\"http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com:8080/download/{file-id}\");\n        HttpURLConnection httpConn = (HttpURLConnection) url.openConnection();\n        httpConn.setRequestMethod(\"GET\");\n\n        InputStream responseStream = httpConn.getResponseCode() / 100 == 2\n                ? httpConn.getInputStream()\n                : httpConn.getErrorStream();\n        Scanner s = new Scanner(responseStream).useDelimiter(\"\\\\A\");\n        String response = s.hasNext() ? s.next() : \"\";\n        System.out.println(response);\n    }\n}"}]},"head":{"tags":["download"],"summary":"Get file information by ID","description":"Retrieves file information by its ID.","parameters":[{"name":"file-id","in":"path","description":"ID of the uploaded file","required":true,"schema":{"type":"string"}}],"responses":{"200":{"description":"File information returned successfully","headers":{"Content-Length":{"description":"Size of the file in bytes","schema":{"type":"string"}},"Content-Disposition":{"description":"Name of the file","schema":{"type":"string"}}}},"404":{"description":"File not found","content":{"application/json":{"schema":{"$ref":"#/components/schemas/inline_response_404"}}}}},"x-code-samples":[{"lang":"cURL","source":"curl -I http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com:8080/download/{file-id}"},{"lang":"Python","source":"import requests\n\nfile_id = 'your_file_id'\nurl = f'http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com/download/{file_id}'\nresponse = requests.head(url)\n\nprint(response.headers)"},{"lang":"Java","source":"import java.io.IOException;\nimport java.io.InputStream;\nimport java.net.HttpURLConnection;\nimport java.net.URL;\nimport java.util.Scanner;\n\npublic class Main {\n\n    public static void main(String[] args) throws IOException {\n        URL url = new URL(\"http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com:8080/download/{file-id}\");\n        HttpURLConnection httpConn = (HttpURLConnection) url.openConnection();\n        httpConn.setRequestMethod(\"HEAD\");\n\n        InputStream responseStream = httpConn.getResponseCode() / 100 == 2\n                ? httpConn.getInputStream()\n                : httpConn.getErrorStream();\n        Scanner s = new Scanner(responseStream).useDelimiter(\"\\\\A\");\n        String response = s.hasNext() ? s.next() : \"\";\n        System.out.println(response);\n    }\n}"}]}}},"externalDocs":{"description":"Find out more about Swagger","url":"http://swagger.io"},"servers":[{"url":"http://ec2-52-67-249-109.sa-east-1.compute.amazonaws.com"}],"components":{"schemas":{"inline_response_200":{"type":"object","properties":{"data":{"type":"string","description":"Link to the uploaded file"}}},"inline_response_404":{"type":"object","properties":{"error":{"type":"string","example":"File Not Found"}}}}}}},"searchIndex":{"store":["tag/home-page","tag/home-page/paths/~1/get","tag/about-page","tag/about-page/paths/~1about/get","tag/upload","tag/upload/paths/~1upload/post","tag/download","tag/download/paths/~1download~1{file-id}/get","tag/download/paths/~1download~1{file-id}/head"],"index":{"version":"2.3.9","fields":["title","description"],"fieldVectors":[["title/0",[0,2.311]],["description/0",[1,2.268,2,1.658]],["title/1",[3,1.319,4,1.319]],["description/1",[3,1.151,4,1.151,5,1.151,6,1.575,7,1.575]],["title/2",[8,2.311]],["description/2",[2,1.943]],["title/3",[9,1.319,10,1.319]],["description/3",[5,1.281,9,1.281,10,1.281,11,1.754]],["title/4",[12,1.279]],["description/4",[]],["title/5",[12,0.999,13,0.274]],["description/5",[12,1.102,13,0.198,14,1.308,15,1.308,16,1.308,17,1.308]],["title/6",[18,0.973]],["description/6",[13,0.344,18,0.955]],["title/7",[13,0.225,18,0.623,19,0.623]],["description/7",[13,0.266,18,0.738,19,0.738,20,1.281]],["title/8",[13,0.225,19,0.623,21,1.082]],["description/8",[13,0.239,19,0.663,20,1.151,21,1.151,22,1.575]]],"invertedIndex":[["",{"_index":7,"title":{},"description":{"1":{}}}],["about-pag",{"_index":8,"title":{"2":{}},"description":{}}],["clojur",{"_index":9,"title":{"3":{}},"description":{"3":{}}}],["current",{"_index":11,"title":{},"description":{"3":{}}}],["data",{"_index":17,"title":{},"description":{"5":{}}}],["download",{"_index":18,"title":{"6":{},"7":{}},"description":{"6":{},"7":{}}}],["download/{file-id",{"_index":20,"title":{},"description":{"7":{},"8":{}}}],["file",{"_index":13,"title":{"5":{},"7":{},"8":{}},"description":{"5":{},"6":{},"7":{},"8":{}}}],["form",{"_index":16,"title":{},"description":{"5":{}}}],["hello",{"_index":3,"title":{"1":{}},"description":{"1":{}}}],["home",{"_index":1,"title":{},"description":{"0":{}}}],["home-pag",{"_index":0,"title":{"0":{}},"description":{}}],["id",{"_index":19,"title":{"7":{},"8":{}},"description":{"7":{},"8":{}}}],["inform",{"_index":21,"title":{"8":{}},"description":{"8":{}}}],["messag",{"_index":6,"title":{},"description":{"1":{}}}],["multipart",{"_index":15,"title":{},"description":{"5":{}}}],["page",{"_index":2,"title":{},"description":{"0":{},"2":{}}}],["retriev",{"_index":22,"title":{},"description":{"8":{}}}],["return",{"_index":5,"title":{},"description":{"1":{},"3":{}}}],["upload",{"_index":12,"title":{"4":{},"5":{}},"description":{"5":{}}}],["us",{"_index":14,"title":{},"description":{"5":{}}}],["version",{"_index":10,"title":{"3":{}},"description":{"3":{}}}],["world",{"_index":4,"title":{"1":{}},"description":{"1":{}}}]],"pipeline":[]}},"options":{}};

      var container = document.getElementById('redoc');
      Redoc.hydrate(__redoc_state, container);

      </script>
</body>

</html>
