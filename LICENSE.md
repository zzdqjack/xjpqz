<div class="f_2">
           <h5>标签</h5>
             <div id="wpcumuluswidgetcontent9290225" style="height:106px; margin-top:-10px;">
               <p >
                {dede:tag row='30' getall='1' sort='month'}
                <a href='[field:link/]' title="[field:tag /]" target="_blank" style="font-size:12px;">[field:tag /]</a>
                {/dede:tag} 
               </p>
               <p>www.xiuzhanwang.com<a href="http://www.macromedia.com/go/getflashplayer">Flash Player</a> 9 or better.</p>
             </div>
             <script "type=text/javascript">
                 var kk ="{dede:tag row='30' getall='1' sort='month'}<a href='[field:link/]' title='[field:tag /]' target='_blank' style='font-size:12px;'>[field:tag /]</a>{/dede:tag}";
             //  alert(kk);
             var widget_so6341666 = new SWFObject("{dede:global.cfg_templets_skin/}/images/tagcloud.swf?r=7553157", "tagcloudflash", "220", "145", "9", "#ffffff");widget_so6341666.addParam("wmode", "transparent");widget_so6341666.addParam("allowScriptAccess", "always");widget_so6341666.addVariable("tcolor", "0xFFFFFF");widget_so6341666.addVariable("tcolor2", "0xFFFFFF");widget_so6341666.addVariable("hicolor", "0x999999");widget_so6341666.addVariable("tspeed", "150");widget_so6341666.addVariable("distr", "true");widget_so6341666.addVariable("mode", "tags");widget_so6341666.addVariable("tagcloud", "<tags>"+kk+"</tags>");widget_so6341666.write("wpcumuluswidgetcontent9290225");
             </script>
        </div>
