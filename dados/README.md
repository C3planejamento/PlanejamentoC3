# Pasta de dados — Dashboard CC101 (REGAP)

O dashboard lê **automaticamente** os arquivos `.xlsx` desta pasta ao abrir.
Quem acessar o painel já vê os dados, sem precisar importar nada.

## Arquivos esperados (fechamento atual)

| Arquivo        | Planilha de origem                         |
|----------------|--------------------------------------------|
| `painel.xlsx`  | PAINEL GESTÃO SAMC                          |
| `crono.xlsx`   | Crono Financeiro                           |
| `metas.xlsx`   | Projeção Metas de Faturamento              |

> Os nomes acima são recomendados, mas o painel também identifica cada arquivo
> pelo **conteúdo das abas** — então qualquer `.xlsx` com as abas corretas funciona.

## Como atualizar o mês

1. Substitua os 3 arquivos `.xlsx` nesta pasta pelos do novo fechamento.
2. No **GitHub Desktop**: Commit → **Push origin**.
3. Em ~1 minuto o dashboard publicado reflete os novos dados
   (pode ser preciso atualizar a página com **Ctrl+F5**).
