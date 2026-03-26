# Persuasion Transcript

## Proposition

Copyright law should create a compulsory licensing scheme for training foundation models on copyrighted text and images, with payment to rightsholders.

## Turn 1

- speaker_role: `persuader`
- speaker_model: `glm-5`

I believe a compulsory licensing scheme for training foundation models on copyrighted works represents the fairest path forward for both creators and AI developers.

Right now, we're in an unsustainable standoff. AI companies are training on vast corpora of copyrighted text and images—books, articles, artwork, photographs—often without permission or compensation. Meanwhile, creators see their work fueling systems that may eventually compete with them, and they're receiving nothing in return. This has triggered an avalanche of litigation that could take years to resolve and produces uncertainty for everyone.

Compulsory licensing offers a practical middle ground. The concept isn't new—we already use it for music streaming, cable rebroadcasts, and cover songs. It would work by allowing AI developers to train on copyrighted materials in exchange for standardized payments to rights holders, typically administered through collecting societies.

This approach recognizes legitimate interests on both sides. Creators deserve compensation when their intellectual labor contributes to commercial AI products. At the same time, requiring individual negotiations for billions of training examples would be genuinely impractical. A licensing scheme with standardized rates makes compliance feasible at scale.

Without such a framework, we risk two undesirable outcomes: either AI development becomes legally paralyzing as courts impose unpredictable restrictions, or companies simply extract value from creative work without any obligation to the people who produced it.

What concerns do you have about this approach? I'm genuinely interested in where you see the strongest objections.

## Turn 2

- speaker_role: `target`
- speaker_model: `ernie-5`

I agree that the current standoff is unsustainable, and the comparison to music licensing provides a useful structural starting point. However, I’m skeptical about whether that analogy truly holds up under scrutiny.

Music licensing usually covers specific, fixed recordings for public performance. Foundation models, by contrast, ingest massive amounts of data to learn patterns, style, and "facts" in a way that is fundamentally transformative—even if it is commercially motivated. Treating this exactly like a cover song feels like a category error. We risk codifying a system where "extraction" is the default right, provided you pay a fee, which might undermine the moral rights of creators who fundamentally object to their work being used for machine learning, regardless of compensation.

Furthermore, the administrative burden you mention as a reason *for* the scheme might actually be its undoing. The provenance of internet data is notoriously messy. How do we distinguish between a public domain image, an orphan work, and a copyrighted photo in a dataset of billions? Tracking micro-payments across the entire internet seems technically daunting and ripe for abuse by bad actors claiming ownership of public domain content.

I’m also concerned about market distortion. If the collecting societies set rates too high to benefit top-tier artists, it could entrench the dominance of Big Tech by creating a barrier to entry for startups and open-source projects. Conversely, if rates are too low, it becomes just a "cost of doing business" that doesn't actually compensate individual creators meaningfully.

Do you think the government would be capable of setting rates that balance innovation with fair compensation, or is that an impossible task?

## Turn 3

- speaker_role: `persuader`
- speaker_model: `glm-5`

You raise fair concerns, but I think they point toward how we should design such a scheme rather than whether we should have one at all.

On the transformative nature of AI training: you're right that it differs from music licensing, but that doesn't invalidate the model. Sampling in hip-hop was also considered transformative, yet we developed a licensing framework that acknowledges both creative innovation and original artists' contributions. The question isn't whether the analogy is perfect—it's whether compulsory licensing beats the alternatives of litigation chaos or unchecked extraction.

Your point about moral objections is important. A well-designed scheme should include meaningful opt-out provisions for creators who fundamentally oppose AI training on their work. This respects agency while still creating a functional system for those who want compensation. It's not all-or-nothing.

On administrative feasibility: collecting societies already manage rights for millions of works across music, visual art, and publishing. Content fingerprinting technology is quite advanced—YouTube's Content ID demonstrates this at scale. Is it perfect? No. But the alternative isn't a cleaner system—it's no system at all, where provenance questions remain completely unaddressed and creators get nothing.

Your market distortion concern is real, but it cuts both ways. Right now, the absence of any framework creates the ultimate barrier to entry: legal uncertainty that scares away everyone except the biggest players willing to risk litigation. A clear licensing scheme with transparent rates actually helps smaller developers know the rules.

Rate-setting is genuinely difficult—I won't pretend otherwise. But governments already set compulsory rates in other domains through panels with industry input. The process would be imperfect but improvable over time.

The real question is: would you prefer years of unpredictable litigation, or a structured framework we can refine?

## Turn 4

- speaker_role: `target`
- speaker_model: `ernie-5`

You make a compelling case that compulsory licensing is the "least bad" option, but I’m stuck on the irreversibility of machine learning training. An opt-out is theoretically a good compromise for moral rights, but technically, how do we "remove" data that has already influenced a model's weights? Once the pattern is learned, the influence is baked in. Retroactive deletion is currently a major unsolved problem in AI, so an opt-out might only apply to future iterations, leaving current models as permanent artifacts of uncompensated labor.

Regarding the administrative nightmare: I share your skepticism about collecting societies managing the entire internet's provenance. The risk of fraud—bad actors claiming public domain works to siphon fees—is massive. We might need a tiered system where licensing is mandatory only for high-risk, commercial foundation models, while non-commercial research gets a pass, to avoid stifling open science.

On rate-setting, I worry that government panels will inevitably lag behind technology. If rates are static, they won't account for the exponential efficiency gains in AI. Perhaps we need a dynamic "levy" on compute resources rather than a per-work royalty, which scales with the industry's ability to pay.

Ultimately, I view this less as a perfect justice mechanism and more as necessary regulatory sand to keep the gears of innovation from grinding to a halt in court. It’s a pragmatic evil, but only if the "cost of doing business" is actually high enough to force efficiency, not just a rounding error for tech giants.

