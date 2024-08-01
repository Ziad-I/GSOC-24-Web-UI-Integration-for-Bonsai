# GSOC'24: Web-Based UI integration for BlenderBim

This readme has weekly updates on my GSOC project progress during the coding period in the GSOC timeline.

Project Link: https://github.com/opencax/GSoC/issues/87

Community Forum Post: https://community.osarch.org/discussion/2152/gsoc-project-web-based-ui-integration-with-blenderbim#latest

## Exams (May 25th to June 6th)

No work was done during this period due to my exams.

## Week 1 (June 6th to June 11th)

- Implemented a simple websocket server inside Blenderbim.
- IFC file name is sent to the web browser.

## Week 2 (June 12th to June 18)

- Create a new Web Module/Core/Tool for anything web UI related.
- Create a new Blender Panel to start/connect/kill logic for web UI on a user-specified port.
- Moved websocket server from inside Blenderbim into its Python module run as a subprocess. 
- Implemented starting/connecting/communicating/killing logic for the web UI within BlenderBim.

Merged in [PR #4885](https://github.com/IfcOpenShell/IfcOpenShell/pull/4885#issuecomment-2175543797)

## Week 3 (June 19th to June 25th)

- Create HTML/CSS/JS to render IFC data in tabular format in Web UI.
- Add new output format `WEB` to IFC CSV export panel.
- Add a highlight operator in the Web UI data table highlighting objects in Blender.

Merged in [PR #4918](https://github.com/IfcOpenShell/IfcOpenShell/pull/4918)

## Week 4 (June 26th to July 2nd)

- Create HTML/CSS/JS for rendering scheduling Gantt Charts in web UI
- Add changes in the web UI Gantt chart table reflected in BlenderBim Gantt chart panel

Merged in [PR #4979](https://github.com/IfcOpenShell/IfcOpenShell/pull/4979)

## Week 5 (July 3nd to July 9th)

No work was done this week due to my graduation project deadline, and discussions.

## Week 6 (July 10th to July 16th)

- Community feedback
- Create a diagram to represent the project flow

## Week 7 (July 17th to July 23rd)

- Fix issues with starting the server
- Add a light theme to the web UI
- Edit the diagram with more details

Merged in [PR #5066](https://github.com/IfcOpenShell/IfcOpenShell/pull/5066)

## Week 8 (July 24th to July 30th)

- Add drawings page to web UI that shows drawings/sheets
- Add a footer to IFC Data and Gantt chart pages that shows the Blenderbim version
- Add a connected blender list that shows connected blenders to the current web UI

Merged in [PR #5103](https://github.com/IfcOpenShell/IfcOpenShell/pull/5103)

## Week 9 (July 31st to Current)

Pending....
