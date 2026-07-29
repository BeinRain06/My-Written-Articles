## medium.com

## article : Font-size automated in your website

<br/>

### Introduction

Most of the time. A bunch of us glimpse at typography when we are about to proceed with a new website project.

We choose one or two font-size online, bring them right in our project, and globally include their style. We presume we are all fit for basic settings: next, adding code at a steady scale, matching contents on a specific context, simulating and reviewing the result on screen.

From school and self-taught learning we have mastered the art of writing. So we already decided it was trivial to emphasize over text any longer. However modern design appointments start with that push back principle : typography. More steady to observe than colors, layout, or contrast. Bringing clarity, readability and simplicity at the core essence of their presence.

Because this subject is almost every time laid aside on our progress decisions to build something. The rising concerns live on the **_methods_**, **_tips_** and **_processes_** that will assist to deliver fast and professional designs that will synchronize over many media screens.

<br/>

### I/ HTML Tree And attribute Classes Structure

HTML programming Language lays out the **foundation** of a Document Object Model. It helps organize syntax of an entire website from top container to specialized tags down to the lines returning simple texts.
Alongside with CSS Styling is ensure a neat and composed rendering of the visual layouts where style apply in the HTML Document via the attribute labeled : class. Where different instance names are inserted. With each one of them having the potential to carry traits that shape the course of their look alike. For instance in css : **.hero\_\_section** {width: 100vw; height: 100vh} // with _hero\_\_section_ is an inserted name.

Developers and Designers rooting in the IT Field easily acquired understanding of the HTML Concepts. But they struggle the most to write styles that cross painless resistance as screen size changes enter the room. At the expense of their sweat, box by box, section to section, project to project. They learn that **style is not a fashionable mix that we just add randomly throughout an entire website**. It deserved a structure to lean on . So it could obey resizing from large to small devices screens.

<br/>

#### I-1/ HTML Tree Structure Example

Let’s analyze the following code snippets :

// code insert

```html
<section id="project_based" class="project__landscape">
  <div class="project__container">
    <div class="project__content">
      <!-- project cards -->
      <div id="project__card-1" class="project__card">
        <!-- image -->
        <div class="project__img">
          <img
            href="../assets/project-one.png"
            class="project__profile"
            alt="blow my mind"
          />
        </div>
        <!-- description -->
        <div class="project__text">
          <h3 class="project__title">Green Plants</h3>
          <div class="project__description">
            <p>
              Revive lost ecosystems, planting ten thousands trees across the
              major streets of the country. Join us to rejuvenate our cities
              where we always felt inspired growing up with natural and soothing
              blowing air.
            </p>
          </div>
          <a href="#" class="project__btn">more infos</a>
        </div>
      </div>
    </div>
  </div>
</section>
```

<br/>

Where the card inside, includes a text and image waiting to be styled. The card dwells under a section with a class name of **_project\_\_landscape_** that holds one child, **_project\_\_container_** that also has a couple of descendants.

#### I-2/ The “ROOM” SET

The first two ancestors of any significant layout of an HTML Syntax (main wrappers, sections, cards, …) can be identified as bold, and reckless warriors. They conquer lands (“spacing”) and rule the tribe (“orientation”). They are not just figures, they are head without whom, the tribe will barely survive from the external threatening and attacks of other nations.

**_project\_\_landscape_** and **_project\_\_container_** are the first two direct tags of the lineage in our HTML Tree code syntax before.

The “project\_\_landscape” sets the width, margin, and eventually the height of their content, so the work can begin under strict boundaries (the development).

While “project\_\_landscape” is a man fit for war. On the other side the “project\_\_container” is the ruler. He writes down the vision, redact and publishes laws with the help of a selected minded-team.

Here is the domain of adjusting or shaping internal spacing such as padding, margin so the parent container and their incoming children in the house can breathe and kmnows their lanes.

#### I-3/ The “CONTENT” Administration

After setting limits of lands and actions. Tags that follow the lines are the executive. They rule not only by words, but by force when necessary. They ensure citizens understand and internalize their boundaries in society.

The designated governor in our card is “project\_\_content”. Along with his next children in the tree. They rule immediately by setting vivid directions either on horizontal or vertical axes using :

- float
- flexbox
- grid

<br/>

Next to “project\_\_content”, stands “project\_\_card” that is more like a right hand. He is more strict and implied to use force.

- flexbox, or grid
- spacing (margin, padding)
- gutters (gap)

<br/>

From then, moving on there are **businesses owners** or **contractors** like :
“project\_\_img” or “project\_\_text”. They have to respect the instruction sets and make people under their responsibilities (“project\_\_profile”, “project\_\_title”, project\_\_description) doing so. So they won’t be given penalties and even worse remove their operating license.

