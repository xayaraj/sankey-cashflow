This project takes in a CSV of transactions from [Intuit's Mint, Expenses Tracking App](https://mint.intuit.com) and summarizes cash flow into a Sankey visual, i.e.:

- exports a txt that can be used to generate a Sankey diagram at [SankeyMatic](https://sankeymatic.com/build)
- displays a sankey plot using python plotly (not as beautiful as SankeyMatic's imo)

Example of Sankey Diagram
https://i.redd.it/4ke8mvs7hb9a1.png![image](https://user-images.githubusercontent.com/24400570/210920691-1e30fe2b-d2a9-4eeb-a23c-6fcefb018b04.png)
src: Random Reddit Post (https://i.redd.it/4ke8mvs7hb9a1.png)

**Note**: Remember to update [`mint-categories.yaml`](./mint-categories.yaml) with any custom categories you create in Mint
