# Quick Gallery

An automated Python script to generate a static image gallery website from a directory of images.

## Features
- Creates thumbnail galleries where each image can be clicked to view in full-size.
- Automatic pagination with 20 images per page.
- Includes navigation links: Home, Previous, Next, and About.
- Uses Jinja2 templating engine for flexibility in design.
- Outputs the entire static website to an `output` directory.

## Prerequisites

- Python 3.x
- Jinja2

To install Jinja2, run:

```bash
pip install jinja2
```

## How to Use

1. Clone or download this repository.
2. Place your images in the `images` directory. You can also organize them in sub-folders within the `images` directory.
3. Run the `generate_gallery.py` script:

```bash
python generate_gallery.py
```

4. The static HTML pages will be generated inside the `output` directory. You can then deploy this folder to any web server or host it using services like GitHub Pages, Netlify, etc.

## Customization

If you want to change the appearance or structure of the gallery, you can edit the Jinja2 templates in the `templates` directory:

- `gallery.html`: The main gallery page template.
- `about.html`: The About page template.
- `style.css`: The CSS styles for the entire site.

After making changes, rerun the `generate_gallery.py` script to regenerate the static pages.

## License

This project is open-source. Feel free to fork, modify, and use in your projects.

## Contributions

Contributions, issues, and feature requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

## Support the Developer

If you found this helpful, please consider:

- **Buymeacoffee:** [Link](http://buymeacoffee.com/alteredadmin)
