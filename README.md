# Danny Rajalingam

**Building AI for the physical world.**

Co-founder & CEO of **[Ember](https://www.ember-info.com/)**. Oxford DPhil researcher in **hypersonics**. Previously **Rolls-Royce Aerospace**. Now building in San Francisco.

I build **agentic tools for aerospace vehicle design, research, and experiments**. My [open research code](https://github.com/Danny-r-2000/hypersonic_boundary_layers) includes aerodynamic surrogates for exploring design choices, physics-informed boundary-layer models, and a copilot that analyses CFD snapshots and flags deviations from target conditions.

I bring that same approach to Ember, the personal agents I use to run the company, and the websites that put the work in people's hands.

[Ember website](https://www.ember-info.com/) · [Ember repo, private](https://github.com/ember-ai-labs/ember) · [Research code](https://github.com/Danny-r-2000/hypersonic_boundary_layers) · [LinkedIn](https://www.linkedin.com/in/danny-rajalingam/) · [Email](mailto:danny.rajalingam@ember-info.com)

## Ember is my main focus

A construction job changes. The paperwork has to keep up.

Ember writes, checks, and keeps safety documents current. Risk assessments, method statements, permits, and temporary works records. Each finding quotes its source. People review the evidence and sign off. Crews use their phones; managers get the review queue and audit trail.

**Built on live sites.** We started in Oxford and now serve teams in the UK and the US.

[See the product](https://www.ember-info.com/product) · [Ember repository, access required](https://github.com/ember-ai-labs/ember) · [How we started](https://www.ember-info.com/about)

### Guardian computer vision

I'm developing Guardian's computer vision models to recognise people, PPE, and site equipment in camera feeds. The work includes model training, evaluation, and a live camera demo. The aim is to flag potential hazards and give Ember visual context for safety workflows.

**In development.** Model observations support human safety decisions.

[Watch the Guardian concept demo](https://www.youtube.com/watch?v=HaGzGudV7bU)

## My personal agents

I use the company as a proving ground for the agents I build.

| Agent | Work it handles |
| --- | --- |
| **Rocky** | My chief of staff. Morning briefings, meeting preparation, email drafts, follow-ups, and memory of people, projects, and commitments. |
| **Friday** | Sales and marketing. Company research, call preparation, pipeline tracking, CRM reports, and outreach drafts. |
| **Victra** | Product manager. Turns customer signals and founder requests into product specifications, priorities, and plans for what to build next. |

Rocky and Friday combine durable memory, scheduled workflows, and Slack conversations with shared company context. Victra is active in my product workflow. External messages stay under human review. Friday calculates CRM metrics in Python before an agent writes the report.

<details>
<summary>Earlier builds: TARS and CASE</summary>

I also built **TARS** to implement approved specifications and **CASE** for code review and pre-mortems. Those original runtimes are now shelved. They helped me work out where to separate implementation, review, and approval.

</details>

## Hypersonics, with the experiment attached

My Oxford research concerns hypersonic flight and spacecraft reentry. [Hypersonic Copilot](https://github.com/Danny-r-2000/hypersonic_boundary_layers) combines a physics-informed neural network, a pure-NumPy reverse-mode autograd engine, classical boundary-layer models, and a proactive research monitor.

The repository's **Blasius laminar-flow benchmark** reconstructs a velocity profile from **eight samples**.

| Model | Normalized-velocity RMSE |
| --- | ---: |
| Data-only MLP | 0.03232 |
| Physics-informed network | **0.00726** |

**4.45× lower error** on this benchmark. The saved metrics and training script are public.

[Inspect the metrics](https://github.com/Danny-r-2000/hypersonic_boundary_layers/blob/main/figures/metrics.json) · [Reproduce the experiment](https://github.com/Danny-r-2000/hypersonic_boundary_layers/blob/main/scripts/train_and_plot.py) · [See the comparison](https://github.com/Danny-r-2000/hypersonic_boundary_layers/blob/main/figures/pinn_vs_data_only.png)

## Websites and product experiences

I keep building across [Ember's product repository](https://github.com/ember-ai-labs/ember), the [live website](https://www.ember-info.com/), my personal agents, and the public research tools above. The website includes product demos, customer workflows, and signup flows. My web stack includes Next.js, React, TypeScript, and Tailwind. The Ember repository is private and requires access.

Before Oxford, I studied Advanced Aeronautical Engineering at Imperial College London and worked as an aerospace graduate engineer at Rolls-Royce.

**Building in construction, engineering, or applied AI? [Get in touch](mailto:danny.rajalingam@ember-info.com).**
