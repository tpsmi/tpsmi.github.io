---
layout: post
title: An open-access and fully searchable dataset of the  Illustrated London News (1842-1889)
date: 2024-01-27 07:59:00-0400
inline: false
related_posts: false
---

We’re excited to present the initial results of our <a href="https://tpsmi.github.io/news/announcement_3/">2023 Patrick Leary Field Development Grant</a> this week at #RSVP2024! After annotating 908 pages, we fine-tuned an object detection model (YoloV8) that can identify illustrations on scanned pages with high accuracy (mAP50 = 0.964).

Using this model, we extracted 140,351 illustrations from the Illustrated London News (1842-1889) and four other well-known British illustrated periodicals: The Graphic, Illustrated Times, Pictorial Times, and Illustrated Weekly News (see the table below).

<div class="container text-center"> <!-- Center the content -->
    <div class="row mt-3">
        <div class="col-sm mt-3 mt-md-0">
            <div class="d-flex justify-content-center"> <!-- Center the image -->
                {% include figure.html path="assets/img/table.png" class="img-fluid rounded z-depth-1" style="max-width: 50%; height: auto;" %}
            </div>
        </div>
    </div>
    <div class="caption mt-3">
       Table
    </div>
</div>

Employing the OpenCLIP AI model, we extracted multimodal embeddings from these images, making them fully searchable with both textual and visual queries. For instance, users can easily find illustrations of railway accidents using the prompt ‘an illustration of a railway accident’ or images of the British parliament using a modern photograph. The embeddings can also be used to cluster all the images of the ILN, identifying various portraits of different types of men or all the maps published by the British periodical (see below).

In the coming months, we will expand the dataset to include well-known European and American titles. We will release the code, full dataset, and multimodal embeddings as open access in the fall of 2024.

We hope this dataset will be valuable to scholars of the nineteenth century and its press. Please get in touch if you are interested in working with our data and multimodal embeddings. We plan to organize several online meetings and an in-person workshop in the summer of 2025 to familiarize interested scholars with the data and associated methods.

<div class="container text-center"> <!-- Center the content -->
    <div class="row mt-3">
        <div class="col-sm mt-3 mt-md-0">
            <div class="d-flex justify-content-center"> <!-- Center the image -->
                {% include figure.html path="assets/img/maps.png" class="img-fluid rounded z-depth-1" style="max-width: 50%; height: auto;" %}
            </div>
        </div>
    </div>
    <div class="caption mt-3">
       maps
    </div>
</div>

<div class="container text-center"> <!-- Center the content -->
    <div class="row mt-3">
        <div class="col-sm mt-3 mt-md-0">
            <div class="d-flex justify-content-center"> <!-- Center the image -->
                {% include figure.html path="assets/img/portraits.png" class="img-fluid rounded z-depth-1" style="max-width: 50%; height: auto;" %}
            </div>
        </div>
    </div>
    <div class="caption mt-3">
       Portraits
    </div>
</div>
