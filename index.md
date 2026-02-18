---
layout: default
title: Home
description: Developing open-source technology and machine learning tools for wildlife conservation and ecological research
---

<section class="hero">
    <div class="container">
        <h2>About the Lab</h2>
        <p>
            The Conservation Tech Lab develops cutting-edge technology solutions for wildlife conservation and ecological research. 
            Our work spans machine learning for camera trap analysis, edge-AI field devices, bioacoustics tools, and animal tracking systems.
        </p>
        <p>
            All of our projects are open-source, promoting collaboration and knowledge sharing within the conservation technology community.
            We focus on practical, field-deployable solutions that help researchers and conservationists better understand and protect wildlife.
        </p>
        <div class="stats">
            <div class="stat-item">
                <div class="stat-number">24</div>
                <div class="stat-label">Open Source Projects</div>
            </div>
            <div class="stat-item">
                <div class="stat-number">70+</div>
                <div class="stat-label">Stars on GitHub</div>
            </div>
            <div class="stat-item">
                <div class="stat-number">17</div>
                <div class="stat-label">Contributors</div>
            </div>
        </div>
    </div>
</section>

<div class="container">
    <h2 class="section-title">Research Focus Areas</h2>
    <div class="projects-grid">
        <!-- <a href="{{ '/projects' | relative_url}}#camera-traps" -->
        <div class="project-card">
            <h3>📷 Camera Trap AI</h3>
            <p class="project-description">
                Machine learning models and tools for automatically classifying and analyzing wildlife in camera trap images and videos.
            </p>
        </div>
       <!-- <a href="{{ '/projects' | relative_url}}#edge-ai"> -->
       <div class="project-card">
            <h3>📡 Edge AI Devices</h3>
            <p class="project-description">
                Field-deployable devices with on-board AI processing and LoRa connectivity for real-time wildlife detection and monitoring in remote locations.
            </p>
        </div>
        <!-- <a href="{{ '/projects' | relative_url}}#bioacoustics" -->
        <div class="project-card">
            <h3>🔊 Bioacoustic Monitoring</h3>
            <p class="project-description">
                Tools for capturing and detecting wildlife sounds, and for building training data sets and training models.
            </p>
        </div>
        <!-- <a href="{{ '/projects' | relative_url}}#individual-id" -->
        <div class="project-card">
            <h3>🐾 Individual ID</h3>
            <p class="project-description">
                AI-powered systems for identifying individual animals using visual features.
            </p>
        </div>
        <!-- <a href="{{ '/projects' | relative_url}}#data-management" -->
        <div class="project-card">
            <h3>📊 Data Management</h3>
            <p class="project-description">
                Platforms and tools for organizing, visualizing, and analyzing large-scale ecological data from various field devices.
            </p>
        </div>
        <!-- <a href="{{ '/projects' | relative_url}}#thermal-imaging" -->
        <div class="project-card">
            <h3>🌡️ Thermal Imaging</h3>
            <p class="project-description">
                Detection and tracking systems using thermal cameras for monitoring wildlife in challenging environmental conditions.
            </p>
        </div>
    </div>
    <h2 class="section-title">Featured Projects</h2>
    <div class="projects-grid">
        <!-- Animl R -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/animl-r" target="_blank" rel="noopener">animl-r</a></h3>
            <p class="project-description">
                Animl comprises a variety of machine learning tools for analyzing ecological data. The R library includes a set of functions to classify subjects within camera trap field data and can handle both images and videos.
            </p>
            <div class="project-meta">
                <span class="language">R</span>
                <span>⭐ 23</span>
                <span>🍴 6 forks</span>
            </div>
            <div class="topics">
                <span class="topic-tag">deep-learning</span>
                <span class="topic-tag">machine-learning</span>
            </div>
        </div>
        <!-- Animl Python -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/animl-py" target="_blank" rel="noopener">animl-py</a></h3>
            <p class="project-description">
                Animl comprises a variety of machine learning tools for analyzing ecological data. This Python package includes a set of functions to classify subjects within camera trap field data and can handle both images and videos.
            </p>
            <div class="project-meta">
                <span class="language">Python</span>
                <span>⭐ 11</span>
                <span>🍴 6 forks</span>
            </div>
        </div>
        <!-- ScrubCam -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/scrubcam" target="_blank" rel="noopener">scrubcam</a></h3>
            <p class="project-description">
                Code for Edge-AI-enabled field wildlife camera that processes images directly in the field for real-time wildlife detection and analysis.
            </p>
            <div class="project-meta">
                <span class="language">Python</span>
                <span>⭐ 6</span>
            </div>
        </div>
        <!-- ScrubDash -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/scrubdash" target="_blank" rel="noopener">scrubdash</a></h3>
            <p class="project-description">
                Dashboard for organizing, visualizing, and analyzing images received from ScrubCams in the field.
            </p>
            <div class="project-meta">
                <span class="language">Python</span>
                <span>⭐ 3</span>
            </div>
        </div>
        <!-- Whoot -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/whoot" target="_blank" rel="noopener">whoot</a></h3>
            <p class="project-description">
                Tools for capturing, analyzing, and parsing bioacoustic data to help researchers study wildlife through sound recordings.
            </p>
            <div class="project-meta">
                <span class="language">Python</span>
                <span>⭐ 5</span>
            </div>
        </div>
        <!-- MatchyPatchy -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/matchypatchy" target="_blank" rel="noopener">matchypatchy</a></h3>
            <p class="project-description">
                GUI tool for human validation of AI-powered animal re-identification, helping researchers verify and improve AI predictions for individual animal identification.
            </p>
            <div class="project-meta">
                <span class="language">Python</span>
                <span>⭐ 5</span>
            </div>
        </div>
        <!-- DenCam -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/dencam" target="_blank" rel="noopener">dencam</a></h3>
            <p class="project-description">
                Polar bear maternal den observation system designed for monitoring and studying polar bear denning behavior in remote Arctic environments.
            </p>
            <div class="project-meta">
                <span class="language">Python</span>
                <span>⭐ 5</span>
                <span>🍴 2 forks</span>
            </div>
        </div>
        <!-- CougarVision -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/cougarvision" target="_blank" rel="noopener">cougarvision</a></h3>
            <p class="project-description">
                Tools to automatically analyze images and videos from telemetering field cameras and to take responsive action based on detected wildlife.
            </p>
            <div class="project-meta">
                <span class="language">Python</span>
                <span>⭐ 4</span>
            </div>
        </div>
        <!-- CameraBase -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/camerabase" target="_blank" rel="noopener">camerabase</a></h3>
            <p class="project-description">
                GUI application for managing data from camera traps used in field ecology projects, streamlining data organization and analysis workflows.
            </p>
            <div class="project-meta">
                <span class="language">Batchfile</span>
                <span>⭐ 1</span>
            </div>
        </div>
        <!-- HeatSeek -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/heatseek" target="_blank" rel="noopener">heatseek</a></h3>
            <p class="project-description">
                Thermal imagery detection and tracking tools for monitoring wildlife using thermal cameras.
            </p>
            <div class="project-meta">
                <span class="language">Python</span>
                <span>⭐ 1</span>
            </div>
        </div>
        <!-- YoctoDetector -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/yoctodetector" target="_blank" rel="noopener">yoctodetector</a></h3>
            <p class="project-description">
                Tools for training custom animal object detectors, enabling researchers to create specialized models for detecting specific species.
            </p>
            <div class="project-meta">
                <span class="language">Jupyter Notebook</span>
                <span>⭐ 3</span>
                <span>🍴 1 fork</span>
            </div>
        </div>
        <!-- TinyScrubCam -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/tinyscrubcam" target="_blank" rel="noopener">tinyscrubcam</a></h3>
            <p class="project-description">
                Edge-AI and device for wildlife detection and alerts, a compact version designed for deployment in resource-constrained environments.
            </p>
            <div class="project-meta">
                <span class="language">Makefile</span>
                <span>⭐ 3</span>
            </div>
        </div>
        <!-- CameraBase R -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/camerabase-r" target="_blank" rel="noopener">camerabase-r</a></h3>
            <p class="project-description">
                Tools for reading and writing to Camera Base database through R, facilitating data management for camera trap research.
            </p>
            <div class="project-meta">
                <span class="language">R</span>
                <span>⭐ 2</span>
            </div>
        </div>
        <!-- SageRanger -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/sageranger" target="_blank" rel="noopener">sageranger</a></h3>
            <p class="project-description">
                A package to aide in the utilization of EarthRanger as a way to capture and display data of interest from camera traps and other data loggers.
            </p>
            <div class="project-meta">
                <span class="language">Python</span>
                <span>⭐ 2</span>
            </div>
        </div>
        <!-- Otolith -->
        <div class="project-card">
            <h3><a href="https://github.com/conservationtechlab/otolith" target="_blank" rel="noopener">otolith</a></h3>
            <p class="project-description">
                Code for animal-borne devices and bench post-processing associated with logging and analysing inertial measurements, including for activity recognition.
            </p>
            <div class="project-meta">
                <span class="language">C++</span>
                <span>⭐ 2</span>
                <span>🍴 1 fork</span>
            </div>
        </div>
    </div>
</div>
