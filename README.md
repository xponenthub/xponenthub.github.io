# XponentHub Home Page
Official website for Xponenthub.

Contains:

- Menu: Home | About Us | Prodcuts | Contact Us
  - Create a enquiry submit for for Contact Us
- Footer - Social account: Facebook, Gmail, Github.
  - NO twitter at this moment.
- Disclaimer put together during deliver product but not in website.

## How To Setup
   $jekyll serve


## [Setup Godaddy Domain for GitHub Page](https://medium.com/@LovettLovett/github-pages-godaddy-f0318c2f25a)
1. Create a new file CNAME and put the xponenthub.com in the file.
2. Login GoDaddy > Manage domain > DNS Zone File.
3. Under A (Host) change @ point to 192.30.252.153.
4. Under CName (Alias) change www point to xponenthub.github.io.


# Landing Page Jekyll theme

Jekyll theme based on [landing-page bootstrap theme ](http://startbootstrap.com/templates/landing-page/)

## How to use
 - Place a image in `/img/services/`
 - Create posts to display your services. Use the follow as an example:

```txt
---
layout: default
img: ipad.png
category: Services
title: The service title
---
The description of this service
```

## Demo
View this jekyll theme in action [here](https://swcool.github.io/landing-page-theme)

## Screenshot
![screenshot](https://raw.githubusercontent.com/swcool/landing-page-theme/master/img/screenshot.png)

===

For more Jekyll details, read [documentation](http://jekyllrb.com/).
This Jekyll theme used [Freelancer Jekyll theme](https://github.com/jeromelachaud/freelancer-theme/) as reference.

## License
The contents of this repository are licensed under the [Apache
2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

## Version
1.0.1
