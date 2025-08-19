---
layout: home
# title: Home
# navigation_weight: 1
---

<style type="text/css">
.spaced-lines {
  line-height: 20pt;
} 
</style>

<div class="content-wrapper">
  <div class="text-column">
    {% capture text_content %}

I am a (tenure-track) Assistant Professor in the [Department of Computer Science](https://www.cs.jhu.edu/) at [Johns Hopkins University](https://www.jhu.edu/). I am affiliated with the [Data Science and AI Institute](https://ai.jhu.edu/) and the [Center for Computational Biology](https://ccb.jhu.edu/).

My research broadly focuses on developing machine learning methods for addressing fundamental problems in biology. I am particularly interested in developing spatiotemporal and graph-based models for next-generation biological technologies. Please see my [group website](https://chitra-lab.github.io/) for details.

I was previously a postdoctoral fellow at the [Eric and Wendy Schmidt Center](https://www.ericandwendyschmidtcenter.org/) at the [Broad Institute of MIT and Harvard](https://www.broadinstitute.org/).
I completed my PhD in Computer Science at [Princeton University](https://www.cs.princeton.edu) where I was very fortunate to be advised by [Ben Raphael](https://www.cs.princeton.edu/~braphael/).


**Relevant links:** [CV](cv_website.pdf), [Google Scholar](https://scholar.google.com/citations?user=JPKTNnMAAAAJ&hl=en&oi=ao), [research statement](CS_statement_5_no_future_work.pdf).

**Location:** Malone Hall, Office 329, 3400 N. Charles Street, Baltimore, MD 21218

<!-- **Personal:** I like to go [<span style="color:#c869bf">bouldering</span>](http://instagram.com/uthsav_climbs/) in my free time. -->
    {% endcapture %}
    <div class="spaced-lines">
      {{ text_content | markdownify }}
    </div>
  </div>

  <div class="image-column">
    <div class="image-icon-wrapper">
      <img src="images/headshot5.png" alt="headshot" style="border: 0px solid black;">
      <div class="image-caption">
        <!-- <p>Postdoctoral Fellow, Broad Institute of MIT and Harvard</p> -->
        <p>Assistant Professor</p>
        <p>Department of Computer Science </p>
        <p>Johns Hopkins University</p>
        <!-- <p>Malone Hall, 3400 N. Charles Street, Baltimore, Maryland 21218</p> -->
        <p>Email: <a href="mailto:uthsav@jhu.edu">uthsav@jhu.edu</a></p>
      </div>
      <div class="icon-container">
        <a href="https://scholar.google.com/citations?user=JPKTNnMAAAAJ&hl=en&oi=ao" target="_blank">
          <i class="ai ai-google-scholar ai-2x"></i>
        </a>
        <a href="cv_website.pdf" target="_blank">
          <i class="ai ai-cv ai-2x"></i>
        </a>
        <a href="https://github.com/uthsavc" target="_blank">
          <i class="fab fa-github-square fa-2x"></i>
        </a>
        <a href="https://x.com/uthsavc" target="_blank">
          <i class="fab fa-twitter-square fa-2x"></i>
        </a>
        <a href="https://orcid.org/0000-0001-6016-0960" target="_blank">
          <i class="ai ai-orcid ai-2x"></i>
        </a>
        <a href="mailto:uthsav@jhu.edu" target="_blank">
          <i class="fa-solid fa-envelope fa-2x"></i>
        </a>
      </div>
    </div>
  </div>
</div>