# Contributing to SVG Animations

Thank you for your interest in contributing! We welcome contributions from everyone.

## 🎯 How Can I Contribute?

### 1. **Create New Templates**

We're always looking for creative SVG animation templates! Here's how:

**Requirements:**
- Pure SVG with SMIL animations (no external dependencies)
- File size < 50 KB (optimized)
- WCAG 2.1 AA compliant (accessibility-first)
- `prefers-reduced-motion` support mandatory
- No flashing content > 2 Hz
- Smooth 60 FPS animations

**Process:**
1. Fork the repository
2. Create template in appropriate category (`workflow/`, `storytelling/`, or `branding/`)
3. Test on GitHub README (inline markdown)
4. Ensure animations work on mobile
5. Submit Pull Request with preview

**Template Structure:**
```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 WIDTH HEIGHT" role="img" aria-labelledby="title desc">
  <title id="title">Descriptive Title</title>
  <desc id="desc">Detailed description for screen readers</desc>
  
  <style>
    @media (prefers-reduced-motion: reduce) {
      * { animation: none !important; }
    }
  </style>
  
  <!-- Your animation here -->
</svg>
```

### 2. **Improve Existing Templates**

Found a bug or want to enhance a template? Great!

- Open an issue describing the improvement
- Reference the template file
- Explain expected vs. actual behavior
- Submit PR with fix

### 3. **Documentation**

Help make the project more accessible:

- Improve README clarity
- Add usage examples
- Translate documentation
- Create tutorials/guides

### 4. **Report Issues**

Found a problem? Let us know:

- Use the issue template
- Include browser/OS information
- Provide reproduction steps
- Add screenshots if applicable

## 📝 Pull Request Process

1. **Fork & Clone**
   ```bash
   git clone https://github.com/YOUR_USERNAME/SVG-animations.git
   cd SVG-animations
   ```

2. **Create Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Changes**
   - Follow coding standards
   - Test thoroughly
   - Update documentation if needed

4. **Commit**
   ```bash
   git add .
   git commit -m "feat: Add awesome new template"
   ```

   **Commit Message Format:**
   - `feat:` New feature
   - `fix:` Bug fix
   - `docs:` Documentation only
   - `style:` Formatting changes
   - `refactor:` Code restructuring
   - `test:` Adding tests
   - `chore:` Maintenance tasks

5. **Push & PR**
   ```bash
   git push origin feature/your-feature-name
   ```
   Then open a Pull Request on GitHub.

## ✅ Checklist Before Submitting

- [ ] Code follows project style guidelines
- [ ] Accessibility tested (screen reader, keyboard navigation)
- [ ] Performance verified (< 50 KB, smooth 60 FPS)
- [ ] `prefers-reduced-motion` implemented
- [ ] No flashing content > 2 Hz
- [ ] Tested on GitHub README
- [ ] Mobile responsive
- [ ] Documentation updated
- [ ] Commit messages follow convention

## 🚫 What We Don't Accept

- Templates with external dependencies (JS libraries, external fonts)
- Animations violating WCAG guidelines
- Copyrighted content without permission
- Malicious code or security vulnerabilities
- Templates > 100 KB file size

## 💬 Questions?

- **Email:** nexusstudio100@gmail.com
- **GitHub Discussions:** Ask questions, share ideas
- **Issues:** Bug reports, feature requests

## 🙏 Recognition

All contributors will be:
- Listed in README contributors section
- Credited in template comments
- Mentioned in release notes

Thank you for making SVG Animations better! 🎉