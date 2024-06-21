## RoPro - Comments - Get Comments

URL: https://api.ropro.io/getComments.php \
Method: POST \
Auth Required: No

## Query Parameters

`id` - integer - Item ID the comments are for\
`page` - integer - What page of comments you want to fetch

---

_Example Response_

```json
{
  "comments": [
    {
      "username": "Roblox",
      "userid": "1",
      "comment": "these ropro api docs are amazing",
      "date": "2022-10-08 11:40:06.764119"
    },
    {
      "username": "Builderman",
      "userid": "156",
      "comment": "i know right we should 100% donate to the author",
      "date": "2022-10-08 11:41:10.795055"
    }
  ],
  "more": false, 
  "page": 0, 
  "valid": true
}
```
