# PDBX

`pdbx` is a current rewrite of an internal PDBx/mmCIF toolkit for use with other lab projects. The new tools seek to be compatible with current local data and usable with the V4.0 and V5.0 editions [with official specification changes provided by wwPDB](https://mmcif.wwpdb.org/). The preferred format of the live PDB, to current knowledge, is V3.30 where possible and PDBx/mmCIF otherwise ([see wwPDB FAQ](https://mmcif.wwpdb.org/docs/faqs/pdbx-mmcif-faq-general.html)). Additionally, related structure pipelines in the wild (incl. the [AMBER molecular dynamics suite](http://ambermd.org/)) may produce PDB files that do not strictly adhere to any specific version, so it is necessary to consider flexibility in the format specification.

General syntax examples can be found [here](https://mmcif.wwpdb.org/docs/tutorials/mechanics/pdbx-mmcif-syntax.html). wwPDB provides the legacy PDB specification [here](https://www.wwpdb.org/documentation/file-format). A comparative source of implementation can be found on the [OpenStructure documentation here](https://openstructure.org/docs/dev/io/structure_formats/).
## Contributing

Project documentation is provided in English. Please contact the author(s) if you have any questions.
