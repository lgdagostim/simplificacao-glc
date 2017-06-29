## Implementação em **JavaScript** para simplificação de uma gramática livre de contexto **(GLC)**.
---
##### Atividades desenvolvidas pelo código:
- [x] Eliminação de produções vazias.  
- [x] Eliminação de produções unitárias.  
- [ ] Eliminação de símbolos inúteis:
---
### Instruções:
> Utilizar letras em maíusculo para **não terminais**;  
> Utilizar letras em minúsculo para **terminais**;  
> Utilize **->** para separar não terminais das produções;  
> Utilize **| (pipe)** para separar as produções;  
> Utilize **Σ** como vazio.  
* Evitar utilizar espaços em branco, não está 100% a eliminação de espaços em branco.
---
### Exemplo de gramática a ser inserida:
```
J->aABcD|aBcA|bDc
A->bAbD|bb|Σ
B->bDaA|bBBa|bDba|ba|b
D->bB|Σ
```
---
> Código escrito por **[LGDAGOSTIM](http://www.lgdagostim.tk "Acesse.")**.  
> [fb.com/b1duu](https://www.facebook.com/b1duu "Perfil no Facebook")
---