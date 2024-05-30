# Welcome to My GitHub Profile

Welcome to my GitHub profile! I'm Andres, a backend developer with a passion for fast learning, basketball, and nature walks. 🌲🏀 Here, you'll find a collection of my projects and solutions that demonstrate my skills and interests.

## About Me

👋 I'm Andres, a backend developer who loves tackling complex problems and finding efficient solutions. My interests include:
- **Backend Development:** I specialize in creating robust backend systems using various technologies.
- **Learning:** I'm a fast learner who enjoys keeping up with the latest trends and technologies in software development.
- **Hobbies:** When I'm not coding, you can find me playing basketball or enjoying nature walks.

## Pinned Projects

1. **DjangoDiscordBasedWebApp**
   - **Description:** A Discord-based web application where you can create rooms and send messages. Users can tag messages with different topics and log in to use the application.
   - **Technologies:** Python, Django

2. **DjangoBlogWebApp**
   - **Description:** A web application built with Django to facilitate easy content creation and management. It includes features for creating, editing, and deleting blog posts.
   - **Technologies:** Python, Django

3. **Codeforces---Solutions**
   - **Description:** This repository contains my solutions to various Codeforces problems.
   - **Technologies:** C++

4. **FileManagementSystem-AVLTree**
   - **Description:** A file management system that uses various data structures to provide efficient methods for storing, searching, and organizing files and directories.
   - **Technologies:** C++

5. **JavaScript-DictionaryAPI**
   - **Description:** A web application that consumes a dictionary API to provide word definitions. Users can search for words and retrieve their meanings and related information.
   - **Technologies:** JavaScript

6. **JavaScript-PokeAPI**
   - **Description:** A JavaScript project that uses the Pokémon API to provide names and images about various Pokémon.
   - **Technologies:** JavaScript

## Interactive Section

Below is an interactive JavaScript feature where you can explore and interact with my GitHub repositories. Click on the buttons to see more details about each project!

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive GitHub Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .repo {
            border: 1px solid #ddd;
            padding: 10px;
            margin-bottom: 10px;
        }
        .repo h3 {
            margin: 0;
        }
    </style>
</head>
<body>
    <h1>Welcome to My GitHub Profile</h1>
    <div id="repo-container"></div>

    <script>
        const repos = [
            {
                name: "DjangoDiscordBasedWebApp",
                description: "A Discord-based web application where you can create rooms and send messages. Users can tag messages with different topics and log in to use the application.",
                technologies: "Python, Django"
            },
            {
                name: "DjangoBlogWebApp",
                description: "A web application built with Django to facilitate easy content creation and management. It includes features for creating, editing, and deleting blog posts.",
                technologies: "Python, Django"
            },
            {
                name: "Codeforces---Solutions",
                description: "This repository contains my solutions to various Codeforces problems.",
                technologies: "C++"
            },
            {
                name: "FileManagementSystem-AVLTree",
                description: "A file management system that uses various data structures to provide efficient methods for storing, searching, and organizing files and directories.",
                technologies: "C++"
            },
            {
                name: "JavaScript-DictionaryAPI",
                description: "A web application that consumes a dictionary API to provide word definitions. Users can search for words and retrieve their meanings and related information.",
                technologies: "JavaScript"
            },
            {
                name: "JavaScript-PokeAPI",
                description: "A JavaScript project that uses the Pokémon API to provide names and images about various Pokémon.",
                technologies: "JavaScript"
            }
        ];

        function displayRepos() {
            const container = document.getElementById('repo-container');
            repos.forEach(repo => {
                const repoDiv = document.createElement('div');
                repoDiv.className = 'repo';
                repoDiv.innerHTML = `
                    <h3>${repo.name}</h3>
                    <p>${repo.description}</p>
                    <p><strong>Technologies:</strong> ${repo.technologies}</p>
                `;
                container.appendChild(repoDiv);
            });
        }

        window.onload = displayRepos;
    </script>
</body>
</html>
```

<!--
**AnndyyRobles/AnndyyRobles** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
