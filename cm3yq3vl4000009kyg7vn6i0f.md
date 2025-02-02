---
title: "The Art of Moving Clouds: Migration for Less Complexity and More Simplicity."
seoTitle: "Cloud Migration"
seoDescription: "AWS Cloud Migrations"
datePublished: Tue Nov 26 2024 17:20:58 GMT+0000 (Coordinated Universal Time)
cuid: cm3yq3vl4000009kyg7vn6i0f
slug: the-art-of-moving-clouds-migration-for-less-complexity-and-more-simplicity
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1732640569832/558813d9-1835-42a0-93ea-3f42869cedba.png
tags: aws, architecture, cloud-computing

---

We all have stories to tell, and here’s one worth sharing.

Universal Pictures’ *Migration* perfectly captures the exhilaration of moving to new horizons. The mallards’ journey is one of discovery—filled with surprises, setbacks, and triumphs, but ultimately, every moment is worth it.

If only cloud migrations were as effortless as soaring from cloud to cloud. While the comparison may seem whimsical, there’s a lesson hidden in their journey: **every successful migration requires a phased approach.**

Let me explain.

**Cloud: The Icing on the Cake**

Migration is like planning a road trip. It’s not just about the thrill of reaching your destination but the careful preparation and milestones along the way. Months of anticipation, mapping the route, choosing the stops—all leading to the promise of something better.

Here’s the secret: **cloud is the icing on the cake.** But the migration itself? That’s where the recipe for success begins.

With the right frameworks, tools, and techniques, you can pave the road to your ideal destination, one thoughtful step at a time.

**Let’s gain perspective.**

Like the mallards, embarking on a migration journey can be exhilarating. But without meticulous planning, the path can become fraught with challenges. Knowing this changes everything:

**Not all migrations are created equal.** Each strategy—like a carefully planned route—leads to a different destination. The art lies in aligning your approach with your goals.

**Here’s the good part**

Use the **The SIMPLe Framework** to plan meticulously. Take action. Move forward—deliberately and fast.

