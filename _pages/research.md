---
layout: default
title: "Research"
description: "Research overview — heterogeneous catalysis, PDH, ODH, and ML-driven catalyst discovery."
permalink: /research/
---

<div class="site-wrapper">

  <div class="page-header">
    <div class="section-label">Research</div>
    <h1>Catalyst Discovery × Machine Learning</h1>
    <p>Heterogeneous catalysis for light alkane conversion, driven by interpretable AI and operando characterization.</p>
  </div>

  <!-- ── THEME 1 ──────────────────────────────────── -->
  <section class="section" style="border-top:none; padding-top:0">
    <div class="section-label">Theme 01</div>
    <h2>Propane Dehydrogenation (PDH)</h2>
    <div class="card">
      <p>
        Propane dehydrogenation is a critical on-purpose route to propylene — a key feedstock for polypropylene and other petrochemicals. My work targets <strong>Pt-based multimetallic catalysts</strong> (Pt–Sn, Pt–Ga, Pt–Fe, Pt–Cu, Pt–Ca on γ-Al₂O₃) with a focus on understanding how promoter identity and loading modulate the active site geometry, selectivity, and coke resistance.
      </p>
      <p>
        Experimental characterization includes <strong>CO pulse chemisorption</strong> for Pt dispersion, <strong>H₂-TPR / CO-TPD / CO₂-TPD</strong> for surface acid-base characterization, <strong>Raman spectroscopy</strong> for coke quantification (D/G band analysis), and <strong>XPS</strong> for oxidation state fingerprinting. In-situ and operando <strong>X-ray Absorption Spectroscopy (XAS)</strong> — including Modulation Excitation XAS (ME-XAS) with Phase-Sensitive Detection — is used to probe dynamic structural changes under reaction conditions at Pt L₃-edge.
      </p>
      <p>
        On the data side, I have curated a descriptor-rich experimental dataset (particle size from XRD-derived RDFs, electronegativity, cohesive energy, Raman peak ratios) and trained ensemble ML models (Random Forest, LightGBM, XGBoost) with SHAP-based interpretability to rank feature importance across >30 descriptors.
      </p>
      <div>
        <span class="research-tag">Pt/Al₂O₃</span>
        <span class="research-tag">Multimetallic</span>
        <span class="research-tag">XAS / EXAFS</span>
        <span class="research-tag">ME-XAS</span>
        <span class="research-tag">CO chemisorption</span>
        <span class="research-tag">Raman</span>
        <span class="research-tag">XPS</span>
      </div>
    </div>
  </section>

  <!-- ── THEME 2 ──────────────────────────────────── -->
  <section class="section">
    <div class="section-label">Theme 02</div>
    <h2>Bayesian Optimization & ML-Driven Catalyst Discovery</h2>
    <div class="card">
      <p>
        Combinatorial catalyst spaces for multimetallic PDH systems easily exceed one million formulations when varying metal identity, loading, and support. Exhaustive experimental screening is infeasible. I have built a fully automated <strong>Bayesian Optimization</strong> pipeline that couples a surrogate model (Gaussian Process) with an acquisition function (Expected Improvement) to intelligently navigate this space, achieving high-performing formulations in far fewer iterations than random or grid search.
      </p>
      <p>
        The ML stack includes: <code>scikit-learn</code>, <code>LightGBM</code>, <code>XGBoost</code>, <code>SHAP</code>, and custom Python tooling for descriptor engineering from raw characterization data (Raman, XRD peak fitting, chemisorption). Interpretability is central — not just prediction performance — because understanding <em>why</em> a catalyst works is as important as finding one that does.
      </p>
      <div>
        <span class="research-tag">Bayesian Optimization</span>
        <span class="research-tag">Gaussian Process</span>
        <span class="research-tag">SHAP</span>
        <span class="research-tag">LightGBM</span>
        <span class="research-tag">Feature engineering</span>
        <span class="research-tag">Python</span>
      </div>
    </div>
  </section>

  <!-- ── THEME 3 ──────────────────────────────────── -->
  <section class="section">
    <div class="section-label">Theme 03</div>
    <h2>Oxidative Dehydrogenation (ODH) of Light Alkanes</h2>
    <div class="card">
      <p>
        ODH offers thermodynamic advantages over non-oxidative PDH by overcoming equilibrium limitations. I work with <strong>vanadium-based catalysts</strong> (V–Mo–Zr–Ti/Al₂O₃) for ODH of propane and ethane, systematically varying metal oxide composition and calcination conditions.
      </p>
      <p>
        Characterization focuses on surface redox properties (H₂-TPR, CO-TPD, CO₂-TPD), morphology (SEM-EDX, BET), and thermal stability (TGA-MS). Kinetic modeling is used to extract apparent activation energies and reaction orders, and to compare Mars–van Krevelen vs Langmuir–Hinshelwood mechanistic frameworks.
      </p>
      <div>
        <span class="research-tag">Vanadium oxide</span>
        <span class="research-tag">ODH</span>
        <span class="research-tag">TPD / TPR</span>
        <span class="research-tag">BET</span>
        <span class="research-tag">Kinetic modeling</span>
      </div>
    </div>
  </section>

  <!-- ── THEME 4 ──────────────────────────────────── -->
  <section class="section">
    <div class="section-label">Theme 04 — Published Review</div>
    <h2>CO₂ Hydrogenation to Methanol</h2>
    <div class="card">
      <p>
        My M.Tech research culminated in a comprehensive review (published in <em>Coordination Chemistry Reviews</em>, 2023) covering Cu-based and emerging non-Cu catalytic systems for CO₂ → methanol. The review systematically analyzes structure–activity relationships, promoter effects, support interactions, and proposed mechanistic pathways (formate vs. RWGS+CO hydrogenation routes).
      </p>
      <p>
        I also completed a <strong>MITACS Globalink internship</strong> at a Canadian university, where I synthesized lignin-derived catalysts to enable CO₂ as a co-monomer for bio-based polymer production — a direct application of CO₂ utilization chemistry.
      </p>
      <div>
        <span class="research-tag">CO₂ utilization</span>
        <span class="research-tag">Methanol synthesis</span>
        <span class="research-tag">Cu catalysts</span>
        <span class="research-tag">CCR 2023</span>
        <span class="research-tag">MITACS intern</span>
      </div>
    </div>
  </section>

  <!-- ── PROSPECTIVE ───────────────────────────────── -->
  <section class="section">
    <div class="section-label">Looking Forward</div>
    <h2>Prospective work</h2>
    <div class="terminal">
      <div class="terminal-bar">
        <div class="terminal-dot r"></div>
        <div class="terminal-dot y"></div>
        <div class="terminal-dot g"></div>
        <span class="terminal-filename">future_directions.md</span>
      </div>
      <div class="terminal-body">
        <span class="cmt">## Near-term</span><br>
        <span class="cmd">→</span> Integrate high-throughput XAS with automated Bayesian feedback loops<br>
        <span class="cmd">→</span> Extend ME-XAS PSD framework to in-situ Raman for coke characterization<br>
        <span class="cmd">→</span> Scale ML-guided PDH formulations to pilot-level reactor validation<br>
        <br>
        <span class="cmt">## Longer-term</span><br>
        <span class="cmd">→</span> Autonomous catalyst synthesis + testing using robotics integration<br>
        <span class="cmd">→</span> Foundation models for heterogeneous catalysis (structure → activity)<br>
        <span class="cmd">→</span> Sustainable light alkane valorization at industrial scale
      </div>
    </div>
  </section>

</div>
