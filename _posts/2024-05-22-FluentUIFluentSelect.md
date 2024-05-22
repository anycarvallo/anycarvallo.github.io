---
title: "Fluent UI Blazor"
excerpt: |
   Se complico un poco con las distintas versiones de Fluent para poder hacer funcionar el <FluentSelect> y que ejecute un metodo si selecciono una opcion.
 
tags: [Blazor]
---

Hace tiempo que vengo incursionando con Fluent Blazor y a la hora de usar un <FluentSelect> se complico un poco con las distintas versiones de Fluent para poder hacer que al seleccionar una opcion ejecute un metodo.


```xml
        <FluentSelect TOption="string" Placeholder="Seleccione un Usuario" @bind-Value=@selectedUser @onchange=@OnSelectedUser >
            @foreach (var person in users!)
            {
                <FluentOption Value="@person.Email">@person.Name</FluentOption>
            }
        </FluentSelect>
```

De esta forma funciona correctamente, obviamente hay que definir las variables y el metodo que llamo es `OnselectedUser`
---

