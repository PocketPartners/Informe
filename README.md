<p align="center">
  <img src="images/UpcLogo.png" alt="Logo de UPC" width="100%">
</p>

<div align="center">

# Universidad Peruana de Ciencias Aplicadas

## Carrera de Ingeniería de Software

</div>

<div align="center">

Ciclo: 2024 - 0 1

Curso: Desarrollo de Aplicaciones Open Source

Sección: SW58

Profesor: Efraín Ricardo Bautista Ubillús

“Informe de Trabajo Final”

Startup: FairFinance

Producto: PocketPartners

Grupo: 03

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

En esta sección se presenta la descripción del startup y los perfiles de los miembros del equipo

### 1.1.1. Descripción de la Startup

La startup, presentada con el nombre de “FairFinance”, se enfoca en facilitar la división de gastos y la gestión de finanzas compartidas entre grupos de personas.Para ello, implementa una plataforma donde los usuarios pueden crear grupos para organizar y compartir gastos, dentro de estos grupos, pueden agregar gastos, especificando quién pagó y cuánto, así como qué parte corresponde a cada persona. La aplicación calcula automáticamente las deudas y los saldos, mostrando claramente quién debe cuánto a quién, es especialmente útil para compañeros de cuarto, parejas, amigos o familiares
que comparten gastos en actividades como viajes, cenas, alquileres, facturas de servicios, compras compartidas. Por otro lado también ofrece características adicionales, como la posibilidad de dividir los gastos de forma equitativa según porcentajes personalizados, la programación de recordatorios de pago y la capacidad de agregar comentarios o notas a cada gasto. Además, proporciona opciones para liquidar deudas directamente a través de servicios como PayPal o Venmo, lo que facilita la simplificación y la transparencia en la gestión de las finanzas compartidas.

Misión: Facilitar la administración equitativa y transparente de gastos compartidos, simplificando la gestión financiera entre amigos, familiares y compañeros de vivienda.

Visión: Convertirnos en la plataforma líder mundial para la gestión colaborativa de gastos, promoviendo la armonía y la transparencia en las relaciones financieras cotidianas.

Logotipo de la Startup:

Logotipo del servicio:

### 1.1.2. Perfiles de integrantes del equipo

<table>
	<thead>
        <tr >
		<td colspan=6 style="text-align: center">
				<h2>
					Intregantes
				</h2>
		</td >
		<td colspan=6 style="text-align: center">
				<h2>
					Descripción
				</h2>
		</td >
		<td colspan=6 style="text-align: center">
				<h2>
					Conocimientos
				</h2>
		</td >
        </tr>	
    </thead>
	<tr >
		<td> Fiorella Jarama - U202120418 </td >
	</tr>
 	<tr >
		<td> Karen Ramos - U20201E493 </td >
	</tr>
 	<tr >
		<td> Joaquín Carbajal - U2021218813 </td >
	</tr>
	<tr >
		<td> Diego Cisneros Tafur - U20221A715 </td >
	</tr>
	<tr >
		<td> Randel Ventura - U201910669 </td >
	</tr>
</table>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

What (Qué)
¿Cuál es el problema?

El problema radica en el desafío de dividir equitativamente los gastos y las facturas compartidas entre amigos, compañeros de cuarto, familiares y grupos, este proceso podía ser complicado y propenso a generar conflictos, ya que calcular quién debe cuánto y a quién puede resultar confuso y tedioso.

When (Cuándo)
¿Cuándo sucede el problema?

El dilema principal surge cuando se tiene situaciones donde hay gastos compartidos que deben dividirse equitativamente entre múltiples personas. Esto puede ocurrir en cualquier momento en el que un grupo de individuos comparta gastos, ya sea en viajes, cenas, facturas de servicios públicos o cualquier otro tipo de transacción económica compartida.

Where (Dónde)
¿A dónde se dirige?

El servicio está direccionado a ser agente de solución para los grupos de personas que comparten responsabilidades económicas de una mismo recinto.

¿Dónde surge el problema?

El problema se manifiesta durante el proceso de dividir y rastrear gastos compartidos. hay una necesidad de registrar fácilmente quién pagó qué, dividir los gastos de manera equitativa y realizar un seguimiento en tiempo real de quién debe dinero a quién, esto permite simplificar y transparentar este proceso, por otro lado, ayuda a prevenir malentendidos y conflictos relacionados con el dinero, mejorando así la experiencia de compartir gastos entre amigos, familiares y compañeros de vivienda.

Who (Quién)
¿Quiénes están involucrados? ¿Quién lo utilizará?

La plataforma será utilizada por una variedad de personas, incluidos amigos que comparten gastos en viajes, compañeros de apartamento que dividen el alquiler y las facturas, parejas que gestionan sus finanzas conjuntas, entre otros grupos que necesitan dividir y rastrear gastos compartidos.

Why (Por qué)
¿Cuál es la causa del problema?

La causa principal del problema es tener un registro manual de quién ha pagado qué y quién debe a quién puede resultar confuso y propenso a errores humanos, lo que puede dar lugar a malentendidos y conflictos.

¿Cuáles son las 2H?
How (Cómo)
¿Cómo se utilizará el producto?.

El producto será empleado para registrar fácilmente los gastos que comparten con otras personas, ingresando detalles como el monto, la descripción y quién participó en la transacción. A partir de ello, los usuarios pueden optar por dividir equitativamente el gasto entre todos los participantes, asignar porcentajes específicos a cada persona o personalizar la división según las contribuciones individuales.

¿Cómo lograremos desarrollar la correcta división de gastos entre nuestros usuarios?

Los técnicos y administradores acceden a la plataforma a través de un navegador. Dicha plataforma les permitirá revisar los cálculos de cada registro, así como la situación financiera global actual. Por otro lado, los usuarios pueden registrar todos los gastos de manera precisa dentro de la aplicación. Esto puede incluir la cantidad total del gasto, una descripción detallada y quiénes participaron en la transacción.Además, proporciona opciones flexibles para dividir los gastos.

.How (Cómo)
¿Cómo se utilizará el producto?

Permite a los usuarios registrar fácilmente quién pagó qué, dividir los gastos de manera equitativa y realizar un seguimiento en tiempo real de quién debe dinero a quién. Al simplificar y transparentar este proceso, podemos ayudar a prevenir malentendidos y conflictos relacionados con el dinero, mejorando así la experiencia de compartir gastos entre amigos, familiares y compañeros de vivienda.

How much (Cuánto)
¿Cuál es la magnitud del problema?

Según La Encuesta Nacional de Capacidades Financieras (2023), el 46% de la población peruana cuenta con un nivel medio de educación financiera y un 13% tiene un nivel adecuado; pero aún hay un 41% que carece de capacidades financieras, según revela la tercera Encuesta Nacional de Capacidades Financieras, desarrollada por la Superintendencia de Banca, Seguros y AFP del Perú (SBS) y la CAF - Banco de Desarrollo de América Latina, presentada en la inauguración de la Semana Mundial del Ahorro 2023. La encuesta tiene como objetivo conocer los niveles de conocimientos, actitudes y comportamientos de los peruanos con relación a temas financieros, así como identificar cambios producidos respecto a los años 2013 y 2019. Esta fue realizada por Ipsos-Perú en el año 2022 e incluyó a peruanos a partir de los 18 años de todos los niveles socioeconómicos en zonas urbanas como rural. Cabe precisar que la encuesta se basó en la metodología de la Organización para la Cooperación y el Desarrollo Económico (OECD) y que se trata de una iniciativa que forma parte de la Política Nacional de Inclusión Financiera. Por otro lado, el porcentaje de adultos que eligió un producto financiero a partir de una comparación o búsqueda de información creció de 56% a 60% entre el 2019 y 2022. Asimismo, el consejo de familiares y amigos mantiene su influencia (40% en 2019 y 42% en el 2022) al momento de elegir un producto financiero. Sin embargo, otras estrategias que incrementan su relevancia fueron la revisión de portales de comparación de precios, tasas y tarifas y la publicidad en redes sociales, con el 21% y 18%, respectivamente. Es ahí que se ve implicado Pocket Partners como alternativa de gestión para una buena salud financiera.

