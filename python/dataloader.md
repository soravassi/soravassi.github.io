<head>
<style>
html, body { height: 100% }
.button {
  font-family : inherit;
  border: none;
  color: white;
  padding: 8px 16px;
  text-align: center;
  display: inline-block;
  transition-duration: 0.4s;
  cursor: pointer;
}

.button {
  background-color: #f2f2f2; 
  color: black; 
  border: 2px solid black;
}

.button:hover {
  background-color: #666666;
  color: white;
}


.previous {
  background-color: #f2f2f2;
  color: black;
  border: 0.5px solid black;

}

.round {
  border-radius: 50%;
}
</style>
</head>
<section class = "inner-medium">

<h2>Salesforce.com Dataloader</h2>

<a href="https://soravassi.github.io/python.html" class="button previous round">&#8249;</a>

<p>In the world of Salesforce.com administration, a very common tool to use is the "Dataloader". It allows admins to mass insert, update, delete, and extract records from their Salesforce instance. By leveraging Python packages such as simple_salesforce and salesforce_bulk to support the data management operations, as well as Tkinter to build the User Interface, I developed this "Faux Dataloader". Some of its limitations, for now, are only being able to insert/delete/update 10k records per job and not being able to map the column names of an input Excel/Csv file to its equivalents on Salesforce (the column names must match exactly to the fields' API names.</p>

<p><i>By clicking below you can find its Github repository</i></p>

 <a href = "https://github.com/soravassi/FauxSFDCDataloader" target="_blank"><img src="dataloader-banner.png" style="width:100%"></a>
