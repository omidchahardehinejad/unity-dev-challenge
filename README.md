# unity-dev-challenge
Challenge for unity dev applicants

Completion time: ~6h

Inside the Unity project you will find a prefab of a globe and a marker to be used for this challenge.
Of course we just threw all those assets into the project without any structure.

The result should be a project that can either be built for Android using
ARCore, iPhone using ARKit, Desktop (if you do not have access to xr devices) or VR (preferably HTC Vive).

The project then should include all files and sdks necessary to build for the target platform when we receive it.


Task 1:
Add some folders to the project and give a clear structure to the assets.

Task 2:
Create the globe at the position the user is pointing and clicking at
and move it to new position if it has already been placed.
(mouse on desktop, touch on ar, click on vr)

Task 3:
Create controls for the globe so it can be rotated by user input on it’s y-axis only.
(simple drag rotation)

Task 4:
Create an editor interface for adding multiple geolocations by name
and using decimal degrees format, where northern and eastern hemisphere values are positive
and southern and western hemisphere values are negative.
(no custom editor window, just expose the arrays in editor for speeds sake)

Task 5:
Create markers with the name of the cities on the globe based on the entries of geolocations.
(the names should be visible somehow on the globe, yes)


Judgement will be solely based on methodology, not on design, so do not waste time there.

Happy coding!
