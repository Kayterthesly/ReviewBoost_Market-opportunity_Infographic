# ReviewBoost Market Opportunity Infographic

This repository hosts a single-page application (SPA) infographic visualizing the market potential, user demand, and strategic opportunities for **ReviewBoost**, a specialized platform for verified, admin-approved freelance reviews.

The infographic is built for strategic product and investor decision-making, synthesizing data on market sizing, user pain points, competitive landscape, and growth recommendations.

## 🛠️ Technology Stack

* **Structure & Layout:** Single HTML file, utilizing **Tailwind CSS (CDN)** for a responsive, modern layout.
* **Data Visualization:** **Chart.js (CDN)** for all standard charts (Bar, Line, Radar, Doughnut).
* **Design:** Professional, high-contrast aesthetic using a "Brilliant Blues" palette, adhering to Material Design principles.
* **Deployment:** Designed for deployment via **GitHub Pages**.

## 🚀 Deployment Instructions (via GitHub Pages)

To view or host this infographic, follow these simple steps:

1.  **Rename File:** Ensure your main HTML file is named **`index.html`** in the root of the repository.
2.  **Add Configuration:** Create an empty file named **`.nojekyll`** in the root directory. This tells GitHub Pages to treat the content as a simple static site, which is crucial for pure HTML/JS projects.
3.  **Commit & Push:** Commit both `index.html` and `.nojekyll` to your GitHub repository.
4.  **Activate Pages:**
    * Navigate to your repository on GitHub.
    * Go to **Settings** > **Pages** (under the Code and automation section).
    * Under "Build and deployment," ensure **Source** is set to **Deploy from a branch**.
    * Set the **Branch** to **`main`** (or your primary branch) and set the folder to **`/(root)`**.
    * Click **Save**.

The site will now build and be accessible at `https://[your-username].github.io/[your-repo-name]/` within a few minutes.

## 🔗 Open Graph Configuration

The `index.html` includes **Open Graph (OG) meta tags** to ensure that rich, professional thumbnails and descriptions appear when the infographic is shared on social media platforms (LinkedIn, Twitter, Facebook).

**NOTE:** Remember to update the placeholder URL in the `<meta property="og:image">` tag with the actual public URL of your infographic's thumbnail image once it's hosted.