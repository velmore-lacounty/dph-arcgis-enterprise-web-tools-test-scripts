# dph-arcgis-enterprise-web-tools-test-scripts
Code used for testing publication of ArcGIS script tools to the DPH ArcGIS Enterprise Portal as web tools/geoprocessing services.

## Contents
- <b>WebToolsTest.atbx</b><br>
  An ArcGIS Pro Toolbox containing 3 script tools used for testing/troubleshooting the publication of web tools.
  All three script tools run successfully in ArcGIS Pro, but fail during publication as web tools.
  
- <b>webToolsToolboxTest.pyt</b><br>
  An ArcGIS Pro Python Toolbox containing one tool used for testing/troubleshooting the publication of web tools.
  Tool runs successfully in ArcGIS Pro, but fails during publication as a web tool
  
- <b>webToolsToolboxTest.pyt.xml</b><br>
  Metadata associated with the Python toolbox
  
- <b>webToolsToolboxTest.CapitalizeTool.pyt</b><br>
  Metadata associated with the Python toolbox tool

- <b>SharingJobLog-for-webToolsToolboxTest-CapitalizeMessage-tool-on-8.14.25.txt</b><br>
  Log of failed attempt to publish CapitalizeMessage from the webToolsToolboxTest Python toolbox as a web tool on 8-14-2025.
  Contains the standard warning/error messages contained in logs for all attempts to publish web tools.
