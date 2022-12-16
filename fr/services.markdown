---
layout: null
code: services
title: "Nos prestations"
permalink: /fr/nos_prestations # change corresponding i18n path variable if permalink changed here!
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
					<h2>{{ site.data.i18n.services[page.lang].subtitle }}</h2>
					<span>{{ site.data.i18n.services[page.lang].subtitle2 }}</span>
				</div>
				<div class="pger-imgs style2">
					<div class="abt-imgz">
						<img src="{{ site.baseurl }}/assets/images/prestations.png" alt="">
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
							<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit1_path }}" title="" class="lnk-default2"><img src="{{ site.baseurl }}/assets/images/images_prestations_570x465_1.png" alt="" class="w-100"></a>
						</div>
						<div class="svss-info">
							<h3><a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit1_path }}" title="">{{ site.data.i18n.services[page.lang].section1_benefit1_title }}</a></h3>
							<p>{{ site.data.i18n.services[page.lang].section1_benefit1_description }}</p>
							<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.services[page.lang].benefit1_path }}" title="" class="lnk-default2">{{ site.data.i18n.services[page.lang].section1_benefit1_button }} <i class="la la-arrow-right"></i></a>
						</div>
					</div><!--svs-item end-->
					<div class="svs-item">
						<div class="svs-img">
							<img src="{{ site.baseurl }}/assets/images/images_prestations_570x465_2.png" alt="" class="w-100">
						</div>
						<div class="svss-info">
							<h3><a href="#" title="">{{ site.data.i18n.services[page.lang].section1_benefit2_title }}</a></h3>
							<p>{{ site.data.i18n.services[page.lang].section1_benefit2_description }}</p>
							<a href="#" title="" class="lnk-default2">{{ site.data.i18n.services[page.lang].section1_benefit2_button }} <i class="la la-arrow-right"></i></a>
						</div>
					</div><!--svs-item end-->
					<div class="svs-item">
						<div class="svs-img">
							<img src="{{ site.baseurl }}/assets/images/images_prestations_570x465_3.png" alt="" class="w-100">
						</div>
						<div class="svss-info">
							<h3><a href="#" title="">{{ site.data.i18n.services[page.lang].section1_benefit3_title }}</a></h3>
							<p>{{ site.data.i18n.services[page.lang].section1_benefit3_description }}</p>
							<a href="#" title="" class="lnk-default2">{{ site.data.i18n.services[page.lang].section1_benefit3_button }} <i class="la la-arrow-right"></i></a>
						</div>
					</div><!--svs-item end-->
					<div class="svs-item">
						<div class="svs-img">
							<img src="{{ site.baseurl }}/assets/images/images_prestations_570x465_4.png" alt="" class="w-100">
						</div>
						<div class="svss-info">
							<h3><a href="#" title="">{{ site.data.i18n.services[page.lang].section1_benefit4_title }}</a></h3>
							<p>{{ site.data.i18n.services[page.lang].section1_benefit4_description }}</p>
							<a href="#" title="" class="lnk-default2">{{ site.data.i18n.services[page.lang].section1_benefit4_button }} <i class="la la-arrow-right"></i></a>
						</div>
					</div><!--svs-item end-->
				</div><!--svs-section end-->
			</div>
		</section>

		<section class="block">
			<div class="fixed-bg bg1"></div>
			<div class="container">
				<h3 class="sub-title mw-45 mgb-100">Our work process make your dream true</h3><!--sub-title end-->
				<div class="processs-section">
					<div class="row">
						<div class="col-lg-4 col-md-6 col-sm-12">
							<div class="process-col">
								<div class="pro-head">
									<h2>Architectural development <strong>01.</strong></h2>
								</div>
								<ul>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Development of the object concept </h3>
												<div class="dott"></div>
											</div>
											<ul>
												<li>Planning decision</li>
												<li>Development of the object's style direction and its functional content</li>
												<li>Identification of important indicators of the technical and economic justification of the project</li>
											</ul>
										</div>
									</li>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Development of the object concept </h3>
												<div class="dott"></div>
											</div>
											<ul>
												<li>basic solutions for spatial planning, stylistic and architectural design of the object</li>
											</ul>
										</div>
									</li>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Development of the object concept </h3>
												<div class="dott"></div>
											</div>
											<ul>
												<li>The General plan of the site</li>
												<li>Foundation design</li>
												<li>Structural plan of walls and floors</li>
												<li>Rafters and roof plan</li>
												<li>The project of engineering networks</li>
											</ul>
										</div>
									</li>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Development of the object concept </h3>
												<div class="dott"></div>
											</div>
										</div>
									</li>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Development of the object concept </h3>
												<div class="dott"></div>
											</div>
										</div>
									</li>
								</ul>
							</div><!--process-col end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-12">
							<div class="process-col">
								<div class="pro-head">
									<h2>Interior <br />design <strong>02.</strong></h2>
								</div>
								<ul>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Planning solution development </h3>
												<div class="dott"></div>
											</div>
											<ul>
												<li>Measurings</li>
												<li>Draft design concept</li>
												<li>Object budgeting</li>
											</ul>
										</div>
									</li>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Planning solution development</h3>
												<div class="dott"></div>
											</div>
											<ul>
												<li>Planning decision</li>
												<li>3D-visualization</li>
											</ul>
										</div>
									</li>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Planning solution development </h3>
												<div class="dott"></div>
											</div>
											<ul>
												<li>Full package of working documentation</li>
												<li>Selection of materials</li>
												<li>Architectural supervision</li>
											</ul>
										</div>
									</li>
								</ul>
							</div><!--process-col end-->
						</div>
						<div class="col-lg-4 col-md-6 col-sm-12">
							<div class="process-col">
								<div class="pro-head">
									<h2>Commercial interior design <strong>03.</strong></h2>
								</div>
								<ul>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Dive into the project: </h3>
												<div class="dott"></div>
											</div>
											<ul>
												<li>Meeting and discussion of the idea</li>
												<li>Measurements</li>
												<li>Concept development</li>
												<li>Object budgeting</li>
											</ul>
										</div>
									</li>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Design </h3>
												<div class="dott"></div>
											</div>
											<ul>
												<li>Planning decision</li>
												<li>3D visualization of premises</li>
											</ul>
										</div>
									</li>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Implementation</h3>
												<div class="dott"></div>
											</div>
											<ul>
												<li>Full package of working documentation</li>
												<li>Selection of face, finishing materials and furniture </li>
												<li>Architectural supervision</li>
											</ul>
										</div>
									</li>
									<li>
										<div class="prc-sorw">
											<div class="pz-head">
												<h3>Opening </h3>
												<div class="dott"></div>
											</div>
										</div>
									</li>
								</ul>
							</div><!--process-col end-->
						</div>
					</div>
				</div><!--process-section end-->
			</div>
		</section>

		<section class="block">
			<div class="container">
				<div class="consult-text style2 mt-0">
					<h3 class="sub-title">Get a free consultation. Just leave a request below</h3>
					<form class="subsc-form">
						<input type="text" name="name">
						<button type="submit" class="lnk-default">Сallback <i class="la la-arrow-right"></i> <span></span></button>
					</form>
				</div><!--consult-text end-->
				<div class="cnst-img">
					<img src="https://via.placeholder.com/959x640" alt="">
				</div><!--cnst-img end-->
			</div>
		</section>

		<footer>
			{% include footer.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->



{% include scripts.markdown %}


</body>

</html>