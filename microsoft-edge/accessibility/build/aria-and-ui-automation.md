---
ms.assetid: ffd1bc60-2ef1-4f11-8156-b63544cede77
description: Learn how Microsoft Edge can recognize ARIA info, then expose it to assistive technologies that can then use Microsoft UI Automation APIs.
title: ARIA and UI automation in Microsoft Edge
author: MSEdgeTeam
ms.author: msedgedevrel
ms.date: 03/05/2020
ms.topic: article
ms.prod: microsoft-edge
keywords: accessibility, accessibility for developers, accessible websites, edge, web development, ARIA, developer, UIA, UI Automation
ms.custom: seodec18
---
# ARIA and UI automation in Microsoft Edge

The W3C defines Accessible Rich Internet Applications (ARIA) as a syntax for making dynamic web content and custom UI accessible.  Microsoft Edge recognizes the ARIA role, state, and property information and exposes it to assistive technologies, which in turn can use the [Microsoft UI Automation](https://blogs.msdn.microsoft.com/winuiautomation/) APIs to retrieve the information.

Visit [HTML5Accessibility](https://html5accessibility.com) for information on which new HTML5 features are accessibly supported by Microsoft Edge.

The Microsoft Edge rendering engine builds an accessible projection of web pages, conforming to the following W3C specifications:

1. The [HTML Accessibility API Mappings](https://w3.org/TR/html-aam-1.0/) specification defines how HTML elements and attributes map to ARIA and UI Automation objects.
   * [Working draft](https://w3.org/TR/html-aam-1.0/) - stable version of the specification.
   * [Editor's draft](https://w3c.github.io/html-aam/) - work in progress.  Note that while this spec has the latest changes, the changes may not be available in Microsoft Edge yet.

2. The [Core Accessibility API Mappings](https://w3.org/TR/core-aam-1.1/) specification defines general principles for building the accessibility tree and mapping ARIA elements and attributes to UI Automation objects.
   * [Working draft](https://w3.org/TR/core-aam-1.1/) - stable version of the specification.
   * [Editor's draft](https://w3c.github.io/core-aam/) - work in progress.  Note that while this spec has the latest changes, the changes may not be available in Microsoft Edge yet.

3. The [Accessible Name and Description: Computation and API Mappings](https://w3.org/TR/accname-aam-1.1/) specification defines how to compute the name and description of accessible objects given the HTML and the ARIA elements and attributes values available for the accessible elements.
   * [Working draft](https://w3.org/TR/accname-aam-1.1/) - stable version of the specification.
   * [Editor's draft](https://w3c.github.io/accname/) - work in progress.  Note that while this spec has the latest changes, the changes may not be available in Microsoft Edge yet.


<!-- ====================================================================== -->
## See also

* [Building a more accessible web platform](https://blogs.windows.com/msedgedev/2016/04/20/building-a-more-accessible-web-platform/) - A blog post about the accessibility architecture in Microsoft Edge.

* [Building a more accessible user experience with HTML5 and UIA](https://blogs.windows.com/msedgedev/2016/05/12/accessible-ux-with-html5-and-uia/) - Examples of how markup defines the experience of navigating with assistive technologies such as screen readers, and examples of how the architecture improves the end user's experience.
