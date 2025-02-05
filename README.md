## Hi, I'm 영한 a Data Analyst

```python

class Younghan:

    def __init__(self):
        self.username = 'Younghan'
        self.name = 'Lee Younghan'
        self.position = 'Data Analyst'
        self.email = 'dudgks011@gmail.com'
        self.phone = '010-5912-1394'
        self.blog = '[Blog](https://velog.io/@0han/posts)'
        self.portfolio = '[Portfolio](https://buly.kr/8petJAh)'
        self.code = {
            'data_handling': {'Expert': ['Pandas', 'Numpy']},
            'data_visualization': {'Proficient': ['Matplotlib', 'Seaborn', 'Tableau', 'Looker Studio']},
            'machine_learning': {'Proficient': ['Scikit-learn'], 'Familiar': ['TensorFlow', 'Statsmodels']},
            'database_management': {'Proficient': ['SQL'], 'Familiar': ['MongoDB']},
            'document_work': {'Expert': ['한글 / Word', 'Excel'], 'Proficient': ['PowerPoint']},
            'collaboration': {'Expert': ['Discord', 'Notion', 'Slack'], 'Familiar': ['Git', 'GitHub']},
            'python_libraries': ['Pandas', 'Numpy', 'Matplotlib', 'Seaborn', 'Scikit-learn', 'TensorFlow', 'Statsmodels']
        }

    def __str__(self):
        return (f'{self.name} | {self.position}\n'
                f'Email: {self.email}\n'
                f'Phone: {self.phone}\n'
                f'Blog: {self.blog}\n'
                f'Portfolio: {self.portfolio}')


if __name__ == '__main__':
    me = Younghan()
    print(me)


```

