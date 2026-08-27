# 3-DOF Delta Robot with Computer Vision

**Mechatronics Integration | Feb 2025 – Jun 2025**

> **Languages:** English first · Español después

![3-DOF Delta Robot CAD](media/images/Delta_1.jpeg)

---

# English

## Project Overview

This project integrates a **3-DOF Delta parallel robot** with industrial control, machine vision, sensing, and motion logic to perform autonomous Tic-Tac-Toe interaction.

The project demonstrates multidisciplinary mechatronics integration by connecting visual information, PLC control, robot kinematics, sensors, and physical motion within one coordinated system.

## My Role

**Mechatronics Integration**

Main engineering contributions included:

- Integration of Siemens PLC control with the robot workflow.
- TIA Portal automation logic and system coordination.
- Cognex VisionPro and Python machine-vision integration.
- Python Snap7 communication with the Siemens PLC.
- 3-DOF Delta robot motion and positioning logic.
- Mathematical and kinematic analysis using Python / SymPy and MATLAB.
- Sensor integration and interaction logic.
- Positioning, vision-to-motion, and subsystem validation.

## Technologies & Integration

| Area | Technology / contribution |
|---|---|
| Industrial Control | Siemens PLC and TIA Portal |
| Machine Vision | Cognex VisionPro and Python |
| PLC Communication | Python Snap7 |
| Motion Control | 3-DOF Delta mechanism and motor-control logic |
| Mathematical Model | Python / SymPy and MATLAB |
| Sensors | Inputs incorporated into control and interaction logic |
| Validation | Positioning, vision-to-motion coordination, subsystem interaction |

## Engineering Workflow

**Machine Vision → Industrial Control → Motion Logic → Delta Robot → Validation**

The system uses vision-derived information as part of the control workflow so that the robot can coordinate sensing and physical movement rather than operate as an isolated mechanism.

## Engineering Outcomes

- Validated robot positioning and motion behavior.
- Verified coordination between machine vision and robotic movement.
- Validated control logic and subsystem interaction.
- Demonstrated integration across mechanical, electrical, control, and software domains.

## Repository Structure

```text
.
├── src/                 # Python Snap7 controller and Delta-robot control / kinematics
├── plc/                 # TIA Portal archive and PLC documentation
├── vision/              # VisionPro evidence and related project artifacts
├── simulation/          # MATLAB scripts and simulation results
├── media/images/        # CAD and project images
└── docs/                # Role, contribution and system documentation
```

## Python Controller

`src/delta_vision_plc_controller.py` contains the Python control logic under a clear publication-oriented filename. It communicates with the Siemens PLC through Snap7, manages robot positions and homing logic, and includes mathematical operations used in the robotic workflow.

The original project uses PLC address `192.168.0.11`. This address must be changed to match the target PLC and network when the software is used in another environment.

## PLC Project

The supplied TIA Portal project archive is located at:

`plc/tia_portal/delta_control_motors_pneumatics_V19.ap19`

Supporting PLC documentation is available under `plc/documentation/`.

## Simulation & Validation

MATLAB scripts and result images under `simulation/` document part of the kinematic and workspace analysis used during development and validation.

## Large Project Artifacts

Some original files are intentionally separated from the browser-upload package because of their size. See `LARGE_FILES.md` for the Cognex VisionPro project, archived CAD package, and demonstration video, along with recommended Git LFS / GitHub Release options.

---

# Español

## Descripción del proyecto

Este proyecto integra un **robot Delta paralelo de 3 grados de libertad (3-DOF)** con control industrial, visión artificial, sensores y lógica de movimiento para realizar una interacción autónoma de Tic-Tac-Toe.

El proyecto demuestra integración mecatrónica multidisciplinaria al conectar información visual, control mediante PLC, cinemática del robot, sensores y movimiento físico dentro de un solo sistema coordinado.

## Mi función

**Integración Mecatrónica**

Principales contribuciones de ingeniería:

- Integración del control mediante PLC Siemens con el flujo de operación del robot.
- Lógica de automatización y coordinación del sistema mediante TIA Portal.
- Integración de visión artificial utilizando Cognex VisionPro y Python.
- Comunicación entre Python y el PLC Siemens mediante Snap7.
- Lógica de movimiento y posicionamiento del robot Delta de 3-DOF.
- Análisis matemático y cinemático mediante Python / SymPy y MATLAB.
- Integración de sensores y lógica de interacción.
- Validación de posicionamiento, coordinación visión-movimiento e interacción entre subsistemas.

## Tecnologías e integración

| Área | Tecnología / contribución |
|---|---|
| Control industrial | PLC Siemens y TIA Portal |
| Visión artificial | Cognex VisionPro y Python |
| Comunicación con PLC | Python Snap7 |
| Control de movimiento | Mecanismo Delta 3-DOF y lógica de control de motores |
| Modelo matemático | Python / SymPy y MATLAB |
| Sensores | Entradas incorporadas a la lógica de control e interacción |
| Validación | Posicionamiento, coordinación visión-movimiento e interacción entre subsistemas |

## Flujo de ingeniería

**Visión artificial → Control industrial → Lógica de movimiento → Robot Delta → Validación**

El sistema utiliza la información obtenida por visión como parte del flujo de control, permitiendo que el robot coordine percepción y movimiento físico en lugar de operar únicamente como un mecanismo aislado.

## Resultados de ingeniería

- Se validó el posicionamiento y comportamiento de movimiento del robot.
- Se verificó la coordinación entre visión artificial y movimiento robótico.
- Se validó la lógica de control y la interacción entre subsistemas.
- Se demostró integración entre los dominios mecánico, eléctrico, de control y software.

## Estructura del repositorio

```text
.
├── src/                 # Controlador Python Snap7 y lógica/cinemática del robot Delta
├── plc/                 # Proyecto de TIA Portal y documentación del PLC
├── vision/              # Evidencia de VisionPro y artefactos relacionados
├── simulation/          # Scripts de MATLAB y resultados de simulación
├── media/images/        # Imágenes CAD y del proyecto
└── docs/                # Documentación de función, contribución y sistema
```

## Controlador en Python

`src/delta_vision_plc_controller.py` contiene la lógica de control en Python con un nombre adecuado para publicación. Se comunica con el PLC Siemens mediante Snap7, administra posiciones y lógica de homing e incluye operaciones matemáticas utilizadas dentro del flujo robótico.

El proyecto original utiliza la dirección de PLC `192.168.0.11`. Esta dirección debe modificarse para coincidir con el PLC y la red de destino cuando el software se utilice en otro entorno.

## Proyecto PLC

El archivo del proyecto de TIA Portal se encuentra en:

`plc/tia_portal/delta_control_motors_pneumatics_V19.ap19`

La documentación complementaria del PLC se encuentra en `plc/documentation/`.

## Simulación y validación

Los scripts de MATLAB y las imágenes de resultados incluidas en `simulation/` documentan parte del análisis cinemático y de espacio de trabajo utilizado durante el desarrollo y la validación.

## Archivos grandes del proyecto

Algunos archivos originales se separaron intencionalmente del paquete para carga mediante navegador debido a su tamaño. Consulta `LARGE_FILES.md` para información sobre el proyecto Cognex VisionPro, el paquete CAD comprimido y el video de demostración, además de las alternativas recomendadas mediante Git LFS o GitHub Releases.

---

## Author / Autor

**Jacobo Allemann Castro**  
Mechatronics Engineer / Ingeniero Mecatrónico  
Robotics · Controls · Machine Vision · Systems Integration  
Robótica · Control · Visión Artificial · Integración de Sistemas
