Alex Whittemore's Eagle Library
===============================

There are plenty of footprints and devices that I've needed to use in Eagle and couldn't easily find online. Here they are!

Current devices of interest:
* `AD7685`
* ADC121C021
* INA125 (this already exists in the default libs, but I took offense to certain parts or something)
* LTC1063
* MAX7414
* MAX31855
* MC74VHC1GT126
* REF3333
* REG103
* SN754410
* Omega PCB-mount Thermocouple Receptacle
* Bournes 25-t trim pot
* Amphenol USB3.0 A Receptacle
* Amphenol USB3.0 B Receptacle

There are also a few packages I've added that I couldn't seem to find anywhere else.
* SOT223-5

Markups
-------

The following markups are supported.  The dependencies listed are required if
you wish to run the library.

* [.markdown](http://daringfireball.net/projects/markdown/) -- `gem install redcarpet` (https://github.com/tanoku/redcarpet)
* [.textile](http://www.textism.com/tools/textile/) -- `gem install RedCloth`
* [.rdoc](http://rdoc.sourceforge.net/) -- `gem install rdoc -v 3.6.1`
* [.org](http://orgmode.org/) -- `gem install org-ruby`
* [.creole](http://wikicreole.org/) -- `gem install creole`
* [.mediawiki](http://www.mediawiki.org/wiki/Help:Formatting) -- `gem install wikicloth`
* [.rst](http://docutils.sourceforge.net/rst.html) -- `easy_install docutils`
* [.asciidoc](http://www.methods.co.nz/asciidoc/) -- `brew install asciidoc`
* [.pod](http://search.cpan.org/dist/perl/pod/perlpod.pod) -- `Pod::Simple::HTML`
  comes with Perl >= 5.10. Lower versions should install Pod::Simple from CPAN.