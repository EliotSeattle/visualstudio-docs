---
title: Code analysis for managed code
ms.date: 06/12/2019
ms.topic: conceptual
helpviewer_keywords:
- code analysis, managed code
- managed code, code analysis
author: mikejo5000
ms.author: mikejo
manager: jillfra
ms.workload:
- dotnet
---
# Overview of code analysis for managed code in Visual Studio

Visual Studio can perform code analysis of managed code in two ways:
- With [legacy analysis](../code-quality/walkthrough-analyzing-managed-code-for-code-defects.md), also known as FxCop static analysis of managed assemblies.
- With the more modern [.NET Compiler Platform-based code analyzers](../code-quality/roslyn-analyzers-overview.md). .NET Compiler Platform-based code analyzers, which analyze your code live as you type, replace legacy FxCop static code analysis, which only analyzes compiled code.