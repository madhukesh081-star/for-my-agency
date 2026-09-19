<!DOCTYPE html>
<html lang="en" data-theme="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MadhuKesh | Modern Growth & Brand Studio</title>
  <meta name="description" content="MadhuKesh builds thoughtful digital growth experiences with strategy, design, and performance-focused execution.">
  <link rel="icon" type="image/png" href="assets/madhukesh-logo.png">

  <!-- Google Fonts: Plus Jakarta Sans & Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Plus+Jakarta+Sans:wght@500;600;700;800&display=swap" rel="stylesheet">

  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>

  <!-- Stylesheets -->
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/animations.css">
</head>
<body>

  <!-- Custom Magnetic Cursor -->
  <div class="cursor-dot"></div>
  <div class="cursor-outline"></div>

  <!-- Header & Sticky Navigation -->
  <header class="header">
    <div class="container nav-container">
      <a href="#" class="brand">
        <img src="assets/madhukesh-logo.png" alt="MadhuKesh logo" class="brand-logo">
        <span class="brand-name">MadhuKesh</span>
      </a>

      <ul class="nav-menu">
        <li><a href="#services" class="nav-link">Services</a></li>
        <li><a href="#calculator" class="nav-link">ROI Calculator</a></li>
        <li><a href="#work" class="nav-link">Case Studies</a></li>
        <li><a href="#process" class="nav-link">Process</a></li>
        <li><a href="#pricing" class="nav-link">Pricing</a></li>
        <li><a href="#faq" class="nav-link">FAQ</a></li>
      </ul>

      <div class="nav-actions">
        <!-- Interactive Sound Toggle -->
        <button class="btn-icon" id="sound-toggle" title="Toggle UI Sound Effects" aria-label="Toggle Sound">
          <i data-lucide="volume-x"></i>
        </button>

        <!-- Theme Toggle -->
        <button class="btn-icon" id="theme-toggle" title="Toggle Theme" aria-label="Toggle Dark/Light Mode">
          <i data-lucide="sun"></i>
        </button>

        <!-- CTA Button -->
        <a href="#contact" class="btn btn-primary">
          <span>Book Strategy Call</span>
          <i data-lucide="arrow-right" style="width:18px; height:18px;"></i>
        </a>

        <!-- Mobile Hamburger Toggle -->
        <div class="hamburger" id="hamburger-btn" aria-label="Open Navigation Menu">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
    </div>
  </header>

  <!-- Mobile Navigation Drawer -->
  <div class="mobile-nav-drawer" id="mobile-drawer">
    <ul class="mobile-nav-links">
      <li><a href="#services" class="mobile-nav-link">Services</a></li>
      <li><a href="#calculator" class="mobile-nav-link">ROI Calculator</a></li>
      <li><a href="#work" class="mobile-nav-link">Case Studies</a></li>
      <li><a href="#process" class="mobile-nav-link">Process</a></li>
      <li><a href="#pricing" class="mobile-nav-link">Pricing</a></li>
      <li><a href="#faq" class="mobile-nav-link">FAQ</a></li>
      <li><a href="#contact" class="mobile-nav-link gradient-text">Book Strategy Call</a></li>
    </ul>
    <div style="font-size:0.85rem; color:var(--text-muted);">
      © <span id="mobile-year">2026</span> MadhuKesh.
    </div>
  </div>

  <!-- Hero Section with Interactive Constellation Canvas -->
  <section class="hero" id="home">
    <canvas id="hero-canvas"></canvas>

    <div class="container hero-content">
      <div class="hero-badge float-effect">
        <span class="pulse-dot"></span>
        <span>TOP 1% GLOBAL GROWTH AGENCY 2026</span>
      </div>

      <h1 class="hero-title reveal-init">
        We Scale High-Growth Brands With <span class="gradient-text animated-gradient">Precision Marketing</span> &amp; AI Velocity.
      </h1>

      <p class="hero-subtitle reveal-init delay-100">
        Stop lighting ad spend on fire. We fuse algorithmic paid media, conversion rate optimization, and thumb-stopping creative to drive predictable 8-figure revenue.
      </p>

      <div class="hero-actions reveal-init delay-200">
        <a href="#contact" class="btn btn-primary">
          <span>Get Free Growth Audit</span>
          <i data-lucide="sparkles" style="width:18px; height:18px;"></i>
        </a>
        <a href="#work" class="btn btn-secondary">
          <span>View Proven Results</span>
          <i data-lucide="trending-up" style="width:18px; height:18px;"></i>
        </a>
      </div>

      <!-- Live Metric Highlights -->
      <div class="hero-stats-grid reveal-init delay-300">
        <div class="hero-stat-card">
          <div class="stat-number gradient-text" data-counter-target="85" data-counter-prefix="+₹" data-counter-suffix="M">+₹85M</div>
          <div class="stat-label">Client Revenue Generated</div>
        </div>
        <div class="hero-stat-card">
          <div class="stat-number gradient-text-cyan" data-counter-target="4.3" data-counter-suffix="x">4.3x</div>
          <div class="stat-label">Average Campaign ROAS</div>
        </div>
        <div class="hero-stat-card">
          <div class="stat-number gradient-text" data-counter-target="140" data-counter-suffix="+">140+</div>
          <div class="stat-label">Fast-Scaling Brands Scaled</div>
        </div>
      </div>
    </div>
  </section>

  <!-- Infinite Partner Logo Marquee -->
  <div class="marquee-wrapper">
    <div class="marquee-heading">TRUSTED BY FAST-GROWING FOUNDERS &amp; VENTURE-BACKED ENTERPRISES</div>
    <div class="marquee-track">
      <div class="marquee-item"><i data-lucide="shield-check"></i> HYPERFLOW AI</div>
      <div class="marquee-item"><i data-lucide="gem"></i> AURA APPAREL</div>
      <div class="marquee-item"><i data-lucide="cpu"></i> VELOX PAYMENTS</div>
      <div class="marquee-item"><i data-lucide="activity"></i> NEXUS HEALTH</div>
      <div class="marquee-item"><i data-lucide="globe"></i> LUMINARY SaaS</div>
      <div class="marquee-item"><i data-lucide="box"></i> PRISM COMMERCE</div>
      <div class="marquee-item"><i data-lucide="compass"></i> SKYLINE VENTURES</div>
      <div class="marquee-item"><i data-lucide="zap"></i> ZENITH ROBOTICS</div>
      <!-- Duplicate for seamless loop -->
      <div class="marquee-item"><i data-lucide="shield-check"></i> HYPERFLOW AI</div>
      <div class="marquee-item"><i data-lucide="gem"></i> AURA APPAREL</div>
      <div class="marquee-item"><i data-lucide="cpu"></i> VELOX PAYMENTS</div>
      <div class="marquee-item"><i data-lucide="activity"></i> NEXUS HEALTH</div>
      <div class="marquee-item"><i data-lucide="globe"></i> LUMINARY SaaS</div>
      <div class="marquee-item"><i data-lucide="box"></i> PRISM COMMERCE</div>
      <div class="marquee-item"><i data-lucide="compass"></i> SKYLINE VENTURES</div>
      <div class="marquee-item"><i data-lucide="zap"></i> ZENITH ROBOTICS</div>
    </div>
  </div>

  <!-- Services Bento Grid -->
  <section class="section" id="services">
    <div class="container">
      <div class="section-header reveal-init">
        <div class="section-tag">
          <i data-lucide="layers" style="width:16px; height:16px;"></i>
          OUR CAPABILITIES
        </div>
        <h2 class="section-title">Engineered For <span class="gradient-text">Aggressive Growth</span></h2>
        <p class="section-desc">
          We do not offer generic marketing checklists. We deploy integrated growth engines designed to capture market share and maximize valuation.
        </p>
      </div>

      <div class="services-grid">
        <!-- Service 1: Paid Ads (Featured 2-column) -->
        <div class="service-card featured tilt-card reveal-init">
          <div class="tilt-child">
            <div class="service-icon-box">
              <i data-lucide="target"></i>
            </div>
            <h3 class="service-title">Performance Paid Ads (Meta, Google, TikTok, LinkedIn)</h3>
            <p class="service-desc">
              Algorithmic media buying that captures high-intent demand and scales customer acquisition profitably. We deploy proprietary bidding models and first-party CAPI data tracking.
            </p>
            <ul class="service-features">
              <li><i data-lucide="check-circle-2"></i> Custom First-Party Tracking &amp; Conversion API setup</li>
              <li><i data-lucide="check-circle-2"></i> Weekly iterative creative testing with 15+ new hooks</li>
              <li><i data-lucide="check-circle-2"></i> Full-funnel retargeting &amp; dynamic product ads</li>
            </ul>
            <div class="service-card-footer">
              <a href="#" class="link-arrow" data-modal-trigger="perf-marketing">
                <span>View Full Framework</span>
                <i data-lucide="chevron-right" style="width:16px; height:16px;"></i>
              </a>
            </div>
          </div>
        </div>

        <!-- Service 2: AI SEO -->
        <div class="service-card tilt-card reveal-init delay-100">
          <div class="tilt-child">
            <div class="service-icon-box">
              <i data-lucide="search"></i>
            </div>
            <h3 class="service-title">AI Search &amp; Organic Dominance</h3>
            <p class="service-desc">
              Rank in traditional Google Search and be recommended by LLMs (Gemini, ChatGPT Search, Perplexity).
            </p>
            <ul class="service-features">
              <li><i data-lucide="check-circle-2"></i> Generative AI citation strategy</li>
              <li><i data-lucide="check-circle-2"></i> High-intent programmatic SEO content</li>
            </ul>
            <div class="service-card-footer">
              <a href="#" class="link-arrow" data-modal-trigger="ai-seo">
                <span>Explore Method</span>
                <i data-lucide="chevron-right" style="width:16px; height:16px;"></i>
              </a>
            </div>
          </div>
        </div>

        <!-- Service 3: CRO -->
        <div class="service-card tilt-card reveal-init delay-200">
          <div class="tilt-child">
            <div class="service-icon-box">
              <i data-lucide="mouse-pointer-click"></i>
            </div>
            <h3 class="service-title">Conversion Rate Optimization (CRO)</h3>
            <p class="service-desc">
              Double your revenue without increasing ad spend. We engineer scientific A/B split-tests and high-converting landing funnels.
            </p>
            <ul class="service-features">
              <li><i data-lucide="check-circle-2"></i> Heatmap &amp; behavioral drop-off audits</li>
              <li><i data-lucide="check-circle-2"></i> Frictionless checkout architectures</li>
            </ul>
            <div class="service-card-footer">
              <a href="#" class="link-arrow" data-modal-trigger="cro">
                <span>View Strategy</span>
                <i data-lucide="chevron-right" style="width:16px; height:16px;"></i>
              </a>
            </div>
          </div>
        </div>

        <!-- Service 4: Creative & Video -->
        <div class="service-card tilt-card reveal-init delay-100">
          <div class="tilt-child">
            <div class="service-icon-box">
              <i data-lucide="video"></i>
            </div>
            <h3 class="service-title">High-Velocity Creative &amp; Video</h3>
            <p class="service-desc">
              Thumb-stopping UGC, 3D motion graphics, and psychological hook scripts that turn passive scrollers into paying customers.
            </p>
            <ul class="service-features">
              <li><i data-lucide="check-circle-2"></i> High-converting creator network</li>
              <li><i data-lucide="check-circle-2"></i> Rapid creative fatigue counter-testing</li>
            </ul>
            <div class="service-card-footer">
              <a href="#" class="link-arrow" data-modal-trigger="creative-production">
                <span>View Creative Lab</span>
                <i data-lucide="chevron-right" style="width:16px; height:16px;"></i>
              </a>
            </div>
          </div>
        </div>

        <!-- Service 5: Retention & Email/SMS (Featured 2-column) -->
        <div class="service-card featured tilt-card reveal-init delay-200">
          <div class="tilt-child">
            <div class="service-icon-box">
              <i data-lucide="mail"></i>
            </div>
            <h3 class="service-title">Omnichannel Retention &amp; LTV Engine (Email &amp; SMS)</h3>
            <p class="service-desc">
              Acquisition gets them in the door; retention builds your enterprise value. We design hyper-personalized Klaviyo and SMS automation sequences that reliably produce 30-40% of your total brand revenue.
            </p>
            <ul class="service-features">
              <li><i data-lucide="check-circle-2"></i> Advanced behavioral predictive segmentation &amp; VIP tiers</li>
              <li><i data-lucide="check-circle-2"></i> Automated replenishment, win-back &amp; post-purchase flows</li>
              <li><i data-lucide="check-circle-2"></i> Continuous subject line &amp; offer split-testing</li>
            </ul>
            <div class="service-card-footer">
              <a href="#" class="link-arrow" data-modal-trigger="retention-lifecycle">
                <span>View Retention Blueprint</span>
                <i data-lucide="chevron-right" style="width:16px; height:16px;"></i>
              </a>
            </div>
          </div>
        </div>

        <!-- Service 6: Brand & Web -->
        <div class="service-card tilt-card reveal-init delay-300">
          <div class="tilt-child">
            <div class="service-icon-box">
              <i data-lucide="palette"></i>
            </div>
            <h3 class="service-title">Brand Positioning &amp; Web Experience</h3>
            <p class="service-desc">
              Transform your website into an unforgettable digital showcase that commands premium pricing and outclasses competition.
            </p>
            <ul class="service-features">
              <li><i data-lucide="check-circle-2"></i> High-performance responsive web design</li>
              <li><i data-lucide="check-circle-2"></i> Interactive 3D &amp; motion branding</li>
            </ul>
            <div class="service-card-footer">
              <a href="#" class="link-arrow" data-modal-trigger="brand-motion">
                <span>Discover Experience</span>
                <i data-lucide="chevron-right" style="width:16px; height:16px;"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Interactive ROI & Growth Calculator -->
  <section class="section" id="calculator" style="background: var(--bg-secondary);">
    <div class="container">
      <div class="section-header reveal-init">
        <div class="section-tag">
          <i data-lucide="calculator" style="width:16px; height:16px;"></i>
          GROWTH FORECASTER
        </div>
        <h2 class="section-title">Calculate Your <span class="gradient-text">Revenue Potential</span></h2>
        <p class="section-desc">
          Drag the sliders to model how our conversion rate optimization and ad scaling engine will compound your bottom line.
        </p>
      </div>

      <div class="calculator-card reveal-init">
        <!-- Sliders Column -->
        <div class="calc-inputs">
          <div class="slider-group">
            <div class="slider-header">
              <span class="slider-label">Monthly Ad Spend</span>
              <span class="slider-value" id="calc-spend-val">₹25,000</span>
            </div>
            <input type="range" class="range-slider" id="calc-spend" min="5000" max="250000" step="2500" value="25000">
            <div style="display:flex; justify-content:space-between; font-size:0.75rem; color:var(--text-muted);">
              <span>₹5,000 / mo</span>
              <span>₹250,000 / mo</span>
            </div>
          </div>

          <div class="slider-group">
            <div class="slider-header">
              <span class="slider-label">Current Conversion Rate</span>
              <span class="slider-value" id="calc-conv-val">1.8%</span>
            </div>
            <input type="range" class="range-slider" id="calc-conv" min="0.5" max="6.0" step="0.1" value="1.8">
            <div style="display:flex; justify-content:space-between; font-size:0.75rem; color:var(--text-muted);">
              <span>0.5% (Low)</span>
              <span>6.0% (High)</span>
            </div>
          </div>

          <div style="font-size:0.85rem; color:var(--text-secondary); line-height:1.6; padding-top:10px;">
            <i data-lucide="info" style="width:15px; height:15px; display:inline; vertical-align:middle; margin-right:4px;"></i>
            Projections are modeled on MadhuKesh growth benchmarks (averaging a 1.9x CRO multiplier and 15% increase in high-intent traffic efficiency).
          </div>
        </div>

        <!-- Outputs Column -->
        <div class="calc-outputs">
          <div class="calc-output-item">
            <span class="calc-output-label">Projected Monthly Revenue</span>
            <span class="calc-output-num gradient-text" id="calc-projected-rev">₹132,000</span>
          </div>
          <div class="calc-output-item">
            <span class="calc-output-label">Estimated Blended ROAS</span>
            <span class="calc-output-num gradient-text-cyan" id="calc-roas">5.3x</span>
          </div>
          <div class="calc-output-item">
            <span class="calc-output-label">Annual Revenue Lift</span>
            <span class="calc-output-num calc-highlight" id="calc-annual-lift">+₹980,000</span>
          </div>
          <div class="calc-output-item">
            <span class="calc-output-label">Extra Monthly Customers</span>
            <span class="calc-output-num" id="calc-extra-leads">+340</span>
          </div>

          <a href="#contact" class="btn btn-primary" style="margin-top:12px; width:100%;">
            <span>Unlock This Growth Roadmap</span>
            <i data-lucide="arrow-right" style="width:18px; height:18px;"></i>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- Work & Case Studies Showcase -->
  <section class="section" id="work">
    <div class="container">
      <div class="section-header reveal-init">
        <div class="section-tag">
          <i data-lucide="trophy" style="width:16px; height:16px;"></i>
          PROVEN CASE STUDIES
        </div>
        <h2 class="section-title">Verified Results. <span class="gradient-text">Zero Fluff.</span></h2>
        <p class="section-desc">
          Browse through some of our recent client transformation stories across high-growth verticals.
        </p>
      </div>

      <!-- Filter Tabs -->
      <div class="filter-nav reveal-init">
        <button class="filter-btn active" data-filter="all">All Verticals</button>
        <button class="filter-btn" data-filter="ecommerce">E-Commerce</button>
        <button class="filter-btn" data-filter="saas">B2B SaaS</button>
        <button class="filter-btn" data-filter="fintech">Fintech</button>
      </div>

      <!-- Project Cards Grid -->
      <div class="projects-grid">
        <!-- Project 1 -->
        <div class="project-card reveal-init" data-category="ecommerce">
          <div class="project-preview">
            <div class="project-preview-mockup">
              <div style="display:flex; justify-content:space-between; align-items:center;">
                <span style="font-size:0.8rem; font-weight:700; color:var(--primary);">LUMINA BOTANICALS</span>
                <span style="font-size:0.75rem; color:var(--accent-emerald); background:rgba(16,185,129,0.15); padding:2px 8px; border-radius:10px;">D2C BEAUTY</span>
              </div>
              <div style="text-align:center; padding:18px 0;">
                <div style="font-size:1.8rem; font-weight:800; color:white;">₹380,000 / mo</div>
                <div style="font-size:0.8rem; color:var(--text-secondary);">Scaled from ₹42k/mo in 9 months</div>
              </div>
              <div style="height:6px; background:var(--gradient-brand); border-radius:3px;"></div>
            </div>
          </div>
          <div class="project-content">
            <div class="project-tags">
              <span class="project-tag">Meta Ads</span>
              <span class="project-tag">TikTok UGC</span>
              <span class="project-tag">Klaviyo Retention</span>
            </div>
            <h3 class="project-title">Scaling D2C Skincare to ₹4.5M Annual Run Rate</h3>
            <p style="font-size:0.92rem; color:var(--text-secondary); margin-bottom:14px;">
              Re-engineered ad creatives with creator-led UGC, built a customized quiz funnel, and implemented post-purchase VIP replenishment flows.
            </p>
            <div class="project-results-row">
              <div>
                <div class="metric-highlight">+312%</div>
                <div class="metric-label">YoY Revenue Growth</div>
              </div>
              <div>
                <div class="metric-highlight">4.6x</div>
                <div class="metric-label">Blended ROAS</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Project 2 -->
        <div class="project-card reveal-init delay-100" data-category="saas">
          <div class="project-preview" style="background: linear-gradient(135deg, #064E3B 0%, #0F172A 100%);">
            <div class="project-preview-mockup">
              <div style="display:flex; justify-content:space-between; align-items:center;">
                <span style="font-size:0.8rem; font-weight:700; color:var(--secondary);">CLOUDSCALE AI</span>
                <span style="font-size:0.75rem; color:var(--primary); background:var(--primary-light); padding:2px 8px; border-radius:10px;">SERIES A SAAS</span>
              </div>
              <div style="text-align:center; padding:18px 0;">
                <div style="font-size:1.8rem; font-weight:800; color:white;">3,420 Qualified Leads</div>
                <div style="font-size:0.8rem; color:var(--text-secondary);">-58% Customer Acquisition Cost</div>
              </div>
              <div style="height:6px; background:var(--gradient-cyan); border-radius:3px;"></div>
            </div>
          </div>
          <div class="project-content">
            <div class="project-tags">
              <span class="project-tag">LinkedIn Ads</span>
              <span class="project-tag">AI Search SEO</span>
              <span class="project-tag">B2B Funnel</span>
            </div>
            <h3 class="project-title">Enterprise Pipeline Acceleration for AI Infrastructure</h3>
            <p style="font-size:0.92rem; color:var(--text-secondary); margin-bottom:14px;">
              Built high-intent programmatic comparison pages, deployed account-based marketing (ABM) on LinkedIn, and reduced demo no-show rate.
            </p>
            <div class="project-results-row">
              <div>
                <div class="metric-highlight">-58%</div>
                <div class="metric-label">CAC Reduction</div>
              </div>
              <div>
                <div class="metric-highlight">+220%</div>
                <div class="metric-label">Demo Conversion Lift</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Project 3 -->
        <div class="project-card reveal-init delay-200" data-category="fintech">
          <div class="project-preview" style="background: linear-gradient(135deg, #4C1D95 0%, #0F172A 100%);">
            <div class="project-preview-mockup">
              <div style="display:flex; justify-content:space-between; align-items:center;">
                <span style="font-size:0.8rem; font-weight:700; color:#A78BFA;">APEX WEALTH</span>
                <span style="font-size:0.75rem; color:var(--accent-amber); background:rgba(245,158,11,0.15); padding:2px 8px; border-radius:10px;">CONSUMER FINTECH</span>
              </div>
              <div style="text-align:center; padding:18px 0;">
                <div style="font-size:1.8rem; font-weight:800; color:white;">48,000+ App Installs</div>
                <div style="font-size:0.8rem; color:var(--text-secondary);">₹1.18 Cost Per Install</div>
              </div>
              <div style="height:6px; background:var(--gradient-gold); border-radius:3px;"></div>
            </div>
          </div>
          <div class="project-content">
            <div class="project-tags">
              <span class="project-tag">Apple Search Ads</span>
              <span class="project-tag">Google UAC</span>
              <span class="project-tag">App Store CRO</span>
            </div>
            <h3 class="project-title">Scaling Mobile Wealth App to #4 in App Store Finance</h3>
            <p style="font-size:0.92rem; color:var(--text-secondary); margin-bottom:14px;">
              Optimized App Store screenshots for conversion, implemented viral onboarding referral mechanics, and ran targeted micro-influencer campaigns.
            </p>
            <div class="project-results-row">
              <div>
                <div class="metric-highlight">48,000+</div>
                <div class="metric-label">Active Users Acquired</div>
              </div>
              <div>
                <div class="metric-highlight">5.1x</div>
                <div class="metric-label">Deposit ROAS</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Project 4 -->
        <div class="project-card reveal-init delay-300" data-category="ecommerce">
          <div class="project-preview" style="background: linear-gradient(135deg, #831843 0%, #0F172A 100%);">
            <div class="project-preview-mockup">
              <div style="display:flex; justify-content:space-between; align-items:center;">
                <span style="font-size:0.8rem; font-weight:700; color:var(--accent-pink);">NOVA ATHLETICA</span>
                <span style="font-size:0.75rem; color:var(--primary); background:var(--primary-light); padding:2px 8px; border-radius:10px;">PERFORMANCE APPAREL</span>
              </div>
              <div style="text-align:center; padding:18px 0;">
                <div style="font-size:1.8rem; font-weight:800; color:white;">16.4M Impressions</div>
                <div style="font-size:0.8rem; color:var(--text-secondary);">₹1.4M Sold in 30 Days</div>
              </div>
              <div style="height:6px; background:var(--gradient-brand); border-radius:3px;"></div>
            </div>
          </div>
          <div class="project-content">
            <div class="project-tags">
              <span class="project-tag">TikTok Spark Ads</span>
              <span class="project-tag">Viral Video</span>
              <span class="project-tag">Shopify Plus CRO</span>
            </div>
            <h3 class="project-title">Viral Launch Campaign Generating ₹1.4M in First Month</h3>
            <p style="font-size:0.92rem; color:var(--text-secondary); margin-bottom:14px;">
              Orchestrated an synchronized ambassador drop across 50 athletes, combined with high-velocity TikTok Spark Ads and 1-click upsells.
            </p>
            <div class="project-results-row">
              <div>
                <div class="metric-highlight">₹1.4M</div>
                <div class="metric-label">Launch Revenue</div>
              </div>
              <div>
                <div class="metric-highlight">3.9%</div>
                <div class="metric-label">Checkout Conversion Rate</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- The 4-Step Scalability Engine -->
  <section class="section" id="process" style="background: var(--bg-secondary);">
    <div class="container">
      <div class="section-header reveal-init">
        <div class="section-tag">
          <i data-lucide="git-merge" style="width:16px; height:16px;"></i>
          OUR METHODOLOGY
        </div>
        <h2 class="section-title">The 4-Step <span class="gradient-text">Scalability Engine</span></h2>
        <p class="section-desc">
          How we systematically transform plateaued brands into market category leaders.
        </p>
      </div>

      <div class="process-grid">
        <!-- Step 1 -->
        <div class="process-step-card reveal-init">
          <div class="step-number">01</div>
          <h3 class="step-title">Deep Audit &amp; Arbitrage</h3>
          <p class="step-desc">
            We inspect your unit economics, pixel telemetry, competitors, and drop-off points to find untapped revenue leaks.
          </p>
        </div>

        <!-- Step 2 -->
        <div class="process-step-card reveal-init delay-100">
          <div class="step-number">02</div>
          <h3 class="step-title">Creative &amp; Funnel Build</h3>
          <p class="step-desc">
            We script high-converting video hooks, redesign landing pages, and configure first-party tracking architecture.
          </p>
        </div>

        <!-- Step 3 -->
        <div class="process-step-card reveal-init delay-200">
          <div class="step-number">03</div>
          <h3 class="step-title">Omnichannel Launch</h3>
          <p class="step-desc">
            We deploy multi-variant ad campaigns across Meta, Google, and TikTok to identify statistically superior winners.
          </p>
        </div>

        <!-- Step 4 -->
        <div class="process-step-card reveal-init delay-300">
          <div class="step-number">04</div>
          <h3 class="step-title">Algorithmic Scaling</h3>
          <p class="step-desc">
            Once profitability thresholds are validated, we pump aggressive ad spend and automate email/SMS retention for 8-figure valuation.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonials Slider -->
  <section class="section" id="testimonials">
    <div class="container">
      <div class="section-header reveal-init">
        <div class="section-tag">
          <i data-lucide="message-square" style="width:16px; height:16px;"></i>
          FOUNDER VOICES
        </div>
        <h2 class="section-title">Endorsed By <span class="gradient-text">Industry Leaders</span></h2>
        <p class="section-desc">
          Hear directly from CEOs and CMOs who partnered with MadhuKesh to scale.
        </p>
      </div>

      <div class="testimonials-slider reveal-init">
        <!-- Slide 1 -->
        <div class="testimonial-card active">
          <div style="display:flex; justify-content:center; gap:4px; margin-bottom:20px; color:#F59E0B;">
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
          </div>
          <blockquote class="testimonial-quote">
            "Before MadhuKesh, our blended customer acquisition cost was completely erratic. Within 90 days, their creative testing matrix and CRO funnel cut our CAC by 42% while scaling our monthly volume past ₹350k. Best agency decision we've made."
          </blockquote>
          <div class="testimonial-author">
            <div class="author-avatar">MR</div>
            <div class="author-info">
              <div class="author-name">Marcus Reynolds</div>
              <div class="author-role">Founder &amp; CEO, Lumina Botanicals</div>
            </div>
          </div>
        </div>

        <!-- Slide 2 -->
        <div class="testimonial-card">
          <div style="display:flex; justify-content:center; gap:4px; margin-bottom:20px; color:#F59E0B;">
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
          </div>
          <blockquote class="testimonial-quote">
            "Most agencies just burn cash on generic search keywords. MadhuKesh understood our B2B buyer persona at a technical level. Their combination of LinkedIn Ads and programmatic SEO generated over 3,000 enterprise demo requests."
          </blockquote>
          <div class="testimonial-author">
            <div class="author-avatar" style="background:var(--gradient-brand);">SL</div>
            <div class="author-info">
              <div class="author-name">Sarah Lin</div>
              <div class="author-role">VP of Marketing, CloudScale AI</div>
            </div>
          </div>
        </div>

        <!-- Slide 3 -->
        <div class="testimonial-card">
          <div style="display:flex; justify-content:center; gap:4px; margin-bottom:20px; color:#F59E0B;">
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
            <i data-lucide="star" style="fill:#F59E0B;"></i>
          </div>
          <blockquote class="testimonial-quote">
            "Their speed of execution is mind-blowing. When a TikTok creative hits fatigue, MadhuKesh has 5 fresh iterations tested within 48 hours. They operate like an elite in-house growth squad rather than an external vendor."
          </blockquote>
          <div class="testimonial-author">
            <div class="author-avatar" style="background:var(--gradient-gold);">DK</div>
            <div class="author-info">
              <div class="author-name">David Kovacs</div>
              <div class="author-role">Co-Founder, Nova Athletica</div>
            </div>
          </div>
        </div>

        <!-- Controls -->
        <div class="slider-controls">
          <button class="btn-icon" id="test-prev" aria-label="Previous Testimonial">
            <i data-lucide="arrow-left"></i>
          </button>
          <button class="btn-icon" id="test-next" aria-label="Next Testimonial">
            <i data-lucide="arrow-right"></i>
          </button>
        </div>
      </div>
    </div>
  </section>

  <!-- Transparent Pricing & Engagement Models -->
  <section class="section" id="pricing" style="background: var(--bg-secondary);">
    <div class="container">
      <div class="section-header reveal-init">
        <div class="section-tag">
          <i data-lucide="credit-card" style="width:16px; height:16px;"></i>
          ENGAGEMENT MODELS
        </div>
        <h2 class="section-title">Transparent, <span class="gradient-text">Performance-Driven</span> Plans</h2>
        <p class="section-desc">
          No hidden fees or bloated retainers. Just clear deliverables tied to measurable revenue expansion.
        </p>

        <!-- Monthly / Quarterly Switch -->
        <div class="pricing-toggle-wrap" style="margin-top:30px;">
          <span class="toggle-label">Monthly Retainer</span>
          <label class="switch">
            <input type="checkbox" id="pricing-toggle">
            <span class="slider-round"></span>
          </label>
          <span class="toggle-label">Quarterly Partner</span>
          <span class="discount-badge">Save 20%</span>
        </div>
      </div>

      <div class="pricing-grid">
        <!-- Plan 1 -->
        <div class="pricing-card reveal-init">
          <h3 class="pricing-tier-name">Sprint Growth</h3>
          <p class="pricing-tier-desc">Ideal for emerging brands scaling past ₹20k-₹50k monthly revenue.</p>
          <div class="price-box">
            <span class="price-currency">₹</span>
            <span class="price-amount" data-monthly-price="4,500" data-quarterly-price="3,600">4,500</span>
            <span class="price-period">/ month</span>
          </div>
          <ul class="pricing-features">
            <li><i data-lucide="check"></i> 1 Primary Paid Channel (Meta or Google)</li>
            <li><i data-lucide="check"></i> 8 High-Impact Creatives / month</li>
            <li><i data-lucide="check"></i> Bi-weekly performance sprint calls</li>
            <li><i data-lucide="check"></i> Real-time analytics dashboard</li>
            <li><i data-lucide="check"></i> Slack communication channel</li>
          </ul>
          <a href="#contact" class="btn btn-secondary">Get Started</a>
        </div>

        <!-- Plan 2 (Popular) -->
        <div class="pricing-card featured-tier reveal-init delay-100">
          <div class="popular-badge">MOST POPULAR</div>
          <h3 class="pricing-tier-name">Scale Engine</h3>
          <p class="pricing-tier-desc">Our flagship multi-channel machine for brands ready to reach 8 figures.</p>
          <div class="price-box">
            <span class="price-currency">₹</span>
            <span class="price-amount gradient-text" data-monthly-price="8,500" data-quarterly-price="6,800">8,500</span>
            <span class="price-period">/ month</span>
          </div>
          <ul class="pricing-features">
            <li><i data-lucide="check"></i> Multi-Channel Ads (Meta + Google + TikTok)</li>
            <li><i data-lucide="check"></i> Full CRO &amp; Landing Page A/B Testing</li>
            <li><i data-lucide="check"></i> 20+ New Video &amp; Static Creatives / mo</li>
            <li><i data-lucide="check"></i> Klaviyo Email &amp; SMS Retention Funnel</li>
            <li><i data-lucide="check"></i> Weekly Growth Strategy Sprints</li>
            <li><i data-lucide="check"></i> Dedicated Senior Growth Director</li>
          </ul>
          <a href="#contact" class="btn btn-primary">Scale Your Brand</a>
        </div>

        <!-- Plan 3 -->
        <div class="pricing-card reveal-init delay-200">
          <h3 class="pricing-tier-name">Enterprise Bespoke</h3>
          <p class="pricing-tier-desc">Customized growth infrastructure for VC-backed &amp; high-volume brands.</p>
          <div class="price-box">
            <span class="price-currency">₹</span>
            <span class="price-amount" data-monthly-price="15,000" data-quarterly-price="12,000">15,000</span>
            <span class="price-period">/ month</span>
          </div>
          <ul class="pricing-features">
            <li><i data-lucide="check"></i> All Channels + International Expansion</li>
            <li><i data-lucide="check"></i> AI Search &amp; Programmatic SEO Dominance</li>
            <li><i data-lucide="check"></i> Unlimited Creative Production &amp; UGC</li>
            <li><i data-lucide="check"></i> Full Funnel CRO &amp; Headless Optimization</li>
            <li><i data-lucide="check"></i> 24/7 Dedicated Slack War Room</li>
            <li><i data-lucide="check"></i> Revenue Share Performance Incentive</li>
          </ul>
          <a href="#contact" class="btn btn-secondary">Contact For Custom Scope</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Frequently Asked Questions -->
  <section class="section" id="faq">
    <div class="container" style="max-width:860px;">
      <div class="section-header reveal-init">
        <div class="section-tag">
          <i data-lucide="help-circle" style="width:16px; height:16px;"></i>
          FAQ
        </div>
        <h2 class="section-title">Got Questions? <span class="gradient-text">We Have Answers.</span></h2>
      </div>

      <div class="reveal-init" style="display:flex; flex-direction:column; gap:16px;">
        <details style="background:var(--bg-card); border:1px solid var(--border-color); border-radius:var(--radius-md); padding:20px; cursor:pointer;">
          <summary style="font-weight:700; font-size:1.1rem; list-style:none; display:flex; justify-content:space-between; align-items:center;">
            <span>How fast can we launch campaigns once we onboard?</span>
            <i data-lucide="chevron-down" style="color:var(--primary);"></i>
          </summary>
          <p style="margin-top:14px; font-size:0.95rem; line-height:1.6;">
            Our standard onboarding takes 7 to 10 business days. During this window, we audit your tracking telemetry, configure conversion APIs, script and produce initial creative assets, and build custom landing pages before going live.
          </p>
        </details>

        <details style="background:var(--bg-card); border:1px solid var(--border-color); border-radius:var(--radius-md); padding:20px; cursor:pointer;">
          <summary style="font-weight:700; font-size:1.1rem; list-style:none; display:flex; justify-content:space-between; align-items:center;">
            <span>What makes MadhuKesh different from other agencies?</span>
            <i data-lucide="chevron-down" style="color:var(--primary);"></i>
          </summary>
          <p style="margin-top:14px; font-size:0.95rem; line-height:1.6;">
            Most agencies treat media buying and creative as separate silos. We treat them as one unified feedback loop. We also cap client rosters per team so you get experienced senior strategists, not junior interns learning on your budget.
          </p>
        </details>

        <details style="background:var(--bg-card); border:1px solid var(--border-color); border-radius:var(--radius-md); padding:20px; cursor:pointer;">
          <summary style="font-weight:700; font-size:1.1rem; list-style:none; display:flex; justify-content:space-between; align-items:center;">
            <span>What minimum monthly ad budget do you recommend?</span>
            <i data-lucide="chevron-down" style="color:var(--primary);"></i>
          </summary>
          <p style="margin-top:14px; font-size:0.95rem; line-height:1.6;">
            We recommend a minimum monthly ad spend of ₹5,000 across Meta or Google so the machine learning algorithms have enough conversion data to exit the learning phase and optimize rapidly.
          </p>
        </details>

        <details style="background:var(--bg-card); border:1px solid var(--border-color); border-radius:var(--radius-md); padding:20px; cursor:pointer;">
          <summary style="font-weight:700; font-size:1.1rem; list-style:none; display:flex; justify-content:space-between; align-items:center;">
            <span>Are there long-term contracts required?</span>
            <i data-lucide="chevron-down" style="color:var(--primary);"></i>
          </summary>
          <p style="margin-top:14px; font-size:0.95rem; line-height:1.6;">
            We offer flexible 90-day initial agreements (the time needed to test, optimize, and scale a proper funnel). After that, partnerships operate month-to-month with a simple 30-day notice period.
          </p>
        </details>
      </div>
    </div>
  </section>

  <!-- Interactive Project Discovery / Contact Section -->
  <section class="section" id="contact">
    <div class="container">
      <div class="contact-section-inner reveal-init">
        <!-- Info Column -->
        <div class="contact-info-col">
          <div>
            <div class="section-tag">
              <i data-lucide="rocket" style="width:16px; height:16px;"></i>
              LET'S TALK SCALE
            </div>
            <h2 class="section-title" style="text-align:left;">Ready To Accelerate Your <span class="gradient-text">Revenue?</span></h2>
            <p style="font-size:1.05rem; line-height:1.6;">
              Schedule a 30-minute discovery session with our senior marketing architects. We will conduct a live teardown of your current marketing funnel and share custom growth opportunities.
            </p>

            <ul class="contact-perks-list">
              <li class="contact-perk-item">
                <div class="contact-perk-icon"><i data-lucide="check"></i></div>
                <div>
                  <div style="font-weight:700;">Zero-Pressure Audit</div>
                  <div style="font-size:0.85rem; color:var(--text-secondary);">Direct strategic insights you can execute immediately.</div>
                </div>
              </li>
              <li class="contact-perk-item">
                <div class="contact-perk-icon"><i data-lucide="shield"></i></div>
                <div>
                  <div style="font-weight:700;">Strict NDA Protection</div>
                  <div style="font-size:0.85rem; color:var(--text-secondary);">Your ad accounts, margins, and data are 100% confidential.</div>
                </div>
              </li>
              <li class="contact-perk-item">
                <div class="contact-perk-icon"><i data-lucide="clock"></i></div>
                <div>
                  <div style="font-weight:700;">24-Hour Response</div>
                  <div style="font-size:0.85rem; color:var(--text-secondary);">Our founders personally review every brand inquiry.</div>
                </div>
              </li>
            </ul>
          </div>

          <div style="font-size:0.9rem; color:var(--text-secondary); border-top:1px solid var(--border-color); padding-top:20px; display:flex; flex-direction:column; gap:8px;">
            <div>Phone: <a href="tel:8849212876" style="color:var(--primary); font-weight:600;">8849212876</a></div>
            <div>Email: <a href="mailto:madhukesh081@gmail.com" style="color:var(--primary); font-weight:600;">madhukesh081@gmail.com</a></div>
          </div>
        </div>

        <!-- Form Column -->
        <div>
          <form class="contact-form" id="agency-contact-form">
            <div class="form-group">
              <label class="form-label">Select Services Needed</label>
              <div class="form-chips">
                <div class="chip selected">Performance Ads</div>
                <div class="chip">CRO &amp; Funnels</div>
                <div class="chip">AI Search / SEO</div>
                <div class="chip">Video &amp; Creative</div>
                <div class="chip">Email &amp; SMS Retention</div>
                <div class="chip">Full Growth Engine</div>
              </div>
            </div>

            <div class="form-group">
              <label class="form-label" for="contact-name">Your Full Name *</label>
              <input type="text" id="contact-name" class="form-input" placeholder="e.g. Elena Vance" required>
            </div>

            <div class="form-group">
              <label class="form-label" for="contact-email">Work Email *</label>
              <input type="email" id="contact-email" class="form-input" placeholder="elena@yourcompany.com" required>
            </div>

            <div class="form-group">
              <label class="form-label" for="contact-website">Website or Store URL</label>
              <input type="url" id="contact-website" class="form-input" placeholder="https://yourbrand.com">
            </div>

            <div class="form-group">
              <label class="form-label" for="contact-spend">Current Monthly Ad Spend</label>
              <select id="contact-spend" class="form-input" style="background:var(--bg-input); color:var(--text-primary);">
                <option value="under-10k">&lt; ₹10,000 / month</option>
                <option value="10k-50k" selected>₹10,000 - ₹50,000 / month</option>
                <option value="50k-150k">₹50,000 - ₹150,000 / month</option>
                <option value="150k+">₹150,000+ / month</option>
              </select>
            </div>

            <div class="form-group">
              <label class="form-label" for="contact-notes">Primary Growth Bottleneck</label>
              <textarea id="contact-notes" class="form-textarea" rows="3" placeholder="Tell us about your target goals and current acquisition challenges..."></textarea>
            </div>

            <div id="form-feedback" style="display:none;"></div>

            <button type="submit" class="btn btn-primary" style="padding:16px; font-size:1.05rem;">
              <span>Claim Your Free Growth Roadmap</span>
              <i data-lucide="send" style="width:18px; height:18px;"></i>
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Global Modal Popup Container -->
  <div class="modal-overlay" id="global-modal">
    <div class="modal-content">
      <button class="modal-close-btn" id="modal-close" aria-label="Close dialog">
        <i data-lucide="x"></i>
      </button>
      <h3 id="modal-title" style="font-size:1.5rem; margin-bottom:18px; color:var(--text-primary);"></h3>
      <div id="modal-body"></div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <div class="footer-top">
        <div>
          <a href="#" class="brand">
            <img src="assets/madhukesh-logo.png" alt="MadhuKesh logo" class="brand-logo">
            <span class="brand-name">MadhuKesh</span>
          </a>
          <p class="footer-desc">
            Modern digital experiences designed to help brands grow with clarity, confidence, and momentum.
          </p>
          <div style="display:flex; gap:12px; margin-top:18px;">
            <a href="#" class="btn-icon" aria-label="Twitter"><i data-lucide="twitter"></i></a>
            <a href="#" class="btn-icon" aria-label="LinkedIn"><i data-lucide="linkedin"></i></a>
            <a href="#" class="btn-icon" aria-label="Instagram"><i data-lucide="instagram"></i></a>
            <a href="#" class="btn-icon" aria-label="YouTube"><i data-lucide="youtube"></i></a>
          </div>
        </div>

        <div>
          <div class="footer-col-title">Navigation</div>
          <ul class="footer-links">
            <li><a href="#services" class="footer-link">Services</a></li>
            <li><a href="#calculator" class="footer-link">ROI Calculator</a></li>
            <li><a href="#work" class="footer-link">Case Studies</a></li>
            <li><a href="#process" class="footer-link">Methodology</a></li>
            <li><a href="#pricing" class="footer-link">Pricing Models</a></li>
          </ul>
        </div>

        <div>
          <div class="footer-col-title">Capabilities</div>
          <ul class="footer-links">
            <li><a href="#services" class="footer-link">Performance Paid Media</a></li>
            <li><a href="#services" class="footer-link">AI Search &amp; SEO</a></li>
            <li><a href="#services" class="footer-link">Conversion Optimization</a></li>
            <li><a href="#services" class="footer-link">Video &amp; UGC Creative</a></li>
            <li><a href="#services" class="footer-link">Omnichannel Retention</a></li>
          </ul>
        </div>

        <div>
          <div class="footer-col-title">The Growth Letter</div>
          <p style="font-size:0.875rem; color:var(--text-secondary); margin-bottom:12px;">
            Join 12,500+ founders receiving our weekly breakdown on ad algorithm changes and CRO playbooks.
          </p>
          <form class="newsletter-form" onsubmit="event.preventDefault(); alert('Subscribed to Growth Letter!');">
            <input type="email" placeholder="Enter work email..." class="form-input" style="padding:10px 14px; font-size:0.85rem;" required>
            <button type="submit" class="btn btn-primary" style="padding:10px 18px;">
              <i data-lucide="arrow-right" style="width:16px; height:16px;"></i>
            </button>
          </form>
        </div>
      </div>

      <div class="footer-bottom">
        <div>
          © <span id="current-year">2026</span> MadhuKesh. All rights reserved.
        </div>
        <div style="display:flex; gap:24px;">
          <a href="#" class="footer-link">Privacy Policy</a>
          <a href="#" class="footer-link">Terms of Service</a>
          <a href="#" class="footer-link">Security Telemetry</a>
        </div>
      </div>
    </div>
  </footer>

  <!-- Floating Back-to-Top Button -->
  <button class="back-to-top" aria-label="Scroll back to top">
    <i data-lucide="arrow-up"></i>
  </button>

  <!-- JavaScript Modules -->
  <script src="js/canvas-bg.js"></script>
  <script src="js/animations.js"></script>
  <script src="js/calculator.js"></script>
  <script src="js/main.js"></script>

  <!-- Initialize Lucide Icons -->
  <script>
    if (window.lucide) {
      window.lucide.createIcons();
    }
  </script>
</body>
</html>

