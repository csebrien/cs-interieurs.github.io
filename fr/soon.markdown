---
layout: null
code: soon
title: "soon"
permalink: /fr/soon
redirect_from:
  - /fr/
---
<html lang="en">
{% include head.markdown %}


<body>

	{% include page-loading.markdown %}

	<div class="wrapper">
			
		<header class="header-bg">
			{% include header.markdown %}
		</header><!--header end-->

		{% include responsive-menu.markdown %}

		<section class="soon-page">
			<div class="container">
				<div class="error-content">
					<div class="col-xl-6">
						<div class="error-text">
							<h2>{{ site.data.i18n.soon[page.lang].title }}</h2>
							<p>{{ site.data.i18n.soon[page.lang].subtitle }}</p>
							<a href="mailto:{{ site.data.i18n.footer[page.lang].email }}" class="lnk-default" title="">{{ site.data.i18n.footer[page.lang].contactus }}</a>
						</div><!--error-text end-->
					</div>
				</div><!--error-content end-->
			</div>
		</section><!--error-page end-->

		<footer>
			{% include footer-soon.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->

{% include scripts.markdown %}


</body>

</html>