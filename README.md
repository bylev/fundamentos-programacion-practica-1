# 📘 Fundamentos de Álgebra - Práctica 1

## 👨‍💻 Información del Estudiante

- **Nombre:** Michelle Cámara González
- **Matrícula:** SW2509008
- **Grupo:** [C]
- **Cuatrimestre:** Primer Cuatrimestre
- **Carrera:** TSU en Desarrollo e Innovación de Software
- **Profesor:** Jorge Javier Pedrozo Romero

---

## 📋 Descripción del Proyecto

Este repositorio contiene mi solución a la práctica de **Fundamentos de Álgebra**, donde implemento funciones en JavaScript para resolver problemas de álgebra básica, preparándome para trabajar con operaciones matriciales más complejas.

## 🎯 Objetivos Alcanzados

- ✅ Dominar variables y tipos de datos en JavaScript
- ✅ Implementar estructuras condicionales
- ✅ Utilizar bucles y funciones
- ✅ Manipular arrays unidimensionales
- ✅ Trabajar con arrays bidimensionales (matrices)
- ✅ Aplicar control de versiones con Git y GitHub

---

## 📊 Progreso de Ejercicios

### Sección 1: Variables y Tipos de Datos (10 pts)
- [x] 1.1 Mi Información (2 pts) ✅
- [x] 1.2 Operaciones Básicas (3 pts) ✅
- [x] 1.3 Área de Rectángulo (2 pts) ✅
- [x] 1.4 Conversión Celsius a Fahrenheit (3 pts) ✅

**Puntos obtenidos: 10/10**

### Sección 2: Condicionales (15 pts)
- [x] 2.1 Par o Impar (3 pts) ✅
- [x] 2.2 Evaluar Nota (4 pts) ✅
- [x] 2.3 Mayor de Tres (4 pts) ✅
- [x] 2.4 Clasificar Edad (4 pts) ✅

**Puntos obtenidos: 15/15**

### Sección 3: Funciones y Bucles (20 pts)
- [x] 3.1 Factorial (5 pts) ✅
- [x] 3.2 Suma Hasta N (4 pts) ✅
- [x] 3.3 Tabla de Multiplicar (5 pts) ✅
- [x] 3.4 Números Pares (6 pts) ✅

**Puntos obtenidos: 20/20**

### Sección 4: Arrays (25 pts)
- [x] 4.1 Suma de Array (4 pts) ✅
- [x] 4.2 Promedio de Array (5 pts) ✅
- [x] 4.3 Encontrar Máximo (6 pts) ✅
- [x] 4.4 Filtrar Mayores (5 pts) ✅
- [x] 4.5 Invertir Array (5 pts) ✅

**Puntos obtenidos: 25/25**

### Sección 5: Arrays Bidimensionales - Matrices (30 pts)
- [x] 5.1 Crear Matriz (6 pts) ✅
- [x] 5.2 Suma de Matriz (6 pts) ✅
- [x] 5.3 Obtener Fila (5 pts) ✅
- [x] 5.4 Obtener Columna (7 pts) ✅
- [x] 5.5 Transponer Matriz (6 pts) ✅

**Puntos obtenidos: 30/30**

---

## 📈 Calificación Final

```
┌────────────────────────────────────────┐
│  REPORTE DE CALIFICACIÓN               │
├────────────────────────────────────────┤
│  Puntos obtenidos: 100/100             │
│  Porcentaje: 100%                      │
│  🎓 Calificación: A - Excelente        │
└────────────────────────────────────────┘
```

