# Api Trekker
Solução desenvolvida para servir como um gerenciamento do fluxo de dados entre Mobile (front) e o banco de dados (SQL).

## Arquitetura da Solução
<img src="cg3_api_trekker.png">

## Matéria - Digital Business
### Vídeo do projeto final
[Sprint 4 - Digital Business](https://youtu.be/0S26ed02sBY)

##  Matéria - Enterprise Application
### Vídeo do projeto final
[Sprint 4 - Enterprise Application](https://youtu.be/0S26ed02sBY)

##  Matéria - Disruptive Architectures: IT, IoT & IA
### Vídeo do projeto final
[Sprint 4 - Disruptive Architectures](https://youtu.be/0S26ed02sBY)

### Documento
[Sprint 4 - Disruptive Architectures](https://github.com/cecilianeves22/digital-sprint4-trekker/blob/master/Trekker.pdf%20(1).pdf)

## Deploy
### Pré-requisitos:
- Ter instalado o Gradle (Para buildar projeto)
- Editar o arquivo `application.properties` em `src\main\resources\application.properties` com as credenciais do banco

### Passo a passo
Clone o repositório:
```bash
git clone https://github.com/cecilianeves22/digital-sprint3-trekker.git
```
Acesse a pasta:
```bash
cd digital-sprint3-trekker
```
Após editar as credenciais do arquivo `application.properties` faça o build:
```bash
gradle build
```
Será gerado um `Sprint-0.0.1-SNAPSHOT.jar` em `/build/libs/.`. Realize o deploy desse arquivo para o Web App do Azure através do VScode (ou outro programa).
### JSON utilizado em vídeo:
- Usuário: `/usuario` - Exemplo:
```
{
    "nm_usuario": "Carla Fernandes",
    "ds_email": "cacafernan@gmail.com",
    "ds_senha": "EN&Kpk3f"
}
```
- Destino: `/destino` - Exemplo:
```
{
    "cd_usuario": {
        "cd_usuario": 5
    },
    "nm_destino": "Paris",
    "qt_dias": 10,
    "nm_partida": "RJ"
}
```
### Vídeo de demonstração para a matéria de `DevOps and Cloud Computing`
[![Demo](https://img.youtube.com/vi/oMwFXzfBf9s/maxresdefault.jpg)](https://www.youtube.com/watch?v=oMwFXzfBf9s)
