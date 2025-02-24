# Criando um Pacote de Processamento de Imagens com Python

![GitHub](https://img.shields.io/github/license/Paucinha/api-ecommerce-dio?style=flat-square)

Neste projeto você aprenderá a criar o seu primeiro pacote de processamento de imagens em Python e disponibilizá-lo no repositório Pypi. Assim você poderá reutilizá-lo facilmente e compartilhá-lo com outras pessoas. A especialista também vai mostrar um exemplo de pacote para processamento de imagens.

**Python | Git**

**Back-End | Avançado**

## Requisitos Básicos

* Python instalado

* Ter um projeto a ser empacotado

* Git (recomendado)

## Criar o projeto e gerar as distribuições

Como criar o seu programa de uma forma mental, utilizando o computador mais potente do mundo, o nosso cérebro. se você ainda não sabe programar, vai criar o seu primeiro programa hoje, mesmo sem saber sequer uma linha de código. e mesmo que você já saiba programar, você vai conseguir fazer um reforço na sua lógica. sabe quando acontece aqueles errinhos e você fica engasgado em algum ponto? essa aula vai ser muito importante pra você também.

## Passos para criar o projeto

1. Fork do template

2. Adição do conteúdo dos módulos do projeto

3. Edição do  arquivo setup.py

4. Edição do requirements.txt

5. Edição do README.md

## Passos para gerar as distribuições

1. Acessar a raiz do projeto
2. Comandos de instalação
3. Comando para criar a distribuição

## Comandos de instalação

```python
python -m pip install --upgrade pip
python -m pip install --user twine
python -m pip install --user setuptools
```

## Comandos para criar distribuições

```python
python setup.py sdist bdist_wheel
```

## Publicando o pacote

Como criar o seu programa de uma forma mental, utilizando o computador mais potente do mundo, o nosso cérebro. se vc ainda não sabe programar, vai criar o seu primeiro programa hoje, mesmo sem saber sequer uma linha de código. e mesmo que vc já saiba programar, você vai conseguir fazer um reforço na sua lógica. sabe quando acontece aqueles errinhos e você fica engasgado em algum ponto? Essa aula vai ser muito importante para você também.


## Passos para subir o pacote

1. Criar conta no Test Pypi
2. Publicar no Test Pypi
3. Instalar pacote usando Test Pypi
4. Testar pacote
5. Criar conta no Pypi
6. Publicar no Pypi
7. Instalar pacote usando Pypi

## Criando contas no Pypi

https://pypi.org/account/register/
https://test.pypi.org/account/register/

## Comando para publicar no Test Pypi

```python
python -m twine upload --repository-url https://test.pypi.org/legacy/ dist/*
```

## Comando para instalar o pacote de teste 

```python
pip install –-index-url https://test.pypi.org/simple/ image-processing
```

## Comando para publicar no Pypi

```python
python -m twine upload --repository-url https://upload.pypi.org/legacy/ dist/*
```

## Comando para instalar o pacote

```python
python -m pip install package_name
```

# package_name

Description. 
The package package_name is used to:
	Processing:
		- Histrogram matching
		- Structural dimilarity
		- Resize image
	Utils:
		- Read image
		- Save image
		- Plot image
		- Plot result
		- Plot histogram

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install package_name

```bash
pip install package_name
```

## Usage

```python
from package_name.module1_name import file1_name
file1_name.my_function()
```




## Links Importantes

* [Documentação do setuptools](https://setuptools.readthedocs.io/en/latest/setuptools.html)
* [Testes automatizados](https://docs.pytest.org/en/latest/goodpractices.html)
* [Uso do Tox](https://tox.readthedocs.io/en/latest/)
* [package-template](https://github.com/tiemi/package-template)





![text](https://assets.dio.me/IwGGaOEYVw9pPUMVGEaqp7eKn1gV22wDOHmmAmI0zDY/f:webp/h:221/q:80/L3RyYWNrcy9jb3Zlci83OWZiNzhkZC0xNTQ3LTQ0N2YtYTNkOC04ZGQwMWU1YWMzNTEucG5n)

##

Projeto desenvolvido durante o [**Bootcamp Suzano - Python Developer**](https://www.dio.me/bootcamp/suzano-python-developer), fornecido pela [**DIO**](https://www.dio.me/)

##

- [By Páucinha](https://github.com/Paucinha)

