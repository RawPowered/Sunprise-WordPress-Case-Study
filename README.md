<p align="center"><img src="assets/sunprise-case-study-banner.svg" alt="Sunprise; business migration and WordPress case study" width="100%"></p>

# Sunprise · migration, web & communications

I moved Sunprise’s business files, email and web presence onto a new platform stack, built its WordPress site, and configured the team’s phone system.

**2+ TB of files and data · approximately two weeks · no data, file or email loss · spreadsheets preserved**

<p align="center"><a href="https://rawpowered.github.io/Sunprise-WordPress-Case-Study/">Explore the case study</a> · <a href="#delivery">Delivery</a> · <a href="#measured-activity">Results</a> · <a href="docs/implementation.md">Technical detail</a></p>

---

## Delivery

<p align="center"><img src="assets/glass-outcomes.webp" alt="Glass symbols for migration, email continuity, search discovery and audience reach" width="100%"></p>

- ✅ **Migrated 2+ TB of business files and data**, including images, contracts, PDFs and spreadsheets, alongside a substantial email transfer beyond OneDrive files.
- ✅ **Preserved data, files, email and spreadsheets** throughout the approximately two-week transition.
- ✅ **Moved the platform stack:** Microsoft 365 → Google Workspace; GoDaddy → Namecheap; Webflow → WordPress.
- ✅ **Resolved the final DNS cutover** through [DNS-Sentinel](https://github.com/RawPowered/DNS-Sentinel) diagnostics, provider support and phone coordination. Data transfer accounted for much of the schedule; GoDaddy DNS response time affected the final stretch.
- ✅ **Configured Zoom Phone** for multiple people, including call routing, menu logic and recordings.
- ✅ **Delivered a searchable contractor website** with service and location pages, project galleries, editorial content and analytics.

---

## The WordPress build

<table>
<tr>
<td width="33%" align="center" valign="top">
<h3>Pages</h3>
<img src="assets/sections/pages.svg" alt="WordPress / Page System; Pages" width="100%">
<img src="assets/icons/pages-glass.webp" alt="Translucent glass stack of website pages" width="240">
<p><strong>50 published records</strong><br>Service, location and company pages</p>
</td>
<td width="33%" align="center" valign="top">
<h3>Blog Posts</h3>
<img src="assets/sections/blog.svg" alt="WordPress / Editorial; Blog Posts" width="100%">
<img src="assets/icons/blog-glass.webp" alt="Translucent glass editorial article" width="240">
<p><strong>13 published posts</strong><br>Roofing, remodeling and home systems</p>
</td>
<td width="33%" align="center" valign="top">
<h3>Portfolio</h3>
<img src="assets/sections/portfolio.svg" alt="WordPress / Projects; Portfolio" width="100%">
<img src="assets/icons/portfolio-glass.webp" alt="Translucent glass project gallery" width="240">
<p><strong>30 published records</strong><br>Projects and detailed work narratives</p>
</td>
</tr>
</table>

<sub>Archive inventory; page and portfolio totals include demo and operational records.</sub>

<p align="center"><a href="assets/case-study/home-fold.png"><img src="assets/case-study/home-fold.png" alt="Restored Sunprise homepage with centered navigation and remodeling hero" width="100%"></a></p>

- ✅ Centered logo navigation and dedicated service and Florida location pages.
- ✅ Filterable project portfolio with individual project narratives.
- ✅ Image-led blog with practical roofing, remodeling and generator articles.
- ✅ Yoast metadata, canonical links, crawler guidance and a content index for LLMs.

<details>
<summary><strong>Explore the project gallery and editorial layouts</strong></summary>

<p><a href="assets/case-study/projects-fold.png"><img src="assets/case-study/projects-fold.png" alt="Projects archive" width="49%"></a> <a href="assets/case-study/blog-fold.png"><img src="assets/case-study/blog-fold.png" alt="Blog archive" width="49%"></a></p>
<p><a href="assets/case-study/project-detail.png"><img src="assets/case-study/project-detail.png" alt="Project detail page" width="49%"></a> <a href="assets/case-study/article-detail.png"><img src="assets/case-study/article-detail.png" alt="Article detail page" width="49%"></a></p>

</details>

---

## Measured activity

**WordPress reporting period: July 19-October 5, 2026**

| Google Analytics | Result | Facebook | Result |
| --- | ---: | --- | ---: |
| Active users | **639** | Content views | **20,272** |
| Sessions | **755** | Views attributed to link content | **72.2%** |
| Organic-search sessions | **195** | | |
| Engaged sessions | **296** | | |
| Page and screen views | **1,128** | | |

I also received quote inquiries by phone from businesses and residents who said they found Sunprise through organic Google searches, during a period that included paid promotions.

<details>
<summary><strong>Inspect the analytics screenshots and measurement context</strong></summary>

<p><a href="assets/analytics/google-analytics-detail.jpg"><img src="assets/analytics/google-analytics-detail.jpg" alt="Google Analytics acquisition report for July 19-October 5, 2026" width="49%"></a> <a href="assets/analytics/facebook-views-detail.jpg"><img src="assets/analytics/facebook-views-detail.jpg" alt="Facebook content views for the same period" width="49%"></a></p>

These figures cover the WordPress site. The earlier Webflow site had no comparable Google Analytics baseline. The new website and Facebook activity were requested within the last year; the longevity of earlier web-presence work cannot be established from the records. Facebook views are separate from website visits; Meta’s comparison percentage is not a before-and-after website comparison. Organic social includes multiple platforms.

</details>

---

## SEO implementation

<p align="center"><img src="assets/seo-audit.svg" alt="Lighthouse staging SEO scores: 92 mobile and 92 desktop, October 28, 2026" width="100%"></p>

- ✅ Service and location landing pages supported local discovery.
- ✅ The archive contains **37 Yoast title entries, 37 descriptions and 36 focus-keyword entries**: a restored article rendered a description and canonical URL.
- ✅ `robots.txt` supplied crawler rules and a sitemap reference; Yoast generated an `llms.txt` index.

**Audit scope:** The 92/100 scores are automated checks of a partially restored staging homepage. Page speed could not be reliably retested because hosting configurations differed. The `llms.txt` index needs editorial review and is separate from Lighthouse scoring. [Read the implementation notes](docs/implementation.md).

---

## Stack & related work

<p align="center"><img src="assets/icons/wordpress-glass.webp" width="64" alt="WordPress"> <img src="assets/icons/php-glass.webp" width="64" alt="PHP"> <img src="assets/icons/html5-glass.webp" width="64" alt="HTML5"> <img src="assets/icons/css3-glass.webp" width="64" alt="CSS3"> <img src="assets/icons/javascript-glass.webp" width="64" alt="JavaScript"></p>

[TheGem](https://themeforest.net/item/thegem-creative-multipurpose-highperformance-wordpress-theme/16061685) · [Elementor](https://wordpress.org/plugins/elementor/) / [Pro](https://elementor.com/pro/) · [Slider Revolution](https://www.sliderrevolution.com/) · [LayerSlider](https://layerslider.com/) · [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) · [Site Kit](https://sitekit.withgoogle.com/) · [Contact Form 7](https://wordpress.org/plugins/contact-form-7/) · [WP Mail SMTP](https://wordpress.org/plugins/wp-mail-smtp/) · [Complianz](https://wordpress.org/plugins/complianz-gdpr/) · [Wordfence](https://wordpress.org/plugins/wordfence/)

[DNS-Sentinel](https://github.com/RawPowered/DNS-Sentinel) supported migration diagnosis. The later [Sunlectric theme](https://github.com/RawPowered/Sunlectric-Solar-WordPress-Showcase) drew inspiration from Sunprise’s centered navigation and solar presentation.

**Built by [Joseph Edwards](https://github.com/RawPowered).** This repository contains case-study materials and restored-site screenshots. Business files, personal data, databases and installable WordPress packages remain private. Third-party assets retain their owners’ terms; this showcase grants no reuse license.
