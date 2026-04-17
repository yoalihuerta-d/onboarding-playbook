# 🔍 Prework

*⏱ ~5-10 min*



## Objetivo

Conocer al doctor antes de la sesión para poder ofrecer una asesoría personalizada.

La meta es que el doctor sienta que Doctoralia se adapta a su práctica, no al revés.



## 🧰 Tus dos herramientas

| **Herramienta**            | **¿Qué te da?**                                      | **¿Dónde vive?** |
|----------------------------|------------------------------------------------------|------------------|
| **LuCS-ia**               | Datos operativos (qué le falta al doc, su score, su paquete) | Slack            |
| **Gemini** | Datos estratégicos (mercado local, precios, rapport) | [Gem de Gemini](https://gemini.google.com/gem/16XEmRKNs_MsCifRBUWdL5xGpdomBhYXA?usp=sharing)    |



## Fase 1: Prework Operativo (LuCS-ia)

**Meta:** Saber en qué estado real está la cuenta del doctor.

1. **Abre Salesforce** → busca el caso de onboarding  
2. **Copia el Case ID**  
3. **Ve a Slack** → pégalo en el chat de LuCS-ia  
4. **Escanea el mensaje** priorizando estas 5 cosas:

| # | **Qué buscar** | Para qué te sirve |
|---|---------------|-------------------|
| 1 | **Score de Onboarding** | Saber qué tan configurado está su cuenta y cuánto le falta |
| 2 | **Semáforos rojos** | Saber qué features no ha activado/configurado |
| 3 | **Paquete y permanencia** | Saber su plan (Starter, Plus o VIP), si paga mensual/anual, si tiene productos extras |
| 4 | **Objetivo del doctor** | Si contestó el Wizard → úsalo como eje. <br> Si no contestó el Wizard → prepara una hipótesis para validar al inicio con sondeo <br><br> *Respuestas posibles del Wizard:* <br> *Quiere visibilidad:* <br> *- Para conseguir pacientes* <br> *- Para mejorar mi reputación online* <br> *Quiere eficiencia:* <br> *- Para gestionar la comunicación con mis pacientes* <br> *- Para mejorar la eficacia de mi consulta* |
| 5 | **Resultados generados** | ¿Ya tiene reservas? ¿Opiniones? ¿O arranca de cero? |



**✅ Al terminar debes poder decir:**

> "El doctor está en Score [X] , le falta configurar [X], [sí/no] ha generado resultados y su objetivo es [X]."



## Fase 2: Prework Estratégico (Gemini)

**Meta:** Tener argumentos comerciales + temas para romper el hielo.

1. **Abre la Gema de Prework**  
2. **Pega la URL** del perfil del doctor en Doctoralia  
3. **Tip:** Dale clic a "Crear infografía" para verlo más visual  
4. **Escanea en dos bloques:**



### 📊 Datos de Estrategia

| **Dato**                      | **¿Qué haces con él?** |
|-------------------------------|------------------------|
| **TTFV (Time to First Value)** | Fija expectativas reales → *"En tu especialidad, los primeros resultados llegan en ~X días"* |
| **Precios vs. zona**          | ¿Está caro o barato vs. la media local? → argumento de competitividad |
| **Nivel de digitalización**   | ¿Tiene facilidad con herramientas digitales o prefiere una explicación más detallada? |



### 🤝 Datos de Rapport (conexión personal)

| **Dato**              | **¿Qué haces con él?** |
|-----------------------|------------------------|
| **Huella digital**    | ¿Tiene redes sociales, marca personal? Menciónalo → genera confianza |
| **Efemérides médicas** | ¿Se acerca alguna fecha relevante de su especialidad?  → úsalo como rompehielos. |



**✅ Al terminar debes poder decir:**

>  “Puedo mencionar el Día de [efeméride], su presencia en [red social] o sus apariciones en medios (TV, radio, podcasts o prensa). También comentarle si su precio está por encima o por debajo del promedio de su zona y explicarle que los primeros resultados suelen llegar en aproximadamente [X] días.”



:::{iframe} https://www.youtube.com/embed/tr1W5dyKIp0
:::