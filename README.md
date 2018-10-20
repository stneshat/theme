<!--
 
    THEME: CYBELE
    By str-wrs
    (Part XXIV of Mythos)
 
- this is my favourite theme ever omg
- don't steal this pls
- enjoy, ilu (ﾉ◕ヮ◕)ﾉ*:･ﾟ✧
 
- see http://str-wrs.tumblr.com for more themes
 
!!!!!!!!!!!   PLEASE READ   !!!!!!!!!!!
some options will not work with others
- solid permas don't hover
- side permas can't be solid
 
this is done on purpose for the aesthetic of the theme!
please play around with the options a bit before messaging me about a perceived error
 
-->
 
 
<html>
<head>
 
<title>{Title}</title>
<link rel="shortcut icon" href="{Favicon}">
<link rel="alternate" type="application/rss+xml" href="{RSS}">
{block:Description}<meta name="description" content="{MetaDescription}" />{/block:Description}
 
{block:ifnotPaginate}<script type="text/javascript" src="http://codysherman.com/tools/infinite-scrolling/code"></script>{/block:ifnotPaginate}
 
<meta name="image:Sidebar" content=""/>
 
<meta name="color:Background" content="#fff"/>
<meta name="color:Post" content="#fff"/>
<meta name="color:Border" content="#eee"/>
<meta name="color:Accent" content="#fafafa"/>
<meta name="color:Text" content="#666"/>
<meta name="color:Title" content="#222"/>
<meta name="color:Link" content="#999"/>
 
<meta name="if:Small Posts" content=""/>
 
<meta name="if:Solid Posts" content=""/>
<meta name="if:Accent Border" content=""/>
<meta name="if:Image" content=""/>
<meta name="if:Paginate" content=""/>
<meta name="if:Captions" content=""/>
<meta name="if:Tags" content=""/>
<meta name="if:Side Perma" content=""/>
<meta name="if:Solid Perma" content=""/>
<meta name="if:Hover Perma" content=""/>
 
<meta name="select:Perma Align" content="left" title="Left">
<meta name="select:Perma Align" content="center" title="Center">
<meta name="select:Perma Align" content="right" title="Right">
 
<meta name="text:Link 1" content="/"/>
<meta name="text:Link 1 Title" content="one"/>
<meta name="text:Link 2" content="/" />
<meta name="text:Link 2 Title" content="two"/>
<meta name="text:Link 3" content="/" />
<meta name="text:Link 3 Title" content="three"/>
<meta name="text:Link 4" content="/" />
<meta name="text:Link 4 Title" content="four"/>
 
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.4.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
    $(".pn").hide();
        $(".pnh").show();$('.pnh').toggle(function(){
            $(".pn").slideDown(function(){});
                },function(){
            $(".pn").slideUp(function(){});
        });
    });
</script>
 
<script>
$(document).ready(function(){
    $(".lb").hide();
        $(".lh").show();$('.lh').toggle(function(){
            $(".lb").slideDown(function(){});
                },function(){
            $(".lb").slideUp(function(){});
        });
    });
</script>
 
<script src="http://static.tumblr.com/rzl30kg/eAxm7a751/jquery.style-my-tooltips.js"></script>
<script>
   (function($){
       $(document).ready(function(){
           $("[title]").style_my_tooltips({
               tip_follows_cursor:true,
               tip_delay_time:200,
               tip_fade_speed:300
           }
               );
       });
   })(jQuery);
</script>
 
<link href='https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800' rel='stylesheet' type='text/css'>
<style type="text/css">
 
::-webkit-scrollbar {width:5px;height:5px;background:{color:Background};}
::-webkit-scrollbar-thumb {background:{color:Border};}
 
/* General */
 
body {
    margin:0px;
    background:{color:Background};
    font-family:'Open Sans',Calibri, sans-serif;
    color:{color:Text};
    font-size:8px;
}
 
a:link, a:active, a:visited {text-decoration:none;}
a,.playh, .p{
    transition:0.5s ease;
    -o-transition:0.5s ease;
    -moz-transition:0.5s ease;
    -webkit-transition:0.5s ease;
}
 
/* Credit & Pagi */
 