¿Qué porcentaje de usuarios se verá beneficiado por el servicio?

El sistema se dirige principalmente a grupos de personas que comparten gastos, como amigos, compañeros de apartamento, parejas, etc. Por lo tanto, el porcentaje de usuarios que se verán beneficiados depende en gran medida de la prevalencia de este tipo de relaciones y situaciones de compartición de gastos en la población general. En resumen, el porcentaje de usuarios que se verán beneficiados por el servicio probablemente sea significativo, especialmente entre aquellos que comparten gastos de manera regular en diversas situaciones sociales y de convivencia. Sin embargo, el porcentaje exacto variará dependiendo de factores demográficos y culturales específicos.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

- Hemos detectado que a los usuarios les resulta difícil realizar un seguimiento preciso de los gastos compartidos con varias personas, lo que genera confusión, disputas y cálculos manuales que consumen mucho tiempo.
- Hemos observado que los usuarios se sienten frustrados por la falta de actualizaciones en tiempo real sobre los gastos compartidos, lo que genera incertidumbre sobre sus obligaciones financieras y posibles gastos excesivos.
- Hemos notado que los usuarios expresan frustración por el esfuerzo manual necesario para clasificar los gastos con precisión, lo que genera registros desorganizados y dificultades para rastrear los patrones de gastos.
- Hemos detectado que los usuarios desean una integración perfecta con sus cuentas bancarias u otras plataformas financieras para agilizar el seguimiento de gastos y facilitar procesos de reembolso más rápidos.
- Hemos observado que los usuarios luchan con la complejidad de liquidar facturas dentro de grupos, incluidas contribuciones desiguales, pagos parciales y múltiples métodos de pago, lo que genera retrasos y malentendidos.
- Hemos observado que los usuarios expresan preocupaciones sobre la privacidad y la seguridad cuando comparten detalles de gastos con otros, particularmente en situaciones financieras delicadas o entre conocidos.
- Los usuarios enfrentan desafíos al asignar responsabilidades por gastos específicos dentro de los grupos, lo que genera desacuerdos y dificultades para resolver disputas de manera justa.
- Los usuarios enfrentan desafíos al asignar responsabilidades por gastos específicos dentro de los grupos, lo que genera desacuerdos y dificultades para resolver disputas de manera justa.
- Los usuarios se sienten abrumados por el volumen de notificaciones y alertas dentro de la aplicación, lo que genera distracciones y dificultades para priorizar actualizaciones importantes.

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
			<td style="text-align: center" align="center"><ul><li>Suscripción de un mes - 9.90 soles</li> <li>Suscripción de un año - 29.90 soles</li> <li>Suscripción empresarial - 169.90 soles</li></ul> </td>
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

- Se sincroniza de forma automática con nuestros amigos
- Uso de imágenes como evidencia
- Uso de claves de color para mejor visualización
- Integración con cuentas de banco para realizar los pagos dentro de la misma aplicación

**Comprendemos que nuestras fortalezas son:**

- Canales de atención disponibles
- Cálculo automático de saldos
- Uso de etiquetas para categorizar y filtrar las transacciones

Entonces, podemos aplicar las siguientes estrategias y tácticas:

**Estrategias**

- Hacer que el usuario se sienta cómodo utilizando nuestra aplicación.

**Tácticas**

- Aplicar códigos de color para que sea más amigable visualmente para los consumidores
- Agregar la opción de agregar imágenes
- Añadir la sincronización en tiempo real

**Afrontando las debilidades de nuestros competidores:**

- El diseño es demasiado simple
- Cobra por features que se encuentran gratis en otras aplicaciones
- La interfaz no es fácil de usar
- Los planes premium son demasiado costosos

**Comprendemos que nuestras debilidades son:**

- Requiere de conección a internet
- No soporta muchos idiomas

Entonces, podemos aplicar las siguientes estrategias y tácticas:

**Estrategias**

- Crear un ambiente intuitivo y visual para que el usuario no se sienta perdido al momento de utilizar el aplicativo, además de brindarle el mejor valor por su dinero

**Tácticas**

- Utilizar un diseño llamativo
- Crear una interfaz dinámica e intuitiva
- No elevar demasiado los costos luego del posicionamiento inicial
- Agregar más features gratis

**Afrontando las oportunidades de nuestros competidores:**

- Se puede agregar un poco más de profundidad al diseño
- Se puede mejorar la interfaz para que sea más intuitiva
- Es la aplicación con más features

**Comprendemos que oportunidades fortalezas son:**

- Es posible agregar más funcionalidades
- Ya se está empezando a crear un mercado gracias a las otras apps

Entonces, podemos aplicar las siguientes estrategias y tácticas:

**Estrategias**

- Aprovecharemos las oportunidades de nuestros competidores para agregar sus mejoras a nuestro aplicativo

**Tácticas**

- Añadir las mejoras de nuestros competidores
- Aprovechar el mercado existente para tener más alcance

**Afrontando las amenazas de nuestros competidores:**

- Sigue quedándose atrás en la cantidad de features que tiene comparado con la competencia
- Los consumidores están acostumbrados a aplicaciones intuitivas, por lo que aprender a utilizar una app va a ser complicaco para algunos usuarios
- Los precios altos ocasionan que los usuarios no deseen pagar la suscripción

**Comprendemos que nuestras amenazas son:**

- Es comlpicado competir con aplicaciones ya establecidas en el mercado

Entonces, podemos aplicar las siguientes estrategias y tácticas:

**Estrategias**

- Utilizaremos las amenazas de los otros competidores para evitar caer en los mismos errores que ellos

**Tácticas**

- No aumentar mucho los precios
- Siempre comparar nuestros features con los de la competencia para no quedarnos por detrás
- Crear una interfaz intuitiva y simple

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

_Preguntas generales:_

- ¿Cuál es su nombre?
- ¿Cuántos años tiene?
- ¿Cuál es la actividad que más realiza con sus amigos o conocidos?

## _Preguntas para viajeros_

1. Al momento de realizar su viaje, ¿cómo llevan los registros de los gastos de cada uno?
2. Cuando viaja con sus amigos, ¿cómo suelen realizar los pagos?
3. ¿Cuál piensa que es la mayor dificultad al momento de hacer esta operación?
4. ¿Encuentra tardado este proceso de divisón?
5. ¿Qué hace cuando se olvida anotar algún gasto o préstamo realizado?
6. ¿Conoce alguna herrmienta que le pueda ayudar a realizar estos cálculos?

## _Preguntas para amigos que salen a almorzar_

1. Cuando salen a cenar, ¿cómo pagan la cuenta?
2. ¿Cómo hacen para recordar cuánto debe pagar cada uno?
3. ¿Cuánto tiempo se demoran en el proceso del cálculo?
4. ¿Qué hace cuando se olvida anotar algún gasto o préstamo realizado?
5. ¿Conoce alguna herrmienta que le pueda ayudar a realizar estos cálculos?
6. ¿Cuál piensa que es la mayor dificultad al momento de hacer esta operación?

## _Preguntas para compañeros de piso_

1. ¿Cuál es su proceso para dividir los gastos?
2. ¿Cómo lleva registro de los gastos?
3. ¿Cómo lleva registro de los pagos?
4. ¿Conoce alguna manera de hacer más simple este tema?
5. ¿Cuál es la mayor dificultad que tiene al momento de realizar esta operación?
6. ¿Conoce alguna herramienta que le pueda ayudar a realizar estos cálculos?

