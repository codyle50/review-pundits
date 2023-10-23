<img src="https://i.ibb.co/ZXVNVY5/pr-logo-plain-opauq.png" width="7.5%" height="7.5%">

##

## About this repository
This repository holds the directory used to deploy the Pundits Review project on Heroku. Intended as a legacy repository as part of my contribution to the MSc Computational and Data Journalism at Cardiff University, the files inside represent the front and backend of the website as presented in the walkthrough video - 10/09/2020

## Contents

#### <a href="https://github.com/andyclarkemedia/Pundits-Review/tree/master/">TOP LEVEL</a>
Project configuration files alongside 'tasks.py' - used to run scheduled tasks on Heroku

#### <a href="https://github.com/andyclarkemedia/Pundits-Review/tree/master/__mocks__">Mocks</a>
Used to stop Jest incorporating non JS files into testing

#### <a href="https://github.com/andyclarkemedia/Pundits-Review/tree/master/frontend">Frontend</a>
Frontend of site - React/Redux app configured with webpack & babel. Components, functions and resources used within website.

#### <a href="https://github.com/andyclarkemedia/Pundits-Review/tree/master/main">Main</a>
Django models & API configuration - Defines models, views, serializers & url patterns to store and access data

#### <a href="https://github.com/andyclarkemedia/Pundits-Review/tree/master/matchreportscraper">Match Report Scraper</a>
Scrapy Pipeline - used to collect & process incoming data each week. Contains spider, pipelines, prediction model & entity extraction module 

#### <a href="https://github.com/andyclarkemedia/Pundits-Review/tree/master/premierleaguematchreports">Premier League Match Reports</a>
Project Settings - deployment & local use settings for project
