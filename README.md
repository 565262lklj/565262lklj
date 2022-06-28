<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' expr:lang='data:blog.locale' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
        <!--inicio efeito -->
    <script src='http://ajax.googleapis.com/ajax/libs/jquery/2.0.3/jquery.min.js'/>
    <link href='https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css' rel='stylesheet'/>
         <!--fim efeito -->
    <meta expr:content='data:blog.isMobile         ? &quot;width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=5.0&quot;         : &quot;width=1100&quot;' name='viewport'/>
    <b:include data='blog' name='all-head-content'/>
    <title><data:blog.pageTitle/></title>

    <b:skin><![CDATA[/*-----------------------------------------------

Blogger Template Style
Name:     Picture Window
Designer: Blogger
URL:      www.blogger.com
----------------------------------------------- */

/* Variable definitions
   ====================
   <Variable name="keycolor" description="Main Color" type="color" default="#1a222a" value="#ff9900"/>
   <Variable name="body.background" description="Body Background" type="background"
       color="$(body.background.color)" default="#111111 url(//themes.googleusercontent.com/image?id=1OACCYOE0-eoTRTfsBuX1NMN9nz599ufI1Jh0CggPFA_sK80AGkIr8pLtYRpNUKPmwtEa) repeat-x fixed top center" value="#fafafa url(//themes.googleusercontent.com/image?id=1iJBX-a-hBX2tKaDdERpElPUmvb4r5MDX9lEx06AA-UtZIQCYziZg3PFbmOyt-g2sH8Jo) repeat-x fixed top center"/>

   <Group description="Page Text" selector="body">
     <Variable name="body.font" description="Font" type="font"
         default="normal normal 15px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal normal 15px Arial, Tahoma, Helvetica, FreeSans, sans-serif"/>
     <Variable name="body.text.color" description="Text Color" type="color" default="#333333" value="#000000"/>
   </Group>

   <Group description="Backgrounds" selector=".body-fauxcolumns-outer">
     <Variable name="body.background.color" description="Outer Background" type="color" default="#296695" value="transparent"/>
     <Variable name="header.background.color" description="Header Background" type="color" default="transparent" value="transparent"/>
     <Variable name="post.background.color" description="Post Background" type="color" default="#ffffff" value="#EEEEEE"/>
   </Group>

   <Group description="Links" selector=".main-outer">
     <Variable name="link.color" description="Link Color" type="color" default="#336699" value="#000000"/>
     <Variable name="link.visited.color" description="Visited Color" type="color" default="#6699cc" value="#000000"/>
     <Variable name="link.hover.color" description="Hover Color" type="color" default="#33aaff" value="#dd7700"/>
   </Group>

   <Group description="Blog Title" selector=".header h1">
     <Variable name="header.font" description="Title Font" type="font"
         default="normal normal 36px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal normal 48px Georgia, Utopia, &#39;Palatino Linotype&#39;, Palatino, serif"/>
     <Variable name="header.text.color" description="Text Color" type="color" default="#ffffff"  value="#ffffff"/>
   </Group>

   <Group description="Tabs Text" selector=".tabs-inner .widget li a">
     <Variable name="tabs.font" description="Font" type="font"
         default="normal normal 15px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal normal 15px Georgia, Utopia, &#39;Palatino Linotype&#39;, Palatino, serif"/>
     <Variable name="tabs.text.color" description="Text Color" type="color" default="#ffffff" value="#ff9900"/>
     <Variable name="tabs.selected.text.color" description="Selected Color" type="color" default="$(link.color)" value="#ffffff"/>
   </Group>

   <Group description="Tabs Background" selector=".tabs-outer .PageList">
     <Variable name="tabs.background.color" description="Background Color" type="color" default="transparent" value="#1c1c1c"/>
     <Variable name="tabs.selected.background.color" description="Selected Color" type="color" default="transparent" value="#dd7700"/>
     <Variable name="tabs.separator.color" description="Separator Color" type="color" default="transparent" value="#000000"/>
   </Group>

   <Group description="Post Title" selector="h3.post-title, .comments h4">
     <Variable name="post.title.font" description="Title Font" type="font"
         default="normal normal 18px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="italic normal 25px Lobster"/>
   </Group>

   <Group description="Date Header" selector=".date-header">
     <Variable name="date.header.color" description="Text Color" type="color" default="$(body.text.color)" value="#000000"/>
   </Group>

   <Group description="Post" selector=".post">
     <Variable name="post.footer.text.color" description="Footer Text Color" type="color" default="#999999" value="#999999"/>
     <Variable name="post.border.color" description="Border Color" type="color" default="#dddddd" value="transparent"/>
   </Group>

   <Group description="Gadgets" selector="h2">
     <Variable name="widget.title.font" description="Title Font" type="font"
        default="bold normal 13px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal normal 18px Georgia, Utopia, &#39;Palatino Linotype&#39;, Palatino, serif"/>
     <Variable name="widget.title.text.color" description="Title Color" type="color" default="#888888" value="#ffffff"/>
   </Group>

   <Group description="Footer" selector=".footer-outer">
     <Variable name="footer.text.color" description="Text Color" type="color" default="#cccccc" value="#cccccc"/>
     <Variable name="footer.widget.title.text.color" description="Gadget Title Color" type="color" default="#aaaaaa" value="#ffffff"/>
   </Group>

   <Group description="Footer Links" selector=".footer-outer">
     <Variable name="footer.link.color" description="Link Color" type="color" default="#99ccee" value="#cccccc"/>
     <Variable name="footer.link.visited.color" description="Visited Color" type="color" default="#77aaee" value="#999999"/>
     <Variable name="footer.link.hover.color" description="Hover Color" type="color" default="#33aaff" value="#cccccc"/>
   </Group>

   <Variable name="content.margin" description="Content Margin Top" type="length" default="20px" min="0" max="100px" value="0"/>
   <Variable name="content.padding" description="Content Padding" type="length" default="0" min="0" max="100px" value="10px"/>
   <Variable name="content.background" description="Content Background" type="background"
       default="transparent none repeat scroll top left" value="transparent url(https://resources.blogblog.com/blogblog/data/1kt/transparent/black50.png) repeat scroll top left"/>
   <Variable name="content.border.radius" description="Content Border Radius" type="length" default="0" min="0" max="100px" value="0"/>
   <Variable name="content.shadow.spread" description="Content Shadow Spread" type="length" default="0" min="0" max="100px" value="3px"/>

   <Variable name="header.padding" description="Header Padding" type="length" default="0" min="0" max="100px" value="30px"/>
   <Variable name="header.background.gradient" description="Header Gradient" type="url"
       default="none" value="none"/>
   <Variable name="header.border.radius" description="Header Border Radius" type="length" default="0" min="0" max="100px" value="0"/>

   <Variable name="main.border.radius.top" description="Main Border Radius" type="length" default="20px" min="0" max="100px" value="0"/>
   <Variable name="footer.border.radius.top" description="Footer Border Radius Top" type="length" default="0" min="0" max="100px" value="0"/>
   <Variable name="footer.border.radius.bottom" description="Footer Border Radius Bottom" type="length" default="20px" min="0" max="100px" value="0"/>
   <Variable name="region.shadow.spread" description="Main and Footer Shadow Spread" type="length" default="3px" min="0" max="100px" value="0"/>
   <Variable name="region.shadow.offset" description="Main and Footer Shadow Offset" type="length" default="1px" min="-50px" max="50px" value="0"/>

   <Variable name="tabs.background.gradient" description="Tab Background Gradient" type="url" default="none" value="none"/>
   <Variable name="tab.selected.background.gradient" description="Selected Tab Background" type="url"
       default="url(https://resources.blogblog.com/blogblog/data/1kt/transparent/white80.png)" value="none"/>
   <Variable name="tab.background" description="Tab Background" type="background"
       default="transparent url(https://resources.blogblog.com/blogblog/data/1kt/transparent/black50.png) repeat scroll top left" value="transparent none no-repeat scroll top left"/>

   <Variable name="tab.border.radius" description="Tab Border Radius" type="length" default="10px" min="0" max="100px" value="0"/>
   <Variable name="tab.first.border.radius" description="First Tab Border Radius" type="length" default="10px" min="0" max="100px" value="0"/>
   <Variable name="tabs.border.radius" description="Tabs Border Radius" type="length" default="0" min="0" max="100px" value="0"/>

   <Variable name="tabs.spacing" description="Tab Spacing" type="length" default=".25em" min="0" max="10em" value="0"/>
   <Variable name="tabs.margin.bottom" description="Tab Margin Bottom" type="length" default="0" min="0" max="100px" value="1em"/>
   <Variable name="tabs.margin.sides" description="Tab Margin Sides" type="length" default="20px" min="0" max="100px" value="15px"/>

   <Variable name="main.background" description="Main Background" type="background"
       default="transparent url(https://resources.blogblog.com/blogblog/data/1kt/transparent/white80.png) repeat scroll top left" value="transparent none repeat scroll top center"/>
   <Variable name="main.padding.sides" description="Main Padding Sides" type="length" default="20px" min="0" max="100px" value="20px"/>

   <Variable name="footer.background" description="Footer Background" type="background"
       default="transparent url(https://resources.blogblog.com/blogblog/data/1kt/transparent/black50.png) repeat scroll top left" value="transparent none repeat scroll top center"/>

   <Variable name="post.margin.sides" description="Post Margin Sides" type="length" default="-20px" min="-50px" max="50px" value="-20px"/>
   <Variable name="post.border.radius" description="Post Border Radius" type="length" default="5px" min="0" max="100px" value="0"/>
   <Variable name="widget.title.text.transform" description="Widget Title Text Transform" type="string" default="uppercase" value="none"/>

   <Variable name="mobile.background.overlay" description="Mobile Background Overlay" type="string"
       default="transparent none repeat scroll top left" value="transparent none repeat scroll top left"/>

   <Variable name="startSide" description="Side where text starts in blog language" type="automatic" default="left"/>
   <Variable name="endSide" description="Side where text ends in blog language" type="automatic" default="right"/>
*/

/* Content
----------------------------------------------- */
body {
  font: $(body.font);
  color: $(body.text.color);
  background: $(body.background);
}

html body .region-inner {
  min-width: 0;
  max-width: 100%;
  width: auto;
}

.content-outer {
  font-size: 90%;
}

a:link {
  text-decoration:none;
  color: $(link.color);
}

a:visited {
  text-decoration:none;
  color: $(link.visited.color);
}

a:hover {
  text-decoration:underline;
  color: $(link.hover.color);
}

.content-outer {
  background: $(content.background);

  -moz-border-radius: $(content.border.radius);
  -webkit-border-radius: $(content.border.radius);
  -goog-ms-border-radius: $(content.border.radius);
  border-radius: $(content.border.radius);

  -moz-box-shadow: 0 0 $(content.shadow.spread) rgba(0, 0, 0, .15);
  -webkit-box-shadow: 0 0 $(content.shadow.spread) rgba(0, 0, 0, .15);
  -goog-ms-box-shadow: 0 0 $(content.shadow.spread) rgba(0, 0, 0, .15);
  box-shadow: 0 0 $(content.shadow.spread) rgba(0, 0, 0, .15);

  margin: $(content.margin) auto;
}

.content-inner {
  padding: $(content.padding);
}

/* Header
----------------------------------------------- */
.header-outer {
  background: $(header.background.color) $(header.background.gradient) repeat-x scroll top left;
  _background-image: none;

  color: $(header.text.color);

  -moz-border-radius: $(header.border.radius);
  -webkit-border-radius: $(header.border.radius);
  -goog-ms-border-radius: $(header.border.radius);
  border-radius: $(header.border.radius);
}

.Header img, .Header #header-inner {
  -moz-border-radius: $(header.border.radius);
  -webkit-border-radius: $(header.border.radius);
  -goog-ms-border-radius: $(header.border.radius);
  border-radius: $(header.border.radius);
}

.header-inner .Header .titlewrapper,
.header-inner .Header .descriptionwrapper {
  padding-left: $(header.padding);
  padding-right: $(header.padding);
}

.Header h1 {
  font: $(header.font);
  text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
}

.Header h1 a {
  color: $(header.text.color);
}

.Header .description {
  font-size: 130%;
}


/* Headings
----------------------------------------------- */
.sidebar h4 {
  font: $(widget.title.font);
  text-transform: $(widget.title.text.transform);
  color: $(widget.title.text.color);
  margin: .5em 0;
}

/* Main
----------------------------------------------- */
.main-outer {
  background: $(main.background);

  -moz-border-radius: $(main.border.radius.top) $(main.border.radius.top) 0 0;
  -webkit-border-top-left-radius: $(main.border.radius.top);
  -webkit-border-top-right-radius: $(main.border.radius.top);
  -webkit-border-bottom-left-radius: 0;
  -webkit-border-bottom-right-radius: 0;
  -goog-ms-border-radius: $(main.border.radius.top) $(main.border.radius.top) 0 0;
  border-radius: $(main.border.radius.top) $(main.border.radius.top) 0 0;

  -moz-box-shadow: 0 $(region.shadow.offset) $(region.shadow.spread) rgba(0, 0, 0, .15);
  -webkit-box-shadow: 0 $(region.shadow.offset) $(region.shadow.spread) rgba(0, 0, 0, .15);
  -goog-ms-box-shadow: 0 $(region.shadow.offset) $(region.shadow.spread) rgba(0, 0, 0, .15);
  box-shadow: 0 $(region.shadow.offset) $(region.shadow.spread) rgba(0, 0, 0, .15);
}

.main-inner {
  padding: 15px $(main.padding.sides) 20px;
}

.main-inner .column-center-inner {
  padding: 0 0;
}

.main-inner .column-left-inner {
  padding-left: 0;
}

.main-inner .column-right-inner {
  padding-right: 0;
}

/* Posts
----------------------------------------------- */
h1.post-title {
text-align: center;
font: $(post.title.font);
text-transform: none;
margin-top: 20px;
}

h2.post-title {
text-align: center;
font: $(post.title.font);
text-transform: none;
margin-top: 20px;
}

h2.post-title a {
text-decoration: none;
font: $(post.title.font);
}

h2.post-title a:hover {
text-decoration: none;
font: $(post.title.font);
color: $(link.color);
}

.comments h4 {
  margin: 1em 0 0;
  font: $(post.title.font);
}

.date-header span {
  color: $(date.header.color);
}

.post-outer {
background: $(post.background.color); /* Fundo da postagem */
padding-top: 10px; /* Espaço do topo */
padding-left: 15px; /* Espaço da esquerda */
padding-right: 15px; /* Espaço da direita */
padding-bottom: 10px; /* Espaço de baixo */
margin-left: -15px;
margin-right: -10px;
margin-top: 5px;
margin-bottom: 30px;
}
  

.post-body {
  line-height: 1.4;
  font-size: 110%;
  position: relative;
}

.post-header {
  margin: 0 0 1.5em;

  color: $(post.footer.text.color);
  line-height: 1.6;
}

.post-footer {
  margin: .5em 0 0;

  color: $(post.footer.text.color);
  line-height: 1.6;
}

#blog-pager {
  font-size: 140%
}

