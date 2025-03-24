# come back to and add in
-Install Jellyfin Intros Plugin from `https://github.com/BrianCArnold/jellyfin-plugin-intros`
-need to add in the parts where you remove username pasword and change the libnrary and tags. point it out for the use use chatgpt to switch out personal information.

# Python-Jellyfin-Tagger

Python Script that autotags library content in Jellyfin. Created for the Local-Intros plugin, which uses local pre-roll media.

This will: 
✔ Log into Jellyfin
✔ Find the "name of your library" library
✔ Add the "your specified tag" tag to all items inside

---

## Prerequisites

Jellyfin Server


---

## Instructions

### 1. Install Python

- Download the latest version of Python from [Python.org](https://www.python.org/downloads/).
- **Important**: Make sure to check the box to add Python to your PATH during installation.

   After installation, confirm Python is correctly installed by opening the command prompt and typing:
   ```
   python --version
   ```

### 2. Install Required Python Packages

To interact with Jellyfin, we need to install the Jellyfin API Client.

- Open Command Prompt and run the following command to install the required package:
  ```
  pip install jellyfin-apiclient-python
  ```

### 3. Enable API Access in Jellyfin

- Open the Jellyfin Web UI: [http://localhost:8096](http://localhost:8096).
- Navigate to **Dashboard > Advanced > API Keys**.
- Ensure that **API Access** is enabled (if it's not already).
- Add an API key for the script to use.

**Note**: This will also work with Jellyfin Media Player.

---

## Scripts

There are currently three scripts available:

1. **Tag Movies**  
2. **Tag Series**
3. **Merged**

### 1. Create the Scripts

- Download From Repository [Here](blank/)

Or Manually create it
- The easiest way to create the scripts is by using Notepad:
   - Go to your desktop, click **New > Text Document**.
   - Rename the file to `yournamehere.py` (or `jellyfin_tagger_Series.py` for the other script).
   - Make sure to change the file extension from `.txt` to `.py`.
  

### 2. Run the Scripts

- Place the scripts in a directory you can access from the Command Prompt.
- Open Command Prompt and navigate to the script directory:
  ```
  cd your-directory-path-here
  ```
![1](https://github.com/user-attachments/assets/d4de3b10-50d0-4afc-b7dd-e55c4c595776)

![2](https://github.com/user-attachments/assets/8cab0e0d-d4b7-4c42-8a28-b3cfe38e1014)


- Run the script with:
  ```
  python "script_name.py"
  ```

- **Note**: If you have a lot of content, it may take some time, especially for shows.

---

## Verify Changes

1. Open the Jellyfin Web UI: [http://localhost:8096](http://localhost:8096).
2. Navigate to **Movies** or **Series** and check if the tags appear in the metadata.
3. If successful, the logs in Command Prompt will confirm that the tags were added.

---

## Final Steps


