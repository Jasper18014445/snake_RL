# 🤖 Reïnforcement Learning in Snake

Welkom bij de GitHub-repository over **Reïnforcement Learning (RL)** in het spel **Snake**.  
In dit project is er een RL model ontwikkeld dat in staat is om Snake te spelen.

Het project combineert een bekende en overzichtelijke spelomgeving met geavanceerde leertechnieken. Hierdoor konden we op gestructureerde wijze kennismaken met de concepten achter autonome besluitvorming en zelflerende systemen. Deze repository bevat de code, documentatie en een toelichting op de ontwerpkeuzes die we tijdens het ontwikkelproces hebben gemaakt.

---

## 🐍 Snake

**Snake** is een klassiek en bekend computerspel waarbij de speler een slang bestuurt die probeert zoveel mogelijk voedsel op te eten. Bij elk stuk voedsel dat wordt gegeten, groeit de slang, waardoor het spel geleidelijk moeilijker wordt.  

Het doel is om zo lang mogelijk te overleven zonder tegen de muren of jezelf aan te botsen. Dankzij de eenvoudige spelregels en oplopende complexiteit is Snake bijzonder geschikt als testomgeving voor leer- en besluitvormingsalgoritmen.

---

## 🎯 Waarom Reïnforcement Learning?

Reïnforcement Learning is een krachtige methode om systemen te trainen op basis van beloningen en straffen. In plaats van vooraf vast te leggen welke acties optimaal zijn, leert het model door ervaring welke keuzes leiden tot succes.

De spelomgeving van Snake biedt hierbij meerdere voordelen:

- 📈 **Simpele standaard beloningsstructuur**: bijvoorbeeld +1 voor voedsel, -1 bij een botsing  
- 🌍 **Dynamische omgeving**: elke actie beïnvloedt direct de toekomstige situatie  
- 🧭 **Langetermijnstrategie vereist**: de agent moet vooruitdenken om te overleven

Deze eigenschappen maken Snake tot een waardevolle omgeving om de werking van reinforcement learning in de praktijk te verkennen.

---

## 📁 Projectstructuur

```plaintext
📁 Snake_RL
├── 📁 notebooks/
│   ├── 📜
│   ├── 📜
├── 📁 src/
│   ├── 📜
│   ├── 📜
├── 📜 .gitignore
├── 📜 LICENSE
├── 📜 README.md
├── 📜 requirements.txt
```

---

## 🚀 Installatie

Volg deze stappen om het project lokaal op te zetten:

1. **Clone de repository**
   ```bash
   git clone https://github.com/jasper18014445/Snake_RL.git
   cd Snake_RL
   ```

2. **Installeer de vereiste pakketten**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🏗 Gebruik

Het is aan te raden om de code enkel via notebooks te gebruiken, gezien er geen functionaliteit is gemaakt voor het runnen van losse bestanden. Je kunt de notebooks openen en uitvoeren met Jupyter Notebook of Jupyter Lab:

```bash
jupyter notebook
```

---

## 📊 Geteste modellen

T.B.D.

---

## 📜 Licentie

Dit project is beschikbaar onder de **MIT License**. Zie [`LICENSE`](LICENSE) voor meer details.
