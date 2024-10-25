# Justify your Tech-stack

## User Experience

### Publiek
Het publiek voor de website is vooral hogeschool docenten in het HBO en HBO studenten. Er kan verwacht worden dat zij een relatief goede laptop hebben en dat zij de website dan ook op een laptop bezoeken. Ook zullen zij waarschijnlijk semi-regelmatig de website op een mobiele telefoon bezoeken, maar dit zal een stuk minder vaak gebeuren. Er kan gesteld worden dat de gebruikers van de website relatief goed tech-geletterd zijn, en weten hoe een website werkt.

### User Experience in Astro
Astro is gebaseerd op Vite voor bundling. Vite is alleen gericht op relatief nieuwe browsers die moderne Javascript functies ondersteunen. De oudst ondersteunde browsers in Vite (en dus Astro) zijn als volgt:
- Chrome >=87
- Firefox >=78
- Safari >=14
- Edge >=88

Ook zijn SEO en snelle laadtijden een prioriteit in Astro. Het is zo gebouwd om zo min mogelijk, en zo simpel mogelijke Javascript op de pagina te hebben. Als je een statische website bouwt, wordt er dan ook geen enkele Javascript naar de client gestuurd.

Ook is alles standaard op de server gerenderd. Dit betekent dat een gebruiker zonder Javascript de website ook kan gebruiken.

## Developer Experience

### Developer Experience in Astro
Astro is fundamenteel gebouwd met een focus op de Developer Experience. De docs zijn ontzettend uitgebreid en goed onderhouden. Ik had een probleem met het gebruiken van React in Astro en kon het zelf niet uitvinden. Toen ik het googlede kreeg ik een StackOverflow antwoord wat ook nogal complex was, en wat mij niet veel verder hielp. Toen ik het echter eenmaal in de docs zocht was het allemaal heel duidelijk omschreven, en kwam ik er al snel uit. De docs zijn bij Astro een van de sterkste punten.

Ook is het framework agnostisch, wat inhoudt dat je veel verschillende UI frameworks kan gebruiken en zelfs kan combineren in een Astro project. Dit klinkt heel fijn, en het is ook heel flexibel, maar ik vind het persoonlijk heel verwarrend. Dit omdat je uiteindelijk verschillende syntaxen door elkaar moet gebruiken. Zo is in ieder project de pagina zelf bijvoorbeeld een .astro bestand, maar had ik in mijn project voor de components React gebruikt. Dit betekende dat ik React syntax moest schrijven in mijn components, maar dat als ik iets op de pagina zelf wou veranderen, ik ineens weer in de syntax van Astro moest schrijven. Dit vond ik zelf heel vervelend.

Ten slotte is Astro ook begonnen als static site generator, en dit is terug te vinden in hoe je het gebruikt. Zo wordt er namelijk van Astro verwacht dat alles eigenlijk statisch is, en moet je het bij ieder component specifiek aangeven als je het dynamisch wilt maken. Dit betekent dat het framework beter geschikt is voor websites die grotendeels statisch zijn en een klein deel reactivity nodig hebben, niet voor erg dynamische websites waar veel reactive components komen kijken.

## Content Management Experience

### Content Management Experience in Hygraph
Content management in Hygraph heeft naar mijn mening best een hoge learning curve. Het heeft veel verschillende bouwblokken die je eigenlijk samenvoegt tot een data model. Dit betekent echter dat je wel de juiste blokken moet gebruiken voor de juiste data, en daarom was het voor mij vaak wel zoeken of ik de juiste blokken gebruikte. Dit gaat naar mijn mening in een CMS als Directus een stuk makkelijker, omdat ze daar niet zo veel verschillende bouwblokken hebben, maar ze iets algemener en flexibeler zijn.

Ook heeft het werken met Hygraph als developer een hoge learning curve. Het gebruikt namelijk GraphQL voor de queries. Dit zorgt ervoor dat je meer fine-grained controle hebt over de data die je van je CMS vraagt, maar het betekent ook dat je veel meer tijd kwijt bent aan het schrijven van queries en dat deze vaak erg groot en lastiger te begrijpen zijn voor iemand die minder ervaring heeft met GraphQL.

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

