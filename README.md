## Description

Kabeja is a Java library for parsing, processing and converting Autodesk's DXF format. You can use Kabeja from the CommandLine or embed into your application. All parsed data are accessible with the DOM-like API.

The processing system allows you to process, filter (e.g. XSLT) and convert DXF drafts to different output formats (SVG, JPEG, PNG, TIFF, PDF, XML).

## GUI:

#### Windows: 

    * double-click "kabeja.exe"

#### Linux: 

    * sh kabeja.sh
          
    or:
          
    * chmod a=rx kabeja.sh (only ones)
    * ./kabeja.sh
   		
#### Other:

    * java -jar launcher.jar

## CLI:

in the Kabeja-folder try:

* Help and pipeline list
  
      java -jar launcher.jar --help
  
* Convert to svg

      java -jar launcher.jar -nogui -pipeline svg myfile.dxf result.svg
  
* Convert to pdf / jpeg / png / etc...
  
      java -jar launcher.jar -nogui -pipeline <pdf|jpeg|png>  myfile.dxf 
  
  
Normally Java uses 64 MB of your memory, to setup more use the following commandline

## Feedback and Help

Any help and feedback are greatly appreciated.
