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
	import IconCommand from "~icons/lucide/command";
	import IconShield from "~icons/lucide/shield";
	import IconMail from "~icons/lucide/mail";
	import IconBrain from "~icons/lucide/brain";
	import IconCode from "~icons/lucide/code";
	import IconLock from "~icons/lucide/lock";
</script>

<CenteredTextOnlyHero
	title="Your inbox, powered by AI you control"
	subtitle="Transform email into an intelligent command center with natural language control over your data and connections."
	imageSrc="/generated/image-a-modern-indoor-lounge-space-with-a-styl.webp"
/>
<LogoScroller
	label="Trusted by forward-thinking teams"
	logoUrls={[
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/linear.app/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/github.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Building email's future"
	text="Earendil embeds AI directly into your inbox, transforming email into an intelligent command center you control. We serve knowledge workers at tech companies who waste hours context-switching between fragmented tools, enabling them to manage data and connections through natural language without losing control to vendor lock-in."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Chen",
			position: "Engineering Lead",
			company: "Helios Labs",
			quote:
				"Earendil eliminated the 2 hours I was losing daily to context-switching between email and AI tools. Having natural language control directly in my inbox means I can query our data, schedule meetings, and manage workflows without ever leaving the conversation thread.",
			image: "/generated/image-a-professional-asian-male-engineer-stand.webp"
		},
		{
			name: "Amara Williams",
			position: "VP of Product",
			company: "Tessera AI",
			quote:
				"The open protocol foundation gave us confidence we'd never have vendor lock-in. We control our data completely, choose which AI models we use, and maintain full ownership of our communication infrastructure. That's worth more than any feature.",
			image: "/generated/image-a-professional-black-female-leader-in-a-.webp"
		},
		{
			name: "Diego Ramirez",
			position: "Founder & CEO",
			company: "Cascade Systems",
			quote:
				"We consolidated five different tools into Earendil and cut our software spend by $4,200 monthly. More importantly, our team's response time improved by 40% because everything flows through one intelligent command center they already live in.",
			image: "/generated/image-a-professional-latino-male-founder-in-a-.webp"
		}
	]}
/>

<Features
	title="Built for human agency"
	subtitle="Transform your inbox into an intelligent command center while maintaining full control over your AI interactions and data."
	features={[
		{
			title: "Natural language control",
			description:
				"Command your email with natural language to trigger AI workflows, query data, and manage connections without leaving your inbox.",
			icon: IconCommand
		},
		{
			title: "Your AI, your choice",
			description:
				"Choose which AI models you interact with and maintain complete control over your data. No vendor lock-in, no hidden algorithms deciding for you.",
			icon: IconShield
		},
		{
			title: "Open protocol foundation",
			description:
				"Built entirely on open email protocols you already own, ensuring your communication infrastructure remains under your control forever.",
			icon: IconMail
		},
		{
			title: "Intelligent context",
			description:
				"Semantic clustering automatically organizes disparate data types into a real-time personal data lake, giving AI the context it needs to be truly helpful.",
			icon: IconBrain
		},
		{
			title: "Developer-friendly",
			description:
				"Open-source first architecture with webhooks and APIs that let you build custom integrations and extend functionality to match your workflow.",
			icon: IconCode
		},
		{
			title: "Privacy by design",
			description:
				"Your data stays yours with user-controlled infrastructure that strengthens human agency instead of eroding it.",
			icon: IconLock
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
