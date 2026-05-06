# AWS Cost Monitoring Workshop - Internship Report

A Hugo-based documentation site for an internship report featuring AWS Cost Monitoring workshops and guides.

---

## Table of Contents

- [AWS Cost Monitoring Workshop - Internship Report](#aws-cost-monitoring-workshop---internship-report)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Workshop Overview](#workshop-overview)
    - [AWS Cost Monitoring](#aws-cost-monitoring)
    - [Local Development](#local-development)
    - [Bilingual Content](#bilingual-content)
    - [Best Practices](#best-practices)
  - [Team \& Contact](#team--contact)
  - [License](#license)

---

## Project Overview

This project is an **Internship Report** documenting practical AWS cloud workshops completed during an internship at Amazon Web Services Vietnam. The site is built with **Hugo** using the `hugo-theme-learn` theme and supports both **English** and **Vietnamese** languages.

## Workshop Overview

### AWS Cost Monitoring

This workshop demonstrates how to monitor, control, and visualize AWS spending using integrated cloud services. Users gain practical experience with cost budgeting, alerts, and dashboard visualization.

**Workshop Goals:**
- Set up **AWS Cost Explorer** as a data source
- Create an **Amazon S3 bucket** for billing data export
- Build a cost dashboard in **Amazon QuickSight**
- Configure user access and permissions
- Review cost trends and spending patterns

**Workshop Modules:**

1. **Overview** – Introduction to cost monitoring architecture and prerequisites
2. **Create S3 bucket** – Set up storage for billing data exports
3. **Amazon QuickSight** – Build cost visualization dashboards
   - Sign up for QuickSight
   - Export billing data
   - Setup QuickSight dashboard
   - Invite users to view dashboards
4. **Clean up** – Remove resources to avoid unnecessary AWS charges

**Target Audience:** AWS learners, cloud engineers, DevOps professionals, and cost optimization specialists.


### Local Development

**Start the development server:**
   ```bash
   hugo server -D
   ```
   - The site opens at `http://localhost:1313`
   - `-D` flag includes draft pages
   - Auto-reloads on file changes


---

### Bilingual Content

- Create both `_index.md` (English) and `_index.vi.md` (Vietnamese)
- Keep translations parallel in structure and organization
- Use the same front matter weights and metadata

### Best Practices

- Use clear, descriptive filenames
- Include images with alt text
- Add step-by-step instructions for tutorials
- Keep content organized with proper headings (H2, H3, etc.)
- Link to related sections within the site
- Test multilingual features before pushing

---

## Team & Contact

**Project Lead:**
- Dang Thanh Phat
  - Email: phatdang.lionel@gmail.com
  - LinkedIn: [Thành Phát](https://www.linkedin.com/in/phat-dang-57a502393)


## License

This project is part of an internship report. Please refer to the repository license file for usage terms.

---

**Last Updated:** 20-09-2024
