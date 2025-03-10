---
title: Overview of taxonomy tagging in Microsoft Syntex
ms.author: chucked
author: chuckedmonson
manager: jtremper
audience: admin
ms.reviewer: shrganguly
ms.date: 06/17/2024
ms.topic: conceptual
ms.service: microsoft-syntex
ms.subservice: syntex-content-intelligence
ms.custom: intro-overview
search.appverid: 
ms.collection: 
    - enabler-strategic
    - m365initiative-syntex
ms.localizationpriority: medium
description: Learn about taxonomy tagging in Microsoft Syntex.
---

# Overview of taxonomy tagging in Microsoft Syntex

> [!NOTE]
> Through June 2025, you can try out taxonomy tagging and other selected Syntex services at no cost if you have [pay-as-you-go billing](syntex-azure-billing.md) set up. For information and limitations, see [Try out Microsoft Syntex and explore its services](promo-syntex.md).

Microsoft Syntex gives you the ability to automatically tag documents in SharePoint libraries with terms configured in your term store using AI. These terms are stored in a managed metadata column (also known as a taxonomy column) on the item, making the documents easier to search, sort, filter, and manage.

The taxonomy tagging feature offers an automated tagging solution for documents stored in document libraries. This straightforward, no-training option eliminates the need for users to manually tag documents or build and train sophisticated AI models to tag basic terms. This feature is beneficial if you want to quickly search for and locate documents in your libraries or set up any subsequent processes based on the tags attached to files.

## Requirements and limitations

### Supported file types

Taxonomy tagging is available for the following file types: .doc, .docx, .pdf, and .pptx.

### Current release notes

- A maximum of three columns in a library can be configured with taxonomy tagging.

- Taxonomy tagging does not work on scanned PDF files at this time. It only works on regular (native) PDF files.

- Time taken to reflect tags getting in the taxonomy column: Minimum: 20 minutes, maximum: 24 hours.

- The configured column is an editable taxonomy column. Therefore, you can add new tags or remove the AI-generated tags to meet your requirements.

- Existing documents processing: By default, existing documents are not processed when taxonomy tagging is enabled. Any newly uploaded files or existing files that are edited will be processed for automatic taxonomy tagging.
