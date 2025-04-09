# 🕹️ Tic-Tac-Toe în React

Acesta este un proiect simplu de joc Tic-Tac-Toe (X și O) creat în React, construit în scop educațional pentru a învăța conceptele de bază ale React: componente funcționale, state, props, lifting state up, imutabilitate și time travel.

---

## 📁 Structura fișierelor

```bash
src/
├── components/
│   ├── Board.js
│   ├── Game.js
│   └── Square.js
├── styles/
│   └── styles.css
├── App.js
├── index.js
└── ...
```

---

## 🚀 Cum rulezi aplicația

### 1. Instalează Node.js

Verifică dacă ai deja Node.js instalat:
```bash
node -v
```

Dacă nu, descarcă de pe: [https://nodejs.org](https://nodejs.org)

### 2. Creează proiectul React (dacă e de la zero)

```bash
npx create-react-app tic-tac-toe
cd tic-tac-toe
```

### 3. Rulează aplicația local

```bash
npm install
npm start
```

Aplicația va porni la `http://localhost:3000`.

---

## 🎮 Funcționalități implementate

- ✅ Tablă de joc 3x3 cu pătrate interactive
- ✅ Alternarea între jucătorii X și O
- ✅ Determinarea câștigătorului
- ✅ Time Travel – navigarea prin mutările anterioare
- ✅ Resetarea jocului la orice mutare anterioară

---

## 🧠 Ce am învățat

- Cum se structurează un proiect React
- Cum se utilizează `useState` pentru gestionarea stării
- Cum se transmite informația între componente cu props
- Cum se mută starea într-un component părinte (lifting state up)
- Cum se aplică concepte de imutabilitate și randare condiționată

---
