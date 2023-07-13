# [Periodic Table](https://scientific-boats.surge.sh/)
This is a static website that displays the periodic table of elements using [Bulma CSS](https://bulma.io/) and [Hugo](https://gohugo.io/). It uses Hugo's features such as archetypes, data files, shortcodes and templates to reduce redundancy and make the code more maintainable.

![periodic-table.png](https://periodic-table-photo.surge.sh/periodic-table.webp)

## How to run the project

To run the project, you must have [Hugo](https://gohugo.io/getting-started/installing/) installed on your system.

Follow these steps to set up the project after cloning from git:

1. Open a terminal and navigate to the project directory.
2. Run `hugo server` to start the development server.
3. Open your browser and go to `http://localhost:1313` to see the website in action.

## How to use the website

The website has a simple interface that allows you to view the periodic table of elements. Visit the site at [Periodic Table](https://scientific-boats.surge.sh/). You can click on an element to go to its detail page, where you can see more information such as its category, group, period, block, electron configuration and properties.

## How the project works

The project uses Hugo's archetypes to create a template for each element's detail page. The archetype contains the front matter variables and the layout for the page. The data for each element is stored in a JSON file in the `data` directory. The JSON file contains an array of objects, each representing an element with its attributes.

The project also uses Hugo's shortcodes to create reusable components for the periodic table and the element cards. The shortcodes take parameters from the data file and generate the HTML code for the components. The shortcodes are defined in the `layouts/shortcodes` directory.

The project uses Bulma CSS as a framework for styling the website. Bulma provides a responsive grid system, typography, colours, icons and components that make the website look modern and elegant. The custom CSS code is written in a file called `style.css` in the `static/css` directory.

The project uses Hugo's templates to define the layout and structure of the website. The templates are composed of partials, which are reusable chunks of HTML code that can be included in other templates. The templates are defined in the `layouts` directory.

## How to contribute

Feel free to open an issue or pull request if you have any suggestions or feedback for improving this project. I would appreciate your contribution.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
