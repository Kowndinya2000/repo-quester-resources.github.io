# Steps to run the tool RepoQuester
> 1. Install python libraries
````
pip -r requirements.txt
````
> 2. Download cloc
````
https://github.com/AlDanial/cloc/tree/1.88#install-via-package-manager
````
> 3. Download Ack
```
https://beyondgrep.com/install/
```
> 4. Open the file repo_urls 
````
Add username/repositoryname in newlines. 
A sample of 265 repository urls are present already in the file.
````
> 5. Open the file repo_languages 
````
Add repository's programming language in newlines. 
A sample of 265 repository languages are present already in the file.
````
> 6. Open the file repo_ids 
````
A sample of 265 repository ids are present already in the file.
To generate ids automatically. run the command: ## python3 generate_ids.py
````
> 7. Open the file tokens.py 
````
Alteast provide one Github Personal Access Token. 
Format to provide is already presented in the file.
````

> 8. Initialize the database
````
chmod +x *sh
./initialize.sh
````
> 9. Run the script to analyze the repositories
````
./run.sh
````
> 10. Check the results in the database file ```repo_quester.db```


