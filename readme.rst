tree-sitter-rst test files
##########################

This repo contains a few samples to help debugging `tree-sitter reStructuredText grammar <https://github.com/stsewd/tree-sitter-rst>`_.

nbsp-after-inline-markup.rst
****************************

Non-breaking space symbols ``0xA0`` before or after inline markups (italics,
bold and inline literals samples are provided) should not break parser, and
formatting should parse as expected.

Discussed `here <https://github.com/stsewd/tree-sitter-rst/issues/13>`_.

gwip-breaks-tree-parsing.txt
****************************

`gwip` command (rewrap inside paragraph) turns valid unnumbered and numbered
list items (second lines and further) to term definiion lists.

Discussed `here <https://github.com/stsewd/tree-sitter-rst/issues/14>`_.
