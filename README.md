# SAPHTTP
Code snippet for viewing incomming call to sap ICM
1. Place code class in the service tree where the application is located (SICF)
2. add zhandler class in handler list tab
3. set break points in zhandler class, 
4. execute calling aplication and watch data.
4.a sett attaced document for examples and code snippets to get header/body and to get other incomming data

-When debuggin/trouble shooting; you have to find where in the service tree to place you zhandler. 
-The closer to the expected called application is the direct way, but you have to place the zhandler calls higher or lower.\
-Can be used to observe incomming calls
--Case scenerio was to foward or redirect calls to specific bsp using url parameters
(Enjoy :)