#comments .comment-author {
  padding-top: 1.5em;

  border-top: dashed 1px #ccc;
  border-top: dashed 1px rgba(128, 128, 128, .5);

  background-position: 0 1.5em;
}

#comments .comment-author:first-child {
  padding-top: 0;

  border-top: none;
}

.avatar-image-container {
  margin: .2em 0 0;
}

/* Comments
----------------------------------------------- */
#comments h4, #comments .comment-author a, #comments .comment-timestamp a { /*HEADING DOS COMENTÁRIOS:"*/
color: #000000; /*COR DA FONTE DA HEADING DOS COMENTÁRIOS*/
font: 17px 'Montserrat'; /*Fonte do texto*/
text-align: center;
}
#comments {
background: #fff; /*COR DE FUNDO GERAL DOS COMENTÁRIOS*/
padding: 15px;
}
.comments .comment-block {
margin-left: 70px; /*ESPAÇO ENTRE O AVATAR E A ÁREA DO COMENTÁRIO*/
}
.comment-header {
background: #e6e6e6; /*COR DE FUNDO DO AUTOR DO COMENTÁRIO*/
padding: 3px;
}
.comment-header a {
color: #000 !important; /*COR DA FONTE DO AUTOR DO COMENTÁRIO*/
font: 15px 'Montserrat', sans serif; /*FONTE DO AUTOR DO COMENTÁRIO*/
font-weight: 400;
}
.comment-header a:hover {
color: #0000 !important; /*COR DA FONTE DO AUTOR DO COMENTÁRIO HOVER*/
text-decoration: none;
}
.comments .comments-content .datetime a{
font-size: 10px !important;
float: right;
line-height: 16px;
margin-top: 5px;
}
.comments .comments-content .comment-content{
margin-top: -10px;
position: relative;
background: #fff; /*FUNDO DA AREA DO COMENTÁRIO*/
border: 1px solid #000; /*BORDA DA AREA DO COMENTÁRIO*/
border-top: 0px;
padding: 10px;
color: #222222; /*COR DO TEXTO DO COMENTÁRIO*/
font-size: 13px; /*TAMANHO DA FONTE DO COMENTÁRIO*/}
.comments .avatar-image-container {
/*MEDIDAS DO AVATAR */
max-width: 50px;
max-height: 50px;
min-height: 50px;
min-width: 50px;
background: #606060; /*COR DA BORDA*/
padding: 5px; /*ESPESSURA DA BORDA*/}
.comments .avatar-image-container img{
/*MEDIDAS DO AVATAR- MANTENHA IGUAL ACIMA */
max-width: 50px;
max-height: 50px;
min-height: 50px;
min-width: 50px;
}
.comments .comments-content .comment {
padding:20px 10px !important;
margin-bottom:15px !important;
}
.comments .comment .comment-actions a {
padding: 5px;
background: #e6e6e6; /*COR DOS BOTÕES*/
color: #000 !important; /*COR DA FONTE DOS BOTÕES*/
font: 15px 'Open Sans'; /*FONTE DOS BOTÕES*/
font-weight: 400 !important;
margin-right: 6px;
}
.comments .comment .comment-actions a:hover {
background: #faf2ff; /*COR DOS BOTÕES EM ESTADO HOVER*/
color: #000 !important; /*COR DA FONTE DOS BOTÕES EM ESTADO HOVER*/
text-decoration: none;}
.comments .continue { border-top: none;}
.comments .continue a {display: none;}



