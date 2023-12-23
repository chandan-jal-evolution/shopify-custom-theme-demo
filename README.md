# Custom Shopify Theme App

Welcome to the Custom Shopify Theme App! This app provides a customized Shopify theme tailored to meet your unique requirements.

## Table of Contents

- [Directory Structure](#directory-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [License](#license)

## Directory Structure

The app is organized into the following directories:

- **assets**: Contains your theme's assets such as images, stylesheets, and JavaScript files.
- **config**: Includes configuration files for your theme.
- **layout**: Holds Liquid templates for your theme's layout.
- **locals**: Contains localization files for translating your theme.
- **sections**: Includes Liquid templates for your theme's sections.
- **snippets**: Contains reusable code snippets that can be included in various templates.
- **templates**: Includes Liquid templates for specific page types.

```plaintext
custom-shopify-theme-app/
|-- assets/
|-- config/
|-- layout/
|-- locals/
|-- sections/
|-- snippets/
|-- templates/
|-- config.yml
```

## Installation

To install the Custom Shopify Theme App, follow these steps:

1. Clone the repository: `git clone https://github.com/chandan-jal-evolution/shopify-custom-theme-demo.git`
2. Navigate to the app directory: `cd shopify-custom-theme-demo`
3. Customize the theme according to your needs.

## Usage

To use the Custom Shopify Theme App, follow these guidelines:

1. Upload the theme to your Shopify store.
2. Activate the theme from your Shopify admin dashboard.
3. Customize the theme settings as needed.

## Configuration

The app's configuration can be modified through the `config.yml` file. Adjust the settings in this file to tailor the theme to your preferences.

### Example `config.yml`:

```yaml
# Add your configuration settings here
password: You can use the provided password other wise you can use your own
theme_id: The Theme Id
store: testing-store-ei.myshopify.com
```

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as per the terms of the license.
