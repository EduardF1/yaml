#### Resource: https://www.youtube.com/watch?v=1uFVr15xDGg

#### Why ?
- configuration files are written in YAML
- widely used format
- devops tools + apps, ex.: Docker, Kubernetes, Ansible, Prometheus

#### What it is ?
- Serialization language like XML, Json
- Serialization, upon agreeing on a format (XML, JSON, YAML) different applications or tools interact.
- YAML stands for "YAML Ain't Markup Language"
- File extensions: .yaml, .yml
- Increased popularity due to increased human readability and intuitiveness
- YAML is a superset of JSON, any valid JSON file is also a valid YAML file

#### YAML format
- line separation and indentation
- Example:
```
microservices:
     - app:  user-authentication
     port: 9000
     version: 1.0
```