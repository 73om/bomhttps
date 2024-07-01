# Bureau of Meteorology https Enabler
Redirects requests for the Bureau of Meteorology website to their little-known https server at https://reg.bom.gov.au to avoid the "HTTPS not supported" page.

The only difference between the Chrome/Edge/Opera version and the Firefox one is that firefox required an extra section in the Manifest file that Chrome and friends throw an error on, so to use in Firefox, add the following section in manifest.json:
```json
"browser_specific_settings": {
  "gecko": {
    "id":"{your-uuid-here}"
  },
```

Feel free to buy me a beer at https://ko-fi.com/73oldman

This extension is currently available for:<br /> 
[Chrome](https://chromewebstore.google.com/detail/bureau-of-meteorology-htt/hbkpgmpejibghnedepcminnfjmiepoii)<br /> 
[Edge](https://microsoftedge.microsoft.com/addons/detail/bureau-of-meteorology-htt/jccjppajcjhnnpafkpcdlbhojhefacgg)<br /> 
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/bureau-of-meteorology-https/)<br />
I have submitted it to the Opera add-ons and it's in review but they are so pathetically slow that I'm not holding my breath, there are people who've waited multiple years sofar and haven't been reviewed yet. You should be able to install from the Chrome Web Store link above anyway.<br /> 
