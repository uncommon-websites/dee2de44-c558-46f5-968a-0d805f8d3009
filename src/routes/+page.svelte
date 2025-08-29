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
	text="Avido accelerates financial services AI deployment by 6-12 months through automated compliance monitoring and proactive risk assessment, helping banks deploy customer-facing AI applications within regulatory deadlines."
	imageSrc="/generated/image-a-group-of-financial-services-profession.webp"
/>

<Testimonials
	testimonials={[
		{
			name: "Sarah Chen",
			position: "Chief Risk Officer",
			company: "Regional Bank",
			quote:
				"Avido reduced our AI deployment timeline from 18 months to 6 months.\nTheir automated compliance monitoring gave us confidence to launch customer-facing chatbots without regulatory concerns.",
			image: "/generated/image-a-professional-woman-banker-in-a-tailore.webp"
		},
		{
			name: "Michael Rodriguez",
			position: "AI Product Manager",
			company: "Community Credit Union",
			quote:
				"The pre-built regulatory frameworks passed our audit in just 3 weeks.\nAvido's proactive risk assessment identified potential issues before they became costly problems.",
			image: "/generated/image-a-professional-man-risk-manager-in-a-cri.webp"
		},
		{
			name: "Jessica Thompson",
			position: "Head of AI Strategy",
			company: "Mid-Market Bank",
			quote:
				"We deployed 5 compliant AI applications in the time it used to take for one.\nAvido's expertise in financial services regulations is unmatched in the AI governance space.",
			image: "/generated/image-a-professional-woman-ai-manager-in-a-chi.webp"
		}
	]}
/>

<Features
	title="Features"
	subtitle="AI compliance made simple"
	features={[
		{
			title: "Automated compliance monitoring",
			description:
				"Continuously monitor AI systems for regulatory compliance with automated audit trails that save the equivalent of one full-time employee per application.",
			imageSrc: "/generated/image-a-professional-woman-an-ai-compliance-le.webp"
		},
		{
			title: "Proactive risk assessment",
			description:
				"Identify and address potential risks before they become costly problems with actionable insights and comprehensive risk analysis.",
			imageSrc: "/generated/image-a-professional-man-a-financial-technolog.webp"
		},
		{
			title: "Pre-built regulatory frameworks",
			description:
				"Deploy customer-facing AI applications 6-12 months faster with frameworks designed specifically for financial services regulations.",
			imageSrc: "/generated/image-a-professional-woman-a-risk-management-d.webp"
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Ready to accelerate your AI deployment?"
	subtitle="Join leading banks"
	description="Deploy compliant AI applications 6-12 months faster with Avido's automated compliance monitoring and pre-built regulatory frameworks designed for financial services."
	imageSrc="/generated/image-a-confident-professional-financial-servi.webp"
/>
