# Pastebin

## Preview
![Pastebin Extension](/extensions/pastebin/images/preview.png?raw=true)

## Get API Key
1. Login to your Pastebin account [here](https://pastebin.com/login)
2. Go to this [link](https://pastebin.com/api#1) and you should be able to see a section like this:
![Pastebin API Page](/extensions/pastebin/images/pastebin_api_page.png?raw=true)
3. Copy the key from **Your Unique Developer API Key** to the Key field inside Pastebin extension

## Download Raw Data
1. Paste the Pastebin link to URL input box, valid URL types are `https://pastebin.com/example`, `https://pastebin.com/raw/example` and `example`
2. Switch **Type** from `None` to `Download`
3. Wait for Status to change to **Downloaded**
4. Close Pastebin extension, it should be added to your bot's command or event

## Upload Raw Data
1. Switch **Type** from `None` to `Upload`
2. Wait for status change to **Post!**
3. You should able to see the Pastebin URL, link is valid for 30 days and the link is unlisted

## Status Code
- Downloaded - Successfully downloaded raw data from Pastebin
- Post! - Successfully uploaded raw data to Pastebin
- Error! - Something went wrong, read the error below.
- Key not found. - Please put your API key in the Key field inside the extension
