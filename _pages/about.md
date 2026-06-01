---
layout: about
title: about
permalink: /
subtitle: Instructor of Medicine, Dana-Farber Cancer Institute

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info:

selected_papers: false # rendered manually in the body below so Funding can sit beneath it
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # news section removed
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  /* keep the headshot modest so it balances a short bio (no big white gap) */
  .profile { max-width: 168px; margin-top: -1.75rem; }
  .profile img { width: 100%; height: auto; }
</style>

My research is at the interface of genomics, machine learning, and network biology. I often combine tools from these disciplines to address fundamental questions about the functioning of biological systems. I develop open-source, parallel software that leverages high-dimensional biological data to model regulatory genomics, small molecule dynamics, and metabolism in time and space.

<div style="clear: both;"></div>

<div style="display:flex; flex-wrap:wrap; gap:1rem; margin:0.5rem 0 2.25rem;">
  <div style="flex:1 1 230px; background:rgba(77,171,247,0.10); border:1px solid rgba(77,171,247,0.28); border-radius:12px; padding:1rem 1.25rem;">
    <h3 style="margin:0 0 .5rem; color:#1c7ed6;">Biology</h3>
    <ul style="margin:0; padding-left:1.1rem; line-height:1.6;">
      <li>Metabolic modeling in time and space</li>
      <li>Gene regulatory networks</li>
      <li>Protein&ndash;protein interactions</li>
      <li>Kidney cancer</li>
      <li>Pharmacogenomics</li>
    </ul>
  </div>
  <div style="flex:1 1 230px; background:rgba(47,158,68,0.10); border:1px solid rgba(47,158,68,0.28); border-radius:12px; padding:1rem 1.25rem;">
    <h3 style="margin:0 0 .5rem; color:#2f9e44;">Methods</h3>
    <ul style="margin:0; padding-left:1.1rem; line-height:1.6;">
      <li>Optimization (linear &amp; dynamic programming)</li>
      <li>High-dimensional statistics</li>
      <li>Machine learning</li>
      <li>Recommender systems</li>
      <li>Graphs &amp; hypergraphs</li>
    </ul>
  </div>
  <div style="flex:1 1 230px; background:rgba(151,117,250,0.10); border:1px solid rgba(151,117,250,0.28); border-radius:12px; padding:1rem 1.25rem;">
    <h3 style="margin:0 0 .7rem; color:#7048e8;">Frameworks</h3>
    <div style="display:flex; flex-wrap:wrap; gap:.4rem;">
      <span style="background:rgba(151,117,250,0.16); border:1px solid rgba(151,117,250,0.32); border-radius:999px; padding:.25rem .7rem; font-size:.9rem;">Django</span>
      <span style="background:rgba(151,117,250,0.16); border:1px solid rgba(151,117,250,0.32); border-radius:999px; padding:.25rem .7rem; font-size:.9rem;">Pydantic</span>
      <span style="background:rgba(151,117,250,0.16); border:1px solid rgba(151,117,250,0.32); border-radius:999px; padding:.25rem .7rem; font-size:.9rem;">DSPy</span>
      <span style="background:rgba(151,117,250,0.16); border:1px solid rgba(151,117,250,0.32); border-radius:999px; padding:.25rem .7rem; font-size:.9rem;">Vector database</span>
      <span style="background:rgba(151,117,250,0.16); border:1px solid rgba(151,117,250,0.32); border-radius:999px; padding:.25rem .7rem; font-size:.9rem;">Bootstrap</span>
      <span style="background:rgba(151,117,250,0.16); border:1px solid rgba(151,117,250,0.32); border-radius:999px; padding:.25rem .7rem; font-size:.9rem;">Nextflow</span>
      <span style="background:rgba(151,117,250,0.16); border:1px solid rgba(151,117,250,0.32); border-radius:999px; padding:.25rem .7rem; font-size:.9rem;">JupyterHub</span>
    </div>
  </div>
</div>

## Selected publications

<div class="publications">

{% bibliography --query @*[selected=true] --group_by none %}

</div>

<div style="height: 2.75rem;"></div>

## Funding & support

<div class="funding-logos" style="display:flex; flex-wrap:wrap; gap:2.5rem; align-items:center; margin-top:1.5rem;">
  <a href="https://www.nih.gov/" target="_blank" rel="noopener noreferrer" title="National Institutes of Health">
    <img src="/assets/img/funding/nih.png" alt="National Institutes of Health (NIH)" style="height:64px; width:auto;" loading="lazy">
  </a>
  <a href="https://aws.amazon.com/" target="_blank" rel="noopener noreferrer" title="Amazon Web Services">
    <img src="/assets/img/funding/aws.png" alt="Amazon Web Services (AWS)" style="height:52px; width:auto;" loading="lazy">
  </a>
  <a href="https://phylo.bio/" target="_blank" rel="noopener noreferrer" title="Phylo">
    <img src="/assets/img/funding/phylo.png" alt="Phylo" style="height:58px; width:auto;" loading="lazy">
  </a>
</div>

<div style="height: 2.75rem;"></div>