### 2.2.2 Registro de entrevistas

- Renzo Castro, 20 años.

 <div align="center">
  <img src="images/image-entrevista-renzo.png"/>
 </div>
 
 Link de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a715_upc_edu_pe/EeGZzWgvpHBJr63SdUhU5nMBkNyqKHawW4ybbB9OPmhAcA?e=Vjn5sO
#### Resumen de la entrevista

El entrevistado indica que al momento de viajar o en salidas con amigos y a la vez con personas con las que vive, utiliza herramientas conocidas como papel y lápiz, Google Sheets o Excel para llevar el registro de los gastos. Indica que el proceso de división de gastos es demora y que en ocasiones se olvida de anotar algún gasto o préstamo. Además, menciona que no conoce muchas herramientas que le ayuden con los cálculos o que le faciliten el proceso aparte de Splitwise o otra mas conocida.

## 2.3. Needfinding

### 2.3.1 User Personas

## **User persona viajero**

<p align="center"><img src="images/userAndreaNewman.png" alt="User Andrea Newman" width="100%"></p>

## **User persona que frecuenta restaurantes**

<p align="center"><img src="images/userRodrigoBarrera.png" alt="User Rodrigo Barrera" width="100%"></p>

## **User persona compañero de piso**

<p align="center"><img src="images/userPetraRios.png" alt="User Petra Ríos" width="100%"></p>

### 2.3.2 User task Matrix

<table>
    <thead>
        <tr >
        	<th colspan=1 style="text-align: center"></th>
		<th colspan=2 style="text-align: center">Viajero</th>
		<th colspan=2 style="text-align: center">Frecuenta restaurantes</th>
		<th colspan=2 style="text-align: center">Tiene compañeros de piso</th>
        </tr>
    </thead>
    <tbody>
        <tr>
        	<td style="text-align: center" align="center">TASK</td>
        	<td style="text-align: center" align="center">FREQUENCY</td>
		<td style="text-align: center" align="center">IMPORTANCE</td>
		<td style="text-align: center" align="center">FREQUENCY</td>
		<td style="text-align: center" align="center">IMPORTANCE</td>
		<td style="text-align: center" align="center">FREQUENCY</td>
		<td style="text-align: center" align="center">IMPORTANCE</td>
        </tr>
	<tr>
        	<td style="text-align: center" align="center">Dividir los gastos</td>
        	<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">High</td>
		<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">High</td>
		<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">High</td>
        </tr>
	<tr>
        	<td style="text-align: center" align="center">Calcular los gastos</td>
        	<td style="text-align: center" align="center">Sometimes</td>
		<td style="text-align: center" align="center">Medium</td>
		<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">HIgh</td>
		<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">High</td>
        </tr>
	<tr>
        	<td style="text-align: center" align="center">Mantener registro de deudas</td>
        	<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">High</td>
		<td style="text-align: center" align="center">Sometimes</td>
		<td style="text-align: center" align="center">High</td>
		<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">High</td>
        </tr>
	<tr>
        	<td style="text-align: center" align="center">Mantener registro de pagos</td>
        	<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">High</td>
		<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">Medium</td>
		<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">High</td>
        </tr>
	<tr>
        	<td style="text-align: center" align="center">Rotular los gastos</td>
        	<td style="text-align: center" align="center">Sometimes</td>
		<td style="text-align: center" align="center">Medium</td>
		<td style="text-align: center" align="center">Never</td>
		<td style="text-align: center" align="center">Low</td>
		<td style="text-align: center" align="center">Sometimes</td>
		<td style="text-align: center" align="center">Low</td>
        </tr>
	<tr>
        	<td style="text-align: center" align="center">Uso de múltiples divisas</td>
        	<td style="text-align: center" align="center">Sometimes</td>
		<td style="text-align: center" align="center">High</td>
		<td style="text-align: center" align="center">Never</td>
		<td style="text-align: center" align="center">Low</td>
		<td style="text-align: center" align="center">Sometimes</td>
		<td style="text-align: center" align="center">Medium</td>
        </tr>
	<tr>
        	<td style="text-align: center" align="center">Guardado de boletas</td>
        	<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">Medium</td>
		<td style="text-align: center" align="center">Sometimes</td>
		<td style="text-align: center" align="center">Low</td>
		<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">High</td>
        </tr>
	<tr>
        	<td style="text-align: center" align="center">Uso de archivos excel</td>
        	<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">High</td>
		<td style="text-align: center" align="center">Sometimes</td>
		<td style="text-align: center" align="center">Medium</td>
		<td style="text-align: center" align="center">Neves</td>
		<td style="text-align: center" align="center">Low</td>
        </tr>
	<tr>
        	<td style="text-align: center" align="center">Estar notificados de los consumos de otros</td>
        	<td style="text-align: center" align="center">Always</td>
		<td style="text-align: center" align="center">Medium</td>
		<td style="text-align: center" align="center">Sometimes</td>
		<td style="text-align: center" align="center">Low</td>
		<td style="text-align: center" align="center">Sometimes</td>
		<td style="text-align: center" align="center">Medium</td>
        </tr>
    </tbody>
</table>

### 2.3.3 User Journey Mapping

## **User persona viajero**

<p align="center"><img src="images/mapaAndreaNewman.png" alt="Mapa Andrea Newman" width="100%"></p>

## **User persona que frecuenta restaurantes**

<p align="center"><img src="images/mapaRodrigoBarrera.png" alt="Mapa Rodrigo Barrera" width="100%"></p>

## **User persona compañero de piso**

<p align="center"><img src="images/mapaPetraRios.png" alt="Mapa Petra Ríos" width="100%"></p>

### 2.3.4 Empathy Mapping

Técnica utilizada en el diseño UX y la investigación de usuarios para comprender mejor las necesidades, emociones y comportamientos de los usuarios. Mapa Visual que representa desde la perspectiva del usuario el recorrido de sus necesidades y deseos en la problemática reconocida.

## **Empathy Map User Viajero**

<p align="center"><img src="images/empathyMapUserViajero.png" alt="Empathy Map User Viajero" width="100%"></p>

## **Empathy Map User Frecuente de restaurantes**

<p align="center"><img src="images/empathyMapUserFrecuentedeRestaurantes.png" alt="Empathy Map User Frecuente de Restaurantes" width="100%"></p>

## **Empathy Map User Compañero de Piso**

<p align="center"><img src="images/empathyMapUserCompañerodePiso.png" alt="Empathy Map Compañero de Piso" width="100%"></p>

### 2.3.5 As-Is Scenario Mapping

Visualización y comprensión el estado actual del proceso de la determinación de requerimientos. Este mapa muestra el flujo de actividades, las interacciones entre elementos y las áreas potenciales para mejorar.

### As - Is User Viajero

<p align="center"><img src="images/asIsUserViajero.jpg" alt="AsIs User Viajero" width="100%"></p>

### As - Is User Frecuente de Restaurante

<p align="center"><img src="images/asIsUserFrecuenteDeRestaurante.jpg" alt="AsIs User Frecuente de Restaurante" width="100%"></p>

### As - Is User Compañero de Piso

<p align="center"><img src="images/asIsUserCompañeroDePiso.jpg" alt="AsIs User Compañero de Piso" width="100%"></p>

## 2.4 Ubiquitous Language

# Capítulo III Requirements Especification

## 3.1 To-Be Scenario Mapping

### To - Be User Viajero

<p align="center"><img src="images/toBeUserViajero.jpg" alt="toBe User Viajero" width="100%"></p>

### To - Be User Frecuente de Restaurante

<p align="center"><img src="images/toBeUserFrecuenteDeRestaurante.jpg" alt="toBe User Frecuente de Restaurante" width="100%"></p>

### To - Be User Compañero de Piso

<p align="center"><img src="images/toBeUserCompañeroDePiso.jpg" alt="toBe User Compañero de Piso" width="100%"></p>

