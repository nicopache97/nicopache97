---
description: Guide for creating a professional GitHub Profile README
---

# GitHub Profile README Best Practices

This skill outlines best practices for creating an engaging and professional GitHub Profile README, based on successful examples.

## Structure

A great profile README typically follows this structure:

1.  **Header**:
    -   **Greeting**: A friendly opening (e.g., "Hi 👋, I'm [Name]").
    -   **Headline**: A brief, catchy tagline about what you do (e.g., "I build systems. I break assumptions. I ship.").
    -   **Hero Image/Banner**: An optional but recommended visual element.

2.  **Introduction & Bio**:
    -   **About Me**: Bullet points covering:
        -   Current work/projects.
        -   Collaboration interests.
        -   Portfolio link.
        -   Blog/Writing link.
        -   Contact info.
        -   Fun fact or additional info.
    -   Use emojis to make it visually appealing.

3.  **Stats & Metrics**:
    -   Showcase your GitHub activity using tools like `github-readme-stats`.
    -   Include:
        -   General stats (stars, commits, PRs).
        -   Top languages.
        -   Streak stats.
        -   Profile views counter.
        -   Trophies (optional).

4.  **Tech Stack**:
    -   List languages, frameworks, and tools you use.
    -   Use icons/badges (e.g., from `devicon` or `shields.io`) instead of just text for a cleaner look.
    -   Group them logically (e.g., Languages, Frameworks, Tools, Cloud).

5.  **Social Links**:
    -   Direct links to your other profiles (LinkedIn, Twitter/X, Medium, Portfolio).
    -   Use icons for these links.

## Tools & Resources

-   **Stats**:
    -   `https://github-readme-stats.vercel.app/`
    -   `https://github-readme-streak-stats.herokuapp.com/`
    -   `https://komarev.com/ghpvc/` (Profile views)
    -   `https://github.com/ryo-ma/github-profile-trophy`

-   **Icons & Badges**:
    -   `https://shields.io/`
    -   `https://simpleicons.org/`
    -   `https://github.com/devicons/devicon`

## Markdown Snippets

### Centered Header
```markdown
<h1 align="center">Hi 👋, I'm [Name]</h1>
<h3 align="center">[Tagline]</h3>
```

### Banner/Gif
```markdown
<p align="center">
  <img src="[URL]" alt="banner" />
</p>
```

### Stats Row
```markdown
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=[gh_username]&show_icons=true&locale=en" alt="stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=[gh_username]&" alt="streak" />
</p>
```
