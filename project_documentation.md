# Project Structure: myproject

```
myproject/
├── Dockerfile
├── docker-compose.yml
├── main.py
└── version
```

# Files Content

## Dockerfile

```text
FROM python:3.10
WORKDIR /app
COPY . .
CMD ["python", "main.py"]

```

---


## docker-compose.yml

```yaml
version: '3'
services:
  app:
    build: .
    container_name: devops_app

```

---


## main.py

```python
print('Hello, DevOps!')

```

---


## version

```text
0.1.1

```

---

