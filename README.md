# Firebase CRUD in Angular Material

###### Before Running this Project
 1. Install npm packages using 'npm install' command.
  
Content discussed : 
 - firebase crud operations
- angular form submission
- render dynamic dropdown
- create popup notification in angular material

## Issues and Fixes
-hireDate not inserted to firebase <br/>
reason: forgot to formate the date before insert/ update operation. <br/>
fix :  <br/>
add DatePipe to app.module.ts providers array <br/>
update in employeeService.ts <br/>
inject the DatePipe to constructor <br/>
constructor(...,private datePipe: DatePipe){} <br/>
update functions : insertEmployee & updateEmployee for hireDate formatting <br/>
hireDate: this.datePipe.transform(employee.hireDate, 'yyyy-MM-dd') <br/>

 
 # Step By Step Explanation
 
 Video Tutorial : https://youtu.be/hfhlzY3U27M
 
 <a href="http://www.youtube.com/watch?feature=player_embedded&v=hfhlzY3U27M
" target="_blank"><img src="http://img.youtube.com/vi/hfhlzY3U27M/0.jpg" 
alt="Video Tutorial for Firebase CRUD in Angular Material" width="500" height="400" border="10" /></a>

# Complete Angular Material Tutorial
1. https://goo.gl/XmR6Li - Form Design.  
2. https://goo.gl/3VQn29 - Firebase CRUD.[this one ]
3. https://goo.gl/5h59y5 - Angular Material Data Table.



# All Video Tutorial Series
| Series        | Video PlayList          |
| ------------- |:-------------:|
| C# Tutorial For Beginners      | https://goo.gl/s1zJxo |
| Asp.Net MVC Tutorials      | https://goo.gl/gvjUJ7      |
| Angular 5 Tutorials | https://goo.gl/jzrPJx      |
| Angular 4 Tutorials | https://goo.gl/Ha71kq      |
| Asp.Net WebForm Tutorials | https://goo.gl/GXC2aJ      |
| C# WinForm Tutorials | https://goo.gl/vHS9Hd      |
| jQuery Datatable in Asp.Net MVC | https://goo.gl/Ezpfnj      |
| Crystal Report Tutorials | https://goo.gl/5Vou7t      |
| Web API Tutorials | https://goo.gl/itVayJ     |
| Common C# Excercises | https://goo.gl/EPZ69B     |
| jQuery Tutorials | https://goo.gl/MxgKHY     |
| SQL Server Tutorials | https://goo.gl/8uP8dd      |
| CG Exercises in C Program | https://goo.gl/qEWJCs      |
