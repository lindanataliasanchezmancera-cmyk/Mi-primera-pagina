# A continuacion implementaremos un codigo sencillo utilizando la libreria turtle para que realice movimientos simulando bajar escalas.

```python
import turtle

tortuga = "t"
espacios = 0

def adelante(camina_adelante):
    global espacios
    print((" " * espacios) + ">" + ("-" * camina_adelante) + "v")
    espacios += camina_adelante + 1

def abajo(camina_abajo):
    for _ in range(camina_abajo):
        print((" " * espacios) + "|")

adelante(5)
abajo(2)

adelante(5)
abajo(2)

adelante(5)
abajo(2)

```
<img width="220" height="171" alt="ESCALA" src="https://github.com/user-attachments/assets/3b1de31d-0707-4e66-877b-78eefa950ef8" />
