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

<form id="contactform" method="POST">
    <input type="text" name="name" placeholder="Your name">
    <input type="email" name="_replyto" placeholder="Your email">
    <input type="hidden" name="_subject" value="Website contact" />
    <textarea name="message" placeholder="Your message" style="height:75px"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <input type="submit" value="Send">
</form>

<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'tobias.johannink' + '@' + 'gmx' + '.' + 'de');
</script>
