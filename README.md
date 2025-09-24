This project is a simple HTML page I created to practice how file paths work when linking resources like images in web development.

When building websites, the way you reference files is very important. If your file paths are wrong, images, CSS, or JavaScript files won’t load in the browser. In this project, I tested both absolute and relative paths to see how they behave.

What the Page Contains:

1. A short introduction about file paths.

2. Four images displayed using different path references:

3. Using ../ to move up one directory.

4. Using ./ to point to the current directory.

5. Using a direct relative path without ./.

6. Another direct reference within the assets/inserts/ folder.

7. Each screenshot is labeled (Screenshot1 → Screenshot4) so I can see which pathing method works and which one might break depending on where the HTML file is located.

Why I Built This:

To understand the difference between absolute paths and relative paths.

To see how the folder structure of a project affects file linking.

To practice organizing assets (like images) into a dedicated assets/ folder.

Lessons Learned

The browser looks for files relative to the location of the HTML file, unless given a full absolute path.

../ is used to move up one folder, ./ means the current folder, and leaving it blank also means “from the current folder”.

A small mistake (like writing atl instead of alt or using 250pxpx instead of 250px) can break HTML or accessibility.
