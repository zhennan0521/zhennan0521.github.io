---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# About
I am Zhennan Shen. I received my B.E. in Computer Science and Technology from Shanghai Jiao Tong University in 2025. My research focuses on **language-model agents** and **agentic reinforcement learning** (especially on computer-use agents). I will join [HKUST](https://hkust.edu.hk/) as a Ph.D. student in Fall 2026, advised by [Prof. May Fung](https://mayrfung.github.io/).

I have worked closely with [Prof. Tao Yu](https://taoyds.github.io/) at [HKU NLP](https://hkunlp.github.io/) and with [Prof. Lu Chen](https://coai-sjtu.github.io/) and [Prof. Kai Yu](https://x-lance.github.io/kaiyu/) at the [X-LANCE Lab](https://x-lance.github.io/). In 2025, I interned at [Moonshot AI](https://www.moonshot.ai/) ([Kimi](https://www.kimi.com/en/)), contributing to the **[OKComputer](https://www.kimi.com/kimiplus/ok-computer)** and **[K2.5](https://www.kimi.com/blog/kimi-k2-5.html)** projects on large-scale agent training pipelines. I currently work at <span style="font-size: 1.1em; font-weight: bold;">**[JD.com](https://corporate.jd.com/)**</span> on the pretraining team, focusing on agent data synthesis and capability improvement.


**Contact:** 1641225799szn@gmail.com or ieee-szn@sjtu.edu.cn · [Google Scholar](https://scholar.google.com/citations?user=JPwg5MwAAAAJ) · [LinkedIn](https://www.linkedin.com/in/zhennan-shen-188a632b6) · [Resume]({{ "/ZhennanShen_Resume.pdf" | relative_url }})

<span class='anchor' id='research-interests'></span>
# Research Interests
- **(α) Agentic reinforcement learning** that strengthens reasonning, planning, and generalization for LLM-based agents.
- **(β) Human-aligned evaluation** frameworks and **scalable benchmarks** for LLM agents.
- **(γ) Scalable data synthesis pipelines** that mix supervised, reinforcement, and self-improvement signals for continual agent growth.

<u>I see reinforcement learning as the key to unlocking the full agentic potential of large language models.</u> To get there, we need **(α)** richer training paradigms that fuse supervised, reinforcement, and self-improvement signals; rigorous, **(β)** human-aligned evaluation suites to keep agents grounded; and **(γ)** scalable data pipelines that deliver the fuel these systems need to continually improve. Aligned with these agendas, I have worked on agentic foundation models ([OpenCUA](https://opencua.xlang.ai/)), agent data synthesis ([AgentTrek](https://agenttrek.github.io/)), agent evaluation ([OSWorld-Verified](https://xlang.ai/blog/osworld-verified)), and related initiatives.

<div align="center">
  <img src="{{ "/research_image.png" | relative_url }}" alt="Research directions diagram" width="600">
</div>

*High-level view of my research interest across agentic reinforcement learning(interaction), evaluation, and data synthesis.*


<span class='anchor' id='news'></span>
# News
- *2026.01* [Kimi K2.5](https://www.kimi.com/blog/kimi-k2-5.html) released as <span style="color:red;">the most powerful open-source visual agentic model</span>, featuring native multimodal intelligence and Agent Swarm.
- *2025.09* [OpenCUA](https://opencua.xlang.ai/) recognized with a <span style="color:red;">Spotlight at NeurIPS 2025</span>.
- *2025.07* [OSWorld-Verified](https://xlang.ai/blog/osworld-verified) launched  <span style="color:red;">verified OSWorld evaluation suite</span>, delivering more reliable infrastructure and task quality.
- *2025.03* Joined <a href="https://www.moonshot.ai/" style="color:red;">Moonshot AI</a> (<a href="https://www.kimi.com/en/" style="color:red;">Kimi</a>) to develop RL pipelines for advanced computer-use agents.
- *2025.01* [AgentTrek](https://agenttrek.github.io/) selected as a <span style="color:red;">Spotlight paper at ICLR 2025</span>.
- *2024.09* Completed research internship at HKU NLP Group working on large-scale agent data synthesis.

<span class='anchor' id='publications'></span>
# Publications & Preprints
- **[Kimi K2.5: Visual Agentic Intelligence.](https://arxiv.org/abs/2602.02276)** Kimi Team. *<span style="color: red;">arXiv 2026</span>.*
- **[AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials.](https://openreview.net/forum?id=EEgYUccwsV)** \* Yiheng Xu, \* Dunjie Lu, \* **Zhennan Shen (Co-Lead)**, Junli Wang, Zekun Wang, Yuchen Mao, Caiming Xiong, Tao Yu. *<span style="color: red;">ICLR 2025 (Spotlight)</span>.* 
- **[OpenCUA: Open Foundations for Computer-Use Agents.](https://opencua.xlang.ai/)** Xinyuan Wang, Bowen Wang, Dunjie Lu, Junlin Yang, Tianbao Xie, Junli Wang, Jiaqi Deng, Xiaole Guo, Yiheng Xu, Chen Henry Wu, **Zhennan Shen**, et al. *<span style="color: red;">NeurIPS 2025 (Spotlight)</span>.* 
- **[OSWorld-Verified: Reliable Evaluation for Computer-Use Agents.](https://xlang.ai/blog/osworld-verified)** Tianbao Xie, Mengqi Yuan, Danyang Zhang, Xinzhuang Xiong, **Zhennan Shen**, Zilong Zhou, Xinyuan Wang, Yanxu Chen, Jiaqi Deng, Junda Chen, Bowen Wang, Haoyuan Wu, Jixuan Chen, Junli Wang, Dunjie Lu, Hao Hu, Tao Yu. *<span style="color: red;">Follow-up to the original [OSWorld](https://os-world.github.io/) unveiled at NeurIPS 2024</span>.*
- **[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning.](https://arxiv.org/abs/2508.07871)** Yanshu Li, Jiangnan Wang, **Zhennan Shen**, Lihong Han, Haoyan Xu, Ruixiang Tang. <span style="color:red">*AAAI 2026 Oral*</span>. 
- **[SciEval: A Multi-Level Large Language Model Evaluation Benchmark for Scientific Research.](https://ojs.aaai.org/index.php/AAAI/article/view/29872/31521)** Sun Liangtai, Han Yang, Zhao Zihan, Ma Da, **Shen Zhennan**, Chen Baocai, Chen Lu, Yu Kai. <span style="color:red">*AAAI 2024.*</span> 
- **[SciDFM: A Large Language Model with Mixture-of-Experts for Science.](https://neurips.cc/virtual/2024/workshop/84714)** Sun Liangtai, Liu Danyu, Ma Da, Zhao Zihan, Chen Baocai, **Shen Zhennan**, Zhu Su, Chen Lu, Chen Xin, Yu Kai. <span style="color:red">*NeurIPS 2024 Workshop on FM4Science.*</span> 
- **[MobileEnv: Building Qualified Evaluation Benchmarks for LLM-GUI Interaction.](https://arxiv.org/abs/2305.08144)** Zhang Danyang, **Shen Zhennan**, Xie Rui, Zhang Situo, Xie Tianbao, Zhao Zihan, Chen Siyuan, Chen Li, Xu Hongshen, Cao Ruisheng, Yu Kai.

<span class='anchor' id='experience'></span>
# Experience

## Education
- *The Hong Kong University of Science and Technology (HKUST)*, Ph.D. Student, Fall 2026 (Expected), Hong Kong, China (Advisor: [Prof. May Fung](https://mayrfung.github.io/))
- *Shanghai Jiao Tong University*, B.E. in Computer Science and Engineering (Zhiyuan Honors Program), Sep 2021 – Jun 2025, Shanghai, China. GPA 3.9/4.3 (22/127). Outstanding Graduate; Zhiyuan Honors Scholarship (2021–2023).

## Research
- *[HKU NLP Group](https://hkunlp.github.io/)*, Research Intern, Jul 2024 – Sep 2024, Hong Kong, China (Advisor: [Prof. Tao Yu](https://taoyds.github.io/))  
  Built LLM-based GUI agent pipelines and large-scale data synthesis workflows; co-led AgentTrek and contributed to OpenCUA.
- *[X-LANCE Lab, SJTU](https://x-lance.github.io/)*, Research Intern, Jul 2023 – Jul 2024, Shanghai, China (Advisors: [Prof. Lu Chen](https://coai-sjtu.github.io/) & [Prof. Kai Yu](https://x-lance.github.io/kaiyu/))  
  Developed MobileEnv benchmark and scientific LLM agents including SciDFM and SciEval for AI4Science reasoning.

## Industry
- [JD.com](https://corporate.jd.com/), Pretraining Team, Dec 2025 – Present, Beijing, China  
  Agent data synthesis and capability improvement for large-scale pretraining.
- [Moonshot AI](https://www.moonshot.ai/) ([Kimi](https://www.kimi.com/en/)), Agent Training Intern, Mar 2025 – Dec 2025, Beijing, China  
  Contributed to the **[OKComputer](https://www.kimi.com/kimiplus/ok-computer)** and **[K2.5](https://www.kimi.com/blog/kimi-k2-5.html)** projects; designed RL workflows for GUI-centric computer-use agents; scaled SFT + RLHF data pipelines with quantitative and qualitative evaluation.

<span class='anchor' id='honors'></span>
# Honors & Awards
- Outstanding Graduate, Zhiyuan Honors Program (2025).
- Zhiyuan Honors Scholarship, Shanghai Jiao Tong University (2021–2024).
- University-Level Scholarship (2022，2023).

<span class='anchor' id='affiliations'></span>
# Affiliations

<div style="display: flex; flex-wrap: wrap; align-items: center; justify-content: center; gap: 30px; padding: 20px 0;">
  <a href="https://hkust.edu.hk/" target="_blank"><img src="{{ '/images/logos/hkust.svg' | relative_url }}" alt="HKUST" style="height: 80px;"></a>
  <a href="https://www.sjtu.edu.cn/" target="_blank"><img src="{{ '/images/logos/sjtu.png' | relative_url }}" alt="SJTU" style="height: 80px;"></a>
  <a href="https://www.hku.hk/" target="_blank"><img src="{{ '/images/logos/hku.jpg' | relative_url }}" alt="HKU" style="height: 80px;"></a>
  <a href="https://www.kimi.com/en/" target="_blank"><img src="{{ '/images/logos/kimi.png' | relative_url }}" alt="Moonshot AI / Kimi" style="height: 80px;"></a>
  <a href="https://corporate.jd.com/" target="_blank"><img src="{{ '/images/logos/JD.png' | relative_url }}" alt="JD.com" style="height: 80px;"></a>
</div>

