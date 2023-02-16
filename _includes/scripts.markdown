<script type="text/javascript" src="{{ site.baseurl }}/assets/js/jquery.min.js"></script>
<script type="text/javascript" src="{{ site.baseurl }}/assets/js/popper.js"></script>
<script type="text/javascript" src="{{ site.baseurl }}/assets/js/bootstrap.min.js"></script>
<script type="text/javascript" src="{{ site.baseurl }}/assets/js/plugin/slick.min.js"></script>
<script type="text/javascript" src="{{ site.baseurl }}/assets/js/plugin/html5lightbox.js"></script>
<script type="text/javascript" src="{{ site.baseurl }}/assets/js/plugin/counter.js"></script>
<script type="text/javascript" src="{{ site.baseurl }}/assets/js/placeholdem.min.js"></script>
<script type="text/javascript" src="{{ site.baseurl }}/assets/js/script.js"></script>
<script type="text/javascript" src="{{ site.baseurl }}/assets/js/date.js"></script>
<script type="text/javascript" src="{{ site.baseurl }}/assets/js/date-fr-FR.js"></script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.29.4/moment-with-locales.min.js"></script>
<!--script
    type="text/javascript"
    async defer
    src="//assets.pinterest.com/js/pinit.js"
></script-->

<!-- Cookie Consent by TermsFeed https://www.TermsFeed.com -->
<script type="text/javascript" src="https://www.termsfeed.com/public/cookie-consent/4.0.0/cookie-consent.js" charset="UTF-8"></script>
<script type="text/javascript" charset="UTF-8">
document.addEventListener('DOMContentLoaded', function () {
cookieconsent.run({"notice_banner_type":"simple","consent_type":"express","palette":"dark","language":"fr","page_load_consent_levels":["strictly-necessary"],"notice_banner_reject_button_hide":false,"preferences_center_close_button_hide":false,"page_refresh_confirmation_buttons":false,"website_name":"cs-interieurs","website_privacy_policy_url":"https://cs-interieurs.com/fr/privacy-policy"});
});

moment.locale('fr');
if(document.getElementById('current-date')){
    document.getElementById('current-date').innerHTML = "Mis à jour le " + Date.today().toString("dd MMMM yyyy");
}
if(document.getElementById('page-date')){
    document.getElementById('page-date').innerHTML = "Mis à jour le " + moment(document.getElementById('page-date').innerHTML, "yyyy-MM-DD").format("LL");
}
const posts = document.querySelectorAll("#post-date");
for (var i = 0; i < posts.length; i++) {
    posts[i].innerHTML = moment(posts[i].innerHTML, "yyyy-MM-DD").format("LL");
}
</script>

<noscript>Free cookie consent management tool by <a href="https://www.termsfeed.com/" rel="nofollow noopener">TermsFeed Policy Generator</a></noscript>
<!-- End Cookie Consent by TermsFeed https://www.TermsFeed.com -->

<!-- Go to www.addthis.com/dashboard to customize your tools --> 
<script type="text/javascript" src="//s7.addthis.com/js/300/addthis_widget.js#pubid=ra-63ecf20d4564a186"></script> 




<!-- Below is the link that users can use to open Preferences Center to change their preferences. Do not modify the ID parameter. Place it where appropriate, style it as needed. -->

<a href="#" id="open_preferences_center">Update cookies preferences</a>