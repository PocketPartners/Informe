<p align="center">
  <img src="images/UpcLogo.png" alt="Logo de UPC" width="100%">
</p>

<div align="center">

# Universidad Peruana de Ciencias Aplicadas

## Carrera de Ingeniería de Software
</div>

<div align="center">

Ciclo: 2024 - 1

Curso: Desarrollo de Aplicaciones Open Source

Sección: SW58

Profesor: Efraín Ricardo Bautista Ubillús

“Informe de Trabajo Final”

Startup: FairFinance

Producto: PocketPartners

Grupo: 3

|          Integrantes           |   Código   |
| :----------------------------: | :--------: |
| Carbajal Pozzo, Joaquín Alonso | U202121881 |
|  Cisneros Tafur, Diego Rafael  | U20221A715 |
|   Jarama Peñaloza, Fiorella    | U202120418 |
|      Ramos Carpio, Karen       | U20201E493 |
| Ventura Allasi, Randel Russell | U201910669 |

Abril 2024

</div>

# **Registro de Versiones**

<table>
  <thead>
    <tr>
        <th>Versión</th>
        <th>Fecha</th>
        <th>Autor</th>
        <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
  <tr>
      <td><strong>TB1</strong></td>
      <td>Sábado 13 de Abril</td>
      <td>
        <ul>
          <li>Carbajal Pozzo, Joaquín Alonso</li>
          <li>Cisneros Tafur, Diego Rafael</li>
          <li>Jarama Peñaloza, Fiorella</li>
          <li>Ramos Carpio, Karen</li>
          <li>Ventura Allasi, Randel Russell</li>
        </ul>
      </td>
      <td>
        Se han incluído los siguientes capítulos:
        <ul>
          <li>Capítulo I: Introducción</li>
          <li>Capítulo II: Requirements Elicitation & Analysis</li>
          <li>Capítulo III: Requirements Specification</li>
          <li>Capítulo IV: Product Design</li>
          <li>Avance del Capítulo V: Product Implementation, Validation & Deployment hasta el punto 5.2.1.8</li>
          <li>Avance de Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
  </tr>
  </tbody>
</table>

# **Project Report Collaboration Insights**

URL Project Report (Github): https://github.com/PocketPartners/Informe

# **Tabla de Contenido**

