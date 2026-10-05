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

Welcome to **Rui Chen**'s academic homepage!

I am a medicinal chemist working at the interface of **synthesis, structure-based design, and developability**. I currently work as a medicinal chemist at [Aidea Pharma](https://aidea.com.cn/) in Jiangsu, China, where for the past three years I have worked on HIV antiviral discovery and process development — from analogue design and multistep synthesis through crystal-form control and scale-up.

I hold an M.Sc. in Pharmacy from [China Pharmaceutical University](https://www.cpu.edu.cn/) (GPA 88.54/100, Top 10%), where I worked in the laboratory of Prof. Zhiyu Li and Prof. Jinlei Bian on targeted protein degradation, transporter inhibitors and kinase inhibitors.

**I am currently applying for PhD entry in 2027**, with a focus on **induced-proximity chemistry and targeted protein degradation**, **antiviral medicinal chemistry**, and **computational (CADD/AIDD-assisted) molecular design**. Technical notes on the tools I build and use are on [rechain-cr.github.io](https://rechain-cr.github.io).

If you are interested in any form of academic collaboration or would like to discuss a doctoral position, please feel free to email me at _chenrui.cpu@gmail.com_.

If you want to know more about me, here is my [CV](/CV.pdf) and my [Research Statement](/ResearchStatement.pdf).

<span class='anchor' id='research-interests'></span>
# 🔬 Research Interests

- **Induced proximity & targeted protein degradation** — linker and degrader construction, ternary-complex geometry, cooperativity, and E3 ligases beyond CRBN and VHL.
- **Antiviral medicinal chemistry & developability** — metabolic-stability and half-life optimization, solubility rescue, crystal-form identification, chiral-intermediate process development.
- **Computational design & ADMET judgment** — using predictive models to prioritize synthesis rather than replace chemical judgment.

<span class='anchor' id='News'></span>
# 🔥 News

- *2025.11*: &nbsp;🎉 Bronze Award, **AI for Science Track**, 2nd Global Digital-Intelligence Education Innovation Competition (Peking University). Team lead; designed the automated synthesis workflow and delivered the project presentation.
- *2024.10*: &nbsp;🎉 Our work on CLK2 inhibitors for non-small cell lung cancer was published in *Eur. J. Med. Chem.* (co-first author, ranked 3rd of six).
- *2023.07*: &nbsp;🎉 Joined Jiangsu Aidea Pharmaceutical as a medicinal chemist, working on HIV antiviral discovery and process development.
- *2023.06*: &nbsp;🎉 Graduated from China Pharmaceutical University with an M.Sc. in Pharmacy (GPA 88.54/100, Top 10%).

<span class='anchor' id='Publications'></span>
# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Li Lab 2023</div><img src='images/ASCT2-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Identification of a Novel ASCT2 (SLC1A5) Inhibitor by Dynamic Pharmacophore-Based Virtual Screening (Manuscript in preparation)

**Rui Chen**, Jiali Huang, Yumeng Chen, Lian Qin, Haoming Chen, Yuxiao Wang, Dongmei Huang, Zhiyu Li, Ahmed R. Ali, Jinlei Bian

**Highlights**
- Discovery of novel scaffold ASCT2 lead compounds through virtual screening and activity assaying workflows

- Virtual screening workflows such as molecular dynamics simulations, molecular docking, and pharmacophore screening

- Based on the lead compounds, studied the drug-target conformational relationship, combined with the protein crystal structure, through molecular docking and MD simulation, designed and synthesized 31 novel inhibitors

- By screening for enzyme and cellular activity, obtained inhibitors with tumor cell inhibitory activity superior to positive drug V9302 in the same proliferation assay (IC₅₀ = 0.39 µM)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Li Lab 2023</div><img src='images/CLK2-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Discovery of CLKs Inhibitors for the Treatment of Non-small Cell Lung Cancer. _Eur. J. Med. Chem._ 2024, 280, 116952.](https://www.sciencedirect.com/science/article/abs/pii/S022352342400833X)

Tianxing Hu¹, Jiangli Huang¹, **Rui Chen**¹, Hui Zhang¹, Mai Liu¹, Ran Wang¹, Wenyi Zhou¹, Dongmei Huang, Mengmeng Cao, Depeng Li, Zhiyu Li, Hongxi Wu, Jinlei Bian (Co-first author, ranked 3rd of six)

**Highlights**
- Design and synthesis of novel CLK2 inhibitors

- LBM22 has significant antiproliferative activity in H1299 cells

- LBM22 can dose-dependently inhibit SR protein phosphorylation

- LBM22 down-regulates the expression of Wnt-related proteins and anti-apoptotic proteins

- CLK2 inhibitors show promise for the treatment of NSCLC
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Li Lab 2023</div><img src='images/DNA-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DNA Framework-Engineered Chimeras Platform Enables Selectively Targeted Protein Degradation. _Nat. Commun._ 2023, 14 (1), 4510.](https://www.nature.com/articles/s41467-023-40244-7)

Li Zhou, Bin Yu, Mengqiu Gao, **Rui Chen**, Zhiyu Li, Yueqing Gu, Jinlei Bian, Yi Ma

**Highlights**
- This paper developed a novel covalent DNA framework-based PROTACs (DbTACs), which can be used for a variety of different ligands and targets
  
- The programmability of the DNA framework allows precise control of the spatial distance between the degradation target protein (POI) and the E3 ligase ligand
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Li Lab 2023</div><img src='images/CDK9-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Discovery of Selective and Potent Macrocyclic CDK9 Inhibitors for the Treatment of Osimertinib-Resistant Non-Small-Cell Lung Cancer. _J. Med. Chem._ 2023, 66 (22), 15340–15361.](https://pubs.acs.org/doi/10.1021/acs.jmedchem.3c01400)

Tizhi Wu, Bin Yu, Yifan Xu, Zekun Du, Zhiming Zhang, Yuxiao Wang, Haoming Chen, Li′ao Zhang, **Rui Chen**, Feihai Ma, Weihong Gong, Sixian Yu, Zhixia Qiu, Hongxi Wu, Xi Xu, Jubo Wang, Zhiyu Li, Jinlei Bian

**Highlights**
- Developed a novel macrocyclic CDK9 inhibitor for ositinib-resistant non-small cell lung cancer (NSCLC)

- A series of CDK9 inhibitors were designed by macrocyclization strategy based on protein structure analysis

- The dominant compounds were highly kinase-selective and also exhibited significant antitumor activity against oxitinib-resistant strains
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Li Lab 2023</div><img src='images/CDK9-patent-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Patent Review of Selective CDK9 Inhibitors in Treating Cancer. _Expert Opin. Ther. Pat._ 2023, 33 (4), 309–322.](https://www.tandfonline.com/doi/full/10.1080/13543776.2023.2208747)

Tizhi Wu, Xiaowei Wu, Yifan Xu, **Rui Chen**, Jubo Wang, Zhiyu Li, Jinlei Bian

**Highlights**
- This review focuses on the development of selective CDK9 inhibitors reported in patent publications during the period 2020-2022

- Contributed molecular docking and prepared the docking figures for this review
  
- Selective targeting of CDK9 is considered an effective strategy for antitumor drug development
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Li Lab 2023</div><img src='images/Glu-patent-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Updated Patent Review of Glutaminase Inhibitors (2019-2022). _Expert Opin. Ther. Pat._ 2023, 33 (1), 17–28.](https://www.tandfonline.com/doi/full/10.1080/13543776.2023.2173573)

Danni Wang, Xiaohong Li, Guangyue Gong, Yulong Lu, Ziming Guo, **Rui Chen**, Huidan Huang, Zhiyu Li, Jinlei Bian

**Highlights**
- This review covers recent patents (2019-present) involving GLS1 inhibitors, which are mostly focused on their chemical structures, molecular mechanisms of action, pharmacokinetic properties, and potential clinical applications

- Mentored two undergraduates through the full review-writing process — literature and patent searching, critical reading, and manuscript structure
  
- Selective targeting of GLS1 is considered an effective strategy for antitumor drug development
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Li Lab 2022</div><img src='images/SARMs-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Overview of the Development of Selective Androgen Receptor Modulators (SARMs) as Pharmacological Treatment for Osteoporosis (1998-2021). _Eur. J. Med. Chem._ 2022, 230, 114119.](https://www.sciencedirect.com/science/article/abs/pii/S0223523422000216?via%3Dihub)

Youquan Xie, Yucheng Tian, Yuming Zhang, Zhisheng Zhang, **Rui Chen**, Mian Li, Jiawei Tang, Jinlei Bian, Zhiyu Li, Xi Xu

**Highlights**
- Summary of chemical scaffolds and corresponding SAR of SARMs as pharmacological treatment for osteoporosis from 1998 to 2021.
  
- Insight into advances and possible mechanisms of the potential toxicity, side effects, the abuse, and future perspectives of SARMs.
</div>
</div>

<span class='anchor' id='patents'></span>
# 💡 Patents

- *2026* &nbsp; Two Chinese invention patent applications on processes for the preparation of an optically active intermediate of a polycyclic carbamoyl pyridone derivative: **(I)** an asymmetric route; **(II)** a route avoiding hazardous reagents. Drafted and finalized with IP counsel; filing pending.

<span class='anchor' id='honors'></span>
# 🎖️ Honors and Awards 
- *11/2025*  **Bronze Award**, AI for Science Track, 2nd Global Digital-Intelligence Education Innovation Competition (Peking University)
  <img src='images/AI_for_science-cert.jpg' alt="AI for Science competition certificate" width="45%">

- *10/2022*  The Second Prize, CPU Scholarship 

- *10/2021*  The Second Prize, CPU Scholarship 

- *12/2020*  The First Prize, CPU Freshman Graduate Student (Top 5%)

- *06/2020*  Shandong Province Outstanding Undergraduate Student Award (Top 1%) 

- *12/2019*  The First Prize, SDUTCM Scholarship 

- *09/2019*  Provincial Team Silver Award, "Internet+" Innovation and Entrepreneurship Competition 

- *12/2018*  The First Prize, SDUTCM Scholarship 

- *12/2018*  SDUTCM Excellent Student 

- *12/2018*  SDUTCM Excellent Student Cadre 

- *11/2017*  Outstanding Work, Communist Youth League of China Social Practice Competition

- *10/2017*  Volunteer Activities for the Country People Excellent Student 

<span class='anchor' id='Educations'></span>
# 📖 Educations
- *2020.09 - 2023.06*, Master, [School of Pharmacy](https://yxy.cpu.edu.cn/enyxy/) , [China Pharmaceutical University](https://www.cpu.edu.cn/) .

  M.S. in Pharmacy (GPA: 88.54/100.00, Top 10%, Ranked 8/81)

  I studied in the Zhiyu Li lab, which is a big friendly family, and my mentors are [Zhiyu Li](https://yxy.cpu.edu.cn/a4/4e/c11941a173134/page.htm) and [Jinlei Bian](https://yxy.cpu.edu.cn/f2/6d/c11941a193133/page.htm).
  

- *2016.09 - 2020.06*, Undergraduate, [School of Pharmacy](https://sps.sdutcm.edu.cn/) , [Shandong University of Traditional Chinese Medicine](https://www.sdutcm.edu.cn/) .

  B.Sc. in Pharmaceutical Engineering (GPA: 82.48/100.00, Top 3%, Ranked 7/247)

  Guaranteed recommendation for postgraduate studies.

- *2013.09 - 2016.06*, Shandong Taian No.1 Senior High School, Taian

<span class='anchor' id='Research_experience'></span>
# 👨‍🔬 Research Experience

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023 - Present</div><img src='images/aidea-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2023.07 - Present** | *Jiangsu Aidea Pharmaceutical Co., Ltd. — Medicinal Chemist*

**Focus:** HIV antivirals and process chemistry — discovery, analogue design and scale-up

**Projects**
- **Process chemistry for a chiral intermediate** — Developed two alternative synthetic routes to an optically active intermediate of a polycyclic carbamoyl pyridone derivative, targeting lower cost, simpler chiral resolution, and reduced reliance on hazardous reagents. Redesigned the chiral resolution step, improving isolation efficiency and eliminating a chromatography-dependent operation not scalable in manufacturing. Authored two patent applications on the two routes.

- **HIV-1 integrase inhibitor analogue series (ACC017 follow-up)** — Synthesized and characterized an analogue series built on the clinical-stage integrase inhibitor ACC017, targeting improved metabolic stability, oral bioavailability and half-life. Contributed to resolving an aqueous-solubility liability and to identifying a developable crystal form for scale-up.

- **Long-acting injectable prodrug platform** — Designed and synthesized high-molecular-weight prodrug candidates (MW > 1500) to extend the dosing interval and improve bioavailability, and built the multistep routes to these complex conjugates.

- **Novel HIV-1 capsid inhibitor — structure-based design** — Designed novel capsid inhibitors using molecular dynamics simulation and docking; synthesized complex polycyclic candidates requiring multistep chiral routes, and evaluated their biological activity.

- **ACC007 — production process improvement** — Redesigned the synthetic route to reduce production cost and cut operational waste at scale.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022-2023</div><img src='images/ASCT2-2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2022-2023** | *M.Sc. thesis project — Project Leader*

**Projects**
- ASCT2 subject refinement and completion of molecular dynamics modeling of ASCT2-related proteins and compounds

- Completion of work related to the modification, design and synthesis of target compounds

- Writing and defending a thesis
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022-2023</div><img src='images/CLK2-2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2022-2023** | *CLK2 inhibitor program*

**Projects**
- Discovery of novel CLK2 inhibitors based on structure‐based drug design

- Enhanced water solubility and formulation properties of the lead compound

- Improved antiproliferative activity against H1299 cells

- Co-first author, published in *Eur. J. Med. Chem.* (2024)
  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022-2023</div><img src='images/studyCADD-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2022-2023** | *Computational (CADD) support across the group*

**Projects**
- Help labs purchase and build high-performance computer hardware and build CADD workstations

- Completed molecular docking and molecular dynamics simulation calculations and mapping in several topics

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022-2023</div><img src='images/LAT-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2022-2023** | *LAT1 inhibitor program*

**Projects**
- Supervise undergraduate experiments and assist in the advancement of LAT1 target projects involving undergraduate students

- Assist undergraduate students with review writing

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021-2022</div><img src='images/JAK-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2021-2022** | *JAK inhibitor process development*

**Projects**
- Participated in the process optimization process of the new JAK inhibitor, optimized some process parameters and improved the overall yield

- Improved recrystallization parameters for compound intermediates resulted in rapid synthesis of kilogram-sized products

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021-2022</div><img src='images/studyCADD-2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2021-2022** | *Self-directed CADD training*

**Projects**
- Learning the molecular docking process on your own, exploring the application of molecular docking in drug design, and outputting results using software such as Pymol

- Self-study kinetic simulation tutorials to master drug molecule interactions in proteins and guide drug design efforts

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021-2022</div><img src='images/DNA-2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2021-2022** | *DNA framework-engineered chimeras (DbTACs)*

**Projects**
- Participated in the synthesis and design of warhead compounds for DbTACs and screened several linkage chains of different lengths

- Complete protein-DNA docking in DbTACs to generate and optimize images for experiments

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021-2022</div><img src='images/DON-1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2021-2022** | *DON prodrug design*

**Projects**
- Participated in the design and synthesis of a series of DON prodrugs.

- Improved the original toxic effects of DON through the design of the prodrug, and improved the plasma stability and tolerability of DON

</div>
</div>

<span class='anchor' id='skills'></span>
# 🛠️ Technical Skills

- **CADD & AIDD:** structure-based design from virtual screening and MD through to synthesis (Schrödinger, MOE, Discovery Studio, AutoDock, GROMACS, PyMOL); completed a full design–synthesis–assay cycle against ASCT2 (31 compounds).

- **AI & data:** apply LLM-based tools to literature mining, patent analysis and AI-assisted design; use AI for SAR reasoning, ADMET triage and docking/MD interpretation. Built a laboratory ELN and a literature-management tool (see [rechain-cr.github.io](https://rechain-cr.github.io)).

- **Experimental:** independently design experiments and deliver target compounds, including complex polycyclic and chiral targets; TLC, recrystallization, column chromatography, and structure elucidation by ¹H NMR, MS and HPLC.

- **Software:** Office, Zotero, Adobe Illustrator, GraphPad, ChemDraw, MestReNova.

- **Language:** Chinese Mandarin (Level II, Grade A); English: IELTS 6.5 (no band below 6.0).

<span class='anchor' id='Extracurricular_activity'></span>
# 💻 Extracurricular Activity

- *2025*, Team lead, AI for Science Track, 2nd Global Digital-Intelligence Education Innovation Competition (Peking University) — led a four-person team building an AI-assisted automated synthesis workflow.

  <img src='images/AI_for_science-team.jpg' alt="AI for Science competition — team in the laboratory" width="70%">

- *2022 - 2023*, Hosted and managed the innovation and entrepreneurship training program for university students

- *2016 - 2020*, Class monitor during the university
