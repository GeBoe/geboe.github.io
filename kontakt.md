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

submit {
 color: #999999;
 font-size: 0;
 width: 200px;
 height: 60px;
 border: none;
 margin: 0;
 padding: 0;
 background: #0c0 url(image) 0 0 no-repeat; 
}
</style>

<h1>Kontakt</h1>

<form id="contactform" method="POST" style="width:300px">
    <input type="text" name="name" placeholder="Your name">
    <input type="email" name="_replyto" placeholder="Your email">
    <input type="hidden" name="_subject" value="Website contact" />
    <textarea name="message" placeholder="Your message"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <input type="submit" value="Send">
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'tobias.johannink' + '@' + 'gmx' + '.' + 'de');
</script>
