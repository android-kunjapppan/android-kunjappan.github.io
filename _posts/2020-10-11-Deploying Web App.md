# Deploying a Jupyter Notebook into a Real App

<p>Start a new Notebook and add to it only the code needed to create and show the widgets that you need, and Markdown for any text that you want to appear.</p>

### Next install Voila 

`!pip install voila`

`jupyter serverextension enable voila --sys-prefix`

* The first line installs the voila library and application, and
* The Second line connects it to your existing jupyter notebook


### To view your notebook as a Voila web application

<p> Replace the word "notebooks" in your browsers URL with "voila/render". You'll see the same content as your notebook, but without any of the code cells.</p>


## Deploying to Binder <https://mybinder.org>

1. Add your notebook to a GitHub repository.
2. Paste the URL of that repo into Binder's URL field.
3. Change the File drop-down to instead select URL.
4. In the "URL to open" field, enter "/voila/render/name.ipynb"
5. Click the clipboard button at the bottom right to copy the URL and paste it somewhere safe.
6. Click Launch.
  
