---
title: "SearchBar en Xamarin Forms"
excerpt: |
   Le toco el turno a Xamarin Forms [@xamarinhq] tambien, una herramienta muy util para hacer aplicaciones mobile.  
   Me encontre con la incognita de como hacer una búsqueda, una barra de búsqueda.
tags: [Xamarin]
---

Le toco el turno a Xamarin Forms [@xamarinhq](https://twitter.com/xamarinhq) tambien, una herramienta muy util para hacer aplicaciones mobile.  

Me encontre con la incognita de como hacer una búsqueda, una barra de búsqueda.  Me puse a hacerla toda a mano usando:

```xml
<Entry Placeholder="Buscar libro por Titulo / Autor / Palabra clave" 
   FontSize="16"
   Margin="30,0,0,10"
   Completed="OnEntryCompleted" />
```
![Entry](/assets/img/xamarin1.jpeg)

Y agregando icono de lupa a mano.



Pero existe: 

```xml
     <SearchBar Placeholder="Buscar libro por Titulo / Autor / Palabra clave" 
               CancelButtonColor="LightGray"
               PlaceholderColor="LightGray"
               TextColor="Black"
               Margin="0,10,0,10"
               TextTransform="Lowercase"
               HorizontalTextAlignment="Start"
               FontSize="Medium"
               FontAttributes="Italic"
               SearchButtonPressed="OnEntryCompleted" />
```

lo cual te soluciona completamente la vida. ;)

![SearchBar](/assets/img/xamarin2.jpeg)


---

It's the turn of Xamarin Forms [@xamarinhq](https://twitter.com/xamarinhq) a very useful tool for making mobile apps.  

I wanted to do a search, a search bar.  I made it using:


```xml
<Entry Placeholder="Buscar libro por Titulo / Autor / Palabra clave" 
   FontSize="16"
   Margin="30,0,0,10"
   Completed="OnEntryCompleted" />
```
![Entry](/assets/img/xamarin1.jpeg)

And adding a magnifying glass icon by hand.

But there is:
```xml
     <SearchBar Placeholder="Buscar libro por Titulo / Autor / Palabra clave" 
               CancelButtonColor="LightGray"
               PlaceholderColor="LightGray"
               TextColor="Black"
               Margin="0,10,0,10"
               TextTransform="Lowercase"
               HorizontalTextAlignment="Start"
               FontSize="Medium"
               FontAttributes="Italic"
               SearchButtonPressed="OnEntryCompleted" />
```
which completely solves your life. ;)


![SearchBar](/assets/img/xamarin2.jpeg)