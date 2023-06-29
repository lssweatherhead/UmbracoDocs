---
title: OrderHasOrderLineWithProductSpecification
description: API reference for OrderHasOrderLineWithProductSpecification in Umbraco Commerce
---
## OrderHasOrderLineWithProductSpecification

```csharp
public class OrderHasOrderLineWithProductSpecification : IQuerySpecification<OrderReadOnly>, 
    ISpecification<OrderReadOnly>
```

**Inheritance**

* interface [IQuerySpecification&lt;!0&gt;](../../umbraco-commerce-common/umbraco-commerce-common-specifications/iqueryspecification-1.md)
* interface [ISpecification&lt;!0&gt;](../../umbraco-commerce-common/umbraco-commerce-common-specifications/ispecification-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Specifications.Order](README.md)

### Constructors

#### OrderHasOrderLineWithProductSpecification (1 of 2)

```csharp
public OrderHasOrderLineWithProductSpecification(string productReferenceOrSku)
```

---

#### OrderHasOrderLineWithProductSpecification (2 of 2)

```csharp
public OrderHasOrderLineWithProductSpecification(string productReferenceOrSku, 
    string productVariantReferenceOrSku)
```


### Properties

#### ProductReferenceOrSku

```csharp
public string ProductReferenceOrSku { get; }
```


---

#### ProductVariantReferenceOrSku

```csharp
public string ProductVariantReferenceOrSku { get; }
```


### Methods

#### Accept

```csharp
public void Accept(IVisitor visitor)
```


---

#### IsSatisfiedBy

```csharp
public bool IsSatisfiedBy(OrderReadOnly item)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->