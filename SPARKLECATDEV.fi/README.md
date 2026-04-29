# SPARKLECATDEV.fi

Static personal website for SPARKLECATDEV.fi. The site is built as plain HTML, CSS, JavaScript, and local image assets, so it can be hosted by any static web host.

## Structure

- `index.html` - main site page with home, FAQ, and character sections.
- `donate/index.html` - donation page.
- `assets/images/` - site artwork and image assets.
- `robots.txt` - crawler rules.
- `LICENSE.txt` - project license.

## Local Preview

Open `index.html` in a browser from the `SPARKLECATDEV.fi` folder.

For a local server preview, run:

```sh
cd SPARKLECATDEV.fi
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Upload the contents of `SPARKLECATDEV.fi` to a static hosting provider. Keep the folder structure unchanged so page links and image paths continue to resolve correctly.

## License

See `LICENSE.txt`.
