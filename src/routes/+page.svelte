<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Skin regeneration powered by concentrated GHK-Cu peptides"
	subtitle="Clinical-strength formulations that stimulate collagen production and deliver real anti-aging results."
	imageSrc="https://www.unc.mn/image-placeholder.svg"
	centered={false}
/>
<LogoScroller
	label="Trusted by skincare enthusiasts"
	logoUrls={[
		'https://cdn.brandfetch.io/sephora.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/dermstore.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/net-a-porter.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/nordstrom.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Science-backed skincare"
	text="We formulate concentrated GHK-Cu peptide serums that work at the cellular level to regenerate skin and reverse visible signs of aging. Designed for discerning skincare enthusiasts who've tried everything else, our clinical-strength formulations deliver the collagen-boosting results that weaker products simply can't match."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Sharma",
			position: "Marketing Director",
			company: "Age 42",
			quote:
				"After trying countless serums, this is the first product that delivered visible results in just 6 weeks. My fine lines are noticeably softer, and I'm saving $300 monthly on spa treatments that never worked as well.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Marcus Chen",
			position: "Attorney",
			company: "Age 38",
			quote:
				"The concentrated GHK-Cu formula simplified my entire routine to 2 minutes daily. My skin looks healthier than it did five years ago, and I avoided the risk and expense of invasive procedures my colleagues tried.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sofia Ramirez",
			position: "Entrepreneur",
			company: "Age 46",
			quote:
				"I was skeptical of peptide claims until I saw clinical studies backing GHK-Cu. Three months in, my dermatologist noticed improved skin texture and elasticity. This replaced four products in my routine and actually works.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	title="Why concentrated GHK-Cu peptides work"
	subtitle="Real science, real results"
	features={[
		{
			title: "Clinical-strength concentration",
			description:
				"Our formulations contain therapeutic levels of GHK-Cu peptides that actually penetrate skin and stimulate collagen synthesis, unlike diluted alternatives that barely register."
		},
		{
			title: "Proven collagen production",
			description:
				"GHK-Cu peptides trigger your skin's natural regeneration pathways to rebuild collagen and elastin. Clinical studies show visible improvement in fine lines and skin firmness within 8-12 weeks."
		},
		{
			title: "No ingredient confusion",
			description:
				"We focus on one powerhouse active ingredient at optimal concentration rather than mixing dozens of weak actives that compete and dilute effectiveness."
		},
		{
			title: "Dermatologist-validated results",
			description:
				"Before-and-after clinical documentation shows measurable improvements in skin texture, elasticity, and fine lines, verified by independent dermatologists."
		},
		{
			title: "Science-backed formulation",
			description:
				"Every product is formulated based on peer-reviewed research on GHK-Cu peptide efficacy, ensuring you get clinically meaningful concentrations that deliver results."
		},
		{
			title: "Transparent ingredient strength",
			description:
				"We publish exact peptide concentrations on every product so you know exactly what you're getting, with no marketing fluff or proprietary blend hiding."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop wasting money on products that don't work"
	subtitle="Start seeing real results in 8 weeks"
	description="Clinical-strength GHK-Cu peptides backed by peer-reviewed research. Join thousands of skincare enthusiasts who stopped chasing the next miracle product and started rebuilding their skin at the cellular level. Every day you wait is another day of collagen loss."
	imageSrc="https://www.unc.mn/image-placeholder.svg"
	callsToAction={[
		{
			href: "/get-started",
			label: "Start your transformation",
			variant: "primary"
		},
		{
			href: "/clinical-results",
			label: "See clinical results",
			variant: "secondary"
		}
	]}
/>
