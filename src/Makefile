all: gotwitter

gotwitter: http_auth.8 twitter.8 main.8
					 8l -o gotweet http_auth.8 twitter.8 main.8

main.8: main.go
	8g main.go

http_auth.8: http_auth.go
	8g http_auth.go

twitter.8: twitter.go
	8g twitter.go

clean:
	rm *.8 gotweet
