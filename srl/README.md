# Multimodal data

This synthetic dataset contains phone activity variables and
self-regulated learning (SRL) variables. The phone activity variables
represent various physical and behavioral patterns related to daily
activities, giving us insights into a person’s physical and digital
behavior, which may affect learning performance.

These include the following features:

-   **`"meanpace"`**: average pace of movement
-   **`"steps"`**: the number of steps taken
-   **`"freqscreen"`**: frequency of screen use
-   **`"duration"`**: duration of screen usage
-   **`"scrrenoff"`**: time the screen is off
-   **`"nightduroff"`**: duration of screen-off time during the night
-   **`"maxoffscreennight"`**: the longest period during which the
    screen is off at night.

The **SRL variables** capture key aspects of cognitive and emotional
self-regulation, which are crucial for understanding how learners manage
and control their learning processes. These variables are derived from
self-reported data reflecting various self-regulated learning
strategies. They include:

-   **`"efficacy"`**: The belief in one’s ability to complete learning
    tasks effectively.
-   **`"value"`**: The perceived importance or value of learning tasks.
-   **`"planning"`**: The ability to plan and organize learning
    activities ahead of time.
-   **`"monitoring"`**: Keeping track of learning progress and task
    completion.
-   **`"effort"`**: The amount of effort put into learning tasks.
-   **`"control"`**: The ability to resist distractions and stay focused
    on learning.
-   **`"help"`**: Seeking help from teachers, friends, or other
    resources when needed.
-   **`"social"`**: Interactions and feelings of belonging within the
    college or learning community.
-   **`"organizing"`**: Organizing and structuring study time and
    materials.
-   **`"motivated"`**: The level of motivation and enthusiasm towards
    learning and achieving better grades.
-   **`"feedback"`**: Learning from feedback to improve performance.
-   **`"evaluating"`**: Self-evaluating one’s work to improve skills and
    performance.
-   **`"anxiety"`**: The level of anxiety or stress experienced during
    learning or in tasks.
-   **`"enjoyment"`**: The amount of enjoyment and satisfaction gained
    from completing tasks and achieving goals.

|                   |    n |     mean |       sd |   median |  min |      max |
|:------------------|-----:|---------:|---------:|---------:|-----:|---------:|
| efficacy          | 5610 |    54.02 |    26.75 |    56.25 | 0.00 |   100.00 |
| value             | 5603 |    56.57 |    26.55 |    59.18 | 0.00 |   100.00 |
| planning          | 5612 |    56.83 |    26.65 |    58.62 | 0.00 |   100.00 |
| monitoring        | 5611 |    49.09 |    29.88 |    52.00 | 0.00 |   100.00 |
| effort            | 5608 |    58.99 |    26.92 |    62.69 | 0.00 |   100.00 |
| control           | 5606 |    52.75 |    29.67 |    55.81 | 0.00 |   100.00 |
| help              | 5604 |    62.10 |    27.54 |    66.27 | 0.00 |   100.00 |
| social            | 5547 |    56.54 |    30.00 |    60.00 | 0.00 |   100.00 |
| organizing        | 5612 |    55.49 |    27.64 |    57.69 | 0.00 |   100.00 |
| motivated         | 5612 |    55.66 |    28.01 |    60.88 | 0.00 |   100.00 |
| feedback          | 5612 |    53.70 |    26.41 |    56.14 | 0.00 |   100.00 |
| evaluating        | 5612 |    50.07 |    26.61 |    52.00 | 0.00 |   100.00 |
| anxiety           | 5607 |    58.34 |    30.03 |    60.34 | 0.00 |   100.00 |
| enjoyment         | 5585 |    54.94 |    27.28 |    56.45 | 0.00 |   100.00 |
| learning          | 5575 |    57.86 |    28.37 |    61.84 | 0.00 |   100.00 |
| meanpace          | 3619 |     0.17 |     0.35 |     0.00 | 0.00 |     4.23 |
| steps             | 1831 |  2189.46 |  3067.46 |   795.00 | 0.00 | 19199.00 |
| freqscreen        | 3819 |    64.38 |    71.20 |    40.00 | 0.00 |   508.00 |
| duration          | 3819 |  8766.37 |  7108.09 |  7693.32 | 0.00 | 66658.53 |
| scrrenoff         | 3819 | 15944.32 | 10741.81 | 15027.52 | 0.00 | 56500.47 |
| nightduroff       | 3819 | 16394.48 | 13904.40 | 12698.46 | 0.00 | 70268.10 |
| maxoffscreennight | 3819 |  6469.52 |  8557.41 |  3267.79 | 1.97 | 47161.37 |
| clusterc          | 3819 |     1.57 |     0.49 |     2.00 | 1.00 |     2.00 |
