---
title: "Kontakt"
permalink: /kontakt/
layout: splash
excerpt: "Kontakt"
sitemap: false
---
<style>
 td {
    vertical-align: middle;
}
</style>

<div style="text-align: center">
<form id="contactform" method="POST" style="width:500px">
    <input type="text" name="name" placeholder="Your name">
    <input type="email" name="_replyto" placeholder="Your email">
    <input type="hidden" name="_subject" value="Website contact" />
    <textarea name="message" placeholder="Your message"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <input type="submit" value="Send">
</form>
</div>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'tobias.johannink' + '@' + 'gmx' + '.' + 'de');
</script>
