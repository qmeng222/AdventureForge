# AdventureForge

## About the project:

- Description: An interactive choose your own adventure app powered by the Stable Diffusion model.
- Highlights:
  - Choose your path: Navigate through a branching storyline where your choices have real consequences. Craft your own adventure by deciding the fate of the protagonist
  - AI-generated text: Experience the magic of the Stable Diffusion model as it dynamically generates descriptive and engaging text that evolves with your choices, keeping you engaged at every turn.
  - Scene visualization: Watch your adventure come to life with scene images generated in real-time, providing visual context and enhancing your immersive storytelling experience.
  - Endless adventures: With multiple storylines, characters, and outcomes, AdventureForge offers endless replayability, ensuring every adventure is a unique and thrilling experience.
- Tech stack:
  - Programming language: Python
  - Computing platform: Jupyter Notebook
  - Text-to-image model: Stable Diffusion
  - Web development framework: Flask
  - Front-end: HTML, CSS, JavaScript
  - Version control: Git, GitHub
- Overview:
  ![project overview](/abc.png)

## Setup:

1. Create & activate the virtual environment (and all subsequent steps will be performed within the virtual environment):
   ```
   python -m venv .venv
   source .venv/bin/activate
   ```
2. Upgrade the pip package manager to the latest version within the current Python environment: `python -m pip install --upgrade pip`
3. Install Jupyter, and configure a kernel specifically for the virtual environment.
   - Install Jupyter in the virtual environment (so that I can use Jupyter notebooks within the virtual environment): `pip install jupyter`
   - Install ipykernel within the virtual environment (to create and manage kernels for Jupyter notebooks): `pip install ipykernel`
   - Create and install a kernel specifically for the virtual environment: `python -m ipykernel install --user --name=myenv`
4. Install libraries/packages:
   - Install the software development kit (SDK): `pip install stability_sdk`
   - install OpenAI: `pip install openai`
   - Install the python-dotenv package: `pip install python_dotenv`
   - Install the pillow package that provides the PIL (Python Imaging Library) module to work with images: `pip install pillow`
   - Install Flask: `pip install Flask`
   - Start the Flask development server in debug mode: `flask run --debug`
5. Generate a snapshot of the installed packages and their versions to the requirements.txt file (or overwrite the txt file): `pip freeze > requirements.txt`, so others can install all the packages and their respective versions specified in the requirements.txt file with `pip install -r requirements.txt`

## Resources:

1. [stability.ai API | Documentation](https://platform.stability.ai/docs/features)
2. [Text-to-image via gRPC API](https://platform.stability.ai/docs/features/text-to-image)
3. [DreamStudio](https://beta.dreamstudio.ai/generate)
