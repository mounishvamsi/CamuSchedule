# Ex08 CAMU Schedule using Bootstrap
## Date:09-06-2026

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
Add the Bootstrap CDN link inside the <head> section.

### Step 5:
Insert a table element with Bootstrap table classes.

### Step 6:
Construct the complete table.

### Step 7:
Add a header/footer displaying copyright information.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM :
```
<html>
<head>

<title>Camu Timetable</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<style>

body{
margin:0;
font-family:Segoe UI;
background:#f5f6f8;
}

.header{
background:#ffffff;
padding:15px 30px;
font-size:20px;
font-weight:600;
border-bottom:1px solid #ddd;
}

.container{
display:flex;
}


.sidebar{
width:240px;
background:white;
border-right:1px solid #ddd;
}

.logo{
text-align:center;
padding:20px;
border-bottom:1px solid #eee;
}

.logo img{
width:150px;
}

.menu a{
display:block;
padding:12px 25px;
text-decoration:none;
color:#555;
}

.menu a.active{
border:1px solid #2fa4d7;
border-radius:6px;
margin:5px 15px;
color:#2fa4d7;
}


.main{
flex:1;
padding:25px;
}

.toprow{
display:flex;
justify-content:space-between;
align-items:center;
}

.weekly{
background:#f1f1f1;
padding:8px 16px;
border-radius:20px;
}

.semester{
font-weight:600;
}

.datebar{
text-align:center;
font-size:22px;
margin:20px 0;
}

</style>

</head>

<body>

<div class="header">
Saveetha Engineering College (Autonomous)
</div>

<div class="container">

<!-- SIDEBAR -->

<div class="sidebar">

<div class="logo">
<img src="logo.png">
</div>

<div class="menu">
<a href="#">Reports</a>
<a href="#">Progress report</a>
<a href="#">Assessments</a>
<a href="#">Holidays</a>
<a class="active" href="#">Timetable</a>
<a href="#">Teaching content</a>
<a href="#">Leave</a>
<a href="#">Services</a>
</div>

</div>

<!-- MAIN CONTENT -->

<div class="main">

<div class="toprow">
<div class="semester">EVEN | 2025-2026</div>
<div class="weekly">Weekly schedule</div>
</div>

<div class="datebar">
< 26 May 2026 >
</div>

<!-- TIMETABLE TABLE -->

<table class="table table-bordered table-striped">

<thead class="table-primary">

<tr>
<th>Subject</th>
<th>Time</th>
<th>Faculty</th>
<th>Room</th>
<th>Status</th>
</tr>

</thead>

<tbody>

<tr>
<td>Fundamentals of Web Application Development</td>
<td>08:00 AM - 09:00 AM</td>
<td>BERLIN MAGTHALIN R</td>
<td>4454</td>
<td>Attendance recorded</td>
</tr>

<tr>
<td>Fundamentals of Web Application Development</td>
<td>09:00 AM - 10:00 AM</td>
<td>BERLIN MAGTHALIN R</td>
<td>4454</td>
<td>Attendance recorded</td>
</tr>

<tr>
<td>Python Programming</td>
<td>10:00 AM - 11:00 AM</td>
<td>KRISHNAMOORTHY J</td>
<td>2331</td>
<td>-</td>
</tr>

<tr>
<td>Python Programming</td>
<td>11:00 AM - 12:00 PM</td>
<td>KRISHNAMOORTHY J</td>
<td>2331</td>
<td>-</td>
</tr>

<tr>
<td>Web Data Mining</td>
<td>10:00 AM - 11:00 AM</td>
<td>Varalakshmi J</td>
<td>2481</td>
<td>Attendance recorded</td>
</tr>

<tr>
<td>Web Data Mining</td>
<td>11:00 AM - 12:00 PM</td>
<td>Varalakshmi J</td>
<td>2481</td>
<td>Attendance recorded</td>
</tr>

</tbody>

</table>

<!-- FOOTER -->

<footer class="text-center mt-4">
© 2026 Saveetha Engineering College
</footer>

</div>

</div>

</body>
</html>
```

## OUTPUT:
<img width="1918" height="1170" alt="image" src="https://github.com/user-attachments/assets/2b36709f-4b50-4666-9137-3a74294ff372" />


## RESULT:
A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.
