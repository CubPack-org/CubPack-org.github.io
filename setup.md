---
title: Setup
layout: page
hero_image: /assets/img/setup-hero.jpg
hero_darken: true
callouts: hosting-options
hero_height: is-small
---

## Google Sites

Google Sites supports custom domains / subdomains over https. To set up a custom subdomain from cubscouts.org with Google Sites, do the following:

- Enter the subdomain you wish to reserve in the form below (make sure to read [What makes a good subdomain?](/about/#what-is-a-good-subdomain)). Please verify that there is not already a pack using this subdomain:
    {% include google-verify-form.html %}

- Select Namecheap from the list of domain providers and copy the google-site-verification code

    ![Verifying Domain Ownership](/assets/img/google-sites-verification.png)

- Submit the [subdomain request](/request-subdomain), including the Google Sites Verification code

- Once you recieve an email that the subdomain is setup, return to the Google Verification Screen

-  Select Settings (the gear icon) then _Custom domains_ then _Start setup_:

    ![Start Google Sites Setup](/assets/img/google-sites-settings.png)
- Select _Use a domain from a third party_
- Replace `www` with the subdomain you want and `yourdomain.com` with `cubpack.org` then click _Next_ to complete the process.

    ![Start Google Sites Custom Domain](/assets/img/google-sites-third-party.png)


## Github Pages

Github Pages supports custom domains / subdomains over https. To set up a custom subdomain from cubscouts.org with Github Pages, do the following:

 - Submit the [subdomain request](/request-subdomain), including the Github Pages URL (e.g. <user/organization>.githug.io) (make sure to read [What makes a good subdomain?](/about/#what-is-a-good-subdomain))
 - Once you recieve an email that the subdomain is setup, complete the [configuration on Github Sites](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-a-subdomain)