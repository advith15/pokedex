# Pokédex App

Welcome to the **Pokédex App**, a web application built using **React.js** that allows you to browse through all **151 original Pokémon** from the first generation. View detailed information including their **stats, types, abilities, and more!**

## Features

- 📜 **View All 151 Original Pokémon**
- 🔍 **Search for Pokémon by Name or Number**
- 📊 **Detailed Stats & Abilities**
- 🎨 **Responsive & Interactive UI**
- ⚡ **Fast & Lightweight (Powered by PokeAPI)**

## Demo

[Live Demo](#) *(Add your deployed link here)*

## Installation & Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/advith15/pokedex.git
   cd pokedex-app
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start the development server:**
   ```sh
   npm start
   ```

4. **Open in your browser:**
   ```
   http://localhost:5173
   ```

## Tech Stack

- **Frontend:** React.js, FantaCSS 
- **Data Source:** [PokeAPI](https://pokeapi.co/)

## API Usage

The app fetches Pokémon data from **PokeAPI**:
```js
fetch(`https://pokeapi.co/api/v2/pokemon/{pokemon_id}`)
  .then(response => response.json())
  .then(data => console.log(data));
```

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## License

This project is licensed under the **MIT License**.

## Acknowledgments

- [PokeAPI](https://pokeapi.co/) for Pokémon data
- Pokémon sprites from [official artwork sources]

