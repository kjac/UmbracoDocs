---
title: IProductSnapshot
description: API reference for IProductSnapshot in Umbraco Commerce
---
## IProductSnapshot

```csharp
public interface IProductSnapshot
```

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Properties

#### Attributes

```csharp
public IEnumerable<AttributeCombination> Attributes { get; }
```


---

#### IsGiftCard

```csharp
public bool IsGiftCard { get; }
```


---

#### Name

```csharp
public string Name { get; }
```


---

#### Prices

```csharp
public IEnumerable<ProductPrice> Prices { get; }
```


---

#### ProductReference

```csharp
public string ProductReference { get; }
```


---

#### ProductVariantReference

```csharp
public string ProductVariantReference { get; }
```


---

#### Properties

```csharp
public IDictionary<string, string> Properties { get; }
```


---

#### Sku

```csharp
public string Sku { get; }
```


---

#### StoreId

```csharp
public Guid StoreId { get; }
```


---

#### TaxClassId

```csharp
public Guid? TaxClassId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->