+++
title = "Contacte"
weight = 60
draft = false
+++

<!-- <button id="button_tarraco" class="tablink active" onclick="openPage('tarraco')">Tarragona</button> -->
<!-- <button id="button_gembukai" class="tablink" onclick="openPage('gembukai')" id="defaultOpen">Bonavista</button> -->
<h3 id="classes-adults">Tarragona</h3>
<!-- <div id="gembukai" hidden>
	<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3005.796468965397!2d1.1900537508851787!3d41.117135920566426!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12a1578b3a8c4de7%3A0xdab6129bb668b585!2sGembu-Kai+Club+Esportiu!5e0!3m2!1ses!2ses!4v1522689375829" width="100%" height="250" frameborder="0" style="border:0" allowfullscreen></iframe>
  També impartim classes al dojo <strong>Gembu-Kai Club Esportiu</strong>, a Bonavista.
</div> -->
<div id="tarraco">
  <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3005.6793942600516!2d1.2590833!3d41.1196925!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12a3fd1f443ca293%3A0xe37b40081f3e8982!2sAikido%20Tarragona!5e0!3m2!1sca!2ses!4v1568911339498!5m2!1sca!2ses" width="100%" height="250" frameborder="0" style="border:0; margin-bottom:1rem;" allowfullscreen=""></iframe>
	El nostre dojo està situat al <strong>Club Natació Tarraco</strong>, al centre de Tarragona.
</div>
<hr>
<form   
  action="https://formspree.io/f/myyqbdgv"
  method="POST"
>
<div style="margin-bottom:1rem;">
Si tens cap dubte o pregunta no dubtis en posar-te en contacte amb nosaltres:
  Truca al <a href="tel:+34977232084" target="_blank">977 232 084</a> o envieu un correu a <a href="mailto:info@cntarraco.cat" name="email" title="email">info@cntarraco.cat</a>.
</div>
<h3 id="classes-adults">FORMULARI WEB</h3>
	<input type="hidden" name="_cc" id="_cc" />
	<div class="field half first">
		<input type="text" name="name" id="name" placeholder="Nom"/>
	</div>
	<div class="field half">
		<input type="email" id="email" name="email" placeholder="Correu">
	</div>
	<div class="field">
		<textarea name="message" id="message" rows="4" placeholder="Missatge"></textarea>
	</div>
	<button type="submit">Enviar</button>
</form>
<span id="contactformsent">
  <p>Gràcies pel seu missatge. Ens posarem en contacte amb vostè directament al més aviat possible.</p>
</span>

<script>
function openPage(page) {
	switch(page){
		case 'tarraco':
			$('#gembukai').hide();
			$('#tarraco').show();
			$('#button_gembukai').removeClass('active');
			$('#button_tarraco').addClass('active');
			break;
		case 'gembukai':
			$('#tarraco').hide();
			$('#gembukai').show();
			$('#button_tarraco').removeClass('active');
			$('#button_gembukai').addClass('active');
			break;
	}
}
</script>
