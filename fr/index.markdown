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
							<div class="abt-imgz" style="margin-left:150px; text-align: center;">
								<img class="wow fadeInUp" data-wow-duration="1000ms" src="{{ site.baseurl }}/assets/images/photo-profil.jpg" alt="">
							</div><!--abt-imgz end-->
							
						</div>
						<div class="col-lg-6">
							<div class="about-text">
								<h2 class="sub-title">{{ site.data.i18n.home[page.lang].section1_title }}</h2>
								<p>{{ site.data.i18n.home[page.lang].section1_subtitle }}</p>
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
								<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.portfolio[page.lang].path }}" title="" class="lnk-default2">{{ site.data.i18n.home[page.lang].section4_button }} <i class="la la-arrow-right"></i></a>
							</div><!--project-text end-->
						</div>
						<div class="col-lg-7">
							<div class="project-carousel">
								<div class="project-item">
									<a href="/fr/sejour_projet_madeleine" title=""><img src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_13.jpg" alt=""></a>
									<div class="project-info">
										<h3><a href="/fr/sejour_projet_madeleine" title="">Séjour projet Madeleine</a></h3>
										<span></span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<a href="/fr/suite_parentale" title=""><img src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_12.jpg" alt=""></a>
									<div class="project-info">
										<h3><a href="/fr/suite_parentale" title="">Suite Parentale</a></h3>
										<span></span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<a href="/fr/agencement_meuble_tv" title=""><img src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_11.jpg" alt=""></a>
									<div class="project-info">
										<h3><a href="/fr/agencement_meuble_tv" title="">Agencement de meuble TV</a></h3>
										<span></span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<a href="/fr/maison_de_famille" title=""><img src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_9.jpg" alt=""></a>
									<div class="project-info">
										<h3><a href="/fr/maison_de_famille" title="">Maison de famille 1850</a></h3>
										<span></span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<a href="/fr/home_staging_old_house" title=""><img src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_10.jpg" alt=""></a>
									<div class="project-info">
										<h3><a href="/fr/home_staging_old_house" title="">Home staging</a></h3>
										<span></span>
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
						<div class="col-lg-12">
							<div class="testi-slide">
								<div class="testi-head">
									<img src="{{ site.baseurl }}/assets/images/myriam.jpg" alt="">
									<div class="user-info">
										<h3>Myriam</h3>
										<span></span>
									</div>
								</div>
								<p>Caroline a été d'une efficacité incroyable concernant notre projet d'aménagement ! Après notre demande, nous avons très vite reçu les plans d'intérieur et l'agencement. C'était parfait ! Tous nos critères étaient remplis (Rangement, verrière, bureau, bibliothèque, luminosité, etc.) Grâce à elle j'ai enfin réussi à me projeter dans ce futur appartement qu'on achète ! Je recommande chaudement.</p>
								<ul class="rating">
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
								</ul>
							</div><!--testi-slide end-->
						</div>
						<div class="col-lg-12">
							<div class="testi-slide">
								<div class="testi-head">
									<img src="{{ site.baseurl }}/assets/images/laura.jpg" alt="">
									<div class="user-info">
										<h3>Laura</h3>
										<span></span>
									</div>
								</div>
								<p>Caroline s’est occupé de mon intérieur comme personne !
Mes travaux ont été réalisé assez rapidement et j’ai pu donc emménagé vite dans mon appartement grâce à une logistique très bien menée de sa part.
Je suis ravie de la prestation !
Je recommande !</p>
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
				<h3 class="sub-title">Ils ont retenu notre attention</h3>
				<div class="blog-posts">
					<div class="row">
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="https://www.deco.fr/deco-piece/79528-comment-decorer-la-chambre-de-bebe-avec-un-petit-budget" title="" target="_blank"><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_home_blog_1.jpg" alt=""></a>
									<span class="category">deco.fr</span>
								</div>
								<div class="blog-info">
									<span>26 janvier 2023</span>
									<h2 class="blog-title"><a href="https://www.deco.fr/deco-piece/79528-comment-decorer-la-chambre-de-bebe-avec-un-petit-budget" title="" target="_blank">Chambre de bébé</a></h2>
									<p>Comment décorer une chambre de bébé avec un petit budget?</p>
									<a href="https://www.deco.fr/deco-piece/79528-comment-decorer-la-chambre-de-bebe-avec-un-petit-budget" title=""   target="_blank" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="https://www.deco.fr/photos/diaporama-10-petites-salles-bains-d_708" title="" target="_blank"><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_home_blog_3.jpg" alt=""></a>
									<span class="category">deco.fr</span>
								</div>
								<div class="blog-info">
									<span>25 janvier 2023</span>
									<h2 class="blog-title"><a href="https://www.deco.fr/photos/diaporama-10-petites-salles-bains-d_708" title="" target="_blank">Les petites salles de bain</a></h2>
									<p>Comment bien les agencer?</p>
									<a href="https://www.deco.fr/photos/diaporama-10-petites-salles-bains-d_708" title="" class="lnk-default2" target="_blank">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="https://www.deco.fr/diapos-deco/73598-20-objets-deco-a-acquerir-pour-une-maison-de-famille" title="" target="_blank"><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_home_blog_2.jpg" alt=""></a>
									<span class="category">deco.fr</span>
								</div>
								<div class="blog-info">
									<span>31 août 2019</span>
									<h2 class="blog-title"><a href="https://www.deco.fr/diapos-deco/73598-20-objets-deco-a-acquerir-pour-une-maison-de-famille" title="" target="_blank">Objets déco</a></h2>
									<p>20 objets déco pour une maison de famille</p>
									<a href="https://www.deco.fr/diapos-deco/73598-20-objets-deco-a-acquerir-pour-une-maison-de-famille" title="" class="lnk-default2" target="_blank">Voir plus <i class="la la-arrow-right"></i></a>
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
