# excel_macro

```
/* *{margin:0;padding:0;} */
body {
	font:14px Roboto,helvetica,arial,freesans,clean,sans-serif;
  color:black;
	line-height:1.6em;
	background-color: #F8F8F8;
	padding: 1.5em;
}
p {
	margin:1em 0em;
	line-height:1.5em;
}
table {
	font-size:inherit;
	font:100%;
	margin:1em;
	border-collapse: collapse;
}
table th{border:1px solid #bbb;padding:.2em 1em;}
table td{border:1px solid #ddd;padding:.2em 1em;}
table tr:nth-child(even) td {
    background: #f0f0f0;
}
input[type=text],input[type=password],input[type=image],textarea{font:99% helvetica,arial,freesans,sans-serif;}
select,option{padding:0 .25em;}
optgroup{margin-top:.5em;}
pre,code{font:14px "Migu 1M","Courier New","DejaVu Sans Mono","Bitstream Vera Sans Mono",monospace;}
pre {
	margin:1em 0;
	font-size:14px;
	background-color:#eee;
	border:1px solid #ddd;
	padding:5px;
	line-height:1.5em;
	color:#444;
	overflow:auto;
	-webkit-box-shadow:rgba(0,0,0,0.07) 0 1px 2px inset;
	-webkit-border-radius:3px;
	-moz-border-radius:3px;border-radius:3px;
}
pre code {
	padding:0;
	font-size:14px;
	background-color:#eee;
	border:none;
}
code {
	font-size:14px;
	background-color:#eee;
	color:#444;
	padding:0 .2em;
	border:1px solid #dedede;
}
img{border:0;max-width:100%;}
abbr{border-bottom:none;}
a{color:#4183c4;text-decoration:none;}
a:hover{text-decoration:underline;}
a code,a:link code,a:visited code{color:#4183c4;}
/* h2,h3{margin:1em 0;} */
/* h1,h2,h3,h4,h5,h6{border:0;} */
/* h1{font-size:200%;border-top:4px solid #aaa;padding-top:1.0em;margin-top:1.5em;} */
/* h1:first-child{margin-top:0;padding-top:.25em;border-top:none;} */
/* h2{font-size:170%;margin-top:1.5em;border-bottom:1px solid #ddd;padding-bottom:.5em;} */
/* h3{font-size:130%;margin-top:1em;} */
/* h4{font-size:100%;margin-top:1em;} */
hr{height:0;margin:15px 0;overflow:hidden;background:transparent;border:0;border-bottom:4px solid #ddd;}
ul{margin:1em 0 1em 0.5em;padding-left: 1.0em;}
ol{margin:1em 0 1em 0.5em;padding-left: 1.0em;}
/* ul li,ol li{margin-top:.5em;margin-bottom:.5em;} */
ul ul,ul ol,ol ol,ol ul{margin-top:0;margin-bottom:0;}
blockquote{margin:1em 0;border-left:5px solid #ddd;padding-left:.6em;color:#555;}
dt{font-weight:bold;margin-left:1em;}
dd{margin-left:2em;margin-bottom:1em;}
@media screen and (min-width: 768px) {
    body {
        width: 748px;
        margin:10px auto;
        border: 1px solid #00A0A0;
    }
}

/*
github.css
github.com style (c) Vasily Polovnyov <vast@whiteants.net>

*/


.hljs {
  display: block;
  overflow-x: auto;
  padding: 0.5em;
  color: #333;
  background: #f8f8f8;
}

.hljs-comment,
.hljs-quote {
  color: #998;
  font-style: italic;
}

.hljs-keyword,
.hljs-selector-tag,
.hljs-subst {
  color: #333;
  font-weight: normal;
}

.hljs-number,
.hljs-literal,
.hljs-variable,
.hljs-template-variable,
.hljs-tag .hljs-attr {
  color: #008080;
}

.hljs-string,
.hljs-doctag {
  color: #d14;
}

.hljs-title,
.hljs-section,
.hljs-selector-id {
  color: #900;
  font-weight: bold;
}

.hljs-subst {
  font-weight: normal;
}

.hljs-type,
.hljs-class .hljs-title {
  color: #458;
  font-weight: bold;
}

.hljs-tag,
.hljs-name,
.hljs-attribute {
  color: #000080;
  font-weight: normal;
}

.hljs-regexp,
.hljs-link {
  color: #009926;
}

.hljs-symbol,
.hljs-bullet {
  color: #990073;
}

.hljs-built_in,
.hljs-builtin-name {
  color: #0086b3;
}

.hljs-meta {
  color: #999;
  font-weight: bold;
}

.hljs-deletion {
  background: #fdd;
}

.hljs-addition {
  background: #dfd;
}

.hljs-emphasis {
  font-style: italic;
}

.hljs-strong {
  font-weight: bold;
}


html body h1 {
  counter-reset: h2counter;

  font-size:250%;
/*  color: #00A0A0; */
  color: #FFFFFF;
  border-left: 4px solid #00A0A0;
  border-bottom: 1px solid #00A0A0;
  border-right: 1px solid #00A0A0;
  border-top: 1px solid #00A0A0;
  padding: 16px 0 16px 0.5em;
/*  background: #D0F0F0; */
  background: #00A0A0;

}
html body h2 {
  counter-increment: h2counter;
  counter-reset: h3counter;

  font-size:170%;
  color: #00A0A0;
  border-left: 9px solid #00A0A0;
  border-bottom: 1px solid #00A0A0;
  padding: 4px 0 4px 0.5em; 
/*  background: #D0F0F0; */

}
html body h3 {
  counter-increment: h3counter;
  counter-reset: h4counter;

  font-size:130%;
  color: #00A0A0;
  border-left: 9px solid #00A0A0;
  border-bottom: 1px solid #00A0A0;
  padding: 1px 0 1px 0.5em;
}
html body h4 {
  counter-increment: h4counter;

  font-size:100%;
  color: #00A0A0;
  border-left: 9px solid #00A0A0;
  border-bottom: 1px solid #00A0A0;
  padding: 0px 0 0px 0.5em;
}
html body h2:before {
/*  content: counter(h2counter) ". "; */
  content: counter(h2counter) " ";
}
html body h3:before {
/*  content: counter(h2counter) ". " counter(h3counter) ". "; */
  content: counter(h2counter) ". " counter(h3counter) " ";
}
html body h4:before {
/*  content: counter(h2counter) ". " counter(h3counter) ". " counter(h4counter) ". "; */
  content: counter(h2counter) ". " counter(h3counter) ". " counter(h4counter) " ";
}
html body .slides {
  font-size: 25px;
}
html body .slides ul,
html body .slides ol,
html body .slides li {
  display: block;
}
html body .slides p,
html body .slides ol,
html body .slides li,
html body .slides h1,
html body .slides h2,
html body .slides h3,
html body .slides h4,
html body .slides h5,
html body .slides h6 {
  text-transform: none;
  text-align: left;
}
html body .slides h2:before,
html body .slides h3:before,
html body .slides h4:before,
html body .slides h5:before,
html body .slides h6:before {
  content: "";
}
html body .slides table {
  width: 90%;
  border: solid;
}
html body .slides th,
html body .slides td {
  word-break: break-all;
  font-size: 20px !important;
  border: solid;
}

```
