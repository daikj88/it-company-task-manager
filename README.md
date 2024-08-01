# IT-Company-Task-Manager

## Check this out!

[Task Manager project deployed to Render](https://it-company-task-manager-1qnh.onrender.com)

You can use the following user to log in:

```
login: user1
password: user09876
```

## Installation

Run the following code in terminal:

```shell
git clone https://github.com/daikj88/it-company-task-manager.git
cd it-company-task-manager
python -m venv venv
source venv/bin/activate (for MacOS)
venv\Scripts\activate (for Windows)
pip install -r requirements.txt
python manage.py runserver 
```

### For testing with data

- Use this command to load prepared data from the fixture:

`python manage.py loaddata task_manager_db.json`

- After loading data from the fixture you can use the following superuser:

```
login: admin.user
password: 1qazcde3
```

### DB structure:
![image](images/db_structure.jpg)
### Home page:
![image](images/home_page.png)
### Task list:
![image](images/task_list.png)
### Task type:
![image](images/task_type.png)
### Positions:
![image](images/positions.png)
### Workers:
![image](images/workers.png)
### Worker detail:
![image](images/worker.png)
### Login page:
![image](images/login_page.png)
