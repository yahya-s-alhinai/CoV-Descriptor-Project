# Dec 11, 2020 - initial upload to Github 

### Top module ###
- The main module manages all other module. For now, it includes SobelAccelerator module and RAM module. 
- The number of rows and columns of the input array is adjusted here.

### RAM module ###
- The input array is saved here.
- Sending and Receiving data could be done simultaneously accessing different addresses of the array. This can be further expanded by dealing with several inputs and outputs being requested at the same time.

### SobelAccelerator module ###
- The computaoinal part is deone here