<br/>

While we use so many recognizable and tangible administrative analogies, we aim to plant the seed of how modular automation of any HTML or JSX components you are in favor to write really works under the hood. So, then every piece of code from the first moment you initiate the project should be perceived as a drive to realize a fulfilling responsive website.

<br/>

### II/ CSS Units - Running our Web Design

The Goal of automating text and spaces between text, is one of the traditional drives that escape the mind of craftsmanship of websites. They navigate around CSS units as if they have mastered it since, from courses or tutorials they have been learning for.

They look at units as a conciliating personal preference. selecting fewer font-families online, checking their style appearances, and moving forward to onboard them in their project. Neglecting the pre-requisites that if well known might transform fundamentally the ways they proceed fluid design.

### II-1 CSS Units

There are two kinds of length units in CSS :

Absolute Units (cm, px, pica, …)
Relative Units (rem, em, vw, …)

**The absolute unit** that provides a precise and fixed size for the element they are applying to.

**The relative unit**, unit of length that might depend on the font-size of the element itself or its parent. The size(width) of the parent or the window of the browser where your website is rendered (viewport).

And quite largely pronounced, there are more than 40 measurement units unders CSS specification with literally just a couple ones that are particularly good to utilize in web design, the rest being fit for others type of products like flyers, logos, figure illustration and more …

Some of the units that can resort for design are illustrated below :

**1.pixel (px)**

**px** is registered as an absolute CSS length. It doesn’t change its size on different devices and screens. Though, in practice, this isn’t absolutely the truth. But trust me this found an entire topic worth a new debate, though it won’t hinder and fade your appreciation of how it works and how to implement it inside a project.

px unit is the foundation of the web unit. A unit on which each device and screen has been taught how to deal with characters and images to display. The most familiar for anyone, which has likely ever used an electronic device (smartphone resolution,...). The difficulty it opposes against change of its dimension across multiple screens, is the cause of its clear out as a unit that could handle text on entire websites.
On a practical level. Px are used for logos, icons, profiles in testimonials where less modification are required. Each time you are clicked to develop with px ask yourself if the element you are on your way to style will not command many changes.

**2.root element (rem)**

**rem** represents the relative unit that value depends on the default root element (<html>) font-size. You can view and change the default font in the settings of your browser if needed (common default font-size 1rem = 16px).

rem is not so rough as px does. rem will not change size on its own just by shrinking or stretching the browser window. But you can rather variate the default size (e.g : 1rem = 20px) if desired and a fresh appearance of the website or implement soft media-queries on your code to have rem respond receptively.

**element (em)**

**em** refers to a relative unit that changed based on the font-size of the element it is applying to, except the em css property is used for the font-size on its own. When it is the case , the em should be tied to the font-size of its nearest parent element that possesses a font-size set.

Let’s look at how it works :

```html
<div class="card__text">
  <h3 class="card__title">Underneath the Blue Sea</h3>
  <div class="card__description">
    <p class="card__paragraph">
      <!-- // content -->
    </p>
  </div>
</div>
```

Imagine card\_\_paragraph with a padding of 2em (padding: 2em). Where no font-size is internally set to the element. The real measurement of the padding will be calculated from the font-size of the nearest parent that has an available one set.

If on the other hand card\_\_paragraph holds an inner font-size. The padding will be a reflection of the actual value of that font-size.
e.g :
font-size : 1.75rem (1.75\*16px = 28px)

then the padding : 2em (2\*28px = 56px)

While this allows texts to shrink or stretch as their container width changes, they can result in confusing and messing design if a bunch of the font-sizes in a lineage are set to em. To have a real measurement we will jump from parent to parent without control and em in one text will not be the same with another. A collection of different will arises in the DOM (Document Object Model) surfacing irregularity and inconsistency of the text involved for example for paragraph or link, …

em looks more elegant to utilize in padding, margin of blocks of text. Such as buttons, cards, or box containers. Where spacing appears more like a caliber to adjust.

**percentage (%)**

**Percentage** or **%** is a relative unit that stretches or shrinks according to the width of its direct parent container. if width equals 100%, the element will inherit the full width of its parent, 70% It will inherit a little more than the two-third (⅔) of the parent width.

Percentages are a real match to accomplish dynamic containers from various screens devices. And hold a lot of importance when layering out media-queries in a project. But also css properties like : top, bottom, left, right benefits of a lot of responsiveness when aligned in %.

**character (ch)**

**ch** is a bit particular than the others. Its measurement is relative to the width of the “0” character of the font-family set.

Experienced UX designers know that a text from inside an html tag has to range between 45-75 characters space included per single row line in a website. So the eyes are not constrained and the focus pushes away swinging neck left to right every time we read the content.

