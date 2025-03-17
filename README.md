# ENPH353_Lab7

Training my robot Windows to be an obstacle course master using Q-Learning.

There are 11*11 states, with 3 actions for each state, so the Q dictionary is small enough to make Q-Learning a good approach for this problem. 

She's slowly getting  there!

### Build and install gym-gazebo and then launch gazebo line follow

In the root directory of the repository:

```bash
sudo pip install -e .
```

To run the cartpole environment go to directory where gym-gazebo is contained, then run:
```
source ~/enph353_gym-gazebo-noetic/gym_gazebo/envs/ros_ws/devel/setup.bash
python3 ~/enph353_gym-gazebo-noetic/examples/gazebo_linefollow_ex/gazebo_linefollow_ex.py
```
