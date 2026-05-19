## POO How To
POO How To (Programación orientada a objetos how to) te indica cómo podemos establecer las primcipales relaciones que ya conocemos de Bases de Datos en programación orientada a objetos con C#

!!! info "Títol"
    Es muy inportante tener claros los conceptos de POO en C#

### Entidades y relaciones

```mermaid
classDiagram
class Blog{
    +String codigoHTML
}
class Post{
    +String texto
}
Post "1" <-- "0..M" Blog:esta_publicado_en
class Label{
    +String etiqueta
}
Label "0..M" <-- "0..M" Post:tiene
```

![CSharp Logo](img\csharp_dotnet.png)
![MySQL Logo](img\Logo MySQL.png)
