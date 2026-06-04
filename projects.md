---
layout: default
title: Projects
description: Open-source conservation technology projects
---

<div class="container">
    <h2 class="section-title">Project Highlights</h2>
    <p style="text-align: center; color: #666; margin-bottom: 2rem;">
        Explore our core open-source conservation technology projects.
    </p>
    <!-- Camera traps (image on right) -->
    <section class="project-section project-section--media-right" id="animl" aria-labelledby="animl-title">
      <div class="project-media">
        <img src="/assets/images/projects/animl.jpg" alt="Camera trap image" />
      </div>
      <div class="project-text" aria-labelledby="animl-title">
        <h3 id="animl-title">AniML</h3>
        <p class="muted">
          A package available in Python and R for AI-assisted camera trap image processing.
        </p>
        <p>
          The AniML package provides functions for ingesting raw image and video files and outputs predictions for 
          species using region-specific species classifier models. We provide several species models including for the African Savanna, 
          the Peruvian Amazon, the Andes mountains, and the Western US. 
          AniML provides the results in a number of export formats, including TimeLapse and CamTrapDP. 
          The package also includes AI-based re-indentification tools and custom species model training.
        </p>
        <br>
        <p>For more information, see:<br>
        <a href="https://conservationtechlab.github.io/animl-py/">AniML (Python Package)</a><br>
        <a href="https://github.com/conservationtechlab/animl-r">AniML (R Library)</a><br>
        <a href="https://github.com/conservationtechlab/animl-lite">AniML-Lite</a><br>
        <!-- <a href="">Model Wilderness</a> -->
        </p>
      </div>
    </section>
     <!-- Re-identification (image on left) -->
    <section href="{{ '/matchypatchy' | relative_url}}" 
             class="project-section project-section--media-left" id="individual-id" aria-labelledby="individual-id-title">
      <div class="project-media">
        <img src="/assets/images/projects/matchypatchy.png" alt="MatchyPatchy Software" />
      </div>
      <div class="project-text" aria-labelledby="individual-id-title">
        <h3 id="individual-id-title">MatchyPatchy</h3>
        <p class="muted">
          A desktop application for Windows and Linux for AI-assisted re-identification of patterned animals. 
        </p>
        <p>
          MatchyPatchy ingests either raw image/video files or a .csv list of images, calculates vector embeddings of the images, and 
          presents the user with potential matches based on similarity of the vectors. MatchyPatchy can be used with a set of reference
          images of named individuals, or from scratch on a set of data where no individuals are indentified yet. 
        </p>
        <br>
        <p>
          For more information, see: <a href="https://conservationtechlab.github.io/matchypatchy/">MatchyPatchy</a><br>
        </p>
      </div>
    </section>
     <!-- SageBRUSH (image on left) -->
    <section href="{{ '/sagebrush' | relative_url}}" 
             class="project-section project-section--media-left" id="sagebrush" aria-labelledby="sagebrush-title">
      <div class="project-media">
        <img src="/assets/images/projects/sagebrush.jpg" alt="SageBRUSH Deployment" />
      </div>
      <div class="project-text" aria-labelledby="individual-id-title">
        <h3 id="individual-id-title">SageBRUSH</h3>
        <p class="muted">
          A desktop application for Windows and Linux for AI-assisted re-identification of patterned animals. 
        </p>
        <p>
          MatchyPatchy ingests either raw image/video files or a .csv list of images, calculates vector embeddings of the images, and 
          presents the user with potential matches based on similarity of the vectors. MatchyPatchy can be used with a set of reference
          images of named individuals, or from scratch on a set of data where no individuals are indentified yet. 
        </p>
        <br>
        <p>
          For more information, see: <a href="https://conservationtechlab.github.io/matchypatchy/">MatchyPatchy</a><br>
        </p>
      </div>
    </section>
<!--
    Environmental sensors (image on right) 
    <section class="project-section project-section--media-right" id="edge-ai" aria-labelledby="edge-ai-title">
      <div class="project-media">
        <img src="/assets/images/projects/sagebrush.jpg" alt="SageBRUSH" />
      </div>
      <div class="project-text" aria-labelledby="edge-ai-title">
        <h3 id="edge-ai">SageBRUSH</h3>
        <p class="muted">
          Projects focused on physical sensors and deployments: low-power environmental monitoring, data ingest and telemetry, calibration, and integration with analysis pipelines.
        </p>
        <p>
          We produce firmware examples, ingest connectors, and best-practice guides for deployments in remote locations. Emphasis is on low-power design, robust telemetry, and reproducible downstream analysis.
        </p>
      </div>
    </section>
    Bioacoustics (image on left) 
    <section class="project-section project-section--media-left" id="bioacoustics" aria-labelledby="bioacoustics-title">
     <div class="project-media">
        <img src="/assets/images/projects/bioacoustics.jpg" alt="Spectrogram of ..." />
      </div>
      <div class="project-text" aria-labelledby="bioacoustics-title">
        <h3 id="bioacoustics-title">Bioacoustics</h3>
        <p class="muted">
          Tools and workflows for acoustic monitoring: sound preprocessing, automated detection/classification, and scalable pipelines for long-term acoustic datasets.
        </p>
        <p>
          We develop reproducible pipelines for long-duration audio, tools for training detectors and classifiers, and integrations to index and search acoustic archives at scale. Typical outputs include event detectors, spectrogram-based embeddings, and lightweight ingestion tools for field recordings.
        </p>
      </div>
    </section>
   
    Data Management
    <section class="project-section project-section--media-left" id="data-management" aria-labelledby="data-management-title">
      <div class="project-text" aria-labelledby="data-management-title">
        <h3 id="data-management-title">Data Management</h3>
        <p class="muted">
          Tools for cleaning, organizing, and analyzing a variety of ecological and evironmental data.
        </p>
        <p>
          Lorem ipsum
        </p>
      </div>
    </section>
    Thermal    
    <section class="project-section project-section--media-left" id="thermal" aria-labelledby="thermal-title">
      <div class="project-media">
        <img src="/assets/images/projects/re-identification.jpg" alt="thermal example" />
      </div>
      <div class="project-text" aria-labelledby="thermal-title">
        <h3 id="thermal-title">Thermal Imaging</h3>
        <p class="muted">
          Research and tools for individual re-identification from images or acoustic signatures, including embedding models, matching workflows, and evaluation scripts.
        </p>
        <p>
          Lorem ipsum
        </p>
      </div>
    </section>
    -->
</div>
