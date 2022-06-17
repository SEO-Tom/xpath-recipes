# SEO XPaths

## Find links to a target domain
//a[contains(@href,'example')]/@href

## Count links to a target domain
count(//a[contains(@href,'example')]/@href)
