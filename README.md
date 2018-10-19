<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<!-- Cherish Theme by Synics/Cleanful. 1-2-3-4 column theme; please do not remove credit or redistribute. Questions can be directed to my ask box @ synics.tumblr.com/asks. Thank you for using this theme -->
<head>
<meta name="color:upd1" content="#6C6C6C"/>
<meta name="color:upd2" content="#6C6C6C"/>
<meta name="color:upd3" content="#6C6C6C"/>
<meta name="color:upd4" content="#6C6C6C"/>
<meta name="color:Tab Text Colour" content="#ffffff"/>
<meta name="color:Tab Links Colour" content="#b6b6b6"/>
<meta name="color:Tab Links Colour Hover" content="#000000"/>
 
<meta name="color:Background" content="#fff" />
<meta name="image:Right Background" content= "" />
<meta name="color:Text" content="#424242" />
<meta name="color:Accent" content="#d8e8ee" />
<meta name="color:Border" content="#ecebeb" />
<meta name="color:Title" content="#9ce4fc" />
<meta name="color:TextPermalink" content="#868585" />
<meta name="color:Link" content="#b7c4dd" />
<meta name="color:Hover" content="#b1ebe9" />
<meta name="color:upd1" content="#ff8f9d"/>
<meta name="color:upd2" content="#ffd3b8"/>
<meta name="color:upd3" content="#e9ece1"/>
<meta name="color:upd4" content="#cce8d1"/>
<meta name="color:upd5" content="#ffffff"/>
<meta name="color:Navigation" content="#e6f6f8" />
<meta name="color:NavigationHover" content="#e6f6f8" />
<meta name="color:NavBackgroundHover" content="#fff" />
<meta name="color:bold" content="#7c6d83" />
<meta name="color:italic" content="#788591" />
<meta name="font:body" content="baskerville" />
<meta name="text:fontsize" content="9px" />
<meta name="text:titlefontsize" content="20px" />
<meta name="text:navigationfontsize" content="15px" />
<meta name="text:Link One Title" content="" />
<meta name="text:Link One" content="/" />
<meta name="text:Link Two Title" content="" />
<meta name="text:Link Two" content="/" />
<meta name="text:Link Three Title" content="" />
<meta name="text:Link Three" content="" />
<meta name="text:title1" content="" />
<meta name="text:title2" content="" />
<meta name="text:navigation" content="navigation" />
<meta name="if:whitetumblrcontrols" content="1" />
<meta name="if:defaultfont" content="1" />
<meta name="if:consolasfont" content="0" />
<meta name="if:one column" content="0" />
<meta name="if:two column" content="1" />
<meta name="if:three column" content="0" />
<meta name="if:four column" content="0" />
<meta name="if:faded images" content="0" />
<meta name="if:title 1" content="0" />
<meta name="if:dropdown box" content="0" />
<meta name="if:round" content="0" />
<meta name="if:sidebar top" content="0" />
<meta name="if:sidebar middle" content="1" />
<meta name="if:sidebar bottom" content="0" />
<meta name="if:small spaces in navigation" content="1" />
<meta name="image:sidebar" content="http://25.media.tumblr.com/5d963465cb936d83221a54f1f055d46a/tumblr_mvwyvgvx0J1s9t1lfo2_500.png" />
 
<title>{Title}</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
{block:Description}<meta name="description" content="{MetaDescription}"/>{/block:Description}
<link rel="shortcut icon" href="{Favicon}" />
<link rel="alternate" type="application/rss+xml" href="{RSS}" />
<link href='http://fonts.googleapis.com/css?family=Open+Sans:400,300' rel='stylesheet' type='text/css'><link href='http://fonts.googleapis.com/css?family=Raleway' rel='stylesheet' type='text/css'> <link href='http://fonts.googleapis.com/css?family=Pompiere' rel='stylesheet' type='text/css'>
 
 <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7/jquery.min.js"></script>
<script src="http://static.tumblr.com/iuw14ew/VSQma1786/jquery.style-my-tooltips.js"></script>
<script>(function($){$(document).ready(function(){$("a[title]").style_my_tooltips({tip_follows_cursor:true,tip_delay_time:20,tip_fade_speed:400,attribute:"title"});});})(jQuery);</script>
 
