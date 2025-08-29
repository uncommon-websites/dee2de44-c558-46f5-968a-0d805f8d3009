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
	title="Deploy compliant AI 6-12 months faster"
	subtitle="Join leading financial institutions using Avido to accelerate AI deployment while meeting regulatory requirements from day one."
	centered={true}
	customers={[
		{
			name: "Sarah Chen",
			position: "Chief Risk Officer",
			imageSrc: "/generated/image-a-professional-woman-banker-in-a-tailore.webp"
		},
		{
			name: "Michael Rodriguez",
			position: "AI Product Manager",
			imageSrc: "/generated/image-a-professional-man-risk-manager-in-a-cri.webp"
		},
		{
			name: "Jessica Thompson",
			position: "Head of AI Strategy",
			imageSrc: "/generated/image-a-professional-woman-ai-manager-in-a-chi.webp"
		},
		{
			name: "David Park",
			position: "Compliance Director",
			imageSrc: "/generated/image-a-professional-man-compliance-officer-in.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/wellsfargo.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/pnc.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/regions.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/navyfederal.org/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser />
<CallToAction />
