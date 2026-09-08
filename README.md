# EDC custom tool list

This list is meant to register tools that are not published in any public registry such as workflowhub, zenodo etc. This will serve as an interm registry. 

## Registry structure

Every tool should have a folder under `tools` with the name of the tool as the folder name and a `codemeta.json` file inside the folder. The `codemeta.json` file should contain the metadata of the tool in JSON format.

## Adding a new tool
> If your tool already has a Github/Gitlab reposity or published in any public registry then this is not the right place to register your tool.


To add a new tool to the registry, follow these steps:
1, fork this repository
2, create a new folder under `tools` with the name of the tool as the folder
3, create a `codemeta.json` file inside the folder with the metadata of the tool in JSON format
4, create a pull request to this repository with the new tool added
5, wait for the pull request to be reviewed and merged

