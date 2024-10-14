# MANAS - Mental Analysis for Nations and Societies

**Project Overview:**
MANAS employs a cutting-edge machine learning model to predict Disability-Adjusted Life Years (DALYs) due to mental disorders. This innovation enables informed healthcare planning and policy formulation globally.

## How to Run the Project

1. **Download the Project:**
   - Download and unzip the project folder from GitHub.

2. **Set Up the Frontend:**
   - Navigate to the `MANAS_React` folder in your terminal.
   - Run the following commands:
     ```bash
     npm install
     npm run dev
     ```

3. **Set Up the Backend:**
   - Open a new terminal window and navigate to the `MANAS_Model_API` folder.
   - Start the API by running:
     ```bash
     uvicorn main:app --reload --port 5000
     ```

4. **Open the Application:**
   - Go to the `Manas_main` folder and open `index.html` using Live Server.
   - If the page does not load in your browser, follow these additional steps:
     - Go to **Extensions** > **Live Server** > **Settings**.
     - Check the option for **Use Local IP**.

5. **Analyze Data:**
   - Once `index.html` is open, click on the **Analyse** button.
   - Fill in the relevant values as required.
   - Click on **Predict**.
   - Wait for the result to show up.

## Troubleshooting
- If you encounter issues with loading `index.html`, ensure that Live Server is properly configured and that you are using the correct folder structure.

By following these steps, you should be able to successfully run the MANAS project and utilize its capabilities for mental health analysis.