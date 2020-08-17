---
layout: default
style: no-margin
title: Media-IO | Media Cloud AI
permalink: /media-cloud-ai
image: assets/images/mediaio_logo.png
---
<div class="section">
  <div class="filler"></div>
  <div>
    <h1>Media Cloud AI</h1>
    <h3>
        Media Cloud AI intend to build an open-source micro-service platform to process media content with some Artificial Intelligence processes.<br/>
        It will also provide some generic tools to manipulate media.
    </h3>
  </div>
  <div class="filler"></div>
</div>
<div class="section">
    <h2>Architecture</h2>
    <p>
        This micro-services platform provides a fully <b>distributed processing</b> for media content accross <b>multi-cloud</b> provider (public & private).<br/>
        The <b>backend is the main orchestrator</b>, combining steps after step a complex workflow.<br/>
        Each worker is connected to the message broken to enable the <b>horizontal scalability</b>.<br/>
    </p>
    {% include mermaid_schemas/main_architecture.html %}
    Read more details about the complete <a href="http://media-cloud.ai/architecture.html" target="_blank">architecture</a>.
</div>
<div class="section">
    <h2>Workers / Features</h2>
    <p>
        In micro-service architecture, each worker will provide a specific feature.<br/>
        The combination of them provides a complex system.<br/>
        Some generic workers are required to create a base available a feature:
        <ul>
            <li>
                <label>Transfer</label>: to move files accross storages (S3, FTP, HTTP, local)
            </li>
            <li>
                <label>File system</label>: to remove or copy local files and folders
            </li>
            <li>
                <label>Command line</label>: to execute any command
            </li>
            <li>
                <label>FFmpeg</label>: to manipulate any video and audio formats
            </li>
            <li>
                <label>Manifest worker</label>: DASH and ISM manifest manipulations
            </li>
            <li>
                <label>AWS Cli worker</label>: execute AWS action with aws2
            </li>
        </ul>
        <p>
            Some additional workers are built in open-source:
            <ul>
                <li>
                    <label>Loudness worker</label>: loudness measurements of audio content (ITU-R BS.1770-4)
                </li>
                <li>
                    <label>ADM Engine worker</label>: renderer for Object-Based Audio (ITU-R BS.2076-1)
                </li>
            </ul>
        </p>
    </p>
</div>

<div class="section">
    <h2>Offical website</h2>
    <a href="https://media-cloud.ai/" target="_blank">
        <div class="button">
            <i class="fa fa-external-link"></i>
            Open offcial website
        </div>
    </a>
</div>