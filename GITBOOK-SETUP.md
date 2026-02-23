# GitBook Setup Guide

This repository is configured to work with GitBook for creating beautiful, interactive documentation.

## What is GitBook?

GitBook is a modern documentation platform that turns your markdown files into a professional, searchable documentation website with:
- Clean, responsive design
- Full-text search
- Table of contents navigation
- Easy deployment options

## Repository Structure

The repository is organized for GitBook with these key files:

```
attacks/
├── .gitbook.yaml          # GitBook configuration
├── README.md              # Introduction/Home page
├── SUMMARY.md             # Table of contents structure
├── GLOSSARY.md            # Security terms glossary
├── QUICK-REFERENCE.md     # Quick reference guide
└── Attack-and-Remediation.md  # Main content with 70 attacks
```

## How to Use This GitBook

### Option 1: View on GitBook.com (Recommended)

1. **Import to GitBook**:
   - Go to [GitBook.com](https://www.gitbook.com)
   - Sign up or log in
   - Click "New Space"
   - Select "Import from GitHub"
   - Authorize GitBook to access your repository
   - Select the `ROGUEDSGNR/attacks` repository

2. **GitBook will automatically**:
   - Detect the `.gitbook.yaml` configuration
   - Build your documentation site
   - Create a beautiful, searchable interface
   - Provide a public URL for sharing

3. **Features Available**:
   - Full-text search across all attacks
   - Organized navigation by category
   - Mobile-responsive design
   - Version control integration
   - Automatic updates on push

### Option 2: Use GitBook CLI Locally

1. **Install GitBook CLI**:
   ```bash
   npm install -g gitbook-cli
   gitbook --version
   ```

2. **Clone and Serve**:
   ```bash
   git clone https://github.com/ROGUEDSGNR/attacks.git
   cd attacks
   gitbook install  # Install plugins
   gitbook serve    # Serve locally at http://localhost:4000
   ```

3. **Build Static Site**:
   ```bash
   gitbook build
   # Output will be in _book/ directory
   ```

### Option 3: View as Markdown on GitHub

The documentation is also fully readable on GitHub:
- Start with [README.md](README.md)
- Navigate using [SUMMARY.md](SUMMARY.md) links
- All internal links work within GitHub's interface

## GitBook Configuration

The `.gitbook.yaml` file configures:

```yaml
root: ./                    # Documentation root directory
structure:
  readme: README.md         # Home page
  summary: SUMMARY.md       # Table of contents
```

## Navigation Structure

The `SUMMARY.md` file defines the sidebar navigation with:

1. **Introduction** - Overview and getting started
2. **Quick Reference** - Fast lookup of common attacks and categories
3. **Attack Categories** - Detailed category descriptions
4. **70 Specific Attacks** - Organized by type:
   - Web Application Attacks
   - Code Execution & Injection
   - Access Control & Authentication
   - Cryptographic Attacks
   - Network & Infrastructure
   - Cloud Security
   - Container & Orchestration
   - DevOps & CI/CD
   - And more...
5. **Glossary** - Security terms and acronyms

## Features

### 🔍 Search
GitBook provides full-text search across all documentation, making it easy to find specific attacks or techniques.

### 📱 Mobile-Friendly
The documentation is fully responsive and works great on mobile devices.

### 🔗 Anchor Links
All headings in the documentation have anchor links for easy sharing of specific sections.

### 📊 Categories
Attacks are organized into logical categories for easier navigation and understanding.

### 💻 Code Examples
Each attack includes:
- Vulnerable code examples
- Secure code implementations
- Remediation strategies

## Deployment Options

### Deploy to GitBook.com
- Automatic deployment on every push
- Built-in hosting and CDN
- Custom domain support
- Analytics available

### Deploy to GitHub Pages
```bash
gitbook build
# Deploy _book/ directory to GitHub Pages
```

### Deploy to Netlify/Vercel
```bash
# Build command
gitbook build

# Publish directory
_book
```

### Deploy to Your Own Server
```bash
gitbook build
# Copy _book/ directory to your web server
```

## Customization

### Adding New Content

1. **Add new attack to Attack-and-Remediation.md**
2. **Update SUMMARY.md** with a link to the new section
3. **Commit and push** - GitBook will auto-update

### Modifying Structure

Edit `.gitbook.yaml` to:
- Change root directory
- Add custom redirects
- Configure additional structure

### Adding Plugins

Create a `book.json` file:
```json
{
  "plugins": ["search", "highlight", "sharing"],
  "pluginsConfig": {
    "sharing": {
      "github": true,
      "twitter": true
    }
  }
}
```

## Maintaining the Documentation

### Best Practices

1. **Keep SUMMARY.md in sync** with Attack-and-Remediation.md structure
2. **Use descriptive anchor links** for easy navigation
3. **Update the Quick Reference** when adding new attack categories
4. **Add new terms to GLOSSARY.md** as needed
5. **Test links** before committing changes

### Link Format

Internal links use this format:
```markdown
[Link Text](filename.md#anchor-id)
```

Example:
```markdown
[SQL Injection](Attack-and-Remediation.md#1-sql-injection-sqli)
```

## Support and Resources

- **GitBook Documentation**: https://docs.gitbook.com
- **GitBook Community**: https://community.gitbook.com
- **Markdown Guide**: https://www.markdownguide.org

## Benefits of Using GitBook

✅ **Professional Appearance** - Clean, modern documentation interface  
✅ **Easy Navigation** - Sidebar navigation with nested sections  
✅ **Search Functionality** - Find any attack or term instantly  
✅ **Version Control** - Integrated with Git for change tracking  
✅ **Collaboration** - Multiple contributors can easily add content  
✅ **Mobile Support** - Works perfectly on all devices  
✅ **SEO Friendly** - Good for discoverability  
✅ **No Build Required** - GitBook.com handles everything  

## Getting Started

The quickest way to get started is to import this repository to GitBook.com:

1. Visit https://www.gitbook.com
2. Sign up with GitHub
3. Import the `ROGUEDSGNR/attacks` repository
4. Your documentation site will be live in minutes!

---

**Questions?** Open an issue in the GitHub repository or refer to the [GitBook documentation](https://docs.gitbook.com).
