---
layout: project
type: project
image: img/fishpond/Fishphoto.webp
title: "Fish Pond Game"
date: 2024
published: true
labels:
  - OOP
  - Java
summary: "My final project for ICS 211"
---

<div class="text-center p-4">
  <img src="/img/fishpond/IaGraph.png" class="img-fluid rounded shadow-lg mx-auto d-block" alt="Fish Pond Game screenshot">
</div>



Here is some code that recursively searches for a fish in the IaTree based on the given search key.

```java
private I_a get(IaNode node, I_a searchKey) {
    if (node == null) {
        throw new IaTreeException("Fish not found.");
    }
    int comparison = searchKey.getName().compareTo(node.getI_a().getName());
    if (comparison == 0) {
        return node.getI_a();
    }
    return comparison < 0 ? get(node.getLChild(), searchKey) : get(node.getRChild(), searchKey);
}