<style type="text/css">
        #s-m-t-tooltip {
        display: block;
        max-width: 100px;
        margin: 15px;
        word-wrap: break-word;
        padding:2px 5px 2px 5px;
        z-index: 9999;
        background: #fff;
        text-transform: uppercase;
        border: 1px solid {color:border};
        font-family: calibri;
        font-size: 9px;
        color: {color:text};
        text-align: center;
        letter-spacing:1px}
 
 
{block:ifwhitetumblrcontrols}#tumblr_controls {-webkit-filter: invert(100%); position: fixed !important;}{/block:ifwhitetumblrcontrols}
 
body {
    background-color:{color:background};
background-image: url('{image:Right Background}');
background-attachment: fixed;
background-position: bottom right;
background-repeat: no-repeat;
        background-color:{color:background};
        color:{color:text};  
        {block:ifnotdefaultfont}font-family: {font:body};
        {/block:ifnotdefaultfont} {block:ifdefaultfont}font-family: 'Open Sans', sans-serif;{/block:ifdefaultfont}     
        {block:ifconsolasfont}font-family:consolas;{/block:ifconsolasfont}
        font-size:{text:fontsize};
        text-align:left;
        padding: 0px;}
 
body, a, a:hover {
        cursor: url(http://cur.cursors-4u.net/cursors/cur-9/cur817.cur),
        progress;}
 
::selection {
        color:{color:background};
        background:{color:accent};}
       
::-webkit-scrollbar {
    width:3px;
    height:7px;
    }
::-webkit-scrollbar-track-piece {
    background-color:{color:border};
    }
::-webkit-scrollbar-thumb {
    background-color:{color:accent};
    }    
   
 a{
        text-decoration:none;
        color:{color:link};
         -moz-transition: all 0.3s ease-out; -o-transition: all 0.3s ease-out; -webkit-transition: all 0.3s ease-out; transition: all 0.3s ease-out;}
a:hover {
        color:{color:hover} ; }
 
#left{
        color:{color:text};
        font-size:{text:fontsize};
        {block:ifnotdefaultfont}font-family: {font:body};{/block:ifnotdefaultfont}
        {block:ifdefaultfont}font-family: 'Open Sans', sans-serif;{/block:ifdefaultfont}
        z-index:1;
        -webkit-transition: 0.6s ease-in;  
        margin-left:300px;
        width:200px;
        padding:10px;
        position:fixed;
        {block:ifconsolasfont}font-family:consolas;{/block:ifconsolasfont};
        opacity:.8;
        -moz-transition: all 0.4s ease-out; -o-transition: all 0.4s ease-out; -webkit-transition: all 0.4s ease-        out; transition: all 0.4s ease-out; margin-top:-100px; }
       
#nav {
        text-align:center;
        width:auto;
        margin-top:5px;
        opacity:0;
        z-index:1009;
        -moz-transition: all 0.4s ease-out; -o-transition: all 0.4s ease-out; -webkit-transition: all 0.4s ease-        out; transition: all 0.4s ease-out; }
       
 
#nav a{
    {block:ifsmallspacesinnavigation}letter-spacing:-2px;{/block:ifsmallspacesinnavigation}
    {block:ifnotsmallspacesinnavigation}letter-spacing:0px;{/block:ifnotsmallspacesinnavigation}
    margin-top:2px;
    display:inline-block;
    font-size:{text:navigationfontsize};
    color:{color:navigation};
    background:{color:background};
    padding:3px;
    border-radius:4px;
    -moz-transition: all 0.3s ease-out; -o-transition: all 0.3s ease-out; -webkit-transition: all 0.3s ease-    out; transition: all 0.3s ease-out;
    }
   
#nav a:hover
    {
    color:{color:navigationhover};
    background:{color:navbackgroundhover}}
 
#info {
    {block:ifsidebartop}margin-top:300px;{/block:ifsidebartop}
    {block:ifsidebarmiddle}margin-top:600px;{/block:ifsidebarmiddle}
    {block:ifsidebarbottom}margin-top:900px;{/block:ifsidebarbottom}
        padding:5px;
        text-align:center;}
       
