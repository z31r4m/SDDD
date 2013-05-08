# SDDD ("Super Dumb Download Done") #


SDDD is a Hazel rule for use in ~/Downloads folder to notify you: "Download Done". 

![SDDD](https://github.com/leoofborg/SDDD/blob/master/README.jpg)

## Why?

Because I miss 'SafariGrowl' and Chrome doesn't notify either. This method doesn't work for Firefox, but if you need the functionality there try the Firefox extension "Growl GNTP" which works with Firefox 20, even on Mac.

Using a last 'any file' rule is problematic. Why? Unzip file. DING. Move into folder. DING. Using this rule, it should catch any file being 'created' via browser Download and then go DING.

## Requires

Hazel, tested with 3.0.18
Growl, tested with 2.0.1

## Usage

- Download the rule
- Import into Hazel, meant for your Download folder
- Make sure the rule is LAST in the chain of things you're trying to do.
- Enjoy

### Workarounds

For those not using Growl:

If you're using 10.8's Notification Center the 'Display Growl Notification' rule may not be there. Under 'Do the Following' just add 'Display Notification' instead, and re-fill the strings to your liking.





