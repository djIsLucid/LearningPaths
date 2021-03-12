# SSRF Learning Path

The path to mastering SSRF vulnerabilities begins here. 

### Where to find SSRF

This seems to be the order you should prioritize

1) Image/File uploads
	- Especially SVGs, JPGs, XMLs, and JSONs
2) Proxies
3) Admin Configuration
	- Most commonly when the site allows importing of XML config files
	- XXE is commonly found here as well
4) Webhooks
5) Hidden API endpoints
6) Anything that accepts a URL as input

### Common SSRF Protection Bypasses

- 

### Research Tips

- Try these searches: 
`site:hackerone.com inurl:/reports/ "ssrf" intext:"2020"`

`site:hackerone.com inurl:/reports/ "server-side request forgery" intext:"2020"`


### Resources

- https://blog.orange.tw/2017/07/how-i-chained-4-vulnerabilities-on.html
- https://www.microsoft.com/security/blog/2021/03/02/hafnium-targeting-exchange-servers/
- https://github.com/jdonsec/AllThingsSSRF
