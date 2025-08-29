<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Compliance first",
			description: "We believe that regulatory compliance should accelerate, not hinder, AI innovation in financial services."
		},
		{
			title: "Expertise driven",
			description: "Our deep understanding of financial services regulations sets us apart from generic AI governance platforms."
		},
		{
			title: "Customer success",
			description: "We measure our success by how much faster our customers can deploy compliant AI applications."
		}
	];
</script>

<SecondaryHero
	title="Accelerating responsible AI in financial services"
	subtitle="Building the future of compliant AI deployment"
	imageSrc="/generated/image-modern-financial-technology-office-envir.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We founded Avido in 2022 when we realized that financial institutions were struggling to deploy AI applications due to complex regulatory requirements. While others focused on building better AI models, we saw the real challenge was compliance.",
		"Our team combines deep expertise in financial services regulations with cutting-edge AI governance technology. We understand that banks need more than just powerful AI - they need AI that meets regulatory standards from day one.",
		"From our first customer deployment, we've focused on one question: 'How can we make AI compliance so seamless that it accelerates rather than slows down innovation?' This drives every feature we build and every partnership we form.",
		"Today, we're proud to help leading financial institutions deploy customer-facing AI applications 6-12 months faster than traditional approaches. Our automated compliance monitoring and pre-built regulatory frameworks are transforming how banks think about AI deployment."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="AI compliance experts with financial services expertise."
	stakeholders={[
		{
			name: "Sarah Mitchell",
			position: "Founder & CEO",
			bio: "Former Chief Risk Officer at a regional bank, Sarah founded Avido to solve the AI compliance challenges she experienced firsthand.",
			image: "/generated/image-professional-woman-ai-compliance-leader.webp"
		},
		{
			name: "David Chen",
			position: "Chief Technology Officer",
			bio: "AI governance expert with 15 years in financial technology, specializing in regulatory-compliant machine learning systems.",
			image: "/generated/image-professional-man-financial-technology-ex.webp"
		},
		{
			name: "Maria Rodriguez",
			position: "Head of Compliance",
			bio: "Former regulatory examiner with deep expertise in financial services AI regulations and risk management frameworks.",
			image: "/generated/image-professional-woman-risk-management-direc.webp"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Leading AI and fintech investors"
	stakeholders={[
		{
			name: "Andreessen Horowitz",
			image: "https://cdn.brandfetch.io/a16z.com/w/400/h/400/logo"
		},
		{
			name: "Bessemer Venture Partners",
			image: "https://cdn.brandfetch.io/bvp.com/w/400/h/400/logo"
		},
		{
			name: "Insight Partners",
			image: "https://cdn.brandfetch.io/insightpartners.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to accelerate your AI deployment?"
	subtitle="Join leading financial institutions"
	description="Partner with Avido to deploy compliant AI applications 6-12 months faster. Our automated compliance monitoring and regulatory expertise help banks innovate responsibly."
/>
