I see
Do you need me to install 
npm would be ideal, but I think I can do this with Python
Okay, note one thing. This is a Qubes VM, so anything outside of ~ is lost on reboot when the VM gets retemplated
If you want me to install something, I have to do it in the debian-8 TemplateVM
okay that worked
no live reload, so it's a bit of a pain, but it's doable
forward 8000 with VS Code for me?
Done
link?Then it should 
I don't think it uses a lonk
Cli
ck the share
nvm, got it working
yeah it's going
There's a Slack extension for VS Code
Apparently
lemme load this in Chrome for Lighthouse audits

port and terminal share?
are you there?
Here now
Getting a Discord extension for VS Code working

don't
it's basically useless
same with the Slack extension
just don't fuck with the extensions for now
Shared both

get ready for your VM to be raped
okay, try adding to homescreen now
I think you'll be happy

does it work?

thot
does it work

Just a moment, will git push

wait
which Discord extension did you get?
the lame "chat from command palette" one, or the Discord integration?
Not sure, disabled it
lame/10

Works, no icon

it would probably help if the files for the icon were there
also here take this: https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode
reload when you're done to get fancy Rich Presence in Discord like wint, sorix, and I do
Is this set up to have a splash screen?

When I tap the icon, it often doesn't work, but will eventually appear

hmmm
one sec

I have to tap the text that reads "capture", rather than the icon

okay, put the images in the directory, I'll update the service worker

Updated?

oh sorry one sec
should be good

currently looking at jobs
a job at the MSFT store came up
the description's.. something
"As a Microsoft Retail Store employee, you have the unique opportunity to impact our company's mission every single day.  Microsoft Retail Stores are the hub of cutting-edge devices and services, providing our customers the opportunity to immerse themselves in the latest and greatest in technology solutions that fit into their everyday lifestyle. As a member of our global Stores team, we value your unique perspective, background, experiences, talents and abilities. We are seeking store teammates who will make authentic connections with our customers, who come from all walks of life, and provide world-class service that transforms them into Microsoft-brand fans."

n i c e

bitch did you not move the images in
okay there we go
lemme update the service worker, nuke it on your phone
Once again, can't nuke on phone
But yeah, added the images
Will Git find those automatically?

yes, VS Code will handle it
you'd run `git add *` or `git add camera-192.png camera-512.png` in the CLI though (just a note, don't actually do it)
I personally have my VS Code set up to automatically add everything new/changed when a commit message is typed and command+enter is pushed

Is everything updated?

appears so

Launches faster now, the "tap the text only glitch" is gone, however the icon still doesn't change

Just the chrome-made "G" on grey background

nice
lemme update the SW again
okay try now

Trying

Okay, now we have the icon, but it's using the outdated manifest where it's called "Fliptool Capture Boi" rather than "Fliptool Capture"

Actually give me a moment, might not have cleared cache on phone

this is a service worker issue
clear cache on your phone, then use wireless devtools to nuke the service worker

Actually, cleared it, it works now. Will still try to figure out how to nuke service worker, give me a moment

nordebook has a touch bar when
anyways I'm going now bye loser