## display: block vs display: inline
— Como as caixas se comportam em relagäo äs outras
— Comportamento externo das caixas

|   **block**                       |  **inline**                    |
|-----------------------------------|--------------------------------|
| Ocupa toda a linha, colocando o   | Elemento ao lado do outro      |
| próximo elemento abaixo desse     |                                |
|-----------------------------------|--------------------------------|
| Width e height são respeitados    | Width e height não funcionam   |
|-----------------------------------|--------------------------------|
| padding, margin, border irão      | Somente valores horizontais de |
| funcionar normalmente.            | margin, padding e border       |
|-----------------------------------|--------------------------------|


exemplos
block: `<p> <div> <section>`, todos os headings `<h1><h2>...`
inline: `<a> <strong> <span> <em>`