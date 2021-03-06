# Electrode metadata

| Subcategory name | Fieldname | Use (Required or optional) | Category (Descriptive, Structural, Administrative) | General Description | Type |
| -------- | -------- | -------- | -------- | -------- | -------- |
| Metadata for All Electrodes | | | | | |
| | type | optional | descriptive | What type of electrode (ie. sharp, patch, injection, extracellular, multibarrel, mutli-electrode-array, tetrode) | ontology_entry (_Ontology1_, _Ontology2_) |
| | geometry | optional | structural | The geometry of the electrode | prb file |
| | electrode_id | optional | administrative  | A unique identifier for the electrode. Custom ID to differentiate electrodes | string |
| | channel_count | optional | structural | The number of channels | int |
| | manufacturer | optional | administrative | The manufacturer of the electrodes | string |
| Electrical Properties | | | | | |
| | impedence | required | descriptive | Electrode impedence | float |
| Physical Properties | | | | | |
| | material | optional | descriptive | The material the electrodes are made of (ie carbon fiber, glass, nichrome) | string |
| | material_manufacturer | optional | administrative | The manufacturer of the wires the electrodes are made of | string |
| | shape_parameter | optional | descriptive | The shape parameters of the electrode. Describes electrode geometry. | array |
| | tip_size | optional | descriptive | Tip size of electrode | float |
| | coating | optional | descriptive | The coating used to insulate the electrodes | string |
| | electrode_count | optional | descriptive | Number of electrodes in an array | int |
| | tip_coat | optional | descriptive | Coating material used to plate electrode tips (e.g. platinum, gold) | string |
| | final_cut_method | optional | descriptive | How the final length of the tetrode was cut (e.g. fire polishing, cold razor, etc) | string |
| Homebuilt Multichannel Electrode | | | | | |
| | jig_material | optional | descriptive | The type of material the electrode jig is made of (ie polyethylene, resin, propriatary printing materials) | string |
| | jig_model | optional | descriptive | A model of the jig in a CAD software | file |
| | connector | optional | descriptive | What sort of connector is used in the electrode (ex. omnetics with model number) | string |
| | guide_tube_material | optional | descriptive | The type of material the electrode guidetube is made of (polyamide, steel, etc) | string |
| | guide_tube_diameter | optional | descriptive | The size of the guide tube | float |

[Add your comments or discuss](https://github.com/VH-Lab/neuroscienceexperimentalmetadata/issues/6)


# Metadata from other platforms:

[NWB](https://github.com/VH-Lab/neuroscienceexperimentalmetadata/blob/master/other_metadata/NWB/electrode.md)

[odML](https://github.com/VH-Lab/neuroscienceexperimentalmetadata/blob/master/other_metadata/odML/electrode.md)



