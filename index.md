# Privacy Policy – Calculator Leankar

**Last Updated:** Aug 8, 2026.

---

## Introduction

This Privacy Policy explains how the **Calculator Leankar** mobile application ("we", "our", or "the app") handles information when you use the application. User privacy and transparency are core principles of Calculator Leankar.

By using the application, you agree to this Privacy Policy. If you do not agree with any part of this policy, please discontinue use of the app.

---

## Information We Collect

### Personal Data

**Calculator Leankar does not directly collect, request, or store any personally identifiable information.**

The application does **not** collect:

* Name
* Email address
* Phone number
* Physical or precise location
* Contact information
* Any personal identification data

### Local App Data

The application stores **only limited data locally on your device** using SharedPreferences:

* **Calculation History:** Mathematical operations performed by the user.
* **Theme Preference:** Light, dark, or system-default theme selection.
* **Language Preference:** Selected display language (Portuguese, English, Spanish, Italian, or French).
* **Ad Consent Status:** Whether you have granted or denied consent for ads, as required by GDPR and LGPD.
* **Last Installed App Version:** The build number of the app, used internally to detect a fresh install or update (for example, to apply the default theme after an update). This value never leaves your device.

This locally stored data:

* Remains exclusively on the user's device
* Is not transmitted to our servers
* Is not shared with third parties by us
* Is fully controlled by the user

### BMI Calculator Input (Health-Related Data)

The app's BMI (Body Mass Index) calculator asks you to enter your **weight** and **height** to compute a result.

* This data is processed **only in memory**, exclusively on your device, for the sole purpose of performing the calculation.
* It is **not saved** to local storage, **not included** in the calculation history, **not transmitted** to us, and **not shared** with any third party, including advertising services.
* The values are cleared as soon as you leave the BMI screen or reset the fields.

### Data Collected by Third-Party Services

Calculator Leankar uses **Unity LevelPlay** (a mediation platform by Unity Technologies, formerly ironSource) to display banner advertisements. **This applies to the Android version of the app only** — the iOS build does not integrate any advertising SDK and does not display ads.

When ads are displayed on Android, Unity LevelPlay and its ad network (Unity Ads) may collect:

* Advertising identifiers (Android Advertising ID)
* IP address
* Device type and operating system version
* General location information (country or region level, derived from IP)
* Ad interaction data (impressions, clicks)
* Diagnostic and performance data

