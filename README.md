# Sudoku Master

A static mock website for the popular game Sudoku, built with pure HTML and CSS. This project is Part 1 of the CS5610 Web Development course assignments.

## Live Site

https://ivanlxc.github.io/cs5610_project_1/


## Collaborators

- Xingchen Liu (Github: ivanlxc)
- Xinyi Hu (Github: 123321-xy)


## Github Repo Link

https://github.com/ivanlxc/cs5610_project_1


## Video walkthrough

Link to be added

## Writeup

- What was the most challenging piece of this assignment?  Did you find it easy or challenging to work with HTML and CSS?  How long did this overall assignment take you?
    - The most challenging piece was building the Sudoku game board layout using pure CSS Grid. We needed to create a nested grid structure — an outer grid of 3x3 subgrids, each containing an inner 3x3 grid of cells — while maintaining proper visual borders and spacing between subgrids. Getting the cells to be perfectly square using `aspect-ratio: 1` and ensuring they scaled responsively across different screen sizes required a lot of trial and error. Working with HTML and CSS was moderately challenging; the basics were straightforward, but achieving pixel-perfect responsive layouts and a CSS-only menu (using a checkbox hack instead of JavaScript) pushed us to think creatively within the constraints of pure HTML/CSS.

- What decisions did you make when you made your site mobile friendly?
    - We set two main breakpoints at 768px (tablet) and 480px (small phone) using CSS media queries. For navigation, we implemented a CSS-only menu that collapses the horizontal nav links into a vertical dropdown on smaller screens. We switched multi-column layouts to single-column stacking — for example, the hero section changes from a side-by-side layout to vertically stacked, and the feature cards grid goes from 3 columns to 1. We also ensured buttons and input fields remain large enough for comfortable touch interaction.


- What did you take into account when you developed the design of your website?  Is there anything that you’re particularly proud of?
    - We aimed for a clean, modern, and professional design using a consistent blue primary color (#0984e3) across all pages, with CSS custom properties (variables) to ensure theming consistency. We chose the Poppins font family for its readability and modern feel, and used a card-based layout throughout the site for visual hierarchy. We're particularly proud of the Sudoku game board implementation — the nested CSS Grid structure with distinct subgrid borders closely resembles a real Sudoku puzzle, and the interactive states (given cells vs. player-input cells vs. empty cells) provide clear visual feedback. The high scores table with gold, silver, and bronze rank badges is another design element we're happy with.


- Given more time or resources, what additional features would you add to your site in the future? 
    - With more time, we would add JavaScript to make the Sudoku game fully playable — including puzzle generation, real-time validation, a working timer, and solution checking. We would also implement actual user authentication with backend support so that login and registration work beyond static forms. A real-time leaderboard that updates based on player performance would enhance the competitive aspect. Additionally, we would add difficulty-based puzzle filtering, a hint system, dark mode toggle, and the ability to save and resume games.


- How many hours did you spend on this assignment? (doesn’t need to be 3 sentences)
    - Around 18-20 hours total between both collaborators.




## Pages

1. **Home** - Landing page with game title, description, and feature highlights
2. **Selection** - Browse and select from a list of available puzzles
3. **Hard Game** - 9x9 Sudoku grid with 3x3 subgrids, timer, and number pad
4. **Easy Game** - 6x6 Sudoku grid with 2x3 subgrids, timer, and number pad
5. **Rules** - Game rules, tips, and credits section with contact links
6. **High Scores** - Leaderboard table with player rankings
7. **Login** - Username and password sign-in form
8. **Register** - Account creation form with password confirmation


