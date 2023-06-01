---
layout: null
code: portfolio
title: "Nos dernières réalisations"
permalink: /fr/nos_dernieres_realisations # change corresponding i18n path variable if permalink changed here!
---
<html lang="en">
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
					<h2>Réalisations</h2>
					<span>Venez découvrir les projets réalisés pour nos clients</span>
				</div>
				<div class="pger-imgs style2">
					<div class="abt-imgz">
						<img src="{{ site.baseurl }}/assets/images/portfolio.jpg" alt="">
					</div>
				</div><!--pger-imgs end-->
				<div class="clearfix"></div>
			</div>
		</section><!--pager-section end-->

		<section class="block">
			<div class="container">
				<div class="blog-posts blog-page">
					<div class="row">
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="/fr/maison_de_famille" title=""><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_9.jpg" alt=""/></a>
									
								</div>
								<div class="blog-info">
									{% assign current_page = site.pages | where: "url", "/fr/maison_de_famille" | first %}
									<span id="post-date">{{ current_page.last_modified_at }}</span>
									<h2 class="blog-title"><a href="/fr/maison_de_famille" title="">Maison de famille 1850</a></h2>
									<p>Quand le contemporain rejoint l'ancien</p>
									<a href="/fr/maison_de_famille" title="" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="/fr/home_staging_old_house" title=""><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_10.jpg" alt=""/></a>
									
								</div>
								<div class="blog-info">
									{% assign current_page = site.pages | where: "url", "/fr/home_staging_old_house" | first %}
									<span id="post-date">{{ current_page.last_modified_at }}</span>
									<h2 class="blog-title"><a href="/fr/home_staging_old_house" title="">Home staging</a></h2>
									<p>Cette maison avait besoin d’un bon coup de frais !</p>
									<a href="/fr/home_staging_old_house" title="" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="/fr/renovation_totale_pour_colocation" title=""><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_8.jpg" alt=""/></a>
									
								</div>
								<div class="blog-info">
									{% assign current_page = site.pages | where: "url", "/fr/renovation_totale_pour_colocation" | first %}
									<span id="post-date">{{ current_page.last_modified_at }}</span>
									<h2 class="blog-title"><a href="/fr/renovation_totale_pour_colocation" title="">Renovation totale pour colocation</a></h2>
									<p>Réaménagement totale d’une maison de 120 m2</p>
									<a href="/fr/renovation_totale_pour_colocation" title="" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="/fr/chambre_bebe" title=""><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_1.jpg" alt=""/></a>
									
								</div>
								<div class="blog-info">
									{% assign current_page = site.pages | where: "url", "/fr/chambre_bebe" | first %}
									<span id="post-date">{{ current_page.last_modified_at }}</span>
									<h2 class="blog-title"><a href="/fr/chambre_bebe" title="">Chambre de bébé safari</a></h2>
									<p>Comme un voyage avec les animaux de la savane</p>
									<a href="/fr/chambre_bebe" title="" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="/fr/sejour_et_salle_a_manger" title=""><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_2.jpg" alt=""></a>
									
								</div>
								<div class="blog-info">
									{% assign current_page = site.pages | where: "url", "/fr/sejour_et_salle_a_manger" | first %}
									<span id="post-date">{{ current_page.last_modified_at }}</span>
									<h2 class="blog-title"><a href="/fr/sejour_et_salle_a_manger" title="">Séjour ouvert</a></h2>
									<p>Un espace accueillant et lumineux</p>
									<a href="/fr/sejour_et_salle_a_manger" title="" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="/fr/chambre_enfant" title=""><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_3.jpg" alt=""></a>
									
								</div>
								<div class="blog-info">
									{% assign current_page = site.pages | where: "url", "/fr/chambre_enfant" | first %}
									<span id="post-date">{{ current_page.last_modified_at }}</span>
									<h2 class="blog-title"><a href="/fr/chambre_enfant" title="">Chambre d'enfant bucolique</a></h2>
									<p>Mélange de moderne et d’ancien</p>
									<a href="/fr/chambre_enfant" title="" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="/fr/chambre_parentale" title=""><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_4.jpg" alt=""></a>
									
								</div>
								<div class="blog-info">
									{% assign current_page = site.pages | where: "url", "/fr/chambre_parentale" | first %}
									<span id="post-date">{{ current_page.last_modified_at }}</span>
									<h2 class="blog-title"><a href="/fr/chambre_parentale" title="">Chambre parentale</a></h2>
									<p>Un style intemporel et chaleureux</p>
									<a href="/fr/chambre_parentale" title="" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="/fr/cuisine" title=""><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_5.jpg" alt=""></a>
									
								</div>
								<div class="blog-info">
									{% assign current_page = site.pages | where: "url", "/fr/cuisine" | first %}
									<span id="post-date">{{ current_page.last_modified_at }}</span>
									<h2 class="blog-title"><a href="/fr/cuisine" title="">Cuisine</a></h2>
									<p>Simplicité et praticité avec un total look blanc</p>
									<a href="/fr/cuisine" title="" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="/fr/renovation_pour_location" title=""><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_portfolio_6.jpg" alt=""></a>
									
								</div>
								<div class="blog-info">
									{% assign current_page = site.pages | where: "url", "/fr/renovation_pour_location" | first %}
									<span id="post-date">{{ current_page.last_modified_at }}</span>
									<h2 class="blog-title"><a href="/fr/renovation_pour_location" title="">Rénovation avant mise en location</a></h2>
									<p>Transformation d’un T2 daté en T3 lumineux</p>
									<a href="/fr/renovation_pour_location" title="" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-6 col-12">
							<div class="blog-post">
								<div class="blog-thumbnail">
									<a href="/fr/projection_3d_photoréalisme" title=""><img class="blog-thumbnail-img" src="{{ site.baseurl }}/assets/images/images_portfolio_7.jpg" alt=""></a>
									
								</div>
								<div class="blog-info">
									{% assign current_page = site.pages | where: "url", "/fr/projection_3d_photoréalisme" | first %}
									<span id="post-date">{{ current_page.last_modified_at }}</span>
									<h2 class="blog-title"><a href="/fr/projection_3d_photoréalisme" title="">Projection 3D Photoréalisme</a></h2>
									<p>Visuel 3D d'un T3</p>
									<a href="/fr/projection_3d_photoréalisme" title="" class="lnk-default2">Voir plus <i class="la la-arrow-right"></i></a>
								</div>
							</div><!--blog-post end-->
						</div>
					</div>
				</div><!--blog-posts end-->
				<!--div class="mint-pagination">
					<ul class="paginated">
						<li>
							<a href="#" title=""><i class="fa fa-angle-left"></i></a>
							<a href="#" title=""><i class="fa fa-angle-right"></i></a>
						</li>
					</ul>
				</div--><!--mint-pagination end-->
			</div>
		</section>

		<footer>
			{% include footer.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->



{% include scripts.markdown %}


</body>

</html>