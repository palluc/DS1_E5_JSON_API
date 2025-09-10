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
<img src="https://github.com/user-attachments/assets/0898a37d-9d86-44b4-aa15-8d237175fc76" width="80%" height="50%" alt="Launch the Jupyter Notebook" />
</td></tr></table>
</p>
</br>

- Extract 20 pokémon characters using the pokemon endpoint https://pokeapi.co/api/v2/pokemon: </br>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/adad8478-709b-431e-b637-1d933fac8a6b" width="80%" height="50%" alt="Call API" />
<img src="https://github.com/user-attachments/assets/139eae56-a06d-4631-b924-3cdc57fc2c2c" width="80%" height="50%" alt="Extract pokemon characters" />
</td></tr></table>
</p>
</br>

- View extracted data: <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/b87c0d6f-fbd3-4cd6-907a-b2af7e77bedc" width="80%" height="50%" alt="View pokemon data"/>
</td></tr>  
</table>
</p>
</br>

- For each Pokemon retrieve height and weight data and then view the data: <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/a6472583-cc0c-4b10-924c-68064e09166b" width="80%" height="50%" alt="Extract height and weight"/>
</td></tr>
<tr><td>
<img src="https://github.com/user-attachments/assets/2f3c871b-15fd-4fb1-8dda-7ba97b7fe19c" width="80%" height="50%" alt="View pokemon data in a tuple datatype"/>
</td></tr></table>
</p>
</br>

- Load into a dataframe (DF): <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/607284a9-70dd-4b1f-bbfb-384a96020e10" height="80%" width="50%" alt="Load to DF" style="border: 2px solid black;"/>
</td></tr></table>
</p>
</br>

- Print DF summary:
<p style="border: 2px solid #000000; padding: 1px;">
<table>
<tr><td> 
<img src="https://github.com/user-attachments/assets/cb570bf6-6b78-42bb-a2de-ec45aa2505de" height="80%" width="70%" alt="DF count" style="border: 2px solid black;"/></br>
</td></tr>
</table>
</p>
