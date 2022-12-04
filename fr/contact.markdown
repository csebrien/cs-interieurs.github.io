---
layout: null
code: contact
title: "Contactez-nous"
permalink: /fr/contactez_nous # change corresponding i18n path variable if permalink changed here!
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
					<ul class="breadcrumb">
						<li><a href="#" title="">Home</a></li>
						<li><span>Contacts</span></li>
					</ul><!--breadcrumb end-->
					<h2>Contacts</h2>
					<span>How to contact us</span>
				</div>
				<div class="pger-imgs style2">
					<div class="abt-imgz">
						<img src="https://via.placeholder.com/763x509" alt="">
					</div>
				</div><!--pger-imgs end-->
				<div class="clearfix"></div>
			</div>
		</section><!--pager-section end-->

		<section class="page-content">
			<div class="container">
				<div class="contact-page">
					<div class="contact-head">
						<p>Any questions or suggestions? <br /> Write us a message and we will contact you!</p>
					</div><!--contact-head end-->
					<div class="contact-main">
						<div class="row">
							<div class="col-lg-4">
								<div class="contact_info">
									<h3 class="sub-title white">Contacts</h3>
									<ul class="cl-list">
										<li>
											<span class="ci-icon">
												<img src="{{ site.baseurl }}/assets/images/ci1.png" alt="">
											</span>
											<p>1556 Broadway, suite 416 New York, NY 10120 USA</p>
										</li>
										<li>
											<span class="ci-icon">
												<img src="{{ site.baseurl }}/assets/images/ci2.png" alt="">
											</span>
											<p><span>Mon-Sat:</span> 9 am til 6 pm <span>Sunday:</span> Closed</p>
										</li>
										<li>
											<span class="ci-icon">
												<img src="{{ site.baseurl }}/assets/images/ci3.png" alt="">
											</span>
											<p>in.design@gmail.com</p>
										</li>
										<li>
											<span class="ci-icon">
												<img src="{{ site.baseurl }}/assets/images/ci4.png" alt="">
											</span>
											<p>+44 20 7722 0088</p>
										</li>
									</ul>
								</div>
							</div>
							<div class="col-lg-8">
								<div class="contact-main-form">
									<form method="post" action="#" id="contact-form">
										<div class="response"></div>
										<div class="row">
											<div class="col-sm-6">
												<div class="form-group">
													<label>Name</label>
													<input type="text" name="name" class="form-control name" placeholder="Daniel">
												</div><!--form-group end-->
											</div>
											<div class="col-sm-6">
												<div class="form-group">
													<label>What city are you from?</label>
													<select class="form-control">
														<option>Los Angeles</option>
														<option>Los Angeles</option>
														<option>Los Angeles</option>
														<option>Los Angeles</option>
													</select>
												</div><!--form-group end-->
											</div>
											<div class="col-sm-6">
												<div class="form-group">
													<label>E-mail</label>
													<input type="email" name="email" class="form-control email" placeholder="Example@gmail.com">
												</div><!--form-group end-->
											</div>
											<div class="col-sm-6">
												<div class="form-group">
													<label>Phone Number</label>
													<input type="text" name="name" class="form-control" placeholder="44 20 7700 0055">
												</div><!--form-group end-->
											</div>
											<div class="col-sm-10">
												<div class="form-group">
													<label>Message</label>
													<textarea class="form-control" placeholder="Hello! I have this question..."></textarea>
												</div><!--form-group end-->
											</div>
											<div class="col-sm-2">
												<div class="form-submit">
													<button type="button" id="submit"><img src="{{ site.baseurl }}/assets/images/submit.png" alt=""></button>
												</div><!--form-submit end-->
											</div>
										</div>
									</form>
								</div><!--contact-main-form end-->
							</div>
						</div>
					</div><!--contact-main end-->
					<div class="contact-social">
						<span>Subscribe to our social networks :</span>
						<ul class="social-links without-bg">
							<li><a href="#" title=""><i class="fab fa-behance"></i></a></li>
							<li><a href="#" title=""><i class="fab fa-instagram"></i></a></li>
							<li><a href="#" title=""><i class="fab fa-facebook-f"></i></a></li>
						</ul>
					</div><!--contact-social end-->
				</div><!--contact-page end-->
			</div>
		</section><!--page-content end-->

		<footer>
			{% include footer.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->



{% include scripts.markdown %}


</body>

</html>