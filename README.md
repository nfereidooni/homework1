# Homework 1 - Horiseon SEO

## Project Description

The goal of this project was to update the code in order to meet accessibility standards and be optimized for search engines by:
* Adding semantic elements
* Applying a logical, sequential structure to the code
* Adding alt attributes to the images
* Adding aconcise, descriptive title

## Table of Contents

1 HTML Changes
2 CSS Changes
3 Credits
4 License

## 1 HTML Changes

1. I updated the site title to be both descriptive and concise.

2. I added alt tags to the images. 
    i.e.     
    ```
    Before:
    <img src="testimage.jpeg" />
    After:
    <img src="testimage.jpeg" alt="alternate text" />
    ```
3. I changed non-semantic elements to semantic elements.
    ```
    <header> for the page header
    <nav> for the navigation bar/links within the header
    <section> for the main info section
    <aside> for the section to the right side
    <footer> for the footer at the bottom
    ```

4. I changed one of the image tags to be self closing.
    i.e.
    ```
    Before:
    <img src="textimage.jpeg" />
    After:
    <img src="textimage.jpeg"></img>
    ```
5. I fixed one of the navigation bar links that wasn't working.


## 2 CSS Changes
I improved the codebase for long-term sustainability by reworking the CSS to make it more efficient by consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements and added comments. By doing so I was able to get eliminate a lot of duplicate code.

## 3 Credits
* Fil
* Daniel
* My amazing peers!
* Groot (my 6-month old puppy)

## 4 License
Copyright (c) 2020] [Niki Fereidooni]
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.