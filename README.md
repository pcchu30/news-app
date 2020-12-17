# Django Newspaper app
A newspaper website built using `django` framework implements CRUD(Create-Read-Update-Delete) functionality. The frontend is made using `html` and `bootstrap`. We use `PostgreSQL` as the production database on Heroku. You can add articles which can be viewed by login users . Just make an account and you are good to go.
## Heroku Deployment

### 本新聞網站連結  
https://pcchu30-news.herokuapp.com/

可以使用以下測試帳號登錄：    
username: testuser  
password: huJ12&ko

log in 之後可以閱讀新聞，也可以按左上角的 +New 新增新聞

### 後台管理連結    
可以使用上面的帳號登錄我們客製化的後台管理網頁，該帳號有部份後台權限。  
https://pcchu30-news.herokuapp.com/admin/

## 主要功能
* **Custom User Model**
* **User Authentication**  
  The ability to sign up, log in, and log out users.
* Bootstrap for styling
* Password Reset and Change via Email  
  Users will be able to change their current password or, if they’ve forgotten it, to reset it via email. We use email service `SendGrid` to send emails to users automatically.
* Newspaper app  
  We have an articles page where journalists can post articles, set up permissions so only the author of an article can edit or delete it, and finally add
the ability for other users to write comments on each article.
* Unit Test
