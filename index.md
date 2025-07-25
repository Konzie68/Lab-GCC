---
---

# GDS@GCC by the Fuller Lab

[Lab Website Template](https://github.com/greenelab/lab-website-template) is an easy-to-use, flexible website template for [labs](https://www.greenelab.com/).  
Spend less time managing your website and more time advancing genomic data science.

{%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}

{%
  include button.html
  type="github"
  text="On GitHub"
  link="greenelab/lab-website-template"
%}

{% include section.html %}

## Highlights

{%
  capture text
%}
Our lab is exploring the use of cloud computing in genomic data science.  
We use open source data to make new discoveries in gene expression across diverse organisms.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{%
  endcapture
%}

{%
  include feature.html
  image="images/research.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{%
  capture text
%}
Currently, our lab is working on two projects.  
In collaboration with Dr. Deidre Anglin (CCNY), we are exploring gene expression signatures as a marker for social determinants of health.  
Our second project focuses on gene discovery in urban soil samples.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{%
  endcapture
%}

{%
  include feature.html
  image="images/projects.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{%
  capture text
%}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{%
  endcapture
%}

{%
  include feature.html
  image="images/team.jpg"
  link="team"
  title="Our Team"
  text=text
%}
