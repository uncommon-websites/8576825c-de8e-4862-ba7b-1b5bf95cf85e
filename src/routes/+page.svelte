<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
</script>

<CustomerCardHero
	centered={true}
	title="Strategic finance partners for growing businesses"
	subtitle="From startup funding to fractional CFO services, we provide the financial expertise and operational execution you need to scale confidently."
	customers={[
		{
			name: "Michael Thompson",
			position: "CEO, TechFlow Solutions",
			imageSrc: "/generated/image-centered-portrait-of-a-professional-midd.webp"
		},
		{
			name: "Sarah Chen",
			position: "Founder, GreenVentures",
			imageSrc: "/generated/image-centered-portrait-of-a-professional-fema.webp"
		},
		{
			name: "David Rodriguez",
			position: "Co-founder, DataSync",
			imageSrc: "/generated/image-centered-portrait-of-a-professional-male.webp"
		},
		{
			name: "Amanda Foster",
			position: "CEO, FinTech Innovations",
			imageSrc: "/generated/image-centered-portrait-of-a-professional-fema.webp"
		},
		{
			name: "James Wilson",
			position: "Founder, CloudScale",
			imageSrc: "/generated/image-centered-portrait-of-a-professional-male.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hubspot.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/atlassian.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Finance clarity. Strategic control."
	text="We bring investor-grade expertise to your business—so you can grow with confidence, increase profitability, and prepare for your next move. Many SMBs run without clear reporting, strategic planning, or visibility into what's really driving profit. We fix that."
/>

<Testimonials
	testimonials={[
		{
			name: "Alexandra Martinez",
			position: "CEO",
			company: "Precision Manufacturing Co.",
			quote:
				"LIMESTONE transformed our financial chaos into clarity. Within 90 days, we identified $2.3M in cost savings and secured our Series A funding 6 months ahead of schedule. Their fractional CFO approach gave us enterprise-level financial strategy at a fraction of the cost.",
			image: "/generated/image-professional-headshot-of-a-confident-mid.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Founder",
			company: "Sustainable Energy Solutions",
			quote:
				"Before LIMESTONE, we were flying blind financially. Now we have real-time dashboards and monthly board-ready reports that helped us avoid a potential cash flow crisis. Their proactive approach saved us from what could have been a $500K bridge loan.",
			image: "/generated/image-professional-headshot-of-a-successful-ma.webp"
		},
		{
			name: "Victoria Chen",
			position: "Managing Director",
			company: "Digital Health Ventures",
			quote:
				"The financial infrastructure LIMESTONE built reduced our month-end close from 3 weeks to 5 days. This efficiency gain freed up 40 hours monthly that we now invest in strategic initiatives. Their investor-grade reporting directly contributed to our successful $15M Series B.",
			image: "/generated/image-professional-headshot-of-an-experienced-.webp"
		}
	]}
/>

<Features
	title="Strategic finance that scales with your growth"
	subtitle="From startup funding to fractional CFO expertise, we provide the financial foundation and strategic guidance that transforms good businesses into great ones"
	features={[
		{
			title: "Investor-grade financial reporting",
			description: "Transform unclear financials into compelling data stories that secure funding and drive strategic decisions with confidence."
		},
		{
			title: "Fractional CFO partnership",
			description: "Access C-suite financial expertise without the full-time commitment, providing strategic leadership precisely when you need it most."
		},
		{
			title: "Capital raising facilitation",
			description: "Navigate the complex funding landscape with seasoned expertise that connects your growth story to the right investors."
		},
		{
			title: "Operational finance execution",
			description: "Bridge the gap between financial strategy and daily operations with hands-on implementation that delivers measurable results."
		},
		{
			title: "Growth transition planning",
			description: "Prepare your business for acquisition or exit with strategic positioning that maximizes valuation and ensures smooth transitions."
		},
		{
			title: "Data-driven decision support",
			description: "Convert financial complexity into clear insights that unlock growth opportunities and prevent costly strategic missteps."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