ch unit has yet the power to fix borders and limits to containers. Ensuring max-width is tailored to give an unique and pleasant experience to drive the emotions of the users.

**ex**

**ex** is an alive unit also looking pretty much the same than ch. Except its value is rather based on the height of the “x” character of the font-family set. This is an alternative to set boundaries like max-width or better max-height. And may be expressed when dealing with fixed containers.

### II-2 Units Union - For Flexibility

From personal learning I discovered many developers in the industry create new types of units based on the available ones, especially for flexibility. They allow a mix of units to be expressed together on such property like font-size, gaining traction on responsiveness.

Let’s unfold some of these in the next lines :

**a/ rem and vw**

By the use of the **“vw”** unit you grab a percentage of the viewport width (1vw = 1% of the browser window). **“rem”** on the other side offers a standard font-size for medium media screen. So by mixing the two of them you can achieve font-size that are extensible and well adapted to large screen media and also one that could easily support shrink constraints on much smaller ones. This opening control of the edges of website super cool and reliable for users reaching out to your solutions using many different kinds of devices.

For example :

```css
@media screen and (min-width: 1060px) {
  p {
    font-size: calc(1.25rem + 0.12vw);
  }
}
```

<br/>

**b/ rem and vh**

**“vh”** unit on the other side, takes a percentage of the viewport height so it could establish change. It is undoubtedly one I skipped a lot and most frankly never used. But lately, I figured out it could be one of the most tailored for texts in mobile phones devices. When associated with the **“rem”** unit, the different size in height from phones to phones instantly stimulate adaptability of text over the media. This interconnection corrects the visual text ensuring it stays large or small enough to fit the screen.

Example :

```css
@media screen and (max-width: 60ch) {
  p {
    font-size: calc(1.05rem + 0.26vh);
  }
}
```

<br/>

**c/ clamp in css**

clamp is not a CSS unit but rather a property in CSS. It operates three different font-sizes evaluating which one collapse the most effectively with the current size of there parent container.

These three values are :

**A Min Value** : When the container shrinks at a level where the font-size is squeezed a lot.

**A Preferred Value** : The default value that will be applied if the text has a few spaces to breathe.

**A Max Value** : When the container holds enough space that the text is in need.

An example of use can be :

```css
@media screen and (min-width: 75ch) {
  p {
    font-size: clamp(1.05rem, 2.5vw, 2rem);
  }
}
```

<br/>

**d/ dvh, svh, dvw, svw**

dvh (dynamic viewport height) or svh (small viewport height) might be used to set height of particular container in mobile

For e.g : hero-section { height: 100 dvh }

dvw (dynamic viewport width) or svw (small viewport width) waving in mobile queries as container width

e.g : project-section {width: 100 dvw}

<br/>

### III/ The Drawbacks we are Subconsciously Taken To

A lot of folk, as I did, consider live web projects they have decided to build, as a forwarded instrument to impress acquaintances, friends, and eventually potential clients they could reach. They spent hours finding the perfect colors, fancy images that don't characterize the brand. They pay too much attention to animations.

The truth is, Design in itself is a craft. An experiment, a carved idea that doesn’t completely ought to be sophisticated all at once. From the first sample though, deeply intentional with concise texts aside images that illustrate the pin points embarrassments or the joyful outcomes that may come out of it.

#### III-1 Personal Experience

I recall this project built from scratch without FIGMA Tool. Wireframes drafted on papers. Then carrying the duty on with code.

The soul of the project revolved around **services in real estate** to offer to people who have a desire to concretize their house with their own fundings.

The project included three pages :

- Landing Page
- Project Page
- Contact Page

Under the Landing page emphasizing core value and most clear benefits from the solution. I developed 8 sections among which the “hero” and the “project list” ones. While I was able to communicate **global style** for text (paragraph, title, links, button). I struggled to make this style respond to both sections. On desktop the layout was well served, but moving to tablet or phones the text and even images of these sections crumbled into mess. The issue stuck on me for hours, with the relentless question echoing in my mind : **_“How can i address this problem properly ?”_**. Then, I finally found it easy to add local styled modifications in the current LandingPage.css file.

Since that moment, I taught myself a harsh lesson. Font-size in a website is not a careless subject to look out for.

Down, the next lines present two nicely wrapped safeguard bridges to implement and explore each time neither high or low fidelity wireframe (e.g : in Figma Tool) wasn’t involved in the process before coding. Just a previous collection of drawn sketches.

#### III-2 Global Automated Text

Either you are initiating wireframes for your web design in Figma or directly coding from drafts made on papers. The results can take one of the two roads we are going to mention. First: **“You like it so much !”** and **_die for it!_** The second: **“You assess the outlook and the voice you are leading”** so the challenge cultivated aftermath helps refine the product.