{block:ifnotdropdownbox}
#info:hover #nav { opacity:1;}
{/block:ifnotdropdownbox}
#info img {
    width:150px;
    opacity:.78;
    position:relative;
    -moz-transition: all .7s ease-out; -o-transition: all .7s ease-out; -webkit-transition: all .7s ease-out; transition: all .7s ease-out;
}
 
 
#title { -moz-transition: all 0.3s ease-out; -o-transition: all 0.3s ease-out; -webkit-transition: all 0.3s ease-       out; transition: all 0.3s ease-out;
    position:absolute; width:200px; text-align:center;
    {block:iftitle2}font-family: theonlyexception;{block:iftitle2};
        {block:iftitle1}font-family: 'Pompiere', cursive;{/block:iftitle1};
}
 
#title a{
        font-size:{text:titlefontsize};
        background:transparent;
        padding:5px;
        color:{color:title};
        {block:iftitle1}font-family: 'Pompiere', cursive;{/block:iftitle1};
        text-align:center;}
#info:hover #title a{
        opacity:0; }
 
#title2 { -moz-transition: all 0.3s ease-out; -o-transition: all 0.3s ease-out; -webkit-transition: all 0.3s ease-      out; transition: all 0.3s ease-out; position:absolute; width:200px; text-align:center;;
        {block:iftitle1}font-family: 'Pompiere', cursive;{/block:iftitle1};}
 
#title2 a{
    font-size:{text:titlefontsize};
        background:transparent;
        padding:5px;
        color:{color:title};
        {block:iftitle1}font-family: 'Pompiere', cursive;{/block:iftitle1};
        text-align:center;
        opacity:0;}
       
#info:hover #title2 a {
    opacity:1;
}
 
#title
.des {
    height:65px;
    overflow:auto;
        text-align:left;
 -moz-transition: all .7s ease-out; -o-transition: all .7s ease-out; -webkit-transition: all .7s ease-out; transition: all .7s ease-out;
    border-bottom:1px solid {color:border}; }
 
#bar {
    z-index:99999;
    margin-top:-200px;
    opacity:1;  -moz-transition: all 0.7s ease-out; -o-transition: all 0.7s ease-out; -webkit-transition: all 0.7s ease-        out; transition: all 0.7s ease-out;
}
 
#info:hover #bar
    {opacity:1;}
#content {{block:indexpage}
        margin-left:520px;
        {block:iffourcolumn}width:1200px;{/block:iffourcolumn}
        {block:ifthreecolumn}width:900px;{/block:ifthreecolumn}
        {block:ifonecolumn}width:300px; {/block:ifonecolumn}
        {block:iftwocolumn}width:700px; {/block:iftwocolumn}margin-top:0px; {/block:indexpage}
        {block:permalinkpage}width:800px; padding-left:450px;; {/block:permalinkpage};}
#entry img {
        -moz-transition: all 0.4s ease-out; -o-transition: all 0.4s ease-out; -webkit-transition: all 0.4s ease-out; transition: all 0.4s ease-out;
        {block:Indexpage}width:250px;
        {block:iffadedimages}opacity:.8;{/block:iffadedimages}
        {block:ifnotfadedimages}opacity:1;{/block:ifnotfadedimages}
        z-index:-1;
        {block:ifround}border-radius:5px;{/block:ifround} {/block:Indexpage}
        {block:permalinkpage}width:400px;
        background:{color:postbackground};
        {block:ifborders}border:1px solid {color:border};
        margin-top:10px; {/block:ifborders}{/block:permalinkpage}  }
#entry img:hover {
        opacity:1;}
#entry {
        float:right;
        margin:20px;
        {block:Indexpage} background:{color:postbackground};
        {block:ifborders}border:1px solid {color:border}; {/block:ifborders}width:250px;{/block:Indexpage}      {block:permalinkpage}width:400px;
        margin-left:100px;
        margin-top:100px;
        background: {color:postbackground};{/block:permalinkpage};
        {block:ifround}border-radius:5px;{/block:ifround} }
