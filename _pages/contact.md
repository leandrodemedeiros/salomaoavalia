---
title: Fale comigo
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">
<p class="mb-4">Por favor, envie uma mensagem para <strong>{{site.name}}</strong>. Responderei assim que possível!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Nome*">
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail*">
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Mensagem*"></textarea>
<input class="btn btn-success" type="submit" value="Enviar">
</form>