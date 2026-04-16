
<style>
  .wrap { max-width: 780px; margin: 0 auto; padding: 1.5rem 0; font-family: var(--font-sans); }
  .badge { display: inline-block; font-size: 11px; font-weight: 500; padding: 3px 10px; border-radius: 99px; letter-spacing: 0.04em; text-transform: uppercase; }
  .badge-blue { background: #E6F1FB; color: #0C447C; }
  .badge-teal { background: #E1F5EE; color: #085041; }
  .badge-purple { background: #EEEDFE; color: #3C3489; }
  .badge-coral { background: #FAECE7; color: #712B13; }
  .section-title { font-size: 11px; font-weight: 500; letter-spacing: 0.08em; text-transform: uppercase; color: var(--color-text-secondary); margin: 0 0 10px; }
  .card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1.1rem 1.25rem; margin-bottom: 10px; }
  .metric-row { display: grid; grid-template-columns: repeat(4, minmax(0,1fr)); gap: 10px; margin-bottom: 10px; }
  .metric { background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 0.85rem 1rem; }
  .metric-label { font-size: 11px; color: var(--color-text-secondary); margin: 0 0 4px; }
  .metric-value { font-size: 20px; font-weight: 500; color: var(--color-text-primary); margin: 0; }
  .divider { border: none; border-top: 0.5px solid var(--color-border-tertiary); margin: 1rem 0; }
  .skill-row { display: flex; flex-wrap: wrap; gap: 6px; }
  .q-item { display: flex; align-items: flex-start; gap: 10px; padding: 8px 0; border-bottom: 0.5px solid var(--color-border-tertiary); }
  .q-item:last-child { border-bottom: none; }
  .q-dot { width: 6px; height: 6px; border-radius: 50%; background: #378ADD; margin-top: 7px; flex-shrink: 0; }
  .q-text { font-size: 14px; color: var(--color-text-primary); line-height: 1.6; }
  .header-meta { display: flex; align-items: center; gap: 8px; flex-wrap: wrap; margin-bottom: 1.2rem; }
  h1 { font-size: 22px; font-weight: 500; color: var(--color-text-primary); margin: 0 0 8px; line-height: 1.3; }
  p { font-size: 14px; color: var(--color-text-primary); line-height: 1.75; margin: 0 0 10px; }
  p:last-child { margin-bottom: 0; }
  .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  @media (max-width: 560px) { .metric-row { grid-template-columns: 1fr 1fr; } .two-col { grid-template-columns: 1fr; } }
</style>

<div class="wrap">
  <h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)">Professional project summary for Tata Forage Data Visualisation project</h2>

  <div class="header-meta">
    <span class="badge badge-blue">Data Analytics</span>
    <span class="badge badge-teal">Business Intelligence</span>
    <span class="badge badge-purple">Executive Reporting</span>
    <span class="badge badge-coral">Tata / Forage</span>
  </div>

  <h1>Data Visualisation: Empowering Business with Effective Insights</h1>
  <p style="color:var(--color-text-secondary); font-size:13px; margin-bottom:1.4rem;">Virtual Experience Programme · Tata Consultancy Services × Forage · 2024</p>

  <div class="metric-row">
    <div class="metric"><p class="metric-label">Scope</p><p class="metric-value">End-to-End</p></div>
    <div class="metric"><p class="metric-label">Stakeholder</p><p class="metric-value">C-Suite</p></div>
    <div class="metric"><p class="metric-label">Markets Analysed</p><p class="metric-value">Top 10</p></div>
    <div class="metric"><p class="metric-label">Deliverable</p><p class="metric-value">Exec Dashboard</p></div>
  </div>

  <div class="card">
    <p class="section-title">Project Overview</p>
    <p>Designed and delivered an end-to-end business intelligence solution that transformed raw retail transaction data into executive-ready insights for senior leadership at a multinational retail organisation. The engagement simulated a real consulting scenario, requiring independent scoping, data validation, analytical design, and board-level visual communication — mirroring the full lifecycle of a client-facing BI engagement.</p>
  </div>

  <div class="two-col">
    <div class="card">
      <p class="section-title">Data Engineering & Preparation</p>
      <p>Conducted structured data quality validation on transactional records, applying business-logic filters to eliminate returns and erroneous pricing entries (negative quantities, non-positive unit prices). Engineered revenue metrics and restructured the dataset to support time-series, customer-level, and geographic analysis — ensuring analytical integrity before any insight generation.</p>
    </div>
    <div class="card">
      <p class="section-title">Analytical Framework</p>
      <p>Designed the analysis around four strategic business questions relevant to executive decision-making: revenue seasonality, international market performance, customer value concentration, and global demand distribution. Each analytical view was scoped to directly answer a leadership question rather than demonstrate technical output for its own sake.</p>
    </div>
  </div>

  <div class="card">
    <p class="section-title">Executive Dashboard & Insight Communication</p>
    <p>Produced a structured executive summary dashboard with each visual accompanied by a concise, action-oriented insight statement — translating data patterns into business language. The design prioritised scannability for time-pressed leadership, ensuring the dashboard functioned as a decision-support tool rather than a passive data display. This approach reflects industry best practice in stakeholder-facing BI delivery.</p>
  </div>

  <div class="card">
    <p class="section-title">Business questions addressed</p>
    <div class="q-item"><div class="q-dot"></div><div class="q-text">What is the monthly revenue trend across 2011, and where do seasonal demand peaks occur?</div></div>
    <div class="q-item"><div class="q-dot"></div><div class="q-text">Which are the top 10 international markets by revenue and quantity, excluding the United Kingdom?</div></div>
    <div class="q-item"><div class="q-dot"></div><div class="q-text">Who are the highest-value customers by revenue, and what does concentration risk look like at the top?</div></div>
    <div class="q-item"><div class="q-dot"></div><div class="q-text">Which global regions show the strongest demand signals and the greatest market expansion potential?</div></div>
  </div>

  <div class="card">
    <p class="section-title">Skills demonstrated</p>
    <div class="skill-row">
      <span class="badge badge-blue">Data Cleaning & Validation</span>
      <span class="badge badge-blue">Revenue Metric Engineering</span>
      <span class="badge badge-teal">Time-Series Analysis</span>
      <span class="badge badge-teal">Geographic Demand Analysis</span>
      <span class="badge badge-purple">Customer Segmentation</span>
      <span class="badge badge-purple">Executive Dashboard Design</span>
      <span class="badge badge-coral">Stakeholder Communication</span>
      <span class="badge badge-coral">Strategic Insight Framing</span>
    </div>
  </div>

  <div class="card" style="border-left: 2px solid #378ADD; border-radius: 0 var(--border-radius-lg) var(--border-radius-lg) 0;">
    <p class="section-title">Impact statement</p>
    <p>This project demonstrates the ability to independently scope, execute, and communicate a full BI engagement — from messy raw data to polished executive output. It reflects the core competency mix expected of a junior data analyst or BI developer in a consulting or corporate environment: analytical rigour, commercial awareness, and clear visual storytelling.</p>
  </div>
</div>
