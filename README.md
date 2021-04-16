# Scanner-Ports
Escaneo de los puertos

## Introducción
Un socket (enchufe), es un método para la comunicación entre un programa del cliente y un programa del servidor en una red. Un socket se define como el punto final en una conexión.

Un socket es también una dirección de Internet, combinando una dirección IP (la dirección numérica única de cuatro partes que identifica a un ordenador particular en Internet) y un número de puerto (el número que identifica una aplicación de Internet particular.

## Sistema Operativo
- Windows 10

## Versión
- Python 3.9.1

## Instalación de dependencias
```python	

> pip install -r requirements.txt

```

## Ejecución
Para que se ejecute automáticamente el scanner de puertos sobre la IP indicada en el puerto o puertos mencionados.

Además, esta los puertos 80 y 8080 como default, en el caso de que no indique puertos.

```python	

> python src\scanner_puertos.py -target 192.168.0.0 -ports 139,1357,1623,1682,8080

```

## Salida
```
Puerto 139:      Abierto
Puerto 1357:     Cerrado
Puerto 1623:     Cerrado
Puerto 1682:     Cerrado
Puerto 8080:     Cerrado
```
