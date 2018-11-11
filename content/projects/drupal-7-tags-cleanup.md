---
title: "Drupal 7 Tags Cleanup"
date: 2018-11-11T16:00:42-05:00
type: projects
description: Drupal 7 custom module to clean up duplicate and similar tags.  
keywords: drupal, custom module, taxonomy, clean up tags, remove similar taxonomy, website, web development
image: https://res.cloudinary.com/dkjdeuwlv/image/upload/v1541969158/bargavkondapu.com/projects/code-preview.jpg
imagealt: Programming Code
imagecredits: © [cronislaw] /Adobe Stock
categories: ["Drupal"]
project-url: https://github.com/bhar1red/drupal-7-tags-cleanup
draft: false
---

[comment]: # (Project should contain Summary, Description, Repo and Live urls, Screenshot or demo video and Tutorials( if any.))

One of the problems, user's face is too-many similar tags. Since tags can be created by multiple people, there is a posiblity of two users, creating same tag, with a minor difference.

For example, informationTechnology, Information Technology, Information-Technology, information technology,... are all valid tags and mean the same. When a user wants to tag a content, they often gets confused with which tag to use.

This module, is created as a drush command, scans through such tags, identify which one to keep and deletes other tags. It also updates all content tagged with such similar tags to now tag to real one. For above example, Module would keep Information-Technology and delete all other tags.

Code is available as an open source module on github. All installation and usage instructions are mentioned there.


**Project URL:** https://github.com/bhar1red/drupal-7-tags-cleanup

**Technology :**  [Drupal](https://www.drupal.org/)
