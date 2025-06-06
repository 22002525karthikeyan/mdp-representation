# MDP REPRESENTATION

## AIM:

To represent a Markov Decision Process(MDP) problem in the following ways.

    Text representation

    Graphical representation

    Python - Dictonary representation

### PROBLEM STATEMENT:

The agent has to reach AR/VR (EEE) lab starting from admin 5th floor. The floor is slippery and the agent has 2 options either to move left or right. Probabillity of moving the desired direction is 0.8.

### State Space

0 : Admin

1 : CSE

2 : ECE

3 : EEE(AR/VR)

### Sample State

The agent is at CSE state -> 1.

### Action Space

Left : 0

Right : 1

### Sample Action

The agent takes left from the current state -> 0.

### Reward Function

R = {+1 if state = 3}

### Graphical Representation

![image](https://github.com/user-attachments/assets/b785ff8b-676e-4673-aa69-2f5a3874d28b)

## PYTHON REPRESENTATION:

```
p = {
    0:{
        0:[(0.8, 1, 0, False), (0.2, 2, 0, False)],
        1:[(0.8, 2, 0, False), (0.2, 1, 0, False)]
    }
    1:{
        0:[(0.8, 1, 0, False), (0.2, 0, 0, False)],
        1:[(0.8, 0, 0, False), (0.2, 1, 0, False)]
    }
    2:{
        0:[(0.8, 0, 0, False), (0.2, 3, 1, True)],
        1:[(0.8, 3, 1, True), (0.2, 0, 0, False)]
    }
}
```

## OUTPUT:



![image](https://github.com/user-attachments/assets/a72dcec8-3512-473d-a1cf-270605064f49)


## RESULT:

Thus the given Markov Decision Process(MDP) problem is represented in the following ways.


