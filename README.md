<h1> High jump agent on OpenAI Gym</h1>

<h3>Install the environment :</h3> 
<code>pip install -e gym-jump</code>

<h3>Create the environment in the project :</h3> 
<code>gym.make('gym_jump:jump-v0')</code>



<h4>TODO :</h4>
- Create the environment for the agent
- Code structure of everything
- Test random agent
- Code smart agent Q learning 
- Fine tune Q learning 
- Code smart agent with RL technique 
- Fine tune  swith RL technique

<h4>Help :</h4>

    The larger the gamma, the smaller the discount. This means the learning agent cares more about the long term reward.
    On the other hand, the smaller the gamma, the bigger the discount. This means our agent cares more about the short term reward (the nearest cheese).

    When the episode ends (the agent reaches a “terminal state”), the agent looks at the total cumulative reward to see how well it did. In Monte Carlo approach, rewards are only received at the end of the game.
    
    
    