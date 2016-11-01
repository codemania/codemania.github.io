---
layout: 2016site
title: Codemania of years gone by
years: ['2012', '2013', '2014', '2015', '2016']
---

<div class="parallax__layer parallax__layer--base">
<div class="centerStage">

	{% for year in page.years %}
	<div class="col-xs-12">
		<a href="/{{year}}/index.html">
			<h1 class="center lunchBox huge">{{year}}</h1>
		</a>
	</div>
	{% endfor %}

</div>
</div>