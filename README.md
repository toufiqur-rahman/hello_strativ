First Phase:
1) run command: pip install -r requirements.txt
2) run command: python manage.py migrate
3) run command: python manage.py getData

Second Phase: 
1) run command: python manage.py runserver
2) click on the URL
3) List of all countries: in your browser, 'your URL/api/countries/'
4) Details of an specific country: 'your URL/api/countries/Id/' for example 'http://127.0.0.1:8000/api/countries/3/'
5) Create a new country:  'your URL/api/countries/create/'
6) Update an existing country:  'your URL/api/countries/update/Id' for example 'http://127.0.0.1:8000/api/countries/update/1'
7) Countries of same language: 'your URL/api/countries/same-language/?language=language_name' for example 'http://127.0.0.1:8000/api/countries/same-language/?language=english'
8) Searching country by name: 'your URL/api/countries/search-country/?name=country_name' for example 'http://127.0.0.1:8000/api/countries/search-country/?name=Cayman Islands'
N.B: for no. 7 & 8 you can search by partial language name and partial country name

Third Phase:
1) View the list of country in table: your URL/api/templates/countries/

