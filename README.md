# RL HW3 Practical Code

This repository contains the completed programming files for HW3.

## Files

- `cart_pole.py` - the provided cart-pole simulator and discretization code.
- `control.py` - off-policy model-based cart-pole controller. The completed sections initialize the empirical MDP, choose greedy actions from the estimated model, update transition/reward statistics, and run value iteration after failures.
- `tabular_Q.py` - tabular Q-learning implementation for FrozenLake.
- `network_Q.py` - one-layer Q-network implementation for FrozenLake using one-hot state vectors.

## Running

The handout code expects the older Gym API:

```bash
python control.py
python tabular_Q.py
python network_Q.py
```

The practical outputs are reported separately in `results/OUTPUTS.md`, and the cart-pole learning curve is saved as `results/cart_pole_learning_curve.svg`.
