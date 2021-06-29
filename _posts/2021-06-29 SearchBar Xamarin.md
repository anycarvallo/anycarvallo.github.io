---
title: "SearchBar en Xamarin Forms"
tags: [Xamarin]
---

Le toco el turno a Xamarin Forms [@xamarinhq] tambien, una herramienta muy util para hacer aplicaciones mobile.  

Me encontre con la incognita de como hacer una búsqueda, una barra de búsqueda.  Me puse a hacerla toda a mano usando:

```xaml
<Entry Placeholder="Buscar libro por Titulo / Autor / Palabra clave" 
   FontSize="16"
   Margin="30,0,0,10"
   Completed="OnEntryCompleted" />
```
![Entry](/assets/img/xamarin1.jpeg)

Y agregando icono de lupa a mano.



Pero existe: 

 ```xaml
<SearchBar></>
 ```


```xaml
     <SearchBar Placeholder="Buscar libro por Titulo / Autor / Palabra clave" 
               CancelButtonColor="LightGray"
               PlaceholderColor="LightGray"
               TextColor="Black"
               Margin="0,10,0,10"
               TextTransform="Lowercase"
               HorizontalTextAlignment="Start"
               FontSize="Medium"
               FontAttributes="Italic"
               SearchButtonPressed="OnEntryCompleted" 
```

la cual te soluciona completamente la vida. ;)

![SearchBar](/assets/img/xamarin2.jpeg)