#entry:hover {{block:Indexpage}
        {block:ifborders}border:1px solid {color:accent};
        {/block:ifborders}opacity:1; {/block:Indexpage}}
 
.perma{
    Z-INDEX:99999;
    background:{color:border};
    position:static;
    padding:6px;
    text-align:left;
    height:auto;
    width:30px;
    font-size:9px;
    opacity:0;filter: alpha(opacity = 0);
    -webkit-transition: 0.3s ease-in; font-family:consolas;
    margin-top:-20px;
    {block:ifround}border-radius:5px;{/block:ifround}}
   
#entry:hover .perma{opacity:.8;
    filter: alpha(opacity = 90);
    -webkit-transition: 0.3s ease-in;
    margin-top:0px;}
 
.perma:hover {padding-top:10px;}
.nt{
    Z-INDEX:99999;
    background:{color:background};
    position:static;
    padding:2px;
    text-align:right;
    height:auto;
    width:30px;
    margin-left:42px;
    font-size:9px;
    margin-top:-17px;
    opacity:0;filter: alpha(opacity = 0);
    -webkit-transition: 0.3s ease-in; font-family:consolas; }
   
#entry:hover .nt{opacity:.8;
    filter: alpha(opacity = 90);
    -webkit-transition: 0.3s ease-in;}
   
 .playbutton {
        width: 20px;
        height: 30px;
        overflow: hidden;
        position: relative;
        z-index: 1000;
        margin: 5px 14px 3px 6px;}
 .playbox {
        border:1px solid {color:border};
        background-color: #fff;
        opacity:.7;
        position: absolute;
        z-index: 1000;
        margin-top: 0px;
        -webkit-transition: all 0.3s ease-out; transition: all 0.3s ease-out;
        margin-left: 190px;}
.playbox:hover {opacity:1;}
.capt {
        padding:6px;
        background:{color:border};
        text-align:center;
        -webkit-transition: 0.9s ease-in;
        width:170px;
        height:29px;
        overflow:auto;}
 
.pagination {display: none;}
 
.mark {
        font: bold 60px georgia;
        line-height: 50px;
        position: absolute;
        color:{color:link};
        opacity:.3;}
.quote {text-indent: 35px;
        text-align: justify;
        padding:6px;
        border-bottom:1px solid {color:border};
        line-height:15px;}
 
.tp {
        color:transparent;
        position:absolute;
        background:transparent;
        opacity:0;
        filter: alpha(opacity = 0);-webkit-transition: 0.3s ease-in;
        margin-top:7px;
        text-align:right;  
        margin-left:175px;
        margin-top: -15px;
        padding:5px;}
#entry:hover .tp {opacity:.7;}
.tp a{
        font-size:9px;
        text-align:right;
        font-family:{font:body};
        color:{color:textpermalink}}
.tp a:hover{text-decoration:underline;}
i, em {
        font-style:italics;
        color:{color:italic};}
b, strong {font-weightbold;
 color:{color:bold};}
blockquote {
        margin-top:7px;
        border-radius:5px;
        margin-left:20px;
        padding-left:5px;
        padding-right:5px;
        padding-top:2px;
        padding-bottom:2px;
        background:{color:border};}
 
.permapage {
        position:absolute;
        font-size:9px;
        padding:15px;
        width:200px;
        text-align:left;
        margin-top:100px;
        margin-left:600px;
        max-height:500px;
        overflow:auto;
        background:{color:postbackground};}
 
#synics a{position: fixed; bottom : 10px; margin-left: 5px; left: 0px; z-index: 2; -webkit-transition: all 0.5s; -moz-transition: all 0.5s; transition: all 0.5s; display: inline-block; text-transform: uppercase; letter-spacing: 2px; background: {color:border}; color: {color:text}; text-align: center; width: 55px; width:40px; font-size:8px; font-family:consolas; text-decoration:none; padding:5px;}
#synics a:hover{ width: 50px; color: {color:background}; background: {color:accent}; padding:30px;}
 #update {
    width:100px;
    position:fixed;
    margin-left:10px;
    margin-top:20px;
    z-index:9999999999999;
}
 

  /*--- UPDATE ---*/
 
 
