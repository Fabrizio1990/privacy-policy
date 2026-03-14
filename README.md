# Privacy Policy Pages

## Published Pages

| App | Link |
|-----|------|
| Private AI Chat | https://fabrizio1990.github.io/privacy-policy/privateAIChat.html |
| Talk to Post | https://fabrizio1990.github.io/privacy-policy/talkTopPost.html |

## How to add a new privacy policy

1. Create a `.md` file with the privacy policy content (e.g. `myApp.md`)
2. Create the corresponding `.html` file (or convert the markdown to HTML)
3. Commit and push to the `main` branch
4. The page will be available at `https://fabrizio1990.github.io/privacy-policy/<filename>.html`

## GitHub Pages setup

This repo uses **GitHub Pages** to host privacy policy pages as static sites.

To enable GitHub Pages on a repository:

1. Go to the repository on GitHub
2. Navigate to **Settings** > **Pages**
3. Under **Source**, select the branch (e.g. `main`) and folder (`/ (root)`)
4. Click **Save**
5. The site will be published at `https://<username>.github.io/<repo-name>/`

Files `.html` are served as-is. Files `.md` are automatically converted to HTML by Jekyll.
