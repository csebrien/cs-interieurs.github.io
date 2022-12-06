
<div class="container">
    <div class="top-footer">
        <div class="row">
            <div class="col-lg-6 col-md-12">
                
            </div>
           
            <div class="col-lg-6 col-md-12" style="float: right;">
                <div class="row">
                    <div  >
                        <div class="widget widget-contact text-right">
                            <h3 class="widget-title">{{ site.data.i18n.footer[page.lang].contactus }}</h3>
                            <ul class="ft-links">
                                <li>{{ site.data.i18n.contact[page.lang].address }}</li>
                                <li>{{ site.data.i18n.contact[page.lang].phone }}</li>
                                <li><a href="mailto:{{ site.data.i18n.contact[page.lang].email }}" title="">{{ site.data.i18n.contact[page.lang].email }}</a></li>
                            </ul><!--ft-links end-->
                        </div><!--widget-contact end-->
                    </div>
                    
                </div>
            </div>
        </div>
    </div><!--top-footer end-->
    <div class="bottom-footer">
        
        <ul class="btm-links">
            <li><a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.legal[page.lang].path }}" title="">{{ site.data.i18n.footer[page.lang].legal }}</a></li>
        </ul><!--btm-links end-->
        <div class="clearfix"></div>
    </div><!--bottom-footer end-->
</div>