## 3.2 User Stories

<table>
  <thead>
    <tr>
        <th>Epic/User Story ID</th>
        <th>Titulo</th>
        <th>Descripción</th>
        <th>Criterios de aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>

  <tbody>
  <!-- US01
  -->
  <tr>
      <td><strong>EP01</strong></td>
      <td>US1 - Notificaciones</td>
      <td>
          Como usuario, quiero recibir notificaciones automáticas cuando se agreguen nuevos gastos compartidos para mantenerme al tanto de las actualizaciones en mis finanzas compartidas y evitar perder información importante.
      </td>
      <td>
        <strong>Escenario 1: Recibir Notificacion</strong> <br>
        <strong>Dado que</strong> estoy utilizando la aplicación PocketPartners en mi navegador web y he activado las notificaciones, <br>
        <strong>Cuando</strong> agregue un nuevo gasto compartido asociado a uno de mis contactos ficticios mientras estoy conectado a la aplicación, <br>
        <strong>Entonces</strong> debería ver una notificación emergente en la pantalla de mi navegador que me informe sobre la actualización en mis finanzas compartidas.
      </td>
      <td>
        EP03
      </td>
  </tr>
  <!-- US02
  -->
  <tr>
      <td><strong>EP02</strong></td>
      <td>US2 - Añadir o Eliminar Transacciones</td>
      <td>
          Como usuario, quiero poder editar o eliminar transacciones registradas incorrectamente para corregir errores y mantener un registro preciso de mis gastos compartidos.
      </td>
      <td>
        <strong>Escenario 1: Observar opciones</strong> <br>
        <strong>Dado que</strong> soy un usuario registrado en la aplicación PocketPartners y he iniciado sesión en mi cuenta, <br>
        <strong>Cuando</strong> acceda a la sección de "Historial de Transacciones" o "Registro de Gastos", <br>
        <strong>Entonces</strong> debería ver una lista de todas las transacciones registradas, con opciones para editar o eliminar cada una. <br>
        <br> 
        <strong>Escenario 2: Editar detalles</strong> <br>
        <strong>Dado que</strong> estoy visualizando la lista de transacciones en la aplicación PocketPartners, <br>
        <strong>Cuando</strong> seleccione una transacción específica que deseo editar, <br>
        <strong>Entonces</strong> debería poder acceder a un formulario de edición donde pueda modificar los detalles de la transacción, como el monto, la descripción o la fecha. <br>
        <br>
        <strong>Escenario 3: Eliminar transaccion</strong> <br>
        <strong>Dado que</strong> deseo eliminar una transacción registrada incorrectamente, <br>
        <strong>Cuando</strong>seleccione la opción para eliminar una transacción específica, <br>
        <strong>Entonces</strong> debería ver una confirmación de eliminación y, al confirmar, la transacción debe eliminarse de mi historial de transacciones de manera permanente.<br>
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US03
  -->
  <tr>
      <td><strong>EP03</strong></td>
      <td>US3 - Division</td>
      <td>
          Como usuario, quiero tener la opción de dividir equitativamente un gasto entre los miembros del grupo para garantizar que todos contribuyan de manera justa y transparente a los gastos compartidos.
      </td>
      <td>
        <strong>Escenario 1: Dividir igualmente</strong> <br>
        <strong>Dado que</strong> soy un usuario registrado en PocketPartners y estoy creando un nuevo gasto compartido, <br>
        <strong>Cuando</strong> ingreso los detalles del gasto, como el monto total y la descripción, <br>
        <strong>Entonces</strong> debería tener la opción de seleccionar la función "Dividir Equitativamente" antes de guardar el gasto.<br>
        <br>
        <strong>Escenario 2: Division</strong> <br>
        <strong>Dado que</strong> he seleccionado la opción "Dividir Equitativamente" al crear un nuevo gasto, <br>
        <strong>Cuando</strong> el gasto se guarda exitosamente, <br>
        <strong>Entonces</strong> el monto total del gasto se dividirá automáticamente de manera equitativa entre todos los miembros del grupo.<br>
      </td>
      <td>
        EP01
      </td>
  </tr>
  <!-- US04
  -->
  <tr>
      <td><strong>EP04</strong></td>
      <td>US4 - Exportar Detalles</td>
      <td>
          Como usuario, quiero poder exportar un resumen de mis transacciones en un formato fácilmente legible, como un archivo PDF o CSV, para poder realizar un seguimiento detallado de mis gastos compartidos y compartir información con otros miembros del grupo si es necesario.
      </td>
      <td>
        <strong>Escenario 1: Encontrar Boton</strong> <br>
        <strong>Dado que</strong> soy un usuario registrado en PocketPartners y deseo exportar un resumen de las transacciones de grupo, <br>
        <strong>Cuando</strong> accedo a la sección de "+ detalles" o "Informe de Gastos", <br>
        <strong>Entonces</strong> debería encontrar una opción claramente etiquetada para exportar el resumen de transacciones.<br>
        <strong>Escenario 2: Exportar resumen</strong> <br>
        <strong>Dado que</strong>  he seleccionado la opción de exportar un resumen de transacciones,<br>
        <strong>Cuando</strong> elija el formato de archivo deseado, como PDF o CSV, <br>
        <strong>Entonces</strong> la aplicación debería generar automáticamente el archivo de resumen en el formato seleccionado y comenzar la descarga.<br>
        <strong>Y</strong> debería poder ver claramente un resumen detallado de mis transacciones, incluyendo la fecha, el monto y la descripción de cada transacción.
      </td>
      <td>
        EP03
      </td>
  </tr>
  <!-- US05
  -->
  <tr>
      <td><strong>EP05</strong></td>
      <td>US5 -Acceso Seguro</td>
      <td>
          Como usuario, quiero que mi información sea accesible unicamente por mi o con una autorización especial para garantizar la seguridad y privacidad de mis datos financieros compartidos.
      </td>
      <td>
        <strong>Escenario 1: Acceso Seguro</strong> <br>
        <strong>Dado que</strong> Soy un usuario registrado en la aplicación PocketPartners, <br>
        <strong>Cuando</strong>  Intento iniciar sesión, la aplicación debe solicitar mi nombre de usuario y contraseña o utilizar Google o Facebook. <br>
        <strong>Entonces</strong> Y si ingreso los detalles correctamente, debería tener acceso a mi cuenta.
        <br>
        <strong>Escenario 2: Olvidar Contraseña</strong> <br>
        <strong>Dado que</strong> he olvidado mi contraseña y necesito restablecerla, <br>
        <strong>Cuando</strong> seleccione la opción "Olvidé mi contraseña" en la pantalla de inicio de sesión, <br>
        <strong>Entonces</strong> debería recibir un enlace de restablecimiento de contraseña en mi correo electrónico registrado para crear una nueva contraseña y acceder a mi cuenta.
      </td>
      <td>
        EP02
      </td>
  </tr>
  <!-- US06
  -->
  <tr>
      <td><strong>EP06</strong></td>
      <td>US06 - Conversor de Moneda Integrado</td>
      <td>
          Como usuario, quiero convertir los montos de mis transacciones a diferentes monedas para facilitar la comprensión de los gastos por parte de los usuarios que usen otras monedas.
      </td>
      <td>
        <strong>Escenario 1: Acceso al Conversor</strong> <br>
        <strong>Dado que</strong> 
        Soy un usuario registrado en la aplicación PocketPartners y deseo convertir un monto de transacción a una moneda diferente, <br>
        <br>
        <strong>Cuando</strong> reviso los detalles de una transacción específica, <br>
        <br>
        <strong>Entonces</strong> debería encontrar una opción claramente etiquetada para acceder al conversor de moneda integrado.<br>
      </td>
      <td>
        EP03
      </td>
  </tr>
  <!-- US07
  -->
  <tr>
      <td><strong>EP07</strong></td>
      <td>US7 - Rastreador de Deuda</td>
      <td>
          Como usuario, quiero poder rastrear las deudas que otros usuarios tienen conmigo y mis deudas pendientes con otros para poder mantener un control sobre mis finanzas.
      </td>
      <td>
        <strong>Escenario 1: Rastreador de Deuda</strong> <br>
        <strong>Dado que</strong> que soy un usuario de la aplicación PocketPartners, <br>
        <strong>Cuando</strong>  selecciono el módulo de "Rastreador de Deuda", <br>
        <strong>Entonces</strong> debería ver una lista de todas las deudas pendientes y el nombre del deudor.
        <br>
        <strong>Escenario 2: Notificar al deudor</strong><br>
        <strong>Dado que</strong> que deseo recordar a un deudor sobre una deuda pendiente, <br>
        <strong>Cuando</strong> seleccione la opción "Notificar al Deudor", <br>
        <strong>Entonces</strong> debería poder enviar una notificación automática al deudor para recordarle sobre la deuda pendiente.
      </td>
      <td>
        EP01, EP02
      </td>
  </tr>
  <!-- US08
  -->
  <tr>
      <td><strong>EP08</strong></td>
      <td>US8 - Balance General</td>
      <td>
          Como usuario, quiero visualizar un balance general de mis gastos para poder tener una vision clara acerca de mis ingresos y egresos.	
      </td>
      <td>
        <strong>Escenario 1: Acceso al Balance General</strong> <br>
        <strong>Dado que</strong> 
        Soy un usuario registrado en la aplicación PocketPartners y deseo visualizar mi balance general, <br>
        <strong>Cuando</strong> Accedo a la sección de "Mi Balance" o "Resumen Financiero", <br>
        <strong>Entonces</strong> Debería ver un resumen detallado de mis ingresos y egresos, incluyendo el saldo actual y los gastos totales.
        <strong>Escenario 2: Filtrar por Fecha</strong> <br>
        <strong>Dado que</strong> que deseo visualizar mi balance general para un período de tiempo específico, <br>
        <strong>Cuando</strong> seleccione la opción "Filtrar por Fecha", <br>
        <strong>Entonces</strong> debería poder seleccionar un rango de fechas personalizado para ver el balance general correspondiente a ese período.
        <strong>Escenario 3: Detalles del Balance</strong> <br>
        <strong>Dado que</strong> estoy revisando el resumen del balance, <br>
        <strong>Cuando</strong> selecciono una categoría específica, <br>
        <strong>Entonces</strong> debería ver la lista de transacciones correspondientes a esa categoría para un análisis más detallado.
      </td>
      <td>
        EP03, EP04
      </td>
  </tr>
  <!-- US09
  -->
  <tr>
      <td><strong>EP09</strong></td>
      <td>Titulo US9</td>
      <td>
          Descripción US09
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US10
  -->
  <tr>
      <td><strong>EP10</strong></td>
      <td>Titulo US10</td>
      <td>
          Descripción US10
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US11
  -->
  <tr>
      <td><strong>EP11</strong></td>
      <td>Titulo US11</td>
      <td>
          Descripción US11
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US12
  -->
  <tr>
      <td><strong>EP12</strong></td>
      <td>Titulo US12</td>
      <td>
          Descripción US12
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US13
  -->
  <tr>
      <td><strong>EP13</strong></td>
      <td>Titulo US13</td>
      <td>
          Descripción US13
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US14
  -->
  <tr>
      <td><strong>EP14</strong></td>
      <td>Titulo US14</td>
      <td>
          Descripción US14
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US15
  -->
  <tr>
      <td><strong>EP15</strong></td>
      <td>Titulo US15</td>
      <td>
          Descripción US15
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US16
  -->
  <tr>
      <td><strong>EP16</strong></td>
      <td>Titulo US16</td>
      <td>
          Descripción US16
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US17
  -->
  <tr>
      <td><strong>EP17</strong></td>
      <td>Titulo US17</td>
      <td>
          Descripción US17
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US18
  -->
  <tr>
      <td><strong>EP18</strong></td>
      <td>Titulo US18</td>
      <td>
          Descripción US18
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US19
  -->
  <tr>
      <td><strong>EP19</strong></td>
      <td>Titulo US19</td>
      <td>
          Descripción US19
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  <!-- US20
  -->
  <tr>
      <td><strong>EP20</strong></td>
      <td>Titulo US20</td>
      <td>
          Descripción US20
      </td>
      <td>
        <strong>Escenario 1: ...</strong> <br>
        <strong>Dado que</strong> ... <br>
        <strong>Cuando</strong> ... <br>
        <strong>Entonces</strong> ...
      </td>
      <td>
        EP01, EP02, ...
      </td>
  </tr>
  </tbody>
