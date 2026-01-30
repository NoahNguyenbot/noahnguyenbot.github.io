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

My final project for ICS 211 was a fishing game where two players take turns catching fish with the goal of achieving the highest score.  The game runs over a span of 12 month (12 rounds), where each players score is based on the size and type of the fish caught. At the beginning of the game fish are added to a pond called fishPond to create an enviornment in which they grow. Various types of fish are randomly generated in the pond based on the fish objects we created. Each fish has differnt growth patterns which were managed by the fishGrow method.





Here is some code that shows how the fish grow:

{% highlight java %}
protected void grow() {
      Random ran = new Random();
      double growthAmount = ran.nextDouble() * growthRate;
      double newLength = this.length + growthAmount;
      
      if (newLength > OAMA_MAX_LENGTH) {
         throw new FishSizeException("'Oama has grow too large, it needs to level up!");
      }
      this.length = newLength;
      this.weight = newLength * 2;
   }
{% endhighlight %}

