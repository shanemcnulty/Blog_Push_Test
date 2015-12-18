{\rtf1\ansi\ansicpg1252\cocoartf1404\cocoasubrtf130
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue255;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\fs22 \cf2 =====\
Blog\
=====\
Blog is a reusable blog app for Django\
Detailed documentation is in the "docs" directory.\
Quick start\
-----------\
1. Add "polls" to your INSTALLED_APPS setting like this::\
INSTALLED_APPS = (\
...\
'reusable_blog',\
)\
2. Include the polls URLconf in your project urls.py like this::\
url(r'^blogs/', include('reusable_blog.urls')),\
3. Run `python manage.py migrate` to create the polls models.\
4. Add the blogs css::\
<link rel="stylesheet" href="\{% static "css/blog.css" %\}">\
5. Visit http://127.0.0.1:8000/blogs/ to view the blogs you create.}