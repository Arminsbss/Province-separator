# Province-separator
To convert this app into a GitHub repository, and run you can follow these steps:

1. **Create a GitHub Repository:**
   - Go to GitHub and create a new repository for your project.

2. **Initialize Git in your project directory:**
   - If you haven't already, navigate to your project directory in your terminal and run the following commands:
     ```
     git init
     ```

3. **Create a README.md file:**
   - Create a README.md file in your project directory. You can write the description, usage instructions, and any other relevant information about your project in Markdown format.

4. **Add your Python script:**
   - Copy your Python script into the project directory.

5. **Commit your changes:**
   - Add your files to the staging area and commit them using Git. Run the following commands:
     ```
     git add .
     git commit -m "Initial commit"
     ```

6. **Push to GitHub:**
   - Link your local repository to the GitHub repository you created and push your code. Run the following command:
     ```
     git remote add origin <https://github.com/Arminsbss/Province-separator>
     git push -u origin master
     ```

Your code, along with the README.md file, will be pushed to the GitHub repository. Here's how you can structure your README.md file:

```markdown
# Province Separator App

This is a Python application built using Tkinter that separates data from one Excel file into multiple Excel files based on province names.

## Usage

1. Clone the repository:

   ```bash
   git clone <https://github.com/Arminsbss/Province-separator>
   ```

2. Install the required dependencies:

   ```bash
   pip install pandas
   ```

3. Run the application:

   ```bash
   python engineer_sabour.ipynb
   ```

4. Select the Excel file containing the data.

5. Choose the output directory where the separated files will be saved.

6. Click on the "Generate Files" button to create separate Excel files for each province.

## Dependencies

- pandas

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
