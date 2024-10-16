# Documentation for cloning this Project

Before you begin, make sure you have the following installed:
- [Tailwind css](https://tailwindcss.com/docs/installation) (by tailwind css CLI steps)
- [Git](https://git-scm.com/) (for cloning the repository)

## Steps to Clone and Set Up

### 1. Clone the Repository

Open your terminal and run the following command to clone the project:

                git clone https://github.com/Swayam-Alhat/Login-page.git

3. Install Dependencies
This project uses Tailwind CSS, which requires some Node.js packages to work. To install them, so rum this command : 

                       npm install
            
This will install all the required dependencies listed in the package.json file and create a node_modules folder in your project. Note: The node_modules folder is not included in the repository because it's very large and can be regenerated by running npm install.

4. Build the CSS Automatically (Live Watch)
The output.css file (the compiled Tailwind CSS) is not included in the project repository, so you'll need to generate it locally. To do this, run the following command to watch for changes and automatically compile your CSS while you work: 
                       
                npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

This will create the output.css file in your src/ directory and automatically update it when changes are made to input.css.

**This will ensure that everything works correctly, but If any error occured Kindly asked and try ChatGPT :)**
