# cintel-05-cintel

* Simple PyShiny app with live data (using random, updating 1x/second)
* faicons for better icons on our cards
* pandas (and pyarrow) for data manipulation
* shinywidgets for showing plotly charts (render_plotly) and more
* plotly for interactive charts
* scipy for statistical analysis

# Try in the Browser

Go to PyShiny Playground at https://shinylive.io/py/examples/#basic-app. Copy and paste content from dashboard/app.py and run.

# Get the Code

Fork this project into  GitHub account and/or just borrow code from app.py. Clone  GitHub repo down to  local machine. s.

# git clone intel-05-cintel
Simple PyShiny app with live data (using random, updating 1x/second)

# Try in the Browser
Go to PyShiny Playground at https://shinylive.io/py/examples/#basic-app. Copy and paste content from dashboard/app.py and run.


# git clone https://github.com/Priyankanaskar/cintel-05-cintel
Run Locally - Initial Start
After cloning project down  Documents folder, open the project folder for editing in VS Code.

* Create a local project virtual environment named .venv, activate it, and install the requirements.

* When VS Code asks to use it for the workspace, select Yes. If you miss the window, after installing, select from the VS Code menu, View / Command Palette, and type "Python: Select Interpreter" and select the .venv folder.

* Open a terminal (VS Code menu "View" / "Terminal") in the root project folder and run these commands (for Windows - the activate command is slightly different Linux/Mac).

**py -m venv .venv**
**.venv\Scripts\Activate**
**py -m pip install --upgrade pip setuptools**
**py -m pip install --upgrade -r requirements.txt**
* Open a terminal (VS Code menu "View" / "Terminal") in
  the root project folder and run these commands.

# shiny run --reload --launch-browser dashboard/app.py
Open a browser to http://127.0.0.1:8000/ and test the app.

# Run Locally - Subsequent Starts
Open a terminal (VS Code menu "View" / "Terminal") in the root project folder and run these commands.

Open a terminal (VS Code menu "View" / "Terminal") in the root project folder and run these commands.

**shiny run --reload --launch-browser dashboard/app.py**
Open a browser to http://127.0.0.1:8000/ and test the app.

**Run Locally - Subsequent Starts**
Open a terminal (VS Code menu "View" / "Terminal") in the root project folder and run these commands.

*.venv\Scripts\Activate*
*shiny run --reload --launch-browser dashboard/app.py*
After Changes, Export to Docs Folder
Export to docs folder and test GitHub Pages locally.

Open a terminal (VS Code menu "Terminal" / "New Terminal") in the root project folder and run these commands.

shiny static-assets remove
shinylive export dashboard docs
**py -m http.server --directory docs --bind localhost 8008**
Open a browser to http://[::1]:8008/ and test the Pages app.

Push Changes back to GitHub
Open a terminal (VS Code menu "Terminal" / "New Terminal") in the root project folder and run these commands.

*git add .*
*git commit -m "Useful commit message"*
*git push -u origin main*
Enable GitHub Pages
Go to your GitHub repo settings and enable GitHub Pages for the docs folder.

# Explore
Implement better icons for the dashboard.