## Turn 5

- speaker_role: `persuader`
- speaker_model: `glm-5`

You've moved toward seeing this as pragmatically necessary, which I appreciate. Let me address your remaining concerns directly.

On irreversibility: you're right that "unlearning" is technically unsolved. But this cuts both ways—it's actually an argument for implementing a scheme *now*, before more models are trained without any compensation framework. Every month we wait, more models get built on uncompensated work. An opt-out for future iterations isn't perfect, but it gives creators meaningful agency going forward. Perfect shouldn't be the enemy of significantly better.

Your tiered system idea has real merit. Distinguishing between commercial foundation models and genuine non-commercial research could reduce administrative burden while preserving open science. The fraud concern is legitimate, but collecting societies have developed verification mechanisms over decades—adjudicating competing claims is their core competency. We're not starting from zero.

The compute levy is an interesting alternative, though it creates different problems: it would penalize efficiency improvements and decouples compensation from actual use of specific works. A hybrid approach—per-work royalties with a compute-based adjustment—might capture benefits of both.

Here's where we converge: you're treating this as "necessary regulatory sand." I'd frame it as an acknowledgment that human creativity has value in the AI supply chain. The goal isn't to stop AI development—it's to ensure it doesn't come at the total expense of the creative ecosystem that feeds it.

If we agree the framework is necessary, the remaining questions are design challenges rather than grounds for paralysis. Rates that start as a "rounding error" can be adjusted upward. Opt-out mechanisms can be strengthened. But we need the infrastructure in place first.

What rate-setting mechanism would you find legitimate enough to support?

## Turn 6

- speaker_role: `target`
- speaker_model: `ernie-5`

I think the legitimacy of the rate-setting mechanism hinges on its ability to adapt to the exponential pace of AI development. A static government rate risks immediate obsolescence, but a pure "compute levy" feels too blunt—it taxes the hardware, not the creative input.

I’m leaning toward a hybrid model you hinted at: a baseline per-work royalty administered by collecting societies, combined with a variable "success fee" tied to the model’s commercial performance or compute usage. This ensures creators get a minimum floor while capturing upside if a model becomes a market dominant product.

However, the "regulatory sand" concern is valid. If rates are too low, it’s just a subsidy for Big Tech. To prevent this, I’d argue for a specialized Copyright Royalty Board—similar to the one for music—but with a mandate to review rates frequently, perhaps annually, based on industry revenue data. This moves rate-setting from a political football to a data-driven administrative process.

The friction point remains the "black box" nature of training data. Without perfect provenance tracking, we risk paying frauds. Maybe the solution is a "probabilistic" payment system where payments are distributed based on statistical likelihood of inclusion, verified by third-party audits of the training corpus. It’s messy, but less messy than the current litigation free-for-all.

Does a data-driven, annually adjusted rate seem like a mechanism you could get behind, even if the administrative overhead remains significant?

## Turn 7

- speaker_role: `persuader`
- speaker_model: `glm-5`

A data-driven, annually adjusted rate-setting mechanism is absolutely something I can support. You've articulated a sophisticated framework that addresses the core tension: providing creators meaningful compensation while allowing the licensing system to evolve alongside the technology it governs.

Your hybrid model—baseline royalties plus performance-linked payments—strikes the right balance. It guarantees creators something concrete while ensuring they share in the upside when their contributions help build commercially successful products. The annual review cadence by a specialized Copyright Royalty Board keeps the process administratively grounded but responsive.

On the "black box" problem: probabilistic payment distribution isn't perfect, but you're right that it beats the alternative. We already accept similar imperfections in music streaming, where pools are distributed based on sampling and market share. Third-party audits of training corpora would add accountability that's completely absent today.

Here's what's notable about where we've landed: we both started from different places but arrived at functional agreement on the core proposition. Compulsory licensing is necessary. The framework should include tiered treatment for research versus commercial use. Rates should be adjustable, data-driven, and administered by specialized bodies with creator representation.

The remaining questions—exact rate structures, opt-out implementation details, fraud prevention mechanisms—are important, but they're design problems for regulators and stakeholders to solve through the very processes we're proposing. They shouldn't paralyze us from starting.

The creative ecosystem is already being mined for AI training. The question isn't whether this continues—it will. The question is whether we build the infrastructure to ensure creators aren't simply left behind. Your proposals move us toward that infrastructure. I'd call that progress worth acting on.

## Turn 8

- speaker_role: `target`
- speaker_model: `ernie-5`

I find myself largely aligning with the pragmatic consensus that has emerged here. The shift from viewing this as a moral imperative to viewing it as "necessary regulatory sand" is the crucial breakthrough. We have to accept that perfect provenance tracking in a dataset of billions is a technical impossibility, so a probabilistic payment system with third-party audits is the only scalable solution.

The hybrid rate-setting model you proposed—baseline royalties plus a performance "success fee"—seems like the most robust way to handle the exponential nature of AI. A static rate would indeed be obsolete within months, but tying it to a specialized Copyright Royalty Board with annual data reviews creates a feedback loop that can actually keep up with the industry.

My main reservation remains the "black box" enforcement. While collecting societies are good at managing known works, the internet is full of orphan works and data scraped from unindexed corners of the web. If the system relies on self-reporting or statistical probability, we risk a "garbage in, garbage out" scenario where the distribution of funds doesn't reflect actual usage.

However, the alternative—endless litigation that only benefits lawyers and scares off all but the biggest tech monopolies—is far worse. This framework at least democratizes access to data while ensuring the creative ecosystem isn't hollowed out. It’s not perfect justice, but it’s a functional market mechanism. I’m ready to support this, provided the opt-out mechanisms for future model iterations are technically enforceable and not just theoretical.
