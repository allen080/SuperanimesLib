# Biblioteca desenvolvida para facilitar o download de animes e desenhos do site https://www.superanimes.site

**OBS: biblioteca ainda nao esta finalizada e se encontra na sua versao de testes**

uso:
from superanimes import Superanimes.
s = Superanimes('nome do anime')

Exemplos:

-Download de todos os episodios de um anime.
s.download_all()

-Download de episodios especificos
s.download('primeiro ep que deseja ser baixado','ultimo ep que deseja que seja baixado')
obs: para fazer o download de apenas um episodio, apenas coloque o numero do episodio especifico.

-Saber quantos episodios o anime tem.
episodios = s.num_episodes()
print(episodios)

-Procurar por animes com o nome parecido com o especificado.
s = Superanimes('nome do anime para buscar')
animes = s.search()
print(animes)

-Saber se esse anime se encontra no site do superanimes.
print(s.status)
