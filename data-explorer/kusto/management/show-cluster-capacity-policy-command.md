---
title: .show cluster capacity policy command- Azure Data Explorer
description: This article describes the .show cluster capacity policy command in Azure Data Explorer.
services: data-explorer
author: orspod
ms.author: orspodek
ms.reviewer: yonil
ms.service: data-explorer
ms.topic: reference
ms.date: 09/26/2021
---
# .show cluster capacity policy

Display a cluster's [capacity policy](capacitypolicy.md). A capacity policy is used for controlling the compute resources of data management operations on the cluster. This command requires [AllDatabasesAdmin](access-control/role-based-authorization.md) permission.

## Syntax

`.show` `cluster` `policy` `capacity` 

## Returns

Returns a JSON representation of the policy.

### Example

Display the cluster's capacity policy.

```kusto
.show cluster policy capacity
```