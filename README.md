# cccc-website

**Chronological Corpora Curve Clustering — R Package Website**

[![GitHub Pages](https://img.shields.io/badge/docs-GitHub%20Pages-blue)](https://lucadaniello.github.io/cccc-website/)
[![R Package](https://img.shields.io/badge/R%20package-matildet%2Fcccc-brightgreen)](https://github.com/matildet/cccc)

## About

This is the official website for the **cccc (Chronological Corpora Curve Clustering)** R package. The website provides comprehensive documentation, tutorials, and examples for using the CCCC package for corpus linguistics analysis and time-series clustering.

## What is cccc?

cccc is an R package designed for analyzing chronological patterns in text corpora through advanced curve clustering techniques. It enables researchers to:

- Analyze temporal trends in linguistic data
- Cluster time-series data from text corpora
- Visualize chronological patterns and changes
- Perform statistical analysis on corpus evolution

## Website Contents

This Quarto-based website includes:

- **Home**: Introduction and overview of the cccc package
- **cccc Package**: Detailed information about the package features
- **Functions**: Complete documentation of available functions
- **Use Cases**: Real-world applications and examples
- **Projects**: Research projects using cccc
- **About Us**: Information about the development team
- **References**: Academic references and citations

## Installation

To install the cccc package, visit our [Download page](https://lucadaniello.github.io/cccc-website/) or follow these steps:

```r
# Install remotes package if needed
install.packages("remotes")

# Install CCCC from GitHub
remotes::install_github("matildet/cccc")
```

## Using This Website

This website is built with [Quarto](https://quarto.org/), a scientific and technical publishing system. To build and preview the website locally:

### Prerequisites

- R and RStudio
- Quarto (install from [quarto.org](https://quarto.org/docs/get-started/))

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/lucadaniello/cccc-website.git
   cd cccc-website
   ```

2. Open the project in RStudio (`cccc-website.Rproj`)

3. Preview the website:
   ```bash
   quarto preview
   ```

4. Build the website:
   ```bash
   quarto render
   ```

The rendered website will be in the `docs/` directory.

## Contributing

We welcome contributions to improve the CCCC website! Here's how you can help:

### Reporting Issues

If you find any errors, broken links, or have suggestions:

1. Check if the issue already exists in our [Issues](https://github.com/lucadaniello/cccc-website/issues)
2. If not, [open a new issue](https://github.com/lucadaniello/cccc-website/issues/new) with a clear description

### Submitting Changes

1. Fork this repository
2. Create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes to the `.qmd` files
4. Test your changes locally with `quarto preview`
5. Commit your changes with a descriptive message:
   ```bash
   git commit -m "Add: description of your changes"
   ```
6. Push to your fork and submit a pull request

### Content Guidelines

- Use clear, concise language
- Include code examples where appropriate
- Follow the existing formatting style
- Test all R code examples before submitting
- Add references for academic or technical claims

## Project Structure

```
cccc-website/
├── _quarto.yml          # Quarto configuration
├── index.qmd            # Home page
├── cccc-package.qmd     # Package overview
├── functions.qmd        # Functions documentation
├── use-cases.qmd        # Use cases and examples
├── projects.qmd         # Research projects
├── about-us.qmd         # About the team
├── references.qmd       # References
├── styles.css           # Custom styles
├── images/              # Image assets
├── functions/           # Individual function docs
├── singleFunctions/     # Additional function docs
└── docs/                # Rendered website (GitHub Pages)
```

## Links

- 🌐 **Website**: [https://lucadaniello.github.io/cccc-website/](https://lucadaniello.github.io/cccc-website/)
- 📦 **R Package**: [https://github.com/matildet/cccc](https://github.com/matildet/cccc)
- 🐛 **Issues**: [https://github.com/lucadaniello/cccc-website/issues](https://github.com/lucadaniello/cccc-website/issues)

## License

[Add your license information here]

## Contact

For questions about the cccc package or this website, please:

- Open an issue on this repository
- Visit the [About Us](https://lucadaniello.github.io/cccc-website/about-us.html) page for contact information


---