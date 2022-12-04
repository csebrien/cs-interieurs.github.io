---
layout: null
code: home
permalink: /fr/index.html # change corresponding i18n path variable if permalink changed here!
title: CS Intérieurs, décoration et design d'intérieur
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

		<section class="main-banner">
			<div class="container">
				<div class="row align-items-center">
					<div class="col-lg-6">
						<div class="banner-content">
							<h2 class="wow fadeInUp" data-wow-duration="1000ms">{{ site.data.i18n.home[page.lang].subtitle }}</h2>
							<p class="wow fadeInUp" data-wow-duration="1000ms" data-wow-delay="300ms">{{ site.data.i18n.home[page.lang].subtitle2 }}</p>
							<a href="nos_dernieres_realisations" title="" class="lnk-default wow fadeInUp" data-wow-duration="1000ms" data-wow-delay="500ms">{{ site.data.i18n.home[page.lang].mainbutton }} <i class="la la-arrow-right"></i> <span></span></a>
							
							<div class="clearfix"></div>
						</div><!--banner-content end-->
					</div>
					<div class="col-lg-6">
						<div class="banner-slider">
							<div class="banner-slide">
								<a href="nos_inspirations" title=""><img src="{{ site.baseurl }}/assets/images/home_slider_1.png" alt="" /></a>
							</div><!--banner-slide end-->
							<div class="banner-slide">
								<a href="nos_inspirations" title=""><img src="{{ site.baseurl }}/assets/images/home_slider_2.png" alt=""/></a>
							</div><!--banner-slide end-->
							<div class="banner-slide">
								<a href="nos_inspirations" title=""><img src="{{ site.baseurl }}/assets/images/home_slider_3.png" alt=""/></a>
							</div><!--banner-slide end-->
						</div><!--banner-slider end-->
					</div>
				</div>
			</div>
		</section><!--main-banner end-->

		<section class="block pb-0">
			<div class="container">
				<div class="about-us-section">
					<div class="row align-items-center">
						<div class="col-lg-6">
							<div class="abt-imgz">
								<img class="wow fadeInUp" data-wow-duration="1000ms" src="https://via.placeholder.com/309x463" alt="">
								<img class="wow fadeInRight" data-wow-duration="1000ms" data-wow-delay="400ms" src="https://via.placeholder.com/327x299" alt="">
							</div><!--abt-imgz end-->
							
						</div>
						<div class="col-lg-6">
							<div class="about-text">
								<h2 class="sub-title">{{ site.data.i18n.home[page.lang].section1_title }}</h2>
								<p>{{ site.data.i18n.home[page.lang].section1_subtitle }}</p>
								<a href="about.html" title="" class="lnk-default2">{{ site.data.i18n.home[page.lang].section1_button }} <i class="la la-arrow-right"></i></a>
							</div><!--about-text end-->
						</div>
					</div>
				</div><!--about-us-section end-->
			</div>
		</section>

		<section class="block">
			<div class="container">
				<div class="section-title align-items-center">
					<h3 class="sub-title">{{ site.data.i18n.home[page.lang].section2_title }}</h3>
					<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.portfolio[page.lang].path }}" title="" class="lnk-default2">{{ site.data.i18n.home[page.lang].section2_button }} <i class="la la-arrow-right"></i></a>
				</div><!--section-title end-->
				<div class="process-section">
					<ul>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section2_subtitle1 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section2_subdescription1 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section2_subtitle2 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section2_subdescription2 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section2_subtitle3 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section2_subdescription3 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						
					</ul>
					<div class="clearfix"></div>
				</div><!--process-section end-->
			</div>
		</section>

		<section class="block">
			<div class="container">
				<div class="section-title align-items-center">
					<h3 class="sub-title">{{ site.data.i18n.home[page.lang].section3_title }}</h3>
					<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.portfolio[page.lang].path }}" title="" class="lnk-default2">{{ site.data.i18n.home[page.lang].section3_button }} <i class="la la-arrow-right"></i></a>
				</div><!--section-title end-->
				<div class="process-section">
					<ul>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section3_subtitle1 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section3_subdescription1 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section3_subtitle2 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section3_subdescription2 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section3_subtitle3 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section3_subdescription3 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						
					</ul>
					<div class="clearfix"></div>
				</div><!--process-section end-->
			</div>
		</section>

		<section class="block2">
			<div class="fixed-bg bg1"></div>
			<div class="container">
				<div class="latest-projects-section">
					<div class="row">
						<div class="col-lg-5">
							<div class="project-text">
								<h3 class="sub-title">{{ site.data.i18n.home[page.lang].section4_title }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section4_subtitle }}</p>
								<a href="portfolio.html" title="" class="lnk-default2">{{ site.data.i18n.home[page.lang].section4_button }} <i class="la la-arrow-right"></i></a>
							</div><!--project-text end-->
						</div>
						<div class="col-lg-7">
							<div class="project-carousel">
								<div class="project-item">
									<img src="https://via.placeholder.com/345x453" alt="">
									<div class="project-info">
										<h3><a href="portfolio-details.html" title="">Living room</a></h3>
										<span>59 projects</span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<img src="https://via.placeholder.com/345x453" alt="">
									<div class="project-info">
										<h3><a href="portfolio-details.html" title="">Kitchen</a></h3>
										<span>75 projects</span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<img src="https://via.placeholder.com/345x453" alt="">
									<div class="project-info">
										<h3><a href="portfolio-details.html" title="">Commercial</a></h3>
										<span>49 projects</span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<img src="https://via.placeholder.com/345x453" alt="">
									<div class="project-info">
										<h3><a href="portfolio-details.html" title="">Living room</a></h3>
										<span>59 projects</span>
									</div><!--project-info end-->
								</div><!--project-item end-->
							</div><!--project-carousel end-->
						</div>
					</div>
				</div><!--latest-projects-section end-->
			</div>
		</section>

		<section class="block testi-section">
			<div class="container">
				<div class="section-title">
					<h3 class="sub-title">{{ site.data.i18n.home[page.lang].section5_title }}</h3>
				</div><!--section-title end-->
				<div class="testimonial-section">
					<div class="row testi-carousel">
						<div class="col-lg-4">
							<div class="testi-slide">
								<div class="testi-head">
									<img src="https://via.placeholder.com/70x70" alt="">
									<div class="user-info">
										<h3>Alana Francheska</h3>
										<span>Lorem company</span>
									</div>
								</div>
								<p>Integer vehicula, est vel posuere gravida, eros tellus fermentum magna, sit amet mattis mauris quam a nisl. Mauris vitae commodo elit.  In hac habitasse platea.</p>
								<ul class="rating">
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
								</ul>
							</div><!--testi-slide end-->
						</div>
						<div class="col-lg-4">
							<div class="testi-slide">
								<div class="testi-head">
									<img src="https://via.placeholder.com/70x70" alt="">
									<div class="user-info">
										<h3>Donald Pakura</h3>
										<span>Lorem company</span>
									</div>
								</div>
								<p>Integer vehicula, est vel posuere gravida, eros tellus fermentum magna, sit amet mattis mauris quam a nisl. Mauris vitae commodo elit.  In hac habitasse platea.</p>
								<ul class="rating">
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
								</ul>
							</div><!--testi-slide end-->
						</div>
						<div class="col-lg-4">
							<div class="testi-slide">
								<div class="testi-head">
									<img src="https://via.placeholder.com/70x70" alt="">
									<div class="user-info">
										<h3>Sara Kristian</h3>
										<span>Lorem company</span>
									</div>
								</div>
								<p>Integer vehicula, est vel posuere gravida, eros tellus fermentum magna, sit amet mattis mauris quam a nisl. Mauris vitae commodo elit.  In hac habitasse platea.</p>
								<ul class="rating">
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
								</ul>
							</div><!--testi-slide end-->
						</div>
						<div class="col-lg-4">
							<div class="testi-slide">
								<div class="testi-head">
									<img src="https://via.placeholder.com/70x70" alt="">
									<div class="user-info">
										<h3>Alana Francheska</h3>
										<span>Lorem company</span>
									</div>
								</div>
								<p>Integer vehicula, est vel posuere gravida, eros tellus fermentum magna, sit amet mattis mauris quam a nisl. Mauris vitae commodo elit.  In hac habitasse platea.</p>
								<ul class="rating">
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
								</ul>
							</div><!--testi-slide end-->
						</div>
						<div class="col-lg-4">
							<div class="testi-slide">
								<div class="testi-head">
									<img src="https://via.placeholder.com/70x70" alt="">
									<div class="user-info">
										<h3>Alana Francheska</h3>
										<span>Lorem company</span>
									</div>
								</div>
								<p>Integer vehicula, est vel posuere gravida, eros tellus fermentum magna, sit amet mattis mauris quam a nisl. Mauris vitae commodo elit.  In hac habitasse platea.</p>
								<ul class="rating">
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
								</ul>
							</div><!--testi-slide end-->
						</div>
					</div>
				</div><!--testimonial-section end-->
			</div>
		</section>

		<section class="block">
			<div class="container">
				<h3 class="sub-title">Our Blog and News</h3>
				<div class="blog-posts">
					<div class="row">
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<img src="https://via.placeholder.com/473x373" alt="">
									<span class="category">Interior design</span>
								</div>
								<div class="blog-info">
									<span>Jul 21, 2020</span>
									<h2 class="blog-title"><a href="blog-single.html" title="">Types of home</a></h2>
									<p>Sed pellentesque velit a elit mattis, a volutpat neque feugiat</p>
									<a href="blog-single.html" title="" class="lnk-default2">View more <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<img src="https://via.placeholder.com/473x373" alt="">
									<span class="category">Interior design</span>
								</div>
								<div class="blog-info">
									<span>Jul 21, 2020</span>
									<h2 class="blog-title"><a href="blog-single.html" title="">Purchase of furniture</a></h2>
									<p>Sed pellentesque velit a elit mattis, a volutpat neque feugiat</p>
									<a href="blog-single.html" title="" class="lnk-default2">View more <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<img src="https://via.placeholder.com/473x373" alt="">
									<span class="category">Interior design</span>
								</div>
								<div class="blog-info">
									<span>Jul 21, 2020</span>
									<h2 class="blog-title"><a href="blog-single.html" title="">Kitchen design ideas</a></h2>
									<p>Sed pellentesque velit a elit mattis, a volutpat neque feugiat</p>
									<a href="blog-single.html" title="" class="lnk-default2">View more <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
					</div>
				</div><!---blog-posts end-->
			</div>			
		</section>

		<footer>
			{% include footer.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->

{% include scripts.markdown %}


</body>

</html>
