<h2>Sobre mim</h2>

```python
class HenriqueR:
    def __init__(self):
        self.nome = "Henrique de Figueiredo Reinaldi"
        self.linguagens= ["Python","C","C++"] 
        self.idiomas = ["Inglês","Português"]
        self.tipo = "estudante de ciências da computação"
        
    def intro(self):
        resposta = "Chamo-me "

        index_primeiro_espaco = self.nome.find(' ')
        resposta = resposta + self.nome[:index_primeiro_espaco]

        resposta = resposta + f", gosto de resolver problemas e atualmente sou um {self.tipo}. "

        resposta = resposta + f"Sou fluente em {" e ".join(self.idiomas)} "

        resposta = resposta + f"e minha linguagem de programação favorita é {self.linguagens[0]}."
        
        return(resposta)
    
eu = HenriqueR()
print(eu.intro())
```

<div align="center">
<p><a target="_blank" href="https://www.instagram.com/henrique_reinaldi" style="display: inline-block;"><img src="https://img.shields.io/badge/-Instagram-%23044F88?style=for-the-badge&logo=instagram" alt="instagram" /></a><a target="_blank" href="https://discord.com/users/345917375519916034" style="display: inline-block;"><img src="https://img.shields.io/badge/-Discord-%23424549?style=for-the-badge&logo=discord&logoColor=white" alt="discord" /></a></p>
</div>

<h2></h2>
<div align="center"><img alaing=center alt="nao sabia que so podia gif ate 10mb slk" src="https://github.com/user-attachments/assets/0d25b710-07ee-42ab-9fb7-70406f0b1883"/></div>
