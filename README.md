# Corona Maps

Corona maps is a project to visualize data of the infected patients 

## Views and User interfaces

This app will be used to visualize the data on a map and also provide an admin view to redact some data.

First view will be for the users to check all the places where the infected people have travelled on a map. 

Second view will be for the admin to upload json files and if required remove some sensitive data points. 

## Information Architecture

The database to be used would be SQL
This will be used to store all the data points of the affected patients

The data can enter the database from - 
1. Admin panel
2. Private Kit app

Detailed information architecture is under construction. 
Download http://privatekit.mit.edu/ and export the data to analyse for now.

## Roadmap

1. Starting with Dummy Data create a map to plot points
2. Along with points create paths on the map where the patients might have travelled. 
3. Create filters for each country - https://coronavirus.app/
4. Create an admin panel to upload json files with data points
5. The web app should render the data from the database
6. Create a redaction tool in admin to delete the data points which are sensitive. 
7. Create a post api to upload data directly from the app to the database

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.


## License
Coming Soon
