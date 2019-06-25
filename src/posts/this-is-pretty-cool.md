---
layout: layouts/post.njk
title: This is pretty cool.
socialImage: /images/sansa-please-sit__d6-8bhiueaaokhn.jpg
date: 2019-06-25T09:03:53.068Z
tags:
  - sansa
  - cool
  - please
  - sit
---
Checking out this Hylia starter with Eleventy and NetlifyCMS. This is pretty cool. I suppose this text gets added to the github repo.

> Let's throw in some kitchen sink
>
> \
>
>
> which 
>
> **might not**
>
>  
>
> be a great idea.

<article class="post-6 page type-page status-draft hentry" id="post-6">



\## \[](abide)Abide



<form data-abide="" novalidate="" data-e="2cx4z9-e">



<div class="row">



<div class="columns">



<div data-abide-error="" class="alert callout" style="display: none;">



There are some errors in your form.



</div>



</div>



</div>



<div class="row">



<div class="small-12 columns"><label>Number Requireds <input type="text" placeholder="1234" aria-describedby="exampleHelpText" required="" pattern="number"> <span class="form-error"> Yo, you had better fill this out, it's requiredxx. </span></label> 



Here's how you use this input field!



</div>



<div class="small-12 columns"><label>Nothing Required! <input type="text" placeholder="Use me, or don't" aria-describedby="exampleHelpTex" data-abide-ignore=""></label> 



