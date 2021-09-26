tree-sitter-rst test files
##########################

This repo contains a few samples to help debugging `tree-sitter reStructuredText grammar <https://github.com/stsewd/tree-sitter-rst>`_.

nbsp-after-inline-markup.rst
****************************

Non-breaking space symbols ``0xA0`` before or after inline markups (italics,
bold and inline literals samples are provided) should not break parser, and
formatting should parse as expected.
