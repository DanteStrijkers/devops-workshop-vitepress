# 📊 Jouw DevOps Workshop Voortgangstracker

<div class="workshop-callout">
  <div class="workshop-callout-title">🎯 Belangrijk: Dit is Jouw Eerste DevOps Taak!</div>
  <p><strong>Het bewerken van deze pagina IS het oefenen van de Code fase!</strong> Je zult deze repo forken, deze tracker bewerken met jouw persoonlijke informatie, je wijzigingen committen en een Pull Request aanmaken. Dit leert je Git workflows terwijl je je voortgang bijhoudt.</p>
</div>

## Hoe Voortgang Bijhouden Werkt in Deze Workshop

**Meta-Leer Aanpak**: Deze voortgangstracker heeft een dubbel doel:
1. **Leermiddel**: Het bewerken ervan leert Git workflows (Code fase)
2. **Beoordelingsmiddel**: Het bijhouden van de voltooiing van alle 5 DevOps fasen

<div class="tip-box">
💡 <strong>Jouw Eerste Opdracht:</strong> Na het voltooien van de setup, personaliseer je de onderstaande secties met jouw informatie en commit je de wijzigingen. Dit oefent collaboratieve ontwikkeling via Git!
</div>

---

## Persoonlijke Workshop Informatie

**Deelnemer Naam:** `Dante Strijkers`  
**Workshop Datum:** `27/11/2025`  
**Doel:** `Mijn eerste CI/CD pipeline bouwen`  
**GitHub Gebruikersnaam:** `dantestrijkers`  
**Verwachte Site URL:** `https://dantestrijkers.github.io/devops-workshop-vitepress/`

---

## Fase Voltooiingstracker

Houd je voortgang bij door elke DevOps fase. **Bewerk dit bestand om je status bij te werken!**

<div class="progress-bar">
  <div class="progress-fill" style="width: 100%"></div>
</div>

### Fase 1: Code - Collaboratieve Ontwikkeling 🤝

<div class="phase-card">
  <div class="phase-header">
    <span class="phase-title">Fase 1: Code</span>
    <span class="workshop-status status-completed">Voltooid</span>
  </div>
  <p>Leer Git workflows, branching en Pull Requests</p>
</div>

**Voltooiing Checklist:**
- [x] De workshop repository geforkt naar mijn GitHub account
- [x] Mijn fork lokaal gekloond en de site werkend gekregen (`pnpm dev`)
- [x] Mijn eerste feature branch aangemaakt (`feat/code-fase`)
- [x] **Deze voortgangstracker bewerkt** met mijn persoonlijke informatie
- [x] Mijn eerste commit gemaakt met een goede commit message
- [x] Mijn branch gepusht naar GitHub
- [x] Mijn eerste Pull Request aangemaakt en gemerged
- [x] Geverifieerd dat mijn wijzigingen live zijn op mijn main branch

**Mijn Code Fase Notities:**

Begonnen met DevOps leren door hands-on oefening!
- **Git workflow** voelt nu natuurlijker.
- Begrijp hoe **branches** veilige samenwerking mogelijk maken.
- Enthousiast om mijn wijzigingen later automatisch te zien deployen.

**Tijdstempel Voltooid:** `13:48`

---

### Fase 2: Build - Geautomatiseerde Artifact Creatie 🔨

<div class="phase-card">
  <div class="phase-header">
    <span class="phase-title">Fase 2: Build</span>
    <span class="workshop-status status-completed">Voltooid</span>
  </div>
  <p>Transformeer broncode naar deploybare artifacts</p>
</div>

**Voltooiing Checklist:**
- [x] `.github/workflows/build.yml` bestand aangemaakt
- [x] Succesvol `pnpm build` lokaal uitgevoerd
- [x] Workflow gepusht en groene build gezien in GitHub Actions
- [x] Het build artifact gedownload en geverifieerd
- [x] Begrepen wat **build artifacts** zijn en waarom ze belangrijk zijn

**Mijn Build Fase Notities:**

De overgang van code naar een tastbaar **artifact** is een cruciaal moment.
- Het **build proces** is de eerste stap van de CI/CD-pijplijn.
- Artifacts zorgen voor **consistentie**: de code die wordt gebouwd, is precies wat wordt getest en gedeployed. Dit voorkomt 'Werkt op mijn machine' problemen.

**Tijdstempel Voltooid:** `13:52`

---

### Fase 3: Test - Kwaliteitsborging Automatisering 🧪

<div class="phase-card">
  <div class="phase-header">
    <span class="phase-title">Fase 3: Test</span>
    <span class="workshop-status status-completed">Voltooid</span>
  </div>
  <p>Implementeer geautomatiseerde testing en coverage rapportage</p>
</div>

**Voltooiing Checklist:**
- [x] `tests/site.test.js` aangemaakt met content validatie tests
- [x] Jest geconfigureerd met `jest.config.js`
- [x] Tests lokaal uitgevoerd met `pnpm test`
- [x] Test job toegevoegd aan CI workflow
- [x] >80% test coverage bereikt
- [x] Een test failure opgelost (gesimuleerd of echt)

**Mijn Test Fase Notities:**

- Wat ik geleerd heb over geautomatiseerde testing: **Geautomatiseerde testing** is de veiligheidsgordel van de pipeline. Het is veel efficiënter om een snelle test te laten falen dan om een bug in productie te vinden.
- Hoe testing bugs voorkomt: Door tests direct na de build uit te voeren, wordt de **feedbacklus** verkort. Dit dwingt tot het schrijven van betere, moduleerbare code.
- Testing inzichten: Het bereiken van een hoge **test coverage** geeft echt vertrouwen in elke commit.

**Tijdstempel Voltooid:** `13:57`

---

