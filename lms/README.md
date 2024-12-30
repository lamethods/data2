# LMS data

This is a synthetic dataset based on the study by Jovanović et al. [1]
and consists mostly of behavioral engagement indicators that can be
obtained from learning management system (LMS) trace-log data. These
variables capture both the engagement behavior of students (e.g.,
frequency and regularity of course and forum activities) and their
participatory and time investment in the course (e.g., total duration,
active days, session count) as well as the regularity of participation.
Both time and regularity may be considered proxy indicators of cognitive
engagement. We can also consider forum contributions as indicators of
cognitive engagement since the context is problem-based learning, and
student contributions require students to read, synthesize, critique,
and formulate arguments.

-   **Frequency Variables**
    -   **Freq_Course_View**: The frequency of course page views by the
        student.
    -   **Freq_Forum_Consume**: The frequency with which the student
        consumes content in the forum (i.e., reads forum posts).
    -   **Freq_Forum_Contribute**: The frequency with which the student
        contributes to the forum (i.e., posts in the forum).
    -   **Freq_Lecture_View**: The frequency of lecture video views by
        the student.
-   **Regularity Variables**
    -   **Regularity_Course_View**: The consistency of the student’s
        course page views.
    -   **Regularity_Lecture_View**: The consistency of the student’s
        lecture video views.
    -   **Regularity_Forum_Consume**: The consistency of the student’s
        forum content consumption.
    -   **Regularity_Forum_Contribute**: The consistency of the
        student’s forum contributions.
-   **Time Variables**
    -   **Session_Count**: The total number of sessions the student has
        participated in.
    -   **Total_Duration**: The total duration (in seconds) of all
        sessions participated by the student.
    -   **Active_Days**: The number of days the student was active in
        the course.
-   **Outcome Variables**
    -   **Final_Grade**: The final grade of the student in the course.

<!-- -->

                                    mean       sd   median      min       max
    Freq_Course_View              223.79    59.33   222.00    51.00    356.00
    Freq_Forum_Consume            582.55   175.55   589.00    84.00    991.00
    Freq_Forum_Contribute         178.07    55.57   175.00    17.00    347.00
    Freq_Lecture_View             201.87    56.68   202.00    32.00    346.00
    Regularity_Course_View          0.51     0.14     0.52     0.15      0.90
    Regularity_Lecture_View         0.48     0.15     0.49     0.07      0.80
    Regularity_Forum_Consume        0.49     0.14     0.50     0.13      0.95
    Regularity_Forum_Contribute     0.48     0.16     0.47     0.03      0.90
    Session_Count                 189.54    52.83   191.00    53.00    306.00
    Total_Duration              83150.98 23818.16 83667.00 25055.00 147827.00
    Active_Days                    16.06     4.15    16.00     5.00     31.00
    Final_Grade                    68.62     8.86    68.66    44.73     90.89

[1] Jovanović J, Saqr M, Joksimović S, Gašević D (2021) Students matter
the most in learning analytics: The effects of internal and
instructional conditions in predicting academic success. Comput Educ
172:104251. https://doi.org/10.1016/j.compedu.2021.104251\] The dataset
has the following variables:
