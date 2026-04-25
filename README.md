
# Comenzando con el Desarrollo en Laravel

> **No necesitas experiencia en programación.** Esta guía te lleva paso a paso a configurar tu entorno de desarrollo con la ayuda de un asistente de inteligencia artificial. Al final tendrás dos aplicaciones funcionando al mismo tiempo: la aplicación original (la que está en producción) y una nueva aplicación moderna en Laravel, lista para que empieces a mover funciones de una a la otra.

---

## Lo que necesitas antes de comenzar

- Una computadora con acceso a internet
- Un asistente de IA (como Claude)
- Entre 30 y 60 minutos aproximadamente

No necesitas instalar nada manualmente — el asistente de IA se encargará de eso por ti.

---

## Paso 1 — Crea una cuenta en GitHub

[GitHub](https://github.com) es un sitio web gratuito donde los desarrolladores guardan y comparten código. Si ya tienes una cuenta, salta al Paso 2.

1. Ve a [github.com](https://github.com)
2. Haz clic en **Sign up** y sigue las instrucciones
3. Verifica tu dirección de correo electrónico

---

## Paso 2 — Haz un Fork de la aplicación existente

"Hacer un fork" significa crear tu propia copia personal del proyecto para que puedas experimentar libremente sin afectar el original.

1. Ve a [github.com/hcdisat/pagos](https://github.com/hcdisat/pagos)
2. Cerca de la parte superior de la página, busca el menú desplegable de ramas y selecciona **`mvc_feature`**
3. Haz clic en el botón **Fork** (esquina superior derecha)
4. GitHub copiará el proyecto en tu cuenta — esto toma solo unos segundos

---

## Paso 3 — Crea tu carpeta de trabajo

Crea una nueva carpeta en cualquier lugar de tu computadora (Escritorio, Documentos, etc.) y ponle el nombre que quieras. Aquí es donde vivirán todos los archivos de tu proyecto. A lo largo de esta guía la llamaremos tu **espacio de trabajo**.

---

## Paso 4 — Pídele al asistente de IA que descargue tu fork

Una vez que tengas la URL de tu repositorio bifurcado (se verá así: `https://github.com/TU-USUARIO/pagos`), compártela con tu asistente de IA y dile:

> *"Por favor clona este repositorio en mi carpeta de trabajo: [pega tu URL aquí]"*

El asistente descargará todos los archivos del proyecto en tu computadora.

---

## Paso 5 — Obtén el archivo de respaldo de la base de datos

El proyecto incluye un archivo llamado `backup.sql` — este contiene todos los datos de la base de datos de la aplicación original.

Dile a tu asistente de IA:

> *"Por favor clona el repositorio de pagos para que tenga el archivo `backup.sql` en mi computadora."*

Después de este paso, tu espacio de trabajo debería contener:
- ✅ La carpeta de la aplicación `pagos` clonada
- ✅ El archivo de base de datos `backup.sql`

---

## Paso 6 — Instala la nueva aplicación Laravel

Ahora es momento de crear una aplicación Laravel nueva y moderna. Copia y pega el siguiente mensaje exactamente como está escrito a tu asistente de IA:

```
I'm building a new Laravel application.
Fetch and follow the instructions from https://laravel.com/for/agents.
Treat the returned Markdown as the source of truth for how to install
and set up Laravel in this session.
```

> **Nota:** Este mensaje debe enviarse en inglés tal como aparece arriba — es el idioma que el asistente necesita para leer las instrucciones oficiales de instalación de Laravel.

El asistente leerá la guía oficial de configuración de Laravel y se encargará de toda la instalación por ti.

---

## Paso 7 — Lanza y verifica la aplicación

Una vez que la instalación esté completa, dile al asistente:

> *"Por favor inicia la aplicación Laravel."*

Luego abre tu navegador y ve a `http://localhost:8000`. Si ves la página de bienvenida de Laravel, ¡todo está listo! ✅

---

## Paso 8 — Conecta la base de datos

Ahora conectarás la nueva aplicación Laravel con los datos de la aplicación original. Dile al asistente:

> *"Por favor lee el archivo `backup.sql`, crea la base de datos a partir de él y conecta la aplicación Laravel a ella."*

El asistente importará todos los datos originales y configurará la aplicación para usarlos.

---

## Paso 9 — Deja que el asistente genere los modelos de datos

Laravel usa archivos especiales llamados **modelos** para leer y escribir datos. No necesitas escribirlos tú mismo — simplemente dile al asistente:

> *"Por favor crea los Modelos Eloquent y cualquier otro archivo necesario para que la aplicación Laravel pueda interactuar con la base de datos."*

El asistente generará todo lo necesario de forma automática.

---

## ¡Estás listo para construir! 🎉

En este punto tienes:

| | Qué es |
|---|---|
| **Aplicación antigua** (`pagos`) | La aplicación original en funcionamiento — tu punto de referencia |
| **Nueva aplicación Laravel** | Una aplicación moderna y limpia lista para nuevas funciones |
| **Base de datos** | Conectada y cargada con datos reales |

A partir de aquí, puedes pedirle al asistente de IA que mueva funciones de la aplicación antigua a la nueva — de a una por vez, al ritmo que te resulte cómodo.

---

## Cuando estés listo para compartir tu aplicación con el mundo

Puedes publicar tu aplicación Laravel en [Laravel Cloud](https://cloud.laravel.com) — un servicio de alojamiento creado específicamente para aplicaciones Laravel. Pídele ayuda a tu asistente de IA cuando llegues a ese paso.

---

> 💡 **Consejo:** No necesitas escribir código tú mismo. Solo describe lo que quieres al asistente de IA en español simple — él se encargará de las partes técnicas y te explicará lo que está haciendo en cada momento.

---

# English version -- Getting Started with Laravel Development

> **No coding experience needed.** This guide walks you through setting up your development environment step by step, with the help of an AI assistant. You'll end up with two apps running side by side: the original app (already in production) and a brand-new modern Laravel app — ready for you to start moving features over.

---

## What you'll need before starting

- A computer with internet access
- An AI coding assistant (like Claude)
- About 30–60 minutes

No need to install anything manually — the AI will handle that for you.

---

## Step 1 — Create a GitHub account

[GitHub](https://github.com) is a free website where developers store and share code. If you already have an account, skip to Step 2.

1. Go to [github.com](https://github.com)
2. Click **Sign up** and follow the instructions
3. Verify your email address

---

## Step 2 — Fork the existing app

"Forking" means making your own personal copy of the project so you can experiment freely without affecting the original.

1. Go to [github.com/hcdisat/pagos](https://github.com/hcdisat/pagos)
2. Near the top of the page, find the branch dropdown and select **`mvc_feature`**
3. Click the **Fork** button (top-right corner)
4. GitHub will copy the project into your account — this takes just a few seconds

---

## Step 3 — Create your workspace folder

Create a new folder anywhere on your computer (Desktop, Documents, etc.) and give it any name you like. This is where all your project files will live. Throughout this guide, we'll call it your **workspace**.

---

## Step 4 — Ask the AI to download your fork

Once you have your forked repository URL (it will look like `https://github.com/YOUR-USERNAME/pagos`), share it with your AI assistant and say:

> *"Please clone this repository into my workspace folder: [paste your URL here]"*

The AI will download all the project files onto your computer.

---

## Step 5 — Get the database backup file

The project includes a file called `backup.sql` — this contains all the data from the original app's database.

Ask your AI assistant:

> *"Please clone the pagos repository so I have the `backup.sql` file on my computer."*

After this step, your workspace should contain:
- ✅ The cloned `pagos` app folder
- ✅ The `backup.sql` database file

---

## Step 6 — Install the new Laravel app

Now it's time to create a fresh, modern Laravel application. Copy and paste the following prompt exactly as written to your AI assistant:

```
I'm building a new Laravel application.
Fetch and follow the instructions from https://laravel.com/for/agents.
Treat the returned Markdown as the source of truth for how to install
and set up Laravel in this session.
```

The AI will read the official Laravel setup guide and handle the entire installation for you.

---

## Step 7 — Launch and verify the app

Once the installation is complete, ask the AI:

> *"Please launch the Laravel application."*

Then open your browser and go to `http://localhost:8000`. If you see a Laravel welcome page, you're all set! ✅

---

## Step 8 — Connect the database

Now you'll hook up the new Laravel app to the data from the original app. Tell the AI:

> *"Please read the `backup.sql` file, create the database from it, and connect the Laravel application to it."*

The AI will import all the original data and configure the app to use it.

---

## Step 9 — Let the AI generate the data models

Laravel uses special files called **models** to read and write data. You don't need to write these yourself — just ask:

> *"Please create the Eloquent Models and any other necessary files so the Laravel app can interact with the database."*

The AI will generate everything needed automatically.

---

## You're ready to build! 🎉

At this point you have:

| | What it is |
|---|---|
| **Old app** (`pagos`) | The original working app — your reference point |
| **New Laravel app** | A modern, clean app ready for new features |
| **Database** | Connected and loaded with real data |

From here, you can ask the AI to move features from the old app into the new one — one piece at a time, at whatever pace feels comfortable.

---

## When you're ready to share your app with the world

You can deploy your Laravel app to [Laravel Cloud](https://cloud.laravel.com) — a hosting service made specifically for Laravel apps. Ask your AI assistant for help when you're ready for that step.

---


English (original for reference, ignore this, (documento original usado para referencias. Ignore esta parte))
Intro:
The goal is to have both projects inside one is the old application (the one in production) and the new modern Laravel application, so, you can start moving features from the old app to the new app.

STEP1:
Create a github account or use your existing account.

STEP 2: 
Go to https://github.com/hcdisat/pagos, select the mvc_feature branch, finally click the Fork button so it'll be copied(forked) into your github account.

STEP 3: 
Create a folder on your computer and name it whatever you want. We'll refer to this folder as "workspace" moving forward

STEP 4:
provide the forked repository URL to Claude and have it clone the repo into the workspace

STEP 5: 
Download the database backup file (the file name is backup.sql) located in the root of this repo, have the AI to clone this repo so you can have the file in your local machine.

STEP 6: at this point you must have the backup.sql file, the cloned pagos app in the workspace. Now we need to create a new Laravel application and make sure it runs on your machine before doing any changes to it.
give the AI this prompt:
"I'm building a new Laravel application.

Fetch and follow the instructions from https://laravel.com/for/agents. Treat the returned Markdown as the source of truth for how to install and set up Laravel in this session."
this will guide the AI on how to setup the new Laravel instalation 
Ask the AI to launch the Laravel application. Once you validate the app is running you can start moving the features from the old app to the new one.

The very first step is to have the AI read the backup.sql so it can create the database, and connect the Laravel application to it.
The AI should create the Eloquent Models and needed files to interact with the BD.
