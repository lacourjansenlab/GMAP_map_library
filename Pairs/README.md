# Pairs maps overview


## DipDip (Kimvana, GMAP developer)
(**Comes with GMAP**) This map implements the standard dipole-dipole coupling, and can couple any kind of singles, no effort required. Safe choice if no better alternatives are available.

## ProteinAmide(_series) (Kimvana, GMAP developer)
(**Come with GMAP**) These maps implement many different coupling models for the Amide-I stretch of proteins. They can only be used with the AmideBB and AmideSC singles. The map ProteinAmide is the main one that should be called directly and provided with a choice of model. The others are implementations of the different models.

## TRESP (Kimvana, GMAP developer)
(**Comes with GMAP**) This map implements the TRESP (transition charges from electrostatic potentials) coupling. In theory, every singles map can be coupled by TRESP, but it does need to add a separate file with TRESP charges.

## Water_Intra and WaterCoupling (GHlacour, GMAP developer)
(**Comes with GMAP**) These maps implement two different coupling models for the OH stretch of water. They can only be used with the water singles map. The map WaterCoupling is the main one that should be called directly and provided with a choice of model.