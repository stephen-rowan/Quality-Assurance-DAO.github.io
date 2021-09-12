---
date: 2018-10-06
title: "What is Quality Assurance DAO (QA-DAO)"
linkTitle: "What is Quality Assurance DAO (QA-DAO)"
description: "Quality Assurance DAO (QA-DAO) is an ongoing open source project that provides support for the Cardano Project Catalyst Community."
author: Stephen Whitenstall
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
  params:
    byline: "Photo: Riona MacNamara / CC-BY-CA"
---

**Quality Assurance DAO (QA-DAO) .**

Quality Assurance DAO (QA-DAO) is an ongoing open source project that provides support for the Cardano Project Catalyst Community. 
In Fund 5 of Project Catalyst QA-DAO submitted a proposal "Quality Assurance DAO" in the Developer Ecosystem Challenge that sought to encourage open-source collaboration & innovation and to do a QA Assessment of Catalyst Proposal Process itself. This proposal was successful in receiving votes and was funded in August 2021. Governance of the Quality Assurance DAO Fund 5 proposal may be followed here

## Including images

Here's an image (`featured-sunset-get.png`) that includes a byline and a caption.

{{< imgproc Reputation Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}

The front matter of this post specifies properties to be assigned to all image resources:

```
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
  params:
    byline: "Photo: Riona MacNamara / CC-BY-CA"
```

To include the image in a page, specify its details like this:

```
{{< imgproc sunset Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}
```

The image will be rendered at the size and byline specified in the front matter.


