# DjangoVC

## Table of contents

[Introduction](https://github.com/bhush-n/DjangoVC#introduction)

[API References](https://github.com/bhush-n/DjangoVC#api-reference)

[Features](https://github.com/bhush-n/DjangoVC#features)

[Installation](https://github.com/bhush-n/DjangoVC#installation)

[License](https://github.com/bhush-n/DjangoVC#license)

[Screenshots](https://github.com/bhush-n/DjangoVC#screenshots)

[Support](https://github.com/bhush-n/DjangoVC#support)
# Introduction

I have developed this video conferencing web app using django as an internship task. In this web app I have used Django as a main backend language and HTML, CSS & JS for frontend. I have used Sqlite3 for database. For the video call limit I have used zegocloud API which provides 10,000 free minutes per month.

In this app user can register and further have the accessibility to create new meeting or join the existing meeting. User can also share the screen during conference and also can have a chat with the conference team members.


## API Reference

#### ZegoCloud API

```http
You have to register on ZegoCloud test mode and take your api key.
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

[API KEY](https://console.zegocloud.com/dashboard)
## Features

- User can join the meeting as well as create the meeting.
- Secure video calling.
- Dynamic and user-friendly UI.
- 10,000 free minutes from API.


## Installation

```bash
pip install django-admin

pip install -r requirements.txt

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver
```
    
## License

[MIT](https://choosealicense.com/licenses/mit/)


## Screenshots

![App Screenshot](Will be available soon.)


## Support

For support, email bhushanch45@gmail.com.

