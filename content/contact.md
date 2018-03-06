+++
title = "Contacte"
weight = 60
draft = false
+++

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3005.6792101467636!2d1.2590779505723646!3d41.11969652040898!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12a3fcce6c64a441%3A0x60a18a1099324888!2sClub+de+Nataci%C3%B3+Tarraco!5e0!3m2!1sen!2ses!4v1519899702247" width="100%" height="250" frameborder="0" style="border:0" allowfullscreen></iframe>
El nostre dojo està situat al <strong><a href="http://www.cntarraco.cat/cat/seccions/406/aikido" target="_blank">Club de Natació Tarraco</a></strong>.
<hr>
Si tens cap dubte o pregunta no dubtis en posar-te en contacte amb nosaltres:

<form id="contactform" method="post" action="https://formspree.io/infoacadir@gmail.com">
	<div class="field half first">
		<input type="text" name="name" id="name" placeholder="Nom"/>
	</div>
	<div class="field half">
		<input type="email" id="email" name="email" placeholder="Correu">
	</div>
	<div class="field">
		<textarea name="message" id="message" rows="4" placeholder="Missatge"></textarea>
	</div>
	<ul class="actions">
		<li><input type="submit" value="Enviar missatge" class="special" /></li>
		<li><input type="reset" value="Netejar"></span></li>
	</ul>
	<input type="hidden" name="_next" value="?sent#formspree" />
	<input type="hidden" name="_subject" value="Subject for your mail like new message" />
	<input type="text" name="_gotcha" style="display:none" />
</form>
<span id="contactformsent">Gràcies pel seu missatge</span>

<script>
$(document).ready(function($) {
    $(function(){
        if (window.location.search == "?sent") {
        	$('#contactform').hide();
        	$('#contactformsent').show();
        } else {
        	$('#contactformsent').hide();
        }
    });
});
</script>
