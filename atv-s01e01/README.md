## Conceitos e características de sistemas distribuídos

---

### Definição

 - Um sistema distribuído é composto por vários computadores que interagem e se mostram como um sistema único e coerente ao usuário a fim de se prestar um serviço.



### Objetivos

 -	Compartilhamento de recursos: hardware, software e/ou dados compartilhados entre os módulos do sistema promovendo colaboração e economia.
 -	Transparência da distribuição: garante a apresentação ao usuário como um único sistema, podendo ser aplicado em diversos aspectos dentro do sistema.
 Para tanto, utiliza-se de Middleware que conecta os módulos do sistema em uma única camada, sendo essa a apresentada ao usuário.
 -	 Abertura: O sistema deve ser regido por uma linguagem de definição de interface (IDL) para garantir um padrão de operação desse sistema distribuído.
 -	Interoperabilidade: capacidade de interação entre aplicações e componentes distintos através de um padrão 
 -	Portabilidade: capacidade de execução de uma aplicação em diversos sistemas sem modificação.
 -	Extensibilidade: capacidade de se agregar ou substituir componentes do sistema sem afetar os demais.
 Garante que o sistema possua uma facilidade maior de manutenção e segurança, já que cada nó é independente.



### Dificuldades

 -	Ao se escalar um serviço é fácil cair em um ponto de gargalo que são pontos únicos de falhas.
 -	Nenhum nó do sistema possui informação completa sobre o sistema e sendo assim suas ações são baseadas em informações locais.
 -	Não se pode garantir que os componentes do sistema estejam sincronizados para o compartilhamento de recursos.
 -	Redes WAN são tipicamente mais lentas, não são confiáveis e a comunicação se dá ponto a ponto do sistema.


## Técnicas de Escalabilidade

 -	A fim de se tornar o sistema expandido mais confiável, utiliza-se de técnicas para uma escalabilidade segura e confiável.
---

#### Integrantes

Rodrigo Cardoso | Francisco Peres
--------------- | ----------------
<img width="150" height="150" src="assets/rodrigo.jpg"> | <img width="150" height="150" src="assets/francisco.jpg">
