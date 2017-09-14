---
title: Projects
body_classes: home 
never_cache_twig: true
process:
    twig: true
---

<section class="hero">
	<div class="wrapper">
		<div class="hero__inner">
			<h1 class="hero__h1-alt animate-up-step1-start">Product designer in Glasgow</h1>
			<p class="hero__p-alt animate-up-step1-start">Product designer, illustrator and front end developer <a target="_blank" href="http://www.fanduel.com">Fanduel</a>. I create engaging, intuitive, results driven user interfaces with a focus. <!--on outstanding visual execution.--></p>
			<div class="hero__cta-wrap animate-up-step2-start">
				<a href="" class="hero__cta cta cta--margin">View projects</a>
			</div>
		</div>
	</div>
</section>
<div class="folio_waypoint"></div>
<section class="folio animate-up-lg-step1-start">
<div class="footerappear_waypoint"></div>
    <div class="wrapper">
    	<div class="grid-container-flex">
			{% include 'partials/projectgrid.html.twig'
			        with {
			            'foliotitle': 'FanDuel Championship Leagues',
			            'foliocolor': 'fanduel',
			            'foliolink': 'fanduel-championship-leagues',
			            'folioimage': 'test.png',
			            'folioskills': 'Mobile App Design, UX',
			            'foliodescription': 'Championships is a groundbreaking fantasy sports platform.',
			            'foliowidth': 'grid-6 grid-6--left'
			        }
			%}
			{% include 'partials/projectgrid.html.twig'
			        with {
			            'foliotitle': 'FanDuel Championship Leagues',
			            'foliocolor': 'fanduel',
			            'foliolink': 'fanduel-championship-leagues',
			            'folioimage': 'test.png',
			            'folioskills': 'Mobile App Design, UX',
			            'foliodescription': 'Championships is a groundbreaking fantasy sports platform.',
			            'foliowidth': 'grid-6 grid-6--right'
			        }
			%}
			<div class="clear"></div>
    	</div>
    	<div class="grid-container-flex">
			{% include 'partials/projectgrid.html.twig'
			        with {
			            'foliotitle': 'FanDuel Championship Leagues',
			            'foliocolor': 'fanduel',
			            'foliolink': 'fanduel-championship-leagues',
			            'folioimage': 'test.png',
			            'folioskills': 'Mobile App Design, UX',
			            'foliodescription': 'Championships is a groundbreaking fantasy sports platform.',
			            'foliowidth': 'grid-6 grid-6--left'
			        }
			%}
			{% include 'partials/projectgrid.html.twig'
			        with {
			            'foliotitle': 'FanDuel Championship Leagues',
			            'foliocolor': 'fanduel',
			            'foliolink': 'fanduel-championship-leagues',
			            'folioimage': 'test.png',
			            'folioskills': 'Mobile App Design, UX',
			            'foliodescription': 'Championships is a groundbreaking fantasy sports platform.',
			            'foliowidth': 'grid-6 grid-6--right'
			        }
			%}
			<div class="clear"></div>
    	</div>
    </div>
</section>

