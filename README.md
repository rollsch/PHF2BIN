# PHF2BIN
Extremely basic application that converts a ford PHF file to a binary image. 
Currently is hard coded to convert spanish oak 1024k and black oak 1472k.
Program could easily be expanded to be more generic and convert other files.

PHF sections that are not defined are null padded in the resultant binary. 
Highly recommended to NOT write the resultant binary to a vehicle due to the null padded sections.
