###
> ___cast3___

Proyecto_2/Programaciòn2

[img_arch]: https://user-images.githubusercontent.com/62570607/81858953-2af3b080-952a-11ea-81b4-6782999bfa09.jpg "Previsualizacion archivos"
[img_prog]: https://user-images.githubusercontent.com/62570607/81858935-24653900-952a-11ea-8e68-35d9db080fa0.jpg "Previsualizacion programa"
[img_log]: https://user-images.githubusercontent.com/62570607/81858950-2929ed00-952a-11ea-9e74-5e8ec14a169b.jpg "Logistica"
[img_registro]: https://user-images.githubusercontent.com/62570607/81863569-0fd86f00-9531-11ea-9a98-b327a1105279.png "Registros"
[img_ajust]: https://user-images.githubusercontent.com/62570607/81863560-0e0eab80-9531-11ea-9587-6bc663b5ac21.png  "Ajustes"
[img_ajust2]: https://user-images.githubusercontent.com/62570607/81863562-0ea74200-9531-11ea-8ef0-061e09021af2.png  "Idiomas"
[img_calculo]: https://user-images.githubusercontent.com/62570607/81863563-0ea74200-9531-11ea-9068-474bc6dde004.png  "Suma de raiz"
[img_grafico]: https://user-images.githubusercontent.com/62570607/81863564-0f3fd880-9531-11ea-8c11-1a5bffb5893b.png  "Grafico"
[img_usercontrol]: https://user-images.githubusercontent.com/62570607/81863566-0f3fd880-9531-11ea-9d72-ad90860f3335.PNG  "Datos"
[img_credi]: https://user-images.githubusercontent.com/62570607/81863567-0f3fd880-9531-11ea-9327-252fbbeb6147.png  "Creditos"
###
**Software de programacion 2.**

*Tutor*: Michael Sneider Puentes Palacio

*Estudiante*: Andrés Felipe Castellanos Lizcano

*Universidad*: Universidad de investigacion y desarrollo(UDI)

*Carrera*: Ingenieria de sistemas

> Creo que los animales ven en el hombre un ser igual a ellos que ha perdido de forma extraordinariamente peligrosa el sano intelecto animal.
>Es decir, que ven en él al animal irracional, al animal que ríe, al animal que llora, al animal infeliz.  
>   — **Friedrich Nietzsche**
---

El presente recado es para presentar el software en desarrollo para el proceso de 4 semestre en la Universidad de investigacion y desarrollo(UDI).

Para empezar el software contienen varios temas y esta codificado en c# y desarrollado en Visual studio,asi mismo que en fin de semestre se veran recaldados en este documento.

 Tales temas son:

- Herencia (Class : ClassDesarrollo)

- Encapsulamiento (set:get)

- Listas didacticas (List<>)

- Graficos (charts)

- Librerias  (Dll)

- Futuros temas...

Referencias:
- [Programacion orienta a objetos](https://www.fdi.ucm.es/profesor/jpavon/poo/1.1.Objetos%20y%20Clases.pdf)

- [Video explicativo de encapsulamiento c#](https://www.youtube.com/watch?v=_eyFoySmHPk)

- [Video explicativo de como crear un Dll c#](https://www.youtube.com/watch?v=I-rUqVu0eFA)


---

###
***Herramientas utilizadas para el software***



El programa se hizo con el modelo Winforms de (.net framework), y de ahi mismo las clases que se relacionaban para su mejor manejo.
Entre los objetos usados por el Form serian:

- Buttons
- Panels
- Charts
- Textbox
- ComboBox
- GroupBox

Por tanto también se utilizan eventos que recrean utlidades, como *dobleclick*, *textchanged*, *keypress*, etc. Que en buena medida estos sirven para que el usuario no se salga de sus limites en el programa.

El menu principal está compuesto por varios panel dónde el usuario manipulara para ingresar o recuperar información del mismo.

  - En el primer panel encontramos ciertos datos especificos a ingresar tal panel actuara como principal motor de guardado de datos. Tales datos serian.

![. ][img_registro]


Esté tornara el roll a la entrega de datos a la base de datos. Asi mismo, se crearan registros en un panel que estaran ubicados en el menu principal el cual tendra está informacion cercana al usuario.

![. ][img_usercontrol]

Por otra parte se creara un grafico que contendra informacion en porcentual a los televisores almacenados y esté se modificara si el usuario lo desea. (DLL_graficador)

![. ][img_grafico]

El tercer panel dónde podra hacer un evento de suma de raiz, esto significa que con el fin que una seria de numeros digitados, se sumen cada uno de los dígitos hasta que quede solo un dígito.
Y se añade de forma como Librerias (DLL_Sumatoria_raiz).

![. ][img_calculo]

> **Ejemplo**

> ___123 = 6___


Por ultimo tenemos un panel que esta puesto exclusivamente para la ayuda linguistica del usuario, ya que procedemos de forma no siempre en español.

![. ][img_ajust]   ![. ][img_ajust2]

Y abajo de esto, hay un boton para mostrar creditos, en los diferentes idioma, danto asi fin a la idea de los desarrolladores para su proyecto.

![. ][img_credi]

---


###
***Tema del programa diseñado.***

***Televisores***

El programa está diseñado para almacenar información puntual acerca de un manejo de informacion misma, es decir, está informacion se tendra en el mismo, tal informacion sera;Cantidad de televisores, cuantas pulgadas tiene, que resolucion,marca del producto y propietario.


![. ][img_log]

Por lo tanto el software está diseñado para un almacen, que en si disponga del suficiente espacio y informacion clara del uso de este.
Asi mismo se graficara su porcentaje de cantidad de televisores correspondiente a la marca.Asi si disponen de un proveedor esté tendra información clara del manejo que tiene en el almacen.

En principal formato se subira un ejecutable para la calificacion de este mismo por el docente.




---


###
***Instalacion del software.***



- Descargas los siguientes archivos.(Obligatorio)  
(Ubicados en [Programa_portable](https://github.com/cast3/cast3/tree/master/Programa_portable) )

- [x] 1. DLL_graficador.dll

- [x] 2. DLL_Sumatoria_raiz.dll

- [x] 3. TP_2.exe

- [x] 4. en-US

- [x] 5. de-De



![. ][img_arch]

- Al haberlos descargado procedemos a guardarlos en un lugar que sea fácil llegar a estos archivos juntos.

- Abrimos el archivo TP_2.exe


![. ][img_prog]
> Listo!.

```
Console.writeLine("Hello wordl")
Console.readLine()
```
