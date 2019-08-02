# SHAPEBase
Framework Database


<START MESSAGE>
  Inventory Base Outline 
  To help
<END MESSAGE>
  
2D "columns" Array Implementation
WIRES (Array variable name)
index legend ( 0th = Patch Cables, 1st= Power Cables, 2nd= Video Cables, nth= Phone Cables )
  2D example[0 (patch cable), nTh (size of patch cable & category type)] *count*
  
# 0th index of INVENTORY OBJECT VARIABLE = "base case"
 
 [x,y]
 
 0,0 = Cat6,5ft (individual index would have its own count for how many are in stock)
 0,1 = Cat6, 10ft 
 0,2= Cat6, 20ft
 0,3= Cat5, 5ft
 0,4 = Cat5, 10ft
 0,5 = Cat5, 20ft
 0,n = Others
 
 1,0 = PC power cable
 1,1 = Monitor power cable
 1,n = Other Peripherals
 
 2,0 = anything
 2,1 = DVI
 2,2 = VGA
 2,3 = miniDisplay
 2,4 = Display
 2,5 = HDMI
 2,n = Other Adapters
 
 # All of these 'Array Code Indecies' are known by ourselves, but there will be variables which call the instance of the array index
 # i.e. <ArrayName> -> "Wires" [0,0] == C610F (Cat6, 10feet)
 #      Wires [0,1] == C605F (Cat6, 05feet)
 # This is only for Wires Array , there will be other Arrays such as Hardware , with 'different' index counts
 # Hardware [a,b]
 # 
 
 ##########################################
 ------------------------------------------------------------------------------------------

# Resources #
<a href = "Capture.png">
  
###

