# Challenge-1

**Changes to HTML File**

Symantic elements and structure were added to the file:
Header, Main Content, Aside Content, Sections, Footer.

Added spaces between HTML code for better readability.

Changed title to: "The Future of Online Business Strategies".

Changed div to nav for navigation bar.

Moved the header image to header instead of main, and renamed to "header-image".

Changed "content" class to "main-content".

Included alt properties for each image.

Changed class "search-engine-optimization" to an id.

Changed the classes "benefit-lead", "benefit-brand", and "benefit-cost" to ids.

Removed "online-reputation-management" and "social-media-marketing" classes.

**Changes to CSS File**

Structure was added and CSS rules were organized accordingly:
Global Rules, Element Rules, Class Rules, ID Rules.
(Organized from Header, to Main Content, to Aside Content, to Footer per rule section),

.header div changed to .header nav to account for HTML change.

.content changed to .main-content to account for HTML change.

All classes that were changed in HTML to ids were also changed to ids in CSS.

After removing "online-reputation-management" and "social-media-marketing" classes in HTML, updated CSS rules to ids for the remaining associated ids in HTML.

Rules that were simplified into one rule:

#search-engine-optimization, #online-reputation-management, #social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

#search-engine-optimization img, #online-reputation-management img, #social-media-marketing img {
    max-height: 200px;
}

#search-engine-optimization h2, #online-reputation-management h2, #social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

#benefit-lead, #benefit-brand, #benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

#benefit-lead h3, #benefit-brand h3,#benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

#benefit-lead img, #benefit-brand img,#benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

**Additional Notes**

img in header, "header-image", would not allow an alt or title property to be applied without changing layout of website.

Contemplated changing unique class "float-right" into an id, but for organizational sake in CSS decided not to. Since it would be separated from "float-left", making it difficult to find.