### Fase 4: Release - Versiebeheer 🏷️

<div class="phase-card">
  <div class="phase-header">
    <span class="phase-title">Fase 4: Release</span>
    <span class="workshop-status status-completed">Voltooid</span>
  </div>
  <p>Creëer versioned releases met semantic versioning</p>
</div>

**Voltooiing Checklist:**
- [x] Release job toegevoegd aan CI workflow (getriggerd door tags)
- [x] Mijn eerste tag aangemaakt en gepusht (`v1.0.0`)
- [x] Een release gegenereerd met downloadbare assets
- [x] Release ZIP bestand gedownload en geverifieerd
- [x] Het verschil begrepen tussen **releases** en **deployments**

**Mijn Release Fase Notities:**

- Wat ik geleerd heb over **semantic versioning**: Het is een duidelijk communicatiemiddel. `MAJOR.MINOR.PATCH` vertelt gebruikers onmiddellijk over de aard van de wijzigingen (brekende wijzigingen, nieuwe functies, of bugfixes).
- Hoe releases helpen met distributie: Releases creëren een **onveranderlijk archief** van de software op een specifiek punt. Dit maakt het gemakkelijk om terug te keren naar een bekende goede staat (rollback).
- Release management inzichten: **Tags** zijn de sleutel tot het automatiseren van het releaseproces, waardoor handmatige fouten worden geëlimineerd.

**Tijdstempel Voltooid:** `13:59`

---

### Fase 5: Deploy - Productie Automatisering 🚀

<div class="phase-card">
  <div class="phase-header">
    <span class="phase-title">Fase 5: Deploy</span>
    <span class="workshop-status status-completed">Voltooid</span>
  </div>
  <p>Automatisch deployen naar productie (GitHub Pages)</p>
</div>

**Voltooiing Checklist:**
- [x] Deploy job toegevoegd aan CI workflow
- [x] Succesvol site gedeployed naar GitHub Pages
- [x] Live site geverifieerd op: `https://dantestrijkers.github.io/devops-workshop-vitepress/`
- [x] Een wijziging gemaakt en het automatisch zien deployen
- [x] De volledige CI/CD pipeline voltooid van code tot productie

**Mijn Deploy Fase Notities:**

- Wat ik geleerd heb over **continuous deployment**: Het is het ultieme doel van CI/CD. Zodra code wordt gecommit en alle tests doorstaat, gaat deze automatisch naar productie, wat de **time-to-market** drastisch verkort.
- De kracht van automatisering: Een volledig geautomatiseerde pijplijn vermindert menselijke stress en fouten enorm. Het maakt de stap naar productie **saai en betrouwbaar**.
- Deployment inzichten: Het gebruik van **GitHub Pages** en de Action's `deploy` stap toonde de naadloze integratie die moderne platforms bieden.

**Tijdstempel Voltooid:** `14:02`

---

## Eindreflectie Workshop

### Algemene Leersamenvatting

1. Grootste DevOps inzicht dat ik heb verkregen:
   Het inzicht dat **DevOps gaat over automatisering en cultuur**. De automatisering (CI/CD) is krachtig, maar de onderliggende principes van snelle feedback en gedeelde verantwoordelijkheid tussen ontwikkeling en operaties zijn de echte game-changers.

2. Meest uitdagende deel van de workshop:
   Het oplossen van een initieel probleem met de **GitHub Actions workflow-syntax** (YAML). Kleine indentatie- of syntaxfouten leidden tot onverwacht gedrag, wat leerzaam was over de precisie die nodig is in automatisering.

3. Hoe dit mijn aanpak van softwareontwikkeling verandert:
   Ik zal nu altijd beginnen met het opzetten van een **basis CI/CD-pipeline** voordat ik me op grote functionaliteit stort. Weten dat elke wijziging snel kan worden gevalideerd en gedeployed, creëert een veiliger en sneller ontwikkelritme.

4. Wat ik wil implementeren op het werk/in persoonlijke projecten:
   **Geautomatiseerde Release Management** met Semantic Versioning en Git tags. En het gebruik van **build artifacts** om te zorgen dat dezelfde build door de hele pijplijn gaat.

5. Beoordeling (1-10) en waarom:
   **9/10**. De workshop was extreem **hands-on** en **goed gestructureerd**. Het leverde een tastbaar eindresultaat (een live site gedeployed via CI/CD), wat de theorie concreet maakte. Een 10 zou zijn als er een simulatie van een rollback-proces was inbegrepen.

### Mijn DevOps Pipeline Prestatie 🏆

**Definitieve Site URL:** `https://dantestrijkers.github.io/devops-workshop-vitepress`  
**Repository URL:** `https://github.com/DanteStrijkers/devops-workshop-vitepress`  
**Voltooiingsdatum:** `27/11/2025`

<div class="success-box">
🎉 <strong>Gefeliciteerd!</strong> Je hebt een complete CI/CD pipeline gebouwd en de volledige DevOps levenscyclus ervaren. Deel je prestatie door je site URL toe te voegen aan de workshop chat!
</div>

---

## Workshop Bronnen & Vervolgstappen

- 📚 **Uitbreidingen om te Proberen:** Workshop Uitbreidingen
- 🔧 **Hulp Nodig?** Probleemoplossing Gids  
- 💭 **Geef Feedback:** Workshop Feedback
- 📖 **Diepgaande Theorie:** CI/CD Overzicht

<div class="workshop-callout">
  <div class="workshop-callout-title">🎓 Workshop Voltooid!</div>
  <p>Onthoud: Elke bewerking aan deze tracker oefende Git workflows. Je hebt de volledige DevOps levenscyclus hands-on ervaren. Neem deze kennis mee en pas het toe om je ontwikkelpraktijken te transformeren!</p>
</div>