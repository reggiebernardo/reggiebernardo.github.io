---
layout: default
# Keys from mycv/own-bib.bib, rendered via _data/bibliography.yml (regenerate with `ruby _scripts/bib_to_data.rb`)
selected_papers:
  - Bernardo:2026opv
  - Bernardo:2025srg
  - Bernardo:2024bdc
  - Bernardo:2023pwt
  - Bernardo:2021cxi
# Previous selection, kept for reference:
#  - Bernardo:2022xzl
#  - Bernardo:2023pwt
#  - Appleby:2022bxp
#  - Bernardo:2021cxi
#  - Bernardo:2021vsj
---

### Interests (astro-ph.CO/astro-ph.HE/gr-qc)
**Gravitational Waves, Gravity, Cosmology**, Machine Learning, Data Analysis, Dark Energy
  
### Highlights
Codes: <br />
- [`PTAfast`: PTA correlations from stochastic gravitational wave background](http://ascl.net/code/v/3451) <br />
- [`cosmo-learn`: code for learning cosmology using different methods and mock data](https://github.com/reggiebernardo/cosmo_learn) <br />
- [`gp6`: Gaussian Processes for Physics - designed for late time cosmology with noisy & correlated data](https://github.com/reggiebernardo/gp6) <br />

Selected Papers: <br />
{% include selected_papers.html %}
  
Full publication list at [Inspire HEP](https://inspirehep.net/authors/1758391), [ORCID](https://orcid.org/0000-0001-8589-6851), and [Google Scholar](https://scholar.google.com/citations?user=qoDKcvQAAAAJ&hl=en), or [my CV](./mycv/main.pdf). <br />

<html>
<head>
  <meta charset="utf-8">
  <title>Slideshow</title>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.min.js"></script>
  <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.min.css"/>
  <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick-theme.min.css"/>
  <style>
    .slide-container {
      margin: auto;
      width: 80%;
    }
    .slide-container img {
      width: 100%;
    }
    .slick-prev:before, .slick-next:before {
      color: black;
    }
  </style>
</head>
<body>
  <div class="slide-container">
    <div class="slide">
      <div>
        <!-- <img src="/assets/img/bin_variance_bestfit.png" alt="Image 1"> -->
        <img src="/assets/img/bin_variance_bestfit.png" alt="Binned timing-residual variance of a pulsar timing array compared with the best-fit stochastic gravitational wave background signal">
        <div class="slick-caption"><center>Signal of a stochastic gravitational wave background in the timing residuals in a pulsar timing array (arXiv:2409.01218)</center></div>
      </div>
      <div>
        <!-- <img src="/assets/img/hdlowangle-1_orig.png" alt="Image 2"> -->
        <img src="/assets/img/hdlowangle-1_orig.png" alt="Inter-pulsar correlation curve induced by a stochastic gravitational wave background, with cosmic variance">
        <div class="slick-caption"><center>SGWB-induced inter-pulsar correlations with cosmic variance (arXiv:2209.14834)</center></div>
      </div>
      <div>
        <!-- <img src="/assets/img/hz-gp_orig.png" alt="Image 3"> -->
        <img src="/assets/img/hz-gp_orig.png" alt="Hubble expansion rate reconstructed from observational data with Gaussian processes">
        <div class="slick-caption"><center>Hubble expansion rate reconstructed from observational data via Gaussian Processes (arXiv:2105.12970)</center></div>
      </div>
      <div>
        <!-- <img src="/assets/img/ht-wt_orig.png" alt="Image 4"> -->
        <img src="/assets/img/ht-wt_orig.png" alt="Hubble rate evolution in a well-tempered cosmology reaching the same de Sitter final state from different initial conditions">
        <div class="slick-caption"><center>Well tempering: a de Sitter final state independent of the initial conditions and the CC (arXiv:2107.08762)</center></div>
      </div>
    </div>
  </div>
  <script>
    $(document).ready(function(){
      $('.slide').slick({
        dots: true,
        arrows: false
      });
      $('.prev-button').on('click', function(){
        $('.slide').slick('slickPrev');
      });
      $('.next-button').on('click', function(){
        $('.slide').slick('slickNext');
      });
    });
  </script>
</body>
</html> <br />

### Research Statement

I study what the nanohertz gravitational wave sky and the timing of pulsars can tell us about gravity and the Universe. A pulsar timing array turns the Galaxy into a gravitational wave detector, but a faint correlated signal buried in irregular timing data is only as trustworthy as our understanding of the processes that shape the data. My work addresses both sides of this problem: how gravity and cosmology imprint themselves on the correlations between pulsars, and how the stochastic behavior of the pulsars themselves must be modeled before a signal can be claimed.

My path to this question went through gravity and cosmology. I started with theories of gravity beyond general relativity, studying self-tuning and well-tempered cosmologies and black holes and their perturbations in Horndeski theories, and then turned to data-driven reconstructions of the expansion history with Gaussian processes and approximate Bayesian computation. These threads share one habit and asks what a model predicts, then what the data can actually support. Pulsar timing arrays are a natural place to apply it, because the cosmology lives in the correlations and the statistics are the experiment.

In pulsar timing, my work has followed the signal from prediction to test: inter-pulsar correlations beyond the Hellings-Downs curve, including non-Einsteinian polarizations; the pulsar and cosmic variances of these correlations; simulations of Gaussian background signals; and tests of whether the background is Gaussian. More recently I have turned to the pulsar side, namely spin noise, stationarity, angular momentum conservation, and the non-stationarity that observations themselves induce in timing residuals. Non-stationarity is not a flaw to be hidden; it is a property of the data that has to be identified and interpreted, and it bears directly on how well arrays can separate astrophysical noise from a gravitational wave background.

A promising direction is to bring the cosmological and the pulsar sides into one statistical framework, so that a detection, a non-detection, and a test of gravity all rest on the same model of the data. I also develop open-source tools for this work, such as `PTAfast` and `cosmo-learn`, and I enjoy mentoring students who are learning to do the same.


### Leadership and Service
- **Organizing**: Scientific Organizing Committee of [AGWAM-2026](https://indico.narit.or.th/e/agwam2026) (Chiang Mai, Thailand), the [APCTP Workshop on Gravitational Waves 2025](https://phys.ncts.ntu.edu.tw/en/act/Conferences/APCTP-Workshop-on-Gravitational-Waves-2025-51414941) (Taipei, Taiwan), and [CoMaDS 2025](https://comads.science.upd.edu.ph/) (Aklan, Philippines); organizer of the HEP Seminar and HEP Journal Club at the Institute of Physics, Academia Sinica (2022--2023) <br />
- **Mentoring**: co-advised or mentored students and interns from BS to PhD level <br />


### Experience
- **Senior Scientist**, [Max Planck Institute for Gravitational Physics (Albert Einstein Institute)](https://www.aei.mpg.de/obs-rel-cos), D-30167 Hannover, Germany, Jul. 2026 – present <br />
- **Postdoc/Junior Scientist**, [Max Planck Institute for Gravitational Physics (Albert Einstein Institute)](https://www.aei.mpg.de/obs-rel-cos), D-30167 Hannover, Germany, May 2025 – Jul. 2026 <br />
- **Visiting Scientist**, [Institute of Physics, Academia Sinica](https://www.phys.sinica.edu.tw/index.php), Taipei 11529, Taiwan, Mar. 2025 – May 2025 <br />
- **Postdoctoral Fellow**, [Asia Pacific Center for Theoretical Physics](https://www.apctp.org/), Pohang 37673, Republic of Korea, Nov. 2023 – Mar. 2025 <br />
- **Postdoctoral Fellow**, [Institute of Physics, Academia Sinica](https://www.phys.sinica.edu.tw/index.php), Taipei 11529, Taiwan, Oct. 2021 – Oct. 2023 <br />
- **Assistant Professor**, [National Institute of Physics, University of the Philippines](http://nip.upd.edu.ph/) Diliman, Quezon City 1101, Philippines, Feb. 2021 – Aug. 2021 <br />
- **Instructor**, National Institute of Physics, University of the Philippines Diliman, Quezon City 1101, Philippines, Aug. 2015 – Jul. 2020
  
### Education: [University of the Philippines](https://up.edu.ph/) Diliman, Quezon City 1101, Philippines
- **PhD Physics**, *Most Outstanding Ph.D.*, Aug. 2017 – Jul. 2020 <br />
- MS Physics, *Most Outstanding M.S.*, Aug. 2015 – Jun. 2017 <br />
- BS Physics, *Magna Cum Laude, Best Thesis*, Jun. 2010 – Jun. 2015 <br />

### Awards
- **Most Outstanding Ph.D. Graduate**, **Edgardo Gomez Award for Outstanding Ph.D. Graduate**, and **Excellence in Graduate Studies**, College of Science, University of the Philippines Diliman, 2020 <br />
- Most Outstanding M.S. Graduate, College of Science, University of the Philippines Diliman, 2017 <br />
- Gawad Direktor bilang Natatanging Guro sa Laboratorio, National Institute of Physics, 2016 <br />
- Leticia Shahani Award for Best Undergraduate Thesis and Magna Cum Laude, College of Science, University of the Philippines Diliman, 2015 <br />
- Jose Maria Feliciano Undergraduate Scholar (2012 – 2015); College and University Scholar (2010 – 2015)


### Miscellaneous
Languages: English (fluent), Filipino (mother tongue) <br />
Coding: Command Line, Python, Mathematica, LaTeX

### Community Involvement
Referee: PRL, PRD, JCAP, CQG, Phys. Dark Universe, EPJC, Astron. Comput., MNRAS, ApJ, MPLA, Chinese J. Phys., Sci. Rep., GRG, JKPS, Proceedings of the Physics Society of the Philippines, Philippine Journal of Science

Editor: [Proceedings of the Physics Society of the Philippines](https://proceedings.spp-online.org)

Member: [CosmoVerse COST Action](https://cosmoversetensions.eu)---Data Analysis and Fundamental Physics Working Groups; [SKAO](https://www.skao.int/en/science-users/science-working-groups)---Pulsars and Cosmology Science Working Groups

