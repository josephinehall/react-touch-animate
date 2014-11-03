
#react-touch-animate

A little Reveal.js presentation talking about React and creating touch and animation components.

Given at #SYDCSS in October 2014

##Setup

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the reveal.js repository
   ```sh
   $ git clone https://github.com/josephinehall/react-touch-animate.git
   ```

5. Install dependencies
   ```sh
   $ npm install
   ```

6. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view the presentation

   You can change the port by using `grunt serve --port 8001`.

Press 's' to bring up speaker notes

### Folder Structure
- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)

## License

MIT licensed

Copyright (C) 2014 Hakim El Hattab, http://hakim.se
