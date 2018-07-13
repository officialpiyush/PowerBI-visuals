---
layout: docs
title: Best Practices for Excel Development
description: 
group: building-for-excel
toc: true
---

* Custom visuals in Excel connect directly to data as it exists in the spreadsheet without any additional aggregation operations performed.  When Excel passes data to the visual, rows are not guaranteed to have unique sets of categories.  Visuals wanting to identify a datapoint should identify it by its `DataViewScopeIdentity`.

Next: [FAQ](../faq/)