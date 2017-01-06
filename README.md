Parsing binary data
===================

A list of generic tools for parsing binary data formats, such as
file formats, network protocols or bitstreams.

### Parsing libraries and frameworks

-   [Spicy](http://www.icir.org/hilti/) (DSL, C/C++):
    a next-generation parser generator for network protocols and file formats
    and forge network packets
-   [Scapy](http://secdev.org/projects/scapy) (Python): send, sniff and dissect
    and forge network packets. Usable interactively or as a library
-   [Construct](http://construct.readthedocs.org/) (Python): library for parsing
    and building of data structures (binary or textual). Define your
    data structures in a declarative manner
-   [Hachoir](https://bitbucket.org/haypo/hachoir/wiki/Home) (Python): view and
    edit a binary stream field by field
-   [DataScript Tools](http://dstools.sourceforge.net) (DSL):
    DataScript is a formal language for modelling binary datatypes,
    bitstreams or file formats.
    [PDF](http://people.cs.vt.edu/~gback/papers/gback-datascript-gpce2002.pdf)
-   [Nom](https://github.com/Geal/nom) (Rust):
-   [Parsifal](https://github.com/ANSSI-FR/parsifal) (OCaml):
    [PDF](http://spw14.langsec.org/papers/pasifal-report.pdf):
    A pragmatic solution to the binary parsing problem. Olivier Levillain
-   [Haka](http://www.haka-security.org) (Lua):
    open source security oriented language which allows to describe protocols
    and apply security policies on (live) captured traffic
-   [Katai Struct](http://kaitai.io):
    declarative language used for describe various binary data structures,
    laid out in files or in memory
-   [Marpa](http://savage.net.au/Marpa.html):
    [libmarpa](http://jeffreykegler.github.io/Marpa-web-site/libmarpa.html) (C)
    https://jeffreykegler.github.io/Marpa-web-site/
-   [Hammer](https://github.com/abiggerhammer/hammer) (C):
    bit-oriented parsing library
-   [libtins](http://libtins.github.io/) (C++):
    crafting, sending, sniffing and interpreting raw network packets
-   [libcrafter](https://github.com/pellegre/libcrafter) (C++):
    high level library for C++ designed to create and decode network packets

### Stand-alone software

Hex editors with grammars

-   [Synalyze It!](https://www.synalysis.net):
-   [Hexinator](https://hexinator.com):
-   [010 Editor](http://www.sweetscape.com/010editor/):

Network packet dissection and crafting

-   [Netzob](http://www.netzob.org): open source tool for reverse engineering,
    traffic generation and fuzzing of communication protocols
-   [Wireshark Generic Dissector](http://wsgd.free.fr/index.html) (Wireshark)
-   [Cat Karat Packet Builder](http://packetbuilder.net):
-   [Sharktools](https://github.com/armenb/sharktools) (Python, Matlab)
-   [Wireshark Tools](https://wiki.wireshark.org/Tools)

### Research papers

-   [Nail](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-bangert.pdf):
    A Practical Tool for Parsing and Generating Data Formats.
    Julian Bangert and Nickolai Zeldovich,
-   GAPA: A Generic Application-Level Protocol Analyzer and its Language
-   PADS/ML: a functional data description language.
    Y. Mandelbaum, K. Fisher, D. Walker, M. F. Fernandez, and A. Gleyzer.
-   [PacketTypes](): P. J. McCann and S. Chandra.
    Packet types: Abstract specification of network protocol messages.
-   [Zebu](https://hal.inria.fr/inria-00350019/file/srds07.pdf):
    A Language-Based Approach for Improving the Robustness of Network
    Application Protocol Implementations.  Larent Burgy et. al.
-   [Zebra](https://hal.archives-ouvertes.fr/hal-00806727/document):
    Improving the Performance of Message Parsers for Embedded Systems.
    Jigar Solanki et. al.
-   [z2z](https://pages.lip6.fr/Julia.Lawall/middleware09.pdf)
-   Yakker: Semantics and Algorithms for Data-dependent Grammars.
    Trevor Jim, Yitzhak Mandelbaum, David Walker
-   [BinPAC](http://www.icsi.berkeley.edu/pubs/networking/binpacIMC06.pdf):
    Superseded by BinPAC++, now known as Spicy
-   FlowSifter:
    High-Speed Application Protocol Parsing and Extraction for Deep Flow Inspection.
    Alex X. Liu, Chad R. Meiners, Eric Norige, and Eric Torng
-   [TSN.1](http://www.protomatics.com/tsn1.html):
    Transfer Syntax Notation One (TSN.1).
    A formal notation for describing messages in binary protocols
-   [NetPDL](http://www.nbee.org/doku.php?id=netvm:index):
    Markup Language that aims to describe Protocols from OSI layer 2 to OSI layer 7
-   [Tupni](https://www.microsoft.com/en-us/research/publication/tupni-automatic-reverse-engineering-of-input-formats/):
    Automatic Reverse Engineering of Input Formats. Weidong Cui et. al.
-   [W. Underwood](http://perpos.gtri.gatech.edu/publications/217-911-1-PB.pdf)
    Grammar-Based Specification and Parsing of Binary File Formats.
    William Underwood

### Related topics

-   Compilers
-   Domain Specific Languages
-   Digital Forensics, Network Forensics:
    http://forensicswiki.org/wiki/File_Format_Identification,
    https://github.com/USArmyResearchLab/Dshell
-   Deep Packet Inspection
-   Packet Crafting: hping2/3, tcpreplay, netdude, bittwist, netsniff-ng, Trafgen, ...
-   Reverse Engineering
-   Fuzzing: Sulley, Peach, ...
-   Language-theoretic Security ([LANGSEC](http://langsec.org))

### Interesting binary formats

This is obviously rather subjective and definitely not supposed to be a complete list:

-   https://github.com/Geal/nom/issues/14
-   https://github.com/corkami/pics
-   http://kaitai.io/#format-gallery
