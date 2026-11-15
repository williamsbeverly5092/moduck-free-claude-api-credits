# Free Claude API Credits in 2026: What You Can Actually Claim

You want to test a Claude-powered feature before committing to an API budget. Searching for **free Claude API credits** brings up offers that sound interchangeable, but they are meant for different people. A new Claude Console user, an existing Max subscriber, and a startup founder face different eligibility rules.

The short answer: [Anthropic's API pricing FAQ](https://platform.claude.com/docs/en/about-claude/pricing) says new users receive free credits to test the API, but it does **not publish a fixed amount** there. Eligible paid Max, Ultra, and Team subscribers have a separate monthly API-credit benefit. Anthropic also announced a startup award, but its [current startup cohort is full](https://claude.com/programs/startups) and is not accepting new applications. These are Claude Platform credits, not a general coupon for any service that offers Claude models.

![Conceptual illustration of three Claude API credit paths: a testing path, a paid monthly path, and a closed startup path.](cover.png)

*Claude API credits follow different eligibility and availability rules.*

## Which Claude API credits are actually available?

The important distinction is where the credit lives. Claude chat and Claude Code signed in with a subscription use plan limits; a first-party API key draws on a Claude Console organization’s balance. A Console credit balance does not raise your Claude chat or subscription-based Claude Code limits. Check the balance that will actually pay for your intended request.

| Your situation | Published credit | Can you act now? | Where it applies |
|---|---|---|---|
| New Claude API user | Free test credits; Anthropic's public FAQ gives no fixed dollar amount | Check your own Claude Console offer and balance | First-party Claude API testing |
| Current Max, Ultra, or Team subscriber | Max: $100/month; Ultra: $200/month; Team: $20 per Standard seat or $100 per Premium seat, pooled up to $500/month | Eligible subscribers can claim after the plan has been active for seven days | Linked Claude Console organization |
| Startup founder | Announced one-time $1,000 API credit for program members | No new applications to the current cohort | First-party Claude API for admitted members |

The subscriber amounts and conditions come from [Anthropic's plan-credit documentation](https://platform.claude.com/docs/en/about-claude/api-credits-for-subscribers); the startup amount and closure come from Anthropic's [program announcement](https://claude.com/resources/articles/were-expanding-the-claude-startups-program-to-help-founders-build) and [current program page](https://claude.com/programs/startups), checked November 15, 2026. These are published benefit amounts, not a balance observed in any particular account.

## The new-user test credit has no published fixed amount

If you have never used the Claude API, the simplest starting point is Anthropic's own pricing FAQ. Its answer to whether there are free tiers or trials is brief: **“New users receive free credits to test the API.”** The FAQ does not attach a universal dollar amount, expiration period, or guarantee that a particular account will show a specific balance. A third-party article's “$5 trial” or similar figure is therefore a poor budget assumption.

The relevant place to check is the [Claude Console billing page](https://platform.claude.com/settings/billing) for your organization. Confirm what credit, if any, your account actually displays, when it expires, and the terms shown there *before* you design a test around it. An API key authorizes requests; it does not by itself prove that your account has a promotional balance. If you need more than a small trial, plan for the published pay-as-you-go API pricing instead of treating an unverified signup amount as funding.

This is also why a free Claude chat account is not the same thing as free Claude API usage. The chat interface and Console API have different billing and usage paths. Anthropic's FAQ supports a new-user API test-credit statement, not a claim that the Free chat plan includes the monthly subscriber credit described below.

## Paid plans include a different monthly API credit

For someone who **already pays** for Max, Ultra, or Team, the monthly benefit can be useful. [Anthropic lists](https://platform.claude.com/docs/en/about-claude/api-credits-for-subscribers) $100 USD for Max and $200 USD for Ultra. Team receives $20 per Standard seat and $100 per Premium seat in one pooled balance, capped at $500 per month. These figures are included with eligible paid plans; they are not a general free signup grant. Free, Pro, and Enterprise plans are not eligible for this particular benefit. The plan must be active and in good standing, and new subscribers can claim after seven days.

Check where the balance can be spent *before* linking an organization. It pays for the first-party Claude API, Claude Managed Agents, the Claude Agent SDK and the Console playground. It does not pay for interactive Claude Code, extra usage inside Claude apps, or Claude through AWS, Bedrock, Google Cloud or Microsoft Foundry. If your project calls Claude through another provider, the published monthly credit will not offset that provider's bill. It also does not raise your Claude or Claude Code plan usage limits.

To claim, an eligible Max or Ultra subscriber opens Settings > Billing in Claude; a Team Primary Owner or Owner opens Organization settings > Billing, finds the API credits section, and links one Claude Console organization under Anthropic's terms. You need the appropriate role on both the Claude plan and the Console organization. The [official subscriber guide](https://platform.claude.com/docs/en/about-claude/api-credits-for-subscribers) gives the role and menu details; check the organization carefully because each plan links to one organization, and the link cannot be changed without support. Anthropic says no payment method is needed on the Console side to claim or use this benefit.

The balance refreshes each billing cycle, or monthly on an annual plan, and unused credit expires without rollover. Anthropic applies it before purchased credits. That makes it useful for a real, near-term first-party API workload; subscribing solely because a headline says “free credits” can still cost more than your actual usage warrants.

## The startup credit exists, but this cohort is closed

Anthropic's October 2026 [startup-program announcement](https://claude.com/resources/articles/were-expanding-the-claude-startups-program-to-help-founders-build) described a **one-time $1,000 Claude API credit** for admitted members, alongside a year of Claude Team and other offers. The $1,000 figure is an announced API credit; partner-company offers in the same program are separate benefits and should not be added to it as if they were one API balance.

The program's [current page](https://claude.com/programs/startups) says the cohort is full and **new applications are not being accepted now**. Some third-party pages still contain detailed “how to apply” steps beneath a closure notice. Treat the current first-party status as the action rule. If you are already a member, check your program terms and Console balance. If you are not, wait for Anthropic's next cohort announcement rather than planning a project around an application you cannot currently submit.

Anthropic separately says founders backed by a VC in its partner network *may* be eligible for up to $100,000 in additional API credits claimed through that VC. That is a conditional partner path, not a generally available signup offer. Startup credits also apply to Anthropic's first-party Claude API, not to Claude access billed by AWS, Google Cloud, Azure or another third party.

## What to do next

For a first API test, start with the official pricing FAQ, then inspect your own Claude Console billing balance and expiry before setting a test budget. If you already pay for Max, Ultra or Team, check the eligibility and linking rules, and decide whether your workload actually uses the first-party API. If you are exploring the startup program, watch the official program page for a new cohort rather than following an old application walkthrough.

Another API route is a separate evaluation. Anthropic promotional credit should not be assumed to transfer to an intermediary. If Moduck is on your shortlist, [Read the documentation](https://docs.moduck.ai/) and verify the model route and billing terms before requesting a key. No Moduck free-credit offer is established here.
