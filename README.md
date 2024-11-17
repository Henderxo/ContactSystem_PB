## 🗄️ Setting Up PocketBase
### The project uses PocketBase as a lightweight backend. Follow the steps below to download PocketBase, replace the existing .db file, and set up the server.

###  Step 1: Download PocketBase
1. Visit the PocketBase GitHub Releases..
2. Download the latest version for Windows:
  For 64-bit: pocketbase_0.x.x_windows_amd64.zip
  For 32-bit: pocketbase_0.x.x_windows_386.zip
3. Extract the .zip file to a desired folder on your system.
### Step 2: Replace the Database File
Download existing .db file from https://github.com/Henderxo/ContactSystem_PB:

1. Copy your .db file (e.g., pb_data.db).
2. Go to the extracted PocketBase folder, and navigate to the pb_data directory:
```sh
cd path\to\pocketbase\folder\pb_data
```
3. Replace the default .db file wit .db file from the repository.

### Step 3: Start PocketBase Server

1. Open Command Prompt or PowerShell.
2. Navigate to the PocketBase folder:
```sh
cd path\to\pocketbase\folder
```
3. Start the server:
```sh
./pocketbase.exe serve
```
