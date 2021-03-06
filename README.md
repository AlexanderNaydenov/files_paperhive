[![Build Status](https://travis-ci.org/owncloud/files_paperhive.svg?branch=master)](https://travis-ci.org/owncloud/files_paperhive)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/owncloud/files_paperhive/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/owncloud/files_paperhive/?branch=master)

- [x] Support for 9.0
- [x] Support for 9.1
- [x] Support for 9.2-10.0

To install, go to ```/apps``` in your ownCloud installation directory and ````git clone https://github.com/owncloud/files_paperhive```. In the apps admin panel enable PaperHive app.

It is highly recommended, to place in each user root directory a default introduction PaperHive document, ```https://paperhive.org/documents/0tsHJq1-yyVZ``` which will help the user orient in the new functionality!

# About ownCloud, PaperHive and Collabora

Collabora and ownCloud announced a partnership and released Collabora Online Development Edition, a VM containing LibreOffice Online and ownCloud Server. LibreOffice Online is what the name suggests – an online version of the well known LibreOffice suite of productivity apps: word processor Writer, spreadsheet Calc and presentation tool Impress.

Researchers, students, medicine and engineering specialists collaborating on research using documents in LibreOffice Online, are very frequently referencing professional texts.

Researchers read 12-25 hours a week depending on their discipline. Yet, understanding research articles and books – some of the most complex documents in the world – is hard and inefficient in isolation. Students and inexperienced researchers waste time trying to decipher these texts alone, senior researchers dig through folders of articles irrelevant for their own work, and all at some point might repeat unknowingly others’ mistakes or include these as a citation in their own paper.

PaperHive looks at how the web platform could transform reading into a more social and active process of collaboration. It is a cross-publisher layer of interaction on top of research documents that enables contextual and structured discussions in real time.

Close to 1.2 million academic articles and books can currently be read and discussed with PaperHive.

# Transforming Reading Into a Process of Collaboration

One of the greatest ownCloud features is sharing. Folders or files can be shared with groups, individual users or using password protected or public links.

![](https://github.com/mrow4a/files_paperhive/blob/master/screenshots/sharing_documents_1.png)

The PaperHive documents in this shared folder allow legal sharing of the research intellectual property with a group or groups of users, giving an option to quickly redirect to the PaperHive page using the `Discuss` button in the file list, which additionally shows the current number of discussions online.

![](https://github.com/mrow4a/files_paperhive/blob/master/screenshots/sharing_documents_2.png)

Transform your lectures, research and engineering work into a process of collaboration with ownCloud, PaperHive and Collabora!

# Add PaperHive book to ownCloud

The PaperHive plugin is shipped with the new file menu button "PaperHive Document", which allows adding the documents found on the PaperHive website at `https://paperhive.org`. These are no different to your regular `.doc` or `.jpg` files and will behave the same as any other files in the ownCloud user interface.

Clicking on the "PaperHive Document" button will ask you for a PaperHive URL or DocID, displaying helpful information in the yellow popup on top of your file list. You are free to choose submitting just DocID or whole URL!

![](https://github.com/mrow4a/files_paperhive/blob/master/screenshots/add_new_book_1.png)

DocID is an unique book identifier, which can be found in the URL of the document at `https://paperhive.org`, as shown in the example below, where URL is `https://paperhive.org/documents/0tsHJq1-yyVZ` and unique DocID is `0tsHJq1-yyVZ`.

![](https://github.com/mrow4a/files_paperhive/blob/master/screenshots/add_new_book_2.png)

Desired URL or DocID has to be inserted into the field below and confirmed pressing ENTER.

![](https://github.com/mrow4a/files_paperhive/blob/master/screenshots/add_new_book_3.png)

Your PaperHive Document is now in your synchronisation folder!



