# Contributing to VGDC Website

Thank you for your interest in contributing to the Stetson University Video Game Development Club website! We welcome contributions from all club members and the broader community.

## 🎯 Ways to Contribute

### Content Contributions
- **Add Projects**: Showcase your game development projects
- **Update Resources**: Add new tools, tutorials, or learning materials
- **Write Documentation**: Help improve guides and documentation
- **Share Events**: Add information about upcoming events or workshops

### Development Contributions
- **Bug Fixes**: Help identify and fix issues
- **Feature Development**: Add new functionality to enhance the site
- **Performance Improvements**: Optimize loading times and user experience
- **Accessibility**: Improve accessibility features

### Design Contributions
- **UI/UX Improvements**: Enhance the visual design and user experience
- **Create Assets**: Design icons, graphics, or animations
- **Mobile Optimization**: Improve the mobile experience

## 🚀 Getting Started

### Prerequisites
- Basic knowledge of HTML, CSS, and JavaScript
- Git and GitHub account
- Text editor or IDE (VS Code recommended)

### Setup Process
1. **Fork the Repository**
   ```bash
   # Click the "Fork" button on GitHub, then clone your fork
   git clone https://github.com/YOUR_USERNAME/vgdc-su.github.io.git
   cd vgdc-su.github.io
   ```

2. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/bug-description
   ```

3. **Make Your Changes**
   - Edit the relevant files
   - Test your changes locally by opening `index.html` in a browser
   - Ensure your changes are responsive and work on different screen sizes

4. **Test Your Changes**
   - Open `index.html` in multiple browsers
   - Test on mobile devices or use browser dev tools
   - Validate HTML and CSS if possible
   - Check for JavaScript errors in the console

## 📝 Coding Standards

### HTML
- Use semantic HTML5 elements
- Include proper `alt` attributes for images
- Ensure proper heading hierarchy (h1, h2, h3, etc.)
- Validate markup when possible

### CSS
- Follow existing naming conventions
- Use CSS custom properties (variables) for consistency
- Maintain mobile-first responsive design approach
- Group related styles together
- Add comments for complex CSS

### JavaScript
- Use modern ES6+ syntax
- Write clean, readable code with meaningful variable names
- Add comments for complex logic
- Follow existing code patterns
- Ensure accessibility considerations

### General
- Use 2 spaces for indentation
- Keep lines under 100 characters when reasonable
- Remove trailing whitespace
- End files with a newline

## 📋 Pull Request Process

1. **Before Submitting**
   - Ensure your code follows the coding standards
   - Test your changes thoroughly
   - Write clear commit messages
   - Update documentation if needed

2. **Commit Messages**
   Use clear, descriptive commit messages:
   ```bash
   # Good examples:
   git commit -m "Add Unity tutorial to resources section"
   git commit -m "Fix mobile navigation menu bug"
   git commit -m "Update meeting schedule for Fall 2025"
   
   # Avoid:
   git commit -m "fix stuff"
   git commit -m "updates"
   ```

3. **Submit Pull Request**
   - Push your changes to your fork
   - Create a pull request from your branch to the main repository
   - Fill out the pull request template
   - Request review from maintainers

4. **Pull Request Template**
   ```markdown
   ## Description
   Brief description of what this PR does
   
   ## Type of Change
   - [ ] Bug fix
   - [ ] New feature
   - [ ] Content update
   - [ ] Documentation update
   - [ ] Performance improvement
   
   ## Testing
   - [ ] Tested on Chrome
   - [ ] Tested on Firefox
   - [ ] Tested on Safari
   - [ ] Tested on mobile
   - [ ] No JavaScript errors
   
   ## Screenshots
   (If applicable, add screenshots of your changes)
   ```

## 🎨 Design Guidelines

### Color Palette
- Primary: `#6366f1` (Indigo)
- Secondary: `#ec4899` (Pink)
- Accent: `#06b6d4` (Cyan)
- Success: `#10b981` (Emerald)
- Warning: `#f59e0b` (Amber)
- Background: `#0f0f23` (Dark)

### Typography
- Headings: Orbitron (futuristic, tech feel)
- Body text: Inter (clean, readable)
- Use appropriate font weights and sizes

### Spacing
- Use consistent spacing from CSS custom properties
- Follow existing patterns for margins and padding

## 📁 Project Structure

```
vgdc-su.github.io/
├── index.html          # Main HTML file
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── _config.yml        # Site configuration
├── README.md          # Main documentation
├── CONTRIBUTING.md    # This file
└── assets/            # Future: images and other assets
```

## 🔧 Adding New Content

### Adding a New Project
1. Find the projects section in `index.html`
2. Duplicate an existing project card
3. Update the content:
   ```html
   <div class="project-card">
     <div class="project-image">
       <!-- Add screenshot or use placeholder -->
     </div>
     <div class="project-content">
       <h3>Your Project Name</h3>
       <p>Project description...</p>
       <div class="project-tags">
         <span class="tag">Unity</span>
         <span class="tag">2D</span>
       </div>
       <a href="#" class="project-link">
         View Project <i class="fas fa-arrow-right"></i>
       </a>
     </div>
   </div>
   ```

### Adding a New Resource
1. Find the appropriate category in the resources section
2. Add a new resource item:
   ```html
   <div class="resource-item">
     <div class="resource-header">
       <h4>Tool Name</h4>
       <span class="resource-badge free">Free</span>
     </div>
     <p>Description of the tool...</p>
     <a href="#" target="_blank" class="resource-link">
       Visit Website <i class="fas fa-external-link-alt"></i>
     </a>
   </div>
   ```

### Updating Meeting Information
1. Find the meetings section in `index.html`
2. Update the schedule, location, or agenda items
3. Ensure the information is current and accurate

## 🚨 Common Issues

### Problem: Changes not showing up
- **Solution**: Hard refresh your browser (Ctrl+F5 or Cmd+Shift+R)
- **Cause**: Browser caching

### Problem: Mobile layout broken
- **Solution**: Test using browser dev tools mobile simulation
- **Cause**: Usually CSS issues with responsive design

### Problem: JavaScript errors
- **Solution**: Check browser console for error messages
- **Cause**: Syntax errors or missing dependencies

## 🎉 Recognition

Contributors will be recognized in:
- GitHub contributors list
- Future "Contributors" section on the website
- Club meetings and events

## 📞 Getting Help

If you need help with contributing:

1. **GitHub Issues**: Create an issue for bugs or feature requests
2. **Discord**: Join our club Discord at https://discord.gg/7ZB5yRZnz7 for real-time help
3. **Email**: Contact us at vgdc@stetson.edu
4. **Meetings**: Attend our bi-weekly meetings for in-person help
5. **Engage**: Join officially at https://stetson.campuslabs.com/engage/actioncenter/organization/videogamedev

## 📜 Code of Conduct

By contributing, you agree to:
- Be respectful and inclusive
- Provide constructive feedback
- Help others learn and grow
- Follow Stetson University guidelines
- Create a welcoming environment for all

## 🎮 Thank You!

Your contributions help make the VGDC community stronger and more vibrant. Whether you're fixing a typo, adding a new feature, or sharing your project, every contribution matters!

---

**Happy coding, and see you at the next meeting!** 🚀