/* Widgets
----------------------------------------------- */
.widget ul, .widget #ArchiveList ul.flat {
  padding: 0;
  list-style: none;
}

.widget ul li, .widget #ArchiveList ul.flat li {
  border-top: dashed 1px #ccc;
  border-top: dashed 1px rgba(128, 128, 128, .5);
}

.widget ul li:first-child, .widget #ArchiveList ul.flat li:first-child {
  border-top: none;
}

.widget .post-body ul {
  list-style: disc;
}

.widget .post-body ul li {
  border: none;
}

/* Footer
----------------------------------------------- */
.footer-outer {
  color:$(footer.text.color);
  background: $(footer.background);

  -moz-border-radius: $(footer.border.radius.top) $(footer.border.radius.top) $(footer.border.radius.bottom) $(footer.border.radius.bottom);
  -webkit-border-top-left-radius: $(footer.border.radius.top);
  -webkit-border-top-right-radius: $(footer.border.radius.top);
  -webkit-border-bottom-left-radius: $(footer.border.radius.bottom);
  -webkit-border-bottom-right-radius: $(footer.border.radius.bottom);
  -goog-ms-border-radius: $(footer.border.radius.top) $(footer.border.radius.top) $(footer.border.radius.bottom) $(footer.border.radius.bottom);
  border-radius: $(footer.border.radius.top) $(footer.border.radius.top) $(footer.border.radius.bottom) $(footer.border.radius.bottom);

  -moz-box-shadow: 0 $(region.shadow.offset) $(region.shadow.spread) rgba(0, 0, 0, .15);
  -webkit-box-shadow: 0 $(region.shadow.offset) $(region.shadow.spread) rgba(0, 0, 0, .15);
  -goog-ms-box-shadow: 0 $(region.shadow.offset) $(region.shadow.spread) rgba(0, 0, 0, .15);
  box-shadow: 0 $(region.shadow.offset) $(region.shadow.spread) rgba(0, 0, 0, .15);
}

.footer-inner {
  padding: 10px $(main.padding.sides) 20px;
}

.footer-outer a {
  color: $(footer.link.color);
}

.footer-outer a:visited {
  color: $(footer.link.visited.color);
}

.footer-outer a:hover {
  color: $(footer.link.hover.color);
}

.footer-outer .widget h2 {
  color: $(footer.widget.title.text.color);
}

/* Mobile
----------------------------------------------- */
html body.mobile {
  height: auto;
}

html body.mobile {
  min-height: 480px;
  background-size: 100% auto;
}

.mobile .body-fauxcolumn-outer {
  background: $(mobile.background.overlay);
}

html .mobile .mobile-date-outer, html .mobile .blog-pager {
  border-bottom: none;
  background: $(main.background);
  margin-bottom: 10px;
}

.mobile .date-outer {
  background: $(main.background);
}

.mobile .header-outer, .mobile .main-outer,
.mobile .post-outer, .mobile .footer-outer {
  -moz-border-radius: 0;
  -webkit-border-radius: 0;
  -goog-ms-border-radius: 0;
  border-radius: 0;
}

.mobile .content-outer,
.mobile .main-outer,
.mobile .post-outer {
  background: inherit;
  border: none;
}

.mobile .content-outer {
  font-size: 100%;
}

.mobile-link-button {
  background-color: $(link.color);
}

.mobile-link-button a:link, .mobile-link-button a:visited {
  color: $(post.background.color);
}

.mobile-index-contents {
  color: $(body.text.color);
}

.mobile .tabs-inner .PageList .widget-content {
  background: $(tabs.selected.background.color) $(tab.selected.background.gradient) repeat scroll bottom;
  color: $(tabs.selected.text.color);
}

.mobile .tabs-inner .PageList .widget-content .pagelist-arrow {
  border-$startSide: 1px solid $(tabs.separator.color);
}

/*-- TEXTO COMPARTILHE ESTE POST--*/
.compartilhe {
background: bold;
margin: 0 -0.1em;
margin-right: 0.8em;margin-left: 0.8em;
margin-top: 2em;
padding: 0.1em;
height: 40px;
}
p.share {
float: center;
text-align: center;
padding-right: 1.6em;margin-left: 1.5em;
font-weight: bold;
color: #000;
}
.goog-inline-block {
display: block !important;
}
.google-plus-share-container {
display: initial !important;
}
/* BOTÕES COMPARTILHAMENTO 
-------------------------------------------*/
 .post-share {
  text-align:center;
  margin-top:15px;
  margin-bottom:20px;
  background:none;
 }
 .post-share a {
  display:inline-block;
 }
 .share-box {
  width: 32px;
height: 32px;
background: #fff;
border: 1px solid #e5e5e5;

display: inline-block;
line-height: 32px;
border-radius: 50%;
margin: 0 1px;
-o-transition: .3s;
-ms-transition: .3s;
-moz-transition: .3s;
-webkit-transition: .3s;
 }
 .share-box i {
 
  font-size:15px;
 }