![Tests](https://github.com/bylev/fundamentos-programacion-practica-1/actions/workflows/test.yml/badge.svg)

---

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js (versión 14 o superior)
- Git

### Clonar el repositorio
```bash
git clone https://github.com/TU-USUARIO/fundamentos-programacion-practica-1.git
cd fundamentos-programacion-practica-1
```

### Instalar dependencias
```bash
npm install
```

### Ejecutar tests
```bash
npm test
```

### Ejecutar tests en modo watch
```bash
npm run test:watch
```

### Ver cobertura de código
```bash
npm run test:coverage
```

---

## 📁 Estructura del Proyecto

```
fundamentos-programacion-practica-1/
│
├── ejercicios.js           # ⭐ Archivo principal con mis soluciones
├── ejercicios.test.js      # Tests automatizados (no modificar)
├── package.json            # Configuración del proyecto
├── README.md               # Este archivo
├── GUIA_ESTUDIANTES.md     # Guía de referencia
├── GUIA_INSTRUCTOR.md      # Guía del profesor
│
└── .github/
    └── workflows/
        └── test.yml        # Configuración de GitHub Actions
```

---

## 💡 Aprendizajes Clave

### Lo que más me costó
-**Ejercicio 3.3 (Tabla de multiplicar)**: No sabía como colocar mis valoires al array por lo que tuve que investigar y conocí el método __push__.
- **Ejercicio 5.1 (Crear una matriz)**: Sabía que debía usar un for para recorrer las filas, pero se me había olvidado recorrer las columnas.
- **Ejercicio 5.4 (Obtener una columna)**: Pensé al inicio que sería igual al ejercicio anterior pero después de intentarlo me di cuenta que no. Sino que debía recorrer la matriz, agregar mis filas y también mis columnas.
- **Ejercicio 5.5 (Transponer Matriz)**: No quería hacerlo manual entonces investigué si habia una forma de hacerlo mediante un método. Y encontré que el método era __.map()__ por lo que usé el método para crear un nuevo array en el que itera sobre columnas para crear las filas de las matrices transpuestas.

### Lo que más me gustó
- **Arrays Unidimensionales**: Me gustó ver la aplicación de los arreglos unidimensionales y cómo estos se recorren ya que es justo un tema de la unidad 3 en programación estructurada.
- **Arrays Bidimensionales**: Me gustó mi primer contacto con las matrices en programación y como recorrerlas sin embargo creo que es algo complicado que puedo mejorar con más tiempo y con mucha práctica.
- **Testing Automático**: Me gustó mucho poder correr el programa y saber si lo que hacía estaba bien o mal.
- **Programar en JavaScript**: Nunca había usado JavaScript, había visto como declarar algunas variables con una aplicación pero nunca más lo toqué. Y ahorita que lo usé por primera vez me gustó aunque tendría que repasar los métodos.

### Técnicas aplicadas
- Uso de `for` loops para iteraciones
- Operador módulo `%` para determinar paridad
- Arrays dinámicos con `.push()`
- Bucles anidados para matrices.
- Uso de `if` para evaluaciones.
- Uso de método `Math.max()` para encontrar máximos.
- Uso de método `.reverse()` para obtener el arreglo invertido.
- Uso de método `.map()` para obtener matriz transpuesta.

---

## 🔧 Ejemplos de Código

### Uso de método .map(): Transponer matriz
```javascript
function transponer(matriz) {
  return matriz[0].map((_, indiceColumna) =>
    matriz.map(fila => fila[indiceColumna])
  );
}
```

### Función favorita: Crear una matriz
```javascript 
function crearMatriz(filas, columnas) {
  const matriz = [];
  for (let i = 0; i < filas; i++) {
    const fila = [];
    for (let j = 0; j < columnas; j++) {
      fila.push(0);
    }
    matriz.push(fila);
  }
 
  return matriz;
}
```

**Por qué me gusta:** Me gusta por que me retó a usar bucles anidados y a recordarme que una matriz está compuesta por filas y columnas.

---

## 📚 Recursos Utilizados

- [MDN Web Docs - JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [JavaScript.info](https://es.javascript.info/)
- [Stack Overflow](https://stackoverflow.com)
- [W3 Schools](https://www.w3schools.com/js/)
- [¿Qué es el map en JavaScript?](https://www.youtube.com/watch?v=33-JeJewSCc)
- Guía del estudiante incluida en el repositorio

---

## 🎯 Próximos Pasos

Este proyecto me prepara para:
- ✨ Operaciones matriciales avanzadas (multiplicación, determinantes)
- 🖼️ Desarrollo de editores de imágenes
- 🔐 Implementación de algoritmos de encriptación
- 📊 Creación de calculadoras científicas
- 💻 Aprender JavaScript

---

## 📝 Historial de Commits

```bash
# Ver mi historial completo
git log --oneline --graph --decorate
```

**Commits destacados:**
* 6d81bd7 feat: Ejercicio 22 resuelto
* c92d319 feat: Ejercicio 21 resuelto
* 835a33a feat: Ejercicio 20 resuelto
* c57cce8 feat: Ejercicio 19 resuelto
* b0bae90 feat: Ejercicio 18 resuelto
* 1fccf90 feat: Ejercicio 17 resuelto
* aeb33dd feat: Ejercicio 16 resuelto
* bf699b3 feat: Ejercicio 15 resuelto
* d69fe7f feat: Ejercicio 14 resuelto
* df2aa6c feat: Ejercicio 13 resuelto
* e5891d2 feat: Ejercicio 12 resuelto
* c10717b feat: Ejercicio 11 resuelto
* 7b09e1d feat: Ejercicio 10 resuelto
* 6bfe620 feat: Ejercicio 9 resuelto
* e936395 Ejercicio 9 resuelto
* 960afde feat: Ejercicio 8 resuelto
* 64324b5 feat: Ejercicio 7 resuelto
* 2673d03 feat: Ejercicio 6 resuelto
* 857d29f feat: Ejercicio 5 resuelto
* 96f07f2 feat: Ejercicio 5 resuelto
* 8f01cd2 feat: Ejercicio 4 resuelto
* e4ee418 feat: Ejercicio 3 resuelto
* b431efd feat: Ejercicio 2 resuelto
* afc9bb2 Ejercicio 1 resuelto

---

## 🤝 Agradecimientos

- **Profesor Jorge Javier Pedrozo Romero** por retarnos a nosotros mismos y ayudarnos con las herramientas que nos servirán para nuestro desarrollo laboral.
- **Compañeros del Grupo [C]** por ser un grupo que se destaca en hacer reír, por pedir ayuda cuando lo necesitan.
- **Tecnológico de Software** por los maestros y su plan de estudios que me ayuda a crecer.

---

## 📧 Contacto

- **Email Institucional:** [michelle.camara@tecdesoftware.edu.mx]
- **GitHub:** [@bylev](https://github.com/bylev)

---

## 📄 Licencia

Este proyecto es parte de las actividades académicas del **Tecnológico de Software** y está bajo la licencia MIT.

---

<div align="center">

**⭐ Si te gustó este proyecto, dale una estrella ⭐**

Hecho con 💙 por Michelle Cámara González - 2025

</div>