.update {
position:fixed;
margin-top:50px;
margin-left:0px;
text-align:center;
text-transform:uppercase;
color:#8C8C8C;
font-size:8px;
letter-spacing:1px;
z-index:2147483607;
font-family:consolas;
width:150px;
}
 
/*---BEGIN FIRST TAB ---*/
 
.l1 {
width:50px;
background:black;
margin-bottom:8px;
text-align:center;
background:{color:upd1};
color:white;
padding:1px;
-webkit-transition: all 0.7s ease;
-moz-transition: all 0.7s ease;
-o-transition: all 0.7s ease
}
 
.l1:hover {width:180px; -webkit-transition: all 0.7s ease;-moz-transition: all 0.7s ease;-o-transition: all 0.7s ease;
}
 
.txt1 {
position:absolute;
width:100px;
padding:10px;
padding-left:5px;
left:180px;
margin-top:6px;
opacity:0;
color:black;
text-align:left;
-moz-transition:all 0.7s ease-out;
-webkit-transition:all 0.7s ease-out;
-o-transition:all 0.7s ease-out;}
 
.l1:hover .txt1{left:80px;opacity:1;}
 
/*--- END FIRST TAB ---*/
 
/*---BEGIN SECOND TAB---*/
 
.l2 {
width:50px;
background:black;
margin-bottom:8px;
text-align:center;
background:{color:upd2};
color:white;
padding:1px;
-webkit-transition: all 0.7s ease;
-moz-transition: all 0.7s ease;
-o-transition: all 0.7s ease
}
 
.l2:hover {width:180px; -webkit-transition: all 0.7s ease;-moz-transition: all 0.7s ease;-o-transition: all 0.7s ease;
}
 
.txt2 {
position:absolute;
width:100px;
padding:10px;
padding-left:5px;
left:180px;
margin-top:6px;
opacity:0;
color:black;
text-align:left;
-moz-transition:all 0.7s ease-out;
-webkit-transition:all 0.7s ease-out;
-o-transition:all 0.7s ease-out;}
 
.l2:hover .txt2{left:80px;opacity:1;}
 
/*---END SECOND TAB---*/
 
/*---BEGIN THIRD TAB--*/
 
.l3 {
width:50px;
background:black;
margin-bottom:8px;
text-align:center;
background:{color:upd3};
color:white;
padding:1px;
-webkit-transition: all 0.7s ease;
-moz-transition: all 0.7s ease;
-o-transition: all 0.7s ease
}
 
.l3:hover {width:180px; -webkit-transition: all 0.7s ease;-moz-transition: all 0.7s ease;-o-transition: all 0.7s ease;
}
 
.txt3 {
position:absolute;
width:100px;
padding:10px;
padding-left:5px;
left:180px;
margin-top:6px;
opacity:0;
color:black;
text-align:left;
-moz-transition:all 0.7s ease-out;
-webkit-transition:all 0.7s ease-out;
-o-transition:all 0.7s ease-out;}
 
.l3:hover .txt3{left:80px;opacity:1;}
 
/*---END THIRD TAB---*/
 
/*--- BEGIN FOURTH TAB---*/
 
.l4 {
width:50px;
background:black;
margin-bottom:8px;
text-align:center;
background:{color:upd4};
color:white;
padding:1px;
-webkit-transition: all 0.7s ease;
-moz-transition: all 0.7s ease;
-o-transition: all 0.7s ease
}
 
.l4:hover {width:180px; -webkit-transition: all 0.7s ease;-moz-transition: all 0.7s ease;-o-transition: all 0.7s ease;
}
 
.txt4 {
position:absolute;
width:100px;
padding:10px;
padding-left:5px;
left:180px;
margin-top:6px;
opacity:0;
color:black;
text-align:left;
-moz-transition:all 0.7s ease-out;
-webkit-transition:all 0.7s ease-out;
-o-transition:all 0.7s ease-out;}
 
.l4:hover .txt4{left:80px;opacity:1;}
 
/*---END FOURTH TAB---*/
 
/*---END UPDATE---*/
{CustomCSS}/* updates tab */

