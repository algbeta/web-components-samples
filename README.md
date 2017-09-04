# Web-components-samples

This repo contains examples of web component techniques.

- Template example contains template element contains 368kb external image and is being invoked after at least 5s.
- Html import example contains a page which has an html import link. Html to be import has quite complex structure including external resources


## Polymer
- it is complex
- polymer components are described in html files
- it has it's own eco-system, even building of custom components is done through polymer bundle
- if there is the same dependency in different templates it is being downloaded only once
- shadow dom is active by default, in general comparison web components with shadow dom are being slowlier than ones without it. 
- even if we decide to use only one web component thechniques we are bound to get all the polyfills anyway, I haven't found a way to customaze Polymer
- compared to native Web Components (which are fully supported by chrome only) Polymer does slow the perfomance.
- *browser support is a plus*

# React component
- can be embbeded easily into any compatible react app
- easy to serve/ to include into app
- no additional perfomance issues
