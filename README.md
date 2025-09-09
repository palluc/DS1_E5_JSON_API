<!---
Decision Science 1 Class - Exercise 5
# DS1_E5_JSON_API
--->
## Working with JSON Format and Introduction to API

#### Objective
The purpose of this program is to use a web URL API to conbsume their data and retrieve data in JSON format. The URl to extract data from is <a href="www.pokeapi.co" target="_blank">Pokemon website</a>.

The steps followed are:
- Extract 20 pokémon characters by calling the pokemon endpoint https://pokeapi.co/api/v2/pokemon
- For each Pokémon character obtain its height and weight. by calling: https://pokeapi.co/api/v2/pokemon/{id} and store it in a tuple as (name, height, weight)
- Load the list to dataframe (DF)

#### Tools Used
Required tools to run the program are :</br>
\- Jupyter Notebook (It is recommended to install full Python distribution with Anaconda Python distribtion) </br>

#### Program walk-through

- Launch the Jupyter Notebook: <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/a1d2ac89-028b-4dc0-9ea4-5fbbc2f5039b" width="80%" height="50%" alt="Launch the Jupyter Notebook" />
</td></tr></table>
</p>
</br>

- Read in URL with BeautifulSoup: <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="" width="80%" height="50%" alt="collects 3 sets of data from the console" />
</td></tr></table>
</p>
</br>

- Extract the tags containing information needed: <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/bc432bef-78d2-4da8-ba57-0bc80bc58779" width="80%" height="50%" alt="collects 3 sets of data from the console"/>
</td></tr>  
<tr><td>
<img src="https://github.com/user-attachments/assets/ddd8dafe-1edd-4ef1-9fdc-5e38d8ce7194" width="80%" height="50%" alt="collects 3 sets of data from the console"/>
</td></tr></table>
</p>
</br>

- Print the information in the tuple datatype: <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/0f389fa6-2362-42a1-8c81-618124b8b598" width="80%" height="50%" alt="Print tuple" />
</td></tr></table>
</p>
</br>


- Save the data to a CSV file and load it into DF: <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/c7f27341-7e86-4f91-857e-a2f9fd020b2f" height="80%" width="50%" alt="Save to CSV file" style="border: 2px solid black;"/>
</td></tr></table>
</p>
</br>


- Write DF to SQLite database: <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/2345d7a1-8cd5-4539-80e8-45e5ca15a323"  height="80%" width="50%" alt="Output FIles" style="border: 2px solid black;"/>
</td></tr></table>
</p>
</br>

- Read in data table and perform summaries on book price by categories:
<p style="border: 2px solid #000000; padding: 1px;">
<table>
<tr><td>
<img src="https://github.com/user-attachments/assets/6b330d62-9544-4993-89f2-9723b5e42bbd" height="80%" width="70%" alt="Summaries on book price" style="border: 2px solid black;"/></br>
</td></tr>
</table>
</p>
</br>

- Print summaries:
<p style="border: 2px solid #000000; padding: 1px;">
<table>
<tr><td> 
<img src="https://github.com/user-attachments/assets/23f34ae5-ac9a-4252-b1fe-04c96f7024fd" height="80%" width="70%" alt="Summaries on book price" style="border: 2px solid black;"/></br>
</td></tr>
</table>
</p>


