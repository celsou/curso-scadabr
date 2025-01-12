---
layout: page
title: Instalação ScadaBR no Windows (manualmente)
aula: true
tema: "Introdução"
post_index: 0.3
published: true
---

## Resumo da aula
<div class="message">	
	Nesta aula iremos ver como instalar o ScadaBR 1.2 no Windows de forma manual.<br><br>
	Tópicos abordados:
	<ul>
		<li>Instalação da máquina virtual Java (JVM)</li>
		<li>Instalação do Apache Tomcat</li>
		<li>Instalação do webapp do ScadaBR 1.2</li>
		<li>Configuração da acentuação em português</li>
	</ul>
</div>

<br>
## Conteúdo da aula (vídeo)

<div class="iframe-container ratio-16_9">
	<iframe src="https://youtube.com/embed/F7xWKLN_Jzg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<br>
## Material complementar
<ul>
	<li><a href="https://adoptium.net/temurin/releases/?os=windows&version=8" target="_blank">Link para download do OpenJDK</a></li>
	<li><a href="https://tomcat.apache.org/download-90.cgi" target="_blank">Link para download do Apache Tomcat 9</a></li>
	<li><a href="https://github.com/ScadaBR/ScadaBR/releases/tag/v1.2" target="_blank">Link para download do ScadaBR 1.2</a></li>
</ul>

Para configurar a acentuação de caracteres em português, você deve inserir as seguintes linhas na configuração da sua Máquina Virtual Java:

{% highlight plain %}
-Djavax.servlet.request.encoding=UTF-8
-Dfile.encoding=UTF-8
{% endhighlight %}