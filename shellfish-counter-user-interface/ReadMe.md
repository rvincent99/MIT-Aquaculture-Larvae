# Setting up Local Backend Server

Clone this repository.
On your computer, add folder "custom_v14 copy" from the shared Google Drive to the backend folder (due to GitHub size restraints).

1. Navigate to the user interface repository.
2. Set up and activate a virtual environment:
   ```bash
   python3 -m venv myenv
   source myenv/bin/activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Start the backend server:
   ```bash
   node backend/index.js
   ```

# Setting up Front End

1. Open a new terminal tab.
2. Navigate to the `src` directory:
   ```bash
   cd src
   ```

3. Start the React app:
   ```bash
   npm start
   ```
