# 🩺 Doctors Who Code

A GitHub Pages site exploring AI, clinical workflows, and the future of medicine.

## 🚀 Setup

### Local Development

1. Install Ruby and Jekyll:
   ```bash
   # Install Ruby (if not already installed)
   # Windows: https://rubyinstaller.org/
   
   # Install Bundler
   gem install bundler
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run locally:
   ```bash
   bundle exec jekyll serve
   ```

4. View at: `http://localhost:4000/bot-manager-fallacy/`

### Deploy to GitHub Pages

1. Create a new repository on GitHub named `bot-manager-fallacy`

2. Initialize Git and push:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Bot Manager Fallacy blog"
   git branch -M main
   git remote add origin https://github.com/chukwumaonyeije/bot-manager-fallacy.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Save

4. Update `_config.yml`:
   - Change `url` to your GitHub Pages URL
   - Update social links and contact info

## 📁 Structure

```
bot-manager-fallacy/
├── _config.yml           # Jekyll configuration
├── index.md              # Homepage
├── Gemfile               # Ruby dependencies
├── README.md             # This file
├── blog/
│   ├── index.md          # Blog index
│   └── bot-manager-fallacy.md  # Main article
└── assets/
    └── images/           # Images and banners
```

## ✏️ Adding New Articles

1. Create a new `.md` file in `blog/`
2. Add YAML front matter (see existing article for template)
3. Update `blog/index.md` to link to the new article

## 🎨 Customization

- Edit `_config.yml` to update site title, description, and social links
- Modify `index.md` to customize homepage content
- Add custom CSS in `assets/css/style.scss` (create if needed)

## 📧 Contact

Dr. Chukwuma Onyeije  
Maternal–Fetal Medicine | Founder, Doctors Who Code

---

*"AI won't replace doctors — but it will replace what doctors do."*
