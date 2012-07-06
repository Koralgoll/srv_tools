Systems, Robotics and Vision Group (SRV)
========================================

ROS stack with some tools. Separated in bagfile related tools and tf related tools.

## bag_tools

### extract_stereo_images

* Description

Extracts images from a list of bagfiles to a folder. The images extracted are rectified and syncronized.

### bag_add_time_offset

* Description

Adds a defined offset time to the topics you require.

### change_camera_info

* Description

Changes camera info messages in a bagfile

### check_delay

* Description

Checks the delay in a bagfile between publishing (recording) time and the time
stamp in the header (if exists). Prints out min, max and mean delays.

### replace_msg_time_with_hdr

* Description

Replaces the timestamp of the messages in a bagfile for the timestamp in the headers.

### add_header_time_offset

* Description

Changes header timestamps using given offset, can change/tf as well.

### camera_info_parser

* Description

Parses camera info yaml files and returns them as sensor_msgs.msg.CameraInfo.

### change_frame_id

* Description

Changes the frame_id of the selected topics to the desired frame_id

### image_sequence_publisher

* Description

Publishes a folder full of images as if it was a normal camera topic and it's related camera info topic. Works with jpg images.