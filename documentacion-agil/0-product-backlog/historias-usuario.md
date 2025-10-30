2.1 Product Backlog
Crea documentacion-agil/0-product-backlog/historias-usuario.md:

markdown
# 📋 Product Backlog - TravelBudget Planner

##  Épica 1: Gestión Básica de Usuarios y Viajes
### US-001: Como usuario, quiero registrarme en la plataforma
**Criterios de Aceptación:**
- [ ] Formulario con email, contraseña y confirmación
- [ ] Validación de email válido y contraseña segura
- [ ] Mensajes de error claros
- [ ] Redirección al dashboard después del registro

**Estimación:** 3 points
**Prioridad:** Alta

### US-002: Como usuario, quiero iniciar sesión en mi cuenta
**Criterios de Aceptación:**
- [ ] Formulario de login con email y contraseña
- [ ] Manejo de credenciales incorrectas
- [ ] Persistencia de sesión
- [ ] Logout funcional

**Estimación:** 3 points
**Prioridad:** Alta

### US-003: Como usuario, quiero crear un nuevo viaje con presupuesto inicial
**Criterios de Aceptación:**
- [ ] Formulario con nombre, presupuesto total y fecha
- [ ] Validación de presupuesto positivo
- [ ] Persistencia en base de datos
- [ ] Feedback visual de éxito

**Estimación:** 5 points
**Prioridad:** Alta

##  Épica 2: Gestión de Gastos Básica
### US-004: Como usuario, quiero añadir gastos manuales a mi viaje
**Criterios de Aceptación:**
- [ ] Formulario para añadir gasto: descripción, categoría, monto
- [ ] Actualización en tiempo real del presupuesto restante
- [ ] Validación de que no supere presupuesto
- [ ] Lista visual de gastos añadidos

**Estimación:** 8 points
**Prioridad:** Alta

### US-005: Como usuario, quiero editar y eliminar gastos
**Criterios de Aceptación:**
- [ ] Botón de editar en cada gasto
- [ ] Formulario pre-llenado para edición
- [ ] Confirmación para eliminar gasto
- [ ] Actualización automática del presupuesto

**Estimación:** 5 points
**Prioridad:** Media

##  Épica 3: Módulos de Cálculo Especializado
### US-006: Como usuario con auto, quiero calcular costos de combustible
**Criterios:**
- [ ] Selector de modelo de auto con consumo promedio
- [ ] Input para kilómetros totales a recorrer
- [ ] Input para precio promedio del combustible
- [ ] Cálculo automático: (km / consumo) × precio

**Estimación:** 13 points
**Prioridad:** Media

### US-007: Como usuario, quiero calcular costos de alojamiento
**Criterios:**
- [ ] Input para costo por noche
- [ ] Selector para cantidad de noches
- [ ] Cálculo automático del total
- [ ] Diferentes tipos de alojamiento (hotel, hostel, Airbnb)

**Estimación:** 8 points
**Prioridad:** Media

##  Épica 4: Dashboard y Comparación
### US-008: Como usuario, quiero ver un dashboard con mis viajes
**Criterios:**
- [ ] Lista de viajes creados
- [ ] Presupuesto usado vs restante
- [ ] Fecha de creación y último update
- [ ] Acceso rápido a cada viaje

**Estimación:** 8 points
**Prioridad:** Media

### US-009: Como usuario, quiero comparar diferentes viajes
**Criterios:**
- [ ] Selección múltiple de viajes para comparar
- [ ] Gráfico comparativo de distribución de gastos
- [ ] Tabla con diferencias de presupuesto
- [ ] Exportación de comparación

**Estimación:** 13 points
**Prioridad:** Baja

**TOTAL ESTIMADO:** 66 points