#c{position:fixed;bottom:30px;right:30px;}
#pag a{margin:0px 5px;}
#pag {position:relative;margin:0px 0px -50px;}
#c, #pag {text-align:center;}
 
/* Containers */
 
#center {
    position:relative;
    margin:100px auto;
    {block:ifSmallPosts}
    {block:ifSolidPosts}width:316px;{/block:ifSolidPosts}
    {block:ifnotSolidPosts}width:300px;{/block:ifnotSolidPosts}
    {/block:ifSmallPosts}
    {block:ifnotSmallPosts}
    {block:ifSolidPosts}width:366px;{/block:ifSolidPosts}
    {block:ifnotSolidPosts}width:350px;{/block:ifnotSolidPosts}
    {/block:ifnotSmallPosts}
}
 
#entry img {max-width:100%;}
#entry {
    {block:ifSmallPosts}width:300px;{/block:ifSmallPosts}
    {block:ifnotSmallPosts}width:350px;{/block:ifnotSmallPosts}
    {block:ifSolidPosts}
    padding:7px;
    background:{color:Post};
    border:1px solid {color:Border};
    {/block:ifSolidPosts}
    {block:IndexPage}margin:100px 0px;{/block:IndexPage}
}
 
/* Sidebar */
 
#sidebar {
    position:fixed;
    width:130px;
    text-align:center;
    {block:ifSolidPosts}
    padding:7px;
    background:{color:Post};
    border:1px solid {color:Border};
    margin:0px -246px;
    {/block:ifSolidPosts}
    {block:ifnotSolidPosts}margin:0px -230px;{/block:ifnotSolidPosts}
}
 
.image img{width:100%;}
.image {margin-bottom:7px;}
.lb {
    display:none;
    {block:ifSolidPosts}margin:7px -7px -7px{/block:ifSolidPosts}
    {block:ifnotSolidPosts}margin-top:7px{/block:ifnotSolidPosts}
}
 
.lb a{padding:4px;border-top:1px solid {color:Border};}
.lh,.lb a,.link{display:block;}
.lh {
    {block:ifSolidPosts}
    border-top:1px solid {color:Border};
    margin:7px -7px -7px;
    padding:7px;
    {/block:ifSolidPosts}
    {block:ifnotSolidPosts}margin-top:7px{/block:ifnotSolidPosts}
}
 
.desc{
    padding:7px;
    text-align:justify;
    {block:ifSolidPosts}border:1px solid {color:Border};{/block:ifSolidPosts}
}
 
/* Titles */
 
h2, .qut {
    text-align:center;
    font-size:9px;
    text-transform:uppercase;
    font-weight:700;
}
 
h2 {
    padding:10px;
    letter-spacing:1px;
    {block:ifSolidPosts}
    margin:-7px -7px 7px;
    border-bottom:1px solid {color:Border};
    {/block:ifSolidPosts}
    {block:ifnotSolidPosts}margin:0px;{/block:ifnotSolidPosts}
}
 
.qut {padding:20px;letter-spacing:0.5px;}
.src {
    padding:7px;
    text-align:right;
    {block:ifSolidPosts}
    margin:7px -7px -7px;
    border-top:1px solid {color:Border};
    {/block:ifSolidPosts}
    {block:ifnotSolidPosts}margin:0px;{/block:ifnotSolidPosts}
}
 
/* Permalinks */
 
{block:ifSidePerma}
#entry:hover .p{opacity:1;}
.tags a{display:block;}
.tags {margin-top:5px;}
.p {
    position:absolute;
    width:100px;
    line-height:200%;
    padding-left:10px;
    {block:ifHoverPerma}opacity:0;{/block:ifHoverPerma}
    {block:ifSmallPosts}
    {block:ifSolidPosts}margin:-7px 307px;{/block:ifSolidPosts}
    {block:ifnotSolidPosts}margin:0px 300px;{/block:ifnotSolidPosts}
    {/block:ifSmallPosts}
   
    {block:ifnotSmallPosts}
    {block:ifSolidPosts}margin:-7px 357px;{/block:ifSolidPosts}
    {block:ifnotSolidPosts}margin:0px 350px;{/block:ifnotSolidPosts}
    {/block:ifnotSmallPosts}
}
{/block:ifSidePerma}
 
