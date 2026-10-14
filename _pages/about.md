---
layout: about
title: About
permalink: /
subtitle: yinxi.li[at]uwaterloo.ca | SWAG Lab <a href='https://cs.uwaterloo.ca'>DC</a> 2555

profile:
  align: right
  image: self.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Amor fati, carpe diem</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 5 # leave blank to include all the blog posts
---

#### 🦄 About Me | Currently Master’s Student in CS
Hey there, I'm Larry! Thanks for visiting my humble page. I'm currently a Computer Science M.Math. student at the [University of Waterloo](https://uwaterloo.ca), advised by [Pengyu Nie](https://pengyunie.github.io). Before that, I received my B.Sc. in Computer Science (ELITE Stream) from [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/english/index.html), and my final year project was advised by [Eric Lo](https://appsrv.cse.cuhk.edu.hk/~ericlo). I also spent a semester as an exchange student at [ETH Zürich](https://ethz.ch/en.html) during my undergraduate, where I explored advanced topics in Machine Learning and Software Engineering.

My research is supported by grants from Prof. Nie's research group, funded by the Natural Sciences and Engineering Research Council of Canada (NSERC) and the University of Waterloo.

#### 💻 Research Interests

<p class="ri-lead">I study how LLMs and LLM agents use, compress, and adapt their context at test time, and how to make that computation efficient on real inference infrastructure. My work spans four connected directions:</p>

<div class="ri-grid">
<div class="ri-card ri-effic">
<div class="ri-head">
<span class="ri-icon"><i class="fa-solid fa-bolt"></i></span>
<div>
<span class="ri-tag">Efficiency</span>
<h5 class="ri-title">Efficient Inference &amp; Context-to-Weights</h5>
</div>
</div>
<p class="ri-desc">Making LLMs and agents cheaper to run, from the inference engine up: deciding what context to keep, compress, or move into weights, and serving long agentic workloads efficiently.</p>
<ul class="ri-chips">
<li>KV-cache compression &amp; eviction</li>
<li>Agent-aware serving (vLLM / SGLang)</li>
<li>Context &amp; KV memory to weights</li>
<li>Hypernetwork-generated adapters</li>
<li>Efficient computer-use agents</li>
</ul>
<p class="ri-related">Related: <a href="/publications/#hotsko2026code2lorahypernetworkgeneratedadapterscode">Code2LoRA</a> · ongoing work on KV-cache eviction for hybrid-attention reasoning models</p>
</div>
<div class="ri-card ri-reason">
<div class="ri-head">
<span class="ri-icon"><i class="fa-solid fa-brain"></i></span>
<div>
<span class="ri-tag">Reasoning</span>
<h5 class="ri-title">Latent, Looped &amp; Search-Based Reasoning</h5>
</div>
</div>
<p class="ri-desc">How models reason beyond explicit chains of thought, through persistent latent states, recursion, and search, and how reasoning gains should be measured.</p>
<ul class="ri-chips">
<li>Latent &amp; looped reasoning</li>
<li>Agentic search</li>
<li>Code LMs &amp; test generation</li>
<li>RL with verifiable rewards</li>
<li>Reasoning for protein design</li>
</ul>
<p class="ri-related">Related: <a href="/publications/#li2026learning">Latent State Propagation</a> · <a href="https://github.com/larryinx/QRM">QRM</a> · <a href="/publications/#wu2026positionhiddencostsmeasurement">RLVR Position</a> · <a href="/publications/#wu2026proteor">Proteo-R1</a></p>
</div>
<div class="ri-card ri-arch">
<div class="ri-head">
<span class="ri-icon"><i class="fa-solid fa-layer-group"></i></span>
<div>
<span class="ri-tag">Architecture</span>
<h5 class="ri-title">LLM Architecture &amp; Mechanisms</h5>
</div>
</div>
<p class="ri-desc">Understanding model internals, from tokenization to hidden states, and exploring architectural changes with an eye to how they scale on existing inference infrastructure.</p>
<ul class="ri-chips">
<li>Tokenization</li>
<li>Hidden-state analysis</li>
<li>Quantized latent states</li>
<li>Looped LLMs</li>
<li>Hybrid-attention models</li>
</ul>
<p class="ri-related">Related: <a href="/publications/#li-etal-2026-tokdrift">TokDrift</a> · <a href="https://github.com/larryinx/QRM">QRM</a></p>
</div>
<div class="ri-card ri-agents">
<div class="ri-head">
<span class="ri-icon"><i class="fa-solid fa-robot"></i></span>
<div>
<span class="ri-tag">Agents</span>
<h5 class="ri-title">LLM Agents &amp; Test-Time Learning</h5>
</div>
</div>
<p class="ri-desc">Agents that learn from their own experience and operate real software, with an eye to what their learning and behavior cost to serve.</p>
<ul class="ri-chips">
<li>Self-evolving agents &amp; harnesses</li>
<li>Agent memory</li>
<li>Computer-use agents</li>
<li>Agents for scientific software</li>
<li>Agents for ML engineering</li>
</ul>
<p class="ri-related">Related: <a href="/publications/#dai2026osworldscience">OSWorld-Science</a> · <a href="/publications/#xuan2026learning">Learning from Use (survey)</a></p>
</div>
</div>

I am open to academic and research collaborations and welcome any questions or discussions.

