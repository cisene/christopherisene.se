# christopherisene.se

This is the new and updated site.

I didn't care much for Wordpress anymore, since it became more and more insecure and I thought that having so many moving pieces, yeah a whole machinery of moving pieces, some of the must be insecure.
So, instead of having the installation popped, owned by script kiddies, I'd change the whole site to a staticly rendered HTML-site instead, nothing to hack, zero moving parts.

I started off with a theme that I liked but could never get it to work properly, I started over with a bland theme and borrowed the style of the theme I had on the Wordpress site, "Decoded", flat and easy, I liked it.

The implementation was easy once I got rid of all the custom code that was present in the other theme, clean slate.



I updated the contents somewhat also, added and tweaked small stuff so it would render nicely with the new "engine", Hugo.


In this installation, the only custom stuff (personalized) is in
* [config.yaml](config.yaml)
* [content folder](content/)
* [static folder](static/)



Known issues:
* The Schema.org Person JSON+LD in [schema.html](themes/decode-hugo/layout/partials/schema.html) produces a slightly broken list in "SameAs" where is leaves a comma at the end of the list.


