
<div class="container">
    <div class="header-content">
        <div class="logo">
            <a href="index.html" title="">
                <img width="112" src="{{ site.baseurl }}/assets/images/logo.png" alt="">
            </a>
        </div><!--logo end-->
        <nav>
            {% if page.title != "soon" %}
            <ul>
                <li><a class="{% if page.title == "home" %}active{% endif %}" href="{{ site.baseurl }}/{{ page.lang }}/index.html" title="">{{ site.data.i18n.header[page.lang].home }}</a></li>
                <li><a class="{% if page.title == "services" %}active{% endif %}" href="{{ site.baseurl }}/{{ page.lang }}/services.html" title="">{{ site.data.i18n.header[page.lang].services }}</a></li>
                <li><a class="{% if page.title == "portfolio" %}active{% endif %}" href="{{ site.baseurl }}/{{ page.lang }}/portfolio.html" title="">{{ site.data.i18n.header[page.lang].portfolio }}</a></li>
                <li><a class="{% if page.title == "inspirations" %}active{% endif %}" href="{{ site.baseurl }}/{{ page.lang }}/inspirations.html" title="">{{ site.data.i18n.header[page.lang].inspirations }}</a></li>
                <li><a class="{% if page.title == "contact" %}active{% endif %}" href="{{ site.baseurl }}/{{ page.lang }}/contact.html" title="">{{ site.data.i18n.header[page.lang].contact }}</a></li>
            </ul>
            {% endif %}
        </nav><!--navigation end-->
        
        <ul class="mint-funcz">
            <li>
                <a href="https://www.pinterest.fr/carolinesebrien94/" title="" target="_blank">
                    <img src="{{ site.baseurl }}/assets/images/Pinterest_Rounded_icon-icons.com_61571.png" alt="">
                </a>
            </li>
            <li>
                <a href="https://www.instagram.com/cs_interieurs/?hl=fr" title="" target="_blank">
                    <img src="{{ site.baseurl }}/assets/images/Instagram_Rounded_icon-icons.com_61576.png" alt="">
                </a>
            </li>
        </ul>

         {% if page.title != "soon" %}
        <div class="contact-head-info">
            <a href="tel:0663271829" title="" style="font-size: 20px;" >+33 6 63271829</a>
        </div><!--contact-head-info end-->
        {% endif %}
        <div class="menu-btnn">
            <div class="menu-btn">
                <span class="bar1"></span>
                <span class="bar2"></span>
                <span class="bar3"></span>
            </div><!--menu-bar end-->
        </div>
    </div><!--header-content end-->
</div>