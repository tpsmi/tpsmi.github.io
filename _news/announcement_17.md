---
layout: post
title: Open-access and AI-powered dataset of 72,000 illustrations from the Illustrated London News (1842-1890)
date: 2025-01-05 07:59:00-0400
inline: false
related_posts: false
---

🚀📈 Making Victorian visual culture searchable: Introducing an open-access and AI-powered dataset of 72,000 illustrations from the Illustrated London News (1842-1890)

Along with my colleagues Bethany Warner, Paul Fyfe, and Benjamin Charles Germain Lee, we extracted 72,000 illustrations from the Illustrated London News (1842-1890). Using multimodal AI, we've developed a new way to make these images accessible to researchers.

Our Flask application (demo below) allows users to use both textual and visual queries to search the 72,000 images. For example, using the query 'steamship' results in images of steamships. However, the multimodal AI can retrieve images of far more complex subjects.

Try searching for:
"Queen Victoria"
"Victorian horse races"
"19th century battlefields"
"Victorian romance scenes"
"New York"
"Big Ben"

The AI can connect complex visual and textual concepts, making it possible to discover illustrations that traditional keyword searches would surely miss. Each result links back to the original page in the Illustrated London News hosted on the Internet Archive.

Want to explore the dataset yourself? Read our paper in the <a href="https://openhumanitiesdata.metajnl.com/articles/10.5334/johd.284"> Journal of Open Humanities Data </a>

Code:
-<a href="https://github.com/tpsmi/multimodaliln">Extraction</a>
-<a href="https://github.com/tpsmi/ilnmultimodalsearch">Flask APP</a>


Please get in touch if you have any feedback!

<div class="container text-center"> <!-- Center the content -->
    <div class="row mt-3">
        <div class="col-sm mt-3 mt-md-0">
            <div class="d-flex justify-content-center"> <!-- Center the image -->
                {% include figure.html path="assets/img/textsearch.png" class="img-fluid rounded z-depth-1" style="max-width: 50%; height: auto;" %}
            </div>
        </div>
    </div>
    <div class="caption mt-3">
       Text search
    </div>
</div>