</table>

## 3.3 Impact Mapping

#### Mejorar la experiencia de distribución de movimientos financieros grupales.

<p align="center"><img src="images/impactMapUserViajero.png" alt="Empathy Map User Viajero"  width="100%"></p>

#### Digitalizar el 80% de procesos de registro de saldos y movimientos financieros grupales.

<p align="center"><img src="images/impactMapUserFrecuentedeRestaurante.png" alt="Empathy Map User Viajero"  width="100%"></p>

#### Discernir la preocupación constante del uso de diferentes registros de movimientos financieros en los usuarios Compañeros de piso.

<p align="center"><img src="images/impactMapUserCompañerodePiso.png" alt="Empathy Map User Viajero"  width="100%"></p>

## 3.4 Product Backlog

<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>

  <tbody>
    <tr style="text-align: center;">
      <td>1</td>
      <td>US...</td>
      <td>...</td>
      <td style="text-align: justify;">...</td>
      <td>...</td>
    </tr>  
    <tr style="text-align: center;">
      <td>2</td>
      <td>US...</td>
      <td>...</td>
      <td style="text-align: justify;">...</td>
      <td>...</td>
    </tr>  
    <tr style="text-align: center;">
      <td>3</td>
      <td>US...</td>
      <td>...</td>
      <td style="text-align: justify;">...</td>
      <td>...</td>
    </tr>    
  </tbody>

</table>

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

- Margen entre texto: 16px
- Margen entre elementos: 24px
- Margen entre secciones: 72px

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
      <img src="images/footer_wireframe.png" alt="Footer" width="100%">
</p>

### 4.3.2. Landing Page Mock-up

<p align ="justify">
Se elaboró un esquema inicial para la página de inicio, estableciendo la disposición de los elementos. El mock-up resultante ofrece una representación visual detallada de cómo se verán los elementos en la versión final de la página. Este paso permite ajustes y mejoras antes de la implementación del diseño definitivo, asegurando que cumpla con los requisitos establecidos.
</p>

<p align="center">
      <img src="images/home.png" alt="Footer" width="100%">
</p>

<p align="center">
      <img src="images/caracteristicas.png" alt="Footer" width="100%">
</p>

<p align="center">
      <img src="images/planes.png" alt="Footer" width="100%">
</p>

<p align="center">
      <img src="images/about.png" alt="Footer" width="100%">
</p>

<p align="center">
      <img src="images/footer.png" alt="Footer" width="100%">
</p>

## 4.4. Web Applications UX/UI design
### 4.4.1. Web Applications wireframes

<p align="center"><img src="images/wireframeLogIn.jpg" alt="Wireframe de ingreso" width="100%"></p>

<p align="center"><img src="images/wireframeSignUp.jpg" alt="Wireframe de cración de cuenta" width="100%"></p>

<p align="center"><img src="images/wireframeMain.jpg" alt="Wireframe principal" width="100%"></p>

<p align="center"><img src="images/wireframeSideBar.jpg" alt="Wireframe barra lateral" width="100%"></p>

