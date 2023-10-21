---
layout: page
title: Framework for EPS data
description: An Analytical Framework to classify patients suffereing from Schizophrenia
img: assets/img/schizophrenia.jpg
importance: 1
category: work
---


## Back story

The mental disorders are one of the major diseases that needs some attention. The patients suffering from various diseases like schizophrenia, psychotic disorders, autism, etc. need therapy and better treatment.

## Development

We then gave a thought of developing an integrated platform for both the patients and the doctors, where they can:
* Have an assesment for the mental state.
* Meet and interact with people with similar mental states.
* Doctors can prescribe the medicines for the patients.
* Have one-to-one interaction with doctors.
* Track the medication used.

These being the primary features, we embedded AI techniques to enhance them. 
* The assesments are checked and the medication is prescribed accordingly.
* Remainders for medicines to be taken at specific times.

## Success of the project

The project is in progress and an application for the same has been developed by muy senior `Gautam Jain`. We are looking into the issues and are trying to make it more user-friendly.

## Tech stack

This project was a combination of our skills from web development, networking, and artificial intelligence. We followed `agile` approach where we added new features (*use cases*) in interative manner. Of course, we couldn't leave the use-case diagrams, the sequence diagrams, etc.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/scis_forum_usecase.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The application's use case diagram.
</div>

We used:
* `Python` as our primary programming language.
* `Flask` framework to develop the backend.
* `Javascript` to add assesment feature and to make the application a bit-more interactive.
* `SQLite` database as supported by Flask. 
* `scikit-learn` to build a model that checks the assesment.
* `Jinja` for frontend.