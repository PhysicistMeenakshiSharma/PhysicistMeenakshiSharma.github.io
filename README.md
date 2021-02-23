A Github Pages template for academic websites. This was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

I think I've got things running smoothly and fixed some major bugs, but feel free to file issues or make pull requests if you want to improve the generic template / theme.

### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

# Instructions

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

# Changelog -- bugfixes and enhancements

There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch. 

To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here](https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20). Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.

## Qiusheng Wu

[![GitHub Badge](https://img.shields.io/github/followers/giswqs?style=social)](https://github.com/giswqs)
[![Twitter Badge](https://img.shields.io/twitter/follow/giswqs?style=social)](https://twitter.com/giswqs)
[![Google Scholar Badge](https://img.shields.io/badge/Google-Scholar-lightgrey)](https://scholar.google.com/citations?user=vmml4_0AAAAJ&hl=en)
[![UTK Badge](https://img.shields.io/badge/UTK-Faculty-orange)](https://faculty.utk.edu/Qiusheng.Wu)
[![YouTube Badge](https://img.shields.io/badge/My-YouTube-red)](https://www.youtube.com/c/QiushengWu)
[![LinkedIn Badge](https://img.shields.io/badge/My-LinkedIn-blue)](https://www.linkedin.com/in/qiushengwu)
[![CV Badge](https://img.shields.io/badge/My-CV-critical)](https://arcgis.me/cv/)
[![Donate Badge](https://img.shields.io/badge/Donate-Buy%20me%20a%20coffee-yellowgreen.svg)](https://www.buymeacoffee.com/giswqs)

I am an Assistant Professor in the [Department of Geography](https://geography.utk.edu/about-us/faculty/dr-qiusheng-wu/) at the [University of Tennessee, Knoxville](https://www.utk.edu/). My research interests include Geographic Information Science (GIS), remote sensing, and environmental modeling. More specifically, I am interested in applying geospatial big data, machine learning, and cloud computing (e.g., [Google Earth Engine](https://earthengine.google.com/)) to study environmental change, especially surface water and wetland inundation dynamics. I am a strong advocate of open science and reproducible research. More information about my research and teaching can be found at <https://wetlands.io>.

---

### Open-source Projects

- **Linux:** [manjaro-linux](https://github.com/giswqs/manjaro-linux)
- **R packages:** [whiteboxR](https://github.com/giswqs/whiteboxR)
- **Python packages:** [geemap](https://github.com/giswqs/geemap) | [lidar](https://github.com/giswqs/lidar) | [whitebox-python](https://github.com/giswqs/whitebox) | [geospatial](https://github.com/giswqs/geospatial)
- **ArcGIS Toolboxes:** [WhiteboxTools-ArcGIS](https://github.com/giswqs/WhiteboxTools-ArcGIS) | [Depression Analysis Toolbox](https://github.com/giswqs/Depression-Analysis-Toolbox) | [Wetland Hydrology Analyst](https://github.com/giswqs/Wetland-Hydrology-Analyst-Toolbox)
- **Google Earth Engine:** [Awesome-GEE](https://github.com/giswqs/Awesome-GEE) | [earthengine-py-notebooks](https://github.com/giswqs/earthengine-py-notebooks) | [qgis-earthengine-examples](https://github.com/giswqs/qgis-earthengine-examples) | [earthengine-apps](https://github.com/giswqs/earthengine-apps)

---
### Latest Blog Posts
<!-- HASHNODE:START -->
- [Visual Studio Code Tips & Tricks](https://blog.gishub.org/visual-studio-code-tips-and-tricks)
- [Google Colab Tips and Tricks](https://blog.gishub.org/google-colab-tips-and-tricks)
- [GEE Tutorial #52 - How to create timelapse animations with custom projection, scale bar, and north arrow](https://blog.gishub.org/gee-tutorial-52-how-to-create-timelapse-animations-with-custom-projection-scale-bar-and-north-arrow)
- [GEE Tutorial #51 - How to create publication quality maps with customized projections](https://blog.gishub.org/gee-tutorial-51-how-to-create-publication-quality-maps-with-customized-projections)
- [GEE Tutorial #50 - How to create publication quality maps using cartoee](https://blog.gishub.org/gee-tutorial-50-how-to-create-publication-quality-maps-using-cartoee)
<!-- HASHNODE:END -->
---


![github stats](https://github-readme-stats.vercel.app/api?username=giswqs&show_icons=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=giswqs&hide=javascript,go,html)
<!-- ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=giswqs&hide_langs_below=10) -->
