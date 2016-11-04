---
layout: home
title: Inicio
landing-title: Proyecto Renacer
description: Somos un centro dedicado al tratamiento de personas que sufren adicciones,<br> el cual promueve cambios significativos en sus vidas.
image: assets/images/23.jpg
author: 
nav-menu: 
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<header class="major">
			<h1>{{ page.landing-title }}</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ page.description }}</p>
			<ul class="actions">
				<li><a class="button next scrolly" onclick="revealVideo('video','youtube')">Quiero saber más</a></li>
			</ul>
            <div id="video" class="lightbox" onclick="hideVideo('video','youtube')">
                <div class="lightbox-container">
                        <div class="lightbox-content">
                            <button onclick="hideVideo('video','youtube')" class="lightbox-close">Close | ✕</button>
                            <div class="video-container">
                                <iframe id="youtube" width="960" height="540" src="https://www.youtube.com/embed/7XPkPl6cvk0?showinfo=0" frameborder="0" allowfullscreen></iframe>
                            </div>                            
                        </div>
                </div>
            </div>
			
		</div>
	</div>


</section>

<!-- Main -->
<div id="main">


<!-- One -->
{% include tiles.html %}


</div>