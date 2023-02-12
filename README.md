# MY FAKE API (MOCKEND)
Mockend Fake REST API 

# Setup



https://mockend.com/post-install


curl https://mockend.com/org/repo/users


curl https://mockend.com/programmingkitchen/myfakeapi/users

curl https://mockend.com/programmingkitchen/myfakeapi/users \
  -X POST \
  -H "Content-Type: application/json" \
  --data '{"name": "alice"}'



rgran@HPPAVILION-1 MINGW64 ~/Dropbox/UDACITY-PROJECTS/UDACITY-AZURE-DEVOPS
$ curl https://mockend.com/programmingkitchen/myfakeapi/users \
>   -X POST \
>   -H "Content-Type: application/json" \
>   --data '{"name": "alice"}'
{
        "id": 1204620761
}


