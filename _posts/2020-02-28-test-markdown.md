---
layout: post
title: Manuel Outumuro
#subtitle: Each post also has a subtitle
#gh-repo: daattali/beautiful-jekyll
#gh-badge: [star, fork, follow]
#tags: [test]
cover-img: /assets/img/outumuro-land.jpeg
thumbnail-img: /assets/img/outumuro.jpeg
share-img: /assets/img/outumuro-land.jpeg
comments: true
---

Esto es un demo para mostraros como escribir blog posts con markdown.  I Le ruego encarecidamente [que se tome 5 minutos para aprender como escribir en markdown](https://markdowntutorial.com/) - le enseñare como transformar un texto regular en bold/italics/headings/tables/etc.

**Algo de bold text**

## Aquí hay un titulo secundario

Este es un ejemplo de tabla:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


posicion de imagen

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Puede estar centrada tambien!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Algo de codigo:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

el mismo codigo pero resaltado:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
Puede agregar cuadros de notificación, advertencia y error como este:

### Notification

{: .box-note}
**Note:** Este es un cuadro de notificación..

### Warning

{: .box-warning}
**Warning:** Este es un cuadro de advertencia.

### Error

{: .box-error}
**Error:** Este es un cuadro de error.