Automated design neither comes from random wasted code on every single mapped page of a website or a little adjustment of global styled variables. It holds onto identifying which principles of design suffer the most at the stake of responsiveness, capable of being transformed as styled variables that could impact all pages of a website project all at once. Like a switch to turn on/off the light in the room. So spacing and layout becomes seamless and easier to upgrade for multiple screens.

Any web project initialized, generate a global CSS file (commonly named “main.css” or “style.css”). A file where changes indented inside will echo on every page (or component) of the website via specific labelling.

**Automating text** can be quite useful if you understand **how it works**, and how personalized or commercialized websites approach the concept of **reusable components**.

The challenge is, builders don't always value the use of steady variables in the automation process. They just look tag related text one after another and run randomly font-size that changes from one breakpoint to another without scale. Ending up losing hours trying to match changes to every board available for their visual test as we underlined in part III-1.

Therefore let’s look at some regular elements of HTML most commonly involved to bear text, before wrapping the phase that will get them automated properly :

**A/ Title Tags**

- headlines (h1 … h6) : Font-size, line-height, margin (optional)

**B/ Text Oriented Tags**

- paragraph (p)
- list element (li)
- link (a)
- button (button)
- span (span)
- label (label)
- Input/textarea (input/textarea)

Mostly css targeted properties : font-size, line-height, padding.

<br/>

### IV/ The Font-Size Automation Pavement Of Your Website

Quite enough developers start any project with huge confidence around font-size requirements. Since back in school, they used to take notes, write dozens of essays, and assess hundreds of homework assignments. And at the kick, even pass exams.

Reading and writings were the way to go and fulfill all these assessments. Then moving forward : _“It can’t be too different using digital devices, where we literally repeat the same pattern just composing well and willingly enough images and text all together.”_

While it can get true that specific sized notebooks and workbooks were the references for assignments and notes in school. On the net, there are **multiple websites** that have to be displayed on **several devices**. There is more than one _pack of pages_ for _packs of different devices_. Each one with its own characteristics where among the evident one lie : width, height, and screen resolution. Factors named ones but that constantly take changes.

So removing the lent glasses and watching clearly, we can see and sense texts on virtual devices aren’t what they used to be noticeably on paper sheets. What we needed it to be. The essential part we could have said we **mastered** over **time and exposure**.

Now, it is more like a special pencil to craft, so scripture stays readable and consistent to outline the vigorous messages support by a team.

#### IV-1 Font-Size Automation Process

Not all HTML’s tags play the same role and are written without a structural hierarchy. Some are nice to shape boxes and containers. While others prevail to accommodate texts, such as :

**A/ Simple Text**

- paragraph (p)
- span (span)
- list element ()li

**B/ Button**

- link (a)
- button (button)

**C/ Title**

- h1 ... h6

**D/ Form**

- label (label)
- input (input)

Let’s picture one organization inside a website :

// The whole Depicted Situation

- 02 links buttons (secondary, primary -- **a**)
- Hero title ( **h1**)
- Section Title (**h2**)
- Box title (**h3**)
- particular text emphasis (**h4**)
- benefits listings (**li**)
- content (**p**)
- portion of content (**span**)
- form (**input**, **label**)
- footer_link (**a**)

The procedure to automate these variables call for a proper settings under the main css file (main.css or style.css) like instance :

// main.css

