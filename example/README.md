# Mobile-Env Training Examples

This folder contains Jupyter notebooks demonstrating reinforcement learning training on mobile-env environments.

## Notebooks

### mobile_env_training_comparison.ipynb

This notebook demonstrates and compares two approaches to training RL agents on mobile-env:

1. **Stable-Baselines3**: Using the popular SB3 library with PPO algorithm
2. **PufferLib**: Using the performance-optimized PufferLib framework

The notebook includes:
- Environment setup and configuration
- Training with both frameworks
- Performance comparison (training speed)
- TensorBoard logging for visualization
- Model evaluation and comparison

## Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `mobile_env_training_comparison.ipynb`

3. Run all cells to train both models and compare results

4. View training curves in TensorBoard:
```bash
tensorboard --logdir ./logs
```

Then open your browser to http://localhost:6006

## About Mobile-Env

Mobile-env is an open platform for reinforcement learning in wireless mobile networks. It provides realistic simulation environments for network resource allocation, user association, and handover optimization.

For more information, see the [mobile-env repository](https://github.com/stefanbschneider/mobile-env).

## Performance Notes

- **PufferLib** typically provides faster training through vectorization and optimized implementations
- **Stable-Baselines3** offers more mature algorithms and extensive documentation
- Training time depends on your hardware (CPU/GPU)
- For best results, run on a machine with GPU support

## Customization

You can modify the notebook to:
- Try different mobile-env scenarios (small, medium, large)
- Experiment with different RL algorithms
- Adjust hyperparameters for better performance
- Extend training duration
- Implement custom reward shaping

## Citation

If you use mobile-env in your research, please cite:

```bibtex
@inproceedings{schneider2022mobile,
  title={mobile-env: An Open Platform for Reinforcement Learning in Wireless Mobile Networks},
  author={Schneider, Stefan and Werner, Stefan and Khalili, Ramin and Hecker, Artur and Karl, Holger},
  booktitle={IEEE/IFIP Network Operations and Management Symposium (NOMS)},
  year={2022}
}
```