The Art of Intentional Simplicity adopting the SIMPLe Framework works. You can find this SIMPLe framework that we use explained in our newsletter here: [https://leesync.substack.com/](https://leesync.substack.com/)

Every strategy, every decision must be intentional. And with the right frameworks, you can make thoughtful choices to ensure your migration is not just a move but a transformation.

Whether you’re lifting and shifting or breaking everything apart to rebuild, you’re doing more than moving workloads. **You’re reshaping your future.**

In this week’s **Sync Nimbus**, we’re diving into the **art of cloud migration strategies**—not just the steps but the why, the how, and the spark of ingenuity behind each move.

Let’s explore the choices and let’s layer in some elegance. The **SIMPLe Framework** adds clarity to chaos:

**The 7 R’s of Cloud Migration: Which Route is Yours?**

You have your product ready to go and excited to show your awaiting customers on the waiting list to get them onboard asap. 

Product launch needs to be fast with growth factored in from the outset. No architectural changes required, quick and easy to do with minimum effort.

**1\. Rehost (Lift-and-Shift)**

Think of this as moving all your furniture into a new house *exactly* as it was. No new layouts, just a fresh location. The quick, no-frills route. Pick up your workloads and move them to the cloud as-is.

> **Why It Works**: Perfect for fast scalability when time is of essence.
> 
> • **Architect’s Insight**: Rehosting is like moving into a new home but keeping the same furniture and layout.
> 
> It’s not transformative, but it’s essential when speed is the priority.
> 
> This strategy is a reminder that sometimes stability and familiarity are more critical than reinvention.
> 
> The architect’s role here is to see the potential in what’s already working while preparing for future improvements.

A healthcare provider needed to scale fast during the pandemic to support telemedicine. Rehosting their on-premise patient portals to AWS EC2, ensuring rapid scalability without disrupting existing workloads.

**2\. Replatform (Lift, Tinker, and Shift)**

A subtle upgrade. Move workloads with minor optimisations, like shifting to managed services.

> • **Why It Works**: Reduces maintenance overhead without rethinking your entire stack.
> 
> • **Architect’s Insight**: Replatforming is the art of refinement.
> 
> Like upgrading appliances during a move, it doesn’t disrupt your foundation but makes everyday operations smoother and more efficient.
> 
> As architects, we see replatforming as an opportunity to breathe life into legacy systems, extending their utility while laying a foundation for modernisation.

Let’s take a look at a growing Fin~Tech startup migrating its relational database to Amazon RDS.

Switching from a self-hosted setup to a managed service, backups are automated and so are updates.

**3\. Repurchase (Go SaaS)**

Outsource non-core applications to cloud-based SaaS providers.

> • **Why It Works**: Simplifies operations for tools like CRMs or analytic platforms.
> 
> • **Architect’s Insight**: Why build it yourself when someone else already perfected it?
> 
> Repurchasing is a lesson in humility.
> 
> It’s the recognition that some battles are better fought by leveraging someone else’s expertise.
> 
> Architects understand the beauty of balance—choosing to build where it matters most and outsourcing where it doesn’t.
> 
> This strategy reflects the wisdom of focusing on your strengths while embracing external innovation.

E-commerce is great example of a Repurchase migration strategy. Let’s explore a retailer switching from an in-house CRM to Salesforce for customer management. The SaaS platform allows easy integrations with marketing and analytics tools.

**4\. Refactor (Reimagine Everything)**

The bold move. Rebuild your architecture to embrace cloud native features and microservices.

This is your “tear down the house and rebuild” moment. It’s transformative, and it’s for those chasing the cutting edge.

> • **Why It Works**: Unlocks agility. performance, and scalability.
> 
> •**Architect’s Insight:** Refactoring is akin to demolishing a house to build your dream home.
> 
> It’s bold, risky, and requires vision. But the reward?
> 
> A future-proof system that evolves with your needs.
> 
> This strategy reflects the heart of architecture: the courage to imagine and create something entirely new.
> 
> It’s where the architect becomes an innovator, sculpting structures that don’t just solve problems but inspire possibilities.

Let’s explore options for this digital first bank. Neobank re-engineered its core banking system into microservices using AWS Lambda and DynamoDB. This refactor enables them to handle spikes in demand during promotional campaigns.

**5\. Retire (Let It Go)**

Identify outdated tools or apps that no longer spark joy (or value) and let them go.

> • **Why It Works**: Simplifies your tech stack and cuts costs.
> 
> • **Architect’s Insight**: Keep only what sparks joy (and value).

Retirement is the art of subtraction—removing what no longer adds value.

It requires clarity and courage to let go, especially of systems that have served well in the past.

For architects, retiring legacy systems is about creating space for innovation. It’s a reminder that simplicity often lies not in adding more but in removing the unnecessary.

Let’s explore a SaaS company. They identified legacy tools for customer feedback collection that were redundant after implementing a modern analytics dashboard. Retiring the tool saved costs and simplified their tech stack.

**6\. Retain (Hybrid Cloud)**

Some things are better left where they are—for now. Retain critical components on-premises while migrating less sensitive ones to the cloud.

> • **Why It Works**: Balances compliance needs with the benefits of cloud flexibility.
> 
> • **Architect’s Insight**: Retaining workloads is about respect—for legacy systems, compliance needs, and institutional knowledge.
> 
> It’s not about reluctance to change but about honouring what still serves a purpose.
> 
> Architects know that compromise isn’t a weakness; it’s a strength that ensures stability while embracing progress.

A financial services firm moved its analytics workloads to AWS but retained customer-sensitive data on-premise for regulatory compliance. They used **AWS Outposts** to extend AWS services to their on-premises environment.

**7\. Relocate (VM Lift-and-Shift)**

Move your virtual machines as-is, without reconfiguring anything, with minimal changes.

> • **Why It Works**: Familiarity meets scalability.
> 
> • **Architect’s Insight:** A straightforward move for when time is right but scalability is non negotiable.

Relocating VMs is about striking a balance between speed and comfort.

It’s the bridge between familiarity and scalability.

As architects, we see relocation as a way to lay stepping stones toward modernisation without losing sight of the present. It’s a pragmatic choice that honors existing systems while preparing for future transformation.

A media company migrated its video editing and rendering workloads to **VMware Cloud on AWS**, enabling teams to collaborate remotely during the pandemic.

**Final Thoughts: The Architect’s Journey**

Migration isn’t just a technical exercise—it’s a philosophical one. Each strategy reflects a different facet of what it means to build, to simplify, and to innovate.

As architects, our role isn’t just to move workloads but to envision what they could become. Whether we’re lifting and shifting or reimagining from scratch, our purpose is clear: **to create systems that serve, inspire, and endure.**

**Until next time, Keep syncing…**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1732640656662/67e7ee92-db1e-4128-b604-b1d17b5d2887.png align="center")