.share-box:hover {
  background:#171717;
  border:1px solid #171717;
color:#fff;
 }

/*Marcadores e comentario
-----------------------------------*/
.comment-link {
float: right;
margin-right:1em;
margin-top: 0.1em;
font: 13px 'Montserrat';
text-transform:uppercase;
text-decoration: none;
}
.post-labels {
display:block;
padding:4px;
text-align: left;
font: normal 13px 'Montserrat';
margin-top: -1.9em;
text-transform: none;
}

/* Botão voltar ao topo
------------------------------------------*/
#backtotop{
overflow:hidden;
position:fixed;
z-index:90;
right:30px; /*DISTANCIA DO BOTÃO EM RELAÇÃO A DIREITA*/
bottom:20px; /*DISTANCIA DO BOTÃO EM RELAÇÃO AO RODAPÉ*/
display:none;
width:42px; /*LARGURA DO BOTÃO*/
height:25px; /*ALTURA DO BOTÃO*/
line-height:24px;
padding-top:-15px; /*DISTANCIA DO ÍCONE EM RELAÇÃO AO TOPO DO BOTÃO*/
color:#ffffff; /*COR DA FONTE DO BOTÃO*/
text-align:center;
background:#000000; /*COR DE FUNDO DO BOTÃO*/
box-shadow: 0 3px 13px -5px #000; /*SOMBRA DO BOTÃO, APAGUE SE PREFERIR*/
font: 13px 'Open Sans'; /*TAMANHO E FONTE DO BOTÃO*/
text-indent:0;
cursor:pointer;
-webkit-transform:translateZ(0);
padding:4px 0 0;
text-align:center;
border-radius:0px;
transition:all .5s}
#backtotop:hover {
background-color:#000; /*COR DE FUNDO DO BOTÃO EM ESTADO HOVER*/
color:#ffffff;/*COR DA FONTE DO BOTÃO HOVER*/
text-decoration: none !important;
}

/* excuindo coisas desnecessarias
 -------------------------------------*/
#navbar-iframe {display: none !important; }
 body .navbar {height: 0 !important}
.status-msg-wrap, .status-msg-body, .status-msg-border, .status-msg-bg, .status-msg-hidden {display: none;}
.feed-links {height:0px;visibility:hidden;display:none}
.Attribution{display: none; !important}

]]></b:skin>

    <b:template-skin>
      <b:variable default='960px' name='content.width' type='length' value='1108px'/>
      <b:variable default='0' name='main.column.left.width' type='length'/>
      <b:variable default='310px' name='main.column.right.width' type='length' value='269px'/>

      <![CDATA[
      body {
        min-width: $(content.width);
      }

      .content-outer, .content-fauxcolumn-outer, .region-inner {
        min-width: $(content.width);
        max-width: $(content.width);
        _width: $(content.width);
      }

      .main-inner .columns {
        padding-left: $(main.column.left.width);
        padding-right: $(main.column.right.width);
      }

      .main-inner .fauxcolumn-center-outer {
        left: $(main.column.left.width);
        right: $(main.column.right.width);
        /* IE6 does not respect left and right together */
        _width: expression(this.parentNode.offsetWidth -
            parseInt("$(main.column.left.width)") -
            parseInt("$(main.column.right.width)") + 'px');
      }

      .main-inner .fauxcolumn-left-outer {
        width: $(main.column.left.width);
      }

      .main-inner .fauxcolumn-right-outer {
        width: $(main.column.right.width);
      }

      .main-inner .column-left-outer {
        width: $(main.column.left.width);
        right: 100%;
        margin-left: -$(main.column.left.width);
      }

      .main-inner .column-right-outer {
        width: $(main.column.right.width);
        margin-right: -$(main.column.right.width);
      }

      #layout {
        min-width: 0;
      }

      #layout .content-outer {
        min-width: 0;
        width: 800px;
      }

      #layout .region-inner {
        min-width: 0;
        width: auto;
      }

      body#layout div.add_widget {
        padding: 8px;
      }

      body#layout div.add_widget a {
        margin-left: 32px;
      }
      ]]>
    </b:template-skin>

    <b:if cond='data:skin.vars.body_background.image.isResizable'>
      <b:include cond='not data:view.isPreview' data='{                          image: data:skin.vars.body_background.image,                          selector: &quot;body&quot;                        }' name='responsiveImageStyle'/>
    </b:if>

    <b:include data='blog' name='google-analytics'/>
    
  
  </head>

  <body expr:class='&quot;loading&quot; + data:blog.mobileClass'>
  <b:section class='navbar' id='navbar' maxwidgets='1' name='Navbar' showaddelement='no'>
    <b:widget id='Navbar1' locked='true' title='Navbar' type='Navbar'>
      <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/plusone.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://www.blogger.com/navbar.g?targetBlogID\x3d610029351776826710\x26blogName\x3dECOTURISMO\x26publishMode\x3dPUBLISH_MODE_BLOGSPOT\x26navbarType\x3dLIGHT\x26layoutType\x3dLAYOUTS\x26searchRoot\x3dhttps://eco-turismojp.blogspot.com/search\x26blogLocale\x3dpt_BR\x26v\x3d2\x26homepageUrl\x3dhttp://eco-turismojp.blogspot.com/\x26vt\x3d6068366954981101302&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
    </b:widget>
  </b:section>

  <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <div itemscope='itemscope' itemtype='http://schema.org/Blog' style='display: none;'>
      <meta expr:content='data:blog.title' itemprop='name'/>
      <b:if cond='data:blog.metaDescription'>
        <meta expr:content='data:blog.metaDescription' itemprop='description'/>
      </b:if>
    </div>
  </b:if>

  <div class='body-fauxcolumns'>
    <div class='fauxcolumn-outer body-fauxcolumn-outer'>
    <div class='cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left'>
    <div class='fauxborder-right'/>
    <div class='fauxcolumn-inner'>
    </div>
    </div>
    <div class='cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
  </div>

  <div class='content'>
  <div class='content-fauxcolumns'>
    <div class='fauxcolumn-outer content-fauxcolumn-outer'>
    <div class='cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left'>
    <div class='fauxborder-right'/>
    <div class='fauxcolumn-inner'>
    </div>
    </div>
    <div class='cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
  </div>

  <div class='content-outer'>
  <div class='content-cap-top cap-top'>
    <div class='cap-left'/>
    <div class='cap-right'/>
  </div>
  <div class='fauxborder-left content-fauxborder-left'>
  <div class='fauxborder-right content-fauxborder-right'/>
  <div class='content-inner'>

    <header>
    <div class='header-outer'>
    <div class='header-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left header-fauxborder-left'>
    <div class='fauxborder-right header-fauxborder-right'/>
    <div class='region-inner header-inner'>
      <b:section class='header' id='header' maxwidgets='1' name='Header' showaddelement='no'>
        <b:widget id='Header1' locked='true' title='ECOTURISMO (Cabeçalho)' type='Header' version='1'>
          <b:widget-settings>
            <b:widget-setting name='displayUrl'>https://blogger.googleusercontent.com/img/a/AVvXsEj9bVkva8XtbCP3BDrAsvvJOX5iSoJUGpoABkcPheMjp4JQqTKldye42rfaFIcsvOZHSZWaZ1x0UvkM6-hiRxUx0tBRwUN_mvw6JDYpevHjmiX25JHY7_KoI8CBxpEP0_ma1icrEuiyUlhgE3y9jLMpfBfaIt6cWSRT7Wt7Ug6_EKT8E6_pRJ1XbDoduw=s1024</b:widget-setting>
            <b:widget-setting name='displayHeight'>225</b:widget-setting>
            <b:widget-setting name='sectionWidth'>752</b:widget-setting>
            <b:widget-setting name='useImage'>true</b:widget-setting>
            <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
            <b:widget-setting name='imagePlacement'>BEFORE_DESCRIPTION</b:widget-setting>
            <b:widget-setting name='displayWidth'>1024</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
        <div id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      <b:else/>
        <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <h1 style='display:none'><b:include name='title'/></h1>