{block:ifnotSidePerma}
#entry:hover .p {opacity:1;}
.p a{margin:0px 3px;}
.tags a{margin:0px 4px;}
.tags {margin-top:3px;}
.p {
    padding:7px 0px;
    text-align:{select:Perma Align};
        {block:ifSolidPosts}
        {block:ifSolidPerma}
        margin:7px -7px -7px;
        padding:7px 3px;
        border-top:1px solid {color:Border};
        {/block:ifSolidPerma}
 
        {block:ifnotSolidPerma}
        position:absolute;
        {block:ifSmallPosts}width:316px;{/block:ifSmallPosts}
        {block:ifnotSmallPosts}width:366px;{/block:ifnotSmallPosts}
        margin:8px -8px;
        {block:ifHoverPerma}opacity:0;{/block:ifHoverPerma}
        {/block:ifnotSolidPerma}
    {/block:ifSolidPosts}
   
    {block:ifnotSolidPosts}
    {block:ifSolidPerma}
    margin-top:7px;
    border-top:1px solid {color:Border};
    {/block:ifSolidPerma}
    {block:ifnotSolidPerma}
        {block:ifHoverPerma}opacity:0;{/block:ifHoverPerma}
    {/block:ifnotSolidPerma}
    {/block:ifnotSolidPosts}
}
{/block:ifnotSidePerma}
 
 
/* Audio & Chat */
 
#entry:hover .playh{opacity:0.9;}
.lines {padding:5px;}
.play {width:25px;height:25px;overflow:hidden;}
.playh {position:absolute;background:#e4e4e4;opacity:0;padding:20px;}
.aa img{width:100%;}
.aa{float:left;width:65px;}
.au span{display:block;}
.au {
    margin-left:72px;
    height:45px;
    line-height:15px;
    padding:10px;
    {block:ifAccentBorder}padding:9px 10px;{/block:ifAccentBorder}
}
 
/* Text */
 
pre, small, sub, sup, big {font-size:8px;}
p, blockquote {margin:10px;text-align:justify;}
ul {list-style-type:square;}
blockquote p{margin:10px 0px;}
blockquote p:first-child{margin:0px 0px 10px;}
blockquote p:last-child{margin:10px 0px 0px;}
blockquote p:only-child{margin:0px;}
blockquote{margin:10px;padding:0px 10px;border-left:1px solid {color:Border};}
pre {
    font-family:'Open Sans',Calibri,sans-serif;
    white-space:pre-wrap;
    white-space:-moz-pre-wrap;
    white-space:-pre-wrap;
    white-space:-o-pre-wrap;
    word-wrap:break-word;
}
 
/* Photosets */
 
#vignette,#tumblr_lightbox_caption {visibility:hidden;}
#tumblr_lightbox {background:{color:Background}!important;}
#tumblr_lightbox_left_image,
#tumblr_lightbox_right_image {opacity:0.5!important;}
#tumblr_lightbox_center_image,
#tumblr_lightbox_left_image,
#tumblr_lightbox_right_image {
    box-shadow:none!important;
    border-radius:0px!important;
}
 
/* Video */
 
.video iframe,
.video .tumblr_video_container,
.video .tumblr_video_container iframe {
    display:block;
    max-width:100%;
    max-height:width:300px;
}
 
.video #youtube_iframe {
    display:block;
    max-width:100%;
    max-height:calc(width:300px * 0.67);
}
 
/* Ask */
 
.ask b{text-decoration:underline;}
.ask {
    padding:15px;
    font-style:italic;
    font-weight:600;
    letter-spacing:0.3px;
    {block:ifSolidPosts}
    margin:-7px -7px 7px;
    border-bottom:1px solid {color:Border};
    {/block:ifSolidPosts}
}
 
/* Captions */
 
.txt {margin:0px;padding:1px;}
a.tumblr_blog{font-size:6.5px;letter-spacing:1px;text-transform:uppercase;}
 
/* Permalink Page + Postnotes */
 
.perma,.pnh {padding:7px;}
.perma a{margin-right:5px;}
.pn img{display:none;}
.pn li{list-style-type:none;padding:2px 0px;}
.pn ul, .pn ol {padding:0px;margin:0px;}
.pn {display:none;border-top:1px solid {color:Border};padding:10px;}
.pnh{display:block;text-align:center;border-top:1px solid {color:Border};}
.pph{
    border-top:1px solid {color:Border};
    {block:ifnotSolidPosts}margin-top:7px{/block:ifnotSolidPosts}
    {block:ifSolidPosts}margin:7px -7px -7px;{/block:ifSolidPosts}
}
 
