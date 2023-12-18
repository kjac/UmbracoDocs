---
title: CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask
description: API reference for CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask in Umbraco Commerce
---
## CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask

```csharp
public class CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask : 
    PipelineTaskWithTypedArgsBase<OrderCalculationPipelineArgs, OrderCalculation>
```

**Inheritance**

* Class [PipelineTaskWithTypedArgsBase&lt;!0,!1&gt;](../../umbraco-commerce-common/umbraco-commerce-common-pipelines/pipelinetaskwithtypedargsbase-2.md)

**Namespace**
* [Umbraco.Commerce.Core.Pipelines.Order.Tasks](README.md)

### Constructors

#### CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask

The default constructor.

```csharp
public CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask()
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderCalculation> Execute(OrderCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->