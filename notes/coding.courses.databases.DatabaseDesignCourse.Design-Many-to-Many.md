---
id: rzggviv5075htgv36emvqdy
title: Design-Many-to-Many
desc: ''
updated: 1654185172761
created: 1654183797156
---
<br>

**create intermediary table with ids of both tables** 

<br>

class table

|id|class_name|
|:--:|:--:|
|5|Math|
|9|Art|
|2|Science|

<BR>
intermediary table

|id|class_id|student_id|
|:--:|:--:|
|5|5|5|
|2|9|5|
|3|5|4|
|4|2|4|
|1|9|7|

<br>


student table

|id|student_name|
|:--:|:--:|
|5|John|
|4|Joe|
|7|Paul|


