^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cob_teleop
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.6.35 (2024-04-18)
-------------------

0.7.35 (2024-04-30)
-------------------
* 0.6.35
* update changelogs
* Contributors: fmessmer

0.6.34 (2024-02-18)
-------------------
* Merge pull request `#340 <https://github.com/4am-robotics/cob_command_tools/issues/340>`_ from fmessmer/migrate_ipa320
  migrate ipa320
* remove outdated readme
* Contributors: Felix Messmer, fmessmer

0.6.33 (2023-11-06)
-------------------

0.6.32 (2023-04-29)
-------------------

0.6.31 (2023-01-04)
-------------------

0.6.30 (2022-11-17)
-------------------

0.6.29 (2022-07-29)
-------------------
* Merge pull request `#317 <https://github.com/ipa320/cob_command_tools/issues/317>`_ from benmaidel/feature/run_factor_axis
  use right trigger axis as an analog signal for the run_factor
* check vector boundaries
* check if axis_run was ever triggered before applying the run_factor
* add option to use trigger button axis for the run factor
* Contributors: Benjamin Maidel, Felix Messmer

0.6.28 (2022-03-15)
-------------------

0.6.27 (2022-01-12)
-------------------

0.6.26 (2021-11-26)
-------------------

0.6.25 (2021-08-02)
-------------------

0.6.24 (2021-07-02)
-------------------

0.6.23 (2021-07-01)
-------------------

0.6.22 (2021-05-10)
-------------------

0.6.21 (2021-04-06)
-------------------

0.6.20 (2021-01-25)
-------------------

0.6.19 (2020-12-02)
-------------------
* Merge pull request `#287 <https://github.com/ipa320/cob_command_tools/issues/287>`_ from fmessmer/fix_catkin_lint
  fix catkin_lint
* fix catkin_lint
* Contributors: Felix Messmer, fmessmer

0.6.18 (2020-10-21)
-------------------

0.6.17 (2020-10-17)
-------------------
* Merge pull request `#284 <https://github.com/ipa320/cob_command_tools/issues/284>`_ from fmessmer/test_noetic
  test noetic
* Bump CMake version to avoid CMP0048 warning
* Contributors: Felix Messmer, fmessmer

0.6.16 (2020-03-18)
-------------------
* Merge pull request `#271 <https://github.com/ipa320/cob_command_tools/issues/271>`_ from fmessmer/ci_updates
  [travis] ci updates
* catkin_lint fixes
* Contributors: Felix Messmer, fmessmer

0.6.15 (2019-11-07)
-------------------
* Merge pull request `#252 <https://github.com/ipa320/cob_command_tools/issues/252>`_ from benmaidel/feature/dock_undock
  added docking/undocking feature to teleop
* added docking/undocking feature to teleop
* Contributors: Benjamin Maidel, Felix Messmer

0.6.14 (2019-08-07)
-------------------

0.6.13 (2019-07-19)
------------------

0.6.12 (2019-06-07)
-------------------

0.6.11 (2019-04-05)
-------------------

0.6.10 (2019-03-14)
-------------------
* Merge pull request `#238 <https://github.com/ipa320/cob_command_tools/issues/238>`_ from benmaidel/feature/publish_feq
  [cob_teleop] made publish rate configurable
* made publish rate configurable
* Contributors: Benjamin Maidel, Felix Messmer

0.6.9 (2018-07-21)
------------------
* update maintainer
* Contributors: ipa-fxm

0.6.8 (2018-07-21)
------------------

0.6.7 (2018-01-07)
------------------
* Merge remote-tracking branch 'origin/indigo_release_candidate' into indigo_dev
* Merge pull request `#202 <https://github.com/ipa320/cob_command_tools/issues/202>`_ from ipa-fxm/update_maintainer
  update maintainer
* update maintainer
* Merge pull request `#197 <https://github.com/ipa320/cob_command_tools/issues/197>`_ from ipa-fxm/APACHE_license
  use license apache 2.0
