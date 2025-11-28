# Laboratorios Virtuales de Redes en AWS

## 📋 Descripción del Proyecto

Proyecto dirigido para la asignatura "Redes de Nueva Generación" que consiste en el diseño e implementación de 12 laboratorios prácticos en AWS para fortalecer competencias en redes mediante servicios de nube.

## 👥 Autores

- **Nicolás Carreño Tascón**
- **Juan Manuel Canchala Jiménez**

**Director:** Carlos Olarte

## 🎯 Objetivos

Diseñar e implementar un entorno práctico de redes utilizando Amazon Web Services (AWS) que permita a los estudiantes fortalecer sus conocimientos mediante laboratorios virtuales alineados con el contenido del curso AWS Cloud Practitioner.

## 📚 Contenido del Proyecto

### Laboratorios Incluidos

1. **Lab 1:** Introducción a AWS y Configuración Inicial (60-90 min)
2. **Lab 2:** Fundamentos de Amazon VPC (90-120 min)
3. **Lab 3:** Conectividad a Internet en VPC (90 min)
4. **Lab 4:** Amazon EC2 y Seguridad de Red (120 min)
5. **Lab 5:** Alta Disponibilidad y Multi-AZ (120 min)
6. **Lab 6:** VPC Peering (90 min)
7. **Lab 7:** VPN y Conectividad Híbrida (120 min)
8. **Lab 8:** AWS Transit Gateway (120 min)
9. **Lab 9:** Seguridad Avanzada en Redes (120 min)
10. **Lab 10:** Monitoreo y Troubleshooting (90 min)
11. **Lab 11:** AWS Direct Connect - Conceptual (60 min)
12. **Lab 12:** Proyecto Final Integrador (180-240 min)

### Componentes del Proyecto

- ✅ **12 Laboratorios completos en LaTeX/PDF**
- ✅ **150+ preguntas de evaluación** (cuestionarios tipo Kahoot/Quiz)
- ✅ **Diagramas de arquitectura** para cada laboratorio
- ✅ **Scripts de automatización** (CloudFormation/Terraform)
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
│   ├── lab02_vpc_fundamentos.tex
│   └── ... (hasta lab12)
│
├── cuestionarios/
│   └── banco_cuestionarios.tex    # 150+ preguntas
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

1. Completar los laboratorios en orden secuencial (1 al 12)
2. Leer el marco teórico antes de iniciar la práctica
3. Seguir los pasos detalladamente
4. Completar los cuestionarios después de cada lab
5. **Importante:** Eliminar recursos para evitar cargos

### Para Instructores

1. Revisar el manual del instructor
2. Adaptar el cronograma según necesidades del curso
3. Usar los cuestionarios para evaluación
4. Implementar rúbricas de evaluación incluidas
5. Considerar el proyecto integrador (Lab 12) como evaluación final

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
   - Introducción a AWS y VPC
   - Conceptos esenciales

2. **Intermedio:** Labs 4-6
   - Seguridad y alta disponibilidad
   - Conectividad entre VPCs

3. **Avanzado:** Labs 7-11
   - Conectividad híbrida
   - Seguridad avanzada
   - Monitoreo

4. **Integración:** Lab 12
   - Proyecto completo
   - Todos los conceptos juntos

## 📊 Evaluación

### Componentes de Evaluación
- **Laboratorios prácticos:** 50%
- **Cuestionarios:** 20%
- **Proyecto final (Lab 12):** 30%

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

## 📞 Contacto

**Profesor Director:** Carlos Olarte  
**Asignatura:** Redes de Nueva Generación  
**Universidad:** [Nombre de la Universidad]

## 📄 Licencia

Este material es desarrollado con fines educativos para la asignatura "Redes de Nueva Generación".

## 🙏 Agradecimientos

- AWS por la documentación oficial
- Comunidad de AWS en español
- Profesor Carlos Olarte por la dirección del proyecto
- AWS Free Tier por hacer posible el aprendizaje práctico

## 🚀 Estado del Proyecto

**Estado Actual:** En Desarrollo

### Completado ✅
- [x] Planificación general
- [x] Estructura de carpetas
- [x] Plantilla LaTeX
- [x] Definición de contenidos
- [x] Banco de cuestionarios (estructura)

### En Progreso 🔄
- [ ] Desarrollo Lab 1
- [ ] Desarrollo Labs 2-12
- [ ] Toma de capturas
- [ ] Creación de diagramas

### Pendiente 📋
- [ ] Scripts de automatización
- [ ] Manual del instructor
- [ ] Videos explicativos
- [ ] Revisión final

## 📅 Cronograma

**Duración estimada:** 16 semanas  
**Inicio:** [Fecha]  
**Entrega final:** [Fecha]

Ver `CHECKLIST_ENTREGA.txt` para el cronograma detallado.

---

**Última actualización:** Noviembre 2025  
**Versión:** 1.0
