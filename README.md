# [Tarea 3] Casos de Prueba
## Algoritmos y Complejidad (2018-01)

### Obtener los casos
```
git clone https://github.com/mudetz/test3.git
```

Revisar constantemente en caso de que se realicen cambios a los casos de prueba

### Problemas

Para probar el resultado de casos (reemplazar con el nombre de archivo que corresponda)
```bash
# Ejecutar el programa redireccionando desde STDIN y el output a un archivo
./parteX < input.txt > mi_outputX.txt

# Usando el diff de git (es más eficiente y colorido)
git diff outputX.txt mi_outputX.txt

# O bien
diff outputX.txt mi_outputX.txt
```
Si no se imprime nada en consola, su resultado es el correcto.

### Tiempos de ejecución sugeridos para el bonus.

Para probar el tiempo de ejecución de casos
```
time ./parteX < input.txt > /dev/null
```

#### Tiempos para la Parte 1

| Archivo | Tiempo (s) |
|:--|--:|
| `small_input.txt` | 0 |
| `large_input.txt` | 5 |
| `huge_input.txt` | 60 |

#### Tiempos para la Parte 2

| Archivo | Tiempo (s) |
|:--|--:|
| `small_input.txt` | 0 |
| `large_input.txt` | 6 |
| `huge_input.txt` | 63 |


