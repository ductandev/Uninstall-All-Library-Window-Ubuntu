# Uninstall All Library Window && Ubuntu <img src="https://emoji.slack-edge.com/T0172CCPGUW/party-blob/d7253707fa13e9ee.gif" width="30"/>

#### Xem các thư viện đã cài trước đó
```
$ pip list
$ pip3 list
```

- **Tạo file --> "requirement.txt"**
```
$ pip freeze > requirements.txt
$ pip3 freeze > requirements.txt
```
- **Xóa từng cái một**
```
$ pip uninstall -r requirements.txt
$ pip3 uninstall -r requirements.txt
```
- **Xóa một lần tất cả**
```
$ pip uninstall -r requirements.txt -y
$ pip3 uninstall -r requirements.txt -y
```
