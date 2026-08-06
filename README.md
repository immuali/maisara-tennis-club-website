# Maisara Tennis Club Website

Static, responsive website for the Maisara Tennis Club Community Junior Tennis Program in Zanzibar.

## Files

- `index.html` — website structure and content
- `style.css` — layout, colours and responsive design
- `script.js` — mobile navigation and automatic copyright year
- `.gitignore` — excludes local and sensitive files from GitHub

## Run locally

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with Ansible and Nginx

Push these files to a public GitHub repository. Use an Ansible playbook to clone the repository and copy `index.html`, `style.css` and `script.js` to `/usr/share/nginx/html/` on the EC2 server.

## Contact

Registration enquiries: immusaleh@gmail.com
