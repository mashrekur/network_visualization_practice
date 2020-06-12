# # network_visualization_practice

To generate a force directed graph(fdg)

1. Open index_text.html file in a suitable platform e.g. VisualStudio
2. At the bottom end of the code, specify the json file (les_miserables.json) you want to load.
3. Adjust the dimensions and color of the plot using js vars
4. Initiate a local server using python: python3 -m http.server
You should see a message like this: "Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/)"
5. On your preferred browser's address bar GUI paste: http://localhost:8000/index_test.html
6. Visual studio requires constantly reloading your browser tab to include updates. Observable(observablehq.com) is a better way to do d3.

# # Understanding json files
-Nodes: This data is used to create an object and give the node a name. The group represents the color.
-Links: The source is used to identify the index position inside of the nodes list. For example “Napoleon” is in index position 1; same holds true for target. The value is the number of times the connection occurs.