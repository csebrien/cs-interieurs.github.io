---
layout: null
code: services
title: "Nos prestations"
permalink: /fr/nos_prestations # change corresponding i18n path variable if permalink changed here!
---
<html lang="fr">
{% include head.markdown %}
<body>

	{% include page-loading.markdown %}

	<div class="wrapper">
			
		<header>
			{% include header.markdown %}
		</header><!--header end-->

		{% include responsive-menu.markdown %}

		<section class="pager-section">
			<div class="container">
				<div class="pager-info">
					<h2>{{ site.data.i18n.services[page.lang].subtitle }}</h2>
					<span>{{ site.data.i18n.services[page.lang].subtitle2 }}</span>
				</div>
				<div class="pger-imgs style2">
					<div class="abt-imgz">
						<img src="{{ site.baseurl }}/assets/images/prestations.jpg" alt="">
					</div>
				</div><!--pger-imgs end-->
				<div class="clearfix"></div>
			</div>
		</section><!--pager-section end-->

		<section class="block">
			<div class="container">
				<div class="section-title style2 align-items-center">
					<h3 class="sub-title mw-45">{{ site.data.i18n.services[page.lang].section1_title }}</h3>
					<p class="mw-45">{{ site.data.i18n.services[page.lang].section1_description }}</p>
					<div class="clearfix"></div>
				</div>
				<div class="svs-section">
					<div class="svs-item">
						<div class="svs-img">
							<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit1_path }}" title="" ><img src="{{ site.baseurl }}/assets/images/images_prestations_570x465_1.jpg" alt="" class="w-100"></a>
						</div>
						<div class="svss-info">
							<h3><a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit1_path }}" title="">{{ site.data.i18n.services[page.lang].section1_benefit1_title }}</a></h3>
							<p>{{ site.data.i18n.services[page.lang].section1_benefit1_description }}</p>
							<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit1_path }}" title="" class="lnk-default2">{{ site.data.i18n.services[page.lang].section1_benefit1_button }} <i class="la la-arrow-right"></i></a>
						</div>
					</div><!--svs-item end-->
					<div class="svs-item">
						<div class="svs-img">
							<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit2_path }}" title="" ><img src="{{ site.baseurl }}/assets/images/images_prestations_570x465_2.jpg" alt="" class="w-100"></a>
						</div>
						<div class="svss-info">
							<h3><a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit2_path }}" title="">{{ site.data.i18n.services[page.lang].section1_benefit2_title }}</a></h3>
							<p>{{ site.data.i18n.services[page.lang].section1_benefit2_description }}</p>
							<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit2_path }}" title="" class="lnk-default2">{{ site.data.i18n.services[page.lang].section1_benefit2_button }} <i class="la la-arrow-right"></i></a>
						</div>
					</div><!--svs-item end-->
					<div class="svs-item">
						<div class="svs-img">
							<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit3_path }}" title="" ><img src="{{ site.baseurl }}/assets/images/images_prestations_570x465_3.jpg" alt="" class="w-100"></a>
						</div>
						<div class="svss-info">
							<h3><a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit3_path }}" title="">{{ site.data.i18n.services[page.lang].section1_benefit3_title }}</a></h3>
							<p>{{ site.data.i18n.services[page.lang].section1_benefit3_description }}</p>
							<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit3_path }}" title="" class="lnk-default2">{{ site.data.i18n.services[page.lang].section1_benefit3_button }} <i class="la la-arrow-right"></i></a>
						</div>
					</div><!--svs-item end-->
					<div class="svs-item">
						<div class="svs-img">
							<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit4_path }}" title="" ><img src="{{ site.baseurl }}/assets/images/images_prestations_570x465_4.jpg" alt="" class="w-100"></a>
						</div>
						<div class="svss-info">
							<h3><a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit4_path }}" title="">{{ site.data.i18n.services[page.lang].section1_benefit4_title }}</a></h3>
							<p>{{ site.data.i18n.services[page.lang].section1_benefit4_description }}</p>
							<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit4_path }}" title="" class="lnk-default2">{{ site.data.i18n.services[page.lang].section1_benefit4_button }} <i class="la la-arrow-right"></i></a>
						</div>
					</div><!--svs-item end-->
				</div><!--svs-section end-->
			</div>
		</section>

		<footer>
			{% include footer.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->



{% include scripts.markdown %}


</body>

</html>