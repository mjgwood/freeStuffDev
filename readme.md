## FreeStuffDev
List of free services for developer like database, hosting, authentication and other stuff.
[freestuff.dev](https://freestuff.dev)  

Inspired by https://free-for.dev/ , I create my own dev-tool list to start prototyping or making a MVP.

Built with Hugo Static site generator and hosted at Netlify

## Contribute
Want to add new stuff? 
Create a new file [here](https://github.com/hilmanski/freeStuffDev/new/main/content/stuff?value=%2B%2B%2B%0Adate%20%3D%20%22YYYY-MM-DDT00%3A00%3A00%2B00%3A00%22%0Atags%20%3D%20%5B%22tag%22%5D%0Atitle%3D%22Title%22%0Alink%20%3D%20%22https%3A%2F%2Flink%22%0Athumbnail%20%3D%20%22url_thumbnail%22%0Asnippet%3D%22Snippet%20of%20product%22%0A%2B%2B%2B%0ADetail%20what%27s%20free%20here..%0A)

If you're going to create file manually (not via link above):

1. Fork repo
2. Inside your fork navigate to `content/stuff`
3. Create here new file about service you want to add. File must have `.md` extension, i.e. `myservice.md`
4. Use next template for content

```
+++
date = 2021-06-21T18:55:27+03:00
title = "Your service name"
link = "https://link.to.service"
thumbnail = "https://any.logo.of/service"
snippet="Service description, which will be shown under service name"
tags = ["Tag1","Tag2","TagN"]
+++ 
free feature 1
free feature 2
free feature 3
```

P.S:

- You can use any image for thumbnail, but try to avoid using small favicons(16x16) as each **image will be resized to 80x80**
- For existing tags visit https://freestuff.dev/ and open the "Filter"
- At the end write the features as one feature per line

Example with [netlify.md](https://github.com/NEK-RA/freeStuffDev/blob/main/content/stuff/netlify.md) (watch it [raw version](https://raw.githubusercontent.com/NEK-RA/freeStuffDev/main/content/stuff/netlify.md))
```
+++
date = "2021-06-15T00:00:00+00:00"
tags = ["hosting", "hosting-dynamic", "hosting-static", "serverless"]
title="Netlify"
link = "https://www.netlify.com/"
thumbnail = "https://res.cloudinary.com/wegoatdev/image/upload/v1623795952/freestuffdev/stuff/netlify.png"
snippet="An intuitive Git-based workflow and powerful serverless platform to build, deploy, and collaborate on web apps"
+++
Host static and serverless function
Bandwith: 100GB /month
Build Minutes: 300 Minutes /month
Websites: Unlimited
Serverless Functions: 125k per site /month
Forms: 100 /site/month
Identity: 1K /site/month
```
