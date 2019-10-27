		<template lang="pug">
div
	//- i-header._text-center(fullscreen)

	//- 	i.fas.fa-chess-queen.fa-5x
	//- 	h1 Heroic Sentiment
	//- 	h3._text-left(style="width: 360px") Cθ οδιο μθcιθσ ηισ, εθμ αλιι γραεcε δελιcατισσιμι ιδ, θτ παθλο qθαλισqθε εοσ. Ειρμοδ οπτιον qθαεστιο ιν μει.
	//- 	i-button(variant='primary') Act on the Fact

	i-header#header._text-center._text-white(:cover='true')
		h1 Babel Babel Babble On
		h2 Lorem ipsum dolor sit amet
		i-button(variant='primary') Impress Me

	i-container

		i-row
			i-column(md="6")
				h1
					i.fas.fa-sun.fa-3x
				h1  Good Morning, Midnight
				p(style="text-align: left;") Cθ οδιο μθcιθσ ηισ, εθμ αλιι γραεcε δελιcατισσιμι ιδ, θτ παθλο qθαλισqθε εοσ. Ειρμοδ οπτιον qθαεστιο ιν μει. Cετεροσ αccθσαμθσ vιμ τε. Ενιμ cονσθλ ατομορθμ πρι ιν, νο ιγνοτα σθσcιπιαντθρ εοσ. Νονθμεσ προβατθσ vολθπτατιβθσ εαμ θτ, ωισι φιερεντ δελεcτθσ αδ vελ. Πριμισ εριπθιτ vθλπθτατε νο μει, τε qθι λεγιμθσ σθσcιπιτ περιcθλισ. Ερατ προπριαε ετ δθο, ιριθρε cορπορα μενανδρι εα εθμ.
				i-button(variant="dark") Offprint
				i-button(variant="primary") Imprint
				i-button(variant="light") Footprint

			i-column(md="6")
				h1
					i.fas.fa-sun.fa-3x
				h1  Good Morning, Midnight
				p(style="text-align: left;") Cθ οδιο μθcιθσ ηισ, εθμ αλιι γραεcε δελιcατισσιμι ιδ, θτ παθλο qθαλισqθε εοσ. Ειρμοδ οπτιον qθαεστιο ιν μει. Cετεροσ αccθσαμθσ vιμ τε. Ενιμ cονσθλ ατομορθμ πρι ιν, νο ιγνοτα σθσcιπιαντθρ εοσ. Νονθμεσ προβατθσ vολθπτατιβθσ εαμ θτ, ωισι φιερεντ δελεcτθσ αδ vελ. Πριμισ εριπθιτ vθλπθτατε νο μει, τε qθι λεγιμθσ σθσcιπιτ περιcθλισ. Ερατ προπριαε ετ δθο, ιριθρε cορπορα μενανδρι εα εθμ.
				i-button(variant="dark") Offprint
				i-button(variant="primary") Imprint
				i-button(variant="light") Footprint

		i-row
			i-column(md="6")
				h1
					i.fas.fa-sun.fa-3x
				h1  Good Morning, Midnight
				p(style="text-align: left;") Cθ οδιο μθcιθσ ηισ, εθμ αλιι γραεcε δελιcατισσιμι ιδ, θτ παθλο qθαλισqθε εοσ. Ειρμοδ οπτιον qθαεστιο ιν μει. Cετεροσ αccθσαμθσ vιμ τε. Ενιμ cονσθλ ατομορθμ πρι ιν, νο ιγνοτα σθσcιπιαντθρ εοσ. Νονθμεσ προβατθσ vολθπτατιβθσ εαμ θτ, ωισι φιερεντ δελεcτθσ αδ vελ. Πριμισ εριπθιτ vθλπθτατε νο μει, τε qθι λεγιμθσ σθσcιπιτ περιcθλισ. Ερατ προπριαε ετ δθο, ιριθρε cορπορα μενανδρι εα εθμ.
				i-button(variant="dark") Offprint
				i-button(variant="primary") Imprint
				i-button(variant="light") Footprint

			i-column(md="6")
				h1
					i.fas.fa-sun.fa-3x
				h1  Good Morning, Midnight
				p(style="text-align: left;") Cθ οδιο μθcιθσ ηισ, εθμ αλιι γραεcε δελιcατισσιμι ιδ, θτ παθλο qθαλισqθε εοσ. Ειρμοδ οπτιον qθαεστιο ιν μει. Cετεροσ αccθσαμθσ vιμ τε. Ενιμ cονσθλ ατομορθμ πρι ιν, νο ιγνοτα σθσcιπιαντθρ εοσ. Νονθμεσ προβατθσ vολθπτατιβθσ εαμ θτ, ωισι φιερεντ δελεcτθσ αδ vελ. Πριμισ εριπθιτ vθλπθτατε νο μει, τε qθι λεγιμθσ σθσcιπιτ περιcθλισ. Ερατ προπριαε ετ δθο, ιριθρε cορπορα μενανδρι εα εθμ.
				i-button(variant="dark") Offprint
				i-button(variant="primary") Imprint
				i-button(variant="light") Footprint
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Component({
	components: {
		HelloWorld,
	},
})
export default class Home extends Vue {}
</script>

<style>
#header {
		background-image: url(../assets/breugeltorre.jpg);
		height: 100vh;
}
</style>