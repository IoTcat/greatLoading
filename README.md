# greatLoading
A simple solution for a busy loading web page.

```HTML
        <script src="https://cdn.bootcss.com/jquery/3.3.1/jquery.min.js"></script>

    <link rel="stylesheet" type="text/css" href="https://cdn.yimian.ac.cn/greatLoading/greadLoading.min.css">
    <style type="text/css">
        #loader-wrapper .loader-section {background: #067ad0;}
    </style>

<div id="loader-wrapper" >
    
<div id="loader"></div>
    
<div class="loader-section section-left"></div>
    
<div class="loader-section section-right"></div>
    
<div class="load_title">Yimian Login<br><span>Loading..</span></div>
</div>

<script type="text/javascript">
    $(window).on("load",function(){
        $('body').addClass('loaded');
        $('#loader-wrapper .load_title').remove();
    }); 

</script>
```