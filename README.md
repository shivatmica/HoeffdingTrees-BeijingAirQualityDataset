# Beijing-Air-Quality-Dataset
#
Model Parameters:
```
{'binary_split': False,
 'grace_period': 200,
 'leaf_prediction': 'perceptron',
 'learning_ratio_const': True,
 'learning_ratio_decay': 0.001,
 'learning_ratio_perceptron': 0.02,
 'max_byte_size': 33554432,
 'memory_estimate_period': 1000000,
 'nb_threshold': 0,
 'no_preprune': False,
 'nominal_attributes': None,
 'random_state': None,
 'remove_poor_atts': False,
 'split_confidence': 1e-07,
 'stop_mem_management': False,
 'tie_threshold': 0.05}
 ```
#
Hoeffding Tree regressor mean absolute error: $5.545911457093758$
#

Flow of the Tree
```
if Attribute 33 <= -0.12201616357316761:
  if Attribute 42 <= -1.3465633318470427:
    Leaf = Statistics {0: 355.0000, 1: -87661.9377, 2: 27022418.5884}
  if Attribute 42 > -1.3465633318470427:
    if Attribute 42 <= -0.5554716493675651:
      if Attribute 5 <= -0.7898185034106747:
        Leaf = Statistics {0: 161.0000, 1: -44207.9198, 2: 14204387.1508}
      if Attribute 5 > -0.7898185034106747:
        if Attribute 33 <= -1.805516922646181:
          Leaf = Statistics {0: 30.0000, 1: -7945.5292, 2: 2280678.6468}
        if Attribute 33 > -1.805516922646181:
          Leaf = Statistics {0: 583.0000, 1: -77152.0520, 2: 17516918.3311}
    if Attribute 42 > -0.5554716493675651:
      if Attribute 5 <= -0.21414182354084862:
        if Attribute 42 <= 0.3002343835153617:
          Leaf = Statistics {0: 376.0000, 1: -64090.3060, 2: 15557653.9568}
        if Attribute 42 > 0.3002343835153617:
          if Attribute 33 <= -1.919471865139141:
            Leaf = Statistics {0: 14.0000, 1: -3213.7499, 2: 917093.9707}
          if Attribute 33 > -1.919471865139141:
            Leaf = Statistics {0: 614.0000, 1: -38776.3824, 2: 11693940.5736}
      if Attribute 5 > -0.21414182354084862:
        Leaf = Statistics {0: 2457.0000, 1: -40592.3561, 2: 54527599.9720}
if Attribute 33 > -0.12201616357316761:
  if Attribute 42 <= -0.471842620557707:
    if Attribute 5 <= -0.73584585212081:
      Leaf = Statistics {0: 350.0000, 1: -45129.3752, 2: 11404366.7272}
    if Attribute 5 > -0.73584585212081:
      if Attribute 44 <= -0.786781503202143:
        Leaf = Statistics {0: 224.0000, 1: -18299.6647, 2: 4567768.1680}
      if Attribute 44 > -0.786781503202143:
        if Attribute 33 <= 0.4004569787946908:
          Leaf = Statistics {0: 221.0000, 1: -10909.8180, 2: 3390514.3851}
        if Attribute 33 > 0.4004569787946908:
          if Attribute 91 <= 1.0600620243143195:
            Leaf = Statistics {0: 233.0000, 1: 13168.1075, 2: 3945016.8862}
          if Attribute 91 > 1.0600620243143195:
            Leaf = Statistics {0: 523.0000, 1: 3422.1224, 2: 8096957.7686}
  if Attribute 42 > -0.471842620557707:
    if Attribute 5 <= -0.3252344846272188:
      if Attribute 42 <= -0.17681894286620653:
        Leaf = Statistics {0: 153.0000, 1: -4031.4962, 2: 2275184.7897}
      if Attribute 42 > -0.17681894286620653:
        if Attribute 42 <= 0.5379210694247393:
          Leaf = Statistics {0: 321.0000, 1: 2810.8409, 2: 3686877.6085}
        if Attribute 42 > 0.5379210694247393:
          Leaf = Statistics {0: 673.0000, 1: 60361.7530, 2: 15387143.3101}
    if Attribute 5 > -0.3252344846272188:
      Leaf = Statistics {0: 2712.0000, 1: 392021.9879, 2: 108665974.8560}
```
Details of the Tree:
{'Active leaf byte size estimate': 0.0,
 'Active learning nodes': 17,
 'Byte size estimate overhead': 1.0,
 'Inactive leaf byte size estimate': 0.0,
 'Tree depth': 6,
 'Tree size (leaves)': 17,
 'Tree size (nodes)': 33}
