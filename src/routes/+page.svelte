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
	title="Reclaiming human agency"
	text="Earendil transforms email into an intelligent command center by embedding AI directly into your inbox. We serve knowledge workers at tech companies frustrated by fragmented workflows, enabling natural language control over data and connections without vendor lock-in. Built on open email protocols you already own, Earendil strengthens human agency instead of eroding it."
/>

<Testimonials
	testimonials={[
		{
			name: "Keiko Tanaka",
			position: "VP Engineering",
			company: "Prism Technologies",
			quote:
				"We reclaimed 12 hours per week per engineer by eliminating context switches between Slack, email, and five different AI tools. Earendil's command center approach means our team controls everything through natural language in the inbox they already live in.",
			image: "/generated/image-professional-asian-woman-engineer-confid.webp"
		},
		{
			name: "Jordan Mitchell",
			position: "CTO & Co-founder",
			company: "Axiom Labs",
			quote:
				"Data sovereignty was non-negotiable for us. Earendil's open protocol foundation eliminated vendor lock-in risk entirely while cutting our AI tooling costs by 60%. We own our infrastructure, choose our models, and maintain complete control.",
			image: "/generated/image-professional-black-man-founder-confident.webp"
		},
		{
			name: "Layla Hassan",
			position: "Head of Operations",
			company: "Vertex Systems",
			quote:
				"After consolidating seven fragmented tools into Earendil, we saved $5,800 monthly and reduced onboarding time by half. Our team's coordination improved dramatically because everything flows through one intelligent system they already know.",
			image: "/generated/image-professional-middle-eastern-woman-execut.webp"
		}
	]}
/>

<Features
	title="Built for human agency"
	subtitle="Transform your inbox into an intelligent command center while maintaining full control over your AI interactions and data."
	features={[
		{
			title: "Eliminate context-switching",
			description:
				"Trigger AI workflows, query data, and manage connections through natural language directly in your inbox. Stop wasting hours jumping between fragmented tools.",
			icon: IconCommand
		},
		{
			title: "Your AI, your rules",
			description:
				"Choose which AI models you use and maintain complete ownership of your data. No vendor lock-in, no algorithms deciding for you.",
			icon: IconShield
		},
		{
			title: "Open protocols, not walled gardens",
			description:
				"Built entirely on open email protocols you already own, ensuring your communication infrastructure remains under your control forever.",
			icon: IconMail
		},
		{
			title: "Context that actually helps",
			description:
				"Semantic clustering organizes your data into a real-time personal data lake, giving AI the context it needs to deliver genuinely useful responses.",
			icon: IconBrain
		},
		{
			title: "Built for developers",
			description:
				"Open-source architecture with webhooks and APIs lets you extend functionality and build custom integrations that match your exact workflow.",
			icon: IconCode
		},
		{
			title: "Privacy that strengthens agency",
			description:
				"User-controlled infrastructure designed to amplify human decision-making, not replace it. Your data stays yours, your choices stay yours.",
			icon: IconLock
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop letting fragmented tools control your workflow"
	subtitle="Start with 20 threads free"
	description="Join knowledge workers at tech companies who've reclaimed hours daily by embedding AI directly into their inbox. Built on open protocols you own, no vendor lock-in, no credit card required. Your data stays yours. Your decisions stay yours."
	imageSrc="/generated/image-a-focused-developer-smiling-while-workin.webp"
/>
