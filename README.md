# C0bW3b
<img src="https://github.com/Zebratic/C0bW3b/blob/main/imgs/banner.png?raw=true"/>

<h3>
 A web crawler that looks for targetted sites using a dork list with a match list.
 
 Can be used to find vulnurable websites that have exposed strings, or to find sites that sell a specific item.
</h3>
<h3>✔ This project is still actively being developed!</h3>

# Overview
![Overview](https://github.com/Zebratic/C0bW3b/blob/main/imgs/C0bW3b_I94wsxJF7y.png?raw=true)

# Installation
1. Head over to the releases and download the latest build.

## Or alternatively:
1. Make sure you have installed the `.NET Framework 4.7.2`.
2. **Clone this repository** and open the solution file with Visual Studio. Preferebly `Visual Studio Community 2022`.
3. Switch to **Release** mode for a much cleaner output.
4. **Build** the solution (Visual Studio will fetch all the missing nuget packages).
5. You can find the executable inside the folders `C0bW3b/bin/Release`

# Usage
## Lists
There is 3 different type of lists:
- Dorks
  - A Dork list is the terms that C0bW3b will use to search for sites, its practically what it will google for.
- Matches
  - A Match list is what all the result sites that are found will be checked against.
  - An example would be if a site has some text where it says `Buy Now`, and you have that exact text in your match list, it will flag that site as a Hit.
- Proxies
  - A Proxy list is simple, you would have a list of proxies which would be used to search around the web with.
  - Proxy formats that are supported are `IP:PORT` and `IP:PORT:USER:PASS`.
  - Alternatively, you can still find hits easily without proxies. *(Proxies are not needed)*

## Settings
C0bW3b has many settings that can help find your target more specifically.
Such as:
- Target Search
  - You can use the `%ITEM%` tag in both your Dork and Match list to replace it with whatever is inputted in the Target text field.
- Regex Matches
  - You can use **Regular Expressions** in your Match list to find specific results.
  - To use Regex Matches, make sure you enable the feature on the side panel before starting.
  - [View more about Regex here](https://cs.lmu.edu/~ray/notes/regex/)

# Todo
- [x] Target Search (Replaces `%ITEM%` with input in Target's text field)
- [x] Proxy Support (`IP:PORT` and `IP:PORT:USER:PASS`)
- [x] Proxyless
- [x] Regex Matches
- [ ] Plugin Support
- [ ] Recursive Searches (Deep scan on websites, Find Urls in Urls...)

## Search Engines:
- [x] Bing
- [x] Google (*Gives Captcha without proxies*)
- [ ] DuckDuckGo
- [ ] Baidu
- [ ] Yahoo!
- [ ] Ask.com
- [ ] Yandex
- [ ] Naver

# Donate
If you like this software, consider making a donation to the developer. Thank you!
- BTC: **bc1qh5tamp2sq7mdelxz2leeuc47j9llp2wt9y4d67**
- LTC: **MTsj4btp4WAWWof7WyjCDiFapPoiHtA6tr**
- ETH: **0x71504CAAbD13F0cDEF71e342D3Aa6D91139A8EDe**

# Contact
- Telegram: ``Zebratic``
- Discord: ``Zebratic#6969``

Found a bug? [Create an issue!](https://help.github.com/en/articles/creating-an-issue)
