====================
{{ TemplateName }}
====================

Project Outline
----------------

{{ if ProjectGoal }}Project Goals
'''''''''''''

{{ ProjectGoal }}
{{ end }}
{{ if SimilarWork }}Similar Work
''''''''''''

{{ SimilarWork }}
{{ end }}
{{ if Justification }}
Justification
'''''''''''''

{{ Justification }}
{{ end }}

Summary
'''''''

============= ==============
License       Language
------------- --------------
MIT           en-AU [lang]_
============= ==============

Installation
-------------

.. Code:: bash

  $ boilr template download {{ GithubReference }} {{ TemplateName }}

Usage
-----

Swap `foo` and `bar` for your own values.

.. Code:: bash

  $ mkdir foo
  $ cd foo
  $ git init
  $ git remote set-url origin git@github.com:foo/bar.git
  $ boilr template use {{ TemplateName }}
  $ git add .
  $ git commit -m "Initial Commit"
  $ git push

Thanks
------

- The team behind boilr (https://github.com/tmrts/boilr)

Contributing
------------

Contributions are always welcome! Nothing is to small, and the best place to start is to open an issue.

References
-----------

.. [lang] Lingoes.net,. (2015). Language Code Table. Retrieved 4 June 2015, from http://www.lingoes.net/en/translator/langcode.htm
