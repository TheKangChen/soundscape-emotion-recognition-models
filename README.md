# Soundscape Emotion Recognition Models
Neural Networks for predicting Russell's valence and arousal circumplex model of affect for soundscapes.

---
<br>

### Feature Set Dimensions
- Database feature set dimension: 1213 x 122
- Reduced feature set dimension: 1213 x 74

---
<br>

### Trained Neural Network
|                    | Arousal | Valence |
| :----------------: | :-----: | :-----: |
|      R Squared     | 0.8684  | 0.7281  |
| Mean Squared Error | 0.0438  | 0.0906  |
---
<br>

### SVR baseline model (122 x 1)
|       Arousal      |    Mean   |    Std    |
| :----------------: | :-------: | :-------: |
|      R Squared     | 0.793712  | 0.031416  |
| Mean Squared Error | 0.067285  | 0.009299  |

|       Valence      |    Mean   |    Std    |
| :----------------: | :-------: | :-------: |
|      R Squared     | 0.562547	 | 0.048298  |
| Mean Squared Error | 0.143315  | 0.014217  |

<br>

### SVR reduced feature model (74 x 1)
|       Arousal      |    Mean   |    Std    |
| :----------------: | :-------: | :-------: |
|      R Squared     | 0.785556  | 0.026073  |
| Mean Squared Error | 0.071068  | 0.009651  |

|       Valence      |    Mean   |    Std    |
| :----------------: | :-------: | :-------: |
|      R Squared     | 0.547271	 | 0.051466  |
| Mean Squared Error | 0.148914  | 0.011666  |
---
<br>

### Neural Network (122 x 1)
|       Arousal      |    Mean   |    Std    |
| :----------------: | :-------: | :-------: |
|      R Squared     | 0.722813  | 0.235087  |
| Mean Squared Error | 0.068943	 | 0.033179  |

|       Valence      |    Mean   |    Std    |
| :----------------: | :-------: | :-------: |
|      R Squared     | 0.494576	 | 0.173223  |
| Mean Squared Error | 0.137190	 | 0.030402  |

<br>

### Neural Network reduced feature (74 x 1)
|       Arousal      |    Mean   |    Std    |
| :----------------: | :-------: | :-------: |
|      R Squared     | 0.730940  | 0.161783  |
| Mean Squared Error | 0.070679	 | 0.028536  |

|       Valence      |    Mean   |    Std    |
| :----------------: | :-------: | :-------: |
|      R Squared     | 0.504163	 | 0.121443  |
| Mean Squared Error | 0.138414	 | 0.038270  |

<br>

---
### Reference
- Database from Emo-Soundscapes: https://metacreation.net/emo-soundscapes/