* use license apache 2.0
* Contributors: Felix Messmer, Richard Bormann, ipa-fxm, ipa-uhr-mk

0.6.6 (2017-07-17)
------------------
* manually fix changelog
* Contributors: ipa-fxm

0.6.5 (2016-10-10)
------------------
* add safe mode for teleop
* Contributors: Florian Weisshardt, ipa-fmw, ipa-nhg

0.6.4 (2016-04-01)
------------------
* reduce terminal output
* changes for new message structure and concurrent mode
* compile fixes because of changes in cob_light
* swap say-setLight execution order2
* introduce enable params, styling, consistency, beautifying
* add catkin include dirs
* adapt twist_mux topic names according to https://github.com/ipa320/orga/pull/1#issuecomment-159195427
* added apply_ramp parameter to switch velocity smoothing on teleop side on and off (if velocity_smoother is active teleop do not need to smooth)
* changed keyboard default topic to twist_mux input
* Merge branch 'fix_teleop' of https://github.com/ipa-fmw/cob_command_tools into fix_teleop
* announce 'go' after init all
* tabs vs. spaces
* replace string before passing to say
* change speach output
* enable speach for default position mode
* cob_teleop: disable light, encapsulate say and use deadman button to enable mode switch
* Fix typo
* added tag exported targets
* deleted config folder
* change frequencies
* removed configuration files
* use light action server
* first robot test
* global ns for actions
* cob_teleop review
* updated package.axml and CMakeLists
* fisrt testable version
* adapt the node for other robots
* beautify
* update
* update
* new node
* Contributors: Benjamin Maidel, Florian Weisshardt, Marco Bezzon, ipa-fmw, ipa-fxm, ipa-nhg

0.6.3 (2015-08-25)
------------------
* boost revision
* do not install headers in executable-only packages
* explicit dependency for boost
* more cleanup
* remove obsolete autogenerated mainpage.dox files
* remove FILES_MATCHING
* remove trailing whitespaces
* migrate to package format 2
* sort dependencies
* Contributors: ipa-fxm

0.6.2 (2015-06-17)
------------------
* replace brics_actuator
* use new Trigger from std_srvs
* Update README-PS3.md
* Update README-PS3.md
* Update README-PS3.md
* Update README-PS3.md
* catkin_lint
* use correct default namespace
* Instruction for PS3 Joystick with Bluetooth
* changed hardcoded namespace
* improved ROS_DEBUG output
* improved ROS output
* improved homing/recover srv-calls: now checking success of pltf-init/recovering instead of just checking srv call response
* Contributors: Nadia Hammoudeh García, Thorsten Kannacher, fmw-ms, ipa-fxm

0.6.1 (2014-12-15)
------------------
* merge
* adapt teleop_v2 to the new controllers structure
* add gencpp dependency
* rename teleop to teleop_v1
* change maintainer
* rename finished
* rename files from cob4 to v2
* Contributors: Florian Weisshardt, ipa-nhg

0.6.0 (2014-09-18)
------------------
* fix cppcheck warnings
* Contributors: Florian Weisshardt

0.5.2 (2014-08-28)
------------------
* restore original cob_teleop
* moved folder
* base works, attemp arm
* Contributors: ipa-fmw-ms, ipa-fxm

