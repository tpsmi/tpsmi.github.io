---
layout: post
title: New article on color and visual orientalism published in Nature's Humanities and Social Sciences Communications
date: 2024-10-16 07:59:00-0400
inline: false
related_posts: false
---

Excited to share that our latest article - Coloring in the world of others: color use in visual orientalism, 1890–1920 - has been published in Nature Portfolio's Humanities and Social Sciences Communications.

With Melvin Wevers, I examine the impact of media on color sense: our ability to see different colors and use them to interpret the world. Specifically, we studied the role of color in creating the “Orient” in two turn-of-the-twentieth-century types of color(ed) photographs: photochromes, where a printer added color, and autochromes, where colors were captured during exposure. While most research on Visual Orientalism has focused on content, Melvin and I applied machine learning methods to study the role of a key aesthetic feature: color. After using the K-means algorithm to extract sixteen dominant colors from ca. 18.000 photochromes and autochromes, we trained three random forest classification algorithms to make a distinction between:

• photochromes and autochromes
• photochromes of the Orient and the Occident
• autochromes of the Orient and the Occident.

While the algorithm can easily separate photochromes from autochromes (0.95) and Oriental from Occidental photochromes (0.93), it struggles with the same task in the autochrome collection (0.68).

These results lead to three key findings:

• Around 1900 color perception transitioned from a direct experience to a mediated phenomenon. Different media, such as the photochrome and autochrome, enabled diverse color palettes.
• Color as a Tool of Visual Orientalism: In photochromes, we found that the presence and absence of specific colors served as predictors of whether an image depicted the Orient or Occident. This finding underscores the role of color in constructing and reinforcing cultural stereotypes.
• Autochrome's Objectivity: Interestingly, our classifier struggled to distinguish between Oriental and Occidental scenes in autochromes, suggesting that this medium provided a more neutral representation of countries in the near and middle East than the photochrome

For those interested in diving deeper into our research, the <a href="https://www.nature.com/articles/s41599-024-03895-5">full paper is available here</a>:


Please get in touch if you have any feedback!

<div class="container text-center"> <!-- Center the content -->
    <div class="row mt-3">
        <div class="col-sm mt-3 mt-md-0">
            <div class="d-flex justify-content-center"> <!-- Center the image -->
                {% include figure.html path="assets/img/dominant.png" class="img-fluid rounded z-depth-1" style="max-width: 50%; height: auto;" %}
            </div>
        </div>
    </div>
    <div class="caption mt-3">
       Dominant colors
    </div>
</div>

<div class="container text-center"> <!-- Center the content -->
    <div class="row mt-3">
        <div class="col-sm mt-3 mt-md-0">
            <div class="d-flex justify-content-center"> <!-- Center the image -->
                {% include figure.html path="assets/img/shap.png\" class="img-fluid rounded z-depth-1" style="max-width: 50%; height: auto;" %}
            </div>
        </div>
    </div>
    <div class="caption mt-3">
       SHAP plot for the photochrome orient-occident classifier
    </div>
</div>
