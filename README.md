# Uninstall All Library Window && Ubuntu <img src="https://emoji.slack-edge.com/T0172CCPGUW/party-blob/d7253707fa13e9ee.gif" width="30"/>

#### Xem các thư viện đã cài trước đó
```
$ pip list
$ pip3 list
```

### Tạo file --> "requirement.txt"**
- **Cách 1:**
```
$ pip freeze > requirements.txt
$ pip3 freeze > requirements.txt
```
- **Cách 2:**
```
$ pip install pipreqs
$ pipreqs /path/to/project
```

- **Xóa từng thư viện một**
```
$ pip uninstall -r requirements.txt
$ pip3 uninstall -r requirements.txt
```
- **Xóa một lần tất cả thư viện**
```
$ pip uninstall -r requirements.txt -y
$ pip3 uninstall -r requirements.txt -y
```
