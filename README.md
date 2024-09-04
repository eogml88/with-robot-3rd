# 1. Env
```
pip install coppeliasim-zmqremoteapi-client
pip install numpy
pip install pynput
pip install matplotlib
```

# pendulum_1d

## 1. Control by Keyboard [control_by_keyboard.py](./pendulum_1d/control_by_keyboard.py)
- right arrow: positive force
- left arrow: negative force
- q: quit simulator
![mapping distance and angle](./images/pendulum_1d_control_by_keyboard.gif)
# youBot

## 1. Control by Keyboard [control_by_keyboard.py](./youBot/control_by_keyboard.py)
- arrow: wheel
- w, s: joint-0
- e, d: joint-1
- r, f: joint-2
- t, g: joint-3
- y, h: joint-4
- u, j: gripper
- q: quit simulator

## 2. mapping Distance and angle [mapping_distance_angle.py](./youBot/mapping_distance_angle.py)
- 가정: 정확한 자동차 위치를 알고 있음
- 목표: 100x100 grid 내에서 탐색 가능한 지역을 numpy를 이용해 계산 및 시각화
- 동작확인:
![mapping distance and angle](./images/youbot_mapping_distance_angle.gif)