#updates { /* entire updates tab */
    top:15px;
    left:20px;
    position:fixed;
    background-color:transparent;
    width:120px;
    z-index:9999;
    padding:4px;
}
 
 
#tab001, #tab002, #tab003, #tab004 { /* individual tab */
    padding:5px;
    margin-top:5px;
    height:14px;
    text-align:center;
    overflow:hidden;
    margin-top:1px1px;
    text-transform:uppercase;
    letter-spacing:1px;
    font-size:10px;
    line-height:10px;
    z-index:0;
        -webkit-transition: all 0.7s ease-in-out;
        -moz-transition: all 0.7s ease-in-out;
        -o-transition: all 0.7s ease-in-out;
        transition: all 0.7s ease-in-out;
}

#box001, #box002, #box003, #box004 { /* styling for the hover boxes */
    margin-top:5px;
    width:12px;
    height:12px;
        -webkit-transition: all 0.7s ease-in-out;
        -moz-transition: all 0.7s ease-in-out;
        -o-transition: all 0.7s ease-in-out;
        transition: all 0.7s ease-in-out;
}

#body001, #body002, #body003, #body004 { /* text styling */
    color:#2e2e2e;
    text-align:left;
    line-height:150%;
    font-family:Arial; /* change the font here */
    text-transform:lowercase;
    font-size:9px;
    letter-spacing:1px;
    margin-left:20px;
    padding-top:10px;
}

#tab001:hover #box001, #tab002:hover #box002, #tab003:hover #box003, #tab004:hover #box004 { /* box rotation transition */
    -webkit-transform: rotate(180deg);
    -moz-transform: rotate(180deg);
    -o-transform: rotate(180deg);
    -ms-transform: rotate(180deg);
    transform: rotate(180deg);
}

/* box colors */
/* change the color of each box here! */
#box001 {
    background-color:#45966e;
}
#box002 {
    background-color:#56bc8a;
}
#box003 {
    background-color:#78c9a1;
}
#box004 {
    background-color:#9ad7b9;
}

/* tab opening */
/* change the heights of each tab here. make sure it fits the length of your text exactly, otherwise it'll get cut off! */
#tab001:hover{
    height:300px;
}
#tab002:hover {
    height:300px;
}
#tab003:hover {
    height:100px;
}
#tab004:hover {
    height:100px;
}

/* end updates tab */</style>
 
{block:IndexPage}
<script type="text/javascript" src="http://static.tumblr.com/dbek3sy/iBElrgjim/jquerymasonry.js"></script>
<script type="text/javascript" src="http://static.tumblr.com/dbek3sy/Qyblrgjfn/jqueryinfintescroll.js"></script>
 
<script type="text/javascript">
$(window).load(function(){
var $wall = $('#content');
$wall.imagesLoaded(function(){
$wall.masonry({
itemSelector: '#entry',
isAnimated : false
});
});
 
$wall.infinitescroll({
navSelector : 'div.pagination',
nextSelector : '.pagination a#next',
itemSelector : '#entry',
bufferPx : 2000,
debug : false,
errorCallback: function() {
$('#scroll').fadeOut('normal');
}},
function( newElements ) {
var $newElems = $( newElements );
$newElems.hide();
$newElems.imagesLoaded(function(){
$wall.masonry( 'appended', $newElems,{isAnimated: false}, function(){$newElems.fadeIn('slow');} );
});
}); $('#content').show(500);
});
</script>
 
{/block:IndexPage}
</head>
<body><!-- updates tab -->

<div id="updates">
 
<!--- tab 1 --->
<div id="tab001"><div id="box001"></div>
<div id="body001">

<b>Suha</b><p>
canadian |she/her<p>
<center><iframe src="http://free.timeanddate.com/clock/i66tadcx/n250/ts1" frameborder="0" width="95" height="19"></iframe>
</center>

<b>Stats:</b><p>
Mixed vintage blog<p>
Semi - Hiatus<p>

 
</div></div>
 
 <!--- tab 2 --->
<div id="tab002"><div id="box002"></div>
<div id="body002">

