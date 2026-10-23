# Hola, soy Guillermo Cuevas 👋

Especializándome en **Ingeniería de Identidades (IAM)**, arquitecturas de directorio híbridas y seguridad del plano de control de identidad. Enfocado en el ciclo de vida de usuarios, modelos de acceso de mínimo privilegio (Zero Trust / RBAC) y gobernanza en ecosistemas Microsoft (Active Directory & Entra ID).

---

### 🛡️ Gestión de identidades y accesos (IAM) | Mirador de Montepinar SL

Repositorio de proyectos y laboratorios de ingeniería de identidad, seguridad híbrida y control de accesos (Active Directory On-Premises + Microsoft Entra ID). Se articula con un caso de estudio unificado: la gestión del inquilino corporativo de Mirador de Montepinar SL durante sus primeras y más conflictivas juntas de propietarios.

Implementar una arquitectura Zero Trust en una organización donde nadie confía en nadie no es solo una buena práctica; es una cuestión de supervivencia operativa. El entorno aborda la mitigación de vectores de ataque reales a través del cuadro de actores de la comunidad:

- Presidencia paranoica y control de acceso (Antonio Recio): Enfoque de desconfianza absoluta. Se exige verificar cada intento de autenticación, restringir el acceso a Mis Aplicaciones mediante Acceso Condicional y monitorear cualquier anomalía para evitar que usurpen su cargo de Mayorista.

- Gobernanza, cumplimiento y gestión de cambios (Enrique Pastor): Como Concejal de Juventud y Tiempo Libre, traslada la normativa de la Ley de Propiedad Horizontal al marco de ITIL e IAM. Se aprueban peticiones en comités de control de cambios (CAB), se auditan inicios de sesión y se formalizan directivas de ciclo de vida (JML).

- Amenaza interna por negligencia y credenciales débiles (Amador Rivas): El eslabón más vulnerable frente a ataques de ingeniería social, phishing elemental y reutilización de contraseñas inseguras tipo `merengue123`. Exige la imposición obligatoria de MFA anti-fatiga con coincidencia numérica (Number Matching).

- Shadow IT y rutas no autorizadas (Maxi “Mente Fría”): Intentos de eludir los controles perimetrales oficiales del conmutador central montando servicios paralelos sin supervisión técnica desde el Max & Henry.

- Resiliencia operativa y accesos de rescate (Coque): La conserjería necesita operar tareas rutinarias de mantenimiento sin llaves maestras permanentes. Se aplica el principio de privilegio mínimo y se aíslan dos cuentas nativas de emergencia solo en la nube (Break-Glass) para evitar un bloqueo administrativo total (bloqueo de inquilino) si el servidor local colapsa.

- Intrusión y persistencia no autorizada (Izaskun y Mari Tere): Vectores de acceso oportunistas que aprovechan sesiones desatendidas y brechas en la directiva para infiltrarse en el sistema como si fuera el piso piloto del Bajo B.

- Resistencia al cambio y sesiones inactivas (Goya y Vicente): Usuarios finales con baja fricción tecnológica que dejan equipos encendidos en el salón frente a la tele, requiriendo límites estrictos de caducidad en tokens de sesión y revisiones periódicas de acceso.

- La amenaza persistente latente (El Moroso del 2º C, Germán Palomares): Con el moroso en paradero desconocido y las cuotas sin pagar, la infraestructura adopta el principio fundamental de Zero Trust: Asumir la brecha (Assume Breach). Se parte de la premisa de que el perímetro ya ha sido comprometido y cada recurso debe autenticarse individualmente.

| **Proyecto** | **Alcance técnico y casos de uso** | **Tecnologías y conceptos** | **Estado** |
|---|---|---|---|
| [**01 · Arquitectura de identidad híbrida**](https://github.com/Malastro/Hybrid-identity-lab) | Integración de Active Directory Domain Services (AD DS) con Microsoft Entra ID mediante sincronización de identidades. Filtrado por unidades organizativas (OU), sincronización de hashes de contraseña y automatización del aprovisionamiento de usuarios. | Windows Server 2022, AD DS, Microsoft Entra ID, Entra Connect Sync, PowerShell, PHS | `Completado` |
| [**02 · MFA y Acceso Condicional en Microsoft Entra ID**](https://github.com/Malastro/Lab_02-Entra_MFA) | Configuración de una política de acceso condicional que exige MFA. Preparación de cuentas de emergencia (*Break-Glass*), evaluación con What If, pruebas en modo *Report-only* y activación de la política. | Microsoft Entra ID, Conditional Access, MFA, Break-Glass, What If | `Implementado` |
| **03 · Ciclo de vida JML** | Automatización de altas, cambios y bajas con PowerShell. | AD DS, Powershell, Entra Connect Sync | `Planificado` |
| **04 · SSO y federación de aplicaciones** | Configuración de inicio de sesión único (SSO) para aplicaciones empresariales y estudio de los flujos de autenticación y aprovisionamiento de usuarios. | Microsoft Entra ID, SAML 2.0, OpenID Connect (OIDC), SCIM | `Planificado` |

**Objetivo profesional:** desarrollar experiencia práctica en IAM mediante laboratorios reproducibles, documentación técnica y validación de configuraciones de seguridad.

---

📫 **Contacto:** [LinkedIn](https://www.linkedin.com/in/guillermocuevasarroyo)