</b:if>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block' width='100%'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      
      
      <div class='titlewrapper'>
  <b:if cond='data:blog.homepageUrl == data:blog.url'>
    <h1 class='title'>
      <b:include name='title'/>
    </h1>
  <b:else/>
    <div class='title'>
      <b:include name='title'/>
    </div>
  </b:if>
</div>
      <b:include name='description'/>
    </div>
      </b:if>
</b:includable>
          <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
          <b:includable id='title'>
  <b:tag cond='data:blog.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
    <data:title/>
  </b:tag>
</b:includable>
        </b:widget>
      </b:section>
    </div>
    </div>
    <div class='header-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
    </header>
    
    <!-- inicio botao volta ao topo -->
    
    <script type='text/javascript'>
// Back to top
jQuery(document).ready(function(e){var t=e(&quot;#backtotop&quot;);e(window).scroll(function(){e(this).scrollTop()&gt;=500?t.show(10).animate({opacity:&quot;1&quot;},10):t.animate({opacity:&quot;0&quot;},10)});t.click(function(t){t.preventDefault();e(&quot;html,body&quot;).animate({scrollTop:0},400)})})
</script>
    
    <!-- fim botão volta ao topo -->
    
    <!-- inicio do menu -->
  
  <style type='text/css'> 

  *, *:after, {
   margin: 0;
   padding: 0;
   box-sizing: border-box;
   font-family: sans-serif;
   font-size: 14px;
   line-height: 1.5;
 }
 .menu {
   background: #000;
 }
 .menu .menu-list, .menu .sub-menu {
   list-style: none;
 }
 .menu a {
   color: #fff;
   text-decoration: none;
   display: block;
   cursor: pointer;
   text-transform: uppercase;
   font-size: 10px;
   font-weight: 700;
   letter-spacing:0.2em;
 }
 .menu &gt; .menu-list &gt; li {
   float: left;
   position: relative;
 }
 .menu &gt; .menu-list &gt; li &gt; a {
   padding: 15px;
   margin: 1 1px;
   background: #000;
 }
 .menu &gt; .menu-list &gt; li:hover a {
   background: #444;
 }
 .menu &gt; .menu-list &gt; li:hover &gt; .sub-menu {
   display: block;
 }
 .menu &gt; .menu-list &gt; li &gt; .sub-menu {
   position: absolute;
   top: 40px;
   left: 5px;
   background: grey31;
   min-width: 150px;
   z-index: 2000;
   display: none;
 }
 .menu &gt; .menu-list &gt; li &gt; .sub-menu &gt; li &gt; a {
  padding: 7px 5px;
 }
 .menu:after {
   content: &#39;.&#39;;
   display: block;
   clear: both;
   visibility: hidden;
   line-height: 0;
   height: 0;
 }
 .site-content {
   padding: 20px;
 }
 h1 {
   font-size: 22px;
   margin: 0 0 0.6em 0;
   letter-spacing:0.2em;
   color: #444;
 }
 p {
   margin: 0 0 1.6em 0;
 }
</style>
    <div class='menu'>
  <ul class='menu-list'>
    <li><a href='https://eco-turismojp.blogspot.com/'>Pagina Inicial</a></li>
 	           <li><a href='#'>sobre</a>
       <ul class='sub-menu'>
		<li><a href='https://eco-turismojp.blogspot.com/p/pagina-inicial.html'>Sobre o Bog</a></li>        
		<!-- <li><a href='#'>Trilhas</a></li> -->
        <li><a href='https://eco-turismojp.blogspot.com/p/politica-de-privacidade.html'>Política de Privacidade</a></li>
       </ul>
                 
         <li>
      <a href='#'>Trilhas</a>
       <ul class='sub-menu'>
        <li><a href='https://eco-turismojp.blogspot.com/p/niteroi.html'>Niterói</a></li>
         <li><a href='https://eco-turismojp.blogspot.com/p/marica.html'>Maricá</a></li>
         <li><a href='https://eco-turismojp.blogspot.com/p/trilhas-cabo-frio.html'>Cabo Frio</a></li>
   </ul>
  </li> 
                 
	<li>
      <a href='#'>Museu</a>
       <ul class='sub-menu'>
        <li><a href='https://eco-turismojp.blogspot.com/p/museu-de-niteroi.html'>Niterói</a></li>
        <li><a href='https://eco-turismojp.blogspot.com/p/museu-de-marica.html'>Maricá</a></li>
        <li><a href='https://eco-turismojp.blogspot.com/p/museus-de-cabo-frio.html'>Cabo Frio</a></li>
     </ul>
    </li>
          
     <li>
      <a href='#'>Cursos</a>
       <ul class='sub-menu'>
        <li><a href='https://eco-turismojp.blogspot.com/p/curso-essencial-de-sobrevivencia-para.html'>Sobrevivência para Trilheiros</a></li>
       </ul>
     </li>
                 
      <!-- copiado 3 linhas abaixo apenas apagar para funcionar os proximos menus -->           
     </li>
  </ul> 
</div>
    
  <!-- fim do menu -->

    <div class='tabs-outer'>
    <div class='tabs-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left tabs-fauxborder-left'>
    <div class='fauxborder-right tabs-fauxborder-right'/>
    <div class='region-inner tabs-inner'>
      <b:section class='tabs' id='crosscol' maxwidgets='1' name='Cross-Column' showaddelement='yes'/>
      <b:section class='tabs' id='crosscol-overflow' name='Cross-Column 2' showaddelement='no'/>
    </div>
    </div>
    <div class='tabs-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>

    <div class='main-outer'>
    <div class='main-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>

    <div class='fauxborder-left main-fauxborder-left'>
    <div class='fauxborder-right main-fauxborder-right'/>
    <div class='region-inner main-inner'>

      <div class='columns fauxcolumns'>

        <div class='fauxcolumn-outer fauxcolumn-center-outer'>
        <div class='cap-top'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        <div class='fauxborder-left'>
        <div class='fauxborder-right'/>
        <div class='fauxcolumn-inner'>
        </div>
        </div>
        <div class='cap-bottom'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        </div>

        <div class='fauxcolumn-outer fauxcolumn-left-outer'>
        <div class='cap-top'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        <div class='fauxborder-left'>
        <div class='fauxborder-right'/>
        <div class='fauxcolumn-inner'>
        </div>
        </div>
        <div class='cap-bottom'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        </div>

        <div class='fauxcolumn-outer fauxcolumn-right-outer'>
        <div class='cap-top'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        <div class='fauxborder-left'>
        <div class='fauxborder-right'/>
        <div class='fauxcolumn-inner'>
        </div>
        </div>
        <div class='cap-bottom'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        </div>

        <!-- corrects IE6 width calculation -->
        <div class='columns-inner'>

        <div class='column-center-outer'>
        <div class='column-center-inner'>
          <b:section class='main' id='main' name='Main' showaddelement='no'>
            <b:widget id='Blog1' locked='true' title='Postagens no blog' type='Blog' version='1'>
              <b:widget-settings>
                <b:widget-setting name='commentLabel'>Comentarios</b:widget-setting>
                <b:widget-setting name='showShareButtons'>false</b:widget-setting>
                <b:widget-setting name='authorLabel'>Jeferson</b:widget-setting>
                <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                <b:widget-setting name='timestampLabel'>dia</b:widget-setting>
                <b:widget-setting name='reactionsLabel'/>
                <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
                <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                <b:widget-setting name='showLocation'>false</b:widget-setting>
                <b:widget-setting name='showTimestamp'>false</b:widget-setting>
                <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                <b:widget-setting name='style.bordercolor'>#eeeeee</b:widget-setting>
                <b:widget-setting name='showDateHeader'>true</b:widget-setting>
                <b:widget-setting name='style.textcolor'>#000000</b:widget-setting>
                <b:widget-setting name='showCommentLink'>true</b:widget-setting>
                <b:widget-setting name='style.urlcolor'>#999999</b:widget-setting>
                <b:widget-setting name='postLocationLabel'>Location:</b:widget-setting>
                <b:widget-setting name='showAuthor'>true</b:widget-setting>
                <b:widget-setting name='style.linkcolor'>#000000</b:widget-setting>
                <b:widget-setting name='style.bgcolor'>#eeeeee</b:widget-setting>
                <b:widget-setting name='showLabels'>false</b:widget-setting>
                <b:widget-setting name='postLabelsLabel'>Labels:</b:widget-setting>
                <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                <b:widget-setting name='showReactions'>false</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main' var='top'>
  <b:if cond='!data:mobile'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.isDateStart and not data:post.isFirstPost'>
          &lt;/div&gt;&lt;/div&gt;
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-outer&quot;&gt;
        </b:if>
        
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-posts&quot;&gt;
        </b:if>
        <div class='post-outer'>
          <b:include data='post' name='post'/>
          <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
        </div>

        <!-- Ad -->
        <b:if cond='data:post.includeAd'>
          <div class='inline-ad'>
            <data:adCode/>
          </div>
        </b:if>
      </b:loop>
      <b:if cond='data:numPosts != 0'>
        &lt;/div&gt;&lt;/div&gt;
      </b:if>
    </div>

    <!-- navigation -->
    <b:include name='nextprev'/>

    <!-- feed links -->
    <b:include name='feedLinks'/>

  <b:else/>
    <b:include name='mobile-main'/>
  </b:if>
</b:includable>
              <b:includable id='backlinkDeleteIcon' var='backlink'/>
              <b:includable id='backlinks' var='post'/>
              <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
              <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
              <b:includable id='comment_count_picker' var='post'>
  <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
    <data:post.commentLabelFull/>:
  </a>
</b:includable>
              <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.showThreadedComments'>
    <b:include data='post' name='threaded_comments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
              <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4><data:post.commentLabelFull/>:</h4>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
              &#160;
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
              &#160;
          </b:if>

          <data:post.commentRangeText/>

          <b:if cond='data:post.hasNewerLinks'>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
          </b:if>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:elseif cond='data:post.allowComments'/>
          <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
        </b:if>
      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

  </div>
</b:includable>
              <b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>

  <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:include cond='data:post.allowComments and data:post.feedLinks' data='post.feedLinks' name='feedLinksBody'/>
      </b:loop>
    </div>
  </b:if>
</b:includable>
              <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
              <b:includable id='iframe_comments' var='post'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
              <b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title' itemprop='name'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:include cond='data:blog.pageType != &quot;static_page&quot;                          and data:post.allowComments                          and data:post.numComments != 0' data='post' name='comment_count_picker'/>
      </div>
    </div>
  </div>
</b:includable>
              <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
              <b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
              <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
          <b:if cond='data:post.thumbnailUrl'>
            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
          </b:if>
          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
          <meta expr:content='data:post.id' itemprop='postId'/>

          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <b:if cond='data:blog.pageType == &quot;index&quot;'>
  <h2 class='post-title entry-title' itemprop='name'>
  <b:if cond='data:post.link'>
    <a expr:href='data:post.link'><data:post.title/></a>
  <b:else/>
    <b:if cond='data:post.url'>
      <b:if cond='data:blog.url != data:post.url'>
        <a expr:href='data:post.url'><data:post.title/></a>
      <b:else/>
        <data:post.title/>
      </b:if>
    <b:else/>
      <data:post.title/>
    </b:if>
  </b:if>
  </h2>
<b:else/>
  <h1 class='post-title entry-title' itemprop='name'>
  <b:if cond='data:post.link'>
    <a expr:href='data:post.link'><data:post.title/></a>
  <b:else/>
    <b:if cond='data:post.url'>
      <b:if cond='data:blog.url != data:post.url'>
        <a expr:href='data:post.url'><data:post.title/></a>
      <b:else/>
        <data:post.title/>
      </b:if>
    <b:else/>
      <data:post.title/>
    </b:if>
  </b:if>
  </h1>
</b:if>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <span itemprop='name'><data:post.author/></span>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <span itemprop='name'><data:post.author/></span>
                    </span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <meta expr:content='data:post.url.canonical' itemprop='url'/>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
            </div>

          </div>
        </div>

        <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
      </div>
    </div>
  </div>
</b:includable>
              <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
              <b:includable id='post' var='post'>
  <div class='post hentry uncustomized-post-template' itemprop='blogPost' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
    <b:if cond='data:post.firstImageUrl'>
      <meta expr:content='data:post.firstImageUrl' itemprop='image_url'/>
    </b:if>
    <meta expr:content='data:blog.blogId' itemprop='blogId'/>
    <meta expr:content='data:post.id' itemprop='postId'/>

    <a expr:name='data:post.id'/>
    <b:if cond='data:post.title'>
      <b:if cond='data:blog.pageType == &quot;index&quot;'>
  <h2 class='post-title entry-title' itemprop='name'>
  <b:if cond='data:post.link'>
    <a expr:href='data:post.link'><data:post.title/></a>
  <b:else/>
    <b:if cond='data:post.url'>
      <b:if cond='data:blog.url != data:post.url'>
        <a expr:href='data:post.url'><data:post.title/></a>
      <b:else/>
        <data:post.title/>
      </b:if>
    <b:else/>
      <data:post.title/>
    </b:if>
  </b:if>
  </h2>
<b:else/>
  <h1 class='post-title entry-title' itemprop='name'>
  <b:if cond='data:post.link'>
    <a expr:href='data:post.link'><data:post.title/></a>
  <b:else/>
    <b:if cond='data:post.url'>
      <b:if cond='data:blog.url != data:post.url'>
        <a expr:href='data:post.url'><data:post.title/></a>
      <b:else/>
        <data:post.title/>
      </b:if>
    <b:else/>
      <data:post.title/>
    </b:if>
  </b:if>
  </h1>
</b:if>
    </b:if>

    <div class='post-header'>
    <div class='post-header-line-1'/>
      
      <!-- Inicio data-->
      <center>
                                        <!--Autor e data-->
                                        <div style='display:inline;width:auto;color:#000;font:normal 12px open sans;'>
                                          <span class='post-author vcard' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'> Publicado por
                    <span class='fn author'>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <span itemprop='name'><data:post.author/></span>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn author'><span itemprop='name'><data:post.author/></span></span>
                  </b:if>
                </b:if>
              </span>
                                          <b:if cond='data:post.dateHeader'>
                                            em
                                            <data:post.dateHeader/>
                                          </b:if>
                                        </div>
                                        <p/>
                                        <!--Fim -->
                                      </center>
      <!-- FIM data-->
    </div>

    <!-- Then use the post body as the schema.org description, for good G+/FB snippeting. -->
    <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' expr:itemprop='(data:blog.metaDescription ? &quot;&quot; : &quot;description &quot;) + &quot;articleBody&quot;'>
      <data:post.body/>
      <div style='clear: both;'/> <!-- clear for photos floats -->
    </div>

    <b:if cond='data:post.hasJumpLink'>
      <div class='jump-link'>
        <a expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'><data:post.jumpText/></a>
      </div>
    </b:if>

    <div class='post-footer'>
      
      <!--Inicio do BOTÕES COMPATILHAMENTO-->
     <font face='Type teste'>
      <center><b> Compartilhe este post </b> </center>
       </font>
      
<div class='post-share'>

      <a expr:href='&quot;https://www.facebook.com/sharer/sharer.php?u=&quot; + data:post.url' target='_blank'><span class='share-box'><i class='fa fa-facebook'/></span></a>
	  <a expr:href='&quot;http://twitter.com/share?url=&quot; + data:post.url' target='_blank'><span class='share-box'><i class='fa fa-twitter'/></span></a>
  	  <a expr:href='&quot;https://www.pinterest.com/pin/create/button/?url=&quot; + data:post.url' target='_blank'><span class='share-box'><i class='fa fa-pinterest'/></span></a>

 
  
      <a alt='Compartilhar no WhatsApp' data-action='share/whatsapp/share' expr:href='&quot;whatsapp://send?text=&quot; + data:post.title + &quot;-&quot; + data:post.url' title='Compartilhar no WhatsApp'><span class='share-box'><i class='fa fa-whatsapp'/></span></a>  

     </div>
       <!--FIM do BOTÕES COMPATILHAMENTO-->
      
    <div class='post-footer-line post-footer-line-1'>
      
      <span class='post-author vcard'>
        <b:if cond='data:top.showAuthor'>
          <data:top.authorLabel/>
            <b:if cond='data:post.authorProfileUrl'>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                  <span itemprop='name'><data:post.author/></span>
                </a>
              </span>
            <b:else/>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <span itemprop='name'><data:post.author/></span>
              </span>
            </b:if>
        </b:if>
      </span>

      <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <data:top.timestampLabel/>
          <b:if cond='data:post.url'>
            <meta expr:content='data:post.url.canonical' itemprop='url'/>
            <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
          </b:if>
        </b:if>
      </span>

     

      <span class='post-icons'>
        <!-- email post links -->
        <b:if cond='data:post.emailPostUrl'>
          <span class='item-action'>
          <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
            <img alt='' class='icon-action' height='13' src='https://resources.blogblog.com/img/icon18_email.gif' width='18'/>
          </a>
          </span>
        </b:if>

        <!-- quickedit pencil -->
        <b:include data='post' name='postQuickEdit'/>
      </span>

      <!-- share buttons -->
      <div class='post-share-buttons goog-inline-block'>
        <b:include cond='data:post.sharePostUrl' data='post' name='shareButtons'/>
      </div>

      </div>

      <div class='post-footer-line post-footer-line-2'>
        
        <!-- Inicio comentarios e marcadores -->
        
        <span class='post-comment-link'>
<b:if cond='data:post.allowComments'>
<a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
<b:if cond='data:post.numComments == 0'><i class='fa fa-comments'/> Comente aqui
<b:else/>
<b:if cond='data:post.numComments == 1'><i class='fa fa-comments'/> 1 comentário
<b:else/>
<i class='fa fa-comments'/> <data:post.numComments/>  comentários
</b:if></b:if></a>
</b:if>
</span>

<span class='post-labels'>
        <b:if cond='data:post.labels'><i class='fa fa-tags'/>
          <data:postLabelsLabel/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url + &quot;?&amp;max-results=5&quot;' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
          </b:loop>
        </b:if>
      </span>
        
        <!-- Fim comentarios e marcadores -->
      
      </div>

      <div class='post-footer-line post-footer-line-3'>
      <span class='post-location'>
        <b:if cond='data:top.showLocation and data:post.location'>
          <data:postLocationLabel/>
          <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
        </b:if>
      </span>
      </div>
      <b:if cond='data:post.authorAboutMe'>
        <div class='author-profile' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
          <b:if cond='data:post.authorPhoto.url'>
            <img expr:src='data:post.authorPhoto.url' itemprop='image' width='50px'/>
          </b:if>
          <div>
            <a class='g-profile' expr:href='data:post.authorProfileUrl' itemprop='url' rel='author' title='author profile'>
              <span itemprop='name'><data:post.author/></span>
            </a>
          </div>
          <span itemprop='description'><data:post.authorAboutMe/></span>
        </div>
      </b:if>
    </div>
  </div>
</b:includable>
              <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='https://resources.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
              <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showPinterestButton'><a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToPinterestMsg/></span></a></b:if>
</b:includable>
              <b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
  </b:if>
</b:includable>
              <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
              <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        var text = (entry &&
                    ((entry.content && entry.content.$t) ||
                     (entry.summary && entry.summary.$t))) ||
            '';
        if (entry && entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + text + '</span>';
            }
          }
        }
        return text;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          replybox.src = '';
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
              <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4><data:post.commentLabelFull/>:</h4>

    <div class='comments-content'>
      <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
    </div>
    </div>
  </div>
</b:includable>
            </b:widget>
          </b:section>
        </div>
        </div>

        <div class='column-left-outer'>
        <div class='column-left-inner'>
          <aside>
          <macro:include id='main-column-left-sections' name='sections'>
            <macro:param default='0' name='num'/>
            <macro:param default='sidebar-left' name='idPrefix'/>
            <macro:param default='sidebar' name='class'/>
            <macro:param default='true' name='includeBottom'/>
          </macro:include>
          </aside>
        </div>
        </div>

        <div class='column-right-outer'>
        <div class='column-right-inner'>
          <aside>
          <macro:include id='main-column-right-sections' name='sections'>
            <macro:param default='2' name='num'/>
            <macro:param default='sidebar-right' name='idPrefix'/>
            <macro:param default='sidebar' name='class'/>
            <macro:param default='true' name='includeBottom'/>
          </macro:include>
          </aside>
        </div>
        </div>

        </div>

        <div style='clear: both'/>
      <!-- columns -->
      </div>

    <!-- main -->
    </div>
    </div>
    <div class='main-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>

    <footer>
    <div class='footer-outer'>
    <div class='footer-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left footer-fauxborder-left'>
    <div class='fauxborder-right footer-fauxborder-right'/>
    <div class='region-inner footer-inner'>
      <macro:include id='footer-sections' name='sections'>
        <macro:param default='2' name='num'/>
        <macro:param default='footer' name='idPrefix'/>
        <macro:param default='foot' name='class'/>
        <macro:param default='false' name='includeBottom'/>
      </macro:include>
      <!-- outside of the include in order to lock Attribution widget -->
      <b:section class='foot' id='footer-3' name='Footer' showaddelement='no'>
        <b:widget id='Attribution1' locked='true' title='' type='Attribution'>
          <b:widget-settings>
            <b:widget-setting name='copyright'>Jeferson Cerqueira</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
        </b:widget>
      </b:section>
    </div>
    </div>
    <div class='footer-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
    </footer>

  <!-- content -->
  </div>
  </div>
  <div class='content-cap-bottom cap-bottom'>
    <div class='cap-left'/>
    <div class='cap-right'/>
  </div>
  </div>
  </div>

  <script type='text/javascript'>
    window.setTimeout(function() {
        document.body.className = document.body.className.replace(&#39;loading&#39;, &#39;&#39;);
      }, 10);
  </script>
    <!-- inico botão volta a topo -->
    
    <a href='#' id='backtotop'><i class='fa fa-chevron-up'/>Topo</a>
    <!-- fim botão volta a topo -->
    
</body>

<macro:includable id='sections' var='col'>
  <macro:if cond='data:col.num == 0'>
  <macro:else/>
    <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-1&quot;' preferred='yes' showaddelement='yes'/>

    <macro:if cond='data:col.num &gt;= 2'>
      <table border='0' cellpadding='0' cellspacing='0' mexpr:class='&quot;section-columns columns-&quot; + data:col.num'>
      <tbody>
      <tr>
        <td class='first columns-cell'>
          <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-1&quot;'/>
        </td>

        <td class='columns-cell'>
          <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-2&quot;'/>
        </td>

        <macro:if cond='data:col.num &gt;= 3'>
          <td class='columns-cell'>
            <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-3&quot;'/>
          </td>
        </macro:if>

        <macro:if cond='data:col.num &gt;= 4'>
          <td class='columns-cell'>
            <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-4&quot;'/>
          </td>
        </macro:if>
      </tr>
      </tbody>
      </table>

      <macro:if cond='data:col.includeBottom'>
        <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-3&quot;' showaddelement='no'/>
      </macro:if>
    </macro:if>
  </macro:if>
</macro:includable>

<b:section-contents id='sidebar-right-1'>
  <b:widget id='HTML2' locked='false' title='' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;style&gt;
.profile-pic {
text-align: center;
color: #d4d4d4;
font-size: 14px; /*TAMANHO DA FONTE DO TEXTO*/
}
.profile-pic img {
width: 250px; /*LARGURA DA FOTO*/
height: auto;
border-radius: 1000px; /*GRAU DE ARREDONDAMENTO DA FOTO*/
-webkit-border-radius: 1000px; /*GRAU DE ARREDONDAMENTO DA FOTO*/
opacity:1
}
.profile-pic img:hover {opacity:0.7;
}
#socialmediaiconsside {
font-size: 25px; /*TAMANHO DA FONTE DOS ÍCONES*/
margin: 0;
padding-right: 10px;
text-align: center;
position:relative;
}
#socialmediaiconsside a {
color: #d4d4d4; /*COR DOS ÍCONES*/
display: inline-block;
line-height: 40px;
padding: 0 5px;
}
#socialmediaiconsside a:hover {
color: #FF9A4F; /*COR DOS ÍCONES EM ESTADO HOVER*/
}
&lt;/style&gt;