<p align="center"><img src="images/wireframeAdd.jpg" alt="Wireframe agregar" width="100%"></p>

<p align="center"><img src="images/wireframeCreateGroup.jpg" alt="Wireframe crear grupo" width="100%"></p>

<p align="center"><img src="images/wireframePayIn.jpg" alt="Wireframe pago entrante" width="100%"></p>

<p align="center"><img src="images/wireframePayOut.jpg" alt="Wireframe pago saliente" width="100%"></p>

<p align="center"><img src="images/wireframeNewSpent.jpg" alt="Wireframe nuevo gasto" width="100%"></p>

<p align="center"><img src="images/wireframeDivision.jpg" alt="Wireframe división" width="100%"></p>

<p align="center"><img src="images/wireframeExport.jpg" alt="Wireframe exportar" width="100%"></p>

### 4.4.2. Web Application Wireflow Diagram

El usuario tiene una cuenta y desea ingresar para consultar sus movimientos y resumen.
<p align="center"><img src="images/wireflowLogIn.png" alt="Wireflow ingreso" width="100%"></p>

El usuario no tiene una cuenta y desea crearse una para poder emprezar a utilizar la aplicaicón.
<p align="center"><img src="images/wireflowSignUp.png" alt="Wireflow de cración de cuenta" width="100%"></p>

El usuario desea realizar ajustes y cambios en su cuenta
<p align="center"><img src="images/wireflowSidebar.png" alt="Wireflow barra lateral" width="100%"></p>

El usuario busca exportar sus datos para poder presentarselo a sus amigos y tenerlo registrado dentro de su máquina.
<p align="center"><img src="images/wireflowExport.png" alt="Wireflow exportar" width="100%"></p>

El usuario desea agregar un grupo o relizar un nuevo pago.
<p align="center"><img src="images/wireflowAdd.png" alt="Wireflow agregar" width="100%"></p>

El usuario desea crear un grupo
<p align="center"><img src="images/wireflowCreateGroup.png" alt="Wireflow crear grupo" width="100%"></p>

El usuario desea consultar los pagos que le han hecho en sus distintos grupos
<p align="center"><img src="images/wireflowPayIn.png" alt="Wireflow pago entrante" width="100%"></p>

El usuario desea consultar sus pagos realizados y pagos faltantes
<p align="center"><img src="images/wireflowPayOut.png" alt="Wireflow pago saliente" width="100%"></p>

El usuario desea registrar un nuevo gasto y dividirlo con su grupo
<p align="center"><img src="images/wireflowNewSpent.png" alt="Wireflow nuevo gasto" width="100%"></p>

### 4.4.3 Web Application Mock-Ups

<p align="center"><img src="images/mockupLogIn.jpg" alt="Mock-Up de ingreso" width="100%"></p>

<p align="center"><img src="images/mockupSignUp.jpg" alt="Mock-Up de cración de cuenta" width="100%"></p>

<p align="center"><img src="images/mockupMain.jpg" alt="Mock-Up principal" width="100%"></p>

<p align="center"><img src="images/mockupSideBar.jpg" alt="Mock-Up barra lateral" width="100%"></p>

<p align="center"><img src="images/mockupAdd.jpg" alt="Mock-Up agregar" width="100%"></p>

<p align="center"><img src="images/mockupCreateGroup.jpg" alt="Mock-Up crear grupo" width="100%"></p>

<p align="center"><img src="images/mockupPayIn.jpg" alt="Mock-Up pago entrante" width="100%"></p>

<p align="center"><img src="images/mockupPayOut.jpg" alt="Mock-Up pago saliente" width="100%"></p>

<p align="center"><img src="images/mockupNewSpent.jpg" alt="Mock-Up nuevo gasto" width="100%"></p>

<p align="center"><img src="images/mockupDivision.jpg" alt="Mock-Up división" width="100%"></p>

<p align="center"><img src="images/mockupExport.jpg" alt="Mock-Up exportar" width="100%"></p>

### 4.4.4. Web Applications User Flow Diagrams

El usuario tiene una cuenta y desea ingresar para consultar sus movimientos y resumen.
<p align="center"><img src="images/userflowLogIn.png" alt="UserFlow ingreso" width="100%"></p>

El usuario no tiene una cuenta y desea crearse una para poder emprezar a utilizar la aplicaicón.
<p align="center"><img src="images/userflowSignUp.png" alt="UserFlow de cración de cuenta" width="100%"></p>

El usuario desea realizar ajustes y cambios en su cuenta
<p align="center"><img src="images/userflowSideBar.png" alt="UserFlow barra lateral" width="100%"></p>

El usuario busca exportar sus datos para poder presentarselo a sus amigos y tenerlo registrado dentro de su máquina.
<p align="center"><img src="images/userflowExport.png" alt="UserFlow exportar" width="100%"></p>

El usuario desea agregar un grupo o relizar un nuevo pago.
<p align="center"><img src="images/userflowAdd.png" alt="UserFlow agregar" width="100%"></p>

El usuario desea crear un grupo
<p align="center"><img src="images/userflowCreateGroup.png" alt="UserFlow crear grupo" width="100%"></p>

El usuario desea consultar los pagos que le han hecho en sus distintos grupos
<p align="center"><img src="images/userflowPayIn.png" alt="UserFlow pago entrante" width="100%"></p>

El usuario desea consultar sus pagos realizados y pagos faltantes
<p align="center"><img src="images/userflowPayOut.png" alt="UserFlow pago saliente" width="100%"></p>

El usuario desea registrar un nuevo gasto y dividirlo con su grupo
<p align="center"><img src="images/userflowNewSpent.png" alt="UserFlow nuevo gasto" width="100%"></p>

## 4.6. Domain-Driven Software Architecture.

### 4.6.1. Software Architecture Context Diagram.

  <div align="center">
        <img src="images/Context-diagram.png" alt="Context Diagram" width="100%">

  </div>
<p align ="justify">
      En esta imagen podemos evidenciar la relación entre el usuario y la aplicación, 
      así como los servicios que se ofrecen a través de la misma. Además, se muestra la interacción con otros sistemas externos, 
      como el sistema como notificaciones y el sistema de autenticación.
</p>

### 4.6.2. Software Architecture Container Diagrams.

  <div align="center">
      <img src="images/Container-diagram.png" alt="Container Diagram" width="100%">

  </div>
<p align ="justify">
      Este diagrama ilustra la estructura de la aplicación, 
      incluyendo los contenedores que la componen y las tecnologías utilizadas en cada uno. 
      Se observa la interacción entre los contenedores y cómo se comunican para brindar los servicios que el usuario necesita.
</p>

### 4.6.3. Software Architecture Components Diagrams.

  <div align="center">
        <img src="images/Component-diagram.png" alt="Component Diagram" width="100%">
  </div>
<p align ="justify">
      El presente diagrama expone en detalle los componentes que integran la aplicación, 
      incluyendo las interfaces y dependencias entre ellos.
      Se ilustra la estructura interna de la aplicación y la forma en que los 
      distintos componentes mantienen una interconexión para ofrecer los servicios que el usuario demanda.
</p>

## 4.7. Software Object-Oriented Design.

### 4.7.1. Class Diagrams.

  <div align="center">
        <img src="images/PocketPartners-Diagram-Class.png" alt="Class Diagram" width="100%">
  </div>

<p align ="justify">
      En este diagrama de clases se muestran las clases que componen la aplicación PocketPartners, se añadió el patron observer para la notificación de los usuarios que permite mantener informados a los usuarios sobre los cambios en el grupo o otros sistemas importantes como pagos o gastos.

### 4.7.2. Class Dictionary.

