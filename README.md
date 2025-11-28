# Laboratorios Virtuales de Redes en AWS

## 📋 Descripción del Proyecto

Proyecto dirigido para la asignatura "Redes de Nueva Generación" que consiste en el diseño e implementación de 8 laboratorios prácticos en AWS para fortalecer competencias en redes mediante servicios de nube.

## 👥 Autores

- **Nicolás Carreño Tascón**
- **Juan Manuel Canchala Jiménez**

## 🎯 Objetivos

Diseñar e implementar un entorno práctico de redes utilizando Amazon Web Services (AWS) que permita a los estudiantes fortalecer sus conocimientos mediante laboratorios virtuales alineados con el contenido del curso AWS Cloud Practitioner.

## 📚 Contenido del Proyecto

### Laboratorios Incluidos

1. **Lab 1:** Introducción a AWS y Configuración Inicial (60-90 min)
2. **Lab 2:** Fundamentos de Amazon VPC (75-90 min)
3. **Lab 3:** Conectividad a Internet en VPC (45-60 min)
4. **Lab 4:** Amazon EC2 y Security Groups (90-120 min)
5. **Lab 5:** Seguridad Avanzada - Network ACLs y VPC Flow Logs (90 min)
6. **Lab 6:** VPC Peering - Conectividad entre VPCs (75 min)
7. **Lab 7:** Monitoreo y CloudWatch (75 min)
8. **Lab 8:** Proyecto Integrador - Arquitectura Completa 3-Tier (120-150 min)

### Componentes del Proyecto

- ✅ **8 Laboratorios completos en LaTeX/PDF**
- ✅ **120+ preguntas de evaluación** (cuestionarios tipo Kahoot/Quiz)
- ✅ **Diagramas de arquitectura** para cada laboratorio
- ✅ **Documentación textual detallada** (sin capturas, excepto Lab 8)
- ✅ **Manual para instructores**
- ✅ **Guía de implementación**

## 📁 Estructura del Repositorio

```
proyectodirigidi/
│
├── proyecto.txt                    # Datos del proyecto
├── PLAN_PROYECTO.txt              # Plan completo de ejecución
├── CHECKLIST_ENTREGA.txt          # Checklist de entregables
├── README.md                      # Este archivo
│
├── laboratorios/
│   ├── plantilla_lab.tex          # Plantilla base LaTeX
│   ├── CONTENIDO_LABORATORIOS.txt # Detalle de cada lab
│   ├── lab01_introduccion_aws.tex
│   ├── lab02_vpc_redes_virtuales.tex
│   ├── lab03_internet_gateway.tex
│   └── ... (hasta lab08)
│
├── cuestionarios/
│   └── banco_cuestionarios.tex    # 120+ preguntas
│
├── recursos/
│   ├── diagramas/                 # Diagramas de arquitectura
│   ├── scripts/                   # Scripts de automatización
│   └── guias/                     # Guías complementarias
│
└── documentacion/
    ├── manual_instructor.pdf
    ├── memoria_proyecto.pdf
    └── guia_implementacion.pdf
```

## 🛠️ Tecnologías y Servicios AWS

### Servicios Core
- Amazon VPC (Virtual Private Cloud)
- Amazon EC2 (Elastic Compute Cloud)
- AWS IAM (Identity and Access Management)
- CloudWatch (Monitoreo y Logs)

### Servicios de Red
- Internet Gateway
- NAT Gateway
- VPC Peering
- AWS Transit Gateway
- Virtual Private Gateway (VPN)
- AWS Direct Connect (conceptual)
- Elastic Load Balancer (ALB)

### Servicios de Seguridad
- Security Groups
- Network ACLs
- AWS Network Firewall
- VPC Flow Logs
- AWS WAF (conceptual)

## 💰 Consideraciones de Costos

- **Objetivo:** Todos los laboratorios diseñados para AWS Free Tier
- **Recomendación:** Eliminar recursos después de cada práctica
- **Costos estimados:** $0.00 siguiendo las instrucciones correctamente
- **Sin Free Tier:** ~$5-10 por completar todos los labs

