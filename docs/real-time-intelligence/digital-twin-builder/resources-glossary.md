---
title: Digital twin builder (preview) glossary
description: This article defines important digital twin builder (preview) terminology.
author: baanders
ms.author: baanders
ms.date: 03/10/2025
ms.topic: conceptual
---

# Digital twin builder (preview) glossary

This article defines important digital twin builder (preview) terminology. The list is alphabetically organized.

[!INCLUDE [Fabric feature-preview-note](../../includes/feature-preview-note.md)]

| Terminology | Definition |
|---|---|
| *Base layer* | Modeling concept. The *base layer* is the foundational set of delta tables designed to store both the ontology definitions and the instantiated ontology data. This layer organizes and preserves the core structures of the ontology, including the definitions of entity types, properties, relationships, namespaces, and any metadata associated with the domain model. For more information, see [Modeling data in digital twin builder (preview)](concept-modeling.md#storage-and-access). |
| *Configure (mode)* | One of two modes in the digital twin builder experience. In *Configure* mode, you have access to the [semantic canvas](concept-semantic-canvas.md) where you can create entities, map data, and relate entities. |
| *Contextualization* | Feature. The *contextualization* feature allows you to further augment the context of your data by creating semantic relationships between entities in your ontology. For more information, see [Perform contextualization](model-perform-contextualization.md). |
| *Digital twin builder (preview)* | Name of the product. *Digital twin builder (preview)* is a new item within the Real-Time Intelligence workload in Microsoft Fabric. It creates digital representations of real-world environments to optimize physical operations using data. For more information, see [What is digital twin builder (preview)?](overview.md) |
| *Digital twin builder flow* | Feature. *Digital twin builder flow* items are created to execute mapping and contextualization operations. For more information, see [Digital twin builder (preview) flow](concept-flows.md). |
| *Digital twin builder item* | Instance of digital twin builder created by a user. |
| *Domain layer* | Modeling concept. The *domain layer* is a structured set of normalized database views created from the base layer to present a clear representation of the instantiated ontology. This layer is built by arranging data from the base layer tables into views that directly reflect the logical structure and relationships defined in the domain ontology. For more information, see [Modeling data in digital twin builder (preview)](concept-modeling.md#storage-and-access).|
| *Explore (mode)* | One of two modes in the digital twin builder experience. In *Explore* mode, you can view and explore your entity instances and time series data. |
| *Explorer* | Feature. The *explorer* in digital twin builder lets you identify assets from keywords, explore asset details, and visualize time series data. For more information, see [Search and visualize your modeled data](explore-search-visualize.md). |
| *Mapping* | Feature. The *mapping* feature allows you to create an ontology with semantically rich entities, and hydrate it with data from various source systems in a simplified manner. For more information, see [Mapping data to entities in digital twin builder (preview)](concept-mapping.md). |
| *Ontology* | Concept. An *ontology* is a formal model that defines a set of concepts, entities, properties, and relationships within a specific domain, creating a shared vocabulary and framework for organizing information. Namespace, entity type, entity, entity instance, property, and relationship are the core elements of an ontology. You can use these elements to consistently define and represent complex knowledge. For more information, see [Modeling data in digital twin builder (preview)](concept-modeling.md#storage-and-access). |
| *Relationship* | Contextualization concept. A *relationship* is a link between two entities created as part of a contextualization job. For more information, see [Contextualization](model-perform-contextualization.md). |
| *Semantic canvas* | UX component. The *semantic canvas* is the centerpiece for creating your ontology. In the canvas, you can create entities, map data to them, and create semantic relationships between entities. For more information, see [Using the semantic canvas in digital twin builder (preview)](concept-semantic-canvas.md). |
