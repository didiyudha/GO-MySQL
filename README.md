# GO-MySQL
This is very simple example to learn how GO deal with the template engine in  GO. I used *html/template* package that is already 
built in inside of default package of GO. Connect to database MySQL, grab the data and passing to the template, so that we can display 
the data to the user.

Here's the struct of User

```go
type user struct {
	ID        int64
	Username  string
	FirstName string
	LastName  string
	Password  []byte
}
```
For database driver of MySQL I used this library: *github.com/go-sql-driver/mysql*
