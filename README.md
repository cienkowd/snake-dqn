# Snake DQN

> Snake agent trained with Deep Q-Learning, comparing a linear Q-network with a deeper DQN.

## Run

```bash
pip install -r requirements.txt
python agent.py
```

Trains both models (`Linear_QNet`, `DQN`) and plots score per game. Trained weights are in `model/`.

## Credits

The game environment and training loop are based on [patrickloeber/snake-ai-pytorch](https://github.com/patrickloeber/snake-ai-pytorch). The `DQN` model variant and the model comparison are my additions.

---

Built as coursework for Applied Computer Science at Warsaw University of Technology.
