# python-api-ai

Esta API prevê as letras de seis bandas: Oficina G3, POD, Ed Sheeran, Bruno Mars, Xitãozinho e Chororó e Tião Carreiro e Pardinho.

A API espera a seguinte requisição:
`https://apilyricsia.herokuapp.com/api/v1/classification/band/lyrics` [POST]

No corpo da requisição é necessário passar o seguinte objeto:

`
{
  "lyrics": "A letra da música"
}
`

E a API devolve a seguinte resposta:

`
{
  "band": "a banda com maior probabilidade",
  "proba": "0.9"//sendo esta a probabilidade de ser a banda da resposta.
}
`
