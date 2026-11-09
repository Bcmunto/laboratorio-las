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
| 1      | brandon_01      | 84.0            | 246.0           |
| 2      | Christopher_02  | 68.0            | 141.0           |
| 3      | doris_03        | 63.0            | 39.0           |

**Cálculo del MTTD promedio:** 71.67 segundos 
**Cálculo del MTTR promedio:** 142.0 segundos 