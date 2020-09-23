=======
HISTORY
=======
Something very similar was on PSC but it doesn't work
any more. Sadness ruled...

The existing PSC entry worked just fine but when Microsoft
upgraded Internet Explorer for security resaons, it just
stopped working altogether.

No matter how I mucked around with the registry entry
I couldn't get the darned thing to work.

So after some research on JavaScript sites, I now present
a working solution as follows:

=========================
INSTALLATION INSTRUCTIONS
=========================

CREATE FOLDER:

   C:\Program Files\V8Software\

COMPILE PROJECT AS:

   C:\Program Files\V8Software\WebText.exe

COPY THE JAVASCRIPT HTM PAGE TO:

   c:\Program Files\V8Software\V8JavaScript.htm

DOUBLE CLICK THE REG FILE (UPDATE REGISTRY:

   WebTextGrabber.reg


======================
EXECUTION INSTRUCTIONS
======================
TO EXECUTE : OPEN NEW INSTANCE OF EXPLORER

   Highlight (Select) some text
   Click Right Mouse Button
   Choose V8LINK from the Context Sensitive (PopUP) Menu

============
HOW IT WORKS
============
In the registry key you created with the reg file
you instructed Internet Explorer to add a memu item
that item has a key value that runs the JavaScript
in the HTM file.

That script COPIES the highlighted text
and copies it to the clipboard
the VB6 app is a NOTHING program that
just reads the text on the clipboard
and shoves it int the text box

=====
KUDOS
=====
Submitted on: 10/23/2002 8:25:40 PM
By: Pamela RAI

Run your exe from Internet Explorer
and Send selected text in Internet
Explorer to your program 

txtCodeId=40102

=======
FINALLY
=======
AGAIN - I didn't invent the concept.

Essentially I needed this for an autodialer
for one of my clients.

Besides - it's pretty cool stuff and I
was saddened when the original posting
version ceased to work.
=========================================
Enjoy
Kevin Ritch
V8Software.com