This data is collected and processed by Unity Technologies in accordance with [Unity's Privacy Policy](https://unity.com/legal/game-player-privacy-policy). Calculator Leankar has no access to or control over the data Unity collects.

---

## Ad Consent

To comply with GDPR and LGPD, Calculator Leankar presents an **in-app consent dialog** before enabling advertising, instead of relying on any third-party consent platform.

* On first launch, a dialog asks whether you accept or decline ads.
* If you **accept**, the Unity LevelPlay SDK is initialized and banner ads may be displayed. Your choice is also forwarded to Unity LevelPlay as a GDPR consent signal for the Unity Ads network.
* If you **decline**, the advertising SDK is **not initialized** and **no ads are shown** at all — there is no fallback to non-personalized ads.
* Your consent choice is stored locally on your device (as a simple accepted/declined flag) and applied again automatically on every app start. It can be changed by clearing the app's local data, which triggers the consent dialog again on the next launch.
* This entire flow applies only to the Android version of the app, the only platform where ads currently exist.

---

## How We Use Information

Locally stored data is used solely to:

* Display calculation history within the app
* Persist your theme and language preferences across sessions
* Track your ad consent status to comply with applicable privacy regulations
* Compute your BMI result on demand, without retaining the input values

No data collected by Calculator Leankar is used for analytics, tracking, profiling, or advertising purposes on our end. The app does not integrate any analytics or crash-reporting SDK.

---

## Data Sharing

**Calculator Leankar does not directly share your data with third parties.**

However, on Android, when ads are enabled by your consent, **Unity LevelPlay** receives data as described in the "Data Collected by Third-Party Services" section above.

We do not:

* Sell or rent user data
* Share personal data with partners or advertisers directly
* Transmit app data to our own external servers
* Process user data on remote infrastructure controlled by us

---

## Data Storage and Security

### Storage

All app data is stored locally on the user's device. Calculator Leankar does not use cloud storage, remote databases, or servers of its own.

### Security Measures

We apply appropriate technical measures including:

* Secure coding practices
* Input validation
* Error handling to preserve data integrity

### Data Deletion

Users may delete locally stored data at any time by:

* Using the **Clear History** feature within the app
* Clearing app data via device system settings
* Uninstalling the application, which removes all local data automatically

Note: Ad-related data collected by Unity LevelPlay is subject to Unity's own data retention and deletion policies, and only applies to the Android version of the app.

---

## App Permissions

Calculator Leankar requests only the permissions required for its functionality. The permissions below apply to the **Android** build; the iOS build requests none of them, since it has no advertising integration.

| Permission | Purpose |
|---|---|
| `INTERNET` | Required by Unity LevelPlay to load and display banner advertisements |
| `com.google.android.gms.permission.AD_ID` | Allows access to the Android Advertising ID, used by Unity LevelPlay for ad delivery and measurement |

The application does **not** request access to:

* Camera
* Microphone
* Location services
* Contacts
* External storage
* Photos, media, or files

---

## Third-Party Services

Calculator Leankar integrates the following third-party service:

### Unity LevelPlay (Unity Technologies)

* **Purpose:** Display banner advertisements within the Android version of the app
* **Provider:** Unity Technologies (formerly ironSource)
* **Data collected:** As described in "Data Collected by Third-Party Services" above
* **Privacy Policy:** [https://unity.com/legal/game-player-privacy-policy](https://unity.com/legal/game-player-privacy-policy)
* **Opt-out:** You can decline ads in the in-app consent dialog (no ads or ad-related data collection will occur), and you can reset or limit your Android Advertising ID in your device settings (Google Settings → Ads)

No other third-party analytics, crash reporting, social media, or authentication services are used.

---

## Children's Privacy

Calculator Leankar is a general-audience application. As we do not directly collect personal data from any user, the app does not knowingly collect information from children under 13 (or the applicable age in your jurisdiction).

Ad content served through Unity LevelPlay on Android is subject to Unity's family and content policies. If you are a parent or guardian and have concerns about ad content, you can decline ads entirely in the in-app consent dialog, which stops all ad-related data collection.

---

## Legal Compliance

Calculator Leankar is designed to comply with the principles of:

* **GDPR** (General Data Protection Regulation – European Union)
* **LGPD** (Lei Geral de Proteção de Dados – Brazil)

Including:

* Privacy by default and by design
* Data minimization
* Transparency and user control
* Lawful basis for data processing (explicit in-app consent before enabling ads)

---

## Changes to This Privacy Policy

This Privacy Policy may be updated to reflect changes in the app's features or applicable legal requirements. Any changes will be posted on this page with an updated revision date.

We recommend reviewing this policy periodically.

---

## User Rights

Under GDPR and LGPD, you have the right to:

* **Access** the locally stored data within the app
* **Delete** locally stored data at any time (see "Data Deletion" above)
* **Withdraw consent** for ads at any time by clearing the app's local data, which re-triggers the consent dialog
* **Stop using** the application freely

For data collected by Unity LevelPlay, exercise your rights directly through Unity's tools referenced in their [Privacy Policy](https://unity.com/legal/game-player-privacy-policy).

---

## International Data Transfers

Calculator Leankar itself does not transfer data internationally. However, on Android, Unity LevelPlay may transfer data to servers in the United States and other countries. Such transfers are governed by Unity Technologies' data transfer mechanisms in compliance with GDPR and applicable laws.

---

## Cookies and Tracking Technologies

Calculator Leankar does **not** use cookies or tracking pixels directly. On Android, Unity LevelPlay may use the Android Advertising ID and similar technologies to serve and measure ads, but only if you have accepted ads in the in-app consent dialog. The iOS version does not use any advertising identifier or tracking technology.

---

## Contact Information

If you have questions about this Privacy Policy or our privacy practices, please contact:

**Developer:** Leankar.dev
**Email:** [leankar.dev@gmail.com](mailto:leankar.dev@gmail.com)
**GitHub:** [https://github.com/Leankar-dev/calculator_leankar](https://github.com/Leankar-dev/calculator_leankar)

---

## Google Play Compliance

This Privacy Policy is designed to comply with Google Play Store requirements, including:

* Accurate Data Safety section disclosures
* Clear and transparent disclosure of third-party SDKs (Unity LevelPlay)
* Explicit declaration of ad consent practices
* Accurate description of permissions requested

---

**Effective Date:** Aug 8, 2026
**Applicable to:** Calculator Leankar v0.10.2+

---

---

# Política de Privacidade – Calculator Leankar

**Última Atualização:** 8 de agosto de 2026

---

## Introdução

Esta Política de Privacidade explica como o aplicativo móvel **Calculator Leankar** ("nós", "nosso" ou "o app") trata as informações quando você utiliza a aplicação. A privacidade do usuário e a transparência são princípios fundamentais do Calculator Leankar.

Ao utilizar o aplicativo, você concorda com esta Política de Privacidade. Caso não concorde com alguma parte desta política, por favor, encerre o uso do app.

---

## Informações que Coletamos

### Dados Pessoais

**O Calculator Leankar não coleta, solicita nem armazena diretamente nenhuma informação pessoalmente identificável.**

O aplicativo **não** coleta:

* Nome
* Endereço de e-mail
* Número de telefone
* Localização física ou precisa
* Informações de contato
* Quaisquer dados de identificação pessoal

### Dados Locais do App

O aplicativo armazena **apenas dados limitados localmente no seu dispositivo** usando SharedPreferences:

* **Histórico de Cálculos:** Operações matemáticas realizadas pelo usuário.
* **Preferência de Tema:** Seleção de tema claro, escuro ou padrão do sistema.
* **Preferência de Idioma:** Idioma de exibição selecionado (Português, Inglês, Espanhol, Italiano ou Francês).
* **Status de Consentimento de Anúncios:** Se você concedeu ou recusou o consentimento para anúncios, conforme exigido pela LGPD e GDPR.
* **Última Versão Instalada do App:** O número de build do app, usado internamente para detectar uma instalação nova ou uma atualização (por exemplo, para aplicar o tema padrão após uma atualização). Esse valor nunca sai do seu dispositivo.

Esses dados armazenados localmente:

* Permanecem exclusivamente no dispositivo do usuário
* Não são transmitidos para nossos servidores
* Não são compartilhados com terceiros por nós
* Estão totalmente sob controle do usuário

### Dados de Entrada da Calculadora de IMC (Dados Relacionados à Saúde)

A calculadora de IMC (Índice de Massa Corporal) do app solicita que você informe seu **peso** e sua **altura** para calcular um resultado.

* Esses dados são processados **apenas em memória**, exclusivamente no seu dispositivo, com a única finalidade de realizar o cálculo.
* Eles **não são salvos** em armazenamento local, **não são incluídos** no histórico de cálculos, **não são transmitidos** a nós e **não são compartilhados** com nenhum terceiro, incluindo serviços de publicidade.
* Os valores são descartados assim que você sai da tela de IMC ou limpa os campos.

### Dados Coletados por Serviços de Terceiros

O Calculator Leankar utiliza o **Unity LevelPlay** (uma plataforma de mediação de anúncios da Unity Technologies, anteriormente ironSource) para exibir anúncios em banner. **Isso se aplica apenas à versão Android do app** — a versão iOS não integra nenhum SDK de publicidade e não exibe anúncios.

Quando anúncios são exibidos no Android, o Unity LevelPlay e sua rede de anúncios (Unity Ads) podem coletar:

* Identificadores de publicidade (Android Advertising ID)
* Endereço IP
* Tipo de dispositivo e versão do sistema operacional
* Informações gerais de localização (nível de país ou região, derivadas do IP)
* Dados de interação com anúncios (impressões, cliques)
* Dados de diagnóstico e desempenho

Esses dados são coletados e processados pela Unity Technologies de acordo com a [Política de Privacidade da Unity](https://unity.com/legal/game-player-privacy-policy). O Calculator Leankar não tem acesso nem controle sobre os dados coletados pela Unity.

---

## Consentimento para Anúncios

Para cumprir a LGPD e o GDPR, o Calculator Leankar apresenta um **diálogo de consentimento dentro do próprio app** antes de habilitar a publicidade, em vez de depender de qualquer plataforma de consentimento de terceiros.

* Na primeira execução, um diálogo pergunta se você aceita ou recusa anúncios.
* Se você **aceitar**, o SDK do Unity LevelPlay é inicializado e anúncios em banner podem ser exibidos. Sua escolha também é enviada ao Unity LevelPlay como um sinal de consentimento GDPR para a rede Unity Ads.
* Se você **recusar**, o SDK de publicidade **não é inicializado** e **nenhum anúncio é exibido** — não há anúncios não personalizados como alternativa.
* Sua escolha de consentimento é armazenada localmente no seu dispositivo (como uma simples marcação de aceito/recusado) e reaplicada automaticamente a cada abertura do app. Ela pode ser alterada limpando os dados locais do app, o que faz o diálogo de consentimento ser exibido novamente na próxima abertura.
* Todo esse fluxo se aplica apenas à versão Android do app, única plataforma onde há anúncios atualmente.

---

## Como Usamos as Informações

Os dados armazenados localmente são usados exclusivamente para:

* Exibir o histórico de cálculos dentro do app
* Manter suas preferências de tema e idioma entre as sessões
* Registrar seu status de consentimento de anúncios para cumprir com as regulamentações de privacidade aplicáveis
* Calcular seu resultado de IMC sob demanda, sem reter os valores informados

Nenhum dado coletado pelo Calculator Leankar é usado por nós para fins de análise, rastreamento, criação de perfis ou publicidade. O app não integra nenhum SDK de análise (analytics) ou relatório de falhas.

---

## Compartilhamento de Dados

**O Calculator Leankar não compartilha diretamente seus dados com terceiros.**

No entanto, no Android, quando os anúncios são habilitados pelo seu consentimento, o **Unity LevelPlay** recebe dados conforme descrito na seção "Dados Coletados por Serviços de Terceiros".

Nós não:

* Vendemos ou alugamos dados de usuários
* Compartilhamos dados pessoais diretamente com parceiros ou anunciantes
* Transmitimos dados do app para nossos próprios servidores externos
* Processamos dados de usuários em infraestrutura remota controlada por nós

---

## Armazenamento e Segurança dos Dados

### Armazenamento

Todos os dados do app são armazenados localmente no dispositivo do usuário. O Calculator Leankar não utiliza armazenamento em nuvem, bancos de dados remotos ou servidores próprios.

### Medidas de Segurança

Aplicamos medidas técnicas adequadas, incluindo:

* Práticas de codificação segura
* Validação de entrada
* Tratamento de erros para preservar a integridade dos dados

### Exclusão de Dados

Os usuários podem excluir os dados armazenados localmente a qualquer momento:

* Usando o recurso **Limpar Histórico** dentro do app
* Limpando os dados do app nas configurações do sistema do dispositivo
* Desinstalando o aplicativo, o que remove automaticamente todos os dados locais

Observação: os dados relacionados a anúncios coletados pelo Unity LevelPlay estão sujeitos às próprias políticas de retenção e exclusão da Unity, e se aplicam somente à versão Android do app.

---

## Permissões do App

O Calculator Leankar solicita apenas as permissões necessárias para seu funcionamento. As permissões abaixo se aplicam à versão **Android**; a versão iOS não solicita nenhuma delas, pois não possui integração de publicidade.

| Permissão | Finalidade |
|---|---|
| `INTERNET` | Necessária pelo Unity LevelPlay para carregar e exibir anúncios em banner |
| `com.google.android.gms.permission.AD_ID` | Permite acesso ao Android Advertising ID, usado pelo Unity LevelPlay para entrega e mensuração de anúncios |

O aplicativo **não** solicita acesso a:

* Câmera
* Microfone
* Serviços de localização
* Contatos
* Armazenamento externo
* Fotos, mídia ou arquivos

---

## Serviços de Terceiros

O Calculator Leankar integra o seguinte serviço de terceiros:

### Unity LevelPlay (Unity Technologies)

* **Finalidade:** Exibir anúncios em banner dentro da versão Android do app
* **Fornecedor:** Unity Technologies (anteriormente ironSource)
* **Dados coletados:** Conforme descrito em "Dados Coletados por Serviços de Terceiros"
* **Política de Privacidade:** [https://unity.com/legal/game-player-privacy-policy](https://unity.com/legal/game-player-privacy-policy)
* **Como cancelar:** Você pode recusar anúncios no diálogo de consentimento dentro do app (nenhum anúncio ou coleta de dados relacionada ocorrerá), e pode redefinir ou limitar seu Android Advertising ID nas configurações do dispositivo (Configurações do Google → Anúncios)

Nenhum outro serviço de análise, relatório de erros, redes sociais ou autenticação de terceiros é utilizado.

---

## Privacidade de Crianças

O Calculator Leankar é um aplicativo para público geral. Como não coletamos diretamente dados pessoais de nenhum usuário, o app não coleta intencionalmente informações de crianças menores de 13 anos (ou a idade aplicável em sua jurisdição).

O conteúdo dos anúncios veiculados pelo Unity LevelPlay no Android está sujeito às políticas de família e conteúdo da Unity. Se você é pai, mãe ou responsável e tem preocupações com o conteúdo dos anúncios, pode recusar os anúncios completamente no diálogo de consentimento do app, o que interrompe toda coleta de dados relacionada a anúncios.

---

## Conformidade Legal

O Calculator Leankar foi desenvolvido para cumprir os princípios da:

* **LGPD** (Lei Geral de Proteção de Dados – Brasil)
* **GDPR** (Regulamento Geral sobre a Proteção de Dados – União Europeia)

Incluindo:

* Privacidade por padrão e por design
* Minimização de dados
* Transparência e controle do usuário
* Base legal para o tratamento de dados (consentimento explícito dentro do app antes de habilitar anúncios)

---

## Alterações nesta Política de Privacidade

Esta Política de Privacidade pode ser atualizada para refletir mudanças nas funcionalidades do app ou nos requisitos legais aplicáveis. Quaisquer alterações serão publicadas nesta página com a data de revisão atualizada.

Recomendamos revisar esta política periodicamente.

---

## Direitos do Usuário

Sob a LGPD e o GDPR, você tem o direito de:

* **Acessar** os dados armazenados localmente no app
* **Excluir** os dados armazenados localmente a qualquer momento (veja "Exclusão de Dados")
* **Revogar o consentimento** para anúncios a qualquer momento, limpando os dados locais do app, o que reexibe o diálogo de consentimento
* **Parar de usar** o aplicativo livremente

Para dados coletados pelo Unity LevelPlay, exerça seus direitos diretamente pelos canais indicados na [Política de Privacidade da Unity](https://unity.com/legal/game-player-privacy-policy).

---

## Transferências Internacionais de Dados

O Calculator Leankar em si não realiza transferências internacionais de dados. No entanto, no Android, o Unity LevelPlay pode transferir dados para servidores nos Estados Unidos e em outros países. Tais transferências são regidas pelos mecanismos de transferência de dados da Unity Technologies, em conformidade com o GDPR e as leis aplicáveis.

---

## Cookies e Tecnologias de Rastreamento

O Calculator Leankar **não** utiliza cookies ou pixels de rastreamento diretamente. No Android, o Unity LevelPlay pode usar o Android Advertising ID e tecnologias similares para veicular e mensurar anúncios, mas somente se você tiver aceitado anúncios no diálogo de consentimento do app. A versão iOS não utiliza nenhum identificador de publicidade ou tecnologia de rastreamento.

---

## Informações de Contato

Se você tiver dúvidas sobre esta Política de Privacidade ou nossas práticas de privacidade, entre em contato:

**Desenvolvedor:** Leankar.dev
**E-mail:** [leankar.dev@gmail.com](mailto:leankar.dev@gmail.com)
**GitHub:** [https://github.com/Leankar-dev/calculator_leankar](https://github.com/Leankar-dev/calculator_leankar)

---

## Conformidade com o Google Play

Esta Política de Privacidade foi elaborada para cumprir os requisitos da Google Play Store, incluindo:

* Divulgações precisas na seção Data Safety
* Divulgação clara e transparente de SDKs de terceiros (Unity LevelPlay)
* Declaração explícita das práticas de consentimento para anúncios
* Descrição precisa das permissões solicitadas

---

**Data de Vigência:** 8 de agosto de 2026
**Aplicável a:** Calculator Leankar v0.10.2+

---

---

# Política de Privacidad – Calculator Leankar

**Última Actualización:** 8 de agosto de 2026

---

## Introducción

Esta Política de Privacidad explica cómo la aplicación móvil **Calculator Leankar** ("nosotros", "nuestro" o "la app") trata la información cuando usted utiliza la aplicación. La privacidad del usuario y la transparencia son principios fundamentales de Calculator Leankar.

Al utilizar la aplicación, usted acepta esta Política de Privacidad. Si no está de acuerdo con alguna parte de esta política, por favor deje de usar la app.

---

## Información que Recopilamos

### Datos Personales

**Calculator Leankar no recopila, solicita ni almacena directamente ninguna información de identificación personal.**

La aplicación **no** recopila:

* Nombre
* Dirección de correo electrónico
* Número de teléfono
* Ubicación física o precisa
* Información de contacto
* Cualquier dato de identificación personal

### Datos Locales de la App

La aplicación almacena **solo datos limitados de forma local en su dispositivo** mediante SharedPreferences:

* **Historial de Cálculos:** Operaciones matemáticas realizadas por el usuario.
* **Preferencia de Tema:** Selección de tema claro, oscuro o predeterminado del sistema.
* **Preferencia de Idioma:** Idioma de visualización seleccionado (portugués, inglés, español, italiano o francés).
* **Estado de Consentimiento de Anuncios:** Si usted ha otorgado o denegado el consentimiento para anuncios, según lo exigido por el GDPR y la LGPD.
* **Última Versión Instalada de la App:** El número de compilación (build) de la app, usado internamente para detectar una instalación nueva o una actualización (por ejemplo, para aplicar el tema predeterminado tras una actualización). Este valor nunca sale de su dispositivo.

Estos datos almacenados localmente:

* Permanecen exclusivamente en el dispositivo del usuario
* No se transmiten a nuestros servidores
* No los compartimos con terceros
* Están totalmente bajo el control del usuario

### Datos de Entrada de la Calculadora de IMC (Datos Relacionados con la Salud)

La calculadora de IMC (Índice de Masa Corporal) de la app le solicita ingresar su **peso** y **altura** para calcular un resultado.

* Estos datos se procesan **únicamente en memoria**, de forma exclusiva en su dispositivo, con el único fin de realizar el cálculo.
* **No se guardan** en el almacenamiento local, **no se incluyen** en el historial de cálculos, **no se transmiten** a nosotros y **no se comparten** con ningún tercero, incluidos los servicios de publicidad.
* Los valores se descartan tan pronto como usted sale de la pantalla de IMC o restablece los campos.

### Datos Recopilados por Servicios de Terceros

Calculator Leankar utiliza **Unity LevelPlay** (una plataforma de mediación de anuncios de Unity Technologies, anteriormente ironSource) para mostrar anuncios en banner. **Esto se aplica únicamente a la versión Android de la app** — la versión iOS no integra ningún SDK de publicidad ni muestra anuncios.

Cuando se muestran anuncios en Android, Unity LevelPlay y su red de anuncios (Unity Ads) pueden recopilar:

* Identificadores de publicidad (Android Advertising ID)
* Dirección IP
* Tipo de dispositivo y versión del sistema operativo
* Información general de ubicación (a nivel de país o región, derivada de la IP)
* Datos de interacción con anuncios (impresiones, clics)
* Datos de diagnóstico y rendimiento

Estos datos son recopilados y procesados por Unity Technologies de acuerdo con la [Política de Privacidad de Unity](https://unity.com/legal/game-player-privacy-policy). Calculator Leankar no tiene acceso ni control sobre los datos que recopila Unity.

---

## Consentimiento para Anuncios

Para cumplir con el GDPR y la LGPD, Calculator Leankar presenta un **diálogo de consentimiento dentro de la propia app** antes de habilitar la publicidad, en lugar de depender de cualquier plataforma de consentimiento de terceros.

* En el primer inicio, un diálogo pregunta si usted acepta o rechaza los anuncios.
* Si **acepta**, se inicializa el SDK de Unity LevelPlay y pueden mostrarse anuncios en banner. Su elección también se envía a Unity LevelPlay como señal de consentimiento GDPR para la red Unity Ads.
* Si **rechaza**, el SDK de publicidad **no se inicializa** y **no se muestra ningún anuncio** — no existe una alternativa de anuncios no personalizados.
* Su elección de consentimiento se almacena localmente en su dispositivo (como una simple marca de aceptado/rechazado) y se vuelve a aplicar automáticamente en cada inicio de la app. Puede cambiarse borrando los datos locales de la app, lo que hace que el diálogo de consentimiento se muestre nuevamente en el próximo inicio.
* Todo este flujo se aplica únicamente a la versión Android de la app, la única plataforma donde existen anuncios actualmente.

---

## Cómo Usamos la Información

Los datos almacenados localmente se usan exclusivamente para:

* Mostrar el historial de cálculos dentro de la app
* Mantener sus preferencias de tema e idioma entre sesiones
* Registrar su estado de consentimiento de anuncios para cumplir con las normativas de privacidad aplicables
* Calcular su resultado de IMC bajo demanda, sin conservar los valores ingresados

Ningún dato recopilado por Calculator Leankar se usa por nuestra parte con fines de análisis, rastreo, perfilado o publicidad. La app no integra ningún SDK de análisis (analytics) ni de reporte de fallos.

---

## Compartición de Datos

**Calculator Leankar no comparte directamente sus datos con terceros.**

Sin embargo, en Android, cuando los anuncios están habilitados por su consentimiento, **Unity LevelPlay** recibe datos según lo descrito en la sección "Datos Recopilados por Servicios de Terceros".

Nosotros no:

* Vendemos ni alquilamos datos de usuarios
* Compartimos datos personales directamente con socios o anunciantes
* Transmitimos datos de la app a nuestros propios servidores externos
* Procesamos datos de usuarios en infraestructura remota controlada por nosotros

---

## Almacenamiento y Seguridad de los Datos

### Almacenamiento

Todos los datos de la app se almacenan localmente en el dispositivo del usuario. Calculator Leankar no utiliza almacenamiento en la nube, bases de datos remotas ni servidores propios.

### Medidas de Seguridad

Aplicamos medidas técnicas adecuadas, entre ellas:

* Prácticas de codificación segura
* Validación de entradas
* Manejo de errores para preservar la integridad de los datos

### Eliminación de Datos

Los usuarios pueden eliminar los datos almacenados localmente en cualquier momento:

* Usando la función **Borrar Historial** dentro de la app
* Borrando los datos de la app en la configuración del sistema del dispositivo
* Desinstalando la aplicación, lo que elimina automáticamente todos los datos locales

Nota: los datos relacionados con anuncios recopilados por Unity LevelPlay están sujetos a las propias políticas de retención y eliminación de Unity, y se aplican solo a la versión Android de la app.

---

## Permisos de la App

Calculator Leankar solicita solo los permisos necesarios para su funcionamiento. Los permisos siguientes se aplican a la versión **Android**; la versión iOS no solicita ninguno de ellos, ya que no cuenta con integración de publicidad.

| Permiso | Finalidad |
|---|---|
| `INTERNET` | Necesario para que Unity LevelPlay cargue y muestre anuncios en banner |
| `com.google.android.gms.permission.AD_ID` | Permite el acceso al Android Advertising ID, usado por Unity LevelPlay para la entrega y medición de anuncios |

La aplicación **no** solicita acceso a:

* Cámara
* Micrófono
* Servicios de ubicación
* Contactos
* Almacenamiento externo
* Fotos, medios o archivos

---

## Servicios de Terceros

Calculator Leankar integra el siguiente servicio de terceros:

### Unity LevelPlay (Unity Technologies)

* **Finalidad:** Mostrar anuncios en banner dentro de la versión Android de la app
* **Proveedor:** Unity Technologies (anteriormente ironSource)
* **Datos recopilados:** Según lo descrito en "Datos Recopilados por Servicios de Terceros"
* **Política de Privacidad:** [https://unity.com/legal/game-player-privacy-policy](https://unity.com/legal/game-player-privacy-policy)
* **Cómo optar por no participar:** Puede rechazar los anuncios en el diálogo de consentimiento dentro de la app (no ocurrirá ninguna recopilación de datos relacionada con anuncios), y puede restablecer o limitar su Android Advertising ID en la configuración de su dispositivo (Configuración de Google → Anuncios)

No se utiliza ningún otro servicio de análisis, reporte de fallos, redes sociales o autenticación de terceros.

---

## Privacidad de los Menores

Calculator Leankar es una aplicación para público general. Como no recopilamos directamente datos personales de ningún usuario, la app no recopila intencionalmente información de menores de 13 años (o la edad aplicable en su jurisdicción).

El contenido de los anuncios servidos a través de Unity LevelPlay en Android está sujeto a las políticas familiares y de contenido de Unity. Si usted es padre, madre o tutor y tiene inquietudes sobre el contenido de los anuncios, puede rechazar los anuncios por completo en el diálogo de consentimiento de la app, lo que detiene toda recopilación de datos relacionada con anuncios.

---

## Cumplimiento Legal

Calculator Leankar está diseñado para cumplir con los principios de:

* **GDPR** (Reglamento General de Protección de Datos – Unión Europea)
* **LGPD** (Lei Geral de Proteção de Dados – Brasil)

Incluyendo:

* Privacidad por defecto y por diseño
* Minimización de datos
* Transparencia y control del usuario
* Base legal para el tratamiento de datos (consentimiento explícito dentro de la app antes de habilitar anuncios)

---

## Cambios en esta Política de Privacidad

Esta Política de Privacidad puede actualizarse para reflejar cambios en las funcionalidades de la app o en los requisitos legales aplicables. Cualquier cambio se publicará en esta página con una fecha de revisión actualizada.

Recomendamos revisar esta política periódicamente.

---

## Derechos del Usuario

Conforme al GDPR y la LGPD, usted tiene derecho a:

* **Acceder** a los datos almacenados localmente en la app
* **Eliminar** los datos almacenados localmente en cualquier momento (vea "Eliminación de Datos")
* **Revocar el consentimiento** de anuncios en cualquier momento, borrando los datos locales de la app, lo que vuelve a mostrar el diálogo de consentimiento
* **Dejar de usar** la aplicación libremente

Para los datos recopilados por Unity LevelPlay, ejerza sus derechos directamente a través de los canales indicados en la [Política de Privacidad de Unity](https://unity.com/legal/game-player-privacy-policy).

---

## Transferencias Internacionales de Datos

Calculator Leankar en sí no realiza transferencias internacionales de datos. Sin embargo, en Android, Unity LevelPlay puede transferir datos a servidores en Estados Unidos y otros países. Dichas transferencias se rigen por los mecanismos de transferencia de datos de Unity Technologies, en cumplimiento del GDPR y las leyes aplicables.

---

## Cookies y Tecnologías de Rastreo

Calculator Leankar **no** utiliza cookies ni píxeles de rastreo directamente. En Android, Unity LevelPlay puede usar el Android Advertising ID y tecnologías similares para entregar y medir anuncios, pero solo si usted ha aceptado los anuncios en el diálogo de consentimiento de la app. La versión iOS no utiliza ningún identificador de publicidad ni tecnología de rastreo.

---

## Información de Contacto

Si tiene preguntas sobre esta Política de Privacidad o nuestras prácticas de privacidad, comuníquese con:

**Desarrollador:** Leankar.dev
**Correo electrónico:** [leankar.dev@gmail.com](mailto:leankar.dev@gmail.com)
**GitHub:** [https://github.com/Leankar-dev/calculator_leankar](https://github.com/Leankar-dev/calculator_leankar)

---

## Cumplimiento con Google Play

Esta Política de Privacidad está diseñada para cumplir con los requisitos de la Google Play Store, incluyendo:

* Divulgaciones precisas en la sección Data Safety
* Divulgación clara y transparente de SDKs de terceros (Unity LevelPlay)
* Declaración explícita de las prácticas de consentimiento de anuncios
* Descripción precisa de los permisos solicitados

---

**Fecha de Vigencia:** 8 de agosto de 2026
**Aplicable a:** Calculator Leankar v0.10.2+

---

---

# Politique de Confidentialité – Calculator Leankar

**Dernière Mise à Jour :** 8 août 2026

---

## Introduction

Cette Politique de Confidentialité explique comment l'application mobile **Calculator Leankar** (« nous », « notre » ou « l'application ») traite les informations lorsque vous utilisez l'application. La confidentialité des utilisateurs et la transparence sont des principes fondamentaux de Calculator Leankar.

En utilisant l'application, vous acceptez cette Politique de Confidentialité. Si vous n'êtes pas d'accord avec une partie de cette politique, veuillez cesser d'utiliser l'application.

---

## Informations que Nous Collectons

### Données Personnelles

**Calculator Leankar ne collecte, ne demande ni ne stocke directement aucune information personnellement identifiable.**

L'application ne collecte **pas** :

* Nom
* Adresse e-mail
* Numéro de téléphone
* Localisation physique ou précise
* Coordonnées de contact
* Toute donnée d'identification personnelle

### Données Locales de l'Application

L'application stocke **uniquement des données limitées localement sur votre appareil** via SharedPreferences :

* **Historique des Calculs :** Opérations mathématiques effectuées par l'utilisateur.
* **Préférence de Thème :** Sélection du thème clair, sombre ou par défaut du système.
* **Préférence de Langue :** Langue d'affichage sélectionnée (portugais, anglais, espagnol, italien ou français).
* **Statut de Consentement Publicitaire :** Si vous avez accordé ou refusé votre consentement pour les publicités, comme l'exigent le RGPD et la LGPD.
* **Dernière Version Installée de l'Application :** Le numéro de build de l'application, utilisé en interne pour détecter une nouvelle installation ou une mise à jour (par exemple, pour appliquer le thème par défaut après une mise à jour). Cette valeur ne quitte jamais votre appareil.

Ces données stockées localement :

* Restent exclusivement sur l'appareil de l'utilisateur
* Ne sont pas transmises à nos serveurs
* Ne sont pas partagées avec des tiers par nos soins
* Sont entièrement sous le contrôle de l'utilisateur

### Données Saisies dans le Calculateur d'IMC (Données Relatives à la Santé)

Le calculateur d'IMC (Indice de Masse Corporelle) de l'application vous demande de saisir votre **poids** et votre **taille** afin de calculer un résultat.

* Ces données sont traitées **uniquement en mémoire**, exclusivement sur votre appareil, dans le seul but d'effectuer le calcul.
* Elles ne sont **pas enregistrées** dans le stockage local, **pas incluses** dans l'historique des calculs, **pas transmises** à nous et **pas partagées** avec un tiers, y compris les services publicitaires.
* Les valeurs sont effacées dès que vous quittez l'écran d'IMC ou réinitialisez les champs.

### Données Collectées par des Services Tiers

Calculator Leankar utilise **Unity LevelPlay** (une plateforme de médiation publicitaire de Unity Technologies, anciennement ironSource) pour afficher des bannières publicitaires. **Cela s'applique uniquement à la version Android de l'application** — la version iOS n'intègre aucun SDK publicitaire et n'affiche aucune publicité.

Lorsque des publicités sont affichées sur Android, Unity LevelPlay et son réseau publicitaire (Unity Ads) peuvent collecter :

* Identifiants publicitaires (Android Advertising ID)
* Adresse IP
* Type d'appareil et version du système d'exploitation
* Informations générales de localisation (au niveau du pays ou de la région, dérivées de l'IP)
* Données d'interaction publicitaire (impressions, clics)
* Données de diagnostic et de performance

Ces données sont collectées et traitées par Unity Technologies conformément à la [Politique de Confidentialité de Unity](https://unity.com/legal/game-player-privacy-policy). Calculator Leankar n'a ni accès ni contrôle sur les données collectées par Unity.

---

## Consentement Publicitaire

Pour se conformer au RGPD et à la LGPD, Calculator Leankar présente une **boîte de dialogue de consentement intégrée à l'application** avant d'activer la publicité, au lieu de s'appuyer sur une plateforme de consentement tierce.

* Au premier lancement, une boîte de dialogue demande si vous acceptez ou refusez les publicités.
* Si vous **acceptez**, le SDK Unity LevelPlay est initialisé et des bannières publicitaires peuvent s'afficher. Votre choix est également transmis à Unity LevelPlay comme signal de consentement RGPD pour le réseau Unity Ads.
* Si vous **refusez**, le SDK publicitaire n'est **pas initialisé** et **aucune publicité n'est affichée** — il n'existe pas d'alternative de publicités non personnalisées.
* Votre choix de consentement est stocké localement sur votre appareil (sous la forme d'un simple indicateur accepté/refusé) et réappliqué automatiquement à chaque démarrage de l'application. Il peut être modifié en effaçant les données locales de l'application, ce qui déclenche à nouveau la boîte de dialogue de consentement au prochain lancement.
* Tout ce processus ne s'applique qu'à la version Android de l'application, seule plateforme sur laquelle des publicités existent actuellement.

---

## Comment Nous Utilisons les Informations

Les données stockées localement sont utilisées exclusivement pour :

* Afficher l'historique des calculs dans l'application
* Conserver vos préférences de thème et de langue d'une session à l'autre
* Enregistrer votre statut de consentement publicitaire afin de respecter les réglementations de confidentialité applicables
* Calculer votre résultat d'IMC à la demande, sans conserver les valeurs saisies

Aucune donnée collectée par Calculator Leankar n'est utilisée par nos soins à des fins d'analyse, de suivi, de profilage ou de publicité. L'application n'intègre aucun SDK d'analyse ni de rapport de plantage.

---

## Partage des Données

**Calculator Leankar ne partage pas directement vos données avec des tiers.**

Cependant, sur Android, lorsque les publicités sont activées par votre consentement, **Unity LevelPlay** reçoit des données comme décrit dans la section « Données Collectées par des Services Tiers » ci-dessus.

Nous ne faisons pas ce qui suit :

* Vendre ou louer les données des utilisateurs
* Partager des données personnelles directement avec des partenaires ou annonceurs
* Transmettre les données de l'application à nos propres serveurs externes
* Traiter les données des utilisateurs sur une infrastructure distante que nous contrôlons

---

## Stockage et Sécurité des Données

### Stockage

Toutes les données de l'application sont stockées localement sur l'appareil de l'utilisateur. Calculator Leankar n'utilise ni stockage en nuage, ni bases de données distantes, ni serveurs propres.

### Mesures de Sécurité

Nous appliquons des mesures techniques appropriées, notamment :

* Pratiques de codage sécurisées
* Validation des entrées
* Gestion des erreurs afin de préserver l'intégrité des données

### Suppression des Données

Les utilisateurs peuvent supprimer les données stockées localement à tout moment :

* En utilisant la fonction **Effacer l'Historique** dans l'application
* En effaçant les données de l'application via les paramètres du système de l'appareil
* En désinstallant l'application, ce qui supprime automatiquement toutes les données locales

Remarque : les données publicitaires collectées par Unity LevelPlay sont soumises aux propres politiques de conservation et de suppression de Unity, et ne s'appliquent qu'à la version Android de l'application.

---

## Autorisations de l'Application

Calculator Leankar ne demande que les autorisations nécessaires à son fonctionnement. Les autorisations ci-dessous s'appliquent à la version **Android** ; la version iOS n'en demande aucune, car elle n'intègre aucune publicité.

| Autorisation | Finalité |
|---|---|
| `INTERNET` | Nécessaire pour que Unity LevelPlay charge et affiche les bannières publicitaires |
| `com.google.android.gms.permission.AD_ID` | Permet l'accès à l'Android Advertising ID, utilisé par Unity LevelPlay pour la diffusion et la mesure des publicités |

L'application ne demande **pas** l'accès à :

* Appareil photo
* Microphone
* Services de localisation
* Contacts
* Stockage externe
* Photos, médias ou fichiers

---

## Services Tiers

Calculator Leankar intègre le service tiers suivant :

### Unity LevelPlay (Unity Technologies)

* **Finalité :** Afficher des bannières publicitaires dans la version Android de l'application
* **Fournisseur :** Unity Technologies (anciennement ironSource)
* **Données collectées :** Comme décrit dans « Données Collectées par des Services Tiers »
* **Politique de Confidentialité :** [https://unity.com/legal/game-player-privacy-policy](https://unity.com/legal/game-player-privacy-policy)
* **Désactivation :** Vous pouvez refuser les publicités dans la boîte de dialogue de consentement de l'application (aucune publicité ni collecte de données associée n'aura alors lieu), et vous pouvez réinitialiser ou limiter votre Android Advertising ID dans les paramètres de votre appareil (Paramètres Google → Publicités)

Aucun autre service tiers d'analyse, de rapport de plantage, de réseau social ou d'authentification n'est utilisé.

---

## Confidentialité des Enfants

Calculator Leankar est une application destinée au grand public. Comme nous ne collectons directement aucune donnée personnelle auprès des utilisateurs, l'application ne collecte pas sciemment d'informations auprès d'enfants de moins de 13 ans (ou l'âge applicable dans votre juridiction).

Le contenu publicitaire diffusé via Unity LevelPlay sur Android est soumis aux politiques familiales et de contenu de Unity. Si vous êtes parent ou tuteur et avez des préoccupations concernant le contenu publicitaire, vous pouvez refuser entièrement les publicités dans la boîte de dialogue de consentement de l'application, ce qui arrête toute collecte de données liée à la publicité.

---

## Conformité Légale

Calculator Leankar est conçu pour respecter les principes du :

* **RGPD** (Règlement Général sur la Protection des Données – Union Européenne)
* **LGPD** (Lei Geral de Proteção de Dados – Brésil)

Notamment :

* La protection de la vie privée dès la conception et par défaut
* La minimisation des données
* La transparence et le contrôle de l'utilisateur
* Une base légale pour le traitement des données (consentement explicite dans l'application avant l'activation des publicités)

---

## Modifications de cette Politique de Confidentialité

Cette Politique de Confidentialité peut être mise à jour pour refléter des changements dans les fonctionnalités de l'application ou dans les exigences légales applicables. Toute modification sera publiée sur cette page avec une date de révision mise à jour.

Nous recommandons de consulter cette politique périodiquement.

---

## Droits de l'Utilisateur

En vertu du RGPD et de la LGPD, vous avez le droit de :

* **Accéder** aux données stockées localement dans l'application
* **Supprimer** les données stockées localement à tout moment (voir « Suppression des Données »)
* **Retirer votre consentement** aux publicités à tout moment en effaçant les données locales de l'application, ce qui réaffiche la boîte de dialogue de consentement
* **Cesser d'utiliser** l'application librement

Pour les données collectées par Unity LevelPlay, exercez vos droits directement via les moyens indiqués dans la [Politique de Confidentialité de Unity](https://unity.com/legal/game-player-privacy-policy).

---

## Transferts Internationaux de Données

Calculator Leankar elle-même n'effectue aucun transfert international de données. Cependant, sur Android, Unity LevelPlay peut transférer des données vers des serveurs situés aux États-Unis et dans d'autres pays. Ces transferts sont régis par les mécanismes de transfert de données de Unity Technologies, conformément au RGPD et aux lois applicables.

---

## Cookies et Technologies de Suivi

Calculator Leankar n'utilise **pas** de cookies ni de pixels de suivi directement. Sur Android, Unity LevelPlay peut utiliser l'Android Advertising ID et des technologies similaires pour diffuser et mesurer les publicités, mais uniquement si vous avez accepté les publicités dans la boîte de dialogue de consentement de l'application. La version iOS n'utilise aucun identifiant publicitaire ni technologie de suivi.

---

## Informations de Contact

Si vous avez des questions concernant cette Politique de Confidentialité ou nos pratiques en matière de confidentialité, veuillez contacter :

**Développeur :** Leankar.dev
**E-mail :** [leankar.dev@gmail.com](mailto:leankar.dev@gmail.com)
**GitHub :** [https://github.com/Leankar-dev/calculator_leankar](https://github.com/Leankar-dev/calculator_leankar)

---

## Conformité avec Google Play

Cette Politique de Confidentialité est conçue pour respecter les exigences de la Google Play Store, notamment :

* Des divulgations précises dans la section Data Safety
* Une divulgation claire et transparente des SDK tiers (Unity LevelPlay)
* Une déclaration explicite des pratiques de consentement publicitaire
* Une description précise des autorisations demandées

---

**Date d'Entrée en Vigueur :** 8 août 2026
**Applicable à :** Calculator Leankar v0.10.2+
