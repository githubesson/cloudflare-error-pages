# cloudflare-error-pages

## Requirements

- Cloudflare Pro subscription
## Installation

- Upload the html files to some sort of static storage (eg. aws s3, or cloudflare r2 which i personally use - make sure to enable some sort of public access in the settings of the bucket).
- Go to the 'Custom Pages' section in the Cloudflare panel of the website you're looking to apply these templates to.
- Grab the PUBLIC links to the html templates.
- Apply the each template to their category.
- DONE!



## Screenshots

![Error 429](https://media.discordapp.net/attachments/1040680712875028561/1159197785506205816/Tyr6H8D.png?ex=651f0290&is=651db110&hm=16265ac06f1701d1ad423e50977affd4c3bc21ff8cfe46642938a404bf9697c5&=&width=1488&height=737)

![WAF Block](https://media.discordapp.net/attachments/1040680712875028561/1159197625568989244/ZR2oA9o.png?ex=651f026a&is=651db0ea&hm=f99084fd2a7ce68c8d19fdec169e674d66ea1df59d6f4f12d8c1c72f8e6123f8&=&width=1488&height=737)

![Interactive Challenge](https://media.discordapp.net/attachments/1040680712875028561/1159197561312268378/KhAdyiR.png?ex=651f025b&is=651db0db&hm=dcbc50c2678fe0aa16ea282d7752e292f6ddcca7afbe28395f48e8696edcbbf8&=&width=1488&height=738)

![Error 5xx](https://media.discordapp.net/attachments/1040680712875028561/1159196842643427420/fw9j9Jc.png?ex=651f01b0&is=651db030&hm=a8d193442ddf226e55b0f16b02860837d4c4d7e91cfb1a4cc80b5508c05357d3&=&width=1488&height=739)
