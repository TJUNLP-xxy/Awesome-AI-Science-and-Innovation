# Contributing to Awesome-LLM-ScienceDiscovery

First off, thank you for considering contributing! Your input helps keep this resource valuable and up-to-date for the AI research community. We welcome contributions of all kinds, from adding new papers and tools to fixing typos and improving documentation.

Please take a moment to review this document to understand how you can best contribute.

## How Can I Contribute?

There are several ways you can contribute:

*   **Adding New Papers:** Help us keep the paper lists current and comprehensive.  
*   **Adding Tools, Benchmarks, Events, or Communities:** Share relevant resources.  
*   **Improving Documentation:** Fix typos, clarify instructions, or enhance the README structure.  
*   **Reporting Issues:** Let us know about broken links, outdated information, or suggest improvements.

## Contribution Workflow (Git & GitHub)

We use the standard GitHub Fork & Pull Request workflow.

1.  **Fork the Repository:** Click the "Fork" button at the top right of the [main repository page](https://github.com/llm4science-discovery/Awesome-LLM-ScienceDiscovery) . This creates your own copy.  
2.  **Clone Your Fork:** Clone your forked repository to your local machine:
    ```bash
    git clone https://github.com/YOUR_USERNAME/Awesome-LLM-ScienceDiscovery.git
    cd Awesome-LLM-ScienceDiscovery
    ```
3.  **Create a New Branch:** Create a descriptive branch for your changes:
    ```bash
    git checkout -b feature/add-paper-xyz  # Or fix/typo-in-readme, etc.
    ```
4.  **Make Your Changes:** Add or modify the resources in the `README.md` or other files. Please pay close attention to the formatting guidelines below.  
5.  **Commit Your Changes:** Add and commit your changes with a clear message:
    ```bash
    git add README.md
    git commit -m "Add: Paper 'Title of Paper' to Section X"
    ```
6.  **Push to Your Fork:** Push your changes to your forked repository on GitHub:
    ```bash
    git push origin feature/add-paper-xyz
    ```
7.  **Submit a Pull Request (PR):** Go to your fork on GitHub. You should see a prompt to create a Pull Request from your new branch to the `main` branch of the original repository. Click it, provide a clear title and description for your PR, explaining the changes you made, and submit it.

## Specific Guidelines for Adding New Papers

This is a core part of maintaining the ecosystem list. Please follow these steps carefully:

1.  **Find the Right Section:** Locate the most relevant section in `README.md` based on the paper's primary contribution (e.g., `📚 Knowledge Building -> Knowledge Utilization`, `💡 Idea Generation -> Generation Method`, `✅ Peer Review`).  
2.  **Check for Duplicates:** Ensure the paper isn't already listed.  
3.  **Maintain Order:** If possible, add the paper chronologically (by year, then month if known) within its subsection.  
4.  **Use the Standard Format:** Add the paper as a new bullet point using this Markdown template:

    ```markdown
    *   [Paper Title](Paper_URL) ![](Venue_Badge_URL) [[Code](Code_Badge_URL)](Code_URL) [[Review](Review_URL)] [[Project](Project_Badge_URL)](Project_URL)
    ```

    **Explanation of Components:**

    *   `[Paper Title](Paper_URL)`: The full title of the paper linked to its official source (e.g., arXiv page, DOI link, conference proceedings page).  
    *   `![](Venue_Badge_URL)`: A Shields.io badge indicating the venue and year.  
        *   Create badges using [Shields.io](https://shields.io/). Example format: `https://img.shields.io/badge/VENUE-YEAR-COLOR?style=flat-square` (or the style used in the README).  
        *   **Color Scheme:** Use consistent colors (e.g., `blue` for conferences/workshops, `red` for arXiv, `green` for journals/reports, `brown` for other). Add `?logo=arxiv` for arXiv badges.  
        *   **Example:** `![](https://img.shields.io/badge/ACL-2024-blue?style=flat-square)` or `![](https://img.shields.io/badge/arXiv-2401.12345-red?style=flat-square&logo=arxiv)`  
    *   `[![Code](Code_Badge_URL)](Code_URL)`: *(Optional)* Link to the official code repository (e.g., GitHub, Hugging Face). Use a consistent badge, e.g., `[![Code](https://img.shields.io/badge/Code-grey?logo=github&style=flat-square)](https://github.com/...)`.  
    *   `[[Review](Review_URL)]`: *(Optional)* Link to the OpenReview page or similar peer review discussion. Example: `[[Review](https://openreview.net/forum?id=...)]`.  
    *   `[![Project](Project_Badge_URL)](Project_URL)`: *(Optional)* Link to an official project website. Use a consistent badge, e.g., `[![Project](https://img.shields.io/badge/Project-Web-green?style=flat-square)](https://project-website.com)`.

    **Example Entry:**

    ```markdown
    *   The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery [[Paper]](https://doi.org/10.48550/arXiv.2408.06292)![](https://img.shields.io/badge/arXiv-2024.08-red?style=flat-square&logo=arxiv) [![Code](https://img.shields.io/badge/Code-grey?logo=github&style=flat-square)](https://github.com/SakanaAI/AI-Scientist)
    ```

5.  **Verify Links:** Ensure all URLs provided are correct and lead to the intended resource.

## Adding Other Resources (Tools, Benchmarks, etc.)

*   Find the relevant section (`🔥 Featured Projects`, `🏆 Benchmarks`, `🌐 Community`).  
*   Follow the existing format within that section (e.g., table format for tools, list format for platforms/benchmarks).  
*   Provide a brief, accurate description and a direct link. Use badges where appropriate and consistent with the section.

## Style Guide

*   **Consistency is Key:** Please match the formatting (Markdown syntax, spacing, badges, list styles) of the existing content in the `README.md`.  
*   **Badges:** Use the badge style consistently (e.g., `?style=flat-square`).  
*   **Clarity:** Write clear and concise descriptions.

## Questions?

If you have questions about contributing or are unsure where to add something, feel free to open a [GitHub Issue](https://github.com/llm4science-discovery/Awesome-LLM-ScienceDiscovery/issues) and ask!

Thank you for helping build the AI Researcher Ecosystem!
