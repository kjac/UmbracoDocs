---
title: ActivityLogEntryMapper
description: API reference for ActivityLogEntryMapper in Umbraco Commerce
---
## ActivityLogEntryMapper

```csharp
public static class ActivityLogEntryMapper
```

**Namespace**
* [Umbraco.Commerce.Cms.Web.Models.Mappers](README.md)

### Methods

#### ActivityLogEntryToDto

```csharp
public static ActivityLogEntryDto ActivityLogEntryToDto(ActivityLogEntry entity, 
    Func<int, string> userNameResolver)
```


---

#### ActivityLogEntryToDtos

```csharp
public static IEnumerable<ActivityLogEntryDto> ActivityLogEntryToDtos(
    IEnumerable<ActivityLogEntry> entity, Func<int, string> userNameResolver)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.Web.dll -->
