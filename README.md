# ocsvalidation
ocs pkp 2.3.6 validation

This validation works only for author submission step's.
So hackers cant upload phtml, php and other files.

At this moment you can uploads only .doc and .docx files.
But if you want to extend the selection you can add addition file type and file name in PaperFileManager.inc.php (line: 480;481) file.
file types you can find in here: http://filext.com/faq/office_mime_types.php
If you want to dont upload warning, you can change it in author.xml (line: 91) file.


You have to change these files:

classes\file -> PaperFileManager.inc.php
locale\en_US -> author.xml
