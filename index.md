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
			<!-- <h1>{{ page.landing-title }}</h1> -->
			<img class="image-responsive" src="{{ site.baseurl }}/assets/images/renacer_DEF.png" >
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
                                <object width="640" height="360" id="youtube">
                                    <param name="movie" value="//www.youtube.com/embed/yt-video-id?html5=1&amp;rel=0&amp;hl=en_US&amp;version=3"/
                                    <param name="allowFullScreen" value="true"/>
                                    <param name="allowscriptaccess" value="always"/>
                                    <embed width="640" height="360" src="//www.youtube.com/embed/7XPkPl6cvk0?html5=1&amp;rel=0&amp;hl=en_US&amp;version=3" class="youtube-player" type="text/html" allowscriptaccess="always" allowfullscreen="true"/>
                                </object>
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