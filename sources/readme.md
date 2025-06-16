---
title: "Global Trade, Climate Clubs, and Associated Uncertainties"
subtitle: "Energy Transitions Policy and Modeling at a Crossroads"
author: "John Paul Helveston"
institute: "George Washington University"
date: "Snowmass 2025"
output:
  xaringan::moon_reader:
    css:
      - default
      - css/lexis.css
      - css/lexis-fonts.css
    lib_dir: libs
    nature:
      highlightStyle: github
      highlightLines: true
      countIncrementalSlides: false
      ratio: "16:9"
    seal: true
---

<style>
.tab {
    display: inline-block;
    margin-left: 8em;
}
</style>

```{r, child="setup.Rmd"}
```

---

class: middle, center

# What if the assumptions underlying our energy transition models are fundamentally changing?

---

# The Old Paradigm vs. New Reality

<br>

--

### **2000s Globalization**: Free flow of capital, talent, innovation
- Technology spillovers across borders
- Global learning curves
- Efficiency through comparative advantage

--

<br>

### **2020s Fragmentation**: Economic nationalism meets climate action
- Trade wars targeting clean technology
- Industrial policy competition
- "Friend-shoring" supply chains

---

# Nation-States Acting in Self-Interest

<br>

### **United States** 🇺🇸
- Inflation Reduction Act: $370B in domestic incentives
- Tariffs on Chinese solar panels, EVs, batteries

--

<br>

### **European Union** 🇪🇺
- Critical Raw Materials Act
- Anti-dumping measures on Chinese renewables

--

<br>

### **China** 🇨🇳
- Dual circulation strategy
- Technology export controls
- 78% of global solar manufacturing

---

class: middle, center, inverse

# What does this cost us?

---

# Solar PV: A Natural Experiment

<br>

### **Research Question**: What are the cost savings from globalized vs. nationalized solar supply chains?

--

<br>

### **Method**: Two-factor learning model
- Historical data: 2008-2020
- Three largest markets: US, Germany, China
- Compare global vs. national learning scenarios

--

<br>

### **Context**: China achieved 78% global production share by 2021

---

background-color: #fff

## Historical Savings from Global Supply Chains (2008-2020)

<center>
<img src="images/historical-savings.png" width=85%>
</center>

### **Total Savings: $67 billion across three countries**

---

# The Learning Mechanism

<br>

### **Learning Rates Varied by Country**:
- **China**: 33% cost reduction per doubling of capacity
- **United States**: 26% cost reduction
- **Germany**: 20% cost reduction

--

<br>

### **Why Global Markets Matter**:
- Larger scale → Faster learning
- Technology spillovers across borders
- Competition drives innovation

--

<br>

### **National Markets = Constrained Learning**

---

# Future Costs of Fragmentation (2020-2030)

<br>

--

### **Scenario**: Gradual transition to domestic production over 10 years

--

<br>

### **Results**: Solar module prices **20-25% higher** by 2030

--

<br>

### **Economic Impact**:
- **National trends scenario**: $15 billion additional costs
- **Sustainable development scenario**: $36 billion additional costs

--

<br>

### **Climate Impact**: Slower deployment, higher costs for climate goals

---

class: center

background-color: #fff

## Price Projections Under Different Scenarios

<center>
<img src="images/price-projections.png" width=90%>
</center>

---

# Beyond Solar: The Broader Pattern

<br>

### **Wind Energy**: Globally integrated supply chain
- Specialized component trade
- Even larger disruptions from nationalization

--

<br>

### **Electric Vehicles**: Similar dynamics emerging
- Battery supply chain concentration
- Industrial policy competition

--

<br>

### **The Pattern**: Clean technologies caught in geopolitical crossfire

---

class: middle, center

# So what do we do about this tension?

---

# Climate Clubs: A Potential Solution?

<br>

### **The Concept**: Coalitions of willing countries
- Coordinated climate action
- Preferential trade treatment for members
- Burden sharing for global public goods

--

<br>

### **Trade Dimension**:
- Lower tariffs within the club
- Common standards and regulations
- Technology sharing agreements

--

<br>

### **The Challenge**: Balancing cooperation with competition

---

# The Trilemma

<br>

.leftcol[
### **Three Goals**:
1. **Climate Action**: Speed and scale
2. **Economic Competitiveness**: Domestic benefits
3. **Technology Sovereignty**: Strategic autonomy
]

--

.rightcol[
### **Reality**:
Cannot optimize all three simultaneously

### **Policy Question**:
How to sequence and prioritize?
]

---

# Research and Modeling Implications

<br>

### **Current Models Assume**:
- Frictionless technology transfer
- Global learning curves
- Minimal trade barriers

--

<br>

### **New Reality Requires**:
- Political economy constraints
- Fragmented innovation systems
- Trade policy feedbacks

--

<br>

### **Research Priorities**:
- Extending analysis to other clean technologies
- Designing effective climate clubs
- Updating Integrated Assessment Models

---

class: middle, center

# Key Takeaways

---

# Three Main Points

<br>

### **1. Globalization delivered massive cost savings**
$67 billion for solar PV alone (2008-2020)

--

<br>

### **2. Fragmentation will slow progress and increase costs**
20-25% higher prices by 2030 under national scenarios

--

<br>

### **3. Models need updating to reflect new trade realities**
Political economy cannot be ignored

---

class: middle, center, inverse

# The question isn't whether countries will pursue industrial policy—they already are.

# The question is whether we can design these policies to preserve the global cooperation that made clean technology affordable in the first place.

---

class: inverse
background-image: url("images/blue.jpg")
background-size: cover

<br>

# Thanks!

<br>

### <span class="white-text">Questions?</span>

<style>
.white-text a {
  color: white !important;
}
</style>

.footer-large[.white[.right[

@jhelvy.bsky.social `r fa(name = "bluesky", fill = "white")`<br>
@jhelvy `r fa(name = "github", fill = "white")`<br>
jhelvy.com `r fa(name = "link", fill = "white")`<br>
jph@gwu.edu `r fa(name = "paper-plane", fill = "white")`

]]]

---

class: inverse, middle, center

# Extra Slides

---

# Alternative Learning Model Specifications

<br>

### **Two-Factor Model**:
ln(price) = α + β₁ × ln(capacity) + β₂ × ln(silicon_price)

--

<br>

### **National vs. Global Capacity**:
- Global scenario: Uses worldwide installed capacity
- National scenario: Weighted transition to domestic capacity
- λₜ parameter: 0 (fully global) to 1 (fully national) over 10 years

--

<br>

### **Uncertainty Analysis**:
95% confidence intervals from parameter covariance matrix

---

# Extended Results by Country

<br>

### **United States**:
- Historical savings: $24 billion (2008-2020)
- 2030 price increase: 107% under national scenario
- Learning rate: 26%

--

<br>

### **Germany**:
- Historical savings: $7 billion (2008-2020)
- 2030 price increase: 83% under national scenario
- Learning rate: 20%

--

<br>

### **China**:
- Historical savings: $36 billion (2007-2020)
- 2030 price increase: 54% under national scenario
- Learning rate: 33%

---

# Policy Design Considerations

<br>

### **Climate Club Design**:
- Membership criteria and incentives
- Technology sharing mechanisms
- Burden sharing formulas

--

<br>

### **Complementary Policies**:
- Address distributional concerns
- Support affected communities
- Maintain innovation incentives

--

<br>

### **Modeling Integration**:
- Trade policy in IAMs
- Political economy constraints
- Technology spillover effects


