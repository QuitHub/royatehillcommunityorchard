# Contributing to Royate Hill Community Orchard Website

Thank you for your interest in contributing to the Royate Hill Community Orchard website! We welcome contributions from everyone.

## How to Contribute

### Reporting Issues

If you find a bug or have a suggestion for improvement:

1. Check if the issue already exists in the [Issues](https://github.com/QuitHub/royatehillcommunityorchard/issues) section
2. If not, create a new issue with a clear title and description
3. Include screenshots if relevant
4. Tag the issue appropriately (bug, enhancement, documentation, etc.)

### Making Changes

1. **Fork the Repository**
   ```bash
   # Click the "Fork" button on GitHub, then clone your fork
   git clone https://github.com/YOUR_USERNAME/royatehillcommunityorchard.git
   cd royatehillcommunityorchard
   ```

2. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

3. **Make Your Changes**
   - Keep changes focused and atomic
   - Follow the existing code style
   - Test your changes locally by opening `index.html` in a browser
   - Ensure the site is responsive (test on mobile/tablet sizes)

4. **Test Your Changes**
   ```bash
   # Start a local server
   python -m http.server 8000
   # Visit http://localhost:8000 in your browser
   ```

5. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Brief description of your changes"
   ```
   
   Write clear, descriptive commit messages:
   - Use the imperative mood ("Add feature" not "Added feature")
   - Keep the first line under 72 characters
   - Add details in the body if needed

6. **Push and Create a Pull Request**
   ```bash
   git push origin feature/your-feature-name
   ```
   Then create a Pull Request on GitHub.

## Code Style Guidelines

### HTML
- Use semantic HTML5 elements (`<header>`, `<main>`, `<section>`, `<footer>`)
- Include ARIA labels for accessibility
- Use proper heading hierarchy (h1 → h2 → h3)
- Add alt text for images
- Keep lines under 120 characters when possible

### CSS
- Use clear, descriptive class names
- Follow BEM or similar naming convention if adding classes
- Ensure responsive design (test at 320px, 768px, 1024px, 1920px)
- Use relative units (em, rem, %) where appropriate
- Group related styles together
- Add comments for complex styles

### Accessibility
- Maintain keyboard navigation
- Ensure sufficient color contrast (WCAG AA minimum)
- Test with screen readers when possible
- Use semantic HTML
- Include skip links if adding navigation

### Performance
- Optimize images before adding (use tools like ImageOptim, TinyPNG)
- Minimize use of external dependencies
- Keep CSS and JavaScript inline if small, external if large

## Types of Contributions Welcome

### Content
- Fix typos or grammatical errors
- Improve clarity of existing text
- Add missing information (with permission from orchard team)
- Update outdated information

### Design
- Improve visual design
- Enhance mobile responsiveness
- Add animations or transitions (keep subtle and purposeful)
- Improve color scheme or typography

### Features
- Add photo gallery
- Create event calendar
- Add contact form
- Improve navigation (if adding more pages)
- Add print stylesheet improvements

### Documentation
- Improve README
- Add code comments
- Create tutorials or guides
- Document setup process

### Accessibility
- Improve screen reader support
- Enhance keyboard navigation
- Improve color contrast
- Add ARIA labels where missing

## Review Process

1. Maintainers will review your Pull Request
2. They may suggest changes or improvements
3. Make requested changes and push to the same branch
4. Once approved, your PR will be merged

## Code of Conduct

### Our Standards

- Be respectful and inclusive
- Welcome newcomers
- Focus on what's best for the community
- Show empathy towards others
- Accept constructive criticism gracefully

### Unacceptable Behavior

- Harassment or discriminatory language
- Trolling or insulting comments
- Publishing others' private information
- Any conduct that could reasonably be considered inappropriate

## Questions?

If you have questions about contributing:
- Open an issue with the "question" label
- Reach out during Saturday work days at the orchard
- Contact through community channels

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

Thank you for helping make the Royate Hill Community Orchard website better! 🌳🍎