- [Registro de Versiones](#registro-de-versiones)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#Capítulo-I-Introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#Capítulo-II-Requirements-Elicitation-&-Analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#23-ubiquitous-language)
- [Capítulo III: Requirements Specification](#Capítulo-III-Requirements-Specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#Capítulo-IV-Product-Design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment](#Capítulo-V-Product-Implementation-Validation--Deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint n](#521-sprint-n)
      - [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n) -[5.2.1.2. Sprint Backlog n](#5212-sprint-backlog-n)
      - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Capítulo I Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# Capítulo II Requirements Elicitation & Analysis

## 2.1. Competidores
### 2.1.1. Análisis Competitivo

<table>
    <thead>
        <tr >
            <th colspan=6 style="text-align: center">
				<h2>
					Competitive Analisis Landscape
				</h2>
			</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan=2 rowspan=2 style="text-align: center" align="center">¿Por qué llevar a cabo este análisis?</td>
            <td colspan=4 style="text-align: center" align="center">¿Quiénes son nuestros principales competidores?</td>
        </tr>
		<tr>
            <td colspan=4 style="text-align: center" align="center">Gracias al análisis de la competencia, se logra comprender el entorno competitivo en el que operará nuestro producto. Esto proporciona una visión detallada de quienes son nuestros competidores directos e indirectos, logrando así, trazar 
 una estretegia sólida para alcanzar la máxima exposición de nuestro producto, llegando así a más posibles consumidores.</td>
        </tr>
		<tr>
			<td rowspan=3 style="text-align: center" align="center">Perfil</td>
			<td rowspan=2 style="text-align: center" align="center">Overview</td>
      <td style="text-align: center" align="center">PocketPartners <p align="center"><img src="images/PPLogo.png" alt="Logo PocketPartners" width="25%">
</p></td>
			<td style="text-align: center" align="center">Splittr <p align="center"><img src="images/splittrLogo.png" alt="Logo Splittr" width="40%"></p></td>
			<td style="text-align: center" align="center">Tricount <p align="center"><img src="images/tricountLogo.png" alt="Logo Tricount" width="40%"></p></td>
			<td style="text-align: center" align="center">Splitwise <p align="center"><img src="images/splitwiseLogo.png" alt="Logo Splitwise" width="40%"></p></td>
		</tr>
		<tr>
			<td style="text-align: center" align="center">Plataforma que busca facilitar el proceso de división de costos en diversas situaciones, con varias herramientas que son de utilidad en dicho momento</td>
			<td style="text-align: center" align="center">Plataforma que busca dividir los gastos grupales en viajes o comidas.</td>
			<td style="text-align: center" align="center">Plataforma colaborativa que busca dividir todo tipo de gastos grupales.</td>
			<td style="text-align: center" align="center">Plataforma que busca, de forma colaborativa, llevar un recuento de todos los gastos grupales que se hacen.</td>
		</tr>
		<tr>
			<td style="text-align: center" align="center">Ventaja Competitiva ¿Qué valor ofrecen a los clientes</td>
			<td style="text-align: center" align="center"><ul><li>Organización por grupos y etiquetas</li> <li>Notificaciones en tiempo real</li> <li>Beneficios adicionales por plan premium</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Simplicidad de la plataforma</li> <li>Exportar a pdf o cvs</li> <li>No requiere registro</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>División desigual de gastos</li> <li>Guardado de fotos</li> <li>Notificaciones en tiempo real</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Facilidad de uso</li> <li>Sincronización en la nube</li> <li>Métodos de pago integrados</li> <li>Funciones pro adicionales</li></ul> </td>
		</tr>
		<tr>
			<td rowspan=2 style="text-align: center" align="center">Perfil del Marketing</td>
			<td style="text-align: center" align="center">Mercado Objetivo</td>
			<td style="text-align: center" align="center"><ul><li>Viajeros que busquen dividir sus gastos</li> <li>Roomates que quieran dividir los gastos del hogar</li> <li>Grupos de personas que desean dividir los gastos de una cena</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Viajes</li> <li>Casas compartidas</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Parejas que desean dividir gastos</li> <li>Viajeros que quieren gestionar sus compras</li> <li>Comapñeros de piso</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Viajeros</li> <li>Compañeros de piso</li> <li>Parejas</li> <li>Grupos de amigos</li></ul> </td>
		</tr>
		<tr>
			<td style="text-align: center" align="center">Estrategias de Marketing</td>
			<td style="text-align: center" align="center"><ul><li>Uso de publicidad en redes sociales</li> <li>Recomendación de voz a voz</li> <li>Prueba gratis de 30 días del plan premium para lograr retención</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Promoción de la app en su cuenta de Twitter</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Presentación de referencias en su landing page</li> <li>Cuentas activas de Facebook y Twitter</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Presentación en una landing page vistosa</li> <li>Fácil acceso a los contactos para invitar más personas</li> <li>Página de redes sociales</li></ul> </td>
		</tr>
		<tr>
			<td rowspan=3 style="text-align: center" align="center">Perfil del Producto</td>
			<td style="text-align: center" align="center">Productos & Servicios</td>
			<td style="text-align: center" align="center">Sitio web para el registro y uso de nuestro aplicativo</td>
			<td style="text-align: center" align="center">Aplicativo móvil para el uso de la solución</td>
			<td style="text-align: center" align="center">Aplicativo móvil para el uso de la solución</td>
			<td style="text-align: center" align="center">Aplicativo móvil para el uso de la solución</td>
		</tr>
		<tr>
			<td style="text-align: center" align="center">Precios & Costos</td>
			<td style="text-align: center" align="center"></td>
			<td style="text-align: center" align="center"><ul><li>Pase de un mes - 2.90 soles</li> <li>Suscripción de un año - 11.90 soles</li> <li>Pase de por vida - 39.90 soles</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Suscripción de un mes - 12.90 soles</li> <li>Suscripción de un año - 35.90 soles</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Suscripción de un mes - 19.90 soles</li> <li>Suscripción de un año - 149.90 soles</li></ul> </td>
		</tr>
		<tr>
			<td style="text-align: center" align="center">Canales de distribución (web/móvil)</td>
			<td style="text-align: center" align="center">Plataforma web</td>
			<td style="text-align: center" align="center">Plataforma móvil</td>
			<td style="text-align: center" align="center">Plataforma móvil</td>
			<td style="text-align: center" align="center">Plataforma móvil</td>
		</tr>
		<tr>
			<td rowspan=4 style="text-align: center" align="center">Análisis SWOT</td>
			<td style="text-align: center" align="center">Fortalezas</td>
			<td style="text-align: center" align="center"><ul><li>Canales de atención disponibles</li> <li>Cálculo automático de saldos</li> <li>Uso de etiquetas para categorizar y filtrar las transacciones</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Funciona offline</li> <li>Se sincroniza de forma automática con nuestros amigos</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Uso de imágenes como evidencia</li> <li>Uso de claves de color para mejor visualización</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Integración con cuentas de banco para realizar los pagos dentro de la misma aplicación</li> <li>División en partes iguales o desiguales</li></ul> </td>
		</tr>
		<tr>
			<td style="text-align: center" align="center">Debilidades</td>
			<td style="text-align: center" align="center"><ul><li>Requiere de conección a internet</li> <li>No soporta muchos idiomas</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>El diseño es demasiado simple</li> <li>Carece de diferenciadores con la competencia</li> <li>Cobra por features que se encuentran gratis en otras aplicaciones</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>La interfaz no es fácil de usar</li> <li>Cobra por features que se encuentran gratis en otras aplicaciones</li></ul> </td>
			<td style="text-align: center" align="center"><ul><li>Te da una cantidad de gastos limitados en el plan gratuito</li> <li>Los planes premium son demasiado costosos</li></ul> </td>
		</tr>
		<tr>
			<td style="text-align: center" align="center">Oportunidades</td>
			<td style="text-align: center" align="center"><ul><li>Es posible agregar más funcionalidades</li> <li>Ya se está empezando a crear un mercado gracias a las otras apps</li></ul> </td>
			<td style="text-align: center" align="center">Se puede agregar un poco más de profundidad al diseño</td>
			<td style="text-align: center" align="center">Se puede mejorar la interfaz para que sea más intuitiva</td>
			<td style="text-align: center" align="center">Es la aplicación con más features</td>
		</tr>
		<tr>
			<td style="text-align: center" align="center">Amenazas</td>
			<td style="text-align: center" align="center">Es comlpicado competir con aplicaciones ya establecidas en el mercado</td>
			<td style="text-align: center" align="center">Sigue quedándose atrás en la cantidad de features que tiene comparado con la competencia</td>
			<td style="text-align: center" align="center">Los consumidores están acostumbrados a aplicaciones intuitivas, por lo que aprender a utilizar una app va a ser complicaco para algunos usuarios</td>
			<td style="text-align: center" align="center">Los precios altos ocasionan que los usuarios no deseen pagar la suscripción</td>
		</tr>
    </tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

Gracias al análisis presentado anteriormente, logramos identificar todos los aspectos necesarios para poder idear un plan de acción de forma efectiva. Con el cuál lograremos un mejor producto con mejores resultados después del periodo de lanzamiento. Acontinuación se brindará dicho plan, representado en una serie de estrategias y tácticas para alcanzar lo anteriormente mencionado.

**Afrontando las fortalezas de nuestros competidores:**

* Se sincroniza de forma automática con nuestros amigos
* Uso de imágenes como evidencia
* Uso de claves de color para mejor visualización
* Integración con cuentas de banco para realizar los pagos dentro de la misma aplicación

**Comprendemos que nuestras fortalezas son:**

* Canales de atención disponibles
* Cálculo automático de saldos
* Uso de etiquetas para categorizar y filtrar las transacciones

Entonces, podemos aplicar las siguientes estrategias y tácticas:

**Estrategias**

* Hacer que el usuario se sienta cómodo utilizando nuestra aplicación.

**Tácticas**

* Aplicar códigos de color para que sea más amigable visualmente para los consumidores
* Agregar la opción de agregar imágenes
* Añadir la sincronización en tiempo real

**Afrontando las debilidades de nuestros competidores:**

* El diseño es demasiado simple
* Cobra por features que se encuentran gratis en otras aplicaciones
* La interfaz no es fácil de usar
* Los planes premium son demasiado costosos

**Comprendemos que nuestras debilidades son:**

* Requiere de conección a internet
* No soporta muchos idiomas

Entonces, podemos aplicar las siguientes estrategias y tácticas:

**Estrategias**

* Crear un ambiente intuitivo y visual para que el usuario no se sienta perdido al momento de utilizar el aplicativo, además de brindarle el mejor valor por su dinero

**Tácticas**

* Utilizar un diseño llamativo
* Crear una interfaz dinámica e intuitiva
* No elevar demasiado los costos luego del posicionamiento inicial
* Agregar más features gratis

**Afrontando las oportunidades de nuestros competidores:**

* Se puede agregar un poco más de profundidad al diseño
* Se puede mejorar la interfaz para que sea más intuitiva
* Es la aplicación con más features

**Comprendemos que oportunidades fortalezas son:**

* Es posible agregar más funcionalidades
* Ya se está empezando a crear un mercado gracias a las otras apps

Entonces, podemos aplicar las siguientes estrategias y tácticas:

**Estrategias**

* Aprovecharemos las oportunidades de nuestros competidores para agregar sus mejoras a nuestro aplicativo

**Tácticas**

* Añadir las mejoras de nuestros competidores
* Aprovechar el mercado existente para tener más alcance

**Afrontando las amenazas de nuestros competidores:**

* Sigue quedándose atrás en la cantidad de features que tiene comparado con la competencia
* Los consumidores están acostumbrados a aplicaciones intuitivas, por lo que aprender a utilizar una app va a ser complicaco para algunos usuarios
* Los precios altos ocasionan que los usuarios no deseen pagar la suscripción

**Comprendemos que nuestras amenazas son:**

* Es comlpicado competir con aplicaciones ya establecidas en el mercado

Entonces, podemos aplicar las siguientes estrategias y tácticas:

**Estrategias**

* Utilizaremos las amenazas de los otros competidores para evitar caer en los mismos errores que ellos

**Tácticas**

* No aumentar mucho los precios
* Siempre comparar nuestros features con los de la competencia para no quedarnos por detrás
* Crear una interfaz intuitiva y simple

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas



# Capítulo IV Product Design

## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines

<div style="text-align: justify;">
    <strong>Branding</strong>
    <p>El logotipo de PocketPartners se presenta en forma de un círculo, que sugiere una solución integral y completa para las necesidades técnicas de los clientes. En el centro del círculo se encuentra un bolsillo con unos billetes saliendo de adentro, un símbolo universalmente reconocido para el dinero y como este se guarda en él. El texto 'PocketPartners' se coloca de manera prominente debajo del bolsillo, asegurando que el nombre de la marca sea claramente legible y memorable.
    </p> 
</div>

<p align="center">
      <img src="images/PPLogo.png" alt="Logo PocketPartners" width="50%">
</p>

<div>
  <strong>Typography</strong>
  <p>La tipografía elegida para PocketPartners es "Poppins", una fuente sans-serif moderna y altamente legible. Este tipo de letra se caracteriza por su estilo limpio y contemporáneo, lo que comunica profesionalismo y actualización. La elección de Poppins asegura que el texto en todas las aplicaciones de PocketPartners, desde el logotipo hasta las interfaces de usuario, sea fácilmente legible y tenga una apariencia moderna y uniforme.
  </p>  

  <p>Asimismo también se usa la fuente “Volkhov” para diferentes textos a través del sitio web. Volkhov es una fuente serif de bajo contraste con un carácter robusto, diseñada para proporcionar una experiencia de lectura motivadora. Es una familia de cuatro pesos, lo que la hace adecuada para entornos de texto complejos, siendo económica y legible, contemporánea y prominente.
  </p>
</div>

<p align="center">
      <img src="images/poppins.jpg" alt="Font Poppins" width="50%">
</p>
<p align="center">
      <img src="images/volkhov.jpg" alt="Font Volkhov" width="50%">
</p>


**Spacing**
<p>El spacing mantiene: </p>

* Margen entre texto: 16px
* Margen entre elementos: 24px
* Margen entre secciones: 72px

<p align="center">
      <img src="images/spacing.png" alt="Spacing" width="100%">
</p>

### 4.1.2. Web Style Guidelines

<p align="center">
      <img src="images/web_colors.png" alt="Font Poppins" width="80%">
</p>
<p align="center">
      <img src="images/icons.png" alt="Font Volkhov" width="80%">
</p>
<p align="center">
      <img src="images/buttons.png" alt="Font Volkhov" width="80%">
</p>


## 4.2. Information Architecture
### 4.2.1. Organization Systems

<p align="justify">
  En PocketPartners, aplicamos una organización visual del contenido utilizando un sistema de jerarquía visual. Esto significa que resaltamos la información más relevante y esencial en el diseño de nuestras páginas, asegurando que los usuarios encuentren fácilmente lo que están buscando. Además, utilizamos una organización secuencial para guiar a los usuarios a través del proceso de registro y búsqueda de servicios de manera intuitiva.
</p>

<p align="justify">
  En lo que respecta a la categorización de contenido, empleamos una categorización por temas para simplificar la búsqueda de servicios. Los servicios se agrupan en categorías lógicas que se alinean con las necesidades específicas de nuestros usuarios. También organizamos la información según la audiencia principal para proporcionar una experiencia personalizada y relevante para cada usuario.
</p>

### 4.2.2. Labeling Systems

<p align="justify">
  En el proyecto PocketPartners se ha elegido implementar un sistema de etiquetado breve y fácil de comprender para los usuarios. En la barra de navegación, se muestran constantemente etiquetas textuales para las vistas principales, el panel de control y el registro de procesos. Para el flujo principal de la aplicación, los encabezados están presentes en las pantallas, además de que  las secciones del panel de control tienen etiquetas asociadas que informan al usuario sobre el contenido disponible si accede a esas secciones
</p>

### 4.2.3. SEO Tags and Meta Tags

<p align="justify"> 
  Las meta-etiquetas son fragmentos de código HTML que proporcionan información sobre una página web, ayudando en la optimización para motores de búsqueda (SEO), controlando la descripción y título, especificando el conjunto de caracteres, y gestionando la indexación y derechos de autor.   
</p>

<p align="justify">
  Las meta-etiquetas que estan presenten son:
</p>

**Codificacion de caracteres**

<p align="justify"> 
Este meta especifica la codificación de caracteres del documento HTML. En este caso, se establece en "UTF-8", que es una codificación de caracteres ampliamente compatible que incluye una amplia gama de caracteres y es compatible con varios idiomas.
</p>

```
<meta charset="UTF-8"> 
```

**Título**

<p align="justify"> 
Esta es la etiqueta que define el título del documento HTML que se mostrará en la barra de título o pestaña del navegador.67dx
</p>

```
<title>PocketPartners</title>
```

**Autor**

<p align="justify"> 
Este meta elemento proporciona información sobre el autor del documento HTML. En este caso, el autor se establece como "FairFinance".
</p>

```
<meta name="author" content="FairFinance"/>
```

**Letra del proyecto**

<p align="justify"> 
Este elemento `<link>` se utiliza para importar una fuente externa desde Google Fonts. En este caso, se está importando la fuente "Poppins" con un peso de 300 (delgado). La propiedad rel="stylesheet" indica que el archivo enlazado es una hoja de estilos externa.
</p>

```
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
```

### 4.2.4. Searching Systems

**Implementación del Sistema de Búsqueda:**

<p align="justify"> 
El proyecto FastService tiene previsto implementar un sistema de búsqueda que permita a los usuarios encontrar la información que necesitan de forma sencilla e intuitiva. Este sistema se basará en filtros que faciliten la búsqueda y eviten que el usuario se sienta abrumado por la gran cantidad de información disponible. De esta manera, se mejorará la experiencia del usuario al buscar información en la aplicación.
</p>

  - **Crear Etiquetas Personalizadas:**

    <p align="justify"> 
    En la sección de configuración de PocketPartners, los usuarios pueden crear etiquetas personalizadas para categorizar sus gastos. Por ejemplo, podrían crear etiquetas como "Transporte", "Comida", "Entretenimiento", "Alojamiento", etc.
    </p>

  - **Asignar Etiquetas a Transacciones:**

    <p align="justify"> 
    Cada vez que realizan una transacción durante el viaje, como pagar por comidas, transporte o actividades, los usuarios pueden asignar una o más etiquetas a esa transacción. Por ejemplo, si compran boletos para un espectáculo, pueden etiquetar esa transacción como "Entretenimiento".
    </p>

  - **Filtrar Transacciones por Etiquetas:**

    <p align="justify"> 
    Una vez que han registrado varias transacciones etiquetadas, pueden filtrar fácilmente sus transacciones por etiquetas en PocketPartners. Esto les permite ver rápidamente cuánto han gastado en cada categoría durante el viaje y les ayuda a mantener un registro claro de sus gastos relacionados con diferentes aspectos del viaje.
    </p>

### 4.2.5. Navigation Systems

<p align="justify">
La landing page de PocketPartners está diseñada para ser fácil de usar y te ofrece todas las opciones importantes que necesitas:
</p>

- **Iniciar Sesión / Registrarse:**
    
    En la landing page, los usuarios tienen la opción de iniciar sesión si ya tienen una cuenta o registrarse si son nuevos en la plataforma. Estos botones permiten a los usuarios acceder a sus cuentas existentes o crear nuevas cuentas para aprovechar al máximo PocketPartners.
    
- **Barra de Navegación:**
 
    En la landing page, se tiene una barra de navegación que sigue al usuario a medida que va desplazándose por la landing page, conteniendo los nombres de las 3 secciones principales y únicas.

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe

<p align="justify">
En PocketPartners, se emplea el patrón Z en la página de inicio para dirigir a los usuarios de manera eficiente a través del contenido clave. Comienza con el encabezado y mensaje de bienvenida en la esquina superior izquierda, luego pasa horizontalmente por las características que ofrece la aplicación en la esquina superior derecha, continúa diagonalmente hacia la esquina inferior izquierda para más información sobre los planes ofrecidos y lo que nuestros usuarios opinan de nosotros, y finaliza en la esquina inferior derecha con un mensaje que anima a nuestros usuarios a registrarse y una caja de texto para que coloque su email. Este enfoque organizado aumenta la probabilidad de que los usuarios se registren y utilicen la plataforma.
</p>

<p align="center">
      <img src="images/home_wireframe.png" alt="HomeWireframe" width="100%">
</p>

<p align="center">
      <img src="images/caracteristicas_wireframe.png" alt="CaracteristicasWireframe" width="100%">
</p>

<p align="center">
      <img src="images/planes_wireframes.png" alt="PlansWireframe" width="100%">
</p>

<p align="center">
      <img src="images/about_wireframes.png" alt="AboutWireframe" width="100%">
</p>

<p align="center">
      <img src="images/footero_wireframe.png" alt="Footer" width="100%">
</p>

### 4.3.2. Landing Page Mock-up

## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
### 4.6.2. Software Architecture Container Diagrams.
### 4.6.3. Software Architecture Components Diagrams.

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
### 4.7.2. Class Dictionary.

## 4.8. Database Design.
### 4.8.1. Database Diagram
