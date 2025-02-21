---
layout: page
title: Getting Started
subtitle: Learn how to set up your GitHub Page
use-site-title: true
---

# Build your website in 3 steps

There are a few different ways to build a website using Beautiful Jekyll, and this document will go through the simplest one: using a fork on GitHub. For most people (including myself!), this easy method is the recommended one.

Even if you choose to use one of the [advanced installation methods](https://beautifuljekyll.com/getstarted/#install-steps-hard), I still suggest you read through the easy method first.

## The easy way (recommended!)

Getting started is *literally* as easy as 1-2-3 😃

Scroll down to see the steps involved, but here is a 30-second video just as a reference as you work through the steps. If you don't already have a [GitHub account](https://github.com), you'll need to sign up.

![Installation steps](https://beautifuljekyll.com/assets/img/install-steps.gif)

<div class="gs-section-01" markdown="1">
### 1. Fork this project
Click on the **Fork** button at the top right corner of this page. Forking means that you're copying this entire project and all its files into your account. Do not click on the **Create fork** button on the next page yet.
</div>

<div class="gs-section-02" markdown="1">
### 2. Rename the repository to `YOURUSERNAME.github.io`
You'll see the word "repository" used a lot in GitHub - it simply means "project". Under **Repository name** you should see the name `beautiful-jekyll`, this is where you need to rename your project to `YOURUSERNAME.github.io` (replace `YOURUSERNAME` with your GitHub user name). It's important to use this exact name so that GitHub will recognize it and automatically create a website for this project.

> **Tip:** If you want to use a different URL for your website, check out the [FAQ](https://beautifuljekyll.com/faq/#custom-domain).
</div>

<div class="gs-section-03" markdown="1">
### 3. Customize your website settings
Edit the `_config.yml` file to change any settings you want. To edit the file, first click on it to view the file, and on the next page click on the pencil icon to edit it. The settings in the file are self-explanatory, and there are comments inside the file to help you understand what each setting does.

> **Note:** In the video above, only one setting in the `_config.yml` file is edited, but you should go through the rest of the settings as well.
</div>

<div class="gs-section-04" markdown="1">
### 4. Congratulations! You have a website!
If you named your project correctly and made an edit to the config file, your website should be ready in a minute or two at `https://YOURUSERNAME.github.io`. Every time you make a change to any file, your website will get rebuilt and should be updated in about a minute or so.
</div>

---

## The harder way (for advanced users)

The instructions above explain how to use Beautiful Jekyll in the easiest way: by forking on GitHub. There are more [advanced installation methods](https://beautifuljekyll.com/getstarted/#install-steps-hard) that include either using GitHub Pages with remote themes, or using Ruby gems. They provide you with more control but are only intended for advanced users.

> **Note:** Beautiful Jekyll was primarily designed to be used as a GitHub theme, so you will not get any support if you use this theme via Ruby gems.

---

```html
<style>
.gs-section-01 h3 { 
     color: red; 
}

.gs-section-01 p {
     font-size: 30px;
}

.gs-section-02 h3 { 
     color: blue; 
}

.gs-section-02 p {
     font-size: 30px;
}

.gs-section-03 h3 { 
     color: yellow; 
}

.gs-section-03 p {
     font-size: 30px;
}

.gs-section-04 h3 { 
     color: green; 
}

.gs-section-04 p {
     font-size: 30px;
}
</style>

