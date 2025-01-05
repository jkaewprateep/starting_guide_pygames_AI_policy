# starting_guide_pygames_AI_policy
Starting guild for Pygame AI training and play ( simple policy )

<p align="center" width="100%">
    <img width="25%" src="https://github.com/jkaewprateep/starting_guide_pygames_AI_policy/blob/main/Python.jpg">
    <img width="24%" src="https://github.com/jkaewprateep/starting_guide_pygames_AI_policy/blob/main/pygame.jpg">
    <img width="18%" src="https://github.com/jkaewprateep/starting_guide_pygames_AI_policy/blob/main/image10.jpg">
    <img width="12%" src="https://github.com/jkaewprateep/starting_guide_pygames_AI_policy/blob/main/image6.jpg"> </br>
    <b> Pygame and Tensorflow AI machine learning </b> </br>
    <b> ( Picture from Internet ) </b> </br>
</p>

[Flappybird games]( https://pygame-learning-environment.readthedocs.io/en/latest/user/games/flappybird.html#rewards )

🧸💬 In some cases of game training we do not have to input all possible action responses to inputs. Still, we can create a  simple policy showing how feedback on the model training is rewarding, the same as reinforcement learning. By simple policy same as we create equation guidelines for machine learning to find solution feedback in the scope with rewards and punishment training feedback method. </br>
🐑💬 ➰ In some cases there are system rules, games rules, and learning methods where games rules and system rules cannot violate to have continuity of the action but to create an equation to respond to more than one goal is difficult to understand by handmaking but it may simple by the machine learning in some case they are main method to find the solution within the scopes we are permitted. </br>
🦭💬 There is no way to form coefficients from our polynomials equation to perform this complex task and vary by its input but simple policy for multiple policies can do it easily by us human merged requirements is one method of the solution from the AI machine learning, merged requirements form today our instruments such as sensors, calibrators, equalizers and even they are using in complex response alarm firewalls or notification system. </br>
🐯💬 Culture-INFO, merged requirements can perform verification by their input as rules bases and test cases this way is similar to the comparison method where there is more than one requirement all are responses to each scenario. </br>
🦁💬 Simple stage policy is also one method to perform verification because AI machines can work as state machines and respond within action they are advised by advisory networks or their dataset, they respond while stage changing within drawing scopes of resolution. </br>

<p align="center" width="100%">
    <img width="25%" src="https://github.com/jkaewprateep/starting_guide_pygames_AI_policy/blob/main/2000%20hits-training.gif"></br>
    <b> Training 2,000 times action by guilding algorithms </b> </br>
</p>
</br>
</br>

🐐💬 Machine learning AI still finds solutions in the scopes of reinforcement machine learning should perform this way to prevent the waste of the computing cycle by inputting our known scopes into the scopes of learning action to solution and we can make it easy as rewards punishment or list of action mapping to machine states. </br>

<p align="center" width="100%">
    <img width="25%" src="https://github.com/jkaewprateep/starting_guide_pygames_AI_policy/blob/main/FlappyBird_small.gif"></br>
    <b> Training more than 10,000 times action by guilding algorithms </b> </br>
</p>
</br>
</br>

🧸💬 There are many way to have this solution but there are many ways to work until this solution by the input of different input, methods, and resources where utilization is compared by how much proficiency is provided by the method compared to simple or another method (the same output from different inputs may have different proficiency)  </br>

🧸💬 Model training
```
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""
: Training
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""
# history = model.fit(dataset, epochs=3, callbacks=[custom_callback])
history = model.fit(dataset, epochs=epochs)
model.save_weights(checkpoint_path)

action = predict_action(DATA);
# print(action)   

bonus_reward = 0;
if action == 1 and apply_policy() :
    bonus_reward = 0.50;     
    
if sum(history.history["loss"]) >=  epochs * 0.21:
    action = random_action(); 

reward = p.act(list(actions.values())[action])
scores = scores + ( reward * 10 ) + bonus_reward;
```

👧💬 🎈 We create rules and policies where machine learning finds solutions for us. </br>
👧💬 🎈 Do not just look up the answer figure it out and apply it to machine learning why only some people can make the Flappy Bird fly though. </br>
```
def apply_policy():
    
    if _gamestate["player_y"] - int(_gamestate["next_pipe_bottom_y"]) > -35 :
        return True
    
    return False
```

---

<p align="center" width="100%">
    <img width="30%" src="https://github.com/jkaewprateep/advanced_mysql_topics_notes/blob/main/custom_dataset.png">
    <img width="30%" src="https://github.com/jkaewprateep/advanced_mysql_topics_notes/blob/main/custom_dataset_2.png"> </br>
    <b> 🥺💬 รับจ้างเขียน functions </b> </br>
</p
