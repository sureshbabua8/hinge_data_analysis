Welcome to your Data Export!

What is included:

1. An 'index.html' file that provides a readable report of your data.
2. A directory of media files you uploaded (or linked via social media).
3. machine-readable data files
    * user.json
    * subscriptions.json
    * matches.json
    * media.json
    * prompts.json
    * fresh_starts.json
    * selfie_verification.json
    * match_notes.json
    * prompt_feedback.json


Instructions for viewing your data:

1. Navigate to the directory containing this file.
2. Open the index.html in your web browser (you may be able to "double-click" index.html and it will open in your default web browser).


Python / Jupyter setup (optional)

If you want to run the included notebook (data_analysis.ipynb) in an isolated virtual environment:

1. Create a venv in this folder:
   python3 -m venv .venv

2. Activate it:
   source .venv/bin/activate

3. Install dependencies:
   python -m pip install --upgrade pip
   python -m pip install -r requirements.txt

4. Make the venv selectable as a Jupyter kernel:
   python -m ipykernel install --user --name hinge-venv --display-name ".venv (hinge_exported_data)"

5. Run JupyterLab:
   jupyter lab

Then open data_analysis.ipynb and choose the ".venv (hinge_exported_data)" kernel.
