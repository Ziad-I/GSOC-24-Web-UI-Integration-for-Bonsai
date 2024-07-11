# GSOC'24: Web-Based UI integration for BlenderBim

This readme has weekly updates on my GSOC project progress during coding period in GSOC timeline.

Project Link: https://github.com/opencax/GSoC/issues/87

Community Forum Post: https://community.osarch.org/discussion/2152/gsoc-project-web-based-ui-integration-with-blenderbim#latest

## Exams (May 25th to June 6th)

No work was done during this period due to my exams.

## Week 1 (June 6th to June 11th)

Implemented a simple websocket server inside blenderbim.
IFC file name is sent to the web browser.

## Week 2 (June 12th to June 18)

Create new Web Module/Core/Tool for anything web UI related.
Create new Blender Panel for starting/connecting/killing logic for web UI on user specified port.
Moved websocket server from inside blenderbim into its own python module that is run as a subprocess.
Implemented starting/connecting/communicating/killing logic for the web UI within BlenderBim.

Merged in [PR #4885](https://github.com/IfcOpenShell/IfcOpenShell/pull/4885#issuecomment-2175543797)

## Week 3 (June 19th to June 25th)

Create HTML/CSS/JS for rendering IFC data in tabular format in Web UI.
Add new output format `WEB` to IFC CSV export panel.
Add highligh operator in the Web UI data table that highlighs object in Blender.

Merged in [PR #4918](https://github.com/IfcOpenShell/IfcOpenShell/pull/4918)

## Week 4 (June 26th to July 2nd)

Create HTML/CSS/JS for rendering scheduling Gantt Charts in web UI
Add changes in the web UI gantt chart table reflects in BlenderBim gnatt chart panel

Merged in [PR #4979](https://github.com/IfcOpenShell/IfcOpenShell/pull/4979)

## Week 5 (July 3nd to July 9th)

No work was done during this week due to my graduation project deadline, and disscusions.

## Week 6 (Current)

Pending....
