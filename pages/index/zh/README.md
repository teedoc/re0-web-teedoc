
---
title: RE0：从零开始的异世界生活 （WEB版）
keywords: teedoc, markdown, re0-web
desc: RE0：从零开始的异世界生活 （WEB版）, 使用 teedoc 生成的 re0 小说 web 版本(在线阅读版本/在线小说)
id: home_page
---


<div>
    <!-- <script src="/static/js/scrolloverflow.min.js"></script> -->
    <script src="/static/js/jquery.fullpage.min.js"></script>
    <link rel="stylesheet" href="/static/css/jquery.fullpage.min.css" type="text/css"/>
</div>

<div id="fullpage">
    <div class="section" style="height: 100vh;">
        <div>
            <h1><span>RE0：从零开始的异世界生活 （WEB版）</span></h1>
        </div>
        <div class="big_btn_wrapper">
            <div class="big_btn">
                <a href="/gitbook/book/markdown/ch/">开始阅读</a>
            </div>
        </div>
    </div>
</div>


<div>
<script type='text/javascript'>
    $(document).ready(function () {
        var html = $("#page_footer").html();
        $("#page_footer").remove();
        $("#fullpage").append('<div id="page_footer" class="section fp-auto-height">' + html + "</div>");
        var nav_height = $("#navbar").height();
        $('#fullpage').fullpage({
            menu: '#navbar',
            navigation: true,
            css3: true,
            // dragAndMove: true,
            paddingBottom: nav_height + "px"
            // scrollOverflow: true,
	        // scrollOverflowReset: true,
            // fixedElements: "#navbar"
        });
        $("#learn_more").on("click", function(){
            $.fn.fullpage.moveTo(2);
        });
        $("#to_top").on("click", function(){
            $.fn.fullpage.moveTo(1);
        });
    });
</script>
</div>