/* Tooltips */
 
#s-m-t-tooltip{
    max-width:300px;
    margin:15px;
    z-index:99999999;
    background:{color:Background};
    padding:5px;
    font-size:7.5px;
    font-style:italic;
    letter-spacing:0.5px;
}
 
/* Common Styles */
 
.ask,p,.perma,blockquote,.lines,ul,.qut,.desc{line-height:175%;}
a,.p,.perma,.src{color:{color:Link};}
a:hover,.ask,.ask a,h2,h2 a,h3,h3 a{color:{color:Title};}
.au,#c,#pag,.lines b,.src{
    font-size:7px;
    letter-spacing:1px;
    text-transform:uppercase;
}
 
.pph,.p,.lb a,.lh,.link{
    font-size:6px;
    letter-spacing:0.5px;
    text-transform:uppercase;
}
 
.txt,.qut,.au,.desc,.lines:nth-child(odd) {
    background:{color:Accent};
    {block:ifAccentBorder}border:1px solid {color:Border};{/block:ifAccentBorder}
}
 
/* Etc */
 
.lh {letter-spacing:1.5px;font-weight:bold;}
.link,.nc,.pnh{letter-spacing:1.5px;font-weight:bold;padding:7px 0px;}
.notes img {width:0px;}
img {margin-bottom:-1px;}
 
</style>
</head>
<body>
 
<div id="center">
<div id="sidebar">
{block:ifImage}<div class="image"><a href="/"><img src="{image:Sidebar}"></a></div>{/block:ifImage}
{block:Description}<div class="desc">{Description}</div>{/block:Description}
    <a href="#" class="lh">navigate</a>
    <div class="lb">
        <a href="/">index</a>
        <a href="/ask">enquire</a>
        {block:ifLink1}
        <a href="{text:Link 1}">{text:Link 1 Title}</a>
        {/block:ifLink1}{block:ifLink2}
        <a href="{text:Link 2}">{text:Link 2 Title}</a>
        {/block:ifLink2}{block:ifLink3}
        <a href="{text:Link 3}">{text:Link 3 Title}</a>
        {/block:ifLink3}{block:ifLink4}
        <a href="{text:Link 4}">{text:Link 4 Title}</a>
        {/block:ifLink4}
        <a href="/archive">history</a>
    </div>
</div>
 
<div id="content">
{block:Posts}
<div id="entry">
 
 
{block:ifSidePerma}{block:IndexPage}<div class="p">
<a href="{Permalink}" class="nc">{NoteCount}</a><br>
<a title="{TimeAgo}" href="{Permalink}">{DayofWeek}</a>{block:RebloggedFrom}<br><a title="{ReblogParentName}" href="{ReblogParentURL}">via</a>&nbsp;&nbsp;&middot;&nbsp;&nbsp;<a title="{ReblogRootName}" href="{ReblogRootURL}">origin</a>{/block:RebloggedFrom}
 
{block:ifTags}{block:HasTags}<div class="tags">
{block:Tags}<a href="{TagURL}">#{Tag}</a>{/block:Tags}
</div>{/block:HasTags}{/block:ifTags}
</div>{/block:IndexPage}{/block:ifSidePerma}
 
 
{block:Text}
{block:Title}<h2>{Title}</h2>{/block:Title}<div class="txt">{Body}</div>
{/block:Text}
 
{block:Link}
<a title="{URL}" href="{URL}"><h2> {Name} &rarr;</h2></a>
{block:Description}<div class="txt">{Description}</div>{/block:Description}
{/block:Link}
 
{block:Photo}
<div class="bx"><a href="{Permalink}"><img src="{PhotoURL-500}" alt="{PhotoAlt}"/></a></div>
{block:ifCaptions}{block:Caption}<div class="txt" style="margin-top:7px;">{Caption}</div>{/block:Caption}{/block:ifCaptions}
{/block:Photo}
 
