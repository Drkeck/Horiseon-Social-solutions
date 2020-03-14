# [Horiseon Marketing Agency](https://drkeck.github.io/Horiseon-Social-solutions/)
Horiseon's front end to show you their advertised statagies and the benefits that come with choosing them, do they fit your needs? click their name to find out.

### Code refraction
I was giving the opportunity to work with the to refract their code making sure their was not redundant code to improve their sites performance, while also changing html elements so it could easily conform to the standards needed to cater to those with disabilities.



## Changes
I've consolidated most of the CSS down to fewer lines, as there were many repeated variables that could have been grouped together. almost all the changes are featured below, so don't hesitate to check them out.

## html

### Title
Change the `title` to `Horiseon, Marketing Solutions`

### Header
Made a `header` element to replace `div class="header"`

### Navigation
Made a `nav` element to house the navigation option in the header

### Divs -> Sections
Changed `div`s into `sections`

### Articles
Added `articles` for `search engine optimization`,`online reputation management`and`social medai marketing`

### Benfits now Aside
Made the `benifits` section an `aside` instead of a `div` for better readability.

### Footer 
Nade a `footer` to replace a `div`

## CSS

### Body
Moved other styles to the `body` section as they were already attempted to be applied to all text and the few acceptions were already overwriting this. examples include
`background-color`
`font-family` 
`font-size` 
`color`

### Header
Added `header h1, header h1 .seo, footer` since they all share a font family

### a
The `a` entry houses the only repeated color entry because it won't inhearit it from `body` or any other parent elements

### .Benefits
Consolidated the `.benifits` elements down into `.benefits aside`,`.benefits h3`, and `.benefits img` since there were many repeats in the css code.

### .Content
Same with the `.content` section as well as above making them into `.content article`,`.content img`, and `.content h2`. also added a `.content article, .content h2` for margin-bottom

### Footer
Added black text to `footer` so it was more legible.