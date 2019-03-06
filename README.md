#Kodeklubben Tromsø

Teknologistack:

* [Github Pages](https://pages.github.com) (webhost)
* [Jekyll](https://jekyllrb.com) (static site generator)
* [Bootstrap](http://getbootstrap.com/) (CSS rammeverk)
* [jQuery](https://jquery.com) (JS rammeverk)
* [Particles.js](https://github.com/VincentGarreau/particles.js/) (bakgrunn)

Installasjon med Docker (lettest - krever docker installert på maskinen):

1. [Spinn opp Starefossen/docker-github-pages](https://github.com/Starefossen/docker-github-pages)

Installasjon uten Docker:

1. [Installer Jekyll](https://jekyllrb.com/docs/installation/) 
2. `jekyll serve`

Utvikling:

1. Gjør endringer
2. Refresh [http://127.0.0.1:4000/](http://127.0.0.1:4000/)
3. Hvis ikke fornøyd, loop til pkt 4. :)
4. Commit og push. Jobbet du på en fork, lag pull-request.
5. Github vil bygge og publisere endringer i master-branchen automatisk.


Kjent issue:

* Hamburger-ikonet er sort på mørkegrå bakgrunn. :-/ Løsningen på dette er antakelig å kompilere vår egen bootstrap istedenfor å lenke til CDN.
