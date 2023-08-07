# Personal Website built using Zola

Welcome to the repository of my personal website! This website is constructed using [Zola](https://www.getzola.org/), a rapid static site generator developed in Rust.

## Getting Started

To run this website on your local machine, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/GiriRock/portfolio-zola.git
   ```
2. **Navigate to the project directory:**
    ```sh
   cd portfolio-zola
   ```
3. **Install Zola:**
Ensure you have Zola installed on your system. You can download it from the [official website](https://getzola.org).

4. **Serve the website:**
    ```sh
    zola serve
    ```

5. **View in browser:**
Open your web browser and go to http://127.0.0.1:1111 to see the locally hosted website.

## Customization
Feel free to personalize the content and appearance of the website. You can modify files within the content and themes directories. The content directory holds your page content in Markdown, while the themes directory contains templates and styling.

## Deployment
When you're ready to deploy your website, generate static files using the zola build command:
```sh
    zola build
```


The generated files will reside in the public directory. You can then host these files on any web server that serves static content.

Author
This website is maintained by Giridharan.

- Website: https://giridharan.me
- GitHub: https://github.com/GiriRock