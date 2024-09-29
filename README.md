# DeepSSF ISBE2024
Additional details to accompany a poster titled 'Predicting animal movement with deepSSF: a deep learning step selection framework

# Animations of a simulated animal 'exploring' a landscape

## Habitat selection predictions
The simulated animal is in the centre of the landscape, and at each step the local landscape is evaluated for its suitability. 

![](hab_probs.gif)

## Step selection predictions
The simulated animal is in the centre of the landscape, and at each step the local landscape is evaluated for its suitability, which is combined with the learned movement dynamics of the animal.

![](step_probs.gif)

## Landscape-scale predictions
As convolution filters are fixed in size and apply transformations uniformly across grids, they can be applied to any landscape extent to approximate habitat selection (without accounting for movement dynamics). Here we show habitat selection across the hours of the day in the late-dry season.

![](id2005_landscape_habitat_suitability.gif)

### For further details or a copy of the paper that was submitted for peer-review contact Scott Forrest at scott.forrest@hdr.qut.edu.au.
