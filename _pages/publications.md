---
layout: archive
title:  "Research"
permalink: /publications/
author_profile: true
---


## Working papers

<div class="paper">
  <h3><strong>Do I Really Want to Buy This? Preference Discovery and Consumer Search</strong></h3>
  <p>Joint with Tobias Klein and Christoph Walsh. <a href="https://www.dropbox.com/scl/fi/otgsnm4pnp4o7fch87wbr/JMP_TZhang.pdf?rlkey=fu5pjctjg25bvrdnclejxhuj1&st=uhbzujur&dl=0&raw=1" target="_blank">[PDF]</a></p>
  <button onclick="toggleAbstract(this)">Show Abstract</button>
  <div class="abstract" style="display:none; margin-top:10px;">
    <p>One of the most invoked assumptions in economics is that consumers know their preferences when making choices. Although theories and experiments in psychology and behavioral economics suggest that this may be unrealistic, there is relatively little evidence from the field on this question. In this paper, we use detailed clickstream data from a large Central Asian online platform to study the extent to which consumers learn about their preferences while searching for a smartphone. To quantify the speed at which this takes place and account for other factors, most notably that consumers obtain additional product information when they inspect product pages, we estimate a rich search model in which consumers learn about their willingness to pay each time they visit the checkout page. Consumers initially underestimate their price sensitivity and update it along the way. Taking this into account shows that consumers are more price sensitive than a standard search model would predict, and an intervention that prompts consumers to end their search early can lead to potential welfare loss.</p>
    <p><strong>Selected presentations:</strong> SEG Tilburg; Tilburg-Rotterdam WDM 2024; EMAC Doctoral Colloquium 2025 (Madrid, scheduled); ISMS 2025 (Washington DC, scheduled); 14th Consumer Search and Switching Cost Workshop (Hong Kong, scheduled).</p>
  </div>
</div>

<div class="paper">
  <h3><strong>Estimating Sequential Search Models Based on a Partial Ranking Representation</strong></h3>
  <p><a href="https://arxiv.org/abs/2501.07514" target="_blank">[arXiv]</a> <a href="https://www.dropbox.com/scl/fi/1fusn7428ic8kp92cle4b/Partial_Ranking.pdf?rlkey=k9yj6yoztjrdgql0i3q02vo1r&st=al70cchc&dl=0&raw=1" target="_blank">[Most Recent Version]</a></p>
  <button onclick="toggleAbstract(this)">Show Abstract</button>
  <div class="abstract" style="display:none; margin-top:10px;">
    <p>Consumers are increasingly shopping online, and the availability of datasets documenting consumer search behavior continues to expand. While sequential search models provide a structured framework for analyzing such data, they pose significant empirical challenges. The existing literature often characterizes step-by-step optimality in sequential search models using Optimal Search Rules, but these rules rely on unobserved search outcomes, making estimation computationally intensive due to the need to solve or simulate high-dimensional integrals. This paper introduces a new representation that reformulates a broad class of sequential search models as an equivalent partial ranking of available actions. This reformulation yields a decomposable joint probability expression and enables more general identification arguments. Building on this representation, we develop an improved GHK-style likelihood estimator that is easy to implement, robust to incomplete search process data, and flexible enough to accommodate a wide range of empirical model extensions, including those featuring product discovery. Our approach provides a practical and efficient tool for researchers and practitioners.</p>
    <p><strong>Selected presentations:</strong> SEG Tilburg</p>
  </div>
</div>

## Work in Progress

<div class="paper">
  <h3><strong>Higher Price, Better Quality? Resolve the Endogeneity in Search Decisions</strong></h3>
  <button onclick="toggleAbstract(this)">Show Abstract</button>
  <div class="abstract" style="display:none; margin-top:10px;">
    <p>Consumers typically search before making a purchase to resolve product uncertainty under imperfect information. A key factor driving their search decisions is their private evaluation of the product. However, this evaluation often exhibits an endogenous relationship with price, as consumers tend to associate higher prices with better quality. This creates endogeneity between search decisions and product prices beyond the consumer's price sensitivity in purchase. I developed a novel econometric method demonstrating how using instrumental variables can address this endogeneity, enabling accurate estimation of consumers' preferences in purchase.</p>
  </div>
</div>

<script>
function toggleAbstract(button) {
  var abstractDiv = button.nextElementSibling;
  if (abstractDiv.style.display === "none") {
    abstractDiv.style.display = "block";
    button.textContent = "Hide Abstract";
  } else {
    abstractDiv.style.display = "none";
    button.textContent = "Show Abstract";
  }
}
</script>

<style>
.paper {
  margin-bottom: 30px;
  padding-bottom: 15px;
  border-bottom: 1px solid #ccc;
}
button {
  margin-top: 5px;
  padding: 4px 10px;
  font-size: 0.9rem;
  cursor: pointer;
  background-color: #f0f0f0;
  border: 1px solid #aaa;
}
button:hover {
  background-color: #e0e0e0;
}
</style>
