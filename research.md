---
layout: default
# Keys from mycv/own-bib.bib, rendered via _data/bibliography.yml (regenerate with `ruby _scripts/bib_to_data.rb`)
selected_papers:
  - Bernardo:2022xzl
  - Bernardo:2023pwt
  - Appleby:2022bxp
  - Bernardo:2021cxi
  - Bernardo:2021vsj
---

### Interests (astro-ph.CO/gr-qc)
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
        <img src="/assets/img/bin_variance_bestfit.png" alt="Image 1">
        <div class="slick-caption"><center>Signal of a stochastic gravitational wave background in the timing residuals in a pulsar timing array (arXiv:2409.01218)</center></div>
      </div>
      <div>
        <img src="/assets/img/hdlowangle-1_orig.png" alt="Image 2">
        <div class="slick-caption"><center>SGWB-induced inter-pulsar correlations with cosmic variance (arXiv:2209.14834)</center></div>
      </div>
      <div>
        <img src="/assets/img/hz-gp_orig.png" alt="Image 3">
        <div class="slick-caption"><center>Hubble expansion rate reconstructed from observational data via Gaussian Processes (arXiv:2105.12970)</center></div>
      </div>
      <div>
        <img src="/assets/img/ht-wt_orig.png" alt="Image 4">
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

The current state of cosmology is characterized by a need for new theories and models that can address fundamental questions such as the nature of dark energy and the Hubble tension. I am passionate about exploring alternative theories of gravity that can shed light on these cosmic puzzles. My research focuses on the development of novel models that incorporate irreplaceable features of general relativity, such as gravitational waves, while also making testable astrophysical and cosmological predictions. <br />

I am fascinated by the nanohertz regime for gravitational wave detection, which has the potential to reveal exotic phenomena such as cosmic strings and phase transitions. Additionally, I am interested in the applications of machine learning in cosmology and have been exploring the use of these techniques to analyze large datasets and extract meaningful insights. <br />

My research objectives include identifying interdisciplinary connections between cosmology and other areas of science, staying up-to-date with the latest research in my areas of interest, and collaborating with others to broaden my scope and produce more impactful research. <br />

Overall, my goal is to contribute to the paradigm shift in cosmology by developing new theories and models that can address the fundamental questions and puzzles of the field.

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

### Miscellaneous
Languages: English (fluent), Filipino (mother tongue) <br />
Coding: Command Line, Python, Mathematica, LaTeX

### Community Involvement
Referee: PRL, PRD, JCAP, CQG, Phys. Dark Universe, EPJC, Astron. Comput., MNRAS, ApJ, MPLA, Chinese J. Phys., Sci. Rep., GRG, JKPS, Proceedings of the Physics Society of the Philippines, Philippine Journal of Science

Editor: [Proceedings of the Physics Society of the Philippines](https://proceedings.spp-online.org)

Member: [CosmoVerse COST Action](https://cosmoversetensions.eu)---Data Analysis and Fundamental Physics Working Groups; [SKAO](https://www.skao.int/en/science-users/science-working-groups)---Pulsars and Cosmology Science Working Groups

