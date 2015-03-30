^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ps4eye
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.4 (2015-03-30)
------------------
* Fix create_udev_rules option. Change README.md.
* Add udev install script.
* Automatically loading firmware.
* all need is to run create_udev_rules script.
* add viewer argment to stereo.launch. Set true to bring up stereo viewer.
* Add ps4eye/ps4eye files and update README.md contents.
* using  to nodelet manager name
* use gscam nodelet instead of gscam node
* use load_driver, instead of setting DEVICE false to check use real camera
* Contributors: Hiroaki Yaguchi, Ron Tajima

0.0.3 (2015-03-16)
------------------
* Merge pull request `#9 <https://github.com/longjie/ps4eye/issues/9>`_ from hyaguchijsk/bagfile_player_mode
  Bagfile player mode
* if DEVICE is false, gscam does not run, to use bag file including /camera/{image_raw,camera_info}
* add arg PUBLISH_TF, if false static_transform_publisher will not run.
* Merge pull request `#8 <https://github.com/longjie/ps4eye/issues/8>`_ from hyaguchijsk/using_nodelet_for_stereo_image_proc
  Great!
  change stereo_image_proc from node to nodelet
* change stereo_image_proc from node to nodelet
* Merge pull request `#7 <https://github.com/longjie/ps4eye/issues/7>`_ from hyaguchijsk/add_camera_info_file_left_and_right_args
  add arguments camera_info_file_{left,right} to set calib files when incl...
* add arguments camera_info_file_{left,right} to set calib files when including stereo.launch
* 0.0.2
* Merge pull request `#5 <https://github.com/longjie/ps4eye/issues/5>`_ from k-okada/add_init
  update CHANGELOG
* update CHANGELOG
* Merge pull request `#4 <https://github.com/longjie/ps4eye/issues/4>`_ from k-okada/use_param_for_camera_info_yaml
  use param to set camera_info
* Merge pull request `#2 <https://github.com/longjie/ps4eye/issues/2>`_ from k-okada/for_release
  update for release
* Merge pull request `#1 <https://github.com/longjie/ps4eye/issues/1>`_ from k-okada/patch-1
  Update README.md
* Merge pull request `#3 <https://github.com/longjie/ps4eye/issues/3>`_ from k-okada/add_arg_in_launch
  add arg for camera_info and camera_transformation
* use param to set camera_info
* add run_depends
* add arg for camera_info and camera_transformation
* add install rule
* add license and author
* Update README.md
  ps4eys_init は ps4_init.py ??? -> https://github.com/ps4eye/ps4eye/tree/master/python
* Contributors: Hiroaki Yaguchi, Kei Okada, Ron Tajima

0.0.2 (2015-01-08)
------------------
* use param to set camera_info
* add run_depends
* add arg for camera_info and camera_transformation
* add install rule
* add license and author
* Update README.md (ps4eys_init is ps4_init.py)
* Contributors: Kei Okada, Ron Tajima

0.0.1 (2014-12-28)
------------------
* I found kenel 3.16 does not detect ps4eye, update document
* Update README.md
* change to use rospack.find to locate camera_info.
* Merge branch 'camera_config'
* add camera_info to camera_info directory.
* add README. add stereo_image_proc to launch file.
* add ps4eye: Playstation4 stereo camera launching set for ROS.
* Contributors: Ron Tajima, Ryohei Ueda, 
