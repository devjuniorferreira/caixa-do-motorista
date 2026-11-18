# Caixa do Motorista

App web para motoristas de aplicativo acompanharem ganhos, despesas e lucro. Criei o projeto a partir da minha rotina como motorista. O total recebido nas corridas mostra quanto entrou. Para saber quanto sobrou, é preciso descontar combustível, alimentação, manutenção e os outros gastos registrados.

[Abrir o Caixa do Motorista](https://devjuniorferreira.github.io/caixa-do-motorista/)

## Como funciona

- Registre ganhos e despesas por dia e por categoria.
- Consulte o resumo do período. O lucro é a soma dos ganhos menos a soma dos gastos lançados.
- Acompanhe metas e indicadores como lucro por hora, por quilômetro e por litro, conforme os registros disponíveis.
- Use pelo navegador do celular. Em navegadores compatíveis, é possível instalar o app na tela inicial.

## Dados e backup

Os lançamentos ficam no armazenamento local do navegador (`localStorage`). A aplicação não exige conta e não sincroniza os registros entre aparelhos.

Em **Ajustes → Backup dos dados**, use **Copiar backup** e guarde o texto em um local seguro. Para recuperar os dados, cole o texto completo na mesma seção e selecione **Restaurar**. Guarde uma cópia antes de limpar os dados do navegador ou trocar de aparelho.

## Tecnologias

HTML, CSS e JavaScript sem framework. O manifesto e o service worker dão suporte à instalação como app web. A publicação é feita no GitHub Pages.

Desenvolvido com apoio de IA.

[GitHub](https://github.com/devjuniorferreira) · [LinkedIn](https://www.linkedin.com/in/devjuniorferreira)
