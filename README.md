# Miv

## The add-on has some Firefox navigation keymappings inspired by Vim:
j : down

k : up

f : scroll down

b : scroll up

gg : scroll to top

G : scroll to bottom

Shift + tt : new empty tab

Shift + ss : new tab with https://duckduckgo.com

Shift + xx : new tab with https://google.com

Shift + dd : close tab (works only with tabs that was opened with shift + tt, shift + ss or shift + xx. It is a Firefox rule).

Shift + hh : go back

shift + ll : go forward

## How to create a Firefox extension see this hello world tutorial
https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension

## For installing or removing plugin browser go to:
about:debugging#addons

## Make developing a plugin faster:
https://extensionworkshop.com/documentation/develop/getting-started-with-web-ext/

Run extension from a shell:

web-ext run

Then open about:debugging#/runtime/this-firefox in the browser that gets opened with web-ext run

## Release howto
https://extensionworkshop.com/documentation/publish/package-your-extension/#package-linux

### zip for release (standing in root directory).
 zip -r -FS ../miv.zip * -x *.git* 

## Links
https://addons.mozilla.org/en-GB/developers/addon/miv
