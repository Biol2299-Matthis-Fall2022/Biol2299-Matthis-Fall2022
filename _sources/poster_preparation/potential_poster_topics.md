# Potential Poster Topics
____
## 00 -  FreeMoCap Methods poster

A poster discussing the shared methodolgy underlying the data collection process for these posters.

Focusing on `freemocap` methods and `python` based analysis

### keywords:
#motion-capture
#kinematics
#geometry
#python
#data-analysis
#machine-learning

___
## 01 - The Neural Control of Standing Posture

A general overview of the neural control of standing posture, with a focus on the role of:
- The central nervous system
    -Cortex
    -Cerebellum
    -Brainstem
    -Spinal cord
- The peripheral nervous system
    -Sensory modalities
    -Sensory systems
        - Vision
        - Vestibular
        - Proprioception
        - Somatosensation (touch)
    -Motor pathways
- The musculoskeletal system
    -Muscle
    -Joint
    -Bone

### Potential data analysis
- Postural sway (COM trajectory, aka 'path length')
- compare against different conditions

____
## 02 - The mechanics of standing balance

A general overview of the biomechanics of standing balance, with a focus on the `Center of Mass` vs `Base of Support` model of posture

## Potential data analysis
 - COM vs BOS in different conditions
    - two footed stance  vs one footed
- That cool result where COM was directly over the toe (for one subject, at least! Will that trend be in the other sub's data???)

____

## 03 -  Compensatory Postural Adjustments
How do our nervous systems "know" how to keep balance? We don't have a direct "center of mass" detector, so how do we know how to keep our COM within our BOS?

### Potential data analysis
- COM vs BOS in different weighted conditions (it will be offset, but why? what does this tell us about the neural control of balance?)
- Potentially correct for the weight in the hand - can we 'fix' the COm calculation to reflect the weight in the hand?

___
## 04 - Jumping

We have that one record of me jumping (maybe we have two?)

Physics says that during that jump my COM will be following a 'perfect' parabolic trajectory - can we find that in the data? Can we learn anything about the neural control of movement by analyzing this behavior?

### Potential data analysis
- COM trajectory during jump
    - The acceleration should be exactly -9.812 m/s^2 (aka gravity) - how close is our actual measurement? Why might it be off?
- If we combine this data with Newton's 3 laws, can we calulate the force on the ground on my foot?
