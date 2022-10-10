## Syntax: 

```
awk [flags] [select pattern/find(sort)/commands] [input file]
```

## Examples:

![vnkM0ox](https://user-images.githubusercontent.com/90236635/194926023-7e991ba2-366b-48db-9ea2-9d43dca521ae.png)


## Built-In variables in AWK:

- **NR :**
  - (Number Record)
  - the variable that keeps count of the rows after each line's execution... You can use NR command to number the lines ```awk '{print NR,$0}' file.txt```. Note that awk considers rows as records.

![5OhnYAB](https://user-images.githubusercontent.com/90236635/194927173-bca2b50d-f9c9-41d8-aed1-3b785c2e9078.png)

- **FS: **
  - (Field Separator)
  - the variable to set in case you want to define the field for input stream. The field separation (defaut to space) that we talked above and can be altered to whatever you want while specifying the pattern. FS can be defined to another character(s)(yea, can be plural) at the BEGIN{command}.
 
 ![uw9hWVM](https://user-images.githubusercontent.com/90236635/194929011-8a667cbc-bf4c-4416-a9fb-d8c753ec3b8a.png)


- **RS :**
  - (Record Separator)
  - By default it separate rows with '\n', you can specify something else too.

![dsn9utX](https://user-images.githubusercontent.com/90236635/194929374-5fb61ded-3779-485e-8112-4274e50ab0af.png)


- **OFS :**
  - (Output Field Separator)
  - You must have gathered some idea by the full form, it is to specify a delimeter while outputing... 

![hwIjE8p](https://user-images.githubusercontent.com/90236635/194929854-f34e7ef3-9211-41ba-a917-e99bc0da1084.png)


- **ORS :**
  - (Output Record Separator)
  -  I don't think I really need to specify it's usage...

![5j2f5zy](https://user-images.githubusercontent.com/90236635/194930260-76cef385-2a08-421f-bc01-c78d08da0c5e.png)


## Important Flags:

<img width="817" alt="Screenshot 2022-10-10 235854" src="https://user-images.githubusercontent.com/90236635/194930835-38a19e01-2dcc-41a3-a861-45b6cb7a63fc.png">



