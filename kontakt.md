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
<h2>Kontaktformular</h2>
{: .text-center}

<form id="contactform" method="POST">
    <input type="text" name="name" placeholder="Dein Name">
    <input type="email" name="_replyto" placeholder="Deine E-Mail">
    <input type="hidden" name="_subject" value="Website contact" />
    <textarea name="message" placeholder="Deine Nachricht" style="height:150px"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <input type="submit" value="Send">
</form>

<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'tobias.johannink' + '@' + 'gmx' + '.' + 'de');
</script>