<div align="center">
    <h3>User Class</h3>
    <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
          </tr>
      </thead>
      <tbody>
          <tr>
              <td>id</td>
              <td>int</td>
              <td>Identificador único del usuario</td>
          </tr>
          <tr>
              <td>userName</td>
              <td>string</td>
              <td>Nombre del usuario</td>
          </tr>
          <tr>
              <td>fullName</td>
              <td>string</td>
              <td>Nombre Normal del usuario</td>
          </tr>
          <tr>
              <td>email</td>
              <td>string</td>
              <td>Correo electrónico del usuario</td>
          </tr>
          <tr>
              <td>password</td>
              <td>string</td>
              <td>Contraseña del usuario</td>
          </tr>  
      </tbody>
    </table>
    <h3>Group Class</h3>
    <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
          </tr>
      </thead>
      <tbody>
          <tr>
              <td>id</td>
              <td>int</td>
              <td>Identificador único del grupo</td>
          </tr>
          <tr>
              <td>name</td>
              <td>string</td>
              <td>Nombre del grupo</td>
          </tr>
          <tr>
              <td>members</td>
              <td>list</td>
              <td>Lista de miembros del grupo</td>
          </tr>
          <tr>
              <td>expenses</td>
              <td>list</td>
              <td>Lista de gastos del grupo</td>
          </tr>  
      </tbody>
    </table>
    <h3>PaymentHistory</h3>
    <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
          </tr>
      </thead>
      <tbody>
          <tr>
              <td>id</td>
              <td>int</td>
              <td>Identificador único del historial de pagos</td>
          </tr>
          <tr>
              <td>Transactions</td>
              <td>Transaction</td>
              <td>Lista de transacciones representa Expenses y Payments</td>
          </tr>
          <tr>
              <td>date</td>
              <td>date</td>
              <td>Fecha del pago</td>
          </tr>
      </tbody>
    </table>
    <h3>Notificaciones</h3>
    <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
          </tr>
      </thead>
      <tbody>
        <tr>
            <td>id</td>
            <td>int</td>
            <td>Identificador único de la notificación</td>
        </tr>
        <tr>
            <td>user</td>
            <td>User</td>
            <td>Usuario al que se le envía la notificación</td>
        </tr>
        <tr>
            <td>message</td>
            <td>str</td>
            <td>Mensaje de la notificación</td>
        </tr>
        <tr>
            <td>date</td>
            <td>datetime</td>
            <td>Fecha de la notificación</td>
        </tr>
      </tbody>
    </table>
    <h3>Observer</h3>
    <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
          </tr>
      </thead>
      <tbody>
        <tr>
            <td>Users</td>
            <td>list</td>
            <td>Lista de usuarios observados</td>
        </tr>
        <tr>
            <td>Group</td>
            <td>Group</td>
            <td>Grupo observado</td>
        </tr>
        <tr>
            <td>Notificaciones</td>
            <td>list</td>
            <td>Lista de notificaciones observadas</td>
        </tr>
        <tr>
            <td>Reminders</td>
            <td>list</td>
            <td>Lista de recordatorios observados</td>
        </tr>
      </tbody>
    </table>
    <h3>Reminder</h3>
      <table>
        <thead>
            <tr>
                <th>Attribute</th>
                <th>Type</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
          <tr>
              <td>id</td>
              <td>int</td>
              <td>Identificador único del recordatorio</td>
          </tr>
          <tr>
              <td>user</td>
              <td>User</td>
              <td>Usuario al que se le envía el recordatorio</td>
          </tr>
          <tr>
              <td>message</td>
              <td>str</td>
              <td>Mensaje del recordatorio</td>
          </tr>
          <tr>
              <td>date</td>
              <td>datetime</td>
              <td>Fecha del recordatorio</td>
          </tr>
        </tbody>
      </table>
    <h3>Transaction</h3>
    <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
          </tr>
      </thead>
      <tbody>
        <tr>
            <td>id</td>
            <td>int</td>
            <td>Identificador único de la transacción</td>
        </tr>
        <tr>
            <td>amount</td>
            <td>float</td>
            <td>Monto de la transacción</td>
        </tr>
        <tr>
            <td>payer</td>
            <td>User</td>
            <td>Usuario que realiza la transacción</td>
        </tr>
        <tr>
            <td>group</td>
            <td>str</td>
            <td>Grupo al que pertenece la transacción</td>
        </tr>
        <tr>
            <td>type</td>
            <td>enum</td>
            <td>Tipo de transacción (Expense o Payment)</td>
        </tr>
        <tr>
            <td>money</td>
            <td>Type money</td>
            <td>Moneda de la transacción</td>
        </tr>
        <tr>
            <td>date</td>
            <td>datetime</td>
            <td>Fecha de la transacción</td>
        </tr>
      </tbody>
    </table>      
    <h3>Payment</h3>
    <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
              Esta es una clase heredada de Transaction
          </tr>
      </thead>
      <tbody>
        <tr>
            <td>id</td>
            <td>int</td>
            <td>Identificador único de la transacción</td>
        </tr>
        <tr>
            <td>amount</td>
            <td>float</td>
            <td>Monto de la transacción</td>
        </tr>
        <tr>
            <td>payer</td>
            <td>User</td>
            <td>Usuario que realiza la transacción</td>
        </tr>
        <tr>
            <td>group</td>
            <td>str</td>
            <td>Grupo al que pertenece la transacción</td>
        </tr>
        <tr>
            <td>type</td>
            <td>enum</td>
            <td>Tipo de transacción (Expense o Payment)</td>
        </tr>
        <tr>
            <td>money</td>
            <td>Type money</td>
            <td>Moneda de la transacción</td>
        </tr>
        <tr>
            <td>date</td>
            <td>datetime</td>
            <td>Fecha de la transacción</td>
        </tr>
      </tbody>
    </table>
    <h3>Expense</h3>
    <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
              Esta es una clase heredada de Transaction
          </tr>
      </thead>
      <tbody>
        <tr>
            <td>id</td>
            <td>int</td>
            <td>Identificador único de la transacción</td>
        </tr>
        <tr>
            <td>amount</td>
            <td>float</td>
            <td>Monto de la transacción</td>
        </tr>
        <tr>
            <td>payer</td>
            <td>User</td>
            <td>Usuario que realiza la transacción</td>
        </tr>
        <tr>
            <td>group</td>
            <td>str</td>
            <td>Grupo al que pertenece la transacción</td>
        </tr>
        <tr>
            <td>type</td>
            <td>enum</td>
            <td>Tipo de transacción (Expense o Payment)</td>
        </tr>
        <tr>
            <td>money</td>
            <td>Type money</td>
            <td>Moneda de la transacción</td>
        </tr>
        <tr>
            <td>date</td>
            <td>datetime</td>
            <td>Fecha de la transacción</td>
        </tr>
      </tbody>
    </table>
    <h3>Money</h3>
    <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
          </tr>
      </thead>
      <tbody>
        <tr>
            <td>type</td>
            <td>str</td>
            <td>Nombre de la moneda</td>
        </tr>
        <tr>
            <td>money_codes</td>
            <td>enum</td>
            <td>Código de la moneda</td>
        </tr>
      </tbody>
    </table>
    <h3>Receipt</h3>
    <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
          </tr>
      </thead>
      <tbody>
        <tr>
            <td>typeDocument</td>
            <td>str</td>
            <td>Tipo de documento</td>
        </tr>
        <tr>
            <td>fact_date</td>
            <td>Date</td>
            <td>Fecha de la factura</td>
        </tr>
        <tr>
            <td>expiration_date</td>
            <td>Date</td>
            <td>Fecha de vencimiento</td>
        </tr>
        <tr>
            <td>total</td>
            <td>float</td>
            <td>Total de la factura</td>
        </tr>
        <tr>
            <td>tax</td>
            <td>float</td>
            <td>Impuesto de la factura</td>
        </tr>
      </tbody>
  </table>
  <h3>ReceiptChecker</h3>
  <table>
      <thead>
          <tr>
              <th>Attribute</th>
              <th>Type</th>
              <th>Description</th>
          </tr>
      </thead>
      <tbody>
        <tr>
            <td>Receipts</td>
            <td>list</td>
            <td>Lista de facturas</td>
        </tr>
        <tr>
            <td>Transactions</td>
            <td>list</td>
            <td>Lista de transacciones</td>
        </tr>
      </tbody> 
    </table> 
  </div>