## 📖 Cómo Usar Este Proyecto

### Para Estudiantes

1. Completar los laboratorios en orden secuencial (1 al 8)
2. Leer el marco teórico antes de iniciar la práctica
3. Seguir los pasos detalladamente
4. Completar los cuestionarios después de cada lab
5. **Importante:** Eliminar recursos para evitar cargos

### Para Instructores

1. Revisar el manual del instructor
2. Adaptar el cronograma según necesidades del curso
3. Usar los cuestionarios para evaluación
4. Implementar rúbricas de evaluación incluidas
5. Considerar el proyecto integrador (Lab 8) como evaluación final

## 🔧 Requisitos Previos

### Conocimientos Necesarios
- Conceptos básicos de redes (TCP/IP, subnetting)
- Uso básico de terminal/línea de comandos
- Navegación en consolas web

### Requisitos Técnicos
- Cuenta de AWS (Free Tier recomendado)
- Navegador web moderno
- Conexión a internet estable
- (Opcional) AWS CLI instalado

## 📝 Compilación de Documentos LaTeX

### Requisitos
```bash
# Instalar distribución LaTeX
# Windows: MiKTeX o TeX Live
# macOS: MacTeX
# Linux: texlive-full
```

### Compilar un laboratorio
```bash
pdflatex lab01_introduccion_aws.tex
pdflatex lab01_introduccion_aws.tex  # Segunda vez para referencias
```

### Usando Overleaf (recomendado)
1. Subir archivo .tex a Overleaf
2. Compilar automáticamente
3. Descargar PDF

## 🎓 Metodología Pedagógica

El proyecto sigue una metodología progresiva:

1. **Fundamentos:** Labs 1-3 (Básico)
   - Introducción a AWS, VPC y conectividad
   - Conceptos esenciales de redes en la nube

2. **Intermedio:** Labs 4-5
   - Cómputo con EC2 y Security Groups
   - Seguridad avanzada con NACLs y Flow Logs

3. **Avanzado:** Labs 6-7
   - Conectividad entre VPCs (Peering)
   - Monitoreo con CloudWatch

4. **Integración:** Lab 8
   - Arquitectura completa 3-tier
   - Todos los conceptos integrados

## 📊 Evaluación

### Componentes de Evaluación
- **Laboratorios prácticos:** 50%
- **Cuestionarios:** 20%
- **Proyecto final (Lab 8):** 30%

### Criterios de Calificación
- Completitud de implementación
- Correcta configuración de servicios
- Documentación de proceso
- Respuestas a preguntas de reflexión

## 🤝 Contribuciones

Este es un proyecto académico. Para sugerencias o mejoras:
1. Documentar el problema o mejora propuesta
2. Incluir capturas o ejemplos
3. Referenciar el laboratorio específico

## 📄 Licencia

Este material es desarrollado con fines educativos para la asignatura "Redes de Nueva Generación".

## 🙏 Agradecimientos

- AWS por la documentación oficial
- Comunidad de AWS en español
- AWS Free Tier por hacer posible el aprendizaje práctico sin costos

## 🚀 Estado del Proyecto

**Estado Actual:** En Desarrollo

### Completado ✅
- [x] Planificación general
- [x] Estructura de carpetas
- [x] Plantilla LaTeX
- [x] Definición de contenidos
- [x] Banco de cuestionarios (estructura)

### En Progreso 🔄
- [x] Desarrollo Labs 1-3
- [ ] Desarrollo Labs 4-8
- [ ] Creación de diagramas
- [ ] Manual del instructor

### Pendiente 📋
- [ ] Completar Labs 4-8
- [ ] Banco completo de cuestionarios
- [ ] Memoria del proyecto
- [ ] Revisión final y presentación

## 📅 Cronograma

**Duración:** 10 semanas de desarrollo activo  
**Inicio:** 2 de septiembre de 2025  
**Entrega final:** 20 de diciembre de 2025

Ver `PLAN_PROYECTO_NUEVO.txt` para el cronograma detallado.

---

**Última actualización:** 28 de noviembre de 2025  
**Versión:** 1.0
