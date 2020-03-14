# [Horiseon Marketing Agency](https://drkeck.github.io/Horiseon-Social-solutions/)
Horiseon's front end to show you their advertised statagies and the benefits that come with choosing them, do they fit your needs? click their name to find out.

### Code refraction
I was giving the opportunity to work with the to refract their code making sure their was not redundant code to improve their sites performance, while also changing html elements so it could easily conform to the standards needed to cater to those with disabilities.



## changes
I've consolidated most of the CSS down to fewer lines, as there were many repeated variables that could have been grouped together.

## html

### title
change the `title` to `Horiseon, Marketing Solutions`

### header
made a `header` element to replace `div class="header"`

### navigation
made a `nav` element to house the navigation option in the header

### divs -> sections
changed `div`s into `sections`

### articles
added `articles` for `search engine optimization`,`online reputation management`and`social medai marketing`

### benfits now aside
made the `benifits` section an `aside` instead of a `div` for better readability.

### footer 
made a `footer` to replace a `div`

## css

### body
moved other styles to the `body` section as they were already attempted to be applied to all text and the few acceptions were already overwriting this. examples include
`background-color`
`font-family` 
`font-size` 
`color`

### header
added `header h1, header h1 .seo, footer` since they all share a font family

### a
the `a` entry houses the only repeated color entry because it won't inhearit it from `body` or any other parent elements

### .benefits
consolidated the `.benifits` elements down into `.benefits aside`,`.benefits h3`, and `.benefits img` since there were many repeats in the css code.

### .content
same with the `.content` section as well as above making them into `.content article`,`.content img`, and `.content h2`. also added a `.content article, .content h2` for margin-bottom

### footer
added black text to `footer` so it was more legible.