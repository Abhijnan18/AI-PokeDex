# PokeDex (Image Analyser)

This Python script utilizes the Google Generative AI library to analyze images of Pokemon and extract Pokedex data. If the provided image is not of a Pokemon, it refuses to provide information. The extracted data includes the name, type, species, height, weight, abilities, and a brief description of the Pokemon.

## Installation

Ensure you have Python installed, then run the following commands to install the required dependencies:

```bash
!pip install -q -U google-generativeai
!pip install pillow
```

## Usage

1. Clone this repository to your local machine.
2. Navigate to the directory containing the script.
3. Execute the script in a Jupyter Notebook or any Python environment.

Before running the script, you'll need to obtain an API key from Google Generative AI. You can find instructions on how to obtain an API key [here][(https://generativeai.dev/)](https://aistudio.google.com/app/apikey)).

Once you have obtained the API key, replace `"YOUR_API_KEY"` in the script with your actual API key. Also, ensure that you have images of Pokemon stored in the `pokemon/` folder for the script to analyze.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

This README now includes a note on obtaining the API key and a placeholder for where to insert it in the script.
