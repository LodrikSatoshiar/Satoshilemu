# Satoshilemu – Flujo de Fondos

**Versión:** 0.2  
**Estado:** Draft  

---

## 1. Propósito

Este documento define cómo se reciben, resguardan, administran y distribuyen los fondos dentro del protocolo Satoshilemu.

Su objetivo es:

- asegurar claridad operativa  
- reducir riesgos  
- permitir trazabilidad  
- alinear el manejo de fondos con los principios del protocolo  

---

## 2. Tipos de fondos

### 2.1 Fondo de distribución  
Destinado a renta básica local e incentivos.

### 2.2 Fondo operativo  
Destinado a infraestructura, educación y operación.

### 2.3 Fondo estratégico (opcional)  
Destinado a expansión, contingencias o nuevas iniciativas.

---

## 3. Origen de fondos

Los fondos pueden provenir de:

- donaciones individuales  
- organizaciones  
- campañas de crowdfunding  
- alianzas estratégicas  
- actividades del ecosistema  

### 3.1 Principio de no condicionamiento  

Los aportes no deben comprometer los principios del protocolo ni imponer condiciones incompatibles.

---

## 4. Banco Descentralizado Satoshilemu

El sistema podrá operar mediante una infraestructura denominada **Banco Descentralizado Satoshilemu**.

Este no corresponde a una institución tradicional, sino a una capa operativa que permite:

- facilitar onboarding de usuarios  
- simplificar pagos dentro del sistema  
- coordinar distribución de fondos  
- reducir fricción en etapas tempranas  

---

## 5. Arquitectura de custodia

### 5.1 Principio general  

Custodia coordinada con transición progresiva hacia mayor descentralización.

---

### 5.2 Etapa inicial  

Puede incluir:

- billeteras coordinadas  
- uso de plataformas tipo Lightning custodial  
- ejecución manual o semi-manual de pagos  

---

### 5.3 Etapa intermedia  

- separación de roles  
- validación compartida  
- control de accesos  
- registro de operaciones  

---

### 5.4 Etapa avanzada  

- esquemas tipo multisig (cuando aplique)  
- múltiples validadores  
- reducción de puntos únicos de fallo  

---

## 6. Estructura de cuentas

El sistema podrá dividirse en:

- cuenta principal (reserva)  
- cuenta de distribución  
- cuentas operativas  
- cuentas de usuarios  

---

### 6.1 Separación de fondos  

Siempre que sea posible:

- fondos de distribución separados de operativos  
- acceso diferenciado por rol  

---

## 7. Recepción de fondos

### 7.1 Métodos  

- pagos on-chain  
- pagos Lightning  
- integraciones (ej: BTCPay Server)  

---

### 7.2 Registro  

Cada ingreso relevante deberá registrar:

- fecha  
- monto  
- red utilizada  
- origen (si se conoce)  
- propósito (si aplica)  

---

## 8. Proceso de distribución

### 8.1 Definición  

Cada ciclo deberá definir:

- monto total  
- beneficiarios  
- monto por persona  
- fecha  
- tipo de distribución  

---

### 8.2 Aprobación  

Debe cumplir:

- revisión por al menos un validador distinto  
- registro de la decisión  

---

### 8.3 Ejecución  

Puede realizarse mediante:

- envíos individuales  
- envíos batch  
- herramientas automatizadas  
- scripts  

---

### 8.4 Confirmación  

- verificación de pagos  
- registro de incidencias  

---

## 9. Automatización (objetivo)

El sistema podrá evolucionar hacia:

- distribución semi-automática  
- asignación a subcuentas  
- reglas programables  
- integración con herramientas como Alby Hub  

---

## 10. Operaciones críticas

Se consideran críticas:

- envío desde cuentas principales  
- cambios de permisos  
- acceso a llaves  
- configuración del sistema  

---

### 10.1 Reglas  

- separación de roles  
- validación adicional  
- registro obligatorio  

---

## 11. Seguridad

### 11.1 Principios  

- minimizar exposición  
- limitar accesos  
- evitar concentración de control  

---

### 11.2 Medidas  

- autenticación fuerte  
- backups  
- revisión de accesos  
- control de permisos  

---

## 12. Registro y trazabilidad

El sistema deberá mantener registro de:

- ingresos  
- distribuciones  
- movimientos relevantes  
- decisiones críticas  

---

## 13. Transparencia

### 13.1 Hacia la comunidad  

Podrá incluir:

- montos distribuidos  
- número de participantes  
- frecuencia de distribución  

---

### 13.2 Interna  

- acceso completo a registros  
- historial de decisiones  

---

## 14. Manejo de errores

### 14.1 Incidencias  

- pagos fallidos  
- errores de monto  
- errores de destinatario  

---

### 14.2 Procedimiento  

- registrar  
- evaluar  
- corregir  
- documentar  

---

## 15. Límites operativos

El sistema podrá definir:

- montos máximos por transacción  
- límites por usuario  
- límites por ciclo  

---

## 16. Auditoría

### 16.1 Interna  

- revisión periódica  
- consistencia de registros  

---

### 16.2 Futura  

- auditoría externa  
- revisión comunitaria  

---

## 17. Riesgos

- centralización temporal  
- errores humanos  
- pérdida de acceso  
- dependencia tecnológica  
- ataques o accesos no autorizados  

---

## 18. Evolución

El sistema deberá evolucionar hacia:

- mayor descentralización  
- mayor automatización  
- mayor transparencia verificable  

---

## 19. Relación con gobernanza

El manejo de fondos deberá respetar:

- reglas de validación  
- separación de roles  
- decisiones vía SIP cuando aplique  

---

## 20. Licencia

Este documento se distribuye bajo licencia GNU GPL v3.
