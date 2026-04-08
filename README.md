# MODULO_2---
---
title: "Algoritmos"
author:
  - name: Tu Nombre
    address: Tu Institución
    email: tu@correo.com
abstract: |
  Aquí va un breve resumen de tu trabajo sobre algoritmos.
output: rticles::springer_article
---
---
```{r}
knitr::opts_chunk$set(echo = TRUE)

# Definición de variables y operaciones básicas
a <- 40
b <- 60
c <- b - a
print(c)

# Resumen de base de datos interna
summary(cars)

plot(pressure)

# Generar 350 datos con media 22 y desviación estándar 5
Z1 <- rnorm(350, 22, 5)

# Graficar los puntos
plot(Z1)

# Obtener la longitud
w1 <- length(Z1)
print(w1)

# Crear una secuencia de la misma longitud para graficar (350 elementos)
x1 <- seq(500, length.out = 350)
plot(Z1, x1)

# Creación de histograma
hist(Z1, main = "Histograma de edades", breaks = 10, col = "lightblue")

# Cálculo y gráfico de densidad
densidad <- density(Z1)
plot(densidad, main = "Gráfico de Densidad de Z1", col = "red")

```
## Ejercicio 1
DNI=910

```{r}
#CONSIGNA: CREAR UN VECTOR QUE TENGA TODOS LOS NUMEROS ENTEROS DESDE EL 1 AL 910.
secuencia_dni<-(1:9)
print(secuencia_dni)
```
## Ejercicio 2
##Calcular la suma de todos los valores del vector secuencia_dni
```{r}
Total<-0
valor_final<-length(secuencia_dni)
for (i in 1:valor_final)
Total<-Total+i
Total
```
## Ejercicio 3
##Repetir ejercicio 2 pero usando Python

valor_final = len(secuencia_dni)
total = 0

for i in range(1, valor_final + 1):
    total += i

print(total)