## 4.8. Database Design.

### 4.8.1. Database Diagram

[Modelo en Vertabelo](https://my.vertabelo.com/doc/YrYUSjkG3P9nyXFwHtsHMCz09bs5xKvS)

  <div align="center">
        <img src="images/PocketPartners-data-base-diagram.png" alt="Database Diagram" width="100%">
  </div>

# Capítulo V Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration

**Requirements Management**
1. Trello: Es una herramienta utilizada para gestionar el flujo de trabajo de proyectos principalmente basados en marcos detrabajos ágiles. Será empleado para visualizar y actualizar el estado actual de las tareas e historias de usuariopertenecientes al sprint a desarrollar. Ruta de referencia https://trello.com/es

**Product UX/UI Design**
1. Figma: Plataforma de elaboración de prototipos y edición gráfica, principalmente utilizado para el diseño digital. En elcaso del proyecto, será utilizado para el prototipado de la aplicación y sus versiones de Desktop y Mobile Web Browser.Ruta de referencia https://www.figma.com/login2.
2. Lucidchart: Aplicación para diagramar flujos. Será empleado para el diseño de wireflows, user-flows y el diagrama declases asociado a la aplicación. Ruta de referencia https://www.lucidchart.com/

**Software Testing**
1. Gherkin: Es un sistema de etiquetado utilizado para describir los criterios de aceptación de estructura de una user story.Ruta de referencia https://cucumber.io/docs/gherkin/
   
**Software Development**
1. WebStorm: Entorno de desarrollo integrado elegido para la elaboración y compilación del código por motivos dedominio por parte de los integrantes del equipo de trabajo. Utilizar este IDE supone de valor para el desarrollo del proyecto puesto que incluye la posibilidad de agregar extensiones de utilidad, soporte de edición de texto en múltipleslenguajes de programación, disponibilidade en múltiples sistemas operativos, entre otros beneficios. Ruta de referencia https://www.jetbrains.com/webstorm/
2. HTML5: HyperText Markup Language, o por sus siglas HTML, es un lenguaje de etiquetado para páginas web. Seráempleado en el desarrollo del proyecto para la presentación del contenido en la aplicación. Ruta de referenciahttps://www.w3schools.com/html/html5_syntax.asp
3. CSS: Cascading Style Sheets es un lenguaje que maneja el diseño y presentación de las páginas web, el cual va de la manocon HTML. Ruta de referencia https://google.github.io/styleguide/htmlcssguide.html
4. JavaScript: Es un lenguaje de programación interpretado y orientado a objetos. Se utilizará para elaborar la interfaz deusuario dentro de la aplicación. Ruta de referencia https://developer.mozilla.org/es/docs/Web/JavaScript
5. Angular: Angular es un framework de desarrollo de aplicaciones web de código abierto y basado en TypeScript, mantenido por Google y una comunidad de desarrolladores. Es utilizado para crear aplicaciones web de una sola página (SPA) y aplicaciones web dinámicas. Angular proporciona un conjunto de herramientas y bibliotecas que simplifican el desarrollo de aplicaciones web complejas al seguir el patrón de arquitectura Modelo-Vista-Controlador (MVC) y ofrecer funcionalidades como enlace de datos bidireccional, inyección de dependencias, rutas, formularios reactivos, animaciones y mucho más https://angular.io/

**Software Deployment**
1. Git: Herramienta de control de versiones que permite registrar y gestionar las diferentes versiones del programa. Seutilizará para mantener un historial de cambios y simplificar la corrección de errores. Los miembros del equipo accederána través de la línea de comandos en sus sistemas locales. Ruta de referencia https://git-scm.com/
   
**Software Documentation and Project Management**
1. Github: Plataforma basada en la nube que alojará los repositorios de código del proyecto. Facilitará la colaboración entiempo real y la revisión de contribuciones de cada miembro del equipo. Los miembros del equipo accederán a través desus navegadores web. Ruta de referencia https://github.com/

### 5.1.2. Source Code Management

El presente proyecto seguirá los lineamientos del modelo GitFlow para controlar las versiones, donde utilizaremos GitHub como plataforma y sistema para el control de dichas versiones. 
**Liks del repositorio de GitHub**: 
- Link de la organización: https://github.com/PocketPartners
- Link de la landing page: https://github.com/PocketPartners/LadingPage
- Link del informe: https://github.com/PocketPartners/Informe
- Link del front end: https://github.com/PocketPartners/Frontend
- Link del back end: https://github.com/PocketPartners/Backend

Estrucutra de las ramas:
- **Main Branch:** Esta rama es la principal de la aplicación. Donde se encontrarán las versiones más estables del desarrollo. Solo se admiten cambios que hayan sido probados en otras ramas.
- **Develop Branch:** Esta rama es donde se realizarán los avances del proyecto y desarollo.
- **Feature Branch:** Esta rama es donde se implementarán nuevas características de la aplicación, para luego ser enviada a la rama de desarrollo.
- **Release Branch:** Esta rama es una instancia de la rama Develop, para posteriormente ser enviada a la rama Main.
- **Hotfix Branch:** Estas ramas son creadas con la finalidad de corregir errores puntuales que puedan estar perjudicando al usuario en su experiencia de uso de la aplicación.

### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

<table>
  <caption>Sprint #1</caption>
  <thead>
    <tr>
      <th colspan="2">Sprint Planning Backlog</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Fecha</td>
      <td>09/04/2024</td>
    </tr>
    <tr>
      <td>Hora</td>
      <td>17:00 horas (GMT -5)</td>
    </tr>
    <tr>
      <td>Ubicación</td>
      <td>Modalidad remota a través de plataforma Discord</td>
    </tr>
    <tr>
      <td>Preparado por</td>
      <td>Jarama Peñaloza, Fiorella</td>
    </tr>
    <tr>
      <td>Asistentes (a la reunión de planificación)</td>
      <td>Todos los miembros de FairFinance</td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint n - 1 Review</strong>
      </td>
    </tr>
    <tr>
      <td>Resumen</td>
      <td>
        Se creará la organización de FairFinance en Github y el repositorio de la organización. Además, se implementará el single page landing page.
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint n - 1 Retrospective</strong>
      </td>
    </tr>
    <tr>
      <td>Resumen</td>
      <td>
        La implementación para el landing se ha realizado mediante html y css.
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint Goal and User Stories</strong>
      </td>
    </tr>
    <tr>
      <td>Sprint 1 Velocity</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Sum of Story Points</td>
      <td>8</td>
    </tr>
  </tbody>
</table>

#### 5.2.1.2. Sprint Backlog 1
#### 5.2.1.3. Development Evidence for Sprint Review

<p align="justify">A continuación se presentan capturas del landing page implementado parcialmente en código, con el uso de HTML, CSS</p>



#### 5.2.1.4. Testing Suite Evidence for Sprint Review

<p align="justify">En el transcurso del primer sprint, no se realizaron pruebas en la aplicación ya que nuestro enfoque estuvo dirigido exclusivamente a la construcción de la página de inicio.</p>

#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
<p align="justify">En este sprint en particular, no hemos utilizado servicios web, ya que nos hemos concentrado exclusivamente en la creación de la página de inicio estática. Por lo tanto, en esta presentación no se proporciona documentación relacionada con la utilización de servicios web.
</p>


#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

## Avance de Conclusiones, Bibliografía y Anexos
### Conclusiones
### Bibliografía
### Anexos
