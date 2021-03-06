# Cansat Laika

_CanSat aut贸nomo que mide un perfil atmosf茅rico y transmite las variables e im谩genes desde la estratosfera._

## Mockup y maquetaci贸n 馃殌

_En este repositorio se presentan los dos mockups y su respectiva maquetaci贸n en python._

**Laika GUI:**
<a>
<img width="850" src="https://github.com/DaniSTexe/Telemetry/blob/main/sources/laika_final.jpg">
</a>



### Pre-requisitos 馃搵

_1) Python 3.7.9_

_**Para Windows**: Anaconda_
    
_2) Entorno virtual_

_En el terminal de anaconda lo puede crear usando_

```
conda create -n laika python=3.7.9
```

### Instalaci贸n 馃敡

_Despues de tener el entorno virtual listo_

_En el powershell de anaconda ingrese_

```
activate laika
cd {$path}
conda install pip
```

_Ahora instale los requerimientos_

```
pip install -r requirements.txt
```

_Compruebe la instalaci贸n codificando_
```
python diseno.py 
```
_Deber铆a aparecer la interfaz sin funcionalidad._

_Y una vez se encuentre creado el enlace de comunicaci贸n ejecute_

```
python MAIN.py
```




## Construido con 馃洜锔?

* [Python](https://docs.python.org/3/) - Lenguaje principal
* [Qt-Designer](https://doc.qt.io/qt-5/qtdesigner-manual.html) - Herramienta para la creaci贸n de la interfaz

## Documentaci贸n del proyecto 馃摉

* [Documento](https://github.com/DaniSTexe/laika/blob/main/Documento.pdf)

## Autores 鉁掞笍

* **Oscar Olejua** - *Dise帽o y maquetaci贸n* - [Daniexe](https://github.com/DaniSTexe)
* **Juan Suarez** - *Recepci贸n de datos* - [MrSuaqui](https://github.com/jpsuarezq)
* **Juan Roman** - *Frontend* - [Sebasroman2](https://github.com/sebasroman2)
* **Fritz Ariza** - *Backend* 