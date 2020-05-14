![AI Pos logo](https://github.com/Mr-Smyth/ai-touch/blob/master/assets/images/ai-logo.PNG "Site logo")

---












<div align="center">

[View the website on GitHub Pages](https://mr-smyth.github.io/Touch-AI/)



This is a project website for a fictitious company called Touch AI. They develop Point of sale software for the retail and hospitality trade.
And what really makes this Touch AI Website stand out against its competitors in the Point of Sale sector, is its direct clear information and uncluttered fresh layout.

This project will be submitted for my User-Centric Front End Development and first milestone project, in my Full Stack Software Development course. The project will produce a working static front-end website, demonstrating the technologies I have learned so far.
</div>

<br>

# UX

<br>

## Company Story:

Touch AI needs a B2B website that will reflect their professional standards and the respectable image they have achieved.

The website will be primarily aimed at the POS dealer market, **_not_** the end user.
The goal of the website will be to build a partner network of dealers. The website will be a source of clear and accurate information, that builds confidence, and encourages them to request a demo pack, or otherwise make contact.

The Website must contain all information relevant to the features of the Software. It must also promote the company's emphasis on Backup support — as a priority — in the company philosophy, and how it achieves this.

The information must be accurate, and presented clearly and concisely..


_("**KISS** - keep it simple, stupid" — U.S. Navy 1960)_


The visitor to the website will almost certainly have or will intend to visit and compare other websites and products. So being transparent and informative above and beyond the need is an experience that will remain with the visitor.



---
<br>

## User Stories 

* As a user I want to easily find the information I want.
* As a user I want to gain in-depth information about the benefits of the products from the website.
* As a user I want to feel that the company is reputable.
* As a user I want to know that I can easily and reliably contact someone.
* As management I want a professional responsive online presence.
* As management I want existing partners to be promoted.
* As management I want the versatility of our software to be promoted.
* As management I want an accurate point of information quickly and easily accessible for potential partners.
* As management I want to showcase our philosophy of support first.
* As tech support I want to see how our services and efforts can be showcased to the clients.

---
<br>
<div align="center">

## Opportunities arising from user stories:
<br>
</div>

<div align="center">
 

|Opportunities | Importance | Viability / Feasibility
|-----|:------:|:-----:|
|**Online Presence** | 5 | 5 |
|**Showcase Product** | 5 | 5 |
|**Create a simple point of contact** | 5 | 5 |
|**Make responsive for Mobile/Tablet** | 5 | 5 |
|**Showcase backup support**| 3 | 5 |
|**Showcase the versatility of the software** | 4 | 5 |
|**Showcase existing Partners** | 4 | 5 |
|~~Create a Faq area for partners~~ | 2 | 1 |
|~~Create an online forum for partners~~ | 2 | 1 |

</div>
<br>

Ultimately for the first release we will use the above table to target the most feasible elements.


---

<br>

## Wireframe mock-ups:


I made these of a medium-fidelity, deliberately leaving out promo images as they have not been finalized: I included some color and possible content placement, to test the appearance.


* [Home screen wire frame](https://github.com/Mr-Smyth/ai-touch/blob/master/wireframes/home-screen-wireframe.pdf)

* [Hospitality screen wire frame](https://github.com/Mr-Smyth/ai-touch/blob/master/wireframes/hospitality-screen-wireframe.pdf)

* [Retail screen wire frame](https://github.com/Mr-Smyth/ai-touch/blob/master/wireframes/retail-screen-wireframe.pdf)

* [Features screen wire frame](https://github.com/Mr-Smyth/ai-touch/blob/master/wireframes/features-screen-wireframe.pdf)

* [Contact us screen wire frame](https://github.com/Mr-Smyth/ai-touch/blob/master/wireframes/contact-screen-wireframe.pdf)

* [About us screen wire frame](https://github.com/Mr-Smyth/ai-touch/blob/master/wireframes/about-screen-wireframe.pdf)



---
<br>

## Considered execution and styling
<br>

### DESIGN:

The Hero image I designed to draw the attention with the opaque overlay of the eye, which does make the user take a 2nd look, and is visually appealing. An offset of the main area is deliberately overlapping the hero image so the visitor will be curious to scroll down.

Once the page is scrolled down, I want the Navbar to disappear, with all the CTA buttons on each section, ** feel there is no need for fixed navigation. 

I wanted a very clear white space, with a flow that invites you down the page, and draws your attention with offset images and unboxed content. A clean uncluttered experience, that provides brief but informative overviews of the product, rather than overpower. But then invites you to __*learn more*__, to find out more information, and eventually to achieve the goal, which is to make contact via the form on the contact page.

The information will be organizsed in a manner that both recognizes the clients' needs and makes logical sense. With the core of the page given up to promoting the product in a Benefits section, it will be padded top and bottom by a partner promotional carousel and a service dept promotion via some news blogs, which will satisfy the main demands on the Website.

A common footer with Navigation and CTA button will complete the layout.

Subpages will adopt the same styling as the Benefits section, with the contact page having a form layout.

<br>

### HTML: 

Intention to use [Bootstrap](https://getbootstrap.com) extensively throughout the HTML, with some [flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) as well. This is due to the ease and speed at which you can layout and space objects with bootstrap.


### CSS:

* **Style sheet:** A single style sheet will provide style for all pages.
The aim was to make the CSS as lightweight as possible, using more left to right HTML built-in bootstrap classes and re-using own style classes, to position and style items. 
* Studied new **naming methods** like BEM, but decided not to use it for this project, instead I will stick with solid simple but descriptive class names.
* **Fonts** The site has to be clear and simple, There must be nothing confusing, and so I chose simple clear fonts: **Poppins and Roboto**.
* **Sizing:** Decided to use REM sizing for fonts, as I find it easier to keep the sizes uniform across the site.
* **Colors:** Strong purple [#2e151b](https://www.google.com/search?q=%232e151b&oq=%232e151b&aqs=chrome..69i57.849j0j7&sourceid=chrome&ie=UTF-8) with a light contrasting pink [#da7b93](https://www.google.com/search?q=%23da7b93&oq=%23da7b93&aqs=chrome..69i57.415j0j7&sourceid=chrome&ie=UTF-8), will be the main theme colors of the site, matching with the own-styled logo. Purple is the color of royalty, luxury, power, wisdom, and creativity, whereas pink is a confident color.
A white center trunk when the screen is expanded to desktop type sizes will then contrast nicely with the [#424242](https://www.google.com/search?sxsrf=ALeKk02sJ9VZ3SKReOpg0FJiev_ZayEg2A%3A1588278616107&ei=WDWrXqGdBpup1fAP-ZqXiA8&q=%23424242&oq=%23424242&gs_lcp=CgZwc3ktYWIQAzoECCMQJzoICAAQBRAKEB46BAgAEB46BggAEAUQHjoHCAAQFBCHAjoCCAA6BQgAEIMBOgQIABADUJiaCVjVtAlgprkJaABwAHgAgAFziAHoB5IBBDEyLjKYAQCgAQGqAQdnd3Mtd2l6&sclient=psy-ab&ved=0ahUKEwihqd71_pDpAhWbVBUIHXnNBfEQ4dUDCAw&uact=5) text.


### Images:

* All images used are royalty-free from [Unsplash](https://unsplash.com/)

* **Hero image:** Layered 2 images together using [Gimp](https://www.gimp.org/) to include the subtle eye, to achieve a more catching hero image. Added a light pink opaque overlay to provide better contrast with hero text. 



---
<br>

# Features


#### Common features across the site:

* This website was designed from the mobile screen size first, as a result of some chosen media queries for @992px and @1200px, each web page responds neatly to all screen sizes. 
* They each contain a common navigation bar with the convention of a left-hand logo with the site navigation links on the right and a call-to-action button that links to the contact page.
* Each page also contains a common footer, with site navigation, contact details and social media links, and another call-to-action button for making contact.

#### index — Home - Landing page

* Hero image with promotional text and a call to action to "Take a Look" which leads to more information.
* Contains a brief introduction to Touch AI.
* Contains a carousel of reputable existing partners.
* A Benefits' information section, where the user can click to find out more.
* A Partner sign up Banner CTA.
* A Further reading news section, to promote the pedigree and level of support of the company.


  
#### Hospitality:
* Familiar styling.
* Contains more in-depth information regarding the Hospitality applications of Touch AI.
* Each section has a call to action button inviting them to make contact.


#### Retail:
* Familiar styling.
* Contains more in-depth information regarding the Retail applications of Touch AI.
* Each section has a call to action button inviting them to make contact.


#### Features:
* Familiar styling.
* Explains some core features of the system. This is again split between the two main sectors of Retail and Hospitality.
* Each section has a call to action button inviting them to make contact.


#### About:
* Familiar styling.
* A brief history of AI Pos.
* Some information on the Partner system.


#### Contact us:
* Familiar styling.
* Some information about contacting Touch AI.
* A responsive contact form, which contains:
  * Name.
  * Business Name.
  * Postcode.
  * Telephone Number.
  * email.
  * Contact number.
  * How did you find out about us message box.
  * How would you like to be contacted Radio buttons.
  * Message box.

<br>

## Features considering implementing in future releases:

* A further set of pages relating to the individual products in more specific detail. This would branch off from the current Hospitality and Retail sections, into more specific areas such as Handheld ordering, Online sales, Kitchen Printing/Video ordering, etc. With links back to case studies where Touch AI, helped to solve a problem with its software.
* To be more useful as a point of information, a more specific downloads section or FAQ site would be useful for downloading brochures, spec sheets, etc.
* A Blog page, I feel that news stories and case studies of partner installations and similar news stories does create a more solid online image, and creates confidence.
* A video demonstration page.
* Make bottom navigation bar in the footer section to be more visually appealing and symetrical - perhaps remove vertical bars when on outside of line, when in mobile view.

---
<br>


# Technologies Used:

* **HTML and CSS** programming languages were used as the core building language of this website.
* [VS Studio code](https://code.visualstudio.com/) was used alongside [Gitpod](https://www.gitpod.io/) to develop this website.
* [Bootstrap 4.4 CDN](https://getbootstrap.com/docs/4.4/getting-started/download/#bootstrapcdn) was used extensively on this website build, which greatly simplified the responsive element of the building process.
* [Font Awesome](https://fontawesome.com/) was used to provide icons for the website.
* [Google Fonts](https://fonts.google.com/) was used as the source of fonts for this website.
* [jQuery](https://code.jquery.com/) Toot the latest slim CDN of JQuery core 3.5.0.
* [Favicon](https://favicon.io/) Was used to create the tab page icon for each web page.
  

---
<br>

# Issues during development:

 **Trying to implement the center white column in larger screen sizes**:
 
I had planned to use an absolute positioned block, with the rest of the page rendered on top. What I found was that when resizing the screen (zooming) the absolute block would not resize as expected, and any of the content would have needed a position relative to appear on top of the absolute div. Therefore, it seemed like the wrong or messy way to do it. 
I, therefore, decided to use the main section and style it white and set the offset content(pictures) to have negative margins.

**Getting Offset images to collapse at correct size:**

I Had some trouble making the expanding offset images responsive on the way down screen sizes. As I have set my white center div to be 1200px wide, that corresponds to the bootstrap 1200px breakpoint.
Therefore there is a tiny window between 1260px and 1200px where my images would not collapse properly.  


---
<br>

# Testing
<br>

![Responsive Touch-AI](https://github.com/Mr-Smyth/Touch-AI/blob/master/assets/images/responsive.PNG "Site Responsive Demo Image")


<br>

## Checking with Touch AI's needs:

* **_As a user I want to easily find the information I want:_**
   * The Touch AI Website achieves this by having a clear easy to navigate layout, in simple clear sections.

* **_As a user I want to gain in-depth information about the products benefits from the website._**
     * The Touch AI Website achieves this by providing very clear, detailed information about the systems' capabilities and benefits.

* **_As a user I want to feel that the company is reputable._**
     * The Touch AI Website achieves this by Providing a reputable partner carousel to showcase the reputable companies they are associated with. The website also provides some news stories that are good news/confidence building stories. Also the look and feel of the website is sophisticated and informative.


* **_As a user I want to know that I can easily and reliably contact someone._**
     * The Touch AI Website achieves this by Creating several call to action buttons. By adding the company contact details and telephone number on each page footer. Above all by making it very easy to reach a very clear and very functional contact form.

* **_As management I want a professional responsive online presence._**
     * The Touch AI Website achieves this by looking professional and being fully responsive.


* __*As management I want existing partners to be promoted.*__
     * The Touch AI Website achieves this by a partner promotional carousel, just beneath the company introduction


* **_As management I want the versatility of our software to be promoted._**
     * The Touch AI Website achieves this by using the benefits section and the Type of Business drop-down to provide information and links to how Touch AI can work right across the retail spectrum.


* **_As management I want an accurate point of information quickly and easily accessible for potential partners._**
  * The Touch AI Website achieves this by being informative about the capabilities and benefits of the system.

* **_As management I want to showcase our philosophy of support first._**
   *  The Touch AI Website achieves this by providing news stories on winning the Golden meter award, which explains that Touch AI is very much a service first company.

* **_As tech support I want to see how our services and efforts can be showcased to the clients._**
    * The Touch AI Website achieves this by providing details of the relaunch of the partner support forum.

<br>

## Responsiveness and Rendering:


This was initially done using Google Chrome developer tools, for the initial stages.

Once the Website was completed, I then put my code through some validation checks using the following resources:



* [Autoprefixer](https://autoprefixer.github.io/) was used to parse my CSS and add vendor prefixes where needed.
* [CanIuse](https://caniuse.com) was used for checking on various features which I used. I found a worrying lack of Flexbox compatibility associated with IE 11.
* [W3C Validator](https://validator.w3.org/) was used to check the HTML.
* [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/) was used to check my style.css.

<br>

I then used the following browsers directly on my own PC's to check layouts and links of the website:


* Chrome version 81.
* Edge version 81.
* Opera version 68.
* Firefox version 76.
* IE 11.
* I used [SauceLabs](https://saucelabs.com/) to verify the layout and links on Safari version 13.1.

On Each Browser I performed a simulated visit, Querying various parts of the website to test my User Stories. All eventualities led to the contact page in a minimum number of clicks, where I experimented with trying to submit an empty form, or a form missing any of the key required fields.

<br>

I then checked on the various devices I have available to me:
* A Samsung Galaxy Tab 10".
* A Samsung S7 and S8.
* An Apple iPhone 9.

<br>

## Testing Results:

* All validations on the HTML returned with no errors.
* The CSS Validation, showed warnings for the vendor prefixes, which are required for cross-browser support.
* All browsers rendered and links behaved as required, including form submissions.
* **An exception to this was on IE11, where the browser did not render the shadow effects or any of the simple flexbox classes. I have not been able to find a workaround for this as yet.**
* Each browser carried out the simulated visit as expected and satisfied all the user stories.


**All devices tested worked as expected.**

<br>

## Unresolved issues / Known Bugs

*    An exception on IE11 - where the browser did not render the shadow effects or any of the simple flexbox classes. The effect is that on IE 11, any text positioned using flexbox type classes are not rendering as expected. Also some shadow effects are not compatible with the IE11 Browser. I researched the usage of IE 11 as of April 2020 on [W3counter](https://www.w3counter.com/globalstats.php) and found that only 1.75% still use IE 11, as a result, i do not feel a re-writing of code, or any generous time investment would be worthwhile for a browser that is phasing out. Edge has no such issues.

*    I occasionally found a tiny residual trace left behind after the navigation hover effect, it was very small and infrequent, I spent some time trying to discover the source of the problem, and I suspect it is something to do with the imported [Hover effect](https://ianlunn.github.io/Hover/), as I removed my custom styling of the effect and the issue remained. I felt that the problem was not noticeable to anyone who user tested the site for me so I decided that it wasn't worth the time investment.

---
<br>

# Deployment
<br>

## GitHub Pages:

#### To deploy this website using GitHub pages:

1.  Log in to the GitHub account.
2.  Select the [Touch-AI](https://github.com/Mr-Smyth/Touch-AI) Repository.
3.  Select settings from the menu at the top of the page.
4.  Scroll down to the section titled **GitHub Pages.**
5.  Under the source subheading, click the drop-down menu labeled **None** and select **Master Branch.**
6.  The page will re-load.
7.  Scroll back down the GitHub Pages section and the deployed website link will be displayed.
8.  The website may take some time to become active, as GitHub does not update changes immediately.

<br>

## Local Branch:


#### It is possible to run a clone of this website on your own local machine:

1.  Go to the repository page for Touch-AI. ([Click Here](https://github.com/Mr-Smyth/Touch-AI))
2.  Above the file area, click on the green **Clone or Download** link.
3.  Click on the copy symbol to the right of the [URL](https://github.com/Mr-Smyth/Touch-AI.git).
4.  On your local computer, navigate to the desired containing folder, you want to clone the project to, and right-click and open [Git Bash](https://git-scm.com/downloads) *(or similar command prompt)*.
5.  Type `git clone` then right-click and paste the URL.
6.  The line should look something like this: `$ git clone https://github.com/Mr-Smyth/Touch-AI.git`.
7.  Press Return or Enter and your clone will be created.

---
<br>

# Credits
<br>

## Content and code

* The content of the pages is primarily my knowledge of the EPOS Trade from over 20 years of experience in the industry. However on AI possibilities, i read a [Medium](https://medium.com/@ccspos/ai-integration-in-pos-system-enhances-the-software-and-restaurant-business-bc4de5eac090) and a [Retail CIO](https://artificial-intelligence-apac.retailciooutlook.com/cxoinsights/pos-systems-can-now-become-artificial-intelligence-weapons--nid-145.html) article specifically on the possibilities of AI in Retail to sharpen my knowledge and i took some influence from there on specific AI-related topics.
* I read an article by [Clutch](https://clutch.co/seo-firms/resources/meta-tags-that-improve-seo) about must-have Meta tags, which led me to add the description Meta Tag to the head element.
* Shadows — Read articles on Box shadows in CSS tricks, but implementing the ideas in my own way.
* H1 text internal shadow, credit to [Designshack](https://designshack.net/articles/css/inner-shadows-in-css-images-text-and-beyond/)
* Used [CSS Gradient](https://cssgradient.io/) to achieve a few subtle background colors, most noticeably on the navigation hover effect.
* Took a great deal of help, from [W3 Schools](https://www.w3schools.com/) and [Stack Overflow](https://stackoverflow.com/) in understanding certain behaviors relating to negative margins and Absolute and Relative relationships.

<br>

## Media

* The photos used in this site were royalty-free and obtained from Unsplash and/or, privately owned by me.
* Logo was designed and created by me, using [Gimp](https://www.gimp.org/) after trying and gaining some inspiration from free logo design websites such as [free logo design](https://www.freelogodesign.org/) and [Design Hill](https://www.designhill.com/). Later added a light outline to the text in the logo as it had been mentioned to me that the slogan text was getting lost in the dark purple background.

<br>

## Acknowledgments

* I received inspiration for this project from the eventual realization of what was said in the instructions. As advised, if in doubt stick to something you know. I have always searched for websites that give a clean uncluttered view when dealing with this exact subject in the past, and all too often these types of websites, just feel like the owners have decided to just cram everything in. Often in life — Less is More..

<br>

## Disclaimer

The content of this Website is for educational purposes only.