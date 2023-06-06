# Horiseon Social Solution Services, Inc.

<!-- ![Horiseon Logo](./assets/images/logo.PNG) -->

<img src="./assets/images/logo.PNG" alt="Horiseon Logo" width=40% height=40%>

## About our glorious Corporate Dynasty
- - - -
Welcome to the immortal cybernetic abode (a.k.a. "webpage") of Horiseon Social Services, Inc. Horiseon is a multi-national, multi-generational familial-corporate dynasty that strives to continue providing cutting-edge, industry-standard setting consultations and solutions in the following: `Social Media Marketing`, `Search Engine Optimization`, and `Online Reputation Management`. Yes, for the past five years, customers have constistently rated us to be the best providers of our field*. *Disclaimer: The fact that we are the only providers for said field within 500km is irrevelant.

## Webpage debugging objectives
- - - -
While performing routine maintence and checks, our esteemed and peerless software developers have noticed several errors and inconsistencies witin the code. Thus we have made and accomplished the following objectives:

* **1. Review code to find HTML elements** - To ensure the source code incorporates HTML elements.
* **2. HTML code revisement** - To revise the code and to ensure that it executes itself logically
* **3. Review & amend image attributes** - Makes sure the images are correctly placed within the code.
* **4. Amend and add title content** - Positions the title and its contents in the right place.

### Debugging

1.Upon reviewing the source code, our experts located the `HTML elements`. But, the code was incorrect and the `image attributes` was shown wrong, explained below:

```
    <div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
```

2.Upon further reviewing the code, our experts located  the `header` section. However, it too was incorrectly ordered and missing its title, as show below:

```
<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>
</head>
```

### Amending the mistakes

* **Reviewing & Revising Header Element(s)**
    * The experts fixed the header by placing `<title>website</title>` BEFORE the link to a stylesheet
    * Replaced placeholder title and added the company's name instead: `Horiseon Social Solution Services, Inc.

    ```
    <head>
        <meta charset="UTF-8" />
        <title>Horiseon Social Solution Services, Inc.</title>
        <link rel="stylesheet" href="./assets/css/style.css">
    </head>
    ```
* **Replaced placeholder `div`(s) with correct elements**
    * Added elements such as `figure` for images & images with captions
    * Added the `section` elements to compartmentalize the code.
    * Added `alt` attribute for ease of image identification
    * Replaced `<p></p>` with `<figcaption></figcaption>` , as it fits within the code better.

    ```
        <section class="benefits">
        <figure class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="placeholder stock image" />
            <figcaption>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </figcaption>
        </figure>
    ```



## Ending notes
- - - -

Upon reviewing our criteria and making all neccessary amendments, we have now relaunched the site, available to view at: 