&lt;div class=&quot;profile-pic&quot;&gt; 
&lt;img src=&#39;https://static.tumblr.com/vvnyb6k/iHurda6i6/whatsapp_image_2022-06-10_at_17.38.09-removebg-preview__1_.png&#39; border=&quot;0&quot; alt=&quot;profile&quot;/&gt; 
&lt;p align=&quot;justify&quot;&gt; &lt;b&gt;Trilheiro, 26 anos, guia de turismos por amor, cadastrado no cadastur. Sou apaixonado por fazer por conhecer lugares novos, trilhas, esporte radicais.&lt;/b&gt; &lt;/p&gt;   &lt;/div&gt;


&lt;div id=&quot;socialmediaiconsside&quot;&gt;
&lt;a href=&quot;https://www.facebook.com/JefersonJP17/&quot; target=&quot;_blank&quot;&gt;&lt;i class=&quot;fa fa-facebook&quot;&gt;&lt;/i&gt;&lt;/a&gt;
&lt;!-- 
&lt;a href=&quot;YOUR TWITTER URL&quot; target=&quot;_blank&quot;&gt;&lt;i class=&quot;fa fa-twitter&quot;&gt;&lt;/i&gt;&lt;/a&gt; 
--&gt;
&lt;a href=&quot;https://br.pinterest.com/jeferson_cerq/_saved/&quot; target=&quot;_blank&quot;&gt;&lt;i class=&quot;fa fa-pinterest&quot;&gt;&lt;/i&gt;&lt;/a&gt;
&lt;a href=&quot;https://www.instagram.com/jefersonjp20/&quot; target=&quot;_blank&quot;&gt;&lt;i class=&quot;fa fa-instagram&quot;&gt;&lt;/i&gt;&lt;/a&gt;
&lt;!--
&lt;a href=&quot;YOUR BLOGLOVIN URL&quot; target=&quot;_blank&quot;&gt;&lt;i class=&quot;fa fa-heart&quot;&gt;&lt;/i&gt;&lt;/a&gt;
--&gt;
&lt;!--
&lt;a href=&quot;mailto:YOUR EMAIL ADDRESS&quot;&gt;&lt;i class=&quot;fa fa-envelope&quot;&gt;&lt;/i&gt;&lt;/a&gt;
--&gt;
&lt;/div&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h4 class='title'><data:title/></h4>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
  <b:widget id='BlogSearch1' locked='false' title='Pesquisa' type='BlogSearch' version='1'>
    <b:includable id='main'>
    <!-- only display title if it's non-empty -->
    <b:if cond='data:title != &quot;&quot;'>
      <h4 class='title'><data:title/></h4>
    </b:if>

    <div class='widget-content'>
      <div expr:id='data:widget.instanceId + &quot;_form&quot;'>
        <form class='gsc-search-box' expr:action='data:blog.searchUrl'>
          <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
          <table cellpadding='0' cellspacing='0' class='gsc-search-box'>
            <tbody>
              <tr>
                <td class='gsc-input'>
                  <input autocomplete='off' class='gsc-input' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q' size='10' title='search' type='text'/>
                </td>
                <td class='gsc-search-button'>
                  <input class='gsc-search-button' expr:value='data:messages.search' title='search' type='submit'/>
                </td>
              </tr>
            </tbody>
          </table>
        </form>
      </div>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
  </b:widget>
  <b:widget id='HTML1' locked='false' title='INFORMAÇÕES' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;marquee direction=&quot;up&quot; height=&quot;300&quot; on=&quot;&quot; onmouseout=&quot;this.start()&quot; onmouseover=&quot;this.stop()&quot; scrollamount=&quot;4&quot; with=&quot;200&quot;&gt;
