# djangow
Smooth web development with Django

Django is WEB development framework for Python
Main principal of it is The MVT(Model-View-Template) like MVC(Model View Controller)

General design steps of a Django-site:

    1. First step of backend is URL design: We do it so by adding paths to urls.py
    2. Then mapping each route to a view.
    3. Views designed as simple functions
    4. Views should return an appropriate HTTP response to corresponding URL request.
    5. URL->View->Model->Template->HTTP Response