<b>Reading:</b><p>
<i>-Life of Pi</i><p>
<b>Watching</b><p>
- <i>Shameless</i><p>
-<i>Boy meets world</i><p>
<b>Listening:</b><p>
-Saint Motel <p>
- Spotify Playlist<p>


</div></div>
 
<!--- tab 3 --->
<div id="tab003">
<div id="box003"></div> <div id="body003">

<b>Social:</b><p>
<a href="http://instagra.com/suha.an">instagram</a></br><a href="https://www.pinterest.ca/neiljjosten/">pinterest</a></br><a href="http://skywalkaars.tumblr.com">multifandom blog</a>

</div></div>

<!--- tab 4 --->
<div id="tab004">
<div id="box004"></div> <div id="body004">

Playlist

</div></div>

</div>

<!-- end updates tab -->

<div id="synics"><a href="http://airudite.tumblr.com"> synics themes</a></div>
 
<div id="left">
<div id="info">
<div id="bar">
<img src="{image:sidebar}">
<div id="title"><a href="/">{text:title1}</a></div> <div id="title2"> <a href="/">{text:title2}</a></div> <BR></BR>
<div class="des"><BR>{description}</div>
 
{block:ifnotdropdownbox}
<div id="nav"><a href="/">index</a> <a href="/ask">inbox</a> <a href="/archive">history</a>  {block:IfLinkOneTitle}<a href="{text:Link One}">{text:Link One Title}</a>{/block:ifLinkOneTitle}
{block:ifLinkTwoTitle}<a href="{text:Link Two}">{text:Link Two Title}</a>{/block:ifLinkTwoTitle}
{block:ifLinkThreeTitle}<a href="{text:Link Three}" >{text:Link Three Title}</a>{/block:ifLinkThreeTitle} <a href="http://airudite.tumblr.com">theme</a>  </div> {/block:ifnotdropdownbox}
 
{block:ifdropdownbox}  <BR>
<select onchange='location=this.options[this.selectedIndex].value;' style=' line-height:60%;font-size: 9px; width:120px;letter-spacing:1px;
background-color:{color:background};border: 1px solid {color:border}; height:20px;padding:1px;color:{color:navigation}; border-radius:2px;
'>
<option>navigation</option>
<option value="/">home</option>
<option value="/ask">message</option>
{block:IfLinkOneTitle}<option value="{text:Link One}"> {text:Link One Title} </option>{/block:ifLinkOneTitle}
{block:ifLinkTwoTitle}<option value="{text:Link Two}"> {text:Link Two Title} </option>{/block:ifLinkTwoTitle}
{block:ifLinkThreeTitle}<option value="{text:Link Three}"> {text:Link Three Title} </option>{/block:ifLinkThreeTitle}  </select>
 

</select>
 
{/block:ifdropdownbox}
 
 </div>
 
</div> </div>
 
<div id="content">
 
{block:Posts}
 
{block:Text}
<div id="entry">   <div class="mtitle">
<a href="{Permalink}">{block:Title}{Title}{/block:Title}</a> </div>
{Body} {block:IndexPage}<div class="tp"><a href="{Permalink}">{ShortMonth} {DayOfMonth}{DayOfMonthSuffix}</a> </div>{/block:IndexPage}</div>
{/block:Text}
 
{block:Photo}<div id="entry">
{block:IndexPage}<a href="{Permalink}">{/block:IndexPage}{block:PermalinkPage}{LinkOpenTag}{/block:PermalinkPage}<img src="{block:IndexPage}{PhotoURL-500}{/block:IndexPage}{block:PermalinkPage}{PhotoURL-HighRes}{/block:PermalinkPage}" alt="{PhotoAlt}"/>{block:IndexPage}</a>{/block:IndexPage}
{block:PermalinkPage}{LinkCloseTag}{/block:PermalinkPage}
{block:PermalinkPage}<BR>{block:caption}{caption}{/block:caption}{/block:PermalinkPage}
 {block:IndexPage}
<div class="perma">  <a href="{ReblogUrl}" title="reblog">Reblog</a></div> <div class="nt"><a href="{Permalink}" title="{NoteCountWithLabel}">{NoteCount}</a></div>{/block:indexpage}
</div>
{/block:Photo}
 
