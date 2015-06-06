Typescript Compiling Tool
======================================================

USAGE: ./compile.sh <master-file>.ts 

The idea behind this tool is to make typescript development on linux less painful!

The compiler script will be able to:

- Compile all of your typescript files to a single file for faster loading

- Eliminate the need to make duplicates of your typescript files to make them compile correctly

- Search through and remove reference paths used in developement and remove them (make sure you have all reference paths on your master file) 

ISSUES
=======================================================

- Duplicates of each ts file are being made in temp directory causing ts compiler errors 