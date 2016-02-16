---
title: Why didn't WordPress take off with tech docs?
categories:
- wordpress
keywords: 
summary: "Despite the dominance of WordPress as a web publishing platform for companies, bloggers, organizations, and other online publishers who use it for nearly 75 million websites collectively, WordPress has rarely been used by technical writers as a platform for publishing technical documentation. Some of the reasons WordPress is avoided is due to its heavy LAMP stack architecture, its lack of component content re-use, and its inability to publish multiple outputs such as PDF."
thumb: 14wpstatsthumb.png
---

Despite the popularity of WordPress as detailed in [14 Surprising Statistics About WordPress Usage](https://managewp.com/14-surprising-statistics-about-wordpress-usage), this web CMS still hasn't emerged as a competing help authoring tool in the tech comm industry. 

<a href="14 Surprising Statistics About WordPress Usage](https://managewp.com/14-surprising-statistics-about-wordpress-usage"><img src="{{ "/images/14wpstats.png" | prepend: site.baseurl }}" alt="Surprising statistics about WordPress" /></a>

Here are some of the staggering statistics about WordPress usage mentioned in the article:

* 1. 48% of Technorati’s Top 100 Blogs Are Managed With WordPress
* 2. 74.6 Million Sites Depend on WordPress
* 3. WordPress-Related Keywords Score 37 Million Searches Per Month
* 4. 40 Translations of WordPress
* 5. 22% of New U.S. Registered Domains Run on WordPress
* 6. WordPress.com Gets More Unique Visitors Than Amazon (Us)
* 7. WordPress.com Employs Only 229 People
* 8. 6 New WordPress.com Posts Every Second
* 9. WordPress Developers Charge $50/hr
* 10. 29,000 WordPress Plugins and Growing Daily
* 11. 98 Versions of WordPress to Date
* 12. 46 Million Downloads of WordPress.org
* 13. WordPress Is Most Popular With Business Websites
* 14. Akismet Is the Most Popular Plugin

With a portfolio of stats like that, you'd think that WordPress would be a common CMS used in tech comm departments as well. But as far as I can tell, WordPress is rarely used by technical writers. Why?

Here are a few reasons:

* WordPress is a lightweight web CMS, not a CCMS (component content management system). As such, it isn't optimized for chunking different components and reusing those chunks in different outputs. The latter is much more common in tech doc departments.
* WordPress isn't meant for publishing multiple outputs of content, such as three different versions of documentation for several different audiences, or for publishing PDF, HTML, and mobile outputs. With WordPress, you have just one output: HTML.
* WordPress requires a heavy infrastructure that consists of Linux, Apache, MySQL, and PHP (LAMP). Setting up this infrastructure and fine-tuning it for WordPress can require more application-system-engineering knowledge than most technical writers have or want to get into. Additionally, if you have 10 different doc sites, you would need 10 different instances of the infrastructure. Alternatively, you could run WordPress Multisite, but then you have more robust platform management tasks and challenges.
* WordPress usually doesn't meet enterprise security requirements. WordPress sites get routinely hacked and are noted by enterprise security groups for their poor security. As such, if using a web CMS, much of the time a more robust platform like Drupal will be selected.
* WordPress isn't ideal for managing documentation content. WordPress is really intended for one-off articles published as blog posts, articles, or other web content that you publish once and then rarely update. With tech comm docs, however, you're constantly updating existing content with each new release, re-working and editing and cross-referencing the content to align with the changing shape of the product. When you have to find and update all of the pages in WordPress like this, it can be a pain.

Despite these shortcomings, I still think WordPress wouldn't be a poor choice for publishing tech docs. The many themes, plugins, and web hosts that specialize in WordPress make this a more accessible and functional platform than other web-based CMSs. But so far this hasn't been the case. What do you think? Why is WordPress such a common platform for web publishing but uncommon for tech docs?