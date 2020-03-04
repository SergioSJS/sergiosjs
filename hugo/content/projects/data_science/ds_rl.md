{
  "title": "Reinforcement Learning",
  "date": "2018-07-11T12:41:05-05:00",
  "image": "/img/rl.jpg",
  "link": "https://github.com/SergioSJS/reinforcement-learning",
  "description": "Some tests with reinforcement learning algorithms, including qlearn, sarsa, lambda sarsa, deep q learning",
  "tags": ["python","analysis", "Machine Learning", "reinforcement learning", "q-learning", "keras", "tensorflow", "deep-learning"],
  "fact": "",
  "featured":true
}

In this project it was verified my reinforcement learning algorithm and test the deep-q-learning applying in Atari games. Also check the domain adaptation technique in 2 games of Atari 2600, Space Invaders and Demon Attack, games with similar gameplay and style. The goal of creating a generalist model capable of playing more than one game and trying to help it converge more quickly. We noticed that the domain transfer slowed learning but allowed a higher score at the beginning of the training. When comparing the models trained in two games and testing them in the domain of origin, we could verify that the model forgets what it has learned, reaching a score close to random.

![test](/img/rl.jpg#center)