{block:Photoset}  <div id="entry">
{block:Photos}<a href="{permalink}"><img src="{PhotoURL-500}" width="250" style="padding-bottom:5px;"/></a>  {block:IndexPage}
<div class="perma">  <a href="{ReblogUrl}" title="reblog">Reblog</a></div> <div class="nt"><a href="{Permalink}" title="{NoteCountWithLabel}">{NoteCount}</a></div>{/block:indexpage}
{/block:Photos}
</div>
{/block:Photoset}
 
{block:Quote}
 <div id="entry">  
 <div class="mark">“</div>
 <div class="quote">
    {Quote} </div> <BR>
{block:Source} <a href="{Permalink}">{Source}</a>{/block:Source} {block:IndexPage}<div class="tp"><a href="{Permalink}">{ShortMonth} {DayOfMonth}{DayOfMonthSuffix}</a> </div>{/block:IndexPage}</div>  
{/block:Quote}
 
{block:Link}
<div id="entry">
    <a href="{URL}" {Target}>{Name}</a>
{block:Description}{Description}{/block:Description}
{block:IndexPage}<div class="tp"><a href="{Permalink}">{ShortMonth} {DayOfMonth}{DayOfMonthSuffix}</a> </div>{/block:IndexPage}</div>
{/block:Link}
 
{block:Chat}  <div id="entry">  
{block:Title}<t>{Title}</t>{/block:Title}
{block:Lines}
    {block:Label}<b>{Label}</b>{/block:Label} {Line}<br>
{/block:Lines} {block:IndexPage}<div class="tp"><a href="{Permalink}">{ShortMonth} {DayOfMonth}{DayOfMonthSuffix}</a> </div>{/block:IndexPage}</div>
{/block:Chat}
 
{block:Audio} <div id="entry">  
<div class="playbox"><div class="playbutton">{block:AudioPlayer}{AudioPlayerWhite}{/block:AudioPlayer}</div></div>
 <div class="capt"> {block:Artist}{Artist}{/block:Artist}{block:TrackName}<BR>
{TrackName}
{/block:TrackName} ({FormattedPlayCount}) </div>  {block:IndexPage}
<div class="perma">  <a href="{ReblogUrl}" title="reblog">Reblog</a></div> <div class="nt"><a href="{Permalink}" title="{NoteCountWithLabel}">{NoteCount}</a></div>{/block:indexpage}
</div>
{/block:Audio}
 
{block:Video}  <div id="entry">  
<div style="width:200px; overflow:Auto;">{Video-250}</div>{/block:indexpage}      {block:permalinkpage} {Video-500}{/block:permalinkpage}
{block:Caption}{Caption}{/block:Caption} {block:IndexPage}<div class="tp"><a href="{Permalink}">{ShortMonth} {DayOfMonth}{DayOfMonthSuffix}</a> </div>{/block:IndexPage}</div>
{/block:Video}
 
{block:Answer} <div id="entry">  <div class="mark">“</div><div class="quote">
{Asker} inquires :{Question}</div> {Answer} {block:IndexPage}<div class="tp"><a href="{Permalink}">{ShortMonth} {DayOfMonth}{DayOfMonthSuffix}</a> </div>{/block:IndexPage}</div>
{/block:Answer}
 
 {block:permalinkpage} <div class="permapage"><br>{block:Date}Posted {TimeAgo},{/block:Date} {block:NoteCount} acquiring {NoteCountwithLabel}  {/block:NoteCount}
{block:HasTags} and filed under: {block:Tags}<a href="{TagURL}">#{Tag}</a> {/block:Tags}{/block:HasTags}{/block:NoteCount}
<BR>{block:PostNotes}{PostNotes}{/block:PostNotes} </div>{/block:permalinkpage}
{/block:Posts}
 
<div class="pagination">
{block:Pagination}{block:PreviousPage}<a href="{PreviousPage}">previous</a> &middot;{/block:PreviousPage} {block:NextPage}<a href="{NextPage}" id="next">next</a>{/block:NextPage}{/block:Pagination}
</div></div>{/block:Posts}</div></div></div>
</div>
