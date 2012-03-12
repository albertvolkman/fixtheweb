Fix The Web (or Errata)
=======================

Executive Summary
-----------------

Currently there does not exist an uniform method to report spelling errors,
grammatical errors, or site display issues across the web. This tool will allow
users to easily submit such issues directly to the site administrators.

Implementation
--------------

Users will add a javascript bookmarklet or plugin to their browser. Upon
finding an error on a particular website, the user will click on the
bookmarklet/plugin and a bar will appear within the document window. The user
then selects "Spelling error", "Grammatical error", "Bug report" or "Broken
webpage". If the user selects any of the first three, the webpage will become
inline editable. After updates have been made, clicking a "Submit" button will
present a thank you message. If the user provides their contact information
(to be implemented in the plugin), they'll have the option to receive updates
on the status of their report.

Reports will be available publicly via Github as pull requests. If the site
owner has become active in the repository, they'll be able to review pull
requests, make the change on their system, and actually pull the request to
show completion (this might be abstracted out in the future instead of the
Github interface). The reporter will then receive an email if they have opted
in.

Technical Specifications
------------------------

