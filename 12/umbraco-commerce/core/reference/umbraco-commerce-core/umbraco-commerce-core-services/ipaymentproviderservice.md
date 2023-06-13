---
title: IPaymentProviderService
description: API reference for IPaymentProviderService in Umbraco Commerce
---
## IPaymentProviderService

```csharp
public interface IPaymentProviderService : IService
```

**Inheritance**

* interface [IService](iservice.md)

**Namespace**
* [Umbraco.Commerce.Core.Services](README.md)

### Methods

#### GetPaymentProvider

```csharp
public IPaymentProvider GetPaymentProvider(string alias)
```


---

#### GetPaymentProviderDefinitions

```csharp
public IEnumerable<PaymentProviderDefinition> GetPaymentProviderDefinitions()
```


---

#### GetPaymentProviderScaffold

```csharp
public PaymentProviderScaffold GetPaymentProviderScaffold(string alias)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->