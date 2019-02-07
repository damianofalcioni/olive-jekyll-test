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
    outputAlg: "return output.dataText;"
---

# Project SECOND PAGE
Note that this page is not visualized in the collection due to the presence of the parameter `hide: true`
