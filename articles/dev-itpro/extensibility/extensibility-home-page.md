---
# required metadata

title: Extensibility home page
description: This topic provides links to topics about extensibility.
author: FrankDahl
manager: AnnBe
ms.date: 04/10/2018
ms.topic: index-page
ms.prod: 
ms.service: dynamics-ax-platform
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Developer
# ms.devlang: 
ms.reviewer: robinr
ms.search.scope: Operations
# ms.tgt_pltfrm: 
ms.custom: 268724
ms.assetid: 
ms.search.region: Global
# ms.search.industry: 
ms.author: fdahl
ms.search.validFrom: 2017-02-28
ms.dyn365.ops.version: Platform update 4

---
# Extensibility home page

[!INCLUDE [banner](../includes/banner.md)]

Microsoft Dynamics 365 for Finance and Operations is customized extensively by partners, value added resellers (VARs), and even some customers. This is a strength of the product that historically has been supported through overlayering of the application code. The move to the cloud with more agile servicing and frequent updates requires a less intrusive customization model, which makes updates less likely to impact custom solutions. This new model is called *extensibility* and has replaced customization by overlayering. 

Extensibility is the only customization framework in Microsoft Dynamics 365 for Retail and Microsoft Dynamics 365 for Finance and Operations. Overlayering is not supported.

## Introduction

These introductory topics contain general information about customization, including information on when customization transitions from overlayering to a purely extension-based model. These topics also explain how to log extensibility requests to Microsoft, along with frequently asked questions and answers.

+ [Application extensibility plans](extensibility-roadmap.md)
+ [Extensibility requests](extensibility-requests.md) 
+ [Extensibility FAQ](app-sealing-faq.md) 

## What's new
This section lists the extensibility-related updates that have been made since July 2017.

+ [Extensibility changes in Dynamics 365 for Finance and Operations, Enterprise edition (July 2017)](changes-july-2017.md)
+ [Extensibility changes in Dynamics 365 for Finance and Operations, Enterprise edition 7.3](extensibility-changes-73.md)
+ [Extensibility changes in Dynamics 365 for Finance and Operations release 8.0](Changes-80.md)

## Getting started

Getting started gets you going with building extensions and migrating a current solution, based on overlayered code, to an extension-based solution. This section includes hands on labs that walk you through simple customizations.

+ [Migrate from overlayering to extensions](migrate-overlayer-extension.md)
+ [Customize model elements using extensions (tutorial)](customize-model-elements-extensions.md)
+ [Customization: overlayering and extensions](customization-overlayering-extensions.md)
<!--+ [Customize by overlayering metadata source code (Office Mix)](https://mix.office.com/watch/1ol6ov90jrd4w)-->

## Extensibility fundamentals

Extensibility fundamentals includes principles and practices for how to make extensions. The guiding principles in these topics discuss how customization must be approached through extensions, including naming guidelines. Additionally, these topics discuss the foundation framework, such as extensions and chain of command.

+ [Intrusive customizations](intrusive-customizations.md)
+ [Class extensions](class-extensions.md)
+ [Class extension: Method wrapping and Chain of Command](method-wrapping-coc.md)
+ [Naming guidelines](naming-guidelines-extensions.md)
+ [Relax model restrictions to enable the refactoring of over-layering into extensions](refactoring-over-layering.md)
  
## How do I..?

Here is where you find "How do I?" topics on customizing specific object types or code. Most of these topics are brief and to the point. There are many topics here, so searching for a particular topic may be practical.

### Data types
+ [Add an enum value](add-enum-value.md)
+ [Modify an extended data type](modify-edt.md) 

### Classes
+ [Register a subclass for factory methods](register-subclass-factory-methods.md)
+ [Respond with EventHandlerResult](respond-event-handler-result.md)
+ [Extend the RunBase class](extend-runbase-class.md)
+ [Use delegates to customize Application startup](startup-customizations.md)

### Tables
+ [Modify an existing field in a table](modify-existing-field.md)
+ [Add a new field to an existing table](add-field-extension.md)
+ [Add an index to an existing table](add-index.md)
+ [Add a relation to an existing table](add-relation.md)
+ [Modify properties on an existing table](modify-properties.md)
+ [Add a method to a table](add-method-table.md)
+ [Perform business actions throughout the lifecycle of a table record](subscribe-table-events.md)

### Forms
+ [Add a new data source to a form](add-datasource.md)
+ [Change the caption on a form](change-caption-form.md)
+ [Modify form control properties](modify-control-properties.md)

### Reports
+ [Extend the list of Electronic reporting functions](../analytics/general-electronic-reporting-formulas-list-extension.md)
+ [Customize App Suite reports](../analytics/customize-app-suite-reports-with-extensions.md)

### Labels
+ [Change a label](change-label.md)

## Blog posts

Information on customization is also shared through various blogs where different topics are discussed. This section includes reference to some of these blogs.

+ [Extending Dynamics 365 for Finance and Operations](https://blogs.msdn.microsoft.com/mfp/2017/01/31/extending-dynamics-365-for-operations/)
+ [Extending class state](https://blogs.msdn.microsoft.com/mfp/2017/01/31/extending-class-state/)
+ [Extension methods](https://blogs.msdn.microsoft.com/mfp/2015/12/15/x-in-ax7-extension-methods/)
+ [Extensible base enumerations](http://kashperuk.blogspot.dk/2016/09/development-tutorial-extensible-base.html)
+ [Static event subscription](https://blogs.msdn.microsoft.com/mfp/2015/12/10/x-in-ax7-static-event-subscription/)
+ [Responding through delegates](https://blogs.msdn.microsoft.com/mfp/2017/01/31/responding-through-delegates/)
+ [Subscribing to onValidatingWrite](https://blogs.msdn.microsoft.com/mfp/2017/01/31/subscribing-to-onvalidatingwrite/)
+ [Extending inventory dimensions](https://blogs.msdn.microsoft.com/mfp/2017/08/10/extensible-inventory-dimensions/)
+ [Embrace the extensions mindset with Dynamics 365 for Finance and Operations](https://blogs.msdn.microsoft.com/axinthefield/embrace-the-extensions-mindset-with-dynamics-365-for-finance-and-operations/)
