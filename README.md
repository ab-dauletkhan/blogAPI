# Blog API

Данный API делает простые CRUD операции на моделях Post, Comment. Все операции для создания, изменения и удаления требуют авторизацию через токен.

Для того, чтобы создать токен необходимо отправить POST request на:
http://localhost:8000/api/token/
и данные 
```json
{
	"username": "<your_username>",
	"password": "<your_password>"
}
```
