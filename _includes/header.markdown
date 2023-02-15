
<div class="container">
    <div class="header-content">
        <div class="logo">
            <a href="index.html" title="">
                <img width="112" src="{{ site.baseurl }}/assets/images/logo.png" alt="">
            </a>
        </div><!--logo end-->
        <nav>
            {% if page.code != "soon" %}
            <ul>
                <li><a class="{% if page.code == "home" %}active{% endif %}" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.home[page.lang].path }}" title="">{{ site.data.i18n.header[page.lang].home }}</a></li>
                <li><a class="{% if page.code == "services" %}active{% endif %}" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].path }}" title="">{{ site.data.i18n.header[page.lang].services }}</a></li>
                <li><a class="{% if page.code == "portfolio" %}active{% endif %}" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.portfolio[page.lang].path }}" title="">{{ site.data.i18n.header[page.lang].portfolio }}</a></li>
                <li><a class="{% if page.code == "inspirations" %}active{% endif %}" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.inspirations[page.lang].path }}" title="">{{ site.data.i18n.header[page.lang].inspirations }}</a></li>
                <li><a class="{% if page.code == "contact" %}active{% endif %}" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.contact[page.lang].path }}" title="">{{ site.data.i18n.header[page.lang].contact }}</a></li>
            </ul>
            {% endif %}
        </nav><!--navigation end-->
        
        <!--ul class="mint-funcz">
            <li>
                <a href="https://www.pinterest.fr/csinterieurs/" title="" target="_blank">
                    <img src="{{ site.baseurl }}/assets/images/Pinterest_Rounded_icon-icons.com_61571.png" alt="">
                </a>
            </li>
            <li>
                <a href="https://www.instagram.com/cs_interieurs/?hl=fr" title="" target="_blank">
                    <img src="{{ site.baseurl }}/assets/images/Instagram_Rounded_icon-icons.com_61576.png" alt="">
                </a>
            </li>
        </ul-->

        <ul class="mint-funcz">
            <li><a href="https://www.pinterest.fr/csinterieurs/" title="" target="_blank"><i class="fab fa-pinterest-p"></i></a></li>
            <li><a href="https://www.instagram.com/cs_interieurs/?hl=fr" title="" target="_blank"><i class="fab fa-instagram"></i></a></li>
            <!--li><a href="#" title="" target="_blank"><i class="fab fa-facebook-f"></i></a></li>
            <li><a href="#" title="" target="_blank"><i class="fab fa-linkedin"></i></a></li>
            <li><a href="#" title="" target="_blank"><i class="fab fa-twitter"></i></a></li-->
        </ul>

        <div class="menu-btnn">
            <div class="menu-btn">
                <span class="bar1"></span>
                <span class="bar2"></span>
                <span class="bar3"></span>
            </div><!--menu-bar end-->
        </div>
    </div><!--header-content end-->
</div>