```css
body {
  width: 100vw;
  margin: 0;
  color: var(--text-paragraph);
  background-color: var(--background-primary);
  font-family: "Noto Sans", sans-serif;
  font-optical-sizing: auto;
  font-size: 1.25rem; /* 20px */
  font-weight: 400;
  font-style: normal;
  font-variation-settings: "wdth" 100;
}

h1,
h1 span {
  font-size: var(--hero-title-size);
  font-weight: 900;
  line-height: 1.35;
}

h2 {
  font-size: var(--title-size);
  font-weight: 800;
  line-height: 1.45;
}

h3 {
  color: var(--title-color);
  font-size: var(--title-size);
  font-weight: 700;
  line-height: 1.5;
  opacity: 0.93;
}

h3.highlighted__h3 {
  color: var(--highlight-text);
}

h4 {
  font-size: var(--subtitle-size);
  font-weight: 700;
  line-height: 1.5;
}

h5 {
  font-size: var(--mid-size);
  font-weight: 300;
  line-height: 1.35;
  letter-spacing: 1px;
}

p {
  font-size: var(--regular-size);
  line-height: 1.6;
}

p.smaller__p {
  font-size: var(--mid-size);
  font-weight: 300;
  line-height: 1.6;
}

li.navlink__item,
li.navlink__item-language {
  font-size: var(--cater-size);
  font-weight: 300;
  line-height: 1.6;
}

li.navlink__mobitem-language {
  font-size: var(--regular-size);
  font-weight: 300;
  line-height: 1.6;
}

span {
  font-size: var(--regular-size);
  font-weight: 300;
  line-height: 1.6;
}

label {
  font-size: var(--mid-size);
  font-weight: 300;
  line-height: 1.6;
  opacity: 0.82;
}

span.smaller__span {
  font-size: var(--cater-size);
  font-weight: 300;
  line-height: 1.6;
}

a {
  text-decoration: none;
  padding: 0.46em 1.25em;
  font-weight: 400;
  line-height: 1.5;
}

a.nav_link {
  width: max-content;
  font-size: var(--mid-size);
  font-weight: 300;
  line-height: 1.6;
}

a.cta__button-link {
  font-size: var(--regular-size);
  line-height: 1.6;
}

a.cta__button-primary {
  position: relative;
  color: var(--accent-color-1);
  background-color: var(--title-color);
  font-size: var(--mid-size);
  font-weight: 600;
  line-height: 1.5;
  border-radius: 1.5rem;
  z-index: 5;
}

a.cta__button-secondary {
  position: relative;
  width: max-content;
  padding: 0.25em 0.1em;
  color: var(--highlight-text);
  font-size: var(--mid-size);
  font-weight: 600;
  line-height: 1.5;
  opacity: 0.5;
  border-bottom: 1px solid var(--highlight-text);
  z-index: 5;
}

input::placeholder,
textarea::placeholder {
  font-size: var(--mini-size);
  font-weight: 400;
}

input {
  width: 100%;
  height: 2.5rem;
  padding: 0.25rem 0.5rem;
  font-size: var(--cater-size);
  border-radius: 0.25rem;
  border: 1px solid var(--accent-color-2);
  outline: none;
}

textarea {
  width: 100%;
  height: 6rem;
  padding: 0.25rem 0.5rem;
  font-size: var(--cater-size);
  border-radius: 0.25rem;
  border: 1px solid var(--accent-color-2);
  outline: none;
}
```

From the tracked code above. A natural **outfit** spacing property for text lift out : **line-height**. One always inserted _aimlessly_, without any _ratio_, and _rhythm_ between text elements of different orders (titles, paragraphs, …). Shutting **alignments and texts hierarchy recognition**. While exaggerating the use of padding and margin to do close to close spacing between paragraphs.

The line-height subject is another part of the discussion that won’t entirely get in our development. But we wanted to point it out, so in time of text grouping there is a better understanding of what can render typography spacing efficiently without a first external grip of help.

<br/>

#### IV-2 The Boost Experiment

You don’t actively write code for yourself , or even to exhibit an unhealthy style. You write for a challenge of what you already know or are eager to test.

I crafted a website to supply services for people in need to build their own house. I walked through the code and built essentially three main pages : welcome page, project page, contact page. They were rendering nicely on the desktop screen, particularly on my laptop screen. Unfortunately when i tried to manipulate the browser dev tools and then visualize how the whole renders over small desktops screen. Hold on for minutes! … The website story becomes a nightmare right on a shining and sunny day. The font-sizes, the pages' sections, the page to page appearance, all were choking in pain as I was running through small resolution screens not even yet on tablets, not even yet on phones. So earlier enough that, it dismantled the hope I had. I was aware i will collect gravel on roads but I wasn't expecting so much friction.

The Boost Experiment.

You will no longer treat your project as a whole entity at first. But pieces of components to experiment and start with, before gravitating your full attention to it.

Testing layouts visual of specific components that carry the backbone and emotional anchor of your website. So these ones conquer all the breakpoints you have selected and assume for the project, until responsiveness becomes clear all from desktop landscapes to mobile ones.

**1/ Navbar**

The Navbar is the gatekeeper of a party you have planned a long time ago and now are inviting people to celebrate with you. It doesn’t have to be badging or unfiltering, seeking too much interest. It exceptionally doesn’t have to cause fuss, while in presence of the V.I.P guests, curious enough to show up to your event. By convenience, it requires a simple UI, while dynamically being deeply functional.

**2/ Footer**

The Footer section summaries all the important links from where users could move to. And are really needful to draw terms of privacy safety net contract claims through which both the clients and the owners are protected in case the agreement fails short in some way.

**3/ Hero**

One of the most important sections of a website, if not the first one is, the hero section.

No one will pay attention to a creepy website more than 12s, except this one light to help for review, or just replicate your solution for its own good. The mirror of your website is the **hero section**. It qualifies the part of the UI that visitors explore and analyze the most before giving a green light to evaluate your solution deeper. And one best way to avoid people thinking down of your website is to really achieve the utmost to generate an emotionally connecting and attractive hero section.

