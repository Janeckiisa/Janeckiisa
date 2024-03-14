```js
class SobreMim:

    def __init__(self, nome, area, trabalho, local):
        self.nome = nome
        self.area = area
        self.trabalho = trabalho
        self.local = local

class Skills(SobreMim):

    def __init__(self, nome, area, trabalho, local, linguagens):
        super().__init__(nome, area, trabalho, local)
        self.linguagens = linguagens

meu_nome = "Isabelle"
minha_area = "Desenvolvimento de Sistemas"
meu_trabalho = "Robert Bosch"
meu_pais = "Brazil"
minhas_linguagens = ["Python", "C", "C++", "Java", "SQL", "Web"]

dev1 = Skills(meu_nome, minha_area, meu_trabalho, meu_pais, minhas_linguagens)
```
