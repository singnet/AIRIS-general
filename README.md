# <ins>AIRIS General</ins>

This AIRIS takes time series data from any environment and attempts to find causal relationships in the changes in the data over time. If actions are available for the agent to perform, it will experiment with the actions to determine how the actions affect the inputs. If no actions are provided, it will act as an oracle and attempt to predict future changes. If the agent is given a goal, it will attempt to plan sequences of actions to acheive the goal. If it does not have a goal, it will attempt to refine the accuracy of its predictions.
