---
# Options: 'default', 'seriph', 'apple-basic'
# theme: seriph
theme: ./theme #customized ejected seriph theme
themeConfig:
  primary: '#073bb5'
  darkMode: false
# background image
background: /header.jpg
# some information about your slides (markdown enabled)
title: "Lifespan Normative Modeling; Charting Healthy Norms & Detecting Pathological Deviations"
info: |
  ## Slides for CSC Retreat 2025
  Lifespan Normative Modeling Charting Healthy Norms & Detecting Pathological Deviations
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
transitionDuration: 2000
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
katex: true
# favicon, can be a local file path or URL
favicon: "/favicon.ico"
---

<h1 style="font-size: 4.1rem;">Lifespan Normative Modeling</h1>

<h2 style="font-size: 2rem; font-style: italic;">Charting Healthy Norms & Detecting Pathological Deviations</h2>

<p class="text-lg text-teal-200"> Presentation slides for the </p> [CSC Retreat 2025](https://sina-mansour.github.io/csc_retreat_2025_presentation/)

<div class="abs-br m-6 text-xl">
  <a href="https://sina-mansour.github.io/" target="_blank" class="slidev-icon-btn">
    <carbon:user-avatar-filled />
  </a>
  <a href="https://github.com/sina-mansour" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<div class="abs-bl m-6 flex items-center gap-2">
  <img src="./assets/Avatar_v1.png" alt="Avatar photo" width="80">
  <div>
    <div class="text-4 text-left">Sina Mansour L.</div>
    <div class="text-2 text-left italic">National University of Singapore & The University of Melbourne</div>
    <div class="text-2 text-left italic"><carbon:email /> sina.mansour.lakouraj@gmail.com</div>
  </div>
</div>

<div class="abs-tr m-6 text-sm">
  <carbon:calendar /> Nov. 19. 2025
</div>


---
layout: default
transition: slow-fade
---

# Normative Modeling

ℹ️ Background


<div v-click="1" class="absolute top-60 left-1/18 w-3/7 h-55 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/child_growth_fig.png" class="absolute left-0 w-full p-5 top-20 -translate-y-1/2">
</div>

<div v-click="2" class="absolute top-60 left-5/10 w-2/5 h-55 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/growth_chart.png" class="absolute left-0 w-full p-5 top-20 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1038/s41380-019-0441-1">WHO (2006)</a></div>
</div>

<myFooter />


---
layout: default
transition: slow-fade
---

# Normative Modeling

ℹ️ Background

<ul class="text-5" v-motion:initial="{ x: -20 }":enter="{ x: -20 }">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Characterize population-level phenotype distribution to detect individual deviations.</div>
  </li>
</ul>

<div class="absolute top-45 left-1/6 w-2/3 h-60 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/normative_chart.png" class="absolute left-0 w-1/2 p-5 top-30 -translate-y-1/2">
  <img src="./assets/normative_landscape.png" class="absolute right-0 w-1/2 p-5 top-30 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1038/s41380-019-0441-1">Marquand et al. (2019)</a></div>
</div>

<myFooter />


---
layout: default
transition: slow-fade
---

# Normative Modeling

ℹ️ Background

<ul class="text-5" v-motion:initial="{ x: -20 }":enter="{ x: -20 }">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Map lifespan brain charts using large-scale imaging data.</div>
  </li>
</ul>

<div class="absolute top-55 left-2/10 w-3/5 h-55 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/brain_chart.png" class="absolute left-0 w-full p-5 top-20 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1038/s41380-019-0441-1">Bethlehem et al. (2022)</a></div>
</div>

<myFooter />


---
layout: default
transition: slow-fade
---

# Normative Modeling

ℹ️ Background

<ul class="text-5" v-motion:initial="{ x: -20 }":enter="{ x: -20 }">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Enables exploration of individual-level differences and heterogeneity of deviations.</div>
  </li>
</ul>

<div class="absolute top-55 left-1/ w-6/7 h-40 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/deviation_patterns.png" class="absolute left-0 w-full p-5 top-20 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1016/j.biopsych.2015.12.023">Marquand et al. (2016)</a></div>
</div>

<myFooter />


---
layout: default
transition: slow-fade
---

# Conventional Normative Modeling

🎯 Direct Model

<ul class="text-5" v-motion:initial="{ x: -20 }":enter="{ x: -20 }">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Trained to infer normative ranges of a predefined fixed phenotype (y) from a set of covariates (X).</div>
  </li>
</ul>

<div class="absolute top-55 left-1/6 w-2/3 h-50 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/direct.png" class="absolute left-0 w-full p-5 top-25 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1101/2025.01.16.25320639">Mansour L. et al. (2025)</a></div>
</div>


<myFooter />


---
layout: default
transition: slow-fade
---

# Spectral Normative Modeling (SNM)

💡 The idea?

<ul class="text-5" v-motion:initial="{ x: -20 }":enter="{ x: -20 }">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Idea: Use graph spectral decomposition to compress and reconstruct normative ranges.</div>
  </li>
</ul>

<div class="absolute top-45 left-1/6 w-2/3 h-70 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/snm.png" class="absolute left-0 w-full p-5 top-35 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1101/2025.01.16.25320639">Mansour L. et al. (2025)</a></div>
</div>


<myFooter />


---
layout: default
transition: slow-fade
---

# Spectral Normative Modeling (SNM)

🎖️ Performance

<ul class="text-5" v-motion:initial="{ x: -20 }":enter="{ x: -20 }">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>With at least 1000 modes SNM achieves accurate estimates for normative ranges.</div>
  </li>
</ul>

<div class="absolute top-45 left-1/10 w-4/5 h-70 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/performance.png" class="absolute left-0 w-full p-5 top-35 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1101/2025.01.16.25320639">Mansour L. et al. (2025)</a></div>
</div>

<myFooter />


---
layout: default
transition: slow-fade
---

# Utility of SNM

🔎 High-resolution normative modeling

<ul class="text-5" v-motion:initial="{ x: -20 }":enter="{ x: -20 }">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Utilize a large-scale sample of >70K brain scans.</div>
  </li>
</ul>

<div class="absolute top-45 left-1/6 w-2/3 h-70 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/demography.png" class="absolute left-0 w-full p-5 top-35 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1101/2025.01.16.25320639">Mansour L. et al. (2025)</a></div>
</div>

<myFooter />


---
layout: default
transition: slow-fade
---

# Utility of SNM

🔎 High-resolution normative modeling

<ul class="text-5" v-motion:initial="{ x: -20 }":enter="{ x: -20 }">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Efficiently estimate normative ranges at vertex-resolution across human lifespan.</div>
  </li>
</ul>

<div class="absolute top-45 left-1/6 w-2/3 h-70 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/lifespan.png" class="absolute left-0 w-full p-5 top-35 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1101/2025.01.16.25320639">Mansour L. et al. (2025)</a></div>
</div>

<myFooter />


---
layout: default
transition: slow-fade
---

# Utility of SNM

🔎 High-resolution normative modeling

<ul class="text-5" v-motion:initial="{ x: -20 }":enter="{ x: -20 }">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Enables mapping individualized vertex-resolution normative assessment.</div>
  </li>
</ul>

<div class="absolute top-45 left-1/12 w-5/6 h-70 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/personalized.png" class="absolute left-0 w-full p-5 top-35 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1101/2025.01.16.25320639">Mansour L. et al. (2025)</a></div>
</div>

<myFooter />


---
layout: default
transition: slow-fade
---

# Clinical application in AD

👥 Population-level pathology assessment

<ul class="text-5" v-motion:initial="{ x: -20 }":enter="{ x: -20 }">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Transfer learning: Normative cortical correlates of cognitive impairment in AD</div>
  </li>
</ul>

<div class="absolute top-50 left-1/16 w-7/8 h-55 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/group-level.png" class="absolute left-0 w-full p-5 top-27 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1101/2025.01.16.25320639">Mansour L. et al. (2025)</a></div>
</div>

<myFooter />


---
layout: default
transition: slow-fade
---

# Clinical application in AD

👤 Individual-level assessments

<ul class="absolute text-5" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <li class="flex gap-2 pb-2">
    <div class="text-cyan-500" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Probing inter-individual variability in atrophy:</div>
  </li>
</ul>

<div class="absolute top-50 left-1/16 w-7/8 h-55 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/individual.png" class="absolute left-0 w-full p-5 top-27 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1101/2025.01.16.25320639">Mansour L. et al. (2025)</a></div>
</div>


<myFooter />


---
layout: default
transition: slow-fade
---

# Modeling Other Phenotypes & Modalities

🤝 Ideas for future collaborations

<ul class="absolute text-5" v-click="1" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <li class="flex gap-2 pb-2" v-click="1">
    <div class="text-cyan-500" v-click="[1,2]" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Do you have data to share?</div>
  </li>
  <li class="flex gap-2 pb-2" v-click="2">
    <div class="text-cyan-500" v-click="[2,3]" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Access to in-house developing normative modeling software.</div>
  </li>
  <li class="flex gap-2 pb-2" v-click="3">
    <div class="text-cyan-500" v-click="[3,4]" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Cross-norm associations.</div>
  </li>
  <li class="flex gap-2 pb-2" v-click="4">
    <div class="text-cyan-500" v-click="[4,5]" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Individual-calibrated models from activity/sleep data.</div>
  </li>
  <li class="flex gap-2 pb-2" v-click="5">
    <div class="text-cyan-500" v-click="4" v-motion :initial="{ x: -50, color: '#FFF' }" :enter="{ x: 0, color: '#3BC' }" :leave="{ x: -50, color: '#FFF' }"><carbon:send /></div>
    <div>Let's turn these into a grant proposal... <br/> or at least a good coffee conversation. ☕</div>
  </li>
</ul>

<div class="absolute top-50 left-1/3 w-1/3 h-65 rounded-lg shadow-lg" v-click="1" v-motion :initial="{ x: -50}" :enter="{ x : 0, scale: 1, y: 0 }" :click-2="{ scale: 0.1, y:-185, x:-405 }" :leave="{ x : 50}">
  <img src="./assets/data.png" class="absolute left-0 w-full p-5 top-27 -translate-y-1/2">
</div>

<div class="absolute top-35 left-7/10 w-1/4 h-55 rounded-lg shadow-lg" v-click="2" v-motion :initial="{ x: -50}" :enter="{ x : 0, scale: 1, y: 0}" :click-3="{ scale: 0.15, y:-60, x:-725 }" :leave="{ x : 50}">
  <img src="./assets/SpectraNorm.png" class="absolute left-0 w-full p-5 top-27 -translate-y-1/2">
</div>

<div class="absolute top-55 left-2/5 w-1/3 h-65 rounded-lg shadow-lg" v-click="3" v-motion :initial="{ x: -50}" :enter="{ x : 0, scale: 1, y: 0}" :click-4="{ scale: 0.1, y:-115, x:-470 }" :leave="{ x : 50}">
  <img src="./assets/crossnorm.png" class="absolute left-0 w-full p-5 top-27 -translate-y-1/2">
</div>

<div class="absolute top-55 left-5/8 w-1/3 h-65 rounded-lg shadow-lg" v-click="4" v-motion :initial="{ x: -50}" :enter="{ x : 0, scale: 1, y: 0}" :click-5="{ scale: 0.1, y:-70, x:-690 }" :leave="{ x : 50}">
  <img src="./assets/daily.png" class="absolute left-0 w-full p-5 top-27 -translate-y-1/2">
</div>

<div class="absolute top-90 left-4/6 w-1/4 h-30 rounded-lg shadow-lg" v-click="5" v-motion :initial="{ x: -50}" :enter="{ x : 0, scale: 1, y: 0}" :leave="{ x : 50}">
  <img src="./assets/coffee.png" class="absolute left-0 w-full p-2 top-0 -translate-y-1/2">
</div>


<myFooter />

---
layout: default
transition: fade-out
---

# Acknowledgements

<div v-click="[1,2]" class="absolute top-0 left-0 w-full h-full" v-motion :initial="{ scale : 0.1, y : 20, x : -200}" :enter="{ scale : 0.75, y : 20, x : -200}" :leave="{ scale : 0.1, y : 20, x : -200}">
  <img src="./assets/brainnet.png" class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-170" style="filter: drop-shadow(0 0 5px rgba(158, 228, 228, 0.8));">

  <img src="./assets/andrew-zalesky.png" class="absolute left-136 top-11 rounded-full w-27 object-cover border-4 border-gray-400 bg-cyan-400 shadow-lg">
  <img src="./assets/thomas-yeo.png" class="absolute left-59 top-26 rounded-full w-20 object-cover border-4 border-gray-400 bg-lime-400 shadow-lg">
  <img src="./assets/Maria-Di-Biase.png" class="absolute left-96 top-6 rounded-full w-20 object-cover border-4 border-gray-400 bg-lime-400 shadow-lg">
  <img src="./assets/Helen-Zhou.jpg" class="absolute left-91.5 top-36.5 rounded-full w-20 object-cover border-4 border-gray-400 bg-lime-400 shadow-lg">
  <img src="./assets/Christopher-Chen.png" class="absolute left-53 top-75 rounded-full w-20 object-cover border-4 border-gray-400 bg-amber-400 shadow-lg">
  <img src="./assets/hongwei.png" class="absolute left-136 top-75.2 rounded-full w-20 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/aihuiping.png" class="absolute left-98 top-88 rounded-full w-17 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/aaron.png" class="absolute left-171 top-27 rounded-full w-18 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/dimitri.jpg" class="absolute left-125.5 top-56.2 rounded-full w-16 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/Richard-Bethlehem.jpg" class="absolute left-148 top-45 rounded-full w-21 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/hamid.jpeg" class="absolute left-177 top-64 rounded-full w-15 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/rob.jpeg" class="absolute left-47 top-55 rounded-full w-15 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/Jakob.jpg" class="absolute left-95 top-65 rounded-full w-15 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/vanessa.jpeg" class="absolute left-119 top-30 rounded-full w-14 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/niousha.jpeg" class="absolute left-76 top-89 rounded-full w-16 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/tianfang.avif" class="absolute left-83.5 top-115 rounded-full w-16 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/shaoshi.jpg" class="absolute left-78 top-12 rounded-full w-13 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">
  <img src="./assets/yichi.jpeg" class="absolute left-68 top-67 rounded-full w-11 object-cover border-4 border-gray-400 bg-violet-300 shadow-lg">

</div>

<img src="./assets/NUS-logo.png" v-click="[1,2]" class="absolute top-27 left-149 h-1/8 p-2" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
<div class="absolute top-46 left-141 w-35 text-primary font-size-3" v-click="[1,2]" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
  B.T. Thomas Yeo, <br/>
  Christopher Chen, <br/>
  Aihuiping Xue, <br/>
  Shaoshi Zhang, <br/>
  Joanna Chong, <br/>
  Zhang Yichi, <br/>
  Eric Ng, <br/>
  Teng Yinghui
</div>
<div class="absolute top-46 left-169 w-35 text-primary font-size-3" v-click="[1,2]" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
  Juan Helen Zhou, <br/>
  Hongwei Yan, <br/>
  Chen Zhang, <br/>
  Tian Fang, <br/>
  Niousha Dehestani, <br/>
  Ji Fang, <br/>
  Xing Qian, <br/>
</div>

<img src="./assets/nuhs-logo.png" v-click="[1,2]" class="absolute top-82 left-145 h-1/6 p-2" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
<div class="absolute top-103 left-143 w-35 text-primary font-size-3" v-click="[1,2]" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
  N. Venketasubramanian, <br/>
  Eddie Chong <br/>
</div>


<img src="./assets/unimelb-logo.png" v-click="[1,2]" class="absolute top-27 left-190 h-1/8 p-2" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
<div class="absolute top-46 left-203 w-35 text-primary font-size-3" v-click="[1,2]" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
  Andrew Zalesky, <br/>
  Maria Di Biase, <br/>
  Vanessa Cropley
</div>

<img src="./assets/florey-logo.png" v-click="[1,2]" class="absolute top-60 left-197 h-1/8 p-2" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
<div class="absolute top-75 left-203 w-35 text-primary font-size-3" v-click="[1,2]" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
  Robert E. Smith
</div>

<img src="./assets/CHOP-logo.png" v-click="[1,2]" class="absolute top-78 left-187 h-1/8 p-2" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
<div class="absolute top-94 left-198 w-35 text-primary font-size-3" v-click="[1,2]" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
  Aaron Alexander-Bloch, <br/>
  Jakob Seidlitz
</div>



<img src="./assets/epfl-logo.png" v-click="[1,2]" class="absolute top-111 left-130 h-1/8 p-2" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
<div class="absolute top-115 left-156 w-35 text-primary font-size-3" v-click="[1,2]" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
  Dimitri Van De Ville, <br/>
  Hamid Behjat
</div>

<img src="./assets/Cambridge-Logo.svg" v-click="[1,2]" class="absolute top-95 left-190 h-1/4 p-2" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
<div class="absolute top-118 left-198 w-35 text-primary font-size-3" v-click="[1,2]" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
  Richard Bethlehem
</div>


<div class="absolute top-50 left-0 w-full text-primary font-size-20 text-center" v-click="2" v-motion :initial="{ scale: 0.1 }" :enter="{ scale: 1 }" :leave="{ scale: 0.1 }">
  Thank You! <br/>
</div>

<myFooter />


---
layout: default
transition: slow-fade
---

# Clinical application in AD

👤 Individual-level assessments

<ul class="absolute text-5" v-click="[1,2]" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <li class="flex gap-2 pb-2" v-click="[1,2]">
    <div class="text-cyan-500" v-click="[1,2]" v-motion :initial="{ rotate: -200 }" :enter="{ rotate: 0 }" :leave="{ rotate: 200 }"><carbon:send /></div>
    <div>Probing inter-individual variability in atrophy:</div>
  </li>
</ul>

<div v-click="[1,2]" class="absolute top-50 left-1/16 w-7/8 h-55 rounded-lg shadow-lg" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <img src="./assets/individual.png" class="absolute left-0 w-full p-5 top-27 -translate-y-1/2">
  <div class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1101/2025.01.16.25320639">Mansour L. et al. (2025)</a></div>
</div>

<ul class="absolute text-5" v-click="[2,3]" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <li class="flex gap-2 pb-2" v-click="2">
    <div class="text-cyan-500" v-click="[2,3]" v-motion :initial="{ rotate: -200 }" :enter="{ rotate: 0 }" :leave="{ rotate: 200 }"><carbon:send /></div>
    <div>Hypothetical patterns of inter-individual variability:</div>
  </li>
</ul>

<div v-click="[2,4]" class="absolute top-45 left-1/4 w-1/2 h-70 rounded-lg shadow-lg" v-motion :initial="{ scale : 0.1, y : 0 , x : -50}" :enter="{ scale : 1, y : 0, x : 0}" :click-3="{ scale : 0.7, y : -10, x : -200 }" :leave="{ scale : 0.1, y : 0, x : 50}">
  <img src="./assets/variability.png" class="absolute left-0 w-full p-5 top-35 -translate-y-1/2">
  <div v-click="[2,3]" class="absolute right-3 bottom--7 text-teal-500"><a href="https://doi.org/10.1101/2025.01.16.25320639">Mansour L. et al. (2025)</a></div>
  <div v-click="3" class="absolute top-5 left-7 w-2/3 h-55 bg-white opacity-60"></div>
</div>

<ul class="absolute text-5" v-click="[3,4]" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <li class="flex gap-2 pb-2" v-click="3">
    <div class="text-cyan-500" v-click="[3,4]" v-motion :initial="{ rotate: -200 }" :enter="{ rotate: 0 }" :leave="{ rotate: 200 }"><carbon:send /></div>
    <div>Empirical variability in clinical data:</div>
  </li>
</ul>

<div v-click="[3,8]" class="absolute top-20 left-1/2 w-2/5 h-102 rounded-lg shadow-lg"  v-motion :initial="{ scale : 0.1, y : 0 , x : -50}" :enter="{ scale : 1, y : 0, x : 0}" :click-4="{ scale : 0.5, y : 40, x : -470 }" :leave="{ scale : 0.1, y : 0, x : 50}">
  <img src="./assets/empirical.png" class="absolute left-0 w-full p-5 top-50 -translate-y-1/2">
  <div v-click="4" class="absolute top-0 left-0 w-full h-full bg-white opacity-80"></div>
</div>

<ul class="absolute text-5" v-click="[4,8]" v-motion :initial="{ x: -50}" :enter="{ x : 0}" :leave="{ x : 50}">
  <li class="flex gap-2 pb-2" v-click="4">
    <div class="text-cyan-500" v-click="[4,5]" v-motion :initial="{ rotate: -200 }" :enter="{ rotate: 0 }" :leave="{ rotate: 200 }"><carbon:send /></div>
    <div>Individual heterogeneity <br/>landscape in AD:</div>
  </li>
</ul>

<div v-click="[4,8]" class="absolute top-23 left-16/40 w-11/20 h-103 rounded-lg shadow-lg" v-motion :initial="{ scale : 0.1, y : 0 , x : -50}" :enter="{ scale : 1, y : 0, x : 0}" :leave="{ scale : 0.1, y : 0, x : 50}">
  <img src="./assets/heterogeneity.png" class="absolute left-0 w-full p-5 top-51 -translate-y-1/2">
  <div v-click="[4,5]" class="absolute top-1 left-4 w-27 h-70 bg-white opacity-60"></div>
  <div v-click="[4,6]" class="absolute top-1 left-99 w-30 h-100 bg-white opacity-60"></div>
  <div v-click="[4,7]" class="absolute top-70 left-4 w-95 h-30 bg-white opacity-60"></div>
  <div v-click="7" class="absolute top-1 left-99 w-30 h-100 bg-white opacity-60"></div>
  <div v-click="7" class="absolute top-1 left-4 w-95 h-70 bg-white opacity-60"></div>
</div>

<img v-click="8" src="./assets/landscape.webp" class="absolute left-1/8 w-3/4 p-5 top-1/5">


<myFooter />

