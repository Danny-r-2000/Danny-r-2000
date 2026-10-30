# Danny Rajalingam

**Building AI for the physical world.**

Co-founder & CEO of **[Ember](https://www.ember-info.com/)**. Oxford DPhil researcher in **hypersonics**. Previously **Rolls-Royce Aerospace**. Now building in San Francisco.

I build the product, the agents that help me run the company, and the research tools I wish I had in the lab. The common thread is AI that understands the work in front of someone and helps them act on it.

[Explore Ember](https://www.ember-info.com/) · [Guardian in 3D](https://www.ember-info.com/guardian) · [Research code](https://github.com/Danny-r-2000/hypersonic_boundary_layers) · [LinkedIn](https://www.linkedin.com/in/danny-rajalingam/) · [Email](mailto:danny.rajalingam@ember-info.com)

## Ember is my main focus

A construction job changes. The paperwork has to keep up.

Ember writes, checks, and keeps safety documents current. Risk assessments, method statements, permits, and temporary works records. Each finding quotes its source. People review the evidence and sign off. Crews use their phones; managers get the review queue and audit trail.

**Built on live sites with Laing O'Rourke, Oxford Estates, and Scale Space. Backed by Sterling Road and the University of Oxford.** We started in Oxford and now serve teams in the UK and the US.

[See the product](https://www.ember-info.com/product) · [How we started](https://www.ember-info.com/about)

### Ember Guardian

I'm also developing Guardian, a connected hardhat concept with a camera and bone-conduction audio. The aim is to help workers spot hazards while their hands are busy. It extends the same work into computer vision and wearable hardware.

**Concept in development.** Explore the interactive 3D design and watch the concept demo.

<a href="https://www.ember-info.com/guardian">
  <img src="https://www.ember-info.com/images/guardian-concept.png" alt="Ember Guardian connected hardhat concept, currently in development. Open the interactive 3D design." width="420" />
</a>

## My personal agents

I use the company as a proving ground for the agents I build.

| Agent | Work it handles |
| --- | --- |
| **Rocky** | My chief of staff. Morning briefings, meeting preparation, email drafts, follow-ups, and memory of people, projects, and commitments. |
| **Friday** | Sales and marketing. Company research, call preparation, pipeline tracking, CRM reports, and outreach drafts. |

They combine durable memory, scheduled workflows, and Slack conversations with shared company context. External messages stay under human review. Friday calculates CRM metrics in Python before an agent writes the report.

<details>
<summary>Earlier builds: TARS, CASE, and Victra</summary>

I also built **TARS** to implement approved specifications, **CASE** for code review and pre-mortems, and **Victra** for product planning. Those original runtimes are now shelved or retired. They helped me work out where to separate implementation, review, and approval.

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

I build the web experiences around the work too. [Ember's website](https://www.ember-info.com/) includes product demos, customer workflows, and signup flows. The [Guardian experience](https://www.ember-info.com/guardian) lets visitors rotate and explore the hardware concept. My web stack includes Next.js, React, TypeScript, and Tailwind.

Before Oxford, I studied Advanced Aeronautical Engineering at Imperial College London and worked as an aerospace graduate engineer at Rolls-Royce.

**Building in construction, engineering, or applied AI? [Get in touch](mailto:danny.rajalingam@ember-info.com).**
