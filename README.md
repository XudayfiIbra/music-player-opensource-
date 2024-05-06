# Open-Source-Music-Player

Hi All, Welcome to this open source project, <br>This project is part of bringing or testing your skills to real world project. <br>I have prepared this project to make you capable for your next job.

### Checkout before start working on this project, this should give you idea what this project wnated to achive click this button.
[![youtube](https://img.shields.io/badge/youtube-0A66C2?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/UhgFfxcWBU4)

## Setup

## Setp 1. Clone the repo 
```sh
git clone https://github.com/yeole-rohan/Open-Source-Music-Player.git
```
## Step 2. In Root folder create Virtual
  #### for Macos/Linux
  ```sh
python3 -m venv MusicEnv
  ```
  ####  for Windows
  ```sh
python -m venv MusicEnv
  ```
## Step 3. Activate
  ####  for Macos/Linux
  ```sh
source MusicEnv/bin/activate
  ```
  ####  for Windows
  ```
MusicEnv\Scripts\Activate
  ```
## Step 4. installing packages
  #### 1: Generate requirement.txt
  ```sh
pip freeze > requirement.txt
  ```
  #### 2: install requirement.txt
  ```sh
pip install -r requirement.txt
  ```

## Step 5. make migrations to the tables
 #### for Macos/Linux
```sh
python3 manage.py makemigrations 
```
 #### for Windows
```sh
python manage.py makemigrations 
```

## Step 6. Migrate the tables
 #### for Macos/Linux
```sh
python3 manage.py migrate 
```
 #### for Windows
```sh
python manage.py migrate 
```
## Step 7. Run python manage.py createsuperuser
 #### for Macos/Linux
```sh
python3 manage.py createsuperuser 
```
 #### for Windows
```sh
python manage.py createsuperuser 
```


## That's it. your ready for to work on issue.

## 🔗 Links
**full preview here** : https://ravipython.pythonanywhere.com/






