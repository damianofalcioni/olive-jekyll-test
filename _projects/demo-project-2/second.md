---
title: "DEMO Project"

hide: true

header:
  teaser: assets/images/demo_teaser.png
  
sidebar:
  - image: assets/images/demo_teaser.png
    image_alt: "DEMO Project"
    title: "Project Pages"
    text: "[Home page](../home/)"
  - text: "[Second page](../second/)"

microservices:
  - name: "Hello World"
    microserviceId: "1738cb62-cc55-4abf-8560-feafdb83260c"
    operationId: "default"
    inputJSON: "{\"Append Text\":{\"value\":\"World\"}}"
    outputAlg: "/*\n  Javascript algoritm that _return_ a DOM object.\n  The algorithm can access the microservice output content\n  using the variable output\n*/\nreturn output.dataText;"
---

# Project SECOND PAGE
Note that this page is not visualized in the collection due to the presence of the parameter `hide: true`
