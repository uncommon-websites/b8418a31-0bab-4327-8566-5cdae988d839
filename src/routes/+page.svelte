<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
	
	// Icons
	import IconZap from "~icons/lucide/zap";
	import IconScale from "~icons/lucide/scale";
	import IconSprout from "~icons/lucide/sprout";
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconEye from "~icons/lucide/eye";
	import IconHandshake from "~icons/lucide/handshake";
</script>

<CenteredTextOnlyHero
	title="Fair memecoin launches start here"
	subtitle="Launch your memecoin with zero pre-bonding fees. Build organic communities through equitable distribution that maximizes token survival and aligns creator and community incentives from day one."
	imageSrc="/generated/image-a-modern-softly-lit-interior-space-with-.webp"
/>
<LogoScroller
	label="Trusted by crypto builders"
	logoUrls={[
		'https://cdn.brandfetch.io/base.org/w/400/h/400/logo',
		'https://cdn.brandfetch.io/uniswap.org/w/400/h/400/logo',
		'https://cdn.brandfetch.io/opensea.io/w/400/h/400/logo',
		'https://cdn.brandfetch.io/metamask.io/w/400/h/400/logo'
	]}
/>

<Summary
	title="Our approach"
	text="Openmint lets you launch memecoins without paying upfront fees. Zero pre-bonding costs means your capital stays with creators and early holders, not the launchpad. Fair distribution from the start helps communities form organically before liquidity locks, maximizing token survival instead of extracting value."
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Chen",
			position: "Community Lead",
			company: "PepeDAO",
			quote:
				"Openmint saved us $12,000 in pre-launch fees that would have killed our momentum. Zero fees meant we could focus on building a real community instead of extracting value from day one. Our token survived 90 days with 3,000 active holders.",
			image: "/generated/image-professional-headshot-of-a-young-asian-w.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Founder",
			company: "MoonRise Protocol",
			quote:
				"After two failed launches on traditional platforms, Openmint's fair distribution mechanics changed everything. We went from launch to bonding curve in 48 hours with completely organic growth. No rug pull fears, no extracted fees, just real community building.",
			image: "/generated/image-professional-headshot-of-an-african-amer.webp"
		},
		{
			name: "Layla Mansour",
			position: "Creator",
			company: "DogeCoin Collective",
			quote:
				"The transparent pre-bonding structure gave our community confidence from the start. We reduced launch risk by 80% and attracted genuine believers instead of pump-and-dump traders. Three months later, our token has better survival metrics than anything we've seen.",
			image: "/generated/image-professional-headshot-of-a-middle-easter.webp"
		}
	]}
/>

<Features
	title="Built for fair launches"
	subtitle="Launch mechanics designed to maximize token survival and community success through equitable distribution and zero extractive fees"
	features={[
		{
			title: "Zero pre-bonding fees",
			description:
				"Launch your memecoin without extractive fees eating into early momentum. We eliminate the upfront costs that kill projects before they start, letting your community allocate resources to growth instead of platform fees.",
			icon: IconZap
		},
		{
			title: "Equitable distribution",
			description:
				"Fair allocation mechanics ensure every participant gets equal opportunity. Our bonding curve prevents whale manipulation and creates healthy token distribution from day one.",
			icon: IconScale
		},
		{
			title: "Organic community growth",
			description:
				"Give your community time to form naturally before liquidity locks. Unlike rushed launches, our pre-bonding phase lets genuine believers find your project and build momentum organically.",
			icon: IconSprout
		},
		{
			title: "Maximum token survival",
			description:
				"Our zero-fee structure and fair mechanics dramatically increase project longevity. By aligning creator and community incentives, we help projects thrive beyond the initial launch hype.",
			icon: IconTrendingUp
		},
		{
			title: "Transparent launch process",
			description:
				"Every step of your token launch is clear and auditable. Our Scandinavian-inspired design philosophy brings simplicity and transparency to complex crypto mechanics.",
			icon: IconEye
		},
		{
			title: "Aligned incentives",
			description:
				"We succeed when your token succeeds. Our revenue model shifts to post-bonding, ensuring platform incentives align perfectly with creator and community outcomes.",
			icon: IconHandshake
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
