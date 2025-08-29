# SBA-307
This is the website for a Pokemon guessing game. The user must guess the correct Pokemon based on types, color, generation, and evolution hints. Currently, the game is not functional (Javascript is not implemented yet). This is a basic prototype.

## Features
The webpage consists of a home, about, login, register, and forgot password page. Each page contains a navbar. More details on each page can be found in the next session. The navbar can access the `index.html`, `about.html`, `login.html` pages.

## Project Structure
This section explains the structure of the project. The root folder contains the images and pages subfolders, README.md, and style.css.

### Images Folder
| File Name | Description/Purpose |
| --- | --- |
| `eevee.gif` | An Eevee with a confused face. Used in `index.html` in the Welcome section. |
| `favicon.ico` | A custom-made pokeball icon that resembles a Friend Ball, but the shade of green is altered to match the website theme. Used as the icon for all pages. |
| `logo.png` | A custom-made pokeball icon that resembles a Friend Ball, but the shade of green is altered to match the website theme. Used in the navbar (for all pages) and as a larger logo in the `login.html`, `register.html`, and `forgot-password.html` pages. |
| `pikachu-clap.gif` | A Pikachu that is clapping. Will be used in the pop up message that congratulates the user for guessing the pokemon. |
| `profile.png` | Standard user profile image. Used in the navbar. |
| `rayquaza.jpg` | Picture of a shiny Rayquaza. Used as the background in all pages, but tinted. |

### Pages Folder
| Page Title Name | File Name | Description | Accessible Pages |
| --- | --- | --- | --- |
| PokeGuesser \| Home | `index.html` | The home page consists of a welcome message, instructions on how to play the game, options (just a drop down menu), a form for the user to input guesses, and a table that displays all of the user's guesses.| Only Navbar pages |
| PokeGuesser \| About | `about.html` | The about page consists of heading text and a brief paragraph about the game's purpose and clarifications on having no relations to Nintendo. | Only Navbar pages |
| PokeGuesser \| Login | `login.html` | The login page consists of a login menu with the heading text, website logo, username and password fields, login button, and additional redirects for registering and handling forgotten passwords. | Navbar pages, `register.html`, and `forgot-password.html` |
| PokeGuesser \| Register | `register.html` | The registration page consists of a registration page with the heading text, website logo, fields such as username, password, confirm password, email, and button for registering. It also contains a redirect to the login page within the form. | Navbar pages and `login.html` |
| PokeGuesser \| Forgot Password | `forgot-password.html` | The forgot password page consists of a heading text, brief paragraph, and small form for submitting the user's email. | Navbar pages and `login.html` |

### Other Files
The `README.md` and `style.css` are also located in the root directory of the project. `README.md` is the read me file for the GitHub repository. The `style.css` file contains most of the styling for all pages. Some styling can be found in each respective webpage (inline and internal CSS is used).

## Instructions
After attaining a copy of the repo, navigate to the pages folder and open the index.html file. For more info on page navigation check the pages section and features section.