# ANSIBLE ROS

## Dependencies

```bash
sudo apt install ansible git -y
```

## Usage
Installing ROS
```bash
ansible-pull -U https://github.com/brucechanjianle/ansible-ros -e "ros_distribution=noetic" -K
```

For Docker
```bash
ansible-pull -U https://github.com/brucechanjianle/ansible-ros -e "ros_distribution=noetic"
```

## Reference

- https://github.com/BruceChanJianLe/ansible-ros2
