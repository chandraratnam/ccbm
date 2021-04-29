---
layout: page
title: Booking an Appointment
permalink: /booking/
---


<h1> Booking an Appointment with Dave </h1>

Dave practices at a clinic in East Gosford.<br>
You can book and appointment with Dave here!
<p>
Dave practices at a clinic called "Central Coast body Mechanics" at 37 Althorp Street East Gosford.
<p>
Should this be a link of button?
<br>
<br>
Direct Link <br>
<a href="https://central-coast-body-mechanics.au1.cliniko.com/bookings?business_id=59092&practitioner_id=158654">Here</a>
<br>

Iframe <br>
<iframe id='cliniko-25928570' src='https://central-coast-body-mechanics.au1.cliniko.com/bookings?business_id=59092&practitioner_id=158654&embedded=true' frameborder='0' scrolling='auto' width='100%' height='1000' style='pointer-events: auto;'></iframe>
<script type='text/javascript'>
  window.addEventListener('message', function handleIFrameMessage (e) {
    var clinikoBookings = document.getElementById('cliniko-25928570');
    if (typeof e.data !== 'string') return;
    if (e.data.search('cliniko-bookings-resize') > -1) {
      var height = Number(e.data.split(':')[1]);
      clinikoBookings.style.height = height + 'px';
    }
    e.data.search('cliniko-bookings-page') > -1 && clinikoBookings.scrollIntoView();
  });
</script>














A medium inspired Jekyll blog theme. The basic idea came from the Ghost theme
[Readium 2.0](http://www.svenread.com/readium-ghost-theme/). I use mediator on my own blog [The Base](blog.base68.com).

You can **download** the theme here:
[https://github.com/dirkfabisch/mediator](https://github.com/dirkfabisch/mediator)

You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/)

You can find the source code for the Jekyll new theme at: [github.com/jglovier/jekyll-new](https://github.com/jglovier/jekyll-new)

You can find the source code for Jekyll at [github.com/jekyll/jekyll](https://github.com/jekyll/jekyll)
