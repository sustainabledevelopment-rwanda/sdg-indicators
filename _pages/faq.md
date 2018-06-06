---
title: Frequently Asked Questions (FAQ)
permalink: /faq/
layout: page
---

## How do I suggest new or different data sources?
If you have feedback on the data sources we have used or have suggestions for new data sources then please email us at <a href="mailto:{{site.email_contacts.questions}}">{{site.email_contacts.questions}}</a>.

## What does the reporting status mean?
We have used three different types of reporting status for an indicator, which are also colour coded:

* Reported online (green) – as a minimum the headline national data for this indicator is available on this website but the data might not be fully disaggregated yet. We are continuing to source additional disaggregations.
* Statistics in progress (amber) – we have found a suitable source of data for this indicator or relevant proxy at national level. We are currently quality assuring the data and preparing it for publication.
* Exploring data sources (red) – we are still looking for a suitable data source for this indicator.

Where there is additional information about the status of indicator data collection and reporting, this will be displayed at the top of the indicator page.

<!-- DO NOT REMOVE ANYTHING BELOW THIS LINE -->
<script type='text/javascript'>
document.addEventListener("DOMContentLoaded", function () {
  $('#main-content h2').addClass('roleHeader');
 	$('#main-content h2').attr({
 	  'tabindex': 0,
 	  'role': 'button'
 	});
 	$('.roleHeader').click(function () {
 	  $(this).nextUntil('h2').stop(true, true).slideToggle();
	 }).nextUntil('h2').hide();
	 $('.roleHeader').keypress(function (e) {
 	  if (e.which == 13) { // Enter key pressed
			   $(this).trigger('click');
		  }
	 });
})
 </script>
