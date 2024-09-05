## Response Status Validation.md

```
curl -o /dev/null -s -w '%{http_code}\n' 'https://api.congress.gov/v3/member?api_key=YOUR_API_KEY&offset=0&limit=10&format=json&currentMember=true'
```

Result: 200

**Codes:**
```
1xx informational response – the request was received, continuing process
2xx successful – the request was successfully received, understood, and accepted
3xx redirection – further action needs to be taken in order to complete the request
4xx client error – the request contains bad syntax or cannot be fulfilled
5xx server error – the server failed to fulfil an apparently valid request
```
