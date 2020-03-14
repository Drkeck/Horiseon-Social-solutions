# [Horiseon Marketing Agency](https://drkeck.github.io/Horiseon-Social-solutions/)
Horiseon's front end to show you their advertised statagies and the benefits that come with choosing them, do they fit your needs? click their name to find out.

### Code refraction
I was giving the opportunity to work with the to refract their code making sure their was not redundant code to improve their sites performance, while also changing html elements so it could easily conform to the standards needed to cater to those with disabilities.



## changes
I've consolidated most of the CSS down to fewer lines, as there were many repeated variables that could have been grouped together.

### html

change the `title` to `Horiseon, Marketing Solutions`

made a `header` element to replace `div class="header"`

made a `nav` element to house the navigation option in the header

changed `div`s into `sections`

added `articles` for `search engine optimization`,`online reputation management`and`social medai marketing`

made the `benifits` section an `aside` instead of a `div` for better readability.

made a `footer` to replace a `div`

### css

moved other styles to the body section as they were already attempted to be applied to all text and the few acceptions were already overwriting this. examples include
`background-color`
`font-family` 
`font-size` 
`color`

added `header h1, header h1 .seo, footer` since they all share a font family

the `a` entry houses the only repeated color entry because it won't inhearit it from `body` or any other parent elements

consolidated the `.benifits` elements down into `.benefits aside`,`.benefits h3`, and `.benefits img` since there were many repeats in the css code.

same with the `.content` section as well as above making them into `.content article`,`.content img`, and `.content h2`. also added a `.content article, .content h2` for margin-bottom

added black text to `footer` so it was more legible.