
## Dependencies

```shell
# install pcap library
sudo apt-get install git libpcap-dev 

# install ros-<DISTRO>-geometry2
sudo apt-get install ros-noetic-geometry2
```

## Reference

1. [Getting Started with the Velodyne VLP16](http://wiki.ros.org/velodyne/Tutorials/Getting%20Started%20with%20the%20Velodyne%20VLP16)
2. [Velodyne](http://wiki.ros.org/velodyne?distro=noetic)
    - Point cloud conversions for Velodyne 3D LIDARs: [velodyne_pointcloud](http://wiki.ros.org/velodyne_pointcloud?distro=noetic)

Overview
========

Velodyne<sup>1</sup> is a collection of ROS<sup>2</sup> packages supporting `Velodyne high
definition 3D LIDARs`<sup>3</sup>.

**Warning**:

  The master branch normally contains code being tested for the next
  ROS release.  It will not always work with every previous release.
  To check out the source for the most recent release, check out the
  tag `<version>` with the highest version number.

The current ``master`` branch works with ROS Kinetic and Melodic.
CI builds are currently run for Kinetic and Melodic.

- <sup>1</sup>Velodyne: http://www.ros.org/wiki/velodyne
- <sup>2</sup>ROS: http://www.ros.org
- <sup>3</sup>`Velodyne high definition 3D LIDARs`: http://www.velodynelidar.com/lidar/lidar.aspx
