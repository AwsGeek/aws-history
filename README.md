# A History of Amazon Web Services (AWS)

A history of AWS service announcements (either pre-announced or in some form of limited preview, like beta) and releases (generally available in one or more AWS regions).

This information was obtained from public web pages, mainly <a href="https://aws.amazon.com/new/">What's New with AWS</a> and <a href="https://aws.amazon.com/blogs/aws/author/jbarr/">Jeff Barr's blog posts</a>.

You can view a live version of this site <a href="https://www.awsgeek.com/pages/AWS-History/">here</a>.

#### Contributing:
If you'd like to add a new or missing service, 2 changes need to be made:
1. Add the service to the services.json file. In addition to name and category properties, each service must have at least one of 'announced' or 'released' dates and associated links, and an icon. 'announced' means the service is/was either not yet available, or in limited preview or beta. 'released' means the service is available to everyone in one or more regions. Sometimes a single blog post indicates a service is both being 'announced' and 'released' at the same time. In that case, just indicate 'released' (but duplicating the info in 'announced' doesn't break anything).

2. Upload the icon for the service to the icons folder. You can generally find these <a href="https://aws.amazon.com/architecture/icons/">here</a> (if it's an existing service that I forgot to add) in the SVG assets zip file, in the ```SVG Dark/<category>``` folder. For new services that don't yet have an icon, you can use the category icon instead. Add the name of the icon file to services.json. 

3. Please test your modifications in a browser before submitting a PR. Note that some browsers, e.g. Google Chrome, might not correctly render `index.html` when not accessed through http(s). This is because of the use of [CORS](https://de.wikipedia.org/wiki/Cross-Origin-Request). For local testing you might want to bypass these security controls by passing `--disable-web-security` as a command line flag to the Chrome executable.
