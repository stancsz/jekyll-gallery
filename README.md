
# Jekyll Photo Gallery

A simple Jekyll-based photo gallery website with dynamic image resizing, image zoom, and a clean Bootstrap-based layout. This project uses the Masonry library for creating a responsive grid layout for your photos, and it mimics the style of Google Photos.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Jekyll project is designed to help you create a photo gallery website for showcasing your images. It includes responsive design, a grid layout, and the ability to dynamically resize and zoom images. Additionally, it provides a clean and user-friendly Bootstrap-based interface.

## Features

- Dynamic resizing of images to fit the user's screen.
- Masonry grid layout for displaying multiple images in an organized fashion.
- Clicking on an image opens a modal with the image title and description.
- Zoom-in effect on images when clicked.
- Navigation bar with links to the "About" and "Posts" pages.
- Social links in the navigation bar.
- Easy customization through Jekyll's configuration files.
- Bootstrap-based styling for a modern and clean look.

## Installation

1. Clone the repository to your local machine:

```
git clone https://github.com/yourusername/your-gallery-project.git
```

2. Install Jekyll if you haven't already:

```
gem install bundler jekyll
```

3. Navigate to the project directory:

```
cd your-gallery-project
```

4. Install the required gems:

```
bundle install
```

## Usage

1. Add your images to the `gallery` folder in the project directory.

2. Customize the project by editing the `_config.yml` file. You can change the site title, social links, and more.

3. Create Markdown files for your "About" and "Posts" pages in the root directory or the `_posts` folder.

4. Run the Jekyll server to preview your website:

```
bundle exec jekyll serve
```

5. Access the website in your browser at `http://localhost:4000`.

6. Customize the content and styling to match your preferences.

## Customization

You can customize various aspects of this project:

- **Site Configuration**: Edit the `_config.yml` file to change the site title, social links, and other settings.

- **Styling**: Modify the project's CSS file (usually `_sass/main.scss`) to customize the visual appearance.

- **Layout**: Adjust the layout by editing the `_layouts/default.html` file. You can modify the navigation, header, and footer.

- **Content**: Add or edit Markdown files for your content, such as "About" and "Posts."

## Contributing

Contributions are welcome! If you find any issues or have ideas for improvements, please open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