It is the first section of the first landing page that people will see when browsing over your website. The one almost everyone reaching for your solution won’t miss from their two wide opened eyes. Failing to cleverly depict an **outstanding mood** out of it, could badly influence users' assumptions on what the rest of your content will presumably look like. Suggesting _amateurism_, _uncertainty_, and _pushing people to leave_ without saying Good Bye!

**4/ Mission or About Section**

This section all depends on the orientation of the **core value** of your website. Its role here is to guide your sense on how sections that overlap, render next to each other, and add **general spacings** (padding, margin). To achieve well connected parts that characterize the beauty of the entire and glamorous solution.

This experiment holds great insights so the will to adapt global variable units for screens for several devices already carry a basement that works utterly for _04 unquestionable_ and _accomplished components_.

<br/>

#### IV-3 Embedded CSS Framework Tools

It sounds swift, straightforward, and less complex to start writing in "localized style files” rather than in the “global style file”. But it’s not really an agile and smart move. Most effective is to delocalize a bunch of instructions in the main global style file. And create what we can fiercely named as the “basement” of your entire spacings and text sizes. It costs deeply when you strive to reinvent the wheel. Hard coded css properties, random sections spacings, repeated confident syntaxes. This was **the domain** when websites were the _focus of the online marketplace_. Alone beautiful UI were leading, convincing and conclusive. Now the playland has shifted to **conversion rate**. Websites that make fairly enough leads generation or traffic of clients are considered profitable.

If any website you craft, multiples hours bent on seat, debugging, customizing, adding animations and dynamic functions doesn’t even land a single client. It won’t matter how much effort you put on perfecting style, from simple text element, section, and pages to pages. The waste of time will not be retrieved, as long as it has **prioritized** a process that no longer remains in play in the game. Moreover, you can neither wait until you master CSS in full (100%), before minding to settle for embedded CSS frameworks such as for instance : **Bootstrap** or **Tailwind**, which one of the evident advantages is their utilities added over HTML or JSX tag as if it is **built-in attributes**.

Let’s look to an example :

// with tailwindCSS

```html
<div class="card__container flex flex-col md:flex-row">
  <div class="card__img">
    <!-- image -->
  </div>
  <div class="card__description">
    <!-- description -->
  </div>
</div>
```

<br/>

**flex** : means the _card\_\_container_ is a flexbox.
**flex-col** : _flex-direction_ property is set to **column**.
**md:flex-row :** when the viewport width of screen is **_>= 768px_** the _flex-direction_ property change to **row**.

All these utilities act like _sub-attributes_ of the attribute **class** of _card\_\_container_

// with Bootstrap

```html
<div class="card__container col-12 col-md-7 d-flex flex-column flex-md-row">
  <div class="card__img">
    <!-- image -->
  </div>
  <div class="card__description">
    <!-- description -->
  </div>
</div>
```

<br/>

**d-flex** : _card\_\_container_ is a flexbox.
**flex-column** : _flex-direction_ property set to **column**.
**flex-md-row** : viewport width of screen **_>= 768px_** the _flex-direction_ property change to **row**.
**col-12** : entire width size (native 12 Grid-System)
**col-md-7** : 7/12 of entire width size (native 12 Grid-System) when a media or screen display **_>= 768px_**

<br/>

#### IV-4 Elaborate Your Spacing

**Margin**, **padding**, and **gutters** (gap) are essential css properties that interestingly help to appreciate if a text is well adjusted inside its container.

Anytime builders first start engaging with frameworks like BootstrapCSS or TailwindCSS they consistently chain margin and padding blindlessly over HTML tags. Without any scale-ratio, any identifier, and logic map in mind of how they want the entire website to be seen. By the time readers’ eyes assess one solution online. Their brains subconsciously try to form **patterns of recognition** between all the content that is spilled over the screen. Watching from colors, sections spacing, to text hierarchy. And any familiarity of scale between all these text and layout will inherently suggest intention, trust, professionalism. The solution will be remembered even after closing the site. And eventually build enough trust to lead people back to your services or offers when necessary.

Spacing particularly, emphasizes clarity and constructs hierarchy between text. The most common spacing systems used to improve users experience are the : **4** and **8 px scale**. Where all of the padding, margin, line-height, gap variables are multiple of 4 or 8 px.

These systems work best, because most standard resolution screen (width, height size) are factor of 4 0r 8px (remember the default settings of the browser 16px = 4\*4px). Advantageously, they don’t remain the only scope. You can willingly frame your own system and apply it to layout to make things less square and more interesting.

As an experiment in one of my project, i have originated a scale that work for spacing demands, like this :

