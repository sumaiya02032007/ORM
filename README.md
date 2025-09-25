# Ex02 Django ORM Web Application
## Date: 10.05.2023

## AIM
To develop a Django application to store and retrieve data from a Car Inventory Database using Object Relational Mapping(ORM).

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```
admin.py

from django.contrib import admin
from.model import Car,CarAdmin
admin.site.register(Car,CarAdmin)

models.py

from django.db import models
from django.contrib import admin
class Car(models.Model):
    car_id=models.IntegerField (primary_key=True)
    car_models=models
    car_models.CharField(max_length=20)
    email=models.EmailField()
    dop=models.DateField()
    car_Type=models.CharField(max_length=10)
class CarAdmin(admin.ModelAdmin):
    list_display=['car_id','car_models','email','dop','car_Type'] 
```

## OUTPUT
![alt text](<Screenshot 2025-09-20 132053.png>)


## RESULT
Thus the program for creating car inventory database database using ORM hass been executed successfully
