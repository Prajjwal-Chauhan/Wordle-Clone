# 🎮 Wordle Game Clone

Welcome to the Wordle Game Clone repository! 🎉

This repository contains a fun and interactive Wordle game clone built using HTML, CSS, and JavaScript. The game challenges players to guess a hidden five-letter word by making consecutive guesses and receiving feedback on their progress.

## Game Features

⭐ Players can guess a five-letter word by selecting letters from the alphabet.

⭐ The game provides feedback on the correctness of each guess, indicating correct letters and their correct positions.

⭐ Players can reset the game and start over at any time.

⭐ The game supports dictionary lookup for valid words and provides hints if needed.

## Technologies Used

The following technologies and libraries were used to develop this Wordle game clone:

🔧 HTML\
🎨 CSS\
💻 JavaScript\
📦 Axios (npm library)\
🔒 Cors (npm library)\
⚡ Express (npm library)\
🔁 Nodemon (npm library)\
🔑 Dotenv (npm library)

## APIs Used

Two APIs were integrated into the game for additional functionality:

1. [**Dictionary API**](https://rapidapi.com/twinword/api/word-dictionary/?utm_source=ANIA-KUBOW&utm_medium=DevRel&utm_campaign=DevRel): This API allows the game to perform dictionary lookups to validate words. It ensures that players only guess valid words. The API used for this purpose is from RapidAPI.

2. [**Five-Letter Word Generator API**](https://rapidapi.com/apininjas/api/random-word-by-api-ninjas/): This API generates a random five-letter word for the player to guess. It provides a new word for each game session. The API used for this purpose is from RapidAPI.

## How to Run the Game

To run the Wordle game clone locally on your machine, follow these steps:

1️⃣ Clone this repository to your local machine using Git or download it as a ZIP file and extract it.

2️⃣ Install the required dependencies by running the following command in the project's root directory:

   ```shell
   npm install
   ```

3️⃣ Set up environment variables by creating a `.env` file in the project's root directory and adding the necessary configuration. For example:

   ```plaintext
   RAPIDAPI_KEY=your-api-key
   ```

   Replace `your-api-key` with the actual API key obtained from RapidAPI.

4️⃣ Run the game using the following command:

  First run the backend by navigating to `index.js` file, open the terminal and run the command:
  
   ```shell
   npm run start:backend
   ```
This will start fetching both the API's from your rapid API key. 

5️⃣ Now navigate to `index.html` file. If you are having a live server then click on `Go Live`. It will navigate you to your localhost. The game will start as soon as you go live.

## Contribution Guidelines

Contributions to this project are welcome! 🙌 If you have suggestions for improvements or would like to add new features, please follow these steps:

1️⃣ Fork the repository and clone it to your local machine.

2️⃣ Create a new branch for your feature or bug fix:

   ```shell
   git checkout -b feature/your-feature
   ```

3️⃣ Make your changes and test them thoroughly.

4️⃣ Commit your changes with clear and descriptive commit messages:

   ```shell
   git commit -m "Add feature/fix: description of changes"
   ```

5️⃣ Push your branch to your forked repository:

   ```shell
   git push origin feature/your-feature
   ```

6️⃣ Open a pull request on the original repository and provide a detailed description of your changes.

7️⃣ Wait for the maintainers to review your pull request. Once approved, your changes will be merged.

## License

This project is licensed under the [GNU General Public License v3.0](LICENSE). 📝

## Acknowledgements

Special thanks to RapidAPI for providing the Dictionary API and Five-Letter Word Generator API, which enhance the gameplay experience. 👏
