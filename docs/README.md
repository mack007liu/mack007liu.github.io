# GitHub Pages Documentation

This directory contains the source files for the GitHub Pages website hosted at [https://mack007liu.github.io](https://mack007liu.github.io).

## Structure

```
docs/
├── _config.yml        # Jekyll configuration file
├── index.html         # Main page
├── assets/
│   └── css/
│       └── style.css  # Custom styles
└── README.md         # This file
```

## Local Development

To run this site locally:

1. Install Ruby and Jekyll
2. Run `bundle install`
3. Run `bundle exec jekyll serve`
4. Visit `http://localhost:4000` in your browser

## Theme

This site uses the `jekyll-theme-minimal` theme. You can customize the appearance by modifying the CSS in `assets/css/style.css`.

## Configuration

The site configuration is in `_config.yml`. Update this file to change:

- Site title and description
- Theme settings
- Social media links
- Other Jekyll settings

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request 