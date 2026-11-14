# GitHub Copilot Instructions

## Project purpose
This project is an educational website for sharing homework assignments and coding exercises with students. Students can browse, view, and download assignments directly from the portal.

## Project structure
- [assignments/](../assignments/) contains each homework assignment in its own subfolder with a consistent structure.
- [templates/](../templates/) stores reusable templates for new content.
- [assets/](../assets/) contains the website assets, including CSS, JavaScript, images, and configuration files.
- [index.html](../index.html) is the main website page that serves as a static portal for browsing and viewing assignments.
- [config.json](../config.json) configures the content that dynamically generates the assignment lists and details.

## Project guidelines
- Maintain consistent styling across all pages.
- Keep file and folder names descriptive and organized.
- Preserve the static-site approach and avoid unnecessary complexity.
- Prefer minimal, focused changes that fit the existing structure and visual design.

## Educational standards
When generating content for this project:
- Learning-focused: all content should be designed with clear learning objectives and appropriate difficulty levels.
- Student-friendly: use clear, encouraging language that motivates students.
- Beginner-accessible: keep instructions understandable, practical, and easy to follow.
- Supportive: reinforce confidence and curiosity without overwhelming learners.

## Coding and content expectations
- Keep code readable, maintainable, and easy for students to learn from.
- Prefer simple HTML, CSS, and JavaScript patterns already used in the project.
- Match the tone and structure of the existing educational materials.
- Avoid introducing frameworks, build steps, or dependencies unless specifically required.
- When updating assignment content or starter code, keep it aligned with the learning goals of the exercise.

## Response expectations
- Favor practical, student-centered improvements.
- Keep explanations concise and instructional.
- If a change affects the portal, assignment flow, or configuration, preserve the dynamic structure driven by [config.json](../config.json).
- Do not rewrite learning material in a way that removes clarity or accessibility.