0.5.1 (2014-03-20)
------------------
* fixed cob_teleop_keyboard
* fix teleop for 3DOF torso
* changes for hydro deps
* Fixed CMakefiles for teleop stuff.
* merged catkin version
* Initial catkinization.
* critial bugfix (buffer overflow)
* fixed wrong debug message
* use 100Hz for teleop
* no waiting for parameters
* fuerte migration, joy msg moved
* adapt roslaunch tests
* fix safety
* teleop with safe base movements
* add dependency to joy
* removed deprecated dependency
* new file teleop_keyboard.launch
* fix robot modules
* removed launch files
* removed launch and configuration files
* remove compiler warnings
* use joy.launch in teleop
* removed compiler warnings
* added cob3-4 configs
* removed compiler warninigs
* config files for cob3-bosch
* added ENV variables to tests
* electric update for teleop
* cleanup arm and dashboard configs
* add stop and recover/init button to teleop
* config for cob3-3
* Merge branch 'master' of github.com:ipa-fmw/cob_apps
* added license header
* add recover base button to teleop
* cob3-2 config for teleop
* changed tinmeout to 1sec
* merge
* teleop with brics messages
* added desire.yaml
* merge
* moved output to DEBUG
* added some usage instruction output
* small bug-fix
* new teleop_keyboard version - includes arm, tray, torso
* fixed teleop jump-back error
* deleted old launch file
* added module parameters for all modules
* added yaml teleop module yaml file for cob3-1
* moved robot specific teleop configuration to external configuration files
* merge
* removed deprecated dependencies
* add dependency to pt2_teleop
* wait only for 1 sec
* added support for brics intefaces to tray and arm
* added brics interface for torso
* cleanup in cob_apps and updated stack.xml's
* research camp challenge
* merge
* renamed camera_axis to head_axis and platform to base
* system cleaned - missing launch files added
* much ado about nothing
* Modified launch files of cob_base_drive_chain, cob_relayboard, cob_undercaariage_ctrl and cob_teleop_ucar and made them hierarchic
* merged with cpc-pk: added ctrl for tricycle-kinematic; specification of limit in CanDriveHarmonica can now be specified via Inifile; base_drive_chain can be operated on variable numbers of motors (lesser or equal to eight); variable setting of path to inifile for UndercarriageCtrlGeom; debugged relaysboard - reads Bus now nonblocking
* -
* merge
* teleop keyboard
* Merge branch 'master' into scriptserver
* performance tuning
* teleoperation with keyboard
* update documentation
* bugfix in teleop
* ramp filter for base_controller
* teleop with deadman and run button
* improved joystick handling
* renamed launch file
* modification on cob3-2
* adaptions for cob3-2
* knoeppkes
* new platform launch file
* deleted teleop keyboard
* update on robot
* dual arm cob3 simulation and modified controllers for schunk simulation
* modifications for navigation with ucar
* adapt device
* merge with cpc
* Added dependencies for build of controllers to cob_teleop package
* implemented, debugged and tested basic undercarriage controller - works on Descartes principal of rigid body motion
* remote controll of torso, tray, arm with joystick is working
* added timeout, if no /joint_states message arrives
* initial values for velocities
* get initial joint values from joint_states topic
* test
* Deployment of undercarriage controller debugged and finished: launch-script cob_ucar_joy starts up relayboard, base_drive_chain and controller; also remaps topics and services in correct namespaces. Debugging of controller itself is work in progress: simplified and removed old stuff - code compiles - controller runs but appaerently has some bugs -> may not yet be used
* Merge branch 'review-cpc'
* introduced env variable ROBOT
* debugging undercarriage drivers (base_drive_chain + relayboard + ucar_ctrl) - work in progress
* cleaning up in cob_apps stack
* modified teleop launch file
* launch file for teleop_cob
* new teleop for cob
* merge
* new stl files for torso
* JSF: Added intrinsics to topic
* debugged ucar controller and base drive chain node - still not running
* reduced velocity of joystick
* better 2d navigation
* test of ROS navigation on cob
* renamed packages to cob_ convention
* Contributors: Alexander Bubeck, COB3-Manipulation, COB3-Navigation, Christian, Florian Weißhardt, Your full name, abubeck, b-it-bots, cpc, fmw, ipa, ipa-bnm, ipa-cob3-3, ipa-cpc, ipa-fmw, ipa-fxm, ipa-taj-dm, ipa-uhr-fm, nhg-ipa, snilsson, uh
