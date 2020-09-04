START: Build a PC

PROMPT: Input Pringe Range
  INPUT: Price Range = x 
     if x <=500
      then PRINT lowEndBuild
      else if x>=501
        then PRINT MidTeirBuild
      else x>= 801
        then PRINT HighTeirBuild
 
 PROMPT: Press Enter For Build Instructions
  INPUT: ENTER
  
 FIND working space
 CLEAR working space for build 
 NAME working space = WS
 CHECK WS for metalic items
   if matalic items= true
    then remove metalic times
    esle do nothing
  
 PLACE items from build teir on WS
 SEARCH WS for Anti_static_golves
 WEAR Anti_static_golves
 
 SELECT case
 REMOVE case from case_package
 PLACE case in center of WS
 REMOVE case side_Pannel
 PLACE side_Pannel on floor
 RETURN to case
 
 SELECT Motherboard
 REMOVE Motherboard form packageing
 PLACEC Motherboard in case
 LINEUP Motherboard with case_standoffs
 SEARCH WS for MB_screws and philps_screwdriver
  philps_screwdriver = phil
 PLACE MB_screws in Motherboard and case_standoffs
 USE phil to turn MB_screws clockwise untill tight
 NAME Motherboard = MBinC
 EXIT case
 
 RETURN phil to WS
 SEARCH WS for CPU
 REMOVE CPU form CPU_Package
 HOLD CPU by CPU_Edges
 RETURN to case
 FIND MBinC
 SEARCH Socket for tention_lever
 LIFT tention_lever
 SEARCH MBinC for Sokcet
 ALIGNE CPU with Socket
 SEARCH Socket for tention_lever
 PUSH tention_lever
 EXIT case
 
 SEARCH WS for PSU 
 PLACE PSU in case
 SEARCH MBinC for 24pinPower
 CONNECT 24pinPower to PSU
 EXIT case
 
 SEARCH WS for GPU 
 REMOVE GPU from GPU_package
 SEARCH MBinC for PCIE_slot
 PLACE GPU in PCIE_slot
 PUSH GPU until click
 EXIT case
 
 SELCET SSD
  REMOVE SSD from SSD_package
  SEARCH SSD for SATA_cable
 CONNECT SSD to MBinC with SATA
 EXIT case
 
 SELCT memory
 SEARCH MBinC for DIMM_slots
 PLACE memory in DIMM_slots
 PUSH memory in DIMM_slots untill click
 EXIT case
 
 SEARCH FLOOR for case_pannel 
 ATTACH case_pannel to case
 SEARCH case_package for power_cable
 ATTACH female end of power_cable to PSU 
 SEARCH WS for outlet
 PLUG male end of power_cable to outlet
 SEARCH case for power_button
 Press power_button
 WAIT for power
  if power= false
  then flip power_switch on PSU
  else do nothing
 PRINT ITS ALIVE
 
 LowTeirBuild[Motherboard: B365,
               Memory: 16BG of DDR4 2X8GB,
               storage: 480GB SSD,
               GPU: Radeon RC 570,
               Case: Cooler Master MasterBox Q300L,
               PSU:80+ Bronze,
               CPU:Intel Core i3-9100F]

MidTeriBuild:  [Motherboard : b450,
               Memory:16BG of DDR4 2X8GB,
               Storage: 500GB SSD,
               GPU: Nvidia GeForce GTX 1660,
               Case:Cougar MX330-G,
               PSU:Corsair CXM (2015) 450 W,
               CPU: Ryzen 5 3600]

HighTeirBuild:  [Motherboard :X570 ATX,
               Memory: 500M.2,1TB SSD,
               storage: 2x16GB,
               GPU: GeForce RTX 2080 ,
               Case: Fractal Design Meshify S2,
               PSU:EVGA SuperNOVA T2,
               CPU:Ryzen 7 3700X]
    
  
