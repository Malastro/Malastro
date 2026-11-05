# Hola, soy Guillermo Cuevas 👋

Especializándome en **Ingeniería de Identidades (IAM)**, arquitecturas de directorio híbridas y seguridad del plano de control de identidad. Enfocado en el ciclo de vida de usuarios (JML), modelos de acceso de mínimo privilegio (Zero Trust / RBAC) y gobernanza en ecosistemas Microsoft (Active Directory & Entra ID).

---

### 🛡️ IAM | Mirador de Montepinar SL

Si Antonio Recio administrara las identidades de Montepinar, exigiría MFA hasta para bajar la basura. Exagerado, sí. Pero en IAM, verificar quién accede nunca está de más.

Bienvenido a **Mirador de Montepinar SL**, una organización ficticia inspirada en *La que se avecina*, donde las juntas son un caos, los vecinos no se fían unos de otros y nadie tiene muy claro quién debería tener las llaves.

Este es el escenario de mis laboratorios de **Identity & Access Management (IAM)**, en los que los problemas cotidianos de la comunidad se convierten en retos reales de seguridad:

- **¿Quién puede entrar?** MFA, autenticación y control de accesos.
- **¿Quién tiene las llaves?** Active Directory, permisos y mínimo privilegio.
- **¿Quién se ha mudado sin avisar?** Ciclo de vida de identidades (JML).
- **¿Quién ha entrado y qué ha hecho?** Sign-in Logs y auditoría.

Porque en Montepinar puede que nadie se fíe de nadie, pero en IAM hay algo que no se negocia: **cada identidad debe tener los permisos que necesita, y ni uno más.**

| **Proyecto** | **Alcance técnico y casos de uso** | **Tecnologías y conceptos** | **Estado** |
|---|---|---|---|
| [**01 · Arquitectura de identidad híbrida**](https://github.com/Malastro/Hybrid-identity-lab) | Integración de Active Directory Domain Services (AD DS) con Microsoft Entra ID mediante sincronización de identidades. Filtrado por unidades organizativas (OU), sincronización de hashes de contraseña y automatización del aprovisionamiento de usuarios. | Windows Server 2022, AD DS, Microsoft Entra ID, Entra Connect Sync, PowerShell, PHS | `Completado` |
| [**02 · MFA y Acceso Condicional en Microsoft Entra ID**](https://github.com/Malastro/Lab_02-Entra_MFA) | Configuración de una política de acceso condicional que exige MFA. Preparación de cuentas de emergencia (*Break-Glass*), evaluación con What If, pruebas en modo *Report-only* y activación de la política. | Microsoft Entra ID, Conditional Access, MFA, Break-Glass, What If | `Completado` |
| [**03 · Ciclo de vida JML**](https://github.com/Malastro/Lab_03-Lifecycle-JML) | Automatización de altas, cambios y bajas con PowerShell. | AD DS, Powershell, Entra Connect Sync, JML, RBAC | `Completado` |
| [**04 · SSO con SAML 2.0 en Microsoft Entra ID**](https://github.com/Malastro/Lab_04-SSO-y-Aprovisionamiento-de-Aplicaciones) | Configuración de una aplicación empresarial y validación del inicio de sesión único con Microsoft Entra ID. Configuración de Entity ID, ACS, NameID y atributos de usuario; análisis de la respuesta SAML con SAML-tracer y comprobación de una sesión autenticada con Amador Rivas (`arivas`). | Microsoft Entra ID, Enterprise Applications, SAML 2.0, SSO, federación de identidades, SAML-tracer | `Completado` |
| [**05 · Access Review & Gobernanza de Identidad (IGA)**](https://github.com/Malastro/05_Gobernanza-de-Identidad-y-Revisi-n-de-Acceso) | Desarrollo de una auditoría automatizada con PowerShell para detectar asignaciones de acceso no contempladas en una matriz de accesos esperados e identificar permisos asociados a cuentas inactivas. Generación de informes CSV con hallazgos clasificados por criticidad y recomendaciones de revisión, además de un informe ejecutivo en Markdown. | PowerShell, IGA, CSV, auditoría de accesos, matriz de accesos esperados, mínimo privilegio, ciclo de vida de identidades (JML) | `Completado`|
| [**06 · PAM: Gestión de Accesos Privilegiados**](https://github.com/Malastro/Lab-06-Privileged-Access-Management-PAM-) | Diseño de un modelo de control de cuentas privilegiadas para identificar administradores, detectar asignaciones excesivas y aplicar el principio de mínimo privilegio. Simulación de solicitudes de elevación temporal de permisos, aprobación, caducidad y auditoría de las actividades administrativas mediante PowerShell y datos ficticios. | PAM, Active Directory, PowerShell, RBAC, mínimo privilegio, Just-in-Time (JIT), Just Enough Administration (JEA), auditoría de accesos | `Completado` |
| [**07 · Investigación de inicios de sesión en Microsoft Entra ID**](https://github.com/Malastro/Lab-07-Entra-ID-Sign-in-Logs/tree/main) | Análisis de Sign-in Logs en Microsoft Entra ID para diagnosticar fallos de autenticación, auditar el impacto de Acceso Condicional y MFA, e investigar eventos mediante códigos de error. | Microsoft Entra ID, Sign-in Logs, diagnóstico de autenticación, Acceso Condicional, análisis de eventos, troubleshooting | `Completado` |
| [**08 · Privileged Identity Management (PIM) y acceso JIT**](https://github.com/Malastro/Lab_08-Microsoft-Entra-ID-PIM-Privileged-Management-Just-in-Time-JIT-Access) | Configuración de Microsoft Entra PIM para eliminar privilegios permanentes mediante asignaciones elegibles y activación Just-in-Time (JIT). Aplicación de requisitos de MFA, justificación, flujos de aprobación y auditoría de actividad privilegiada. | Microsoft Entra PIM, Just-in-Time (JIT), Zero Standing Privileges, RBAC, MFA, auditoría de roles | `Completado` |

---

📫 **Contacto:** [LinkedIn](https://www.linkedin.com/in/guillermocuevasarroyo)
