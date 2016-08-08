^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package apriltags
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.3 (2014-11-30)
------------------
* Updating CMakeLists and source includes to point to new apriltags_cpp package
* Modify GetDetectionTransform() to also return rvec & tvec, rename to GetMarkerTransformUsingOpenCV()
* Add node parameters to optionally enable debug graphics
* Add function to draw a marker's ID number
* Add function to draw the ordered edges of a marker
* Add function to draw single-color outline around detected markers
* Add function to draw marker's x,y,z axes
* Add separate color image for visualization, make superimposed marker overlay optional
* Remove un-used variable
* Use distortion coefficients from camera_info
* Convert to mono8
* Use optical center cx,cy from camera intrinsic matrix
* Print warning if camera intrinsic matrix is available but not useful
* Fix launch files so node prints output to terminal
* Change ROS node params from int to bool
* Remove commented-out line
* Add launch file for Kinect2
* Add parameter for cube marker thickness
* Fix arrow marker, add parameter for cube marker thickness
* Add option to publish ROS image topic overlaid with detected markers
* Markers in Rviz should disappear when they are no longer seen
* Add postscript file with default tag images
* Update README.md
* Added CGAL dependency.
* Removed tf_frame parameter from example.
* Removed legacy rosbuild support.
* Removed unnecessary CATKIN_DEPENDS.
  The `message_generation` and `cmake_modules` catkin packages were
  mistakenly added to the `catkin_package(CATKIN_DEPENDS ...` directive,
  leading to unnecessary runtime dependencies.
* Fixed OpenCV rosdep key.
* Upgraded to package.xml format "2".
* Added fix to read frame ID from image message header.
* test
* added launch files
* test
* test
* Added indigo compatibility and an additional raw detection publisher.
  * Adapted CMakeLists to support builds on catkin+indigo.
  * Created a new message AprilTagDetection with raw detection info.
  * Created a new message AprilTagDetections for lists of detections.
  * Publishing raw detections on /detections.
* Contributors: David Butterworth, DavidB-CMU, Michael Koval, Pras, Pras Velagapudi, Stefanos Nikolaidis, Tom Moore, mklingen

0.0.2 (2014-11-30)
------------------
* Bumped to version 0.0.2.
* Contributors: Michael Koval

0.0.1 (2014-09-08)
------------------
* Added c++/python/ros .gitignore
* Added license.
* Updated readme.
* Updated description for package.
* Modified for public release.
* Removed some whitespace.
* spitting out tag size for debugging temporarily
* spitting out tag size for debugging temporarily
* spitting out tag size for debugging temporarily
* spitting out tag size for debugging temporarily
* tag type
* spitting out tag size for debugging temporarily
* testing sizes
* testing sizes
* testing sizes
* testing sizes
* testing sizes
* testing sizes
* testing sizes
* testing sizes
* testing sizes
* testing sizes
* changing scale for a moment
* trying arrows instead of cubes
* updating parameter names
* fixing
* changing tag size
* changing default tag size
* Cleaned up connection and YAML parsing.
* Added YAML parsing code for tag settings that fits ROS spec for YAML keys.
* Fixed default launch file to use default kinect frame.
* Added tf_frame param to apriltags launc hfile.
* Updated dependencies and did cleanup on the rosparams and settings in the apriltags node.
* Minor formatting cleanup.
* Added visualization_msgs dependency.
* Cleaned up makefile.
* Added package.xml fix for opencv2.
* Added system dependencies to package.xml
* Added comments to our autoswitching template.
* Minor fixes to improve display in rviz.
* Minor rewording of stuff.
* Fixed more catkinization issues.
* Added correct catkin dependencies.
* Added most of the fixes to make this work.
* Added new build system that is catkinized.
* Added package.xml to start catkinization.
* Changed repo to use our fork of swatbotics for now.
* Added a cmakelists flag to ensure that apriltags is always built as a shared lib.
* Changed include directory to use extracted varialbes from ExternalProject.
* Changed svn:ignore to ignore bin and build.
* Fixed externalproject dependency to use locally compiled library.
* Removed percy dependency.
* minor changes
* more cleanup
* cleanup
* cleaning up
* removing old comments
* README for Pras at Toyota
* minor changes
* Connect/Disconnect Functionality
* removing srv folder
* get on my lawn
* get off my lawn
* quick and dirty, Mrinals fault
* more stuff
* hacking for external project support
* Added apriltags headers
* safety
* adding start/stop services
* new code hopefully moved correctly now
* first commit
* cleaning up
* no longer uses imageSubscriber
* kinect med tags
* prosilica
* kinect
* Changing tag size
* changing default tag size
* changing default tag size to 2.5 inches and making sure time is set properly
* renamed parameter to tf_frame
* changed frame to default to prosilica and added parameter to change this
* updates
* new april_tags based on Michael Kaess' c++ library
* using a modified camtest to test test tests
* removing build
* removing build
* adding this again
* moving stuff around
* moving stuff around
* removing downloaded zip file
* adding previous stuff to blob directory
* Contributors: Aaron Blasdel, Pras Velagapudi, awalsman, jeking, mkoval, pkv
