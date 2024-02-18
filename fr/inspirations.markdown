---
layout: null
code: inspirations
title: "Nos inspirations"
permalink: /fr/nos_inspirations # change corresponding i18n path variable if permalink changed here!
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
					<h2>Inspirations Pinterest</h2>
					<span>Découvrez nos univers d'inspiration!</span>
				</div>
				<div class="pger-imgs style2">
					<div class="abt-imgz">
						<img src="{{ site.baseurl }}/assets/images/inspirations.jpg" alt="">
					</div>
				</div><!--pger-imgs end-->
				<div class="clearfix"></div>
			</div>
		</section><!--pager-section end-->

		<section class="block">
			<div class="container">
				<div class="grid">
					<div class="grid-sizer"></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/1022515d1cc7cea204314da61bd6665a.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/180cf429b5aa6fa20cc68d2266dd26da.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/2acd7eab6a6ad60b16aee5ccdb4a33f0.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/44384c383f157596e3fc1251123beb72.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/55489aa00aedf4f134e3cbfcc066e66b.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/5bac53fa16c2ce65d50bed47b1846907.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/640d4daf60b32be039f574669d0b09c3.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/687dca786f329cb9e8a2790c419272dd.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/71cc596346c08cf666ddabb4ded69429.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/879e0b9fc9ccaf6d011a765adf9893dd.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/914e59570b395ad11e580ac3e8fbb84c.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/9465a9390c5c8805942249f70702f937.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/d24835d0ab90562cd2b410fc411f21e9.jpg" alt=""/></a></div>
					<div ><a href="https://www.pinterest.fr/csinterieurs/" target="_blank"><img class="grid-item" src="{{ site.baseurl }}/assets/images/pinterest/dbb4f10b411b6ba70ab33cadc58a78ef.jpg" alt=""/></a></div>
				</div>
			</div>
		</section>

		<footer>
			{% include footer.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->



{% include scripts.markdown %}
<script src="https://unpkg.com/masonry-layout@4/dist/masonry.pkgd.min.js"></script>
<script src="https://unpkg.com/imagesloaded@5/imagesloaded.pkgd.min.js"></script>
<script>
var $grid =	$('.grid').masonry({
  // set itemSelector so .grid-sizer is not used in layout
  itemSelector: '.grid-item',
  // use element for option
  columnWidth: '.grid-sizer',
  percentPosition: true
})
$grid.imagesLoaded().progress( function() {
  $grid.masonry('layout');
});
</script>

</body>

</html>