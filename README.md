# laboratorio-las
Práctica de Seguridad MTTD y MTTR-LAS-ESIT

# Laboratorio: Código Seguro y Modelo OWASP

## 1. Datos generales

- **Nombre completo:** Brandon Christopher Munto Escalante
- **Carné:** 05518639-8
- **Correo institucional:**  bcmuntoe@gmail.com
- **Asignatura:** Lenguajes de Programación con Aspectos de Seguridad 03-2026
- **Fecha:** 08/11/2026

## 2. Descripción

Este laboratorio consiste en desarrollar una aplicación web utilizando Python, implementando controles básicos de seguridad basados en buenas prácticas y el modelo OWASP. Se aplican mecanismos de validación de entradas, consultas parametrizadas, protección de contraseñas, registro de eventos de autenticación y detección de incidentes, incluyendo el cálculo de las métricas MTTD y MTTR.

## 3. Estructura del proyecto

```text
repositorio/
├── proyecto/
│   ├── app.py
│   ├── requirements.txt
│   └── otros archivos
└── README.md
```

## 4. Ejecución del proyecto

**Paso 1.** Clonar el repositorio.

```bash
git clone https://github.com/Bcmunto/laboratorio-las.git
```

**Paso 2.** Ingresar al proyecto.

```bash
cd laboratorio-las/proyecto
```

**Paso 3.** Instalar las dependencias.

```bash
pip install -r requirements.txt
```

**Paso 4.** Ejecutar la aplicación.

```bash
python app.py
```
## 5. Resultados de Pruebas MTTD y MTTR

| Prueba | Usuario         | MTTD (segundos) | MTTR (segundos) |
|--------|-----------------|-----------------|-----------------|
| 1      | brandon_01      | 52.0            | 294.0           |
| 2      | Christopher_02  | 69.0            | 177.0           |

**Cálculo del MTTD promedio:** 60.5 segundos 
**Cálculo del MTTR promedio:** 235.5 segundos 