# atari_xai

How to run code:

```
git clone https://github.com/medipixel/rl_algorithms.git
python3 -m venv /xai
```
Lunar Lander:
```
python3 run_lunarlander_continuous_v2.py --cfg-path ./configs/lunarlander_continuous_v2/ddpg.yaml
```
Pong With Gradcam:
```
python3 run_pong_no_frameskip_v4.py --cfg-path ./configs/lunarlander_continuous_v2/dqn.yaml --test --grad-cam
```
