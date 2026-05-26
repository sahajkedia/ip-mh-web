# ip-mh-web — Isha Place, Marathahalli

Static website for **Isha Place, Marathahalli** (programs, volunteering, and contact forms backed by Google Sheets + Apps Script).

Repository: [github.com/sahajkedia/ip-mh-web](https://github.com/sahajkedia/ip-mh-web)

## Run locally

From this folder:

```bash
chmod +x serve.sh   # first time only
./serve.sh
```

Then open [http://localhost:8765/](http://localhost:8765/).

Use another port if this one is busy:

```bash
PORT=8080 ./serve.sh
```

Set your Marathahalli Apps Script web app URL in `config.js` (see `setup-guide.md`) so programs, volunteering, and forms use your Google Sheet—not the Vijayanagar deployment.