This input is ignored by Abide using \`data-abide-ignore\`



</div>



<div class="small-12 columns"><label>Password Required <input type="password" id="password" placeholder="yeti4preZ" aria-describedby="exampleHelpText" required=""> <span class="form-error"> I'm required! </span></label> 



Enter a password please.



</div>



<div class="small-12 columns"><label>Re-enter Password <input type="password" placeholder="yeti4preZ" aria-describedby="exampleHelpText2" required="" pattern="alpha_numeric" data-equalto="password"> <span class="form-error"> Hey, passwords are supposed to match! </span></label> 



This field is using the \`data-equalto="password"\` attribute, causing it to match the password field above.



</div>



</div>



<div class="row">



<div class="medium-6 columns"><label>URL Pattern, not required, but throws error if it doesn't match the Regular Expression for a valid URL. <input type="text" placeholder="http://foundation.zurb.com" pattern="url"></label> </div>



<div class="medium-6 columns"><label>European Cars, Choose One, it can't be the blank option. <select id="select" required=""><option value="volvo">Volvo</option> <option value="saab">Saab</option> <option value="mercedes">Mercedes</option> <option value="audi">Audi</option></select></label></div>



</div>



<div class="row">



<fieldset class="medium-6 columns"><legend>Choose Your Favorite, and this is required, so you have to pick one.</legend> <input type="radio" name="pokemon" value="Red" id="pokemonRed"><label for="pokemonRed">Red</label> <input type="radio" name="pokemon" value="Blue" id="pokemonBlue" required=""><label for="pokemonBlue">Blue</label> <input type="radio" name="pokemon" value="Yellow" id="pokemonYellow"><label for="pokemonYellow">Yellow</label></fieldset>



<fieldset class="medium-6 columns"><legend>Choose Your Favorite - not required, you can leave this one blank.</legend> <input type="radio" name="pockets" value="Red" id="pocketsRed"><label for="pocketsRed">Red</label> <input type="radio" name="pockets" value="Blue" id="pocketsBlue"><label for="pocketsBlue">Blue</label> <input type="radio" name="pockets" value="Yellow" id="pocketsYellow"><label for="pocketsYellow">Yellow</label></fieldset>



<fieldset class="medium-6 columns"><legend>Check these out</legend> <input id="checkbox1" type="checkbox"><label for="checkbox1">Checkbox 1</label> <input id="checkbox2" type="checkbox" required=""><label for="checkbox2">Checkbox 2</label> <input id="checkbox3" type="checkbox"><label for="checkbox3">Checkbox 3</label></fieldset>



</div>



<div class="row">



<fieldset class="medium-6 columns"><button class="button" type="submit" value="Submit">Submit</button></fieldset>



<fieldset class="medium-6 columns"><button class="button" type="reset" value="Reset">Reset</button></fieldset>



</div>



</form>



\* \* *



\## \[](#accordion)Accordion



\*   \[Accordion 1](#panel1d)



\    <div id="panel1d" class="accordion-content" role="tabpanel" data-tab-content="" aria-labelledby="panel1d-label" aria-hidden="true">Panel 1\. Lorem ipsum dolor</div>



\*   \[Accordion 2](#panel1d)



\    <div id="panel1d" class="accordion-content" role="tabpanel" data-tab-content="" aria-labelledby="panel1d-label" aria-hidden="true">Panel 2\. Lorem ipsum dolor</div>



\*   \[Accordion 3](#panel1d)



\    <div id="panel1d" class="accordion-content" role="tabpanel" data-tab-content="" aria-labelledby="panel1d-label" aria-hidden="true">Panel 3\. Lorem ipsum dolor</div>



\* \* *



\## \[](#accordion-menu)Accordion Menu



\*   \[Item 1](#)

\*   \[Item 1A](#)

\*   \[Item 1Ai](#)

\*   \[Item 1Aii](#)

\*   \[Item 1Aiii](#)

\*   \[Item 1B](#)

\*   \[Item 1C](#)

\*   \[Item 2](#)

\*   \[Item 2A](#)

\*   \[Item 2B](#)

\*   \[Item 3](#)



\* \* *



\## \[](#badge)Badge



<span class="secondary badge">2</span> <span class="success badge">3</span> <span class="alert badge">A</span> <span class="warning badge">B</span>



\* \* *



\## \[](#breadcrumbs)Breadcrumbs



<nav aria-label="You are here:" role="navigation">



\*   \[Home](#)

\*   \[Features](#)

\*   Gene Splicing

\*   <span class="show-for-sr">Current:</span> Cloning



</nav>



\* \* *



\## \[](#button)Button



\[Primary](#) \[Secondary](#) \[Success](#) \[Alert](#) \[Warning](#)  

<button type="button" class="success button">Save</button> <button type="button" class="alert button">Delete</button>  

\[So Tiny](#) \[So Small](#) \[So Basic](#) \[So Large](#) \[Such Expand](#)



<div class="button-group"><a class="button">One</a> <a class="button">Two</a> <a class="button">Three</a></div>



\* \* *



\## \[](#callout)Callout



<div class="callout">



\##### This is a default callout.



It has an easy to override visual style, and is appropriately subdued.



\[It's dangerous to go alone, take this.](#)</div>



<div class="callout primary">



\##### This is a primary callout



It has an easy to override visual style, and is appropriately subdued.



\[It's dangerous to go alone, take this.](#)</div>



<div class="callout secondary">



\##### This is a secondary callout



It has an easy to override visual style, and is appropriately subdued.



\[It's dangerous to go alone, take this.](#)</div>



<div class="callout success">



\##### This is a success callout



It has an easy to override visual style, and is appropriately subdued.



\[It's dangerous to go alone, take this.](#)</div>



<div class="callout warning">



\##### This is a warning callout



It has an easy to override visual style, and is appropriately subdued.



\[It's dangerous to go alone, take this.](#)</div>



<div class="callout alert">



\##### This is an alert callout



It has an easy to override visual style, and is appropriately subdued.



\[It's dangerous to go alone, take this.](#)</div>



\* \* *



\## \[](#cards)Cards



<div class="cards-container">



<div class="card">!\[](https://placeimg.com/300/200/arch)



<div class="card-content">



\#### Dreams feel real



I'm going to improvise. Listen, there's something you should know about me... about inception.



<small>Last updated 1 minute ago</small></div>



</div>



<div class="card">!\[](https://placeimg.com/300/200/nature)



<div class="card-content">



\#### Menus



Cards play nicely with menus too! Give them a try.



\*   \[One](#)

\*   \[Two](#)

\*   \[Three](#)



</div>



</div>



<div class="card">



<div class="card-divider">



Featured



</div>



<div class="card-content">



\#### Your title here!



An idea is like a virus, resilient, highly contagious. The smallest seed of an idea can grow. It can grow to define or destroy you.



</div>



</div>



<div class="card">!\[](https://placeimg.com/300/200/people)



<div class="card-content">



\#### Buttons!



Who doesn't love a good button? Buttons work in all of their forms too.



\[I'm a button](#)</div>



</div>



<div class="card">!\[](https://placeimg.com/300/200/tech)



<div class="card-content">



\#### And button groups...



Button groups also work great!



<div class="button-group"><a class="button">One</a> <a class="button">Two</a> <a class="button">Three</a></div>



</div>



</div>



<div class="card text-center">



<div class="card-divider">



Centered



</div>



!\[](https://placeimg.com/300/200/animals)



<div class="card-content">



The utility classes like .text-center work great too.



\[Click me](#)</div>



</div>



</div>



\* \* *



\## \[](#close-button)Close Button



<div class="callout"><button class="close-button" aria-label="Close alert" type="button"><span aria-hidden="true">×</span></button>



This is a static close button example.



</div>



\* \* *



\## \[](#drilldown-menu)Drilldown Menu



<div class="is-drilldown" style="min-height: 230.25px; max-width: 200px;">



\*   <a tabindex="0">Item 1</a>

\*   <a tabindex="0">Back</a>

\*   <a tabindex="0">Item 1A</a>

\*   <a tabindex="0">Back</a>

\*   \[Item 1Aa](#)

\*   \[Item 1Ba](#)

\*   \[Item 1Ca](#)

\*   \[Item 1Da](#)

\*   \[Item 1Ea](#)

\*   \[Item 1B](#)

\*   \[Item 1C](#)

\*   \[Item 1D](#)

\*   \[Item 1E](#)

\*   <a tabindex="0">Item 2</a>

\*   <a tabindex="0">Back</a>

\*   \[Item 2A](#)

\*   \[Item 2B](#)

\*   \[Item 2C](#)

\*   \[Item 2D](#)

\*   \[Item 2E](#)

\*   <a tabindex="0">Item 3</a>

\*   <a tabindex="0">Back</a>

\*   \[Item 3A](#)

\*   \[Item 3B](#)

\*   \[Item 3C](#)

\*   \[Item 3D](#)

\*   \[Item 3E](#)

\*   \[Item 4](#)



</div>



\* \* *



\## \[](#dropdown-menu)Dropdown Menu



\*   <a>Item 1</a>

\*   \[Item 1A Loooong](#)

\*   \[Item 1 sub](#)

\*   \[Item 1 subA](#)

\*   \[Item 1 subB](#)

\*   \[Item 1 sub](#)

\*   \[Item 1 subA](#)

\*   \[Item 1 subB](#)

\*   \[Item 1 sub](#)

\*   \[Item 1 subA](#)

\*   \[Item 1B](#)

\*   \[Item 2](#)

\*   \[Item 2A](#)

\*   \[Item 2B](#)

\*   \[Item 3](#)

\*   \[Item 4](#)



\* \* *



\## \[](#dropdown-pane)Dropdown Pane



<button class="button" type="button" data-toggle="example-dropdown" aria-controls="example-dropdown" data-is-focus="false" data-yeti-box="example-dropdown" aria-haspopup="true" aria-expanded="false">Toggle Dropdown</button>



<div class="dropdown-pane" id="example-dropdown" data-dropdown="" aria-hidden="true" data-yeti-box="example-dropdown" data-resize="example-dropdown" aria-labelledby="027inl-dd-anchor" data-e="sn9qgj-e" data-events="resize">Just some junk that needs to be said. Or not. Your choice.</div>



\* \* *



\## \[](#equalizer)Equalizer



<div class="grid-container">



<div class="grid-x grid-margin-x" data-equalizer="" data-equalize-on="medium" id="test-eq" data-resize="9wccx0-eq" data-mutate="rlxunc-eq" data-e="t05uji-e" data-events="mutate">



<div class="medium-4 cell">



<div class="callout" data-equalizer-watch="" style="height: 162px;">!\[](https://placeimg.com/300/200/arch)</div>



</div>



<div class="medium-4 cell">



<div class="callout" data-equalizer-watch="" style="height: 162px;">



Pellentesque habitant morbi tristique senectus et netus et, ante.



</div>



</div>



<div class="medium-4 cell">



<div class="callout" data-equalizer-watch="" style="height: 162px;">!\[](https://placeimg.com/400/100/arch)</div>



</div>



</div>



</div>



\* \* *



\## \[](#flex-video)Flex Video



<div class="flex-video"><iframe width="420" height="315" src="https://www.youtube.com/embed/V9gkYw35Vws" frameborder="0" allowfullscreen=""></iframe></div>



\* \* *



\## \[](#forms)Forms



<form><label>Input Label <input type="text" placeholder=".small-12.columns" aria-describedby="exampleHelpText"></label> 



Here's how you use this input field!



<label>How many puppies? <input type="number" value="100"> </label> <label> What books did you read over summer break? <textarea placeholder="None"></textarea> </label> <label>Select Menu <select> <option value="husker">Husker</option> <option value="starbuck">Starbuck</option> <option value="hotdog">Hot Dog</option> <option value="apollo">Apollo</option> </select></label> 



<div class="row">



<fieldset class="large-6 columns"><legend>Choose Your Favorite</legend> <input type="radio" name="pokemon" value="Red" id="pokemonRed" required=""><label for="pokemonRed">Red</label> <input type="radio" name="pokemon" value="Blue" id="pokemonBlue"><label for="pokemonBlue">Blue</label> <input type="radio" name="pokemon" value="Yellow" id="pokemonYellow"><label for="pokemonYellow">Yellow</label></fieldset>



<fieldset class="large-6 columns"><legend>Check these out</legend> <input id="checkbox1" type="checkbox"><label for="checkbox1">Checkbox 1</label> <input id="checkbox2" type="checkbox"><label for="checkbox2">Checkbox 2</label> <input id="checkbox3" type="checkbox"><label for="checkbox3">Checkbox 3</label></fieldset>



</div>



<div class="row">



<div class="small-3 columns"><label for="middle-label" class="right middle">Label</label></div>



<div class="small-9 columns"><input type="text" id="middle-label" placeholder="Right- and middle-aligned text input"></div>



</div>



<div class="input-group"><span class="input-group-label">$</span> <input class="input-group-field" type="url">



<div class="input-group-button"><input type="submit" class="button" value="Submit"></div>



</div>



</form>



\* \* *



\## \[](#grid)Grid (XY)



<div class="kitchen-sink-grid">



<div class="grid-x">



<div class="cell">full width cell</div>



<div class="cell">full width cell</div>



</div>



<div class="grid-x">



<div class="small-6 cell">6 cells</div>



<div class="small-6 cell">6 cells</div>



</div>



<div class="grid-x">



<div class="medium-6 large-4 cell">12/6/4 cells</div>



<div class="medium-6 large-8 cell">12/6/8 cells</div>



</div>



</div>



\* \* *



\## \[](#label)Label



<span class="secondary label">Secondary Label</span> <span class="success label">Success Label</span> <span class="alert label">Alert Label</span> <span class="warning label">Warning Label</span>



\* \* *



\## \[](#media-object)Media Object



<div class="media-object">



<div class="media-object-section">!\[](http://placeimg.com/200/200/people)</div>



<div class="media-object-section">



\#### Dreams feel real while we're in them.



I'm going to improvise. Listen, there's something you should know about me... about inception. An idea is like a virus, resilient, highly contagious. The smallest seed of an idea can grow. It can grow to define or destroy you.



</div>



</div>



\* \* *



\## \[](#menu)Menu



\*   \[One](#)

\*   \[Two](#)

\*   \[Three](#)

\*   \[Four](#)



\*   [<span>One</span>](#)

\*   [<span>Two</span>](#)

\*   [<span>Three</span>](#)

\*   [<span>Four</span>](#)



\* \* *



\## \[](#motion-ui)Motion UI



<div id="motion-example-1" data-toggler="" data-animate="fade-in fade-out" data-toggle="motion-example-1" class="callout secondary" aria-controls="motion-example-1" aria-expanded="true" data-e="lxgxgp-e">



This panel fades.



</div>



<div id="motion-example-2" data-toggler="" data-animate="slide-in-down slide-out-up" data-toggle="motion-example-2" class="callout secondary" aria-controls="motion-example-2" aria-expanded="true" data-e="7z48g3-e">



This panel slides.



</div>



<button type="button" class="button" data-toggle="motion-example-1" aria-controls="motion-example-1">Fade</button> <button type="button" class="button" data-toggle="motion-example-2" aria-controls="motion-example-2">Slide</button>



\* \* *



\## \[](#orbit)Orbit



<div class="orbit" role="region" aria-label="Favorite Space Pictures" data-orbit="" data-resize="92g2yj-orbit" id="92g2yj-orbit" data-e="pzhsmj-e" data-events="resize">



<button class="orbit-previous" aria-label="previous" tabindex="0"><span class="show-for-sr">Previous Slide</span>◀</button>



<button class="orbit-next" aria-label="next" tabindex="0"><span class="show-for-sr">Next Slide</span>▶</button>



\*   <div>



\### You can also throw some text in here!



\    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde harum rem, beatae ipsa consectetur quisquam. Rerum ratione, delectus atque tempore sed, suscipit ullam, beatae distinctio cupiditate ipsam eligendi tempora expedita.



\### This Orbit slide has chill



\    </div>



\*   <div>



\### You can also throw some text in here!



\    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde harum rem, beatae ipsa consectetur quisquam. Rerum ratione, delectus atque tempore sed, suscipit ullam, beatae distinctio cupiditate ipsam eligendi tempora expedita.



\### This Orbit slide has chill



\    </div>



\*   <div>



\### You can also throw some text in here!



\    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde harum rem, beatae ipsa consectetur quisquam. Rerum ratione, delectus atque tempore sed, suscipit ullam, beatae distinctio cupiditate ipsam eligendi tempora expedita.



\### This Orbit slide has chill



\    </div>



\*   <div>



\### You can also throw some text in here!



\    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde harum rem, beatae ipsa consectetur quisquam. Rerum ratione, delectus atque tempore sed, suscipit ullam, beatae distinctio cupiditate ipsam eligendi tempora expedita.



\### This Orbit slide has chill



\    </div>



<nav class="orbit-bullets"><button class="" data-slide="0"><span class="show-for-sr">First slide details.</span></button> <button data-slide="1" class=""><span class="show-for-sr">Second slide details.</span></button> <button data-slide="2" class="is-active"><span class="show-for-sr">Third slide details.</span><span class="show-for-sr">Current Slide</span></button> <button data-slide="3"><span class="show-for-sr">Fourth slide details.</span></button></nav>



</div>



\* \* *



\## \[](#pagination)Pagination



\*   Previous <span class="show-for-sr">page</span>

\*   <span class="show-for-sr">You're on page</span> 1

\*   \[2](#)

\*   \[3](#)

\*   \[4](#)



\*   \[12](#)

\*   \[13](#)

\*   [Next <span class="show-for-sr">page</span>](#)



\* \* *



\## \[](#progress-bar)Progress Bar



<div class="success progress" role="progressbar" tabindex="0" aria-valuenow="25" aria-valuemin="0" aria-valuetext="25 percent" aria-valuemax="100">



<div class="progress-meter" style="width: 25%">



25%



</div>



</div>



<div class="warning progress">



<div class="progress-meter" style="width: 50%">



50%



</div>



</div>



<div class="alert progress">



<div class="progress-meter" style="width: 75%">



75%



</div>



</div>



\*\*Native progress:\*\* As an alternative to our custom progress bar style, you can also opt to use the native `<progress>\` element. It provides a more succinct way to create progress bars, but it's not supported in IE9, and some other older browsers. [View \`<progress>` element support.](http://caniuse.com/#feat=progress)



\*\*Native meter:\*\* For the \_extra\_ adventurous developers out there, we also provide styles for the `<meter>\` element. What's the difference? \`<progress>\` represents a value that changes over time, like storage capacity. \`<meter>\` represents a value that fluctates around some optimum value. It also has \_no\_ support in Internet Explorer, Mobile Safari, or Android 2\. [View \`<meter>` element support.](http://caniuse.com/#search=meter)



\* \* *



\## \[](#reveal)Reveal



<a data-open="exampleModal1" aria-controls="exampleModal1" aria-haspopup="true" tabindex="0">Click me for a basic modal</a>



<a data-toggle="exampleModal8" aria-controls="exampleModal8" aria-haspopup="true" tabindex="0">Click me for a full-screen modal</a>



\* \* *



\## \[](#slider)Slider



<div class="slider" data-slider="" data-initial-start="50" data-end="200" data-e="i3igqu-e"><span class="slider-handle" data-slider-handle="" role="slider" tabindex="0" aria-controls="s6k46j-slider" aria-valuemax="200" aria-valuemin="0" aria-valuenow="50" aria-orientation="horizontal" style="left: 24.34%;"></span><span class="slider-fill" data-slider-fill="" style="width: 25%;"></span><input type="hidden" id="s6k46j-slider" max="200" min="0" step="1" value="50"></div>



<div class="slider vertical" data-slider="" data-initial-start="25" data-end="200" data-vertical="true" data-e="32dkcn-e"><span class="slider-handle" data-slider-handle="" role="slider" tabindex="0" aria-controls="lldjvk-slider" aria-valuemax="200" aria-valuemin="0" aria-valuenow="25" aria-orientation="vertical" style="top: 11.54%;"></span><span class="slider-fill" data-slider-fill="" style="height: 13%;"></span><input type="hidden" id="lldjvk-slider" max="200" min="0" step="1" value="25"></div>



\*\*Native range slider:\*\* In Foundation 6.2, we introduced styles for `<input type="range">`, the native HTML element for range sliders. It's not supported in every browser, namely IE9 and some older mobile browsers. \[View browser support for the range input type.](http://caniuse.com/#feat=input-range)



<input type="range" min="1" max="100" step="1">



\* \* *



\## \[](#switch)Switch



<div class="switch tiny"><input class="switch-input" id="tinySwitch" type="checkbox" name="exampleSwitch"> <label class="switch-paddle" for="tinySwitch"><span class="show-for-sr">Tiny Sandwiches Enabled</span></label> </div>



<div class="switch small"><input class="switch-input" id="smallSwitch" type="checkbox" name="exampleSwitch"> <label class="switch-paddle" for="smallSwitch"><span class="show-for-sr">Small Portions Only</span></label> </div>



<div class="switch large"><input class="switch-input" id="largeSwitch" type="checkbox" name="exampleSwitch"> <label class="switch-paddle" for="largeSwitch"><span class="show-for-sr">Show Large Elephants</span></label> </div>



\* \* *



\## \[](#table)Table



<table>



<thead>



<tr>



<th width="200">Table Header</th>



<th>Table Header</th>



<th width="150">Table Header</th>



<th width="150">Table Header</th>



</tr>



</thead>



<tbody>



<tr>



<td>Content Goes Here</td>



<td>This is longer content Donec id elit non mi porta gravida at eget metus.</td>



<td>Content Goes Here</td>



<td>Content Goes Here</td>



</tr>



<tr>



<td>Content Goes Here</td>



<td>This is longer Content Goes Here Donec id elit non mi porta gravida at eget metus.</td>



<td>Content Goes Here</td>



<td>Content Goes Here</td>



</tr>



<tr>



<td>Content Goes Here</td>



<td>This is longer Content Goes Here Donec id elit non mi porta gravida at eget metus.</td>



<td>Content Goes Here</td>



<td>Content Goes Here</td>



</tr>



</tbody>



</table>



\* \* *



\## \[](#tabs)Tabs



\*   \[Tab 1](#panel1)

\*   \[Tab 2](#panel2)

\*   \[Tab 3](#panel3)

\*   \[Tab 4](#panel4)

\*   \[Tab 5](#panel5)

\*   \[Tab 6](#panel6)



<div class="tabs-content" data-tabs-content="example-tabs">



<div class="tabs-panel is-active" id="panel1" role="tabpanel" aria-labelledby="panel1-label">



One



Check me out! I'm a super cool Tab panel with text content! On medium-down screen sizes, this component will transform into an accordion.



</div>



<div class="tabs-panel" id="panel2" role="tabpanel" aria-labelledby="panel2-label" aria-hidden="true">



Two



!\[](http://placeimg.com/200/200/arch)</div>



<div class="tabs-panel" id="panel3" role="tabpanel" aria-labelledby="panel3-label" aria-hidden="true">



Three



Check me out! I'm a super cool Tab panel with text content!



</div>



<div class="tabs-panel" id="panel4" role="tabpanel" aria-labelledby="panel4-label" aria-hidden="true">



Four



!\[](http://placeimg.com/200/200/arch)</div>



<div class="tabs-panel" id="panel5" role="tabpanel" aria-labelledby="panel5-label" aria-hidden="true">



Five



Check me out! I'm a super cool Tab panel with text content!



</div>



<div class="tabs-panel" id="panel6" role="tabpanel" aria-labelledby="panel6-label" aria-hidden="true">



Six



!\[](http://placeimg.com/200/200/arch)</div>



</div>



\* \* *



\## \[](#thumbnail)Thumbnail



<div class="row">



<div class="small-4 columns">!\[Placeholder image.](http://placeimg.com/200/200/nature)</div>



<div class="small-4 columns">!\[Placeholder image.](http://placeimg.com/200/200/nature)</div>



<div class="small-4 columns">!\[Placeholder image.](http://placeimg.com/200/200/nature)</div>



</div>



\* \* *



\## \[](#title-bar)Title Bar



<div class="title-bar">



<div class="title-bar-left"><span class="title-bar-title">FoundationPress</span></div>



</div>



\* \* *



\## \[](#toggler)Toggler



<button class="button small primary" type="button" data-toggle="menuBar" aria-controls="menuBar">Toggle width</button>



\*   \[One](#)

\*   \[Two](#)

\*   \[Three](#)

\*   \[Four](#)



\* \* *



\## \[](#tooltip)Tooltip



The <span data-tooltip="" aria-haspopup="true" class="has-tip" data-disable-hover="false" tabindex="1" title="" aria-describedby="493equ-tooltip" data-yeti-box="493equ-tooltip" data-toggle="493equ-tooltip" data-resize="493equ-tooltip" data-e="l0o1x5-e" data-events="resize">scarabaeus</span> hung quite clear of any branches, and, if allowed to fall, would have fallen at our feet. Legrand immediately took the scythe, and cleared with it a circular space, three or four yards in diameter, just beneath the insect, and, having accomplished this, ordered Jupiter to let go the string and come down from the tree.



\* \* *



\## \[](#top-bar)Top Bar



<div class="top-bar">



<div class="top-bar-left">



\*   Site Title

\*   \[One](#)

\*   \[One](#)

\*   \[Two](#)

\*   \[Three](#)

\*   \[Two](#)

\*   \[Three](#)



</div>



<div class="top-bar-right">



\*   <input type="search" placeholder="Search">

\*   <button type="button" class="button">Search</button>



</div>



</div>



\* \* *



\## \[](#visibility-classes)Visibility classes



<div class="visibility-classes">



You are on a small screen or larger.



You are on a medium screen or larger.



You are on a large screen or larger.



You are \_definitely\_ on a small screen.



You are \_definitely\_ on a medium screen.



You are \_definitely\_ on a large screen.



You are \_not\_ on a medium screen or larger.



You are \_not\_ on a large screen or larger.



You are \_definitely not\_ on a small screen.



You are \_definitely not\_ on a medium screen.



You are \_definitely not\_ on a large screen.



Can't touch this.



Can sort of touch this.



You are in landscape orientation.



You are in portrait orientation.



This text can only be read by a screen reader.



There's a line of text above this one, you just can't see it.



This text can be seen, but won't be read by a screen reader.



</div>



\* \* *



</article>
