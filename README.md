# ocsvalidation
ocs pkp 2.3.6 validation

This validation works only for author submission.

At this moment you can upload only .doc and .docx files.

But if you want to extend the selection you can add addition file type and file name in PaperFileManager.inc.php (line: 480;481) file.
P.S. file types you can find in here: http://filext.com/faq/office_mime_types.php For pdf files add in array's these sentences: $mime_type => application/pdf; $mime_name => pdf.

If you dont like upload warning, you can change it in author.xml (line: 91) file.


You have to change these files:
-
classes\file -> PaperFileManager.inc.php;
locale\en_US -> author.xml;

