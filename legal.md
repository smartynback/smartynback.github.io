---
layout: page
title: Privacy Policy
---
<div class="col-lg-12 text-center">
	<h2 class="section-heading text-uppercase">{%t privacy.title %}</h2>
</div>

{%t privacy.sub_title %}

{%t privacy.personal_information_title %}

{% if site.analytics.google %}

{%t privacy.personal_information_ga_text1 %}

{%t privacy.personal_information_ga_text2 %}

{%t privacy.personal_information_ga_text3 %}

{%t privacy.personal_information_ga_text4 %}

{%t privacy.personal_information_ga_text5 %}

{% else %}

{%t privacy.personal_information_no_ga_text1 %}

{% endif %}

{%t privacy.changes_title %}

{%t privacy.changes_text %}

{%t privacy.contact_us_title %}

{%t privacy.contact_us_text %}