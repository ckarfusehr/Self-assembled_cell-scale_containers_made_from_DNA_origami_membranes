## Notes: Sequences Used in This Study

* This folder contains all DNA sequences utilized for experiments in this study.
* Generally, staple nomenclature should adhere to that in the scadnano file.
Staples listed in "base_monomer_staple.csv" are used in every monomer design of this study. The "mini_scaffold" and "core" notations originate from the original Wickham et al. article.
* Special staple names in the "base_monomer_staple.csv" file should correspond to the named staples in the provided scadnano file.
* The connector strand nomenclature, such as "container_8T_XL_2.1", provides information about the intended assembly type (container) and the design in which it was used (XL), as well as the minimum number of Ts (8) and the individual connector position on the barrel surface (2.1). The position 2.1 corresponds to the staple with that name in the scadnano file. All staples with the same first number (2) are at the same monomer height. All staples with the same second number (1) are aligned along a line parallel to the main monomer axis.
* Connector staples provided in the file "dummy_connector_staple.csv" are intended for producing monomers without overhangs.
* Files for container, tubes, and plane-specific staples include one or more sets of connector strands.
* Typically, a set of connector strands consists of 30 staples.
* Connector strands for container-forming designs are provided in full length for each version (XS,...,XXL), as is the case for the provided plane set.
* The tube sets are organized to enable more cost-efficient ordering by listing staples common to all designs only once, at the top of the file:
    * "tubes_v1_not_used_connector_staples" are staples present in all tubes but without any staple extension.
    * "tubes_v1_planar_faces_8T" are the staples for the planar faces, which are identical across all tube designs.
    * "tubes_v1_constantGCGC" staples are also utilized in all tube versions.
* Staples listed in "optional_handle_extensions" are also included as normal staples in the "base_monomer_staple.csv" file. These handle sequences can be used to attach objects to the top or bottom of the monomer, if desired.