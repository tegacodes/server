Uses python template language Jinja: https://jinja.palletsprojects.com/en/2.11.x/intro/#basic-api-usage
See requirements.txt for python install requirements

> create_html.py takes the data being pulled from the solar server and takes the index.html in the template folder and rewrites it to the output folder with the data inserted into it. 

> try this with the apache server we have to serve the files from the output folder

> we then run the create_html.py regularly with a cron job to get updated data. 
