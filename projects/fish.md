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

My final project for ICS 211 was a fishing game in which two players took turns catching fish to achieve the highest score. The game ran over 12 months (12 rounds), and each player’s score was based on the size and type of fish they caught. At the beginning of the game, fish were added to a pond called "fishPond" to create an environment in which they could grow. Various types of fish were randomly generated in the pond based on the fish objects we created, and each fish had a different growth pattern. 




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

