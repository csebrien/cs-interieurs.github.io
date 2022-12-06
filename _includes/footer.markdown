
<div class="container">
    <div class="top-footer">
        <div class="row">
            <div class="col-lg-6 col-md-12">
                <div class="widget widget-info">
                    <h3 class="widget-title">NEWSLETTER</h3>
                    <form class="widget-form">
                        <input type="text" name="email" placeholder="Your e-mail">
                        <button type="submit"><i class="la la-arrow-right"></i></button>
                    </form>
                    <span>Sign up to receive sprecial offers!</span>
                    <ul class="social-links">
                        <li><a href="https://www.pinterest.fr/carolinesebrien94/" title="" target="_blank"><i class="fab fa-pinterest-p"></i></a></li>
                        <li><a href="https://www.instagram.com/cs_interieurs/?hl=fr" title="" target="_blank"><i class="fab fa-instagram"></i></a></li>
                        <li><a href="#" title="" target="_blank"><i class="fab fa-facebook-f"></i></a></li>
                        <li><a href="#" title="" target="_blank"><i class="fab fa-linkedin"></i></a></li>
                        <li><a href="#" title="" target="_blank"><i class="fab fa-twitter"></i></a></li>
                    </ul><!--social-links end-->
                </div><!--widget-info end-->
            </div>
            <div class="col-lg-6 col-md-12">
                <div class="row">
                    <div class="col-lg-4 col-md-4 col-sm-6 col-12">
                        <div class="widget widget-category text-right">
                            <h3 class="widget-title">Contact Us</h3>
                            <ul class="ft-links">
                                <li><a href="#" title="">Decor</a></li>
                                <li><a href="#" title="">Furniture</a></li>
                                <li><a href="#" title="">Lighting</a></li>
                                <li><a href="#" title="">Interior design</a></li>
                                <li><a href="#" title="">Architecture design</a></li>
                                <li><a href="#" title="">Commercial design</a></li>
                            </ul><!--ft-links end-->
                        </div><!--widget-contact end-->
                    </div>
                    <div class="col-lg-4 col-md-4 col-sm-6 col-12">
                        <div class="widget widget-category text-right">
                            <h3 class="widget-title">Contact Us</h3>
                            <ul class="ft-links">
                                <li><a href="#" title="">Decor</a></li>
                                <li><a href="#" title="">Furniture</a></li>
                                <li><a href="#" title="">Lighting</a></li>
                                <li><a href="#" title="">Interior design</a></li>
                                <li><a href="#" title="">Architecture design</a></li>
                                <li><a href="#" title="">Commercial design</a></li>
                            </ul><!--ft-links end-->
                        </div><!--widget-contact end-->
                    </div>
                    <div class="col-lg-4 col-md-4 col-sm-6 col-12">
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
        <div class="ft-logo">
            <img src="{{ site.baseurl }}/assets/images/ft-logo.png" alt="">
        </div><!--ft-logo end-->
        <ul class="btm-links">
            <li><a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.legal[page.lang].path }}" title="">{{ site.data.i18n.footer[page.lang].legal }}</a></li>
        </ul><!--btm-links end-->
        <div class="clearfix"></div>
    </div><!--bottom-footer end-->
    
</div>