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
 
 0,0 = CLASS INDEX , FIRST PLACE IS IDENTIFIER OF ARRAY
 0,1 = Cat6, 05ft, yellow
 0,2= Cat6, 10ft, yellow
 0,3= Cat5, 5ft, green
 0,4 = Cat5, 10ft, green
 0,5 = Cat5, 20ft, green
 0,n = Others (FOR EXAMPLE: n == whatever the length of the array is)
 
 1,0 = POWER CABLES
 1,1 = Monitor power cable
 1,n = Other Peripherals
 
 2,0 = DISPLAY CABLES
 2,1 = DVI
 2,2 = VGA
 2,3 = miniDisplay
 2,4 = Display
 2,5 = HDMI
 2,n = Other Adapters
 
 # All of these 'Array Code Indecies' are known by ourselves, but there will be variables which call the instance of the array index
 # i.e. <ArrayName> -> "Wires" [0,0] == zeroIndex (String variable name) "Cat6 Wires"
 #      Wires [0,1] == C605F (Cat6, 05feet) | C(cat)
        Wires [0,2] == C610F (Cat6, 10feet)   #(class)
        etc                                   ##(length)
                                              F (in feet)

# This is only for Wires Array , there will be other Arrays such as Hardware , with 'different' index counts
 # Hardware [a,b]
 # TBD
 
 ##########################################
 ------------------------------------------------------------------------------------------
###

<a href = "https://github.com/darienesf/SHAPEBase/blob/master/Capture.PNG">HERE </a>
  
###

