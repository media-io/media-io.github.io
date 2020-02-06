---
layout: default
style: no-margin
title: Media-IO | Media Cloud AI
---
<div class="section">
  <div class="filler"></div>
  <div>
    <h1>Media Cloud AI</h1>
    <h3>
        Media Cloud AI intend to build an open-source platform to process media content with some Artificial Intelligence processes.<br/>
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
    Read more details about the [architecture](/architecture.html){:target="_blank"}.
</div>
