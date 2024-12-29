# Awesome Binary Parsing

A curated collection of tools and resources for parsing and analyzing binary data structures, such as file formats, network protocols or bitstreams.

## Libraries and Tools by Programming Language

### Python
-   [Construct](http://construct.readthedocs.org/):
    library for parsing
    and building of data structures (binary or textual). Define your
    data structures in a declarative manner
-   [Hachoir](http://hachoir.readthedocs.io): view and
    edit a binary stream field by field.
    Long [list of parsers](http://hachoir3.readthedocs.io/parser_list.html) for all kinds of formats
-   [Caterpillar](https://github.com/MatrixEditor/caterpillar): Python 3.12+ library to pack and unpack structurized binary data
-   [Scapy](http://secdev.org/projects/scapy): send, sniff and dissect
    and forge network packets. Usable interactively or as a library
-   [Mr. Crowbar](https://github.com/moralrecordings/mrcrowbar):
    Django-esque model framework for reading and writing binary file formats.
    Includes a suite of command-line tools for visualising and digging through binary data

### JavaScript
-   [Binary-parser](https://github.com/keichi/binary-parser):
    binary parser builder library which enables you to write
    efficient parsers in a simple & declarative way
-   [jBinary](https://github.com/jDataView/jBinary): High-level API for working with binary data.

### C/C++
-   [Hammer](https://github.com/abiggerhammer/hammer) (C):
    bit-oriented parsing library
-   [FormatFuzzer](https://uds-se.github.io/FormatFuzzer/) (C++): framework for high-efficiency, high-quality generation and parsing of binary inputs
-   [Marpa](http://savage.net.au/Marpa.html) (C/C++, Perl, Go):
    [libmarpa](http://jeffreykegler.github.io/Marpa-web-site/libmarpa.html) (C)
-   [Wuffs](https://github.com/google/wuffs): a memory-safe programming language (and a standard library written in that language) for Wrangling Untrusted File Formats Safely. 
    Wrangling includes parsing, decoding and encoding.
-   [libtins](http://libtins.github.io/) (C++):
    crafting, sending, sniffing and interpreting raw network packets
-   [libcrafter](https://github.com/pellegre/libcrafter) (C++):
    high level library for C++ designed to create and decode network packets

### Java
-   [Preon](https://github.com/preon/preon) (Java): 
    Bit syntax for Java. A declarative data binding framework for dealing with binary encoded data
-   [Apache Daffodil](http://daffodil.apache.org) (Scala/Java, XML Schema):
    an open-source implementation of
    [DFDL (Data Format Description Language)](https://en.wikipedia.org/wiki/Data_Format_Description_Language)
    capable of describing [many industry and military standards](https://github.com/DFDLSchemas) and
    parsing into a infoset, which is most commonly represented as either XML or JSON, and writing back to native format.

### Go
-   [restruct](https://github.com/go-restruct/restruct): library for reading and writing binary data

### Rust
-   [Nom](https://github.com/Geal/nom): Rust parser combinator framework
-   [Deku](https://github.com/sharksforarms/deku): bit-level, symmetric, serialization/deserialization implementations for structs and enums
-   [binrw](https://binrw.rs): binrw helps you write maintainable & easy-to-read declarative binary data readers and writers using ✨macro magic✨.

### Ruby
-   [BinData](https://github.com/dmendel/bindata) (Ruby):
    provides a declarative way to read and write structured binary data

### Other Programming Languages
-   [FlexT](http://hmelnov.icc.ru/FlexT/index.eng.html) (Delphi): a DSL and a tool for generating parsers in Delphi
-   [Haka](http://www.haka-security.org) (Lua):
    open source security oriented language which allows to describe protocols
    and apply security policies on (live) captured traffic
-   [binarylang](https://github.com/sealmove/binarylang) (Nim):
    extensible Nim DSL for creating binary parsers/encoders in a symmetric fashion
-   [binaryparse](https://github.com/PMunch/binaryparse) (Nim):
    In-language DSL for reading and writing binary data supporting all sorts of
    patterns. Generates an efficient stream based reader and writer for the
    runtime execution.
-   [Gloss](https://github.com/ztellman/gloss) (Clojure):
    turn complicated byte formats into Clojure data structures and
    Clojure data structures into compact byte representations
-   [scodec](http://scodec.org/) (Scala):
    Combinator library for working with binary data
-   [attoparsec](http://hackage.haskell.org/package/attoparsec) and [attoparsec-binary](https://hackage.haskell.org/package/attoparsec-binary): (Haskell):
    fast parser combinator library, aimed particularly at dealing efficiently
    with network protocols and complicated text/binary file formats
-   [Parsifal](https://github.com/ANSSI-FR/parsifal) (OCaml):
    OCaml-based parsing engine.
    [Paper](http://spw14.langsec.org/papers/pasifal-report.pdf):
    A pragmatic solution to the binary parsing problem. Olivier Levillain

## Language-Agnostic Tools

### Binary Format Description Languages
-   [Kaitai Struct](http://kaitai.io) (DSL):
    declarative language used for describe various binary data structures,
    laid out in files or in memory
-   [RecordFlux](https://github.com/Componolit/RecordFlux): toolset for the formal specification of messages and the generation of verifiable binary parsers and message generators (Ada-inspired).
-   [Spicy](https://github.com/zeek/spicy) (DSL, C/C++, Zeek):
    a next-generation parser generator for network protocols and file formats
-   [DataScript Tools](http://dstools.sourceforge.net) (DSL):
    DataScript is a formal language for modelling binary datatypes,
    bitstreams or file formats.
    [PDF](http://people.cs.vt.edu/~gback/papers/gback-datascript-gpce2002.pdf)
-   [Dogma](https://dogma-lang.org) (DSL): human-friendly metalanguage for describing data formats in documentation using the familiar patterns of Backus-Naur Form.
-   [EverParse](https://project-everest.github.io/everparse/): a framework for generating verified secure parsers and formatters from domain-specific format specification languages

## Standalone Applications

### Hex Editors with Grammars
-   [Synalyze It!](https://www.synalysis.net) (macOS): hex editor with grammar-based binary format parsing
-   [Hexinator](https://hexinator.com) (Windows): hex editor with grammar-based binary format parsing
-   [010 Editor](http://www.sweetscape.com/010editor/) (Windows/macOS/Linux): hex editor with C-style binary templates and large template library
-   [Kiewtai](https://github.com/taviso/kiewtai): plugin for the Hiew hex editor that makes the Kaitai parsers available
-   [Hobbits](https://github.com/Mahlet-Inc/hobbits): multi-platform GUI for bit-based analysis, processing, and visualization. Has a Kaitai plugin.
-   [ImHex](https://imhex.werwolv.net) (Windows/macOS/Linux): A Hex Editor for Reverse Engineers, Programmers and people who value their retinas when working at 3 AM.

### Binary Analysis Tools
-   [GNU poke](https://jemarch.net/poke): The extensible editor for structured binary data
-   [fq](https://github.com/wader/fq): jq for binary formats - tool, language and decoders for working with binary and text formats
-   [radare2](https://github.com/radare/radare2) (C, with bindings/pipe for almost all languages):
    Unix-like reverse engineering framework and commandline tools.
    See [Parsing a fileformat with radare2](http://radare.today/posts/parsing-a-fileformat-with-radare2/)
    and [Types](http://radare.today/posts/types/).
-   [Veles](https://codisec.com/veles/): open source tool for binary analysis

### Network Protocol Analysis
-   [Wireshark](https://www.wireshark.org): network protocol analyzer
    that includes [dissectors](https://www.wireshark.org/docs/wsdg_html_chunked/ChDissectAdd.html)
    for over [two thousand](https://www.wireshark.org/docs/dfref/) protocols.
    -   [TShark](https://www.wireshark.org/docs/man-pages/tshark.html):
        command line version, can easily be called from shell scripts.
    -   [Wireshark Generic Dissector](http://wsgd.free.fr/index.html):
        add-on, allows dissection of a protocol based on a text description of the protocol elements
    -   [Wireshark Lua](https://wiki.wireshark.org/Lua):
        dissectors can be written in Lua ([Examples](https://wiki.wireshark.org/Lua/Examples))
    -   [pyreshark](https://github.com/ashdnazg/pyreshark):
        plugin providing a simple interface for writing Wireshark dissectors in Python
    -   [Sharktools](https://github.com/armenb/sharktools) (Python, Matlab):
        Tools for programmatic parsing of packet captures using Wireshark functionality

-   [Netzob](https://github.com/netzob/netzob): open source tool for reverse engineering,
    traffic generation and fuzzing of communication protocols
-   [Cat Karat Packet Builder](http://packetbuilder.net):
    packet generation tool that allows to build custom packets for firewall or target testing

## Research papers

### Recent developments (2019+)
-   [Interval Parsing Grammars for File Format Parsing](https://arxiv.org/abs/2304.04859) (2023): Jialun Zhang, Greg Morrisett, Gang Tan
-   [LangSec Platform](https://github.com/gangtan/LangSec-papers-and-slides/raw/main/langsec21/papers/Levillain_LangSec21.pdf) (2021): Towards a Platform to Compare Binary Parser Generators. 
    Olivier Levillain, Sébastien Naud, Aina Toky Rasoamanana ([Video](https://www.youtube.com/watch?v=DxtTI9HSV6I))
-   [Narcissus](http://adam.chlipala.net/papers/NarcissusICFP19/) (2019):
    Correct-By-Construction Derivation of Decoders and Encoders from Binary Formats. 
    Benjamin Delaware, Sorawit Suriyakarn, Clément Pit-Claudel, Qianchuan Ye, Adam Chlipala
-   [EverParse](https://www.chajed.io/papers/everparse:usenix-sec2019.pdf) (2019): 
    Verified Secure Zero-Copy Parsers for Authenticated Message Formats. Tahina Ramananandro et. al.

### Historical Papers
-   [Generic packet descriptions](https://www.semanticscholar.org/paper/Generic-packet-descriptions%3A-verified-parsing-and-Geest-Swierstra/d6d742a37d184fd2eb8baa359bc054338cef5b8f) (2017):
    Verified parsing and pretty printing of low-level data. 
    Marcell van Geest, Wouter Swierstra
-   [Nail](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-bangert.pdf) (2014):
    A Practical Tool for Parsing and Generating Data Formats.
    Julian Bangert and Nickolai Zeldovich
-   [FlowSifter](http://ieeexplore.ieee.org/document/6902774/) (2014):
    High-Speed Application Protocol Parsing and Extraction for Deep Flow Inspection.
    Alex X. Liu, Chad R. Meiners, Eric Norige, and Eric Torng
-   [Zebra](https://hal.archives-ouvertes.fr/hal-00806727/document) (2013):
    Improving the Performance of Message Parsers for Embedded Systems.
    Jigar Solanki et. al.
-   [W. Underwood](https://ijdc.net/index.php/ijdc/article/view/217) (2012):
    Grammar-Based Specification and Parsing of Binary File Formats.
    William Underwood
-   [Yakker](http://dl.acm.org/citation.cfm?doid=1706299.1706347) (2010):
    Semantics and Algorithms for Data-dependent Grammars.
    Trevor Jim, Yitzhak Mandelbaum, David Walker
-   [Zebu](https://hal.inria.fr/inria-00350019/file/srds07.pdf) (2009):
    A Language-Based Approach for Improving the Robustness of Network
    Application Protocol Implementations.  Larent Burgy et. al.
-   [z2z](https://pages.lip6.fr/Julia.Lawall/middleware09.pdf) (2009):
    Automatic Generation of Network Protocol Gateways.
    Yerom-David Bromberg, Laurent Reveillere, Julia L. Lawall, Gilles Muller
-   [Tupni](https://www.microsoft.com/en-us/research/publication/tupni-automatic-reverse-engineering-of-input-formats/) (2008):
    Automatic Reverse Engineering of Input Formats. Weidong Cui et. al.
-   [PADS/ML](http://dl.acm.org/citation.cfm?id=1190231) (2007): a functional data description language.
    Y. Mandelbaum, K. Fisher, D. Walker, M. F. Fernandez, and A. Gleyzer.
-   [BinPAC](http://conferences.sigcomm.org/imc/2006/papers/p29-pang.pdf) (2006):
    Superseded by BinPAC++, which is now known as [Spicy](http://www.icir.org/hilti/)
-   [NetPDL](https://staff.polito.it/mario.baldi/publications/2005ComNet_NetPDL.pdf) (2006):
    Markup Language that aims to describe Protocols from OSI layer 2 to OSI layer 7
-   [TSN.1](http://www.protomatics.com/tsn1.html) (2005):
    Transfer Syntax Notation One (TSN.1).
    A formal notation for describing messages in binary protocols
-   [GAPA](https://www.microsoft.com/en-us/research/publication/generic-application-level-protocol-analyzer-and-its-language/) (2005): Generic Application-Level Protocol Analyzer and its Language.
    Nikita Borisov, David J. Brumley, Helen J. Wang, Chuanxiong Guo
-   [PacketTypes](http://conferences.sigcomm.org/sigcomm/2000/conf/paper/sigcomm2000-9-2.pdf) (2000): P. J. McCann and S. Chandra.
    Packet types: Abstract specification of network protocol messages.

## Binary Format References

-   [Hachoir parser list](https://hachoir.readthedocs.io/en/latest/parser.html#parser-list)
    and [source code](https://github.com/vstinner/hachoir/tree/master/hachoir/parser)
-   [Synalyze It! Grammar Page](https://www.synalysis.net/formats.xml)
-   [Nom example parsers](https://github.com/Geal/nom/issues/14)
-   [Corkami posters](https://github.com/corkami/pics/tree/master/binary) for file formats
-   [Kaitai Struct format library](https://github.com/kaitai-io/kaitai_struct_formats)
-   [Catalog of FlexT format specifications](http://hmelnov.icc.ru/geos/scripts/WWWBinV.dll/Cat). [A scraper for them](https://github.com/kaitai-io/kaitai_struct/issues/292). In a e-mail conversation the author of the tool has claimed that the grammars are available under a MIT license. A CoCo/R-like grammar for the DSL also exists, but is in a bit unfinished state.
-   Scapy protocols: [layers](https://github.com/secdev/scapy/tree/master/scapy/layers),
    [contrib](https://github.com/secdev/scapy/tree/master/scapy/contrib)
-   [Wikipedia List of file formats](https://en.wikipedia.org/wiki/List_of_file_formats)

## Related Topics

-   Language-theoretic Security ([LANGSEC](http://langsec.org))
-   [Domain Specific Languages](https://en.wikipedia.org/wiki/Domain-specific_language)
-   Digital Forensics, Network Forensics:
    [file format identification](http://forensicswiki.org/wiki/File_Format_Identification),
    [dshell](https://github.com/USArmyResearchLab/Dshell)
-   Firmware analysis and file carving:
    [Binwalk](https://github.com/ReFirmLabs/binwalk), [Unblob](https://unblob.org), [QuickBMS](http://aluigi.altervista.org/quickbms.htm), [OFRAK](https://github.com/redballoonsecurity/ofrak)
-   Deep Packet Inspection
-   [Packet Crafting](https://en.wikipedia.org/wiki/Packet_crafting):
    hping2/3, tcpreplay, netdude, bittwist, netsniff-ng, Trafgen
-   Reverse Engineering
-   Fuzzing: [Sulley](https://github.com/OpenRCE/sulley), [Peach](http://www.peachfuzzer.com/resources/peachcommunity/), ...
-   [Chomsky hierarchy](https://en.wikipedia.org/wiki/Chomsky_hierarchy)

