# Forge & Craft Website

A clean, minimal website for [Forge & Craft](https://forgeandcraft.co.uk) - showcasing creative projects and events.

![Forge & Craft Logo](https://metapixl.com/storage/avatars/054/671/252/002/144/040/8/tmt1cRqh02wITSu3RHGU_avatar.png?v=3)

## About

This is a single-page application hosted on [omg.lol](https://omg.lol), featuring:

- Clean, responsive design
- Event information and updates
- Integration with social media and galleries
- Photo gallery

## Project Structure

```
├── spa.html    # Main website HTML file
├── deploy.sh   # Deployment script
└── README.md   # This file
```

## Development

The site is built as a static HTML page with embedded styles and JavaScript as omg.lol does not support external CSS or JS files.

## Deployment

Deployment is handled via [clilol](https://clilol.readthedocs.io/latest/), which uploads the site to omg.lol:

```bash
./deploy.sh
```

**Prerequisites:** Install `clilol` and configure your omg.lol credentials.

## License

All content and code for the Forge & Craft website.
