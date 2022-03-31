# Principal-Component-Analysis-in-SAS-Enterprise-Miner

Following are the steps to create the example
1. Use a Data Source wizard to create a raw data source named HMEQ from the SAS sample table SAMPSIO.HMEQ.
2. Use the Metadata Advisor option to set the role and level values for each variable.
3. Drag the SAMPSIO.HMEQ data source from the Data Sources list to the Diagram Workspace
4. Drag and drop a Principal Components node from thr Modift tool folder to the Diagram Workspace.
5. Connect the SAMPSIO.HMEQ Input Data node to the Principal Components node.
6. Click the Principal COmponents node in the Diagram WOrkspace to select it, then in the node Properties Panel, change the value of the Cuulative property in the Eigenvalue Cutoff group to 0.97, and set the Maximum Number property in the Max Number Cutoff group to 7.
7. RUn the Principal Components node and view the results.