{block:Photoset}
<div class="bx">{Photoset}</div>
{block:ifCaptions}{block:Caption}<div class="txt" style="margin-top:7px;">{Caption}</div>{/block:Caption}{/block:ifCaptions}
{/block:Photoset}
 
{block:Quote}
<div class="qut">{Quote}</div>
{block:PermalinkPage}<div class="src">{Source}</div>{/block:PermalinkPage}
{/block:Quote}
 
{block:Chat}
{block:Title}<h2>{Title}</h2>{/block:Title}
{block:Lines}<div class="lines {Alt}"><div class="{Alt} user_{UserNumber}">
{block:Label}<b>{Label}</b> {/block:Label}{Line}</div></div>{/block:Lines}
{/block:Chat}
 
{block:Audio}
{block:AudioPlayer}<div class="playh"><div class="play">{AudioPlayerGrey}
</div></div>{/block:AudioPlayer}
 
{block:AlbumArt}<div class="aa"><img src="{AlbumArtURL}"/></div>{/block:AlbumArt}
<div class="au">
    {block:TrackName}<span><b>{TrackName}</b></span>{/block:TrackName}
    {block:Artist}<span> by {Artist}</span>{/block:Artist}
    {block:PlayCount}<span>({PlayCount} plays)</span>{/block:PlayCount}
</div>
{/block:Audio}
 
{block:Video}
<div class="video">{Video-500}</div>
{block:ifCaptions}{block:Caption}<div class="txt" style="margin-top:7px;">{Caption}</div>{/block:Caption}{/block:ifCaptions}
{/block:Video}
 
{block:Answer}
<div class="ask"><b>{Asker}:</b> {Question}</div>
<div class="txt">{Answer}</div>
{/block:Answer}
 
{block:ifnotSidePerma}{block:IndexPage}<div class="p">
<a href="{Permalink}">{NoteCountWithLabel}</a>
<a title="{TimeAgo}" href="{Permalink}">{DayofWeek}</a>
{block:RebloggedFrom}
<a title="{ReblogParentName}" href="{ReblogParentURL}">via</a>
<a title="{ReblogRootName}" href="{ReblogRootURL}">origin</a>
{/block:RebloggedFrom}
 
{block:ifTags}{block:HasTags}<div class="tags">
{block:Tags}<a href="{TagURL}">#{Tag}</a>{/block:Tags}
</div>{/block:HasTags}{/block:ifTags}
</div>{/block:IndexPage}{/block:ifnotSidePerma}
 
 
{block:PermalinkPage}
{block:Date}
<div class="pph">
<div class="perma">
posted {TimeAgo} on {DayofMonthWithSuffix} {Month}
{block:RebloggedFrom}<br>
via <a href="{ReblogParentURL}">{ReblogParentName}</a>
source <a href="{ReblogRootURL}">{ReblogRootName}</a>
{/block:RebloggedFrom}
 
{block:HasTags}<br>filed under:
{block:Tags}<a href="{TagURL}">{Tag}</a> {/block:Tags}
{/block:HasTags}
</div>
 
{block:PostNotes}
<a href="#" class="pnh">{NoteCountWithLabel}</a>
<div class="pn">{PostNotes}</div>
{/block:PostNotes}
 
</div>
{/block:Date}
{/block:PermalinkPage}
 
{block:ContentSource}
<!-- {SourceURL}{block:SourceLogo}<img src="{BlackLogoURL}"
width="{LogoWidth}" height="{LogoHeight}" alt="{SourceTitle}" />
{/block:SourceLogo}
{block:NoSourceLogo}{SourceLink}{/block:NoSourceLogo} -->
{/block:ContentSource}
 
<!--{block:NoRebloggedFrom}{block:RebloggedFrom}{ReblogParentName}{/block:RebloggedFrom}{/block:NoRebloggedFrom} -->
 
</div>
{/block:Posts}
 
{block:ifPaginate}{block:Pagination}<div id="pag">
{block:PreviousPage}<a href="{PreviousPage}">back</a>{/block:PreviousPage} {CurrentPage} / {TotalPages}
{block:NextPage}<a href="{NextPage}">next</a>{/block:NextPage}
</div>{/block:Pagination}{/block:ifPaginate}
</div>
</div>
 

 
</body>
</html>
