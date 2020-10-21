# FastHelpers Framework [FHF]

   ![image](https://user-images.githubusercontent.com/69651552/96674940-1d104a00-136a-11eb-8924-c505235a4e90.png)

Simple Open Source CSS Framework Especially Suitable for the Beginners in the Field of Front-End Web Development, to help them making their Projects in a Fast Way as Possible, as it let you focus on the code more than on the style anymore.

## Description

FastHelpers Framework will save you a lot of time in adding some frequently duplicated styles for many of the elements in your application. I have collected most of these styles and limited them precisely in some classes named after each style to maintain the flexibility of working with these classes, also i add some helpers classes special for your application theme color and dark mode, and by using them you can make multiple themes in a very easy way as i will show you below, also you can control day and dark mode easily.

> Note: Again i say that this framework matches the beginners in the field than the professional geeks because defenitiely there are many professional frameworks you can use and also advanced ways in control themes changes better than the way i use in this framework, but you can use this framework as a good start step for you in your projects until you deep learning in the other techniques that you will learn in the future.

## Features  

- More Re-usable and Maintainability.
- Easy to use and understand the Classes Components.
- Highly Flexibility.
- Familiar with the use of Bootstrap Framework and can work with it Perfectly.
- Depending on the Name of the Framework (FastHelpers), it has Speed, Fast and Flexible Helper Classes that are named precisely to match the name of each style.
- Very Important Feature: while it has Important Helper Classes that are grouped together in one Collection called  [FastHelpers Themes Classes (FHTC)], these Helpers Themes Classes will help you to make Different and Multiple THEMES for your Website in no Time, Plus they have in the same collection another Helpers Themes Classes Special for DARK MODE Theme,
and by just Manipulating with Colors & Background-colors only in this Helpers Themes Classes you can make Multiple Themes.


## Prerequisites
  
- Some Knowladge of how to manibulating with DOM in Javascript.
- Some Knowladge of jQuery, because i will depend on it to control the links elements of themes, but it is optional for you as you can use pure JS for making same result.
- Good understand for CSS and control Styles of Classes.

## Getting Started

#### First:  Perfect Location to insert this Framework Files.

- If you use Bootstrap framework, so it is prefered to add fasthelpers files after the bootstrap link and after the style of the page itself that you stand on it now, like the photo below.

![image](https://user-images.githubusercontent.com/69651552/96479351-1f26bb80-1239-11eb-91df-bfcd8323f2af.png)

> This order of links will reduce the number of (!important) flags that you may use in the fasthelpers classes to enforce the browser to take the style from the fasthelpers files. You may don't need to any (!important) flags if you follow this order of links.

#### Second: Introduction to each Helper Class and how it can help you.

```
.upper {text-transform: uppercase} /*uppercase for the text*/
```
![image](https://user-images.githubusercontent.com/69651552/96489412-b55de000-123f-11eb-9647-7510fd7e0e41.png)

![image](https://user-images.githubusercontent.com/69651552/96489847-492fac00-1240-11eb-8ae4-b19df5f93075.png)

----------------------------------------------------------------------------
```
.underline {text-decoration: underline} /*add underline for the text*/
```
![image](https://user-images.githubusercontent.com/69651552/96489936-6b292e80-1240-11eb-8c1d-ee308506968d.png)

![image](https://user-images.githubusercontent.com/69651552/96490011-87c56680-1240-11eb-9c06-e07113e2f1ba.png)

----------------------------------------------------------------------------
```
.par {margin: 15px 0; font-size: 18px; font-weight: bold; color: #727586; line-height: 1.6} 
/*
- Special class for any paragraph that enhance most of requirements you need for any paragraph.

- You may need to use the (padding) helper class to add some padding to your paragraph.

- Change the color of the paragrapgh as you want.
*/
```
![image](https://user-images.githubusercontent.com/69651552/96676387-7f1e7e80-136d-11eb-8e44-d625dde1ff64.png)

![image](https://user-images.githubusercontent.com/69651552/96490189-c6f3b780-1240-11eb-98c8-76bb0c257e71.png)

----------------------------------------------------------------------------
```
.shadow {box-shadow: 0 0 16px rgba(0, 0, 0, .1)} 
/*
- Add box-shadow for your box.
- Suitable for Paragraphs boxes.
- The Style of the shadow follows the material Designs, preferred to use it as shown above to have best experience.
*/
```
![image](https://user-images.githubusercontent.com/69651552/96676352-6ada8180-136d-11eb-85ca-67569a7973c6.png)

![image](https://user-images.githubusercontent.com/69651552/96490463-23ef6d80-1241-11eb-8e8b-f3bbc533b5bc.png)

----------------------------------------------------------------------------
```
.bold {font-weight: bold} /*Increase the font weight of the text*/
```
----------------------------------------------------------------------------
```
.border {border: 1px solid #ddd} /*Add small border to your element*/
```
----------------------------------------------------------------------------
```
.list {background: transparent; border: none; font-size: 16px}
/*
- Suitable for using with the elements that have bootstrap class (list-group-item) to remove the white background of these elements and remove the border.
*/
```
- before add <code>list</code> helper class

![image](https://user-images.githubusercontent.com/69651552/96490743-85174100-1241-11eb-8294-72e54b2fa016.png)

- after add <code>list</code> helper class

![image](https://user-images.githubusercontent.com/69651552/96500937-ee05b580-124f-11eb-89ee-46e4b149d647.png)

![image](https://user-images.githubusercontent.com/69651552/96490921-cc9dcd00-1241-11eb-9d5d-553f4b82d485.png)

----------------------------------------------------------------------------
```
.padding {padding: 10px} /*Add some padding to your element*/
```
![image](https://user-images.githubusercontent.com/69651552/96676290-47afd200-136d-11eb-8b61-6d38338ee444.png)

![image](https://user-images.githubusercontent.com/69651552/96491045-f9ea7b00-1241-11eb-8bca-d88e8621a56a.png)

----------------------------------------------------------------------------
```
.radius {border-radius: 15px} /*Add some border-radius for your element*/
```
![image](https://user-images.githubusercontent.com/69651552/96676202-1c2ce780-136d-11eb-86ac-6f86863e670c.png)

![image](https://user-images.githubusercontent.com/69651552/96491099-0ff83b80-1242-11eb-939b-9e6695292d21.png)

----------------------------------------------------------------------------
```
.margin-bt {margin-bottom: 15px} /*Add 15px margin bottom for your element*/
```
----------------------------------------------------------------------------
```
.relative {position: relative} /*Add position relative for your element*/
```
----------------------------------------------------------------------------
```
.overlay {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background: rgba(0,0,0,.6);
    z-index: 1
}
/*
- This helper class is most suitable if you want to add a background-image to your section element, so you may need an overlay above this background-image to enhance its appearance.
- You may need to add (relative) helper class to the parent of the element that has this helper class to get the right effect.
*/
```
- before add <code>overlay</code> helper class.

![image](https://user-images.githubusercontent.com/69651552/96491488-9b71cc80-1242-11eb-8c8c-d20d72c86362.png)

- after add <code>overlay</code> helper class.

![image](https://user-images.githubusercontent.com/69651552/96676642-1683d180-136e-11eb-918a-664c435d6cf4.png)

![image](https://user-images.githubusercontent.com/69651552/96491294-53eb4080-1242-11eb-95b8-4a916b9c405d.png)

> background-image has a dark overlay now that makes its appearance better than before.

----------------------------------------------------------------------------
```
.transition,
.transition:before,
.transition:hover::before {
    transition: all .4s linear;
    -webkit-transition: all .4s linear;
    -moz-transition: all .4s linear;
    -o-transition: all .4s linear
}
/*
- Add this helper class to your element, makes it has some transition or has some transition for its before element, or has some transition for its before element when hover on it also.
*/
```
----------------------------------------------------------------------------
```
.before::before {
    width: 100%;
    height: 100%;
    top: 0;
    left: auto;
    right: 0px;
    position: absolute;
    border-radius: 15px;
    content: '';
    opacity: 0
}

.before:hover::before {opacity: 1}
/*
   - Add a box element as a before element in its parent element.

   - Its opacity equals to 0 until you hover on its parent element.
   
   - You may need to add (relative) class to the element that has this helper class to get the right effect.
*/
```
----------------------------------------------------------------------------
```
.cursor {cursor: pointer} /*Change the mouse pointer to cursor for specific element*/
```
----------------------------------------------------------------------------
```
.line-through {position: relative; z-index: 5} 

.line-through span {
    width: 250px;
    height: 12px;
    display: block;
    margin: auto;
    position: relative;
    bottom: 20px;
    opacity: .4;
    z-index: -1; 
}

/*
   - Make a line through the element. 
   - You MUST use a (span) element inside the element that has this helper class to get the right effect of it.
   - If you don't use the fasthelpers themes classes with the (span) inside the element, you may need to add a backgrond-color for this (span) as you want to can show it.
*/
```
![image](https://user-images.githubusercontent.com/69651552/96499870-48057b80-124e-11eb-9d1b-d6ac6e930c5c.png)

![image](https://user-images.githubusercontent.com/69651552/96500108-a92d4f00-124e-11eb-9589-632d8bd4965f.png)

----------------------------------------------------------------------------
```
.line-below::before {
    content: "";
    position: absolute;
    bottom: -5px;
    width: 66px;
    height: 2px;
    background: #ddd
} 
/*
   - Add incomplete line below the text that has this class.
   - You may need to add (relative) helper class to the element that has this helper class to get the right effect.
*/
```
![image](https://user-images.githubusercontent.com/69651552/96497128-7e40fc00-124a-11eb-9fde-6aeaa9eb51aa.png)

![image](https://user-images.githubusercontent.com/69651552/96496944-39b56080-124a-11eb-90bb-9fcca8460097.png)

----------------------------------------------------------------------------
```
.section-padd {padding: 40px 0} /*Preferred to use with section elements to add 40px padding top and bottom for customizing the distance between sections*/
```
----------------------------------------------------------------------------
```
.high-height {height: 400px} /*Add height 400px to your element*/
```
----------------------------------------------------------------------------
```
.middle-content {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%)
} 
/*
   - In order to center the content inside any element.
   - You may need to use the bootstrap class (text-center) with this helper class to have the right effect.
   - You may need to add (relative) helper class to the parent of the element that has this helper class to get the right effect.
*/
```
![image](https://user-images.githubusercontent.com/69651552/96502057-9405ef80-1251-11eb-955d-68673262e1af.png)

![image](https://user-images.githubusercontent.com/69651552/96498355-40dd6e00-124c-11eb-80ee-40f93ec36e1e.png)

----------------------------------------------------------------------------
```
/*Colors Helper Classes*/

.grey {color: #ddd} /*Add grey color to the text*/

.dark-grey {color: #222} /*Add dark grey color to the text*/ 

.white-color {color: #fff} /*Add white color to the text*/

.white-bg {background: #fff} /*Add white background to the element*/

.white-color-hvr:hover {color: #fff} /*Add white color to the text when hover on it*/

.white-bg-hvr:hover {background: #fff} /*Add white background to the element when hover on it*/
```

#### Third: FastHelpers Themes Classes and Dark Mode Classes [FHTC]

* Before anything you may need to use the mechanism that i will follow, to can move between multiple themes easily without any disturbance.

   - 1) You need to add features to your application, something like tools menu that allows to the user to choose between options of change themes and modes like that.

   ![image](https://user-images.githubusercontent.com/69651552/96512326-9de31f00-1260-11eb-942c-e3478914e55c.png)

   - 2) Also you may need to take a look at the structure of the tools menu as html code, if you want to follow my way in changing the themes.

   ![image](https://user-images.githubusercontent.com/69651552/96512988-a0924400-1261-11eb-94e4-3cf9712505d9.png)
   > I will depend on the data-theme attr. to can manibulate with the style links of the themes easily., as you can see i made 3 different themes colors, each theme has its own file with the same fasthelpers themes classes but with different values of colors and background-colors, and i follow a stable pattern to name theses themes files as you see, the color name of each theme then a dash sign (-) then the word of (theme), and i add additional name (default) to the default theme of the application to can distinguishe it from the rest of themes, then i add each theme file name with its full url path inside the <code>data-theme</code> attr.

   - 3) In the top of the page i add the default theme url link, and i will depend on it to change between themes later.

   ![image](https://user-images.githubusercontent.com/69651552/96515252-4f844f00-1265-11eb-92f6-66632de97ea6.png)
   > I add to the fasthelpers themes classes inside this file all the colors and background-colors that belongs to this theme only. don't forget to add this link after the link of the fasthelpers itself and the bootstrap link as i showed in the perfect order before.

   - 4) Then the Javascript part comes, i will use jQuery here to control the themes changing color mechanism, the function to change theme color is very easy.

   ![image](https://user-images.githubusercontent.com/69651552/96516265-19e06580-1267-11eb-9620-0e508bac0184.png)
   > when clicking on any colors inside the tools menu, the function search about link element that has href attribute containing this word (-theme) then replace the url of this href with the url of the chosen theme, the url that i saved before inside the data-theme attr. of each theme color {step b}, and this how to change between themes, while the new theme will be replaced instead of the old current theme depending on changing the url of each theme file, so the new theme will come to your application with its special colors that are saved inside the fastHelpers themes classes.

   - 5) The Most important thing that i still haven't talked about it is you Must add the required fasthelper theme class to each element that you want it to follow the themes colors rules, for example if you want to make a text has the theme color you will need to add <code>theme-color</code> helper class to it, if you want to make an element has the theme background you will need to add <code>theme-bg</code> helper class to it, and so on.

   - 6) Then, the function of changing the modes from day to night or night to day will be: 

   ![image](https://user-images.githubusercontent.com/69651552/96519457-544d0100-126d-11eb-9895-767e3ba40722.png)
   > I move all the FastHelpers Dark Mode Classes from the fasthelpers_themesclasses file to another isolated file called (dark-mode), then when the user clicks on the night icon the function will search about link element that has href containing (-theme) and inject the dark mode file after this link in the order of the code as shown in the function, and when clicking on the day icon the dark mode file will be removed from the DOM.

   - 7) You may notice in the previous dark mode function that we add to each element that has <code>text-for-dark</code> class another class called <code>dark-color</code> and each element has <code>box-for-dark</code> class another class called <code>dark-box</code> when switching to the dark mode., that means if you need any text to be colored with a different color suitable for the dark mode you may need to add <code>text-for-dark</code> helper class to it in order to match the dark mode function and if you need any element to be colored with a different background-color suitable for the dark mode you may need to add <code>box-for-dark</code> helper class to it in order to match the dark mode function, and you may notice that <code>dark-box</code> and <code>dark-color</code> helper classes will be removed from any elements in the DOM after clicking on the day icon as the day mode function said, to return the elements to its normal style.  

   > Note: the way above of chnaging themes color or theme modes is optional, you don't have to use it anymore, and you can use any way else that leads to the same result, i wish you understand the concept of my way then you can use it by any another way, but the next point of explanation each fasthelper theme class is the important point and you have to use it as shown below to have the right effect.

* Now i will explain each fasthelper theme class and dark mode classe individually like i do with the normal fasthelpers classes before, and i will add some fully components examples that has a combination of multiple helper classes from the framework which will be useful to use it directly as a ready fast element after the end of the explanation.

```
.theme-color {color: var(--main-color)}
/*
   - Add this class to text you want it to has the theme color.
*/
```
----------------------------------------------------------------------------
```
.theme-bg {background: linear-gradient(to left, var(--main-color) 0%, var(--second-color) 100%)} 

/*
   - Add this class to element you want it to has the theme background color.
*/
```
----------------------------------------------------------------------------
```
.theme-bg-hvr:hover {background: linear-gradient(to top, var(--main-color) 0%, var(--second-color) 100%)}
/*
   - Add this class to element you want it to has the theme background color when hover on it.
*/
```
----------------------------------------------------------------------------
```
.theme-color-hvr:hover {color: var(--main-color)}
/*
   - Add this class to text you want it to has the theme color when hover on it.
*/
```
----------------------------------------------------------------------------
```
.theme-border {border: 1px solid var(--main-color)}
/*
   - Add this class to element you want it to has a border that colored with the theme color.
*/
```
----------------------------------------------------------------------------
```
.theme-text-shw {text-shadow: 0 0 20px /*rgba(var(--second-color) >> in rgb syntax, 0.6)*/}
/*
   - Add this class to text you want it to has a text shadow that colored with the theme color.
*/
```
----------------------------------------------------------------------------
```
.theme-box-shw {box-shadow: 0px 2px 10px 0px var(--main-color)}
/*
   - Add this class to element you want it to has a box shadow that colored with the theme color*/
```
----------------------------------------------------------------------------
```
.theme-box-shw-hvr:hover {box-shadow: 0 0 3px 2px /*rgb(var(--main-color) >> in rgb syntax, .8)*/}
/*
   - Add this class to element you want it to has a box shadow that colored with the theme color when hover on it.
*/
```
----------------------------------------------------------------------------
```
.before-bg:before {background: linear-gradient(to top,var(--main-color) 0%, var(--second-color) 100%)}
/*
   - Add this class to element you want its before element has the theme background color.
*/
```
----------------------------------------------------------------------------
```
.before-bg:hover::before {background: linear-gradient(to top, var(--main-color) 0%, var(--second-color) 100%)}
/*
   - Add this class to element you want its before element has the theme background color when hover on the element.
*/
```
----------------------------------------------------------------------------
```
/*Dark Mode Classes*/ 
body {background-color: #121212}

.par {color: #b1b1b1}

.dark-color {color: #f7f7f7}

.dark-box {background: #222}

.shadow {box-shadow: 0 0 16px rgba(126, 126, 126, .6)}

/*
   {body} >> will have this background #121212.

   {.par} >> any element that has (par) class in the normal mode, its texts color will be changed to #b1b1b1 in the dark mode. 

   {.dark-color}  >> this class is a dynamic class, you haven't to add it manually to any text in your App. but to play it automatically when switching to dark mode you MUST add to the text that you want to use this helper class with it in the dark mode another class called (text-for-dark), so the text will take the color of #f7f7f7

   {.dark-box}  >> this class is a dynamic class, you haven't to add it manually to any element in your App. but to play it automatically when switching to dark mode you MUST add to the element that you want to use this helper class with it in the dark mode another class called (box-for-dark), so the element will take the background color of #f7f7f7

   {.shadow} >> any element that has (shadow) class in the normal mode, its box shadow will be changed to have a color with rgba(126, 126, 126, .6) in the dark mode. 

   Note: Every color and background color used in the dark mode is chosen precisely depending on the material designs rules.  
*/
```

#### Fourth: Fully Components Examples (Ready to Use)

* Component Example 1:

```
<div class="service theme-box-shw before before-bg text-center transition cursor padding radius relative box-for-dark">
   <div class="service-img padding border relative img-circle">
      <img src="images/services/2.png" alt="service-clipart" class="center-block">
   </div>
   <h4 class="upper dark-grey text-for-dark relative">Free Cpanels & CMS</h4>
   <p class="par relative">What you search about it, is existed with CMS and Cpanels, you can now reach the ultimate power of control.</p>
   <button class="btn btn-lg theme-bg theme-color-hvr white-color border white-bg-hvr relative transition">Show More</button>
</div>
```
> Results:

- Day Mode

![image](https://user-images.githubusercontent.com/69651552/96672925-9a858b80-1365-11eb-8f6a-b39bc19fd5a9.png)

- Day Mode when Hover on the Component

![image](https://user-images.githubusercontent.com/69651552/96673051-ea645280-1365-11eb-907c-9b0ddd698561.png)

- Dark Mode

![image](https://user-images.githubusercontent.com/69651552/96672989-bee16800-1365-11eb-9723-ee19ec2f258f.png)

- Dark Mode when Hover on the Component

![image](https://user-images.githubusercontent.com/69651552/96673015-cd2f8400-1365-11eb-92f5-8075c8f624ae.png)

----------------------------------------------------------------------------

* Component Example 2:

```
<div class="feature relative theme-box-shw-hvr transition padding radius shadow box-for-dark">
   <span class="logo theme-bg radius"><i class="fas fa-robot fa-2x white-color"></i></span>
   <h4 class="upper dark-grey text-for-dark">Advanced Functionality</h4>
   <p class="par">We have several stetion all over the world, unlimted speed, spaces for sure and Storage.</p>
   <span class="theme-color read cursor">Read More <i class="fas fa-arrow-right"></i></span>
</div>
```
> Results: 

- Day Mode  

![image](https://user-images.githubusercontent.com/69651552/96673231-55ae2480-1366-11eb-9966-af7469567d2c.png)

- Day Mode when Hover on the Component

![image](https://user-images.githubusercontent.com/69651552/96673289-76767a00-1366-11eb-962d-39126cc32b8e.png)

- Dark Mode

![image](https://user-images.githubusercontent.com/69651552/96673321-8c843a80-1366-11eb-976f-a3e3f7607662.png)

- Dark Mode when Hover on the Component

![image](https://user-images.githubusercontent.com/69651552/96673341-97d76600-1366-11eb-8d25-47c8dff0c144.png)

----------------------------------------------------------------------------

* Component Example 3:

```
<div class="box">
   <h4 class="h3 theme-color upper">Perfect Plan Suitable for you is important.</h4>
   <p class="par shadow padding box-for-dark radius">Choosing Suitable Plan is very important to save the usability and flexability of your website mechanism, also you need to be active with any kinds of updated Plans, we have a great newer Plans everyday, so don't miss it.</p>
</div>
```
> Results: 

- Day Mode  

![image](https://user-images.githubusercontent.com/69651552/96673695-5b583a00-1367-11eb-9c2e-d7d46d034c63.png)

- Dark Mode

![image](https://user-images.githubusercontent.com/69651552/96673724-70cd6400-1367-11eb-9a1d-24adff43b323.png)


## Versions  

* [v1.0](https://github.com/Mohamed-Elhawary/fasthelpers-framework-fhf/tree/v1.0)  

This is the beginning vesion of the framework, i will enhance it in the next versions by adding more classes, use different techniques to build the framework like (SASS) and add some other features that absolutely will improve the performance, so all i need is your support to continue. 


## Built With

* CSS

## Applications that built based on FastHelpers Framework

* I made a Fully Responsive Hosting Website that are depending totally on Bootstrap Framework and my own Fast Helpers Framework.
  - you can see the code of this project from its repositry from [here](https://github.com/Mohamed-Elhawary/firebeta).

  - or you can have a direct live preview by visiting the website from [here](https://firebeta.netlify.app).

## Author

* Mohamed Elhawary  

## Contact Me  

* Email: mohamed.k.elhawary@gmail.com  

* [Linkedin](https://www.linkedin.com/in/mohamed-elhawary14/) 

* [codePen](https://codepen.io/Mohamed-ElHawary)

## Deploy with Me

Feel Free to Deploy it with me, send Issues or a Pull Request and i'll deal with you, just test it First.

## License

Code and documentation copyright 2020 the FastHelpers Framework [Author](https://github.com/Mohamed-Elhawary), Code released under [MIT License](LICENSE)