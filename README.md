# come back to and add in
-Install Jellyfin Intros Plugin from `https://github.com/BrianCArnold/jellyfin-plugin-intros`

This will: ✔ Log into Jellyfin
✔ Find the "name of your library" library
✔ Add the "your specified tag" tag to all items inside

#  -Start- Python-Jellyfin-Tagger
Python Script that Autotags Library content in Jellyfin. Created for Local-Intros plugin that uses local pre-roll media.

# Instructions

-Download Latest Version Of Python `https://www.python.org/downloads/` (Make sure to have the path assoication in the optional box checked, so command prompt recognizes python commands.)
Check if Python is Installed
To confirm Python was installed and recognized by your system, open command prompt and type:
`python --version`

# Install Required Python Packages

We need the Jellyfin API Client to interact with Jellyfin.
Install the package using pip
Run this in Command Prompt:
`pip install jellyfin-apiclient-python`

# Enable API Access in Jellyfin

Open Jellyfin Web UI (http://localhost:8096).

Go to Dashboard > Advanced > API Keys.

Ensure API Access is Enabled (if not already enabled).

Add an API key

Note- Will also work in Jellyfin Media Player

# Scripts
There are two scripts, one for tagging Movies and one for Series. add in a third for combined option later

# Running the Scripts
There are two scripts, one for tagging Movies and one for Series. There will be a third as spoon i come back and edit here
 The easies way to Create the files is using notepad:

 go to desktop, click new text document, reanme the file to whatever you want and add .py to the extension replace the txt extension.

In my case, 
    jellyfin_tagger_Movies.py

  jellyfin_tagger_Series.py

Place them in a directory you can access from Command Prompt. insert gif here to show how to copy directory paths

cd your direcrory path here
python "script name"

let script run, if you have alot of content, it will be a long time especially for shows

Verify Changes

    Open Jellyfin Web UI (http://localhost:8096).

    Navigate to Movies or Series and check if the tags appear in the metadata.

    If successful, the logs in Command Prompt will confirm the tags were added.
