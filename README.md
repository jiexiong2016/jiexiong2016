```python
class Attributes(jiexiong2016):
	
    @staticmethod
    def contact() -> tuple:
        name = "Jiexiong Tang"
        email = "jiexiong@kth.se"
        return name, email

    @staticmethod
    def life() -> tuple:
        langs = ['English', 'Chinese']
        base  = ['Stockholm', 'Sweden']
        return langs, base
	
    @staticmethod
    def skills() -> tuple:
        coding = {
            'daily use':   ['python', 'c++'],
            'if have to': ['c', 'cuda']
        }
        expertise  = ['Computer vision', 'Machine learning', 
                    'Simultaneous localization and mapping', 'Self-supervised learning',
                    'Deep but not that deep learning']		
        return coding, expertise
	
    @staticmethod
    def education() -> tuple:
        highest = ['Phd in Computer Science', 'KTH Royal Institute of Technology']
        return highest
```

<!-- Skills -->
<img src="https://skillicons.dev/icons?i=python,cpp,vscode,pytorch" />

<!-- Stats -->
<img alt="" src="https://github-readme-stats.vercel.app/api?username=jiexiong2016&theme=tokyonight&show_icons=true">
