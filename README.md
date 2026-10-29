# Land Rover Defender — GitHub Pages

**Elevate Labs DevOps Internship · Task 5: Host a Static Website with GitHub Pages**

This repository contains a responsive, single-page Land Rover Defender showcase. The task demonstrates how to publish static HTML and CSS using GitHub Pages, a free static website hosting service provided by GitHub.

## Task objective

Create a simple HTML website, push it to a GitHub repository, and publish it with GitHub Pages from the `main` branch and repository root. The required deliverables are the GitHub repository and the live website link.

## Website features

- Sticky navigation to Home, Models, Features, and Contact
- Defender 130 overview and specification cards for the Defender 90, 110, and V8
- Responsive layouts for desktop, tablet, and mobile
- CSS animations with reduced-motion support

## Project files

| File | Description |
| --- | --- |
| `index.html` | Website content and page structure |
| `style.css` | Styling, responsive layouts, and animations |
| `home defender.jpg` | Defender 130 hero image |
| `90 def.jpeg` | Defender 90 image |
| `110 def.jpeg` | Defender 110 image |
| `v8 def.jpeg` | Defender V8 image |

## Run locally

No build tools or paid software are required. Open `index.html` in a browser, or start a local server from the project folder:

```bash
python -m http.server 8000
```

Visit <http://localhost:8000>.

## Publish with GitHub Pages

1. Push the project files to the `main` branch of a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under the build and deployment settings, select **Deploy from a branch**, choose `main` and the `/ (root)` folder, then save.
4. Wait for the deployment to finish. GitHub displays the published URL in the Pages settings.
5. Open that URL and use it as the live website link in the task submission.

### Deliverables

- **GitHub repository:** [Add your repository URL]
- **Live website:** [Add the GitHub Pages URL after deployment]

Replace these placeholders with the actual links before submitting.

## Interview questions

1. **What is GitHub Pages?**  
   A GitHub service that publishes static websites from a repository, such as a project site from a branch or a configured publishing source.

2. **Can you host dynamic apps here?**  
   GitHub Pages serves static files. It does not run server-side application code or databases. A static frontend can still call external APIs.

3. **What are the limits of GitHub Pages?**  
   It is intended for static sites and has publishing, build, and usage limits. It is not a general-purpose application server and does not provide server-side processing. Check GitHub's current Pages documentation for exact limits.

4. **How do you update the website?**  
   Edit the site files and push the changes to the configured publishing source. GitHub Pages rebuilds and republishes the site.

5. **What happens when you delete the repository?**  
   The repository and its Pages site are removed, so the published website is no longer available from that repository.

6. **What is the default file that loads?**  
   `index.html` is the standard entry page for this site.

7. **Can you use a custom domain?**  
   Yes. A custom domain can be configured in the repository's Pages settings, with the required DNS records set at the domain provider.

## Customize

- Edit website text and specifications in `index.html`.
- Change colors, layout, and responsive styling in `style.css`.
- Replace the images while keeping their filenames, or update their paths in `index.html`.

> **Content note:** Vehicle specifications, prices, and contact details are sample content for this demonstration. Verify them before relying on or publishing them.
