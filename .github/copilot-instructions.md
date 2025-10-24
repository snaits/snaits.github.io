# GitHub Copilot Instructions for snaits.github.io

## Project Overview
This is a GitHub Pages repository for hosting a personal website at snaits.github.io. The site is deployed automatically through GitHub Pages.

## Project Type
- **Type**: GitHub Pages static site
- **Deployment**: Automatically deployed from the main/master branch
- **Purpose**: Personal website hosting

## Coding Standards and Conventions

### General Guidelines
- Keep the repository structure simple and maintainable
- Follow standard GitHub Pages conventions
- Ensure all changes are compatible with GitHub Pages deployment
- Test locally when possible before committing

### File Organization
- Keep the root directory clean and organized
- Use appropriate subdirectories for assets (images, CSS, JavaScript)
- Follow Jekyll conventions if Jekyll is being used
- Maintain consistent naming conventions (lowercase, hyphen-separated for files)

## Documentation
- Update README.md when making significant structural changes
- Document any special configuration or build requirements
- Keep comments in code clear and concise

## Testing and Deployment

### Before Committing
- Verify that HTML is valid and well-formed
- Check that links work correctly
- Ensure responsive design works on different screen sizes
- Test locally with Jekyll if applicable (`bundle exec jekyll serve`)

### GitHub Pages Specifics
- Remember that GitHub Pages uses Jekyll by default
- Certain Jekyll plugins are supported; check GitHub Pages documentation
- The `_site/` directory is auto-generated and should not be committed
- `Gemfile.lock` should not be committed (already in .gitignore)

## What to Avoid

### Protected Files
- Do NOT modify `.gitignore` unless absolutely necessary
- Do NOT commit build artifacts or dependencies
- Avoid making changes to LICENSE unless explicitly requested

### Security
- Never commit sensitive information (API keys, passwords, tokens)
- Do not expose personal information unless intended for public display

## Pull Request Guidelines
- Keep PRs focused and small
- Include clear descriptions of changes
- Test changes locally before creating PR
- Update documentation if structural changes are made

## Helpful Commands
```bash
# Install Jekyll (if using)
bundle install

# Run Jekyll locally
bundle exec jekyll serve

# Build the site
bundle exec jekyll build
```

## Additional Notes
- This repository uses standard GitHub Pages deployment
- Changes to the main/master branch are automatically deployed
- Follow Jekyll documentation for advanced features: https://jekyllrb.com/docs/
