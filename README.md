# ramona94


/* ---------- misc ---------- */

* {
 padding: 0;
 margin: 0;
 border: 0;
 }
body	{
 background: #eee url(body.gif) no-repeat 50% 100%;
 color: #666; 
 font: 11px/1.3em Arial, Tahoma, sans-serif;
 text-align: center;
 }
abbr {
 cursor: help;
 }

/* ---------- div ---------- */

.page-wrapper {
 margin: 30px auto;
 border: 1px solid #ddd;
 background: transparent url(container.gif) repeat-y 50% 50%;
 text-align: left;
 width: 448px !important;
 width /**/:450px;
 }
.intro {
 background: transparent url(intro.gif) no-repeat 0 0;
 }
.page-wrapper, .intro {
 position: relative;
 }
header {
 width: 448px;
 height: 260px;
 }
.preamble, .supporting {
 width: 303px;
 }
.supporting {
 background: transparent url(supportingText.gif) no-repeat 0 100%;
 width: 448px;
 }
.explanation {
 background: transparent url(explanation.gif) no-repeat 0 50%;
 }
.participation {
 background: transparent url(participation.gif) no-repeat 0 80%;
 }
.benefits {
 background: transparent url(benefits.gif) no-repeat 0 100%;
 }
.requirements {
 padding-bottom: 2px;
 }
footer {
 text-align: center;
 font: 10px/33px Tahoma, Arial, sans-serif;
 width: 100%;
 height: 35px;
 }
.summary, .sidebar {
 position: absolute;
 left: 303px;
 width: 140px;
 font: 10px/1.3em Arial, Tahoma, sans-serif;
 }
.summary {
 top: 260px;
 padding-top: 18px;
 }
.sidebar {
 top: 420px;
 }
.sidebar div {
 text-align: center;
 }
.design-selection, .design-archives, .zen-resources {
 padding: 5px 0 10px;
 }

/* ---------- h3 ---------- */

h3	{
 margin: 7px 15px 3px;
 background-position: 0 0;
 background-repeat: no-repeat;
 text-indent: -9999em;
 font: 1px/1px sans-serif; /* stop IE from revealing unnecessary bg */
 width: 273px;
 height: 28px;
 }
.preamble h3 {
 margin-top: 13px;
 background-image: url(h3_01.gif);
 }
.explanation h3 {
 background-image: url(h3_02.gif);
 }
.participation h3 {
 background-image: url(h3_03.gif);
 }
.benefits h3 {
 background-image: url(h3_04.gif);
 }
.requirements h3 {
 background-image: url(h3_05.gif);
 }
.sidebar h3 {
 margin: 0 10px;
 width: 120px;
 height: 10px;
 }
.select {
 background-image: url(h3_06.gif);
 }
.archives {
 background-image: url(h3_07.gif);
 }
.resources {
 background-image: url(h3_08.gif);
 }

/* ---------- p ---------- */

p {
 padding: 0 15px 5px;
 text-align: justify;
 }
.supporting p {
 margin-right: 145px;
 }
.summary p {
 padding: 3px 12px 0;
 text-align: left;
 }

/* ---------- a ---------- */

a {
 text-decoration: none;
 }
a:link, a:visited {
 color: #666;
 }
a:hover, a:active {
 color: #000;
 }
.supporting a {
 font-weight: bold;
 }
footer a {
 padding: 0 1px;
 font-weight: normal;
 }
.summary a:link, .summary a:visited, footer a:link, footer a:visited {
 border-bottom: 1px dotted #888;
 }
.summary a:hover, .summary a:active, footer a:hover, footer a:active {
 border-bottom: 1px dotted #222;
 }
.sidebar a:link, .sidebar a:visited {
 text-transform: lowercase;
 color: #888;
 }
.design-selection a:link.c, .design-selection a.designer-name:visited {
 display: inline;
 color: #666;
 }
.sidebar a:hover, .sidebar a:active, .design-selection a.designer-name:hover, .design-selection a.designer-name:active {
 color: #000;
 }
.design-selection a {
 display: block;
 text-transform: lowercase;
 }

/* ---------- ul, li ---------- */

ul {
 margin: 5px 10px 0;
 border-top: 1px solid #ddd;
 text-align: left;
 list-style: none;
 }
li {
 padding: 3px 0 3px 20px;
 border-bottom: 1px solid #ddd;
 background-repeat: no-repeat;
 background-position: 6px 5px;
 display: block;
 list-style: none;
 }
li:hover {
 background-color: #f3f3f3;
 }
.design-selection li {
 background-image: url(designs.gif);
 }
.design-archives li {
 background-image: url(archives.gif);
 }
.zen-resources li {
 background-image: url(resources.gif);
 }

/* ---------- the unused ---------- */

h1, h2, extra1, extra2, extra3, extra4, extra5, extra6 {
 display: none;
 }
