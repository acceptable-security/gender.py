#gender.py

A simple library to take first names and return their gender using the genderize.io API.

##Usage

    >>> getGenders(["Brian","Apple","Jessica","Zaeem","NotAName"])
    [(u'male', u'1.00', 483), (u'female', u'0.86', 14), (u'female', u'1.00', 787), (u'male', u'1.00', 1), (u'None', u'0.0', 0.0)]

##Output

Output is a list of results form the website, formated to be (name (string), probability (string), population (int))

##Requirements

Requires requests to function for HTTP requests.