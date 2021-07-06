# Class 11 Reading Notes

## Chapter 16: Images (pp.406-427)

* By default, images are **inline** objects
* Using the **width** and **height** properties in CSS, you can control the size of an image
* You can use a background image behind yje box created by any element on the page
* You can create image rollover effects by moving the background position of an image
* To reduce the number of images your browser has to load, you can create image sprites
* When a single image is used for several different parts of an interface, it is known as a **sprite**

### Centering image
* First turn it into a **block-level** element using the `display` property with a value of `block`
* Then use the `text-align` property with a value of `center`
* Or, use the `margin` property & set values of the left & right margins to `auto`

### Repeating Images

`background-repeat` and `background-attachment`

The `background-repeat` propery can have 4 values:

1. `repeat`: the background image is repeated both horizontally and vertically
2. `repeat-x`: the image is repeated *horizontally* only
3. `repeat-y`: the image is repeated *vertically* only
4. `no-repeat`: the image is only shown once

The `background-attachment` property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have 2 values:

1. `fixed`: the background image stays in the same position on the page
2. `scroll`: the background image moves up and down as the user scrolls up and down the page

## Chapter 19: Practical Information (476-492)

* Search Engine Optimization helps visitors find your site when using search engines
* To put your site on the web, you need to obtain a domain name and web hosting
* FTP (File Transfer Protocol) programs allow you to transfer files from your local computer to your web server
* Many companies provide platforms for blogging, email newsletters, e-commerce and other popular website tools to save you from writing them from scratch

### Search Engine Optimization (SEO)

### On-Page SEO

In every page of your website, there are seven key places where keywords can appear in order to improve its findability. **Never** try to fool search engines. They will penalize you for it. For example, never add "hidden" text in the same color as the background page.

1. Page Title

The page title appears at the top of the browser window or on the top of the browser tab, specified in the `<title>` element

2. URL/ Web Address

The name of the file is part of the URL

3. Headings

If keywords are in a heading `<hn>` element, then a search engine will know that this page is all about that subject and give it greater weight than other text

4. Text

It helps to repeat the keywords in the main body of the text at least 2-3 times

5. Link Text

Use keywords in the text that creates links between pages, rather than using generic terms like "click here"

6. Image Alt Text

Search engines rely on you providing accurate descriptions of images & helps your image show up in the results of image-based searches

7. Page Descriptions

The description lives inside the `<head>` element and is specified using a `<meta>`tag. It should be a sentence that describes the content of the page

### Analytics

As visitors come to your site, you can start analyzing how they found your site, what they were looking at, and at what point they left. Google offers a free service called Google Analytics

### Web Hosting

To make your site visible online, you need to upload it to a web server. There are lots of different types of hosting offers, but there are important things that will help you choose which company to use.

1. Disk Space

This refers to the total size of all of the files that make up your site

2. Bandwidth

This is the amount of data the hosting company will send to your site's visitors. If you imagine 10 people looked at every page on your site, it would be equivalent to 10 times the amound of disk space you use

3. Backups

Check whether the hosting company performs backups on your site. Some only create backups so they can restore your website in the event of a server break. Others allow access to backups which can be helpful if you accidentally break the site while updating