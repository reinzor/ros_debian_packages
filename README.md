```bash
echo "deb [trusted=yes] https://github.com/reinzor/ros_debian_packages/raw/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/reinzor_ros_debian_packages.list
echo "yaml https://github.com/reinzor/ros_debian_packages/raw/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-reinzor_ros_debian_packages.list
```
