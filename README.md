FOSS WebApp
________________

Nomad doesn't use a cloud storage system, it relies on browser cache, it is up to you to back up your own items from Nomad notes with the built in export feature that exports your data as a JSON.
<br>
<br>
If you plan on clearing your browser cache, export first.

<br>


License:
See MIT license.

<br>
<br>
<br>
Self Hosting:
<br>
Clone the Repo:

```bash
git clone "https://github.com/ColaCaine/nomad.git"
```
Install Homebrew:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" #Install Homebrew
```
Install Python dependency:
```bash
brew install python3
```
Enter Nomad:
```bash
cd nomad
```
Begin hosting via Python:
```bash
python -m http.server 8080 # or another port of your choice, you can pretty much put whatever, 8000, 8800, 1200, whatever, this is so you can have more than one port open to host multiple things.
```
Open the following link/url (you may have to change the number if you chose a different port): [localhost:8080](https://localhost:8080)