1. I gave the **body** a font-size = 1.125rem // 18px (in main.css or style.css)
2. I picked up a **scale ratio**, delta_Scale = 1.125 / 5 = 0.225rem
3. All margin, padding, gap was the result of **0.225rem\*n** where **n** is an integer number
4. Example : _ margin-top : 0.675rem (3 times) , _ padding : 0.9rem 1.35rem (4 and 6 times)

The entire system you construct from your derived spacing is a **channel** you insert into your global css file. So it represents the founding of each major distinctive tag the website might use on demands.

Let's approach this with a practical example :

// style.css or main.css

```css
/* spacing variables */
:root {
  --spacing1: 0.225rem;
  --spacing2: 0.45rem;
  --spacing3: 0.9rem;
  --spacing4: 1.3rem;
  --spacing5: 2.475rem;
  --spacing6: 4.95rem;
  --spacing7: 9.9rem;
}

/* spacing references */
.padding1 {
  padding: var(--spacing1) 0;
}
.padding2 {
  padding: var(--spacing2) 0;
}
.padding3 {
  padding: var(--spacing3) 0;
}
... .padding7 {
  padding: var(--spacing7) 0;
}

.margin1 {
  margin: var(--spacing1) auto;
}
.margin2 {
  margin: var(--spacing2) auto;
}
.margin3 {
  margin: var(--spacing3) auto;
}
... .margin7 {
  margin: var(--spacing7) auto;
}
```

<br/>

### V/ The Cunning Containers

Let’s assume a particular situation :

“You styled the welcome page of your websites all the way from Desktop to mobile phones. But still there is a problem!? One section , **-a project cards-** list. Where **_images_**, **_descriptions_** and **_links buttons_** are messing in size, when reaching tablets and mobile. The links, _too small_, the titles, _less bigger than the content_, the images, _more pronounced than the texts they emphasize_. While there is a complete harmony with the remaining content of the page outside of this current section.”

Well! On that kind of moment. Practically quite two available options, can afford the issue as moving below :

**1- Localized CSS Style**

The apparent manner to fix the problem, is to add style in the localized css component file. The rewritten code will apply change immediately moving round all the media-queries breakpoints and fix the layout.

**_While it works_**, it will create unwillingly a temporary and fussy solution, in **need of review** every and each time there is one or many features (location, date, ratings) added in the **cards**. Repeatedly pushing builders to **edge coding** for the case of that "single section" and wasting large amounts of time that could be required for testing and performance rendering of the DOM instead.

**2- Containers Queries**

Arbitrarily, instead of using “media-queries” (@media …). Another solution could be, to apply “container queries” to forge the layout appearance of the container box on each breakpoint we are concerned with. So features become malleable, and can be inserted or removed easily without the need and the use of the code variable values in the global css file.

**Container Queries** works as much as media-queries do but with the role to _compact flexible layouts_ for specific boxes or containers instead of a whole page. It is related to the local style css and call for property like “container-type” and “container-name” like we are going to see in a few moment :

( N.B : // There are four categories of container-queries : **size**, **style**, **scroll-state** and **anchored** )

// We discuss here of _container-queries size_

1. **container-name**: a property name for a box that will carry our queries
2. **container-type** : a size property sets over x-axis or y-axis (_inline-size_, _size_, _inline_) that modify the box layout appearance at specific designated **threshold**.

Example :

```css
.card__container {
  container-name: project-sample;
  container-type: inline-size; /* (x-axis width -- control) */
}

.card__content {
  display: flex;
  flex-direction: column;
  /* ... */
}

@container project-sample (width >= 38.75rem) {
  .card__content {
    flex-direction: row;
    /* ... */
  }
}
```

Container queries are reusable and extensible. Once implemented in a project it could also satisfy another displaying the same behaviors and same layouts relevance.

<br/>

### VI/ Grid Systems Confidence

#### VI-1 Board Game Guidance

Before we expand on Grid Systems. Let me show you some screenshots :

// Picture Website 16px Desktop

![Picture Website 16px Desktop](./assets/inside/16-columns_960%20Grid%20System.png)

<br/>

// Picture Website 12px Desktop

![Picture Website 12px Desktop](./assets/inside/12-columns_960%20Grid%20System.png)

The vertical thick **orange strip bands** you can see are what we called **“Columns”** of the grid. The **tiny white strip bands** between these columns are referred to as **“Gutters”**. Space to make every and each column breathe.

Why is It Important?

Let me tell you this. You may have heard of reusable-components, but what people don’t really grasp and integrate is **reusable** means, **accountable value**, finds first. There is no way reusable-components from one website can be effortlessly inserted in a new other website if we can establish a facilitator and transitional hidden template behind the two of them. That is the **Grid System**.

Most architecture layouts that are more malleable and easily adapted on media-queries have a grid backbone that funds their structure. Containers Or major wrapper Boxes are inserted painlessly on a Grid template.

The eyes seek for pattern recognition whenever looking at forms, shapes, and any websites. Like a disorganized “Lego sets” your layout will feel messy, unpleasant and unkind reading if there is no **surgical structure** from where your website takes root.

**A website** is a collection of boxes with the **aims to showcase trusting copywriting text**, and **functional selected images** that respond to the outcomes or pinpoints of the solution. A major step that could lead to building rapid and professional design is to take in how Grid-Systems works and choose when to use it or not for a project.

If you remember both the css tools we were talking about earlier. Tailwind or Bootstrap. They offer ready built-in utilities to form your Grid System, most especially when you have only and roughly sketch your website design on papers without later using _Figma tool_ to create “low or high fidelity wireframes” (recently a new feature Figma Site integrated, helps you transform directly your Design into the Website- It is a No-code Tools , but demands you subscribe to a pro version, not more the free one).

Let’s see Basically how Bootstrap built-in utilities intend to achieve Grid-Systems :

Bootstrap naturally allows fast design of websites using the 12 Grid Systems because it was naturally the base upon which bootstrap teams decided to provide their easy solution to recreate websites as quickly as possible.

You can call the 12 grid system using the prefix **“col”** followed by “-n” where **n** represent an integer number from 1 to 12. Like For example :

col-12 : Entire width of the viewport size.

col-8 : ⅔ (66%) of the viewport size.

col-md-6 : 50% of the viewport size when the screen device reaches the breakpoint - md (min-width: 768px).

These utilities are inserted in the “class attribute” of any HTML Tags (or JX Tags) suitable as containers or wrappers.

With times, "bootstrap" expand it grid-system to associate more than just 12 columns, but this part ask for integration of the **tw-bootstrap-grid** plugin as a living package in the web project.

When selecting "Tailwind". You can recreate Grid-Systems using utilities that start with “grid-cols” and follow with “-{n}” where n is the number of columns of the Grid. Also you have the possibilities to control gutters a size by inserting “gap-{size}” as HTML or JSX Tags Classes attributes , **size** being an integer number that will correspond in practice to a product of size\*0.25rem.

 <br/>

#### VI-2 Hierarchic Layout

A Proper **spacing system** attached with a measurably good grid system will largely discern titles or headlines from content or texts. Supplying visual eyes guidance from where to move on after analysis of a specific part of the website. This will be comfortable enough, direct, neat. And avoid loss of focus or cognitive load while users are aiming to make sense of the meanings intended behind the solution proposed.

Spacing is a realm that silently adds **professionalism**. With a back-up Grid system, users will inherently sense a familiarity to each of the sections of the webpages of your website and gradually build trust. And compound feelings of professionalism and trust will entice people to reach out to you for a problem-based on the pitch you are willing to resolve.

 <br/>

### Conclusion

Design is about **creative senses** that meet physical existing layouts. While here we discussed one of the ways to automatize Design Template using font-sizes and grid systems.

I want you to understand that the techniques proposed are just **a hint** on how to become _proficient enough to achieve modern layout designs fast_. But once you understand the particular tastes that are _the fabrics of modern designs_, the time is due to try **new perspectives** that will perfectly sign your work. Many ways to engage texts and images all together, less squared, or breaking some hierarchy for good.

In 2007, the idea of “grid-system” was just emerging on designers' topics, while roughly available for implementation over some plugins to add along with css. And people have to _test it_, _break it_, build their own apprehension of the _advantages and limitations of the system_. And that fascinating interest made **upgrades** much easier to nurture.

If you just need a **functional modern website** for your business it is fine, just automatize your component. But if you are a kicker, even **creating some unaligned intentional square box** between text and images will awaken your desire to do more than the rules you already know.

From there you may also like to expand your knowledge with articles like :

Article 1:
https://www.smashingmagazine.com/2014/09/balancing-line-length-font-size-responsive-web-design/

Article 2:
https://css-tricks.com/linearly-scale-font-size-with-css-clamp-based-on-the-viewport/

Article 3:
https://developer.mozilla.org/en-US/blog/getting-started-with-css-container-queries/

I hope you will joyfully find values taken the times you have voluntarily pushed to read this long content, where, definitely the goals are to point out on how to construct websites that start to talk to a **large public**.

Maybe there could be suggestions, observations, or even questions and feedback. Feel free to join the discussion in the comments, I would really love to hear about you. Or maybe give me a spot under my linkedIn account :  
https://www.linkedin.com/in/ngouend-gerard-5a0584244/

Have a happy Designing!
