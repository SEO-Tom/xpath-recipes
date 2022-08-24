# SEO XPaths

## Find links to a target domain
//a[contains(@href,'example')]/@href

## Count links to a target domain
count(//a[contains(@href,'example')]/@href)

## Target sibling of element with specified text
//span[contains(text(),'**Insert Text Here**')]/following-sibling::span[@class='**class of target element**']
