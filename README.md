# Ex08 CAMU Schedule using Bootstrap
## Date:
28-05-2026

## AIM:
To design a responsive and visually appealing CAMU Schedule using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :

```
<!DOCTYPE html>
<html>
<head>
    <title>CAMU Schedule</title>

    <link rel="stylesheet"
    href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>

    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

    <style>
        body{
            background-color:#f5f5f5;
            padding-top:20px;
        }

        .page-header{
            background:#337ab7;
            color:white;
            padding:15px;
            border-radius:5px;
            margin-top:0;
        }

        .table th{
            text-align:center;
            vertical-align:middle !important;
        }

        .table td{
            text-align:center;
            vertical-align:middle !important;
        }

        .subject{
            background-color:#5bc0de;
            color:white;
            font-weight:bold;
        }

        .lunch{
            background-color:#f0ad4e;
            color:white;
            font-weight:bold;
        }

        .course-table th{
            background-color:#337ab7;
            color:white;
        }

        .timetable th{
            background-color:#337ab7;
            color:white;
        }
    </style>
</head>

<body>

<div class="container">

    <div class="page-header text-center">
        <h2>CAMU Schedule - Even Semester 2025-2026</h2>
        <h4>Student Time Table - Anto Williams S(212224240012)</h4>
    </div>

    <div class="panel panel-primary">

        <div class="panel-heading">
            <h3 class="panel-title">Weekly Schedule</h3>
        </div>

        <div class="panel-body">

            <div class="table-responsive">

                <table class="table table-bordered timetable">

                    <tr>
                        <th>DAY / TIME</th>
                        <th>8 - 10</th>
                        <th>10 - 12</th>
                        <th>12 - 1</th>
                        <th>1 - 3</th>
                        <th>3 - 5</th>
                    </tr>

                    <tr>
                        <th>Monday</th>
                        <td>-</td>
                        <td class="subject">Computer Networks</td>
                        <td rowspan="6" class="lunch">Lunch</td>
                        <td>-</td>
                        <td>-</td>
                    </tr>

                    <tr>
                        <th>Tuesday</th>
                        <td class="subject">FWAD</td>
                        <td class="subject">Python Programming</td>
                        <td class="subject">Computer Networks</td>
                        <td>-</td>
                    </tr>

                    <tr>
                        <th>Wednesday</th>
                        <td class="subject">FWAD</td>
                        <td>-</td>
                        <td class="subject">Mentor Meet</td>
                        <td>-</td>
                    </tr>

                    <tr>
                        <th>Thursday</th>
                        <td>-</td>
                        <td class="subject">Python Programming</td>
                        <td class="subject">Computer Networks</td>
                        <td>-</td>
                    </tr>

                    <tr>
                        <th>Friday</th>
                        <td class="subject">FWAD</td>
                        <td class="subject">Python Programming</td>
                        <td>-</td>
                        <td class="subject">Computer Networks</td>
                    </tr>

                    <tr>
                        <th>Saturday</th>
                        <td class="subject">FWAD</td>
                        <td>-</td>
                        <td class="subject">Python Programming</td>
                        <td>-</td>
                    </tr>

                </table>

            </div>

        </div>

    </div>

    <div class="panel panel-info">

        <div class="panel-heading">
            <h3 class="panel-title">Course Details</h3>
        </div>

        <div class="panel-body">

            <div class="table-responsive">

                <table class="table table-bordered course-table">

                    <tr>
                        <th>S.No</th>
                        <th>Course Code</th>
                        <th>Course Name</th>
                    </tr>

                    <tr>
                        <td>1</td>
                        <td>19AI414</td>
                        <td>Fundamentals of Web Application Development</td>
                    </tr>

                    <tr>
                        <td>2</td>
                        <td>19CS301</td>
                        <td>Python Programming</td>
                    </tr>

                    <tr>
                        <td>3</td>
                        <td>19CS406</td>
                        <td>Computer Networks</td>
                    </tr>

                    <tr>
                        <td>4</td>
                        <td>ECA-M</td>
                        <td>Mentor Meet</td>
                    </tr>

                </table>

            </div>

        </div>

    </div>

</div>

</body>
</html>
```
## OUTPUT:
<img width="1919" height="1147" alt="image" src="https://github.com/user-attachments/assets/20493b95-ec5b-4d56-919d-8624823e9347" />


## RESULT:
A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.