&lt;a href=&quot;https://eco-turismojp.blogspot.com/2022/06/congresso-de-trilha-em-niteroi.html&quot; target=&quot;_blank&quot;&gt;&lt;img border=&quot;10&quot; src=&quot;https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhIAEYTG7T0CCB5u5AGf1_jx87AYTtF6Eim-tv7L1GIrBO-c9kEdbB3CgOhEWsmTWdfAsmv_PNbQk3273g4wt4nC_eqisrt8m-VkoLQVAtdon7j-Ej5A91o7I4-M1bw7GEcL2ncrd5PJe4bjewU1wkKNFMn4yS1RCjKO64NcSdIvAjgC6ccpB8u6nBmww/s1280/WhatsApp%20Image%202022-06-05%20at%2021.09.31.jpeg&quot; style=&quot;height: 90px; width: 200px;&quot; /&gt;&lt;/a&gt;
&lt;a href=&quot;https://go.hotmart.com/T72202032E?ap=25bf&quot; target=&quot;_blank&quot;&gt;&lt;img border=&quot;10&quot; src=&quot;https://static.tumblr.com/vvnyb6k/Y72re51p4/whatsapp_image_2022-06-27_at_09.40.32.jpeg&quot; style=&quot;height: 90px; width: 200px;&quot; /&gt;&lt;/a&gt;


&lt;/marquee&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h4 class='title'><data:title/></h4>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
  <b:widget id='ReportAbuse1' locked='false' title='' type='ReportAbuse'>
    <b:includable id='main'>
  <b:include name='reportAbuse'/>
</b:includable>
  </b:widget>
</b:section-contents><b:section-contents id='sidebar-right-2-1'/><b:section-contents id='sidebar-right-2-2'/><b:section-contents id='sidebar-right-3'/><b:section-contents id='footer-1'/><b:section-contents id='footer-2-1'/><b:section-contents id='footer-2-2'/></html>
