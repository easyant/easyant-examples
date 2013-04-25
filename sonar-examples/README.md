## integration of sonar plugin in easyant projects
Here you'll find a few samples projects using sonar plugin

Just invoke easyant sonar:sonar to see results

### Prerequisites ###

* have easyant 0.9 or higher installed and configured
* have sonar 3.3 or higher installed with default configuration (derby)

### Configuring sonar ###

Configuration can be adapted through properties by adding the this to module.ivy file close to plugin declaration:
<ea:property name="aproperty" value="myvalue"/> 

Alternatively if you have a few property to set you can set it as attribute in plugin declaration

<ea:plugin module="sonar" revision="1.0" aproperty="myvalue"/>

see sonar documentation to see exhaustive list of properties http://docs.codehaus.org/display/SONAR/Analysis+Parameters
