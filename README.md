
### Hi there, I'm Eric 👋

```Python
class Eric:

    def __init__(self):
        self.username = 'Eric54920'
        self.name = 'Eric'
        self.profession = 'Full Stack Developer'
        self.position = 'Hangzhou, China'
        self.email = 'realmaguodong@outlook.com'
        self.blog = 'https://theguodong.com'
        self.hobby = ['Photograph', 'Travel']
        self.code = {
            'backend': ['Python', 'Flask', 'Django', 'FastAPI', 'Go', 'Gin'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3', 'Mongo DB', 'Redis'],
            'devops': ['Docker', 'Linux'],
            'frontend': ['HTML', 'CSS', 'JavaScript', 'Vuejs', 'Bootstrap', 'Tailwind'],
            'tools': ['Git', 'GitHub', 'Nginx']
        }
        self.social = {
            'github': 'https://github.com/Eric54920',
            'instagram': 'https://www.instagram.com/_ericphotograph',
            'x': 'https://x.com/realmaguodong'
        }

    def __str__(self):
        return f'{self.name} | {self.position}'


if __name__ == '__main__':
    me = Eric()
    print(me)
```
