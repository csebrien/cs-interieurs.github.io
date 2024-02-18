---
layout: null
code: contact
title: "Contactez-nous"
permalink: /fr/contactez_nous # change corresponding i18n path variable if permalink changed here!
last_modified_at : "2024-02-18"
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
					<h2>{{ site.data.i18n.contact[page.lang].subtitle }}</h2>
					<span>{{ site.data.i18n.contact[page.lang].subtitle2 }}</span>
				</div>
				<div class="pger-imgs style2">
					<div class="abt-imgz">
						<img src="{{ site.baseurl }}/assets/images/images_contact.jpg" alt="">
					</div>
				</div><!--pger-imgs end-->
				<div class="clearfix"></div>
			</div>
		</section><!--pager-section end-->

		<section class="page-content">
			<div class="container">
				<div class="contact-page">
					<div class="contact-head">
						<p>{{ site.data.i18n.contact[page.lang].question }}</p>
					</div><!--contact-head end-->
					<div class="contact-main">
						<div class="row">
							<div class="col-lg-4">
								<div class="contact_info">
									<h3 class="sub-title white">{{ site.data.i18n.contact[page.lang].subtitle3 }}</h3>
									<ul class="cl-list">
										<li>
											<span class="ci-icon">
												<img src="{{ site.baseurl }}/assets/images/ci1.png" alt="">
											</span>
											<p>{{ site.data.i18n.contact[page.lang].address }}</p>
										</li>
										<li>
											<span class="ci-icon">
												<img src="{{ site.baseurl }}/assets/images/ci2.png" alt="">
											</span>
											<p>{{ site.data.i18n.contact[page.lang].work_time }}</p>
										</li>
										<li>
											<span class="ci-icon">
												<img src="{{ site.baseurl }}/assets/images/ci3.png" alt="">
											</span>
											<p>{{ site.data.i18n.contact[page.lang].email }}</p>
										</li>
										<li>
											<span class="ci-icon">
												<img src="{{ site.baseurl }}/assets/images/ci4.png" alt="">
											</span>
											<p>{{ site.data.i18n.contact[page.lang].phone }}</p>
										</li>
									</ul>
								</div>
							</div>
							<div class="col-lg-8">
								<div class="contact-main-form">
									<form method="post" action="https://formspree.io/f/myyvrzap" id="contact-form">
										<input type="text" name="_gotcha" style="display:none" />
										<input name="subject" value="{{ site.data.i18n.contact[page.lang].email_subject }}" style="display:none"/>
										<input type="hidden" id="g-recaptcha-response" name="g-recaptcha-response">
										<div class="response"></div>
										<div class="row">
											<div class="col-sm-6">
												<div class="form-group">
													<label>{{ site.data.i18n.contact[page.lang].name }}</label>
													<input type="text" name="name" class="form-control name" placeholder="Daniel">
												</div><!--form-group end-->
											</div>
											<div class="col-sm-6">
												<div class="form-group">
													<label>{{ site.data.i18n.contact[page.lang].from_city }}</label>
													<input type="text" name="city" class="form-control name" placeholder="Paris">
												</div><!--form-group end-->
											</div>
											<div class="col-sm-6">
												<div class="form-group">
													<label>{{ site.data.i18n.contact[page.lang].dest_email }}</label>
													<input type="email" name="email" class="form-control email" placeholder="Example@gmail.com">
												</div><!--form-group end-->
											</div>
											<div class="col-sm-6">
												<div class="form-group">
													<label>{{ site.data.i18n.contact[page.lang].dest_phone }}</label>
													<input type="text" name="phone" class="form-control" placeholder="44 20 7700 0055">
												</div><!--form-group end-->
											</div>
											<div class="col-sm-10">
												<div class="form-group">
													<label>{{ site.data.i18n.contact[page.lang].message }}</label>
													<textarea name="message" class="form-control" placeholder="Hello! I have this question..."></textarea>
												</div><!--form-group end-->
											</div>
											<div class="col-sm-2">
												<div class="form-submit">
													<button type="submit" id="submit"><img src="{{ site.baseurl }}/assets/images/submit.png" alt=""></button>
												</div><!--form-submit end-->
											</div>
										</div>
									</form>
								</div><!--contact-main-form end-->
							</div>
						</div>
					</div><!--contact-main end-->
					<!--div class="contact-social">
						<span>{{ site.data.i18n.contact[page.lang].subscribe }}</span>
						<ul class="social-links without-bg">
							<li><a href="#" title=""><i class="fab fa-pinterest-p"></i></a></li>
							<li><a href="#" title=""><i class="fab fa-instagram"></i></a></li>
							<li><a href="#" title=""><i class="fab fa-facebook-f"></i></a></li>
							<li><a href="#" title=""><i class="fab fa-linkedin"></i></a></li>
							<li><a href="#" title=""><i class="fab fa-twitter"></i></a></li>
						</ul>
					</div--><!--contact-social end-->
				</div><!--contact-page end-->
			</div>
		</section><!--page-content end-->

		<footer>
			{% include footer.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->



{% include scripts.markdown %}

<script src="https://www.google.com/recaptcha/api.js?render=6LdC5FcjAAAAABzm0IjJdAbPZfKkwHi0e6FzgtDT"></script>
<script>
	grecaptcha.ready(function () {
		grecaptcha.execute('6LdC5FcjAAAAABzm0IjJdAbPZfKkwHi0e6FzgtDT', {action: 'submit'}).then(function (token) {
			document.getElementById('g-recaptcha-response').value = token;
		});
	});
</script>

</body>

</html>