This task was completed using Antigravity IDE with Tailwind CSS for styling and UI.
Follow the steps below to run the code.

Run the following command in the terminal:(npm install tailwindcss @tailwindcss/cli)

Create a src folder, and inside it, create an input.css file.

In the input.css file, write:(@import "tailwindcss";)

Run the following command in the terminal:(npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch)
This will generate an output.css file inside the src folder.


Create an index.html file in the main project folder (outside the src folder).

Link the ./src/output.css file in your index.html, then start writing your HTML code.
