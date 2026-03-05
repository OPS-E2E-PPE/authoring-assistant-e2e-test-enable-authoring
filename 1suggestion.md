---
title: Title
description: description
ms.devlang: azurecli
ms.topic: conceptual
ms.date: 03/11/2022 
ms.custom: devx-track-azurecli
---
1. Notify objects are COM objects that reside within dynamic-link libraries (DLLs). These DLLs are COM component servers. Each type of network component is associated with a class installer. The class installer installs specific types of network components and registers COM class objects that these network components own. After the main installation phase for network components finishes, the system registers the objects. To register a COM class object, the class installer calls the object's DLL entry-point function.
