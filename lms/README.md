# LMS

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

<div id="cljbphusqq" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#cljbphusqq table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#cljbphusqq thead, #cljbphusqq tbody, #cljbphusqq tfoot, #cljbphusqq tr, #cljbphusqq td, #cljbphusqq th {
  border-style: none;
}

#cljbphusqq p {
  margin: 0;
  padding: 0;
}

#cljbphusqq .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#cljbphusqq .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#cljbphusqq .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#cljbphusqq .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#cljbphusqq .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#cljbphusqq .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#cljbphusqq .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#cljbphusqq .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#cljbphusqq .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#cljbphusqq .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#cljbphusqq .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#cljbphusqq .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#cljbphusqq .gt_spanner_row {
  border-bottom-style: hidden;
}

#cljbphusqq .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#cljbphusqq .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#cljbphusqq .gt_from_md > :first-child {
  margin-top: 0;
}

#cljbphusqq .gt_from_md > :last-child {
  margin-bottom: 0;
}

#cljbphusqq .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#cljbphusqq .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#cljbphusqq .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#cljbphusqq .gt_row_group_first td {
  border-top-width: 2px;
}

#cljbphusqq .gt_row_group_first th {
  border-top-width: 2px;
}

#cljbphusqq .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#cljbphusqq .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#cljbphusqq .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#cljbphusqq .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#cljbphusqq .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#cljbphusqq .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#cljbphusqq .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#cljbphusqq .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#cljbphusqq .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#cljbphusqq .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#cljbphusqq .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#cljbphusqq .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#cljbphusqq .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#cljbphusqq .gt_left {
  text-align: left;
}

#cljbphusqq .gt_center {
  text-align: center;
}

#cljbphusqq .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#cljbphusqq .gt_font_normal {
  font-weight: normal;
}

#cljbphusqq .gt_font_bold {
  font-weight: bold;
}

#cljbphusqq .gt_font_italic {
  font-style: italic;
}

#cljbphusqq .gt_super {
  font-size: 65%;
}

#cljbphusqq .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#cljbphusqq .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#cljbphusqq .gt_indent_1 {
  text-indent: 5px;
}

#cljbphusqq .gt_indent_2 {
  text-indent: 10px;
}

#cljbphusqq .gt_indent_3 {
  text-indent: 15px;
}

#cljbphusqq .gt_indent_4 {
  text-indent: 20px;
}

#cljbphusqq .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="mean">mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="sd">sd</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="median">median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="min">min</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="max">max</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="mean" class="gt_row gt_right">223.79</td>
<td headers="sd" class="gt_row gt_right">59.33</td>
<td headers="median" class="gt_row gt_right">222.00</td>
<td headers="min" class="gt_row gt_right">51.00</td>
<td headers="max" class="gt_row gt_right">356.00</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">582.55</td>
<td headers="sd" class="gt_row gt_right">175.55</td>
<td headers="median" class="gt_row gt_right">589.00</td>
<td headers="min" class="gt_row gt_right">84.00</td>
<td headers="max" class="gt_row gt_right">991.00</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">178.07</td>
<td headers="sd" class="gt_row gt_right">55.57</td>
<td headers="median" class="gt_row gt_right">175.00</td>
<td headers="min" class="gt_row gt_right">17.00</td>
<td headers="max" class="gt_row gt_right">347.00</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">201.87</td>
<td headers="sd" class="gt_row gt_right">56.68</td>
<td headers="median" class="gt_row gt_right">202.00</td>
<td headers="min" class="gt_row gt_right">32.00</td>
<td headers="max" class="gt_row gt_right">346.00</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">0.51</td>
<td headers="sd" class="gt_row gt_right">0.14</td>
<td headers="median" class="gt_row gt_right">0.52</td>
<td headers="min" class="gt_row gt_right">0.15</td>
<td headers="max" class="gt_row gt_right">0.90</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">0.48</td>
<td headers="sd" class="gt_row gt_right">0.15</td>
<td headers="median" class="gt_row gt_right">0.49</td>
<td headers="min" class="gt_row gt_right">0.07</td>
<td headers="max" class="gt_row gt_right">0.80</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">0.49</td>
<td headers="sd" class="gt_row gt_right">0.14</td>
<td headers="median" class="gt_row gt_right">0.50</td>
<td headers="min" class="gt_row gt_right">0.13</td>
<td headers="max" class="gt_row gt_right">0.95</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">0.48</td>
<td headers="sd" class="gt_row gt_right">0.16</td>
<td headers="median" class="gt_row gt_right">0.47</td>
<td headers="min" class="gt_row gt_right">0.03</td>
<td headers="max" class="gt_row gt_right">0.90</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">189.54</td>
<td headers="sd" class="gt_row gt_right">52.83</td>
<td headers="median" class="gt_row gt_right">191.00</td>
<td headers="min" class="gt_row gt_right">53.00</td>
<td headers="max" class="gt_row gt_right">306.00</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">83,150.98</td>
<td headers="sd" class="gt_row gt_right">23,818.16</td>
<td headers="median" class="gt_row gt_right">83,667.00</td>
<td headers="min" class="gt_row gt_right">25,055.00</td>
<td headers="max" class="gt_row gt_right">147,827.00</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">16.06</td>
<td headers="sd" class="gt_row gt_right">4.15</td>
<td headers="median" class="gt_row gt_right">16.00</td>
<td headers="min" class="gt_row gt_right">5.00</td>
<td headers="max" class="gt_row gt_right">31.00</td></tr>
    <tr><td headers="mean" class="gt_row gt_right">68.62</td>
<td headers="sd" class="gt_row gt_right">8.86</td>
<td headers="median" class="gt_row gt_right">68.66</td>
<td headers="min" class="gt_row gt_right">44.73</td>
<td headers="max" class="gt_row gt_right">90.89</td></tr>
  </tbody>
  
  
</table>
</div>

[1] Jovanović J, Saqr M, Joksimović S, Gašević D (2021) Students matter
the most in learning analytics: The effects of internal and
instructional conditions in predicting academic success. Comput Educ
172:104251. https://doi.org/10.1016/j.compedu.2021.104251\] The dataset
has the following variables:
