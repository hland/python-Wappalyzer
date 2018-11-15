python-Wappalyzer
=================

Python3 version of https://github.com/chorsley/python-Wappalyzer. 
Uses the `apps.json` file from https://github.com/AliasIO/Wappalyzer to look analyze websites.

    $ pip3 install git+ssh://git@github.com:hland/python-Wappalyzer.git

    >>> from Wappalyzer import Wappalyzer, WebPage
    >>> wappalyzer = Wappalyzer.latest()
    >>> webpage = WebPage.new_from_url('http://example.com')
    >>> wappalyzer.analyze(webpage)
    set([u'EdgeCast'])

[Wappalyzer]: http://wappalyzer.com/
