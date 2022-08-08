# Advanced-Physica-Design-using-openLANE/Sky130

This repository contains all the steps performed in 5-day Advanced-Physica-Design-using-openLANE/Sky130 workshop. This workshop is focused in complete RTL2GDS flow using openLANE flow which is open source flow.

# Table of Contents

# Day 1 - Exploring Open-source Tools, OpenLANE Flow and Sky130 Pdk

## Open source PDK structure

![](Day1/pdk_dir_structure.png)

## Initalizing OpenLANE
In Linux Ubuntu, to invoke OpenLANE, we should first run docker everytime. In our case, we invoke OpenLANE in openlane directory. The script is as follow:
`docker`

There are two modes of operation for OpenLANE: interactive and autonomous.
To invoke openLANE run `./flow.tcl`.
In our workshop, We use interactive mode by running `./flow.tcl -interactive`

After invoking openLANE, we import package required for openLANE of the required version. We use version 0.9.
![](Day1/openlane_invoke.png)

The next step is to prepare our design for OpenLANE flow. The following command is used :
`prep -design picorv32a`

![](Day1/prep_design.png)



# Day 2 
