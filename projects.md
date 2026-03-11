---
layout: default
title: Projects
description: Open-source conservation technology projects
---

<div class="container">
    <h2 class="section-title">Projects</h2>
    <p style="text-align: center; color: #666; margin-bottom: 2rem;">
        Explore our open-source conservation technology projects.
    </p>
    <!-- Camera traps (image on right) -->
    <section href="{{ '/animl' | relative_url}}" 
             class="project-section project-section--media-right" id="animl" aria-labelledby="animl-title">
      <div class="project-media">
        <img src="/assets/images/projects/camera-traps.jpg" alt="Camera trap image" />
      </div>
      <div class="project-text" aria-labelledby="animl-title">
        <h3 id="animl-title">AniML</h3>
        <p class="muted">
          Open-source tooling for camera-trap imagery: ingestion, annotation, automated detection and species classification, and reproducible analysis pipelines.
        </p>
        <p>
          Work focuses on robust ingestion from diverse camera systems, annotation workflows that speed labeling, and models that detect animals and estimate abundance. We also prioritize reproducible notebooks and deployment-ready detection pipelines.
        </p>
      </div>
    </section>
    <!-- Environmental sensors (image on right) -->
    <section class="project-section project-section--media-right" id="edge-ai" aria-labelledby="edge-ai-title">
      <div class="project-media">
        <img src="/assets/images/projects/edge-ai.jpg" alt="Edge AI" />
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
    <!-- Bioacoustics (image on left) -->
    <section class="project-section project-section--media-left" id="bioacoustics" aria-labelledby="bioacoustics-title">
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
    <!-- Re-identification (image on left) -->
    <section href="{{ '/matchypatchy' | relative_url}}" 
             class="project-section project-section--media-left" id="individual-id" aria-labelledby="individual-id-title">
      <div class="project-media">
        <img src="/assets/images/projects/re-identification.jpg" alt="individual-id example" />
      </div>
      <div class="project-text" aria-labelledby="individual-id-title">
        <h3 id="individual-id-title">MatchyPatchy</h3>
        <p class="muted">
          Research and tools for individual re-identification from images or acoustic signatures, including embedding models, matching workflows, and evaluation scripts.
        </p>
        <p>
          Projects include model training recipes for embeddings, example matching services, and evaluation suites for comparing approaches. We provide guidance for dataset preparation, cross-validation strategies, and deployment considerations for field use.
        </p>
      </div>
    </section>
    <!-- Data Management -->
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
    <!-- Re-identification (